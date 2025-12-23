# Ex.06 Book Front Cover Page Design
# Date:
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
<html>
<head>
    <title>Book Cover</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            background: #f1f5f9;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            font-family: "Segoe UI", Tahoma, sans-serif;
        }
        .cover {
            width: 420px;
            height: 640px;
            background: linear-gradient(180deg, #0f172a, #2563eb);
            border-radius: 22px;
            padding: 30px;
            color: #ffffff;
            box-shadow: 0 20px 40px rgba(0, 0, 0, 0.35);
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }
        .badge {
            align-self: flex-start;
            padding: 8px 18px;
            border-radius: 25px;
            background: rgba(255, 255, 255, 0.15);
            backdrop-filter: blur(8px);
            font-size: 12px;
            font-weight: 600;
            letter-spacing: 1px;
            text-transform: uppercase;
        }
        .title-section {
            text-align: center;
            margin-top: 40px;
        }
        h1 {
            font-size: 38px;
            margin: 10px 0;
            font-weight: 700;
        }
        h2 {
            font-size: 18px;
            font-weight: 400;
            color: #e0e7ff;
            margin-bottom: 35px;
        }
        ul {
            list-style: none;
            padding: 0;
            margin: 0;
        }
        ul li {
            font-size: 15px;
            padding: 10px 0;
            border-bottom: 1px solid rgba(255, 255, 255, 0.2);
        }
        ul li:last-child {
            border-bottom: none;
        }
        .author-box {
            background: linear-gradient(90deg, #020617, #1e293b);
            border-radius: 16px;
            padding: 18px;
            display: flex;
            align-items: center;
            border-left: 5px solid #facc15;
        }
        .author-details h3 {
            margin: 0;
            font-size: 18px;
            font-weight: 600;
        }
        .author-details p {
            margin: 5px 0 0;
            font-size: 14px;
            color: #cbd5f5;
        }
    </style>
</head>
<body>
    <div class="cover">
        <div class="badge">Textbook Edition</div>
        <div class="title-section">
            <h1>Modern Web Design</h1>
            <h2>HTML, CSS & UI Development</h2>
        </div>
        <ul>
            <li>Aligned with Anna University syllabus</li>
            <li>Clear explanations with real examples</li>
            <li>Ideal for engineering students</li>
            <li>Exam-oriented structured content</li>
        </ul>
        <div class="author-box">
            <div class="author-details">
                <h3>Ponsriram P</h3>
                <p>Register No: 25011113</p>
            </div>
        </div>
    </div>
</body>
</html>
```

# OUTPUT:
<img width="1910" height="961" alt="image" src="https://github.com/user-attachments/assets/05a75425-8eda-425d-8a66-77a701a609d4" />

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
