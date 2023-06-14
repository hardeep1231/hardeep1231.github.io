
<html>
<head>
   <title>Film Collection</title>
   <style>
      body {
         font-family: Arial, sans-serif;
         margin: 0;
         padding: 0;
      }

      .navbar {
         background-color: #333;
         padding: 10px;
      }

      .navbar ul {
         list-style-type: none;
         margin: 0;
         padding: 0;
         display: flex;
         justify-content: space-between;
         align-items: center;
      }

      .navbar li {
         margin: 0 10px;
      }

      .navbar a {
         color: #FCA311;
         text-decoration: none;
         font-size: 16px;
      }

      .container {
         max-width: 1200px;
         margin: 0 auto;
         padding: 40px;
      }

      h1 {
         text-align: center;
        
         margin-bottom: 30px;
      }

      p {
         margin-bottom: 20px;
      
         text-align: center;
         font-size: 16px;
      }

      .image-container {
         display: flex;
         flex-wrap: wrap;
         justify-content: center;
         margin-top: 40px;
      }

      .image {
         width: 400px;
         height: 600px;
         margin: 10px;
         background-color: #ffffff;
         border-radius: 4px;
         overflow: hidden;
         box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
         transition: transform 0.3s ease;
      }

      .image:hover {
         transform: scale(1.05);
      }

      .image img {
         width: 100%;
         height: 100%;
         object-fit: cover;
      }

      .button-container {
         display: flex;
         justify-content: center;
         margin-top: 30px;
      }

      .button {
         display: inline-block;
         padding: 12px 20px;
         background-color: #FF5722;
         color: #ffffff;
         text-decoration: none;
         font-size: 16px;
         border-radius: 4px;
         transition: background-color 0.3s ease;
         margin: 10px;
         border: none;
         cursor: pointer;
      }

      .button:hover {
         background-color: #E64A19;
      }

      .feature-container {
         margin-top: 40px;
         display: flex;
         justify-content: center;
         align-items: center;
         flex-wrap: wrap;
      }

      .feature {
         width: 300px;
         padding: 20px;
         background-color: #ffffff;
         border-radius: 4px;
         box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
         margin: 10px;
         text-align: center;
      }

      .feature h2 {
         color: #6D4C41;
         font-size: 20px;
         margin-bottom: 10px;
      }

      .feature p {
         color: #666666;
         font-size: 14px;
         line-height: 1.5;
      }
   </style>
     
</head>
<body>
   <div class="navbar">
      <ul>
         <li><a href="#" style="background-color: #153;
         color: #fff;
         padding: 20px;
         display: flex;
         justify-content: space-between;
         align-items: center;">Film Collection</a></li>
         <li>
            <a href="signin.html" class="button" style="color: #ffffff;">Login</a>
            <a href="signup.html" class="button" style="color: #ffffff;">Signup</a>
         </li>
      </ul>
   </div>

   <div class="container">
      <h1>Welcome to Film Collection</h1>
      <p>Explore, organize, and enjoy your favorite films.</p>

      <div class="image-container">
         <div class="image">
            <img src="https://www.joblo.com/wp-content/uploads/2020/01/the-flash-new-poster-3-400x600.jpg" alt="Film Image 1">
         </div>
         <div class="image">
            <img src="https://www.washingtonpost.com/graphics/2019/entertainment/oscar-nominees-movie-poster-design/img/black-panther-web.jpg" alt="Film Image 2">
         </div>
         <div class="image">
            <img src="https://static-01.daraz.pk/p/b327cc57bf5fa9cca345139b38e8f52a.jpg" alt="Film Image 3">
         </div>
      </div>


      <div class="feature-container">
         <div class="feature">
            <h2>Personalized Collection</h2>
            <p>Create and maintain your own film collection based on your interests and preferences.</p>
         </div>
         <div class="feature">
            <h2>Discover New Films</h2>
            <p>Explore a wide range of films from different genres and discover new favorites to add to your collection.</p>
         </div>
         <div class="feature">
            <h2>Rating and Reviews</h2>
            <p>Rate and review films in your collection to keep track of your thoughts and share recommendations with others.</p>
         </div>
      </div>
   </div>
</body>
</html>
