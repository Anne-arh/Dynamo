The script "Color change in view" overrides the color of an element (floor, roof, etc) in a Revit view. 
It is similar to the Revit command: right-click on element/ Override Graphics in View.

    How to use it with Dynamo Player: 
      Open Revit model/ Manage/ Dynamo Player/
      Required inputs: color RGB/ select a Revit element

    How to use and change nodes:
      In Revit: Open Revit model/ Manage/ Dynamo/ 
      In Dynamo: Open dyn file/ click on Select/ click on an element in Revit/ return to Dynamo and run
      Change the RGB color as needed/ Run
      Close the dyn file. The element in Revit is colored. 


The script "Delete Rooms" helps deleting the rooms in Revit. 
It cab be also used to clean the model from reference lines, room tags or other unwanted categories that cannot be purged in Revit.

    How to use it with Dynamo Player: 
        Open Revit model/ Manage/ Dynamo Player/Run (there is no input requires)

    How to use and change nodes:
        In Revit: Open Revit model/ Manage/ Dynamo/ 
        In Dynamo: Open dyn file/ change the category if needed (for instance, to Room Tags, so that the script will delete the room tags).
