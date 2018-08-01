****This project will help to insert, update, delete or show data from database******


***copy the "Employee_Info" folder to the local server diractory.
*** hit "http://localhost/.../Employee_info" to run the project.

//database connection
  $servername = "localhost";
  $username = "root";
  $password = "";
  $dbname = "employee_info";
  $con = new mysqli($servername, $username, $password, $dbname);

  if($con->connect_error){
    die ('Connection failed: ' . $con->connect_error);
  }

**this will connect to the local server, so please make sure local server is running.**....
