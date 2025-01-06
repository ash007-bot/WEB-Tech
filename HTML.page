A01 - User Signup Page  and Login

*code:*

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Signup Page</title>
  
 <style>
   
</title> 
<style> 
body { 
  font-family: Arial, sans-serif; 
  margin: 0; 
  padding: 0; 
  background-image: linear-gradient(180deg, rgb(34, 151, 5), rgb(77, 73, 73)); 
} 
.container { 
  max-width: 600px; 
  margin: 50px auto; 
  padding: 20px; 
  background-color: white; 
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1); 
  border-radius: 10px; 
  border: 2px solid rgb(255, 255, 255, 0.3); 
  background: rgb(255, 255, 255, 0.1); 
  backdrop-filter: blur(3px); 
} 
h2 { 
  text-align: center; 
  color: #000000; 
} 
.signup-form { 
  display: flex; 
  flex-direction: column; 
  gap: 15px; 
} 
label { 
  font-weight: bold; 
  color: rgb(255, 255, 255); 
} 
input[type="text"], 
input[type="password"], 
input[type="date"], 
input[type="tel"], 
input[type="email"], 
select { 
  padding: 10px; 
  font-size: 16px; 
  border: 1px solid #ccc; 
  border-radius: 5px; 
} 
input[type="radio"] { 
  margin-right: 10px; 
} 
button[type="submit"] { 
  padding: 10px 15px; 
  font-size: 20px; 
  background-color: #eb4e39; 
  color: white; 
  border: none; 
  border-radius: 5px; 
} 
button[type="submit"]:hover { 
  background-color: #0c6b11; 
} 
.gender-options label { 
  display: inline-block;
  margin-right: 20px;
}
 </style>
</head>

<body>
  <div class="container">
    <h2>Signup Page</h2>
    <form  action="POST" class="signup-form">

      <label for="username">Username:</label>
      <input type="text" id="username" name="username" required>

      <label for="password">Password:</label>
      <input type="password" id="password" name="password" required>

      <label for="gender">Gender:</label>
      <div class="gender-options">
        <label>
          <input type="radio" name="gender" value="male"> Male
        </label>
        <label>
          <input type="radio" name="gender" value="female"> Female
        </label>
      </div>

      <label for="dob">Date of Birth:</label>
      <input type="date" id="dob" name="dob" required>

      <label for="telephone">Telephone Number:</label>
      <input type="tel" id="telephone" name="telephone" pattern="^\+?[0-9\s\-()]*$" required>

      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>
      
      <button type="submit">Submit</button>
    </form>
  </div>
</body>
</html>
