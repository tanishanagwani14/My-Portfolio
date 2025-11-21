<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tanisha Nagwani | Portfolio</title>
    <style>
        /* --- CSS Styles --- */
        :root {
            --primary-color: #2c3e50; /* Dark Blue */
            --secondary-color: #3498db; /* Light Blueish */
            --accent-color: #e74c3c; /* Red for highlights */
            --bg-light: #f4f7f6;
            --text-dark: #333;
        }

        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: var(--text-dark);
            background-color: var(--bg-light);
        }

        /* Container for central alignment */
        .container {
            width: 90%;
            max-width: 1100px;
            margin: auto;
            padding: 20px;
        }

        /* Header Section */
        header {
            background: var(--primary-color);
            color: white;
            padding: 3rem 0;
            text-align: center;
        }

        header h1 {
            font-size: 3rem;
            margin-bottom: 10px;
        }

        header p {
            font-size: 1.2rem;
            opacity: 0.9;
        }

        /* General Section Styles */
        section {
            padding: 3rem 0;
            border-bottom: 1px solid #ddd;
        }

        section h2 {
            text-align: center;
            font-size: 2rem;
            margin-bottom: 2rem;
            color: var(--primary-color);
            text-transform: uppercase;
            letter-spacing: 1px;
        }

        section h3 {
            color: var(--secondary-color);
            margin: 1.5rem 0 1rem 0;
            font-size: 1.5rem;
            border-left: 5px solid var(--secondary-color);
            padding-left: 10px;
        }

        /* About Section Styles */
        .about-content {
            text-align: center;
            font-size: 1.1rem;
            max-width: 800px;
            margin: auto;
        }

        .highlight {
            color: var(--secondary-color);
            font-weight: bold;
        }

        /* Social Links Styles */
        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 2rem;
            list-style: none;
        }

        .social-btn {
            display: inline-block;
            padding: 10px 25px;
            background-color: var(--primary-color);
            color: white;
            text-decoration: none;
            border-radius: 5px;
            transition: background-color 0.3s ease;
            font-weight: bold;
        }

        .social-btn:hover {
            background-color: var(--secondary-color);
        }
        
        .social-btn.leet { background-color: #f39c12; } /* Orange for Leetcode styling */
        .social-btn.leet:hover { background-color: #d68910; }


        /* Video Grid Styles */
        .video-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(200px, 1fr));
            gap: 15px;
            margin-bottom: 2rem;
        }

        .video-card {
            background: white;
            border: 1px solid #ddd;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            transition: transform 0.2s, box-shadow 0.2s;
            text-align: center;
        }

        .video-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 5px 15px rgba(0,0,0,0.2);
            border-color: var(--secondary-color);
        }

        .video-card a {
            display: block;
            padding: 20px 10px;
            text-decoration: none;
            color: var(--primary-color);
            font-weight: 600;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 2rem;
            background: var(--primary-color);
            color: white;
            margin-top: 2rem;
        }
    </style>
</head>
<body>

    <header>
        <div class="container">
            <h1>Tanisha Nagwani</h1>
            <p>Integrated MCA Student | Developer | Problem Solver</p>
        </div>
    </header>

    <section id="about">
        <div class="container">
            <h2>About Me</h2>
            <div class="about-content">
                <p>
                    Hello! I am Tanisha Nagwani. I am currently pursuing an <span class="highlight">Integrated MCA (5-year course)</span> from <span class="highlight">IIPS, DAVV</span>. 
                    I am currently in my <span class="highlight">5th Semester</span>, focused on honing my skills in software development and data structures.
                </p>
            </div>

            <ul class="social-links">
                <li><a href="https://www.linkedin.com/" target="_blank" class="social-btn">LinkedIn Profile</a></li>
                
                <li><a href="https://github.com/" target="_blank" class="social-btn">GitHub Profile</a></li>
                
                <li><a href="https://leetcode.com/" target="_blank" class="social-btn leet">LeetCode Account</a></li>
            </ul>
        </div>
    </section>

    <section id="videos">
        <div class="container">
            <h2>Video Solutions & Walkthroughs</h2>
            <p style="text-align: center; margin-bottom: 2rem;">Below are links to my YouTube video explanations for various academic assessments.</p>

            <h3>Internal 1 Solutions</h3>
            <div class="video-grid">
                <div class="video-card">
                    <a href="#" target="_blank">📺 Section A Solution</a>
                </div>
                <div class="video-card">
                    <a href="#" target="_blank">📺 Section B Solution</a>
                </div>
                <div class="video-card">
                    <a href="#" target="_blank">📺 Section C Solution</a>
                </div>
                <div class="video-card">
                    <a href="#" target="_blank">📺 Section D Solution</a>
                </div>
            </div>

            <h3>Internal 2 Solutions</h3>
            <div class="video-grid" style="grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));">
                <div class="video-card">
                    <a href="#" target="_blank">📺 Internal 2 Full Video Solution</a>
                </div>
            </div>

            <h3>Assignment Questions (10 Videos)</h3>
            <div class="video-grid">
                <div class="video-card"><a href="#" target="_blank">📺 Assignment Q1</a></div>
                <div class="video-card"><a href="#" target="_blank">📺 Assignment Q2</a></div>
                <div class="video-card"><a href="#" target="_blank">📺 Assignment Q3</a></div>
                <div class="video-card"><a href="#" target="_blank">📺 Assignment Q4</a></div>
                <div class="video-card"><a href="#" target="_blank">📺 Assignment Q5</a></div>
                <div class="video-card"><a href="#" target="_blank">📺 Assignment Q6</a></div>
                <div class="video-card"><a href="#" target="_blank">📺 Assignment Q7</a></div>
                <div class="video-card"><a href="#" target="_blank">📺 Assignment Q8</a></div>
                <div class="video-card"><a href="#" target="_blank">📺 Assignment Q9</a></div>
                <div class="video-card"><a href="#" target="_blank">📺 Assignment Q10</a></div>
            </div>

        </div>
    </section>

    <footer>
        <p>© 2023 Tanisha Nagwani. All rights reserved.</p>
    </footer>

</body>
</html>
