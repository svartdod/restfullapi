<h1> Nodejs & Express Restful API  Using Mysql</h1>

Input ana Output are on JSON format  . 

API Link : 
https://efs.atechosting.com/customer

GET all data : Using request GET in API Link 
Input : None  / Output : All data in database 
Exemple : 
Input : none / Output [{"Id":2,"Nom":"HARROUlZ","Prenom":"MOUAD","Phone":"0660845443","Created_on":"2020-02-29T16:31:20.000Z","Updated_on":"2020-02-29T16:31:20.000Z"}]

GET one row  : 
Input ID of customer is json body like {"id":2}  / Output :[{"Id":2,"Nom":"HARROUlZ","Prenom":"MOUAD","Phone":"0660845443","Created_on":"2020-02-29T16:31:20.000Z","Updated_on":"2020-02-29T16:31:20.000Z"}]

Add data - Request Post in API Link : 
Input json : {"Nom" :"Nom_variable" , "Prenom":"Prenom_variable" , "Phone" : "Phone_Variable " } 
Output : Record has been added!

Delete data  Request Delete in API Link : 
Input : { "id"="id_variable "}  
Output :Record has been deleted!  

 Update data - Request Patch in API Link : 
 Input ={"Nom" : "Nom_modified","Prenom":"Prenom_modified","Phone":"Phone_modified","id":ID_OF ELEMENT THAT WE WANT TO CHANGE}
 
 
 
