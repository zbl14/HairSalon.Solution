# Eau Claire's Salon Management 

#### By _**Zhibin Liang**_  

#### A client-sytlist managment portal for Eau Claire's Salon

---
## Technologies Used

* _C#_
* _HTML/CSS_
* _ASP.Net Core MVC_
* _Entity Framework_
* _MySQL_

---
## Description

The Eau Clair's Salon Managemnt is an online managment tool for the owner and employees. They can update stylist and client info as well as tracking relationship between a stylist and his/her clients.

---
## Setup/Installation Requirements

<details>
<summary><strong>To Setup</strong></summary>

* Requires _MySQL_ for the database
* Install _Microsoft .NET SDK_
* Clone the repo
    ```
    $ git clone
    ```
</details>

<details>
<summary><strong>To Run</strong></summary>

* Navigate to  
   <pre>HairSalon.Solution
   ├── <strong>HairSalon</strong>
   └── HairSalon.Tests</pre>
* Create ```appsettings.json``` in the directory of _HairSalon_, and add following to the file with your MySQL username and password
    ```
    {
    "ConnectionStrings": {
        "DefaultConnection": "Server=localhost;Port=3306;database=zhibin_liang;uid=[username];pwd=[password];"
    }
    }
    ```
* Import the database in the root of HairSalon.Solution
* Run following commands
    ```
    $ dotnet restore
    ```
    ```
    $ dotnet build
    ```
    ```
    $ dotnet run
    ```
</details>

<details>
<summary><strong>For Testing</strong></summary>

* Navigate to  
    <pre>HairSalon.Solution
    ├── HairSalon
    └── <strong>HairSalon.Tests</strong></pre>
* Run following commands
    ```
    $ dotnet restore
    ```
    ```
    $ dotnet test
    ```

</details>
<br/>

This program was built using *`Microsoft .NET SDK 5.0.401`*, and may not be compatible with other versions. Your milage may vary.

---
## Known Bugs

* No known bugs

## License
MIT

## Contact Information
Zhibin Liang <ifthereisoneday@gmail.com>

Copyright &copy; 2022 Zhibin Liang