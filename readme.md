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
