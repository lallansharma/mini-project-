# mini-project-
Payment form


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>payment form</title>
</head>
<body>
    <form action="">
        <style>
            h1{
                text-align: center;
                text-align:center;
               color: white;
               background-color:black; 
            }
        </style>
        <h1>payment form</h1>
        <p>* fields are required</p>
        <h2>contact information</h2>
        <p>name*:<input type="text" name="name" required></p>

  <fieldset>
    <legend>gender*</legend>      
    <legend>gender*</legend>      
        <p>
    male <input type="radio" name="*gender" id="male" required> female <input type="radio" name="*gender" id="female"  required>
</p>

</fieldset>
<p>address *:<textarea name="address" id="address" required cols="100" rows="8"></textarea></p>
<p>email*: <input type="email" name="email" id="email"></p>  
<p>pincode*: <input type="number" name="pincode" id="pincode" required</p>
<hr>
<h2>payment ingformation</h2>
<p>card type*:
    <select name*="card_type" id="card_type" required>
        <option value="">--select card type</option>
        <option value="rupay">rupay</option>
        <option value="mastercard">mastercard</option>
        <p>card number* <input type="number" name="number" id="number" required></p>
       <p>expiration date*: <input type="date" name="date" id="expiry_date" required></p>
       <p>CVV* <input type="password" name="CVV" id="CVV" required></p>
       <input type="submit" value="pay now">
    </select>
</p>
</form>
</body>
</html>
