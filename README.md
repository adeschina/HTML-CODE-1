<!DOCTYPE html>
<html>
  <head>
	   <meta charset="UTF-8">
     <meta name="description" content="This is shina first website">
	    <title>www.shina.com</title>

  </head>

  <body style="background-color:#663399;">
	   <h3 style="color:white;">Home</h3>
     <img src="slack.jpeg" alt="Check your connection" />
     <form action="procesform.php"method="POST">
       <p>
         <hr/>
         <a style="color:white;"href="https://app.slack.com/client/TUV68SBHU/CUE6APANN" target="_blank"><h1>Return to Startng Homepage</h1></a>
         <br/>
         <label style="color:white;" for="first_name">First Name</label><br/>

     <input type="text"name="first_name"placeholder="Enter Your First Name"/>
   </p>
   <p>
       <label style="color:white;" for="last_name">Last Name</label><br/>
       <input type="text" name="last_name" placeholder="Enter Your Last Name"/>
     </P>


     <p>
       <label style="color:white;" for="email">Email</label><br/>
       <input type="email" name="email" placeholder="Enter Your Email" required/>
     </p>
     <p>
       <label style="color:white;" for="department">Department</label><br/>
       <select name="department">
         <option>HR</option>
         <option>Marketing</option>
         <option>Board</option>
         <option>kitchen</option>
       </select>
     </p>
     <p>
       <label style="color:white;" for="gender">Gender</label><br/>
       <input style="color:white;" type="radio" name="gender"/> Male

       <input style="color:white;" type="radio" name="gender"/> Female
     </p>
     <p>
       <label style="color:white;" for="email">Your Message</label><br/>
       <textarea name="message"></textarea>
     </p>
     <button type="submit">Send Message</button>
     <p>
       <input type="checkbox" name="terms" required/> By Checking this box you agree to our terms and conditions
     </p>
   </form>


   </body>
<!-- </html> -->
