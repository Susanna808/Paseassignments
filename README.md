<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
    input[type=text], select{
        width: 100%; 
        padding: 12px 20px;
        margin: 8px 0;
        display: inline-block;
        border: 1px solid #ccc;
        border-radius: 4px;
        box-sizing: border-box;
    }
    .button{
        background-color: green;
    }
    div{
        border-radius: 5px;
        background-color: grey;
        padding: 20px;
    }
    .textarea{
        width: 100%;
        padding-bottom: 12rem;
    }

</style>

<body>
<form>
    <label for="fname">First name:</label><br>
    <input type="text" id="fname" name="fname" placeholder="your name"><br>
    <label for="lname">Last name:</label><br>
    <input type="text" id="lname" name="lname" placeholder="Your last name"><br>
    <label for="country">Country</label>
    <select name="country" id="country">
        <option value="Ghana">Ghana</option>
        <option value="Ghana">Spain</option>
        <option value="Ghana">Nigeria</option>
        <option value="Ghana">Germany</option>
        <option value="Ghana">Madagascar</option>
    </select><br>

    <label>Subject</label>
    <textarea class="textarea" placeholder="Write something"></textarea>
    <button class="button">Submit</button>

    
  </form> 
</body>
</html># Paseassignments
