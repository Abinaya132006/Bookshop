<html>          
<head>          
  <title>Bookshop</title>          
  <style>          
    body {          
      font-family: Arial, sans-serif;          
      background: lightgray ;          
      margin: 0;          
      padding: 0;          
    }          
    header {          
      background: darkslategray;          
      color: white;          
      padding: 20px;          
      text-align: center;          
    }          
    nav a {          
      color: white;          
      margin: 0 10px;          
      text-decoration: none;          
      padding-bottom: 5px;          
      border-bottom: 2px solid transparent;          
    }          
    nav a:hover {          
      border-bottom-color: lightgray;          
    }          
    section {          
      display: none;          
      padding: 20px;          
      max-width: 800px;          
      margin: 20px auto;          
      background: white;          
      border-radius: 5px;          
    }          
    section:target {          
      display: block;          
    }          
    #home:target,          
    body:not(:target) #home {          
      display: block;          
    }          
    .books {          
      display: flex;          
      flex-wrap: wrap;          
      gap: 20px;          
      justify-content: center;          
    }          
    .book img {          
      width: 120px;          
      border: 1px solid lightgray;          
      border-radius: 3px;          
    }          
    footer {          
      text-align: center;          
      padding: 10px;          
      color: dimgray;          
    }          
  </style>          
</head>          
<body>    <header>          
    <h1>My Bookshop</h1>          
    <nav>          
      <a href="#home">Home</a>          
      <a href="#about">About Us</a>          
      <a href="#books">Books</a>          
      <a href="#contact">Contact</a>          
    </nav>          
  </header>    <section id="home">          
    <h3><center>Discover your next great read with us!!</center></h3>          
  </section>    <section id="about">          
    <h2>About Us</h2>          
        <center><img src="bs.jpg" alt="Our Bookshop" width="200"></center>          
        <h5>Welcome To <strong>My Bookshop</strong> - your cozy corner for great stories !!<br>          
        We offer a wide range of books for all ages and interests.<br>          
        We are passionate about connecting readers with a diverse selection of titles across all genres,          
        from bestsellers to hidden gems. Our mission is to inspire a love for reading by          
        providing a curated collection that caters to every taste.          
</h5>          
</section>  <section id="books">          
  <h2>Featured Books</h2>          
  <center>          
  <table cellspacing="20" cellpadding="10">  <tr>          
  <td>          
    <img src="book1.jpg" alt="Book One" width="150"><br>          
    <strong>Harry Potter</strong><br>by J K Rowling          
  </td>          
  <td>          
    <img src="book2.jpg" alt="Book Two" width="150"><br>          
    <strong>The Hobbit</strong><br>by John Smith          
  </td>          
</tr>          
<tr>          
  <td>          
    <img src="book3.jpg" alt="Book Three" width="150"><br>          
    <strong>Nuclear War</strong><br>by Annie Jacobsen          
  </td>          
  <td>          
    <img src="book4.jpg" alt="Book Four" width="150"><br>          
    <strong>The Psychology of Money</strong><br>by Morgan Housel          
  </td>          
</tr>          
<tr>    <td>          
    <img src="book5.jpg" alt="Book Five" width="150"><br>          
    <strong>The Alchemist</strong><br>by Paulo Coelho          
  </td>          
  <td>          
    <img src="book6.jpg" alt="Book Six" width="150"><br>          
    <strong>Mind Battles</strong><br>by Kathy DeGraw          
  </td>          
</tr>    </table>          
  </center>          
  </section>          
  <section id="contact">          
    <h2>Contact</h2>          
    <p>Email: bookshop@gmail.com<br>Phone: +91 98765 43210</p>          
  </section>          
</body>          
</html>
