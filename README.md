# EX01 Developing a Simple Webserver

# Date:11-11-2024
# AIM:
To develop a simple webserver to serve html pages and display the configuration details of laptop.

# DESIGN STEPS:
## Step 1:
HTML content creation.

## Step 2:
Design of webserver workflow.

## Step 3:
Implementation using Python code.

## Step 4:
Serving the HTML pages.

## Step 5:
Testing the webserver.

# PROGRAM:
html file:

  <!DOCTYPE html>
  <html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Device Specifications</title>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <div class="container">
      <h1>Device Specifications</h1>
      <div class="spec-box">
        <div class="spec-item">
          <span class="spec-title">Device Name:</span>
          <span class="spec-detail">LAPTOP-OK438C1K</span>
        </div>
        <div class="spec-item">
          <span class="spec-title">Processor:</span>
          <span class="spec-detail">12th Gen Intel(R) Core(TM) i3-1215U 1.20 GHz</span>
        </div>
        <div class="spec-item">
          <span class="spec-title">Installed RAM:</span>
          <span class="spec-detail">8.00 GB (7.68 GB usable)</span>
        </div>
        <div class="spec-item">
          <span class="spec-title">Device ID:</span>
          <span class="spec-detail">FED1B711-7C21-464A-9BAA-30A98F1765ED</span>
        </div>
        <div class="spec-item">
          <span class="spec-title">Product ID:</span>
          <span class="spec-detail">00356-24754-57891-AAOEM</span>
        </div>
        <div class="spec-item">
          <span class="spec-title">System Type:</span>
          <span class="spec-detail">64-bit operating system, x64-based processor</span>
        </div>
        <div class="spec-item">
          <span class="spec-title">Pen and Touch:</span>
          <span class="spec-detail">No pen or touch input is available for this display</span>
        </div>
      </div>
    </div>
  </body>
  </html>


css file:
  /* General styles */
  body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color:lavender;
    }
    
    /* Container styling */
    .container {
      max-width: 800px;
      margin: 50px auto;
      padding: 20px;
      background-color:rosybrown;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
      border-radius: 8px;
    }
    
    /* Header styling */
    h1 {
      text-align: center;
      color:darkgreen;
      margin-bottom: 20px;
    }
    
    /* Specification box styling */
    .spec-box {
      border: 1px solid black;
      border-radius: 8px;
      padding: 20px;
    }
    
    /* Individual specification items */
    .spec-item {
      display: flex;
      justify-content: space-between;
      margin-bottom: 15px;
      padding: 10px;
      background-color:lightgoldenrodyellow;
      border-radius: 4px;
    }
    
    .spec-title {
      font-weight: bold;
      color: #333;
    }
    
    .spec-detail {
      color: #555;
    }
  
  
# OUTPUT:
![alt text](<Screenshot 2024-11-25 140407.png>)
# RESULT:
The program for implementing simple webserver is executed successfully.
