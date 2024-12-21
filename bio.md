<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ariel Onnis - Personal Bio</title>
    <style>
        :root {
            --primary-color: #1e2a47;
            --secondary-color: #2ea043;
            --text-color: #555;
            --bg-color: #f4f7f6;
            --card-bg: #ffffff;
        }

   body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, sans-serif;
            line-height: 1.8;
            margin: 0;
            padding: 20px;
            background-color: var(--bg-color);
            color: var(--text-color);
        }

 .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 40px;
            background: var(--card-bg);
            border-radius: 12px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
        }

   h1, h2 {
            color: var(--primary-color);
            border-bottom: 2px solid var(--secondary-color);
            padding-bottom: 8px;
            margin-top: 30px;
        }

   h1 {
            font-size: 2.5em;
            margin-bottom: 20px;
        }

   h2 {
            font-size: 1.8em;
            margin-top: 40px;
        }

   p {
            font-size: 1.1em;
            margin-bottom: 20px;
        }

   .highlight {
            color: var(--secondary-color);
            font-weight: 600;
        }

   .social-links, .tools {
          display: flex;
            gap: 20px;
            flex-wrap: wrap;
            justify-content: flex-start;
            margin: 25px 0;
            padding: 15px 0;
        }

   .social-links a, .tools a {
            display: flex;
            align-items: center;
            text-decoration: none;
            color: var(--text-color);
            transition: transform 0.3s ease, filter 0.3s ease;
        }

   .social-links img, .tools img {
            width: 40px;
            height: 40px;
            transition: transform 0.3s ease;
            filter: grayscale(20%);
        }

   .social-links a:hover img, .tools a:hover img {
            transform: translateY(-5px);
            filter: grayscale(0%);
        }

   .tools img {
            width: 45px;
            height: 45px;
        }

   .footer {
            text-align: center;
            margin-top: 40px;
            padding-top: 20px;
            border-top: 1px solid #eee;
            font-size: 1.2em;
        }
        @media (max-width: 600px) {
            .container {
                padding: 20px;
            }
        
   .social-links, .tools {
                justify-content: center;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Hey there! 👋</h1>
        <p>I'm <a href="https://www.linkedin.com/in/onnis/" target="_blank">Ariel Onnis</a>, a Quality Assurance (QA) Engineer and Lawyer dedicated to building reliable, high-quality applications. I bring a unique perspective by combining technical expertise with legal knowledge, focusing on creating trustworthy digital solutions.</p>
   <h2>🚀 About Me</h2>
        <p>As the co-founder of <a href="https://www.certainty.solutions" target="_blank">Certainty Solutions</a>, I lead initiatives in data compliance, human rights audits, and tech & data advisory. With over two decades of technology experience and a deep focus on AI-driven compliance solutions, I'm passionate about building trust in the digital age. My work centers on creating bridges between legal requirements and technical implementations.</p>

   <h2>🛠️ Tech Stack & Tools</h2>
        <div class="tools">
            <a href="#" title="VS Code"><img src="https://upload.wikimedia.org/wikipedia/commons/9/9a/Visual_Studio_Code_1.35_icon.svg" alt="VS Code"></a>
            <a href="#" title="Python"><img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg" alt="Python"></a>
            <a href="#" title="JavaScript"><img src="https://upload.wikimedia.org/wikipedia/commons/6/6a/JavaScript-logo.png" alt="JavaScript"></a>
            <a href="#" title="Playwright"><img src="https://playwright.dev/img/playwright-logo.svg" alt="Playwright"></a>
            <a href="#" title="Power BI"><img src="https://upload.wikimedia.org/wikipedia/commons/c/cf/New_Power_BI_Logo.svg" alt="Power BI"></a>
        </div>

   <h2>🤝 Let's Connect</h2>
        <div class="social-links">
            <a href="https://www.linkedin.com/in/onnis/" target="_blank" title="LinkedIn">
                <img src="https://content.linkedin.com/content/dam/me/business/en-us/amp/brand-site/v2/bg/LI-Bug.svg.original.svg" alt="LinkedIn">
            </a>
            <a href="https://wa.me/+541161179711" target="_blank" title="WhatsApp">
                <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp">
            </a>
            <a href="mailto:arielonnis@gmail.com" target="_blank" title="Email">
                <img src="https://upload.wikimedia.org/wikipedia/commons/7/7e/Gmail_icon_%282020%29.svg" alt="Gmail">
            </a>
        </div>

   <div class="footer">
            Let's collaborate on making technology more reliable and compliant! 💡
        </div>
    </div>
</body>
</html>
