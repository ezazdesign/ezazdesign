- 👋 Hi, I’m @ezazdesign
- 👀 I’m interested in Web Development
- 🌱 I’m currently learning MERN
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
ezazdesign/ezazdesign is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Moriam Akter Swarna</title>
    <style>
        :root {
            --dark-bg: #0f0f12;
            --darker-bg: #0a0a0d;
            --text-color: #ffffff;
            --accent-color: #00c4ff;
            --accent-hover: #00e0ff;
            --red-color: #ff5555;
            --gray-color: #666666;
            --border-color: #333333;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            background-color: var(--dark-bg);
            color: var(--text-color);
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            padding: 20px;
            max-width: 1200px;
            margin: 0 auto;
        }

        .header {
            text-align: center;
            padding: 30px 0;
            border-bottom: 1px solid var(--border-color);
            margin-bottom: 30px;
        }

        .header h1 {
            font-size: 2.5rem;
            margin-bottom: 15px;
            color: var(--text-color);
        }

        .header h1 span {
            color: var(--accent-color);
        }

        .header p {
            font-size: 1.2rem;
            margin-bottom: 20px;
            color: var(--gray-color);
        }

        .social-links {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-top: 20px;
        }

        .social-btn {
            padding: 8px 15px;
            border-radius: 4px;
            font-weight: bold;
            text-decoration: none;
            display: inline-flex;
            align-items: center;
            gap: 5px;
        }

        .portfolio-btn {
            background-color: #1a1a1a;
            color: white;
            border: 1px solid #333;
        }

        .linkedin-btn {
            background-color: #0077b5;
            color: white;
        }

        .medium-btn {
            background-color: #000;
            color: white;
        }

        .email-btn {
            background-color: var(--red-color);
            color: white;
        }

        .social-btn:hover {
            opacity: 0.9;
            transform: translateY(-2px);
        }

        .title-section {
            text-align: center;
            margin: 40px 0;
        }

        .title-section h2 {
            font-size: 2.8rem;
            color: var(--accent-color);
            text-shadow: 0 0 10px rgba(0, 196, 255, 0.5);
            letter-spacing: 1px;
        }

        .section {
            margin: 40px 0;
            padding: 30px;
            background-color: var(--darker-bg);
            border-radius: 8px;
            border: 1px solid var(--border-color);
        }

        .section-header {
            display: flex;
            align-items: center;
            gap: 10px;
            margin-bottom: 20px;
            padding-bottom: 15px;
            border-bottom: 1px solid var(--border-color);
        }

        .section-header h3 {
            font-size: 1.8rem;
            color: var(--accent-color);
        }

        .content-container {
            display: flex;
            gap: 30px;
            flex-wrap: wrap;
        }

        .code-block {
            flex: 1;
            min-width: 300px;
            background-color: #121215;
            padding: 20px;
            border-radius: 8px;
            border: 1px solid var(--border-color);
            position: relative;
        }

        .copy-btn {
            position: absolute;
            top: 10px;
            right: 10px;
            background: none;
            border: none;
            cursor: pointer;
            color: var(--gray-color);
            font-size: 1.2rem;
        }

        .copy-btn:hover {
            color: var(--accent-color);
        }

        .code-block pre {
            overflow-x: auto;
            font-family: 'Courier New', Courier, monospace;
            font-size: 0.9rem;
            line-height: 1.5;
        }

        .code-block code {
            color: var(--text-color);
        }

        .keyword {
            color: #ff79c6;
        }

        .string {
            color: #f1fa8c;
        }

        .comment {
            color: #6272a4;
        }

        .property {
            color: #50fa7b;
        }

        .value {
            color: #bd93f9;
        }

        .right-column {
            flex: 1;
            min-width: 300px;
        }

        .what-i-do-item {
            margin-bottom: 25px;
            padding: 15px;
            background-color: #121215;
            border-radius: 8px;
            border: 1px solid var(--border-color);
        }

        .what-i-do-item h4 {
            display: flex;
            align-items: center;
            gap: 10px;
            margin-bottom: 10px;
            color: var(--accent-color);
        }

        .what-i-do-item h4::before {
            content: '';
            width: 20px;
            height: 20px;
            background-size: contain;
            background-repeat: no-repeat;
        }

        .what-i-do-item:nth-child(1) h4::before {
            background-image: url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyNCIgaGVpZ2h0PSIyNCIgdmlld0JveD0iMCAwIDI0IDI0Ij48cGF0aCBkPSJNMTIgMi41YzQuOTcgMCA5IDQuMDMgOSA5cy00LjAzIDktOSA5LTkgLTktOSAtOSA5IC05em0wIDEuNS0zLjQyIDMuNDJjLTAuODUgMC0xLjQyIDAuNTctMS40MiAxLjQydi44NGMwIDAuODUgMC41NyAxLjQyIDEuNDIgMS40MmMwLjg1IDAgMS40Mi0wLjU3IDEuNDItMS40MnYtLjg0YzAtMC44NS0wLjU3LTEuNDItMS40Mi0xLjQydjB6bTIuODQgMGwtMS40MiAxLjQydi44NGwxLjQyIDEuNDJjMC44NSAwIDEuNDItMC41NyAxLjQyLTEuNDJ2Ljg0YzAtMC44NS0wLjU3LTEuNDItMS40Mi0xLjQydjB6bS0yLjg0IDBoLjg0YzAuODUgMCAxLjQyLTAuNTcgMS40Mi0xLjQydjB6bTIuODQgMGwtMS40MiAxLjQ
