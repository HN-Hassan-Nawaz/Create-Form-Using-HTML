<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>form</title>
</head>

<body>
    <h2>My HTML Form</h2>
    <form action="backend.php">
        <label for="name"> Name</label>
        <div>
            <input type="text" name="MyName" id="name">
        </div>
        <br>

        <label for="role">Role</label>
        <div>
            <input type="text" name="myrole" id="role">
        </div>
        <br>

        <label for="mail">Email</label>
        <div>
            <input type="email" name="myemail" id="mail">
        </div>
        <br>

        <label for="date">Date</label>
        <div>
            <input type="date" name="mydate" id="date">
        </div>
        <br>

        <label for="bonus">Bonus</label>
        <div>
            <input type="number" name="mybonus" id="bonus">
        </div>
        <br>

        <label for="eligible">Are You Eligible</label>
        <div>
            <input type="checkbox" name="myeligibility" id="eligible">
        </div>
        <br>

        <label for="malegender">Male</label>
        <label for="femalegender">Female</label>
        <label for="none">Other</label>
        <div>
            <input type="radio" name="mygender" id="malegender">
            <input type="radio" name="mygender" id="femalegender">
            <input type="radio" name="mygender" id="none">
        </div>
        <br>

        <label for="yourself">Write About Yourself</label>
        <div>
            <textarea name="mytext" cols="30" rows="10" id="yourself"></textarea>
        </div>
        <br>

        <label for="car">Car</label>
        <div>
            <select name="mycar" id="car">
                <option value="ind" selected>Indica</option>
                <option value="swf">Swift</option>
            </select>
        </div>
        <br>

        <div>
            <input type="Submit" value="Submit Now">
            <input type="Reset" value="Reset Now">
        </div>
    </form>
</body>
</html>
