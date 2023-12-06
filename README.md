<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pet Care Website</title>
  <style>
    header {
      background-color: #f0f0f0;
      padding: 20px;
      text-align: center;
    }
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }
    header {
      background-color: #333;
      color: #fff;
      padding: 20px;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      background-color: #444;
      padding: 10px 0;
    }
    nav a {
      color: #fff;
      text-decoration: none;
      padding: 8px 15px;
      margin: 0 5px;
      border-radius: 5px;
      transition: background-color 0.3s ease;
    }
    nav a:hover {
      background-color: #666;
    }
    .container {
      width: 80%;
      margin: auto;
      overflow: hidden;
    }
    .main {
      float: left;
      width: 70%;
      padding: 20px;
      background-color: #fff;
      box-sizing: border-box;
    }
    .sidebar {
      float: left;
      width: 30%;
      background-color: #f4f4f4;
      padding: 20px;
      box-sizing: border-box;
    }
    .footer {
      clear: both;
      text-align: center;
      padding: 20px;
      background-color: #333;
      color: #fff;
    }
    footer {
      background-color:grey;
      padding: 20px;
      text-align: center;
    }

    /* Other Styles */
    .pet-info {
      margin-bottom: 20px;
    }
    .pet-info h2 {
      color: #333;
    }
    .pet-info p {
      color: #666;
    }
    .pet-info img {
      width: 100%;
      height: auto;
      margin-bottom: 10px;
      border-radius: 20px;
    }
    .appointment-form {
      background-color: #eee;
      padding: 15px;
      margin-top: 20px;
    }
    .appointment-form input[type="text"],
    .appointment-form input[type="email"],
    .appointment-form textarea,
    .appointment-form input[type="submit"] {
      width: 100%;
      padding: 10px;
      margin-bottom: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
      box-sizing: border-box;
    }
    .appointment-form input[type="submit"] {
      background-color: #333;
      color: #fff;
      cursor: pointer;
    }
    .appointment-form input[type="submit"]:hover {
      background-color: #444;
    }
  </style>
</head>
<body>
  <header>
    <h1>WELCOME TO PAW PERFECT HUB</h1>
  </header>
  
  <nav>
    <a href="#">Home</a>
    <a href="#services">Services</a>
    <a href="#about">About Us</a>
    <a href="#contact">Contact Us</a>
  </nav>
  <section id="about">
  <div class="container">
    <div class="main">
      <h2>About Our Pet Care Services</h2>
      <p>The best way to ensure your pet lives a healthy, happy life is to take a proactive approach to their health and wellness. Every animal has unique needs, so we offer a variety of ways for you to get necessary, non-emergency care that’s right for you and right for them.</p>
      <div class="pet-info">
        <img src="pet-sitter-125863-FINAL_HL-c15673c1d7634512ae359bffb45863f4.png"">
        <p>We provide service that care and assistance for pets.Our Pet care services can range from basic services such as feeding and walking, to more specialized services such as grooming, training, and veterinary care</p>
        <h2>Professional Veterinary Care</h2>
        <p>We provide expert veterinary care for your pets. Our experienced team ensures the well-being of your beloved animals.</p>
      </div>
      
      <div class="pet-info">
        <img src="care-services.jpg">
      </div>
      <p>Expert veterinary care tailored to your pet's needs, from routine check-ups to advanced diagnostics, ensuring their health and happiness. Our compassionate team of skilled veterinarians is dedicated to providing personalized, state-of-the-art medical attention for your beloved pet</p>
      
      <h2>Safety first</h2>
      <p>Counselors certified in pet first aid and CPR put your dog’s health and happiness first.</p>
      <h2>SPACIOUS PLAY YARDS      </h2>
      <p>Our oasis offers large, climate-controlled play yards for optimal tail wags.</p>
      <h2>MONITOR YOUR PUP      </h2>
      <p>Access our live webcams on your computer or smartphone.</p>
      <section id="contact">
      <div class="appointment-form">
        <h2>Book an Appointment</h2>
        <form action="#" method="post">
          <input type="text" name="name" placeholder="Your Name" required>
          <input type="email" name="email" placeholder="Your Email" required>
          <textarea name="message" placeholder="Your Message" rows="4" required></textarea>
          <input type="submit" value="Subscribe">
        </form>
        <h1>THANK YOU FOR VISITING US</h1>
      </div>
      <h2>If you have any Query </h2>
      <a>EMAIL on - mayankkausishrakshak@gmail.com</a>
      <h1>Address</h1>
        <p>Saharanpur , UttarPradesh</p>
        <h1>NOTE-</h1>
        <p>You can book Appointment online </p>
        <h2>&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbspHope we will meet again at</h2>
        <img src="Screenshot 2023-12-03 213831.png">
    </section>
    </div>
    <!-- <img src="Screenshot 2023-12-03 213831.png"> -->
    <div class="sidebar">
      <h2>Opening Hours</h2>
      <p>Monday - Friday: 9am - 6pm</p>
      <p>Saturday: 10am - 4pm</p>
      <p>Sunday: Closed</p>
      <div class="pet-info">
      <h2>Products</h2>
      <img src= "61PWvkjjQXL.jpg" 
                               alt="Product 1" width="400" height="600"
                             > 
                             <p>best for All breeds</p> 
                             <p><span>450 Rs</span></p> 
                            </div>
                            <input type="hidden" 
                            name="product_id" 
                            value="1"> 
                     <label for="product1_quantity"> 
                           Quantity: 
                     </label> 
                     <input type="number"
                            id="product1_quantity" 
                            name="product_quantity" 
                            value="" 
                            min="0" 
                            max="10"> 
      <button type="submit" 
      name="add_to_cart"> 
Add to Cart</button> 
</form> 
      <div class="pet-info">
        <h3>Adoptation</h3>
        <p>A playful and friendly dog looking for a loving home.</p>
        <img src="cutest-dog-breeds-jpg.jpg">
        <label for="breed-select">Select a dog breed:</label>
        <select id="breed-select">
          <option value="labrador">Labrador Retriever</option>
          <option value="germanshepherd">German Shepherd</option>
          <option value="bulldog">Bulldog</option>
         
        </select>
        

      </div>
      <section id="services">
      <div class="pet-info">
        <h3>Dogs Training</h3>
        <img src="dog_trainer.jpg.optimal.jpg">
        <p>Elevate your pet's skills with our customized training sessions, fostering a strong bond and well-mannered behavior. Let us guide your dog's journey to obedience and joyous companionship.</p>

        
      </div>
    </section>
      <div class="pet-info">
        <h3>Pet Grooming Services</h3>
        <img src="woman-grooming-pomeranian-dog-with-clippers_Peakstock_Shutterstock-760x506.jpg">
        <p>Keep your pets clean and healthy with our grooming services. We offer bathing, trimming, and nail clipping.</p>
        
      <h2>Dog day care service</h2>
      <p>Give your dog a day full of fun and social interaction at our premier dog day care. Our supervised facility offers a safe and stimulating environment, complete with playtime, socialization, and personalized care. Let your furry friend thrive in a space designed for their enjoyment and well-being, ensuring a day filled with tail wags and happiness</p>

      </div>
      <div class="pet-info">
        <h3>Dogs Boarding,Walking,Sitting</h3>
        <img src="a80a723a85685d9e1e477855fb523efd.jpg">
        <p>Trust us for top-tier care while you're away—boarding, walking, and sitting services tailored to your dog's comfort and happiness. Our experienced team ensures your dog feels at home, whether strolling, staying overnight, or receiving personalized attention</p>
        
        
      </div>

    </div>
   </div>
  <footer>
    <p>Congratulations You are eligible for 50% discount for today.</p>
</footer>
  
  <footer class="footer">
    <p>&copy; 2023 Pet Care Center. All rights reserved.</p>
  </footer>
  
</body>
</html>
