<!DOCTYPE html>
 <html>
 <html lang="en">
 <head>
     <meta charset="UTF-8">
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <title>My Website</title>
     <style>
         /* CSS to style the page */
         body {
             background-color: #f0f8ff; /* Light blue background */
             font-family: 'Arial', sans-serif; /* Beautiful font */
             color: #333; /* Text color */
             text-align: center;
             padding-top: 50px;
         }
         h1 {
             color: #0077cc; /* Title color */
         }
         a {
             color: #ff6347; /* Link color */
             text-decoration: none;
         }
         a:hover {
             color: #ff4500; /* Hover color */
         }
         img {
             max-width: 80%;
             height: auto;
             border-radius: 10px;
         }
         button {
             padding: 10px 20px;
             font-size: 16px;
             background-color: #4CAF50;
             color: white;
             border: none;
             border-radius: 5px;
             cursor: pointer;
         }
         button:hover {
             background-color: #45a049;
         }
     </style>
 </head>
 <body>
 
 <h1>Hi!</h1>
     <h1>Welcome to My Website!</h1>
 
 <p>Madu this is my first website.</p>
     <!-- Add an image -->
     <img src="https://via.placeholder.com/800x400" alt="Sample Image">
 
     <!-- Add a hyperlink -->
     <p>Check out <a href="https://www.w3schools.com" target="_blank">W3Schools</a> for more tutorials!</p>
 
     <!-- Button with onClick JavaScript event -->
     <button onclick="changeBackgroundColor()">Click Me to Change Background Color</button>
 
     <script>
         // JavaScript function to change background color
         function changeBackgroundColor() {
             document.body.style.backgroundColor = "#90EE90"; // Change background color to light green
         }
     </script>
 
 </body>
 </html>
