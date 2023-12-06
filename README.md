![Icecream Shop API](icecream-shop-api.png)

# Icecream Shop API

Code for an Icecream Shop's REST API, containing some example vulnerabilities.

#1 found sql injection vulnerbiltiy 

There is sql query which is

"SELECT * FROM Customers WHERE Email='{email}'"

it is creating vulnerbility in this application attacker can do sql injection method +OR+1=1-- to get all records from customer table which is vunernability in this api code that needs to be fixed

#2 found another vulnerbility in version control at github where developer commit the changes and left authorisation or configuration key in update commit


