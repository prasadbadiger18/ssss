<!DOCTYPE html>
<html>
<head>
  <meta charset="utf-8">
  <title>Submit Form</title>
  <meta name="description" content="This is an example of a meta description.">
</head>
<body>
  <h1>Submit Form</h1>
  <form action="<?php echo htmlspecialchars($_SERVER["PHP_SELF"]); ?>" method="POST">
    Username : <input type="text" value="Prasad" name="firstName"><br><br>
    Password  : <input type="text" value="55" name="rfidNumber"><br><br>
    <input type="submit" value="Submit">
  </form>

  <?php
  if ($_SERVER["REQUEST_METHOD"] == "POST") {
    // Database connection parameters
    $servername = "sql6.freesqldatabase.com";
    $username = "sql6693786"; // Replace with your MySQL username
    $password = "FMzffykna4"; // Replace with your MySQL password
    $database = "sql6693786"; // Replace with your MySQL database name

    // Create connection
    $conn = new mysqli($servername, $username, $password, $database);

    // Check connection
    if ($conn->connect_error) {
        die("Connection failed: " . $conn->connect_error);
    }

    // Get data from the form
    $firstName = isset($_POST['firstName']) ? $_POST['firstName'] : '';
    $rfidNumber = isset($_POST['rfidNumber']) ? $_POST['rfidNumber'] : '';

    // Prepare SQL statement with a placeholder for values
    $sql = "INSERT INTO RVM (FirstName, RFID_No) VALUES (?, ?)";

    // Create a prepared statement
    $stmt = $conn->prepare($sql);

    // Bind parameters and execute the statement
    $stmt->bind_param("ss", $firstName, $rfidNumber);

    if ($stmt->execute()) {
        echo "New record created successfully";
    } else {
        echo "Error: " . $sql . "<br>" . $conn->error;
    }

    // Close statement and connection
    $stmt->close();
    $conn->close();
  }
  ?>
</body>
</html>
