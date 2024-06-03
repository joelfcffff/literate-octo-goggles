<!DOCTYPE html>
<html lang="en">
<head>
<title>my website</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lato">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body {font-family: "Lato", sans-serif}
.mySlides {display: none}
</style>
</head>
<body>

<!-- Navbar -->
<div class="w3-top">
  <div class="w3-bar w3-black w3-card">
    <a class="w3-bar-item w3-button w3-padding-large w3-hide-medium w3-hide-large w3-right" href="javascript:void(0)" onclick="myFunction()" title="Toggle Navigation Menu"><i class="fa fa-bars"></i></a>
    <a href="#" class="w3-bar-item w3-button w3-padding-large">Home</a>
    <a href="#band" class="w3-bar-item w3-button w3-padding-large w3-hide-small">Products</a>
    <a href="#tour" class="w3-bar-item w3-button w3-padding-large w3-hide-small">Services</a>
    <a href="#contact" class="w3-bar-item w3-button w3-padding-large w3-hide-small">contact us</a>
    <div class="w3-dropdown-hover w3-hide-small">
      <button class="w3-padding-large w3-button" title="More">Packages <i class="fa fa-caret-down"></i></button>     
      <div class="w3-dropdown-content w3-bar-block w3-card-4">
        <a href="#" class="w3-bar-item w3-button">Basic</a>
        <a href="#" class="w3-bar-item w3-button">Intermediate</a>
        <a href="#" class="w3-bar-item w3-button">Advanced</a>
      </div>
    </div>
    <a href="javascript:void(0)" class="w3-padding-large w3-hover-red w3-hide-small w3-right"><i class="fa fa-search"></i></a>
  </div>
</div>

<!-- Navbar on small screens (remove the onclick attribute if you want the navbar to always show on top of the content when clicking on the links) -->
<div id="navDemo" class="w3-bar-block w3-black w3-hide w3-hide-large w3-hide-medium w3-top" style="margin-top:46px">
  <a href="#band" class="w3-bar-item w3-button w3-padding-large" onclick="myFunction()">BAND</a>
  <a href="#tour" class="w3-bar-item w3-button w3-padding-large" onclick="myFunction()">TOUR</a>
  <a href="#contact" class="w3-bar-item w3-button w3-padding-large" onclick="myFunction()">CONTACT</a>
  <a href="#" class="w3-bar-item w3-button w3-padding-large" onclick="myFunction()">Products</a>
</div>

<!-- Page content -->
<div class="w3-content" style="max-width:2000px;margin-top:46px">

  <!-- Automatic Slideshow Images -->
  <div class="mySlides w3-display-container w3-center">
    <img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.peakpx.com%2Fen%2Fsearch%3Fq%3Dbook&psig=AOvVaw3eZpLznHFkzLiLqJf9KOMT&ust=1717429242465000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCMC9m9CgvYYDFQAAAAAdAAAAABAE" style="width:45%" height="50%">
    <div class="w3-display-bottommiddle w3-container w3-text-white w3-padding-32 w3-hide-small">
      <h1>Pride and Prejudice</h1>
      <p><b>Books Give Knowlege</b></p>   
    </div>
  </div>
  <div class="mySlides w3-display-container w3-center">
    <img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Ftest.honda.com.gt%2F%3Fs%3D220%2B-book-hd-wallpapers-and-backgrounds-ii-opk1deHn&psig=AOvVaw3eZpLznHFkzLiLqJf9KOMT&ust=1717429242465000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCMC9m9CgvYYDFQAAAAAdAAAAABAJ" style="width:45%" height="50%">
    <div class="w3-display-bottommiddle w3-container w3-text-white w3-padding-32 w3-hide-small">
      <h1>
        Don Quixote</h1>
      <p><b>Books Give Knowlege</b></p>    
    </div>
  </div>
  <div class="mySlides w3-display-container w3-center">
    <img src="https://www.google.com/url?sa=i&url=https%3A%2F%2Fwallpapers.com%2Fwallpapers%2Feducational-science-books-sxe9wj38f6ugflr8.html&psig=AOvVaw3eZpLznHFkzLiLqJf9KOMT&ust=1717429242465000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCMC9m9CgvYYDFQAAAAAdAAAAABAd" style="width:45%" height="50%">
    <div class="w3-display-bottommiddle w3-container w3-text-white w3-padding-32 w3-hide-small">
      <h1>To Kill a Mockingbird</h1>
      <p><b>Books Give Knowlege</b></p>    
    </div>
  </div>

  <!-- The Band Section -->
  <div class="w3-container w3-content w3-center w3-padding-64" style="max-width:800px" id="band">
    <h2 class="w3-wide"<h2> READ IT</h2>
    <p class="w3-opacity"><i>We love reading</i></p>
    <p class="w3-justify">  "Welcome to our digital sanctuary for book lovers! Our e-book club is a vibrant community where literature aficionados unite to explore the boundless realms of storytelling. Here, the turning of digital pages sparks lively discussions, illuminates new perspectives, and fosters a profound appreciation for the written word. Whether you're a seasoned bibliophile or just embarking on your literary journey, join us as we embark on thrilling adventures through the pages of countless e-books. Let's embark on a voyage of imagination together, one chapter at a time!".</p>
    <div class="w3-row w3-padding-32">
      <div class="w3-third">
        <h1>Basic </h1>
        <p>Book of the month and three own choice books</p>
        <p>Open access to all forums and discussion groups</p>
        <P>Choice of three items of merchandise </P>
        <P>Refreshments x 3 – box of coffee, hot chocolate or tea  </P>
      </div>
      <div class="w3-third">
        <h1>Intermediate</h1>
       <p>Book of the month plus one own choice book</p>
       <p>Access to two review forums and discussion groups</p>
       <p>Bookmark and book bag</p>
       <p> Refreshments x 2 – box of coffee, hot chocolate or tea</p>
      </div>
      <div class="w3-third">
        <h1>Advanced</h1>
        <p> Book of the month </p>
        <p>Access to one review forum and discussion group </p>
        <p> Bookmark and drinks mug </p>
        <p> Refreshments x 1 – box of coffee or tea.</p>
      </div>
      <div class="w3-third">
        <h1 class="w3">Custom</h1>
        <p> ARE AVAILABLE EVERY MONTH FOR PARTICULAR GENRES, ADDITIONAL BOOKS, AND MERCHANDISE. </p>
        <p> </p>
        <p>  </p>
        <p> </p>
      </div>
    </div>
  </div>

  <!-- The Tour Section -->
  <div class="w3-black" id="tour">
    <div class="w3-container w3-content w3-padding-64" style="max-width:800px">
      <h2 class="w3-wide w3-center">READ A BOOK</h2>
      <p class="w3-opacity w3-center"><i>Remember to book your book!</i></p><br>

      <ul class="w3-ul w3-border w3-white w3-text-grey">
        <li class="w3-padding">Pride and Prejudice <span class="w3-tag w3-red w3-margin-left">Sold out</span></li>
        <li class="w3-padding">
          Don Quixote <span class="w3-tag w3-red w3-margin-left">Sold out</span></li>
        <li class="w3-padding">To Kill a Mockingbird<span class="w3-badge w3-right w3-margin-right">3</span></li>
      </ul>
    </div>
  </div>

  <!-- Ticket Modal -->
  <div id="ticketModal" class="w3-modal">
    <div class="w3-modal-content w3-animate-top w3-card-4">
      <header class="w3-container w3-teal w3-center w3-padding-32"> 
        <span onclick="document.getElementById('ticketModal').style.display='none'" 
       class="w3-button w3-teal w3-xlarge w3-display-topright">×</span>
        <h2 class="w3-wide"><i class="fa fa-suitcase w3-margin-right"></i>Tickets</h2>
      </header>
      <div class="w3-container">
        <p><label><i class="fa fa-shopping-cart"></i> Tickets, $15 per person</label></p>
        <input class="w3-input w3-border" type="text" placeholder="How many?">
        <p><label><i class="fa fa-user"></i> Send To</label></p>
        <input class="w3-input w3-border" type="text" placeholder="Enter email">
        <button class="w3-button w3-block w3-teal w3-padding-16 w3-section w3-right">PAY <i class="fa fa-check"></i></button>
        <button class="w3-button w3-red w3-section" onclick="document.getElementById('ticketModal').style.display='none'">Close <i class="fa fa-remove"></i></button>
        <p class="w3-right">Need <a href="#" class="w3-text-blue">help?</a></p>
      </div>
    </div>
  </div>

      <div class="w3-row-padding w3-padding-32" style="margin:0 -16px">
        <div class="w3-third w3-margin-bottom">
          <div class="w3-container w3-white">
            <p><b>Romance</b></p>
            <img src="data:image/jpeg;base64,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" alt="New York" style="width:100%" class="w3-hover-opacity">
            <p class="w3-opacity">Novels that focus on the romantic relationships between characters</p>
            <button class="w3-button w3-black w3-margin-bottom" onclick="document.getElementById('ticketModal').style.display='block'">Buy Book</button>
          </div>
        </div>
        <div class="w3-third w3-margin-bottom">
          <div class="w3-container w3-white">
            <p><b>Mystery</b></p>
            <img src="data:image/jpeg;base64,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" alt="New York" style="width:100%" class="w3-hover-opacity">
            <p class="w3-opacity">Books that involve solving a puzzle or crime,</p>
            <button class="w3-button w3-black w3-margin-bottom" onclick="document.getElementById('ticketModal').style.display='block'">Buy Book</button>
          </div>
        </div>
        <div class="w3-third w3-margin-bottom">
          <div class="w3-container w3-white">
            <p><b>Science Fiction</b></p>
            <img src="data:image/jpeg;base64,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" alt="New York" style="width:100%" class="w3-hover-opacity">
            <p class="w3-opacity">Books that explore the consequences of scientific or technological advancements</p>
            <button class="w3-button w3-black w3-margin-bottom" onclick="document.getElementById('ticketModal').style.display='block'">Buy Book</button>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="w3-row-padding w3-padding-32" style="margin:0 -16px">
    <div class="w3-third w3-margin-bottom">
      <div class="w3-container w3-white">
        <p><b>Gift Card No 01</b></p>
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcR95Re9mJ9UUxDUx3d5L9K2U79QkJGIciAYvw&s" alt="New York" style="width:100%" class="w3-hover-opacity">
        <button class="w3-button w3-black w3-margin-bottom" onclick="document.getElementById('ticketModal').style.display='block'">Buy now</button>
      </div>
    </div>
    <div class="w3-third w3-margin-bottom">
      <div class="w3-container w3-white">
        <p><b>Gift Card No 02</b></p>
        <img src="data:image/jpeg;base64,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" alt="New York" style="width:100%" class="w3-hover-opacity">
        <button class="w3-button w3-black w3-margin-bottom" onclick="document.getElementById('ticketModal').style.display='block'">Buy now</button>
      </div>
    </div>
    <div class="w3-third w3-margin-bottom">
      <div class="w3-container w3-white">
        <p><b>Gift Card No 03</b></p>
        <img src="https://marketplace.canva.com/EAFHy4c46_k/3/0/1600w/canva-neutral-brown-rustic-texture-photo-beauty-gift-certificate-TnWG5xaBbCY.jpg" alt="New York" style="width:100%" class="w3-hover-opacity">
        <button class="w3-button w3-black w3-margin-bottom" onclick="document.getElementById('ticketModal').style.display='block'">Buy now</button>
      </div>
    </div>
  </div>
</div>
</div>

<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {font-family: Arial, Helvetica, sans-serif;}
* {box-sizing: border-box;}

/* Button used to open the chat form - fixed at the bottom of the page */
.open-button {
  background-color: #555;
  color: white;
  padding: 16px 20px;
  border: none;
  cursor: pointer;
  opacity: 0.8;
  position: fixed;
  bottom: 23px;
  right: 28px;
  width: 280px;
}

/* The popup chat - hidden by default */
.chat-popup {
  display: none;
  position: fixed;
  bottom: 0;
  right: 15px;
  border: 3px solid #f1f1f1;
  z-index: 9;
}

/* Add styles to the form container */
.form-container {
  max-width: 300px;
  padding: 10px;
  background-color: white;
}

/* Full-width textarea */
.form-container textarea {
  width: 100%;
  padding: 15px;
  margin: 5px 0 22px 0;
  border: none;
  background: #f1f1f1;
  resize: none;
  min-height: 200px;
}

/* When the textarea gets focus, do something */
.form-container textarea:focus {
  background-color: #ddd;
  outline: none;
}

/* Set a style for the submit/send button */
.form-container .btn {
  background-color: #04AA6D;
  color: white;
  padding: 16px 20px;
  border: none;
  cursor: pointer;
  width: 100%;
  margin-bottom:10px;
  opacity: 0.8;
}

/* Add a red background color to the cancel button */
.form-container .cancel {
  background-color: red;
}

/* Add some hover effects to buttons */
.form-container .btn:hover, .open-button:hover {
  opacity: 1;
}
</style>
</head>
<body>


<button class="open-button" onclick="openForm()">Chat</button>

<div class="chat-popup" id="myForm">
  <form action="/action_page.php" class="form-container">
    <h1>Join with us Whatsapp</h1>

    <label for="msg"><b>Put a Message</b></label>
    <textarea placeholder="Type message.." name="msg" required></textarea>

    <button type="submit" class="btn">Send</button>
    <button type="button" class="btn cancel" onclick="closeForm()">Close</button>
  </form>
</div>

<script>
function openForm() {
  document.getElementById("myForm").style.display = "block";
}

function closeForm() {
  document.getElementById("myForm").style.display = "none";
}
</script>

</body>
</html>

<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}
.w3-third1{
  position: relative;
  left: 100px;
}
.w3-third1{
  position: relative;
  left: 50px;
}
input[type=text], select, textarea {
  width: 100%;
  padding: 12px;
  border: 1px solid #ccc;
  border-radius: 4px;
  resize: vertical;
}

label {
  padding: 12px 12px 12px 0;
  display: inline-block;
}

input[type=submit] {
  background-color: #04AA6D;
  color: white;
  padding: 12px 20px;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  float: right;
}

input[type=submit]:hover {
  background-color: #45a049;
}

.container {
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px;
}

.col-25 {
  float: left;
  width: 25%;
  margin-top: 6px;
}

.col-75 {
  float: left;
  width: 75%;
  margin-top: 6px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive layout - when the screen is less than 600px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .col-25, .col-75, input[type=submit] {
    width: 100%;
    margin-top: 0;
  }
}
</style>
</head>
<body>

<h2>Review Form</h2>

<div class="container">
  <form action="/action_page.php">
    <div class="row">
      <div class="col-25">
        <label for="fname">First Name</label>
      </div>
      <div class="col-75">
        <input type="text" id="fname" name="firstname" placeholder="Your name..">
      </div>
    </div>
    <div class="row">
      <div class="col-25">
        <label for="lname">Last Name</label>
      </div>
      <div class="col-75">
        <input type="text" id="lname" name="lastname" placeholder="Your last name..">
      </div>
    </div>
    <div class="row">
      <div class="col-25">
        <label for="country">Country</label>
      </div>
      <div class="col-75">
        <select id="country" name="country">
          <option value="australia">Australia</option>
          <option value="canada">Sri Lanka</option>
          <option value="usa">India</option>
        </select>
      </div>
    </div>
    <div class="row">
      <div class="col-25">
        <label for="subject">Add Your Review Good & Bad</label>
      </div>
      <div class="col-75">
        <textarea id="subject" name="subject" placeholder="Write something.." style="height:200px"></textarea>
      </div>
    </div>
    <div class="row">
      <input type="submit" value="Submit">
    </div>
  </form>
</div>

</body>
</html>

  <!-- The Contact Section -->
  <div class="w3-container w3-content w3-padding-64" style="max-width:800px" id="contact">
    <h2 class="w3-wide w3-center">CONTACT</h2>
    <p class="w3-opacity w3-center"><i>Fan? Drop a note!</i></p>
    <div class="w3-row w3-padding-32">
      <div class="w3-col m6 w3-large w3-margin-bottom">
        <i class="fa fa-map-marker" style="width:30px"></i> Chicago, US<br>
        <i class="fa fa-phone" style="width:30px"></i> Phone: +00 151515<br>
        <i class="fa fa-envelope" style="width:30px"> </i> Email: mail@mail.com<br>
      </div>
      <div class="w3-col m6">
        <form action="/action_page.php" target="_blank">
          <div class="w3-row-padding" style="margin:0 -16px 8px -16px">
            <div class="w3-half">
              <input class="w3-input w3-border" type="text" placeholder="Name" required name="Name">
            </div>
            <div class="w3-half">
              <input class="w3-input w3-border" type="text" placeholder="Email" required name="Email">
            </div>
          </div>
          <input class="w3-input w3-border" type="text" placeholder="Message" required name="Message">
          <button class="w3-button w3-black w3-section w3-right" type="submit">SEND</button>
        </form>
      </div>
    </div>
  </div>
  
<!-- End Page Content -->
</div>

<!-- Image of location/map -->
<img src="/w3images/map.jpg" class="w3-image w3-greyscale-min" style="width:100%">

<!-- Footer -->
<footer class="w3-container w3-padding-64 w3-center w3-opacity w3-light-grey w3-xlarge">
  <i class="fa fa-facebook-official w3-hover-opacity"></i>
  <i class="fa fa-instagram w3-hover-opacity"></i>
  <i class="fa fa-snapchat w3-hover-opacity"></i>
  <i class="fa fa-pinterest-p w3-hover-opacity"></i>
  <i class="fa fa-twitter w3-hover-opacity"></i>
  <i class="fa fa-linkedin w3-hover-opacity"></i>
  <p class="w3-medium">Powered by <a href="https://www.w3schools.com/w3css/default.asp" target="_blank">w3.css</a></p>
</footer>

<script>
// Automatic Slideshow - change image every 4 seconds
var myIndex = 0;
carousel();

function carousel() {
  var i;
  var x = document.getElementsByClassName("mySlides");
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";  
  }
  myIndex++;
  if (myIndex > x.length) {myIndex = 1}    
  x[myIndex-1].style.display = "block";  
  setTimeout(carousel, 4000);    
}

// Used to toggle the menu on small screens when clicking on the menu button
function myFunction() {
  var x = document.getElementById("navDemo");
  if (x.className.indexOf("w3-show") == -1) {
    x.className += " w3-show";
  } else { 
    x.className = x.className.replace(" w3-show", "");
  }
}

// When the user clicks anywhere outside of the modal, close it
var modal = document.getElementById('ticketModal');
window.onclick = function(event) {
  if (event.target == modal) {
    modal.style.display = "none";
  }
}
</script>

</body>
</html>
 
