<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background: #f9f9f9;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            color: #333;
        }
        .social-links img, .tools img {
            width: 50px;
            height: 50px;
            margin: 5px;
            transition: transform 0.2s;
        }
        .social-links img:hover, .tools img:hover {
            transform: scale(1.1);
        }
        .social-links, .tools {
            display: flex;
            gap: 10px;
            flex-wrap: wrap;
            justify-content: center;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Hey there! 👋</h1>
        <p>I'm Ariel, a passionate Quality Assurance (QA) Engineer and Lawyer committed to building reliable, high-quality applications. With a strong interest in data and a unique blend of expertise in both technology and law, I strive to bridge the gap between these fields.</p>

        <h2>About Me</h2>
        <div class="social-links">
            <a href="https://www.linkedin.com/in/onnis/"><img src="https://content.linkedin.com/content/dam/me/business/en-us/amp/brand-site/v2/bg/LI-Bug.svg.original.svg" alt="LinkedIn Logo"></a>
            <a href="https://wa.me/+541161179711"><img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp Logo"></a>
            <a href="mailto:arielonnis@gmail.com"><img src="https://upload.wikimedia.org/wikipedia/commons/7/7e/Gmail_icon_%282020%29.svg" alt="Gmail Logo"></a>
        </div>

        <h2>Some languages & Tools</h2>
        <div class="tools">
            <img src="https://upload.wikimedia.org/wikipedia/commons/9/9a/Visual_Studio_Code_1.35_icon.svg" alt="VS Code Logo">
            <img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg" alt="Python Logo">
            <img src="https://upload.wikimedia.org/wikipedia/commons/6/6a/JavaScript-logo.png" alt="JS Logo">
            <img src="https://playwright.dev/img/playwright-logo.svg" alt="Playwright Logo">
            <img src="https://upload.wikimedia.org/wikipedia/commons/c/cf/New_Power_BI_Logo.svg" alt="Power BI Logo">
        </div>

        <p>Let's talk! 💬📞🤝😉</p>
    </div>
</body>
</html>
