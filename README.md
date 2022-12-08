# forms<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
<style>
label{
    padding:12px 12px 12px 0;
    display: block;
}
form{
    margin: auto auto;
    background-color: pink;
}
input[type=text],select,textarea, input[type=email], input[type=password]{
    margin:10xp 10px 10px 10px;
    width:70%;
    padding:12px;
    border: 1px solid #ccc;
    border-radius: 4px;
    resize: vertical;
}
input[type=submit], input[type=reset]{
    background-color: lightblue;
    color: white;
    padding:12px 20px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
}
input[type=submit]:hover{
    background-color: yellow;
}
input[type=reset]:hover{
    background-color: darkblue;
}
input:focus{
    background-color:blue;
}
#Search{
    background-image:url('images'jpg');
    background-position: 10px 10px;
    background-repeat: no-repeat;
    background-size: 25px;
    padding-left: 40px;
}
</style>
</head>
<body>
    <div>
    <form><div style="text-align: center;"><input name="Search"  id="Search" type="text" placeholder="Search"></div>
        <fieldset>
            <legend>CONTACT</legend>
        <label for="Firstname">Firstname</label>
        <input type="text" name="Firstname" placeholder="Firstname">
        <label for="Lastname">Lastname</label>
        <input type="text" name="Lastname" placeholder="Lastname">
        <label for="Email">Email</label>
        <input type="text" name="Email" placeholder="Email">
        <label for="Password">Password</label>
        <input type="password" name="Password" placeholder="Password">
		 <input type="confirm password" name=" confirm Password" placeholder="confirm Password">
        <label for="Subjects">Subjects</label>
        <input type="checkbox" name="Subjects" value="HTML">HTML
        <input type="checkbox" name="Subjects" value="CSS">CSS
        <input type="checkbox" name="Subjects" value="Java">Java<br>
        <label for="gender">Gender</label>
        <input type="radio" name="gender" value="Male">Male
        <input type="radio" name="gender" value="Female">Female<br>
        State:&nbsp;&nbsp;&nbsp;<select name="dropdown">
            <option value="AP">Andhra Pradesh</option>
            <option value="MP">Madhya Pradesh</option>
            <option value="Pun">Punjab</option>
            <option value="J&K">Jammu and Kashmir</option></select><br>
            <label for="message">Message</label>
        <textarea name="message" rows="10" cols="50"></textarea><br>
        <input type="submit">
        <input type="reset">
    </fieldset></form></div>
</body>
</html>
