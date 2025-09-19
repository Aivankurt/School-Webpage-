<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Sunnydale School</title>
  <style>
    
    <h1 {font-size: 24px;
      font-weight: bold;
      color: #1E90FF;}
  body {font-family: 'Arial', sans-serif;}

    <h2 {font-weight: bold;}

    <h2.mission {color: #32CD32; /green}

    <h2#upcoming-events {color: #FFA07A; /* salmon /background-color: #FFFFE0; / light yellow background */}

    <h2.contact {color: #20B2AA; /* light sea green */}

    .outdoor {background-color: #AFEEEE;
      padding: 5px; border: 1px solid #B0E0E6;}


    .section {background-color: #f8f3f3; padding: 10px;}
  </style>
</head>
<body>
  <h1>Sunnydale School</h1>

  <!-- Mission Statement -->
  <h2 class="mission">Mission Statement</h2>
  <p>At Sunnydale School, we are dedicated to fostering a love of learning, creativity, and community.</p>

  <!-- Upcoming Events -->
  <h2 id="upcoming-events">Upcoming Events</h2>
  <ul>
    <li data-event-type="indoor" title="Event Type: Indoor">
      Science Fair - <span style="font-weight: bold; color: red;">June 10</span>
    </li>
    <li data-event-type="outdoor" class="outdoor" title="Event Type: Outdoor">
      Art Exhibition - <span style="font-weight: bold; color: red;">June 15</span>
    </li>
    <li data-event-type="outdoor" class="outdoor" title="Event Type: Outdoor">
      Sports Day - <span style="font-weight: bold; color: red;">June 20</span>
    </li>
  </ul>

  <!-- Contact Us -->
  <h2 class="contact">Contact Us</h2>
  <div class="section">
    <p>Email: <a href="mailto:info@sunnydale.edu" title="Click to copy email">info@sunnydale.edu</a></p>
    <p>Phone: <a href="tel:+1234567890" title="Click to copy phone number">+1 234 567 890</a></p>
  </div>
  <!-- Imagine clicking here shows a message: "Thanks for reaching out!" -->

</body>
</html>
