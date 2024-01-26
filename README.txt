This is what had to be done

''Create a custom build form – the user can add or remove fields at will. 
(The fields to be added or deleted have to be of just 2 types – text & select)
When the user saves the data from the form, all the data has to be displayed in a table.
 The table will have at the header the name of each field, for example First name, and in 
the first row the answers of the form submitted, for example Dimitris.''


These two files are different versions of the demo task for Founderhood

The DemoTask#1 lets the user create his own form and then once he submits
the data in the fields, they get saved in a table, the next submit overwrites the data
of the first submit. So, everytime there are only the data of one person on the table.

The DemoTask#2 is an improved version of the previous one. The improvement is that 
it can save data from more than one submits. The table works as a temporary database as
the session is still on. 
