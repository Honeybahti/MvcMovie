Lab-4
Student Name-
Student-ID-
2024-02-08

An ASP.NET Core MVC application requires several crucial actions in order to add a new field.
First, the new field must be added to the model that represents the data object, making sure that it matches
the data structure of the application. Database migration scripts are then written to ensure consistency between 
the application code and the database by synchronizing the database schema with the new model. The controller is
modified to manage the data flow for the additional field, including retrieval, manipulation, and validation as needed,
after the data layer has been altered. It could also be necessary to make changes to views related to the updated model in
order to integrate the new field, like changing form elements or display templates. Thorough testing is essential to verify 
the application's integrity and functionality.

There are a few important things to take into account when integrating validation into an ASP.NET Core MVC application. Validation rules
must first be established for the fields in the model classes themselves that need to be validated. 
This usually entails applying unique validation logic inside the model or using data annotations. After the validation rules are set, 
the MVC framework automatically applies them throughout the model binding and data validation stages. This helps to guarantee data 
integrity and stops erroneous data from being sent to the server.

Moreover, adjustments can be required to the controller activities that handle form submission processing. Here, validation logic is 
used before executing any business logic or database activities to ensure that the incoming data complies with the established rules. 
On the other side, the removal of a resource from the system is managed using the Delete method. Before deleting a resource from the data 
store, it usually asks the user for confirmation that the deletion was done on purpose. Enforcing data integrity restrictions and making
sure related data, including dependent records or relationships, are properly handled to avoid orphaned data are the responsibilities of 
this approach.
