# CPIExam_Toledo
<html>
<head>
</head>
<body>
    <form action="update.php" method="post">
        <h>CREATE</h><br>
        <label> Post Title </label>
        <input type="text" name="ptitle" placeholder="Title"><br>
        <label> Descrition </label>
        <input type="text" name="description" placeholder="Description"><br>
        <label> Your Photo </label>
        <input type="file" name="photo" placeholder="photo"><br>
        <button type="submit">Post</button>
    </form>
</body>
</html>

<?php
session_start();
include "db_conn.php";


$sql = "INSERT INTO `skilltest`(`Title`, `Description`, `Photo`) VALUES ('ptitle','description','photo')";


<?php
session_start();
include "db_conn.php";


$sql = "SELECT * FROM skilltest";
