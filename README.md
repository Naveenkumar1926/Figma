# Ex09 Event Registration Web Application
## Date: 18/12/2024

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
html code

<div class="container--0-">
  <img
    src="data:image.png;"
  /><img
    src="data:image.png;"
  /><svg
    width="257"
    height="52"
    viewBox="0 0 257 52"
    
  >
    <g filter="url(#filter0_i_2_11)">
      <rect width="257" height="52" fill="#C3C540"></rect>
    </g>
    <defs>
      <filter
        id="filter0_i_2_11"
        x="0"
        y="0"
        width="257"
        height="56"
        filterUnits="userSpaceOnUse"
        color-interpolation-filters="sRGB"
      >
        <feFlood flood-opacity="0" result="BackgroundImageFix"></feFlood>
        <feBlend
          mode="normal"
          in="SourceGraphic"
          in2="BackgroundImageFix"
          result="shape"
        ></feBlend>
        <feColorMatrix
          in="SourceAlpha"
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
          result="hardAlpha"
        ></feColorMatrix>
        <feOffset dy="4"></feOffset>
        <feGaussianBlur stdDeviation="2"></feGaussianBlur>
        <feComposite
          in2="hardAlpha"
          operator="arithmetic"
          k2="-1"
          k3="1"
        ></feComposite>
        <feColorMatrix
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"
        ></feColorMatrix>
        <feBlend
          mode="normal"
          in2="shape"
          result="effect1_innerShadow_2_11"
        ></feBlend>
      </filter>
    </defs>
  </svg>
  <div class="text-0-1-3">REGISTER</div>
  <img
    src="data:image.jpeg;"
  /><svg
    width="265"
    height="48"
    viewBox="0 0 265 48"
    
  >
    <g filter="url(#filter0_i_2_16)">
      <rect width="265" height="48" fill="#BCA221"></rect>
    </g>
    <defs>
      <filter
        id="filter0_i_2_16"
        x="0"
        y="0"
        width="265"
        height="52"
        filterUnits="userSpaceOnUse"
        color-interpolation-filters="sRGB"
      >
        <feFlood flood-opacity="0" result="BackgroundImageFix"></feFlood>
        <feBlend
          mode="normal"
          in="SourceGraphic"
          in2="BackgroundImageFix"
          result="shape"
        ></feBlend>
        <feColorMatrix
          in="SourceAlpha"
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"
          result="hardAlpha"
        ></feColorMatrix>
        <feOffset dy="4"></feOffset>
        <feGaussianBlur stdDeviation="2"></feGaussianBlur>
        <feComposite
          in2="hardAlpha"
          operator="arithmetic"
          k2="-1"
          k3="1"
        ></feComposite>
        <feColorMatrix
          type="matrix"
          values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"
        ></feColorMatrix>
        <feBlend
          mode="normal"
          in2="shape"
          result="effect1_innerShadow_2_16"
        ></feBlend>
      </filter>
    </defs>
  </svg>
  <div class="text-0-1-7">LOGIN</div>
</div>

css 

.container--0- {
  position: absolute;
  left: 583px;
  top: -571px;
  width: 384px;
  height: 940px;
  background-color: #ca1313;
  justify-content: start;
  align-items: start;
}
.text-0-1-3 {
  width: 237px;
  height: 47px;
  color: #000000;
  font-size: 32px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-7 {
  width: 153px;
  height: 45px;
  color: #000000;
  font-size: 32px;
  font-family: Inter, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}

html code

<div class="container--0-">
  <img
    src="data:image.jpeg;"
  />
  <div class="text-0-1-1">
    SPORTS DAY <br />
    EVENTS
  </div>
  <div class="text-0-1-2">
    CRICKET<br /><br />FOOTBALL<br /><br />VOLLEY BALL<br /><br />THROW BALL<br /><br />BASKETBALL<br /><br />WWE
  </div>
</div>

css

.container--0- {
  position: absolute;
  left: 1042px;
  top: -579px;
  width: 394px;
  height: 948px;
  background-color: #ffffff;
  justify-content: start;
  align-items: start;
}
.text-0-1-1 {
  width: 260px;
  height: 81px;
  color: #000000;
  font-size: 32px;
  font-family: Jersey 10, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}
.text-0-1-2 {
  width: 189px;
  height: 404px;
  color: #ffffff;
  font-size: 32px;
  font-family: Jersey 10, "Regular";
  font-weight: 400;
  text-align: left;
  vertical-align: top;
}

html & css code 

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Event Registration Form</title>
    <style>
        /* General reset */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: Arial, sans-serif;
        }

        /* Body background and container */
        body {
            background-color: black;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }

        .container {
            position: relative;
            width: 400px;
            height: 750px;
            background: url('https://example.com/ship-background.jpg') no-repeat center center/cover;
            border-radius: 30px;
            box-shadow: 0 0 15px rgba(255, 255, 255, 0.3);
            overflow: hidden;
            text-align: center;
        }

        /* Form Title */
        .form-title {
            color: white;
            margin-top: 30px;
            font-size: 1.8em;
            text-shadow: 1px 1px 2px black;
        }

        .form-subtitle {
            color: red;
            margin: 10px 0;
            font-style: italic;
        }

        /* Form Styling */
        form {
            display: flex;
            flex-direction: column;
            align-items: center;
            margin-top: 20px;
        }

        input {
            width: 80%;
            margin: 10px 0;
            padding: 10px;
            border: none;
            border-radius: 5px;
            font-size: 1em;
            text-align: center;
            background: rgba(0, 0, 0, 0.8);
            color: white;
        }

        input::placeholder {
            color: #ccc;
        }

        /* Register Button */
        .register-btn {
            margin-top: 10px;
            background-color: black;
            color: yellow;
            font-size: 1.2em;
            padding: 10px 20px;
            border: 2px solid yellow;
            border-radius: 5px;
            cursor: pointer;
            transition: 0.3s ease;
            text-transform: uppercase;
        }

        .register-btn:hover {
            background-color: yellow;
            color: black;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1 class="form-title">EVENT REGISTRATION FORM</h1>
        <h2 class="form-subtitle">Fill the Details</h2>
        <form>
            <input type="text" placeholder="Full Name" required>
            <input type="text" placeholder="Gender" required>
            <input type="number" placeholder="Age" required>
            <input type="text" placeholder="Registration No" required>
            <input type="text" placeholder="Department" required>
            <input type="tel" placeholder="Mobile No" required>
            <input type="email" placeholder="Email id" required>
            <button type="submit" class="register-btn">Register</button>
        </form>
    </div>
</body>
</html>

css code 

/* General Reset */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

/* Full Page Background */
body {
    background-color: black;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    color: white;
}

.container {
    position: relative;
    width: 400px;
    height: 750px;
    background: url('red-background.jpg') no-repeat center center/cover;
    text-align: center;
    border-radius: 30px;
    box-shadow: 0 0 15px rgba(255, 255, 255, 0.3);
    overflow: hidden;
}

/* Header */
.header {
    margin-top: 10px;
    color: yellow;
}

.header .college-logo img {
    width: 50px;
    position: absolute;
    left: 15px;
    top: 15px;
}

.header h1 {
    font-size: 1.2em;
    text-transform: uppercase;
}

.header h2 {
    font-size: 0.8em;
    margin: 5px 0;
    text-transform: uppercase;
}

.header h3 {
    font-size: 0.9em;
}

.header .tnea-code {
    color: blue;
}

/* Thank You Message */
.content {
    margin-top: 120px;
}

.thank-you {
    font-size: 2.5em;
    margin-bottom: 20px;
}

.waiting-message {
    font-size: 1.2em;
    line-height: 1.5;
}

/* Contact Section */
.contact-us {
    position: absolute;
    bottom: 20px;
    text-align: center;
    width: 100%;
}

.contact-us h2 {
    font-size: 1.5em;
    margin-bottom: 10px;
}

.contact-us p {
    font-size: 1em;
    line-height: 1.5;
}

.contact-us a {
    color: white;
    text-decoration: underline;
}

html code

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thank You Page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <!-- Top Banner -->
        <div class="header">
            <div class="college-logo">
                <img src="logo.png" alt="College Logo" />
            </div>
            <div class="college-details">
                <h1>SAVEETHA ENGINEERING COLLEGE</h1>
                <h2>AFFILIATED TO ANNA UNIVERSITY</h2>
                <h3>AUTONOMOUS | TNEA CODE <span class="tnea-code">1216</span></h3>
            </div>
        </div>

        <!-- Thank You Message -->
        <div class="content">
            <h1 class="thank-you">THANK YOU</h1>
            <p class="waiting-message">
                We are all eagerly waiting <br />
                for your participation <br />
                in the sports events
            </p>
        </div>

        <!-- Contact Us Section -->
        <div class="contact-us">
            <h2>CONTACT US</h2>
            <p>Email: <a href="mailto:saveethaengineering@gmail.com">saveethaengineering@gmail.com</a></p>
            <p>Phone: 98202828238</p>
        </div>
    </div>
</body>
</html>

```




## OUTPUT:

![alt text](<Screenshot 2024-12-18 132544.png>)
![alt text](<Screenshot (5).png>)
![alt text](<Screenshot (6).png>)
![alt text](<Screenshot (7).png>)


## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
