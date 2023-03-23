# Form-Input-Type

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <form>
        <h1>Signup</h1>
       <div>
        Fullname: <br>
        <input type="text" name="fullname">
       </div>
       <div>
        Email: <br>
        <input type="email" name="email">
       </div>
       <div>
        Password: <br>
        <input type="password" name="Password">
       </div>
       <div>
        Confirm Password: <br>
        <input type="password" name="confirm password">
       </div>
       <div>
        Gender: <br>
        <input type="radio" name="male" value="male">
        Male</input>
        <input type="radio" name="female" value="female">
        Female</input>
        <input type="radio" name="other" value="other">
        Other</input>
       </div>
       <div>
        Security Question: <br>
        <select name="security-question">
            <option value="first-pet-name">What was your pet Name?</option>
            <option value="first-job">What is your first job?</option>
            <option value="nick-name">What is your nick name?</option>
        </select>
       </div>
       <div>
        <textarea name="answer" id="" cols="30" rows="10"></textarea>
       </div>
       <div>
        <input type="checkbox" name="terms-conditions" value="accept">I agree to accept terms and conditions
       </div>
       <input type="submit" value="register">
    </form>
</body>
</html>
