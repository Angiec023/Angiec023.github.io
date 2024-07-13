<!DOCTYPE html>
<html>
<head>
    <title>Filigrana Designs</title>
    <link rel="stylesheet" href="CSS/cardstyle.css"/>

    <!-- UIkit CSS -->
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/uikit@3.17.8/dist/css/uikit.min.css" />
    
    <!-- UIkit JS -->
    <script src="https://cdn.jsdelivr.net/npm/uikit@3.17.11/dist/js/uikit.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/uikit@3.17.11/dist/js/uikit-icons.min.js"></script>
    
    <style>
        /* Additional CSS for styling */
        body {
            font-family: Arial, sans-serif; /* Set a default font */
            margin: 0; /* Remove default margin */
            padding: 0; /* Remove default padding */
            background-color: #f0f0f0; /* Light background color */
        }

        .navbar {
            background-color: #333; /* Dark background color */
            overflow: hidden; /* Clear floats */
            text-align: center; /* Center align text */
            padding: 10px 0; /* Padding top and bottom */
        }

        .navbar a {
            color: white; /* Text color */
            text-decoration: none; /* Remove underline */
            padding: 14px 20px; /* Padding */
            display: inline-block; /* Display as block element */
        }

        .navbar a:hover {
            background-color: #ddd; /* Darken background on hover */
            color: black; /* Change text color on hover */
        }

        .content {
            background-color: #e6e6fa; /* Light purple background */
            padding: 20px; /* Add padding to content */
            text-align: center; /* Center align text */
        }

        .section {
            margin-top: 50px; /* Add top margin to sections */
            padding: 20px; /* Add padding to sections */
            background-color: #fff; /* White background for sections */
            box-shadow: 0 4px 8px rgba(0,0,0,0.1); /* Box shadow for sections */
        }

        .section h2 {
            color: #4B0082; /* Purple heading color */
        }

        .section img {
            margin-top: 20px; /* Add top margin to images */
            display: block; /* Make images block elements */
            margin-left: auto; /* Center align images horizontally */
            margin-right: auto; /* Center align images horizontally */
        }

        .content ul {
            list-style-type: none; /* Remove default bullet points */
            text-align: left; /* Align list items to the left */
            padding-left: 0; /* Remove default left padding */
        }

        .content ul li {
            text-align: center; /* Center align list items */
            margin-bottom: 10px; /* Add bottom margin to separate list items */
        }

        .content ul li:before {
            font-weight: bold; /* Make text before colon bold */
            content: attr(data-title); /* Set content as data attribute */
        }

        .contact {
            background-color: #4B0082; /* Dark purple background */
            color: white; /* Text color */
            padding: 40px; /* Padding top and bottom */
            text-align: center; /* Center align text */
            margin: 0 auto; /* Center the box horizontally */
            max-width: 600px; /* Limit maximum width of the box */
            border-radius: 10px; /* Rounded corners */
            box-shadow: 0 4px 8px rgba(0,0,0,0.2); /* Box shadow for box */
        }

        .contact p {
            font-size: 18px; /* Font size for the message */
            margin-bottom: 20px; /* Bottom margin for spacing */
        }

        .contact a {
            color: #fff; /* Link color */
            text-decoration: none; /* Remove underline */
            font-weight: bold; /* Bold font weight */
            padding: 10px 20px; /* Padding for the link */
            background-color: #8A2BE2; /* Background color for the link */
            border-radius: 5px; /* Rounded corners */
            transition: background-color 0.3s ease; /* Smooth transition for background color */
        }

        .contact a:hover {
            background-color: #6A1B9A; /* Darker background on hover */
        }
    </style>
</head>
<body>

    <div class="navbar">
        <a href="#Graduation" uk-scroll>Graduation</a>
        <a href="#Congratulations" uk-scroll>Congratulations</a>
        <a href="#Holiday" uk-scroll>Holiday</a>
        <a href="#Birthday" uk-scroll>Birthday</a>
        <a href="#Babyshower" uk-scroll>Babyshower</a>
    </div>

    <div class="content">
        

        <p><h1>Discover Personalized Themed Cards</h1></p>

        <p>Welcome to our world of personalized themed cards, where each creation is a testament to craftsmanship and personal touch. Explore a diverse range of themes designed to enrich every special occasion:</p>

        <ul>
            <li data-title="Weddings:"> Celebrate your love story with our elegant wedding cards, tailored to reflect your unique journey together.</li>
            <li data-title="Birthdays:"> Make birthdays unforgettable with our vibrant and creative birthday cards, personalized to suit the personality of the recipient.</li>
            <li data-title="Graduations:"> Honor academic achievements with our stylish graduation cards, capturing the spirit of accomplishment and new beginnings.</li>
            <li data-title="Baby Showers:"> Welcome the newest addition to the family with our charming baby shower cards, customized to convey your heartfelt joy and anticipation.</li>
        </ul>

        <p>We believe every moment deserves to be celebrated uniquely. That’s why we offer personalized options, allowing you to add your personal flair to each card. Whether it’s custom messages, intricate designs, or special embellishments, we are dedicated to creating cards that perfectly reflect your sentiment.</p>

        <p>Explore our collection today and discover how we can help you celebrate life’s precious moments with style and heartfelt sincerity.</p>
    </div>

    <div class="section" id="Graduation">
        <h2>Graduation</h2>
        <img src="Image/graduation.jpg" alt="graduation" width="300" />
        <p>Price:$$</p>
    </div>

    <div class="section" id="Congratulations">
        <h2>Congratulations</h2>
        <img src="Image/Congrats.jpeg" alt="Congratulations" width="300" />
         <p>Price:$$</p>
    </div>

    <div class="section" id="Holiday">
        <h2>Holiday</h2>
        <img src="Image/christmas.jpeg" alt="Holiday" width="300" />
        <img src="Image/x-mas.jpeg" alt="Holiday" width="300" />
         <p>Price:$$</p>
    </div>

    <div class="section" id="Birthday">
        <h2>Birthday</h2>
        <img src="Image/bday.jpeg" alt="Birthday" width="300" />
        <img src="Image/birthday.jpeg" alt="Birthday" width="300" />
         <p>Price:$$</p>
    </div>

    <div class="section" id="Babyshower">
        <h2>Babyshower</h2>
        <img src="Image/baby1.jpeg" alt="Babyshower" width="300" />
         <p>Price:$$</p>
        <img src="Image/baby2.jpeg" alt="Babyshower" width="300" />
         <p>Price:$$</p>
    </div>

    <!-- Contact Section -->
    <div class="contact">
        <p>Interested in discussing personalized items? Contact us today!</p>
        <a href="mailto:angiechanaga23@gmail.com">Contact Us</a>
    </div>

</body>
</html>

/* Reset default margin and padding */
body, html {
    margin: 0;
    padding: 0;
}

/* Body styles */
body {
    font-family: Arial, sans-serif;
    background-color: #E6E6FA; /* Light purple background */
    color: #4B0082; /* Very dark purple lettering */
    text-align: center; /* Centered text */
}

/* Paragraph styles */
p {
    margin: 20px 0;
    line-height: 1.6;
}

/* Anchor (link) styles */
a.uk-button {
    display: inline-block;
    margin: 10px;
    padding: 10px 20px;
    background-color: #F5F5DC; /* Beige scroll color */
    color: #8B4513; /* Brown text color */
    border-radius: 5px;
    text-decoration: none;
    transition: background-color 0.3s ease;
}

a.uk-button:hover {
    background-color: #D2B48C; /* Lighter beige on hover */
}

/* Section styles */
#Filigran {
    margin-top: 30px;
}

/* Heading styles */
h2 {
    font-weight: bold;
    color: #4B0082; /* Very dark purple for headings */
    margin-bottom: 10px;
}

/* Image styles */
img {
    display: block;
    margin: 0 auto;
    width: 300px;
    height: auto;
    border-radius: 10px;
    margin-bottom: 20px;
}

/* Reset default margin and padding */
body, html {
    margin: 0;
    padding: 0;
    font-family: Arial, sans-serif;
    background-color: #E6E6FA; /* Light purple background */
    color: #4B0082; /* Very dark purple lettering */
    text-align: center; /* Centered text */
}

/* Paragraph styles */
p {
    margin: 20px 0;
    line-height: 1.6;
}

/* Anchor (link) styles */
a.uk-button {
    display: inline-block;
    margin: 10px;
    padding: 10px 20px;
    background-color: #F5F5DC; /* Beige scroll color */
    color: #8B4513; /* Brown text color */
    border-radius: 5px;
    text-decoration: none;
    transition: background-color 0.3s ease;
}

a.uk-button:hover {
    background-color: #D2B48C; /* Lighter beige on hover */
}

/* Section styles */
#Filigran {
    margin-top: 30px;
    text-align: left; /* Adjust text alignment */
}

/* Heading styles */
h2, h3 {
    font-weight: bold;
    color: #4B0082; /* Very dark purple for headings */
    margin-bottom: 10px;
}

/* Image styles */
img {
    display: block;
    margin: 0 auto;
    width: 300px;
    height: auto;
    border-radius: 10px;
    margin-bottom: 20px;
}
.content ul {
            list-style-type: none; /* Remove default bullet points */
            text-align: left; /* Align list items to the left */
            padding-left: 0; /* Remove default left padding */
        }

        .content ul li {
            text-align: center; /* Center align list items */
            margin-bottom: 10px; /* Add bottom margin to separate list items */
        }

        .content ul li:before {
            font-weight: bold; /* Make text before colon bold */
            content: attr(data-title); /* Set content as data attribute */
        }

        .section img {
    margin-top: 20px;
    display: block;
    margin-left: auto;
    margin-right: auto;
    border-radius: 5px; /* Adjust this value to make the border softer */
}
.section {
    margin-top: 50px;
    padding: 20px;
    background-color: #fff; /* White background for sections */
    box-shadow: 0 4px 8px rgba(0,0,0,0.1); /* Box shadow for sections */
}

h1 {
  position: relative;
  padding-left: 110px;
  display: inline-block;
  background: linear-gradient(180deg, #8A2BE2, #4B0082); /* Gradient background */
  color: #fff;
  text-align: center; /* Center align text */
  font-size: 3.8rem; /* Adjust font size */
  padding: 20px; /* Add padding */
}

h1 {
  position: relative;
  padding-left: 110px;
  display: inline-block;
  background: url('../Image/flower.png') left center no-repeat;
  background-size: 100px 80px;
  color: #fff;
}

h1::before,
h1::after {
  content: '';
  position: absolute;
  top: 0;
  width: 50%; /* Split the background into two halves */
  height: 100%;
  background: linear-gradient(180deg, rgba(0,0,0,0.5), rgba(0,0,0,0.5));
  z-index: -1;
}

h1::before {
  left: 0;
}

h1::after {
  right: 0;
}
![baby1](https://github.com/user-attachments/assets/63582fb3-07c8-4a65-8250-f2f0e7418f68)
![baby2](https://github.com/user-attachments/assets/ea4f92a9-b6f0-43a6-bc28-a5506fddd21c)

![x-mas](https://github.com/user-attachments/assets/0d78b379-f115-4793-a828-a2f3ba91795e)
708-4b![graduation](https://github.com/user-attachments/assets/5eb74fab-aab3-4e66-9242-708e4a296928)
26-b29e-bdade3422604)
[birthday](https://github.com/user-attachments/assets/497eeac3-2670-427b-8775-849493e4ce04)
-919a-f1907ad8f8d2)![christmas](https://github.com/user-attachments/assets/a60760ce-546a-465e-b71e-d74d04070033)

![flower](https://github.com/user-attachments/assets/d5ebc8c1-7598-42d8-badf-35472671e99f)
![bday](https://github.com/user-attachments/assets/721c0494-7093-4afe-97c0-000dd6d1424d)
![bday](https://github.com/user-attachments/assets/470f9a30-174b-42c8-bc2d-cd92768b3167)
