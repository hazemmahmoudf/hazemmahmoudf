<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hazem - Flutter Developer</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #0d1117;
            color: #c9d1d9;
            line-height: 1.6;
            padding: 20px;
            max-width: 900px;
            margin: 0 auto;
        }
        
        .container {
            background-color: #161b22;
            border-radius: 10px;
            padding: 30px;
            margin-top: 20px;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
        }
        
        header {
            text-align: center;
            padding: 20px 0;
        }
        
        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid #238636;
            margin: 0 auto 20px;
            display: block;
        }
        
        h1 {
            color: #f0f6fc;
            margin-bottom: 10px;
            font-size: 2.2rem;
        }
        
        h2 {
            color: #f0f6fc;
            margin: 25px 0 15px;
            padding-bottom: 8px;
            border-bottom: 2px solid #238636;
        }
        
        h3 {
            color: #f0f6fc;
            margin: 20px 0 10px;
        }
        
        p {
            margin-bottom: 15px;
        }
        
        .tagline {
            color: #8b949e;
            font-size: 1.2rem;
            margin-bottom: 25px;
        }
        
        .divider {
            height: 2px;
            background: linear-gradient(90deg, #238636, #161b22);
            margin: 30px 0;
            border: none;
        }
        
        .skills {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin: 15px 0;
        }
        
        .skill {
            background-color: #238636;
            color: white;
            padding: 6px 12px;
            border-radius: 20px;
            font-size: 0.9rem;
            display: flex;
            align-items: center;
        }
        
        .skill img {
            width: 20px;
            margin-right: 8px;
        }
        
        .stats {
            display: flex;
            gap: 20px;
            margin: 25px 0;
            flex-wrap: wrap;
        }
        
        .stat-box {
            flex: 1;
            min-width: 250px;
            background-color: #161b22;
            border: 1px solid #30363d;
            border-radius: 6px;
            padding: 15px;
        }
        
        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
            margin: 20px 0;
        }
        
        .project {
            background-color: #161b22;
            border: 1px solid #30363d;
            border-radius: 6px;
            padding: 15px;
            transition: transform 0.2s;
        }
        
        .project:hover {
            transform: translateY(-5px);
            border-color: #238636;
        }
        
        .project h3 {
            color: #58a6ff;
            margin-bottom: 10px;
        }
        
        .social-links {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 30px;
        }
        
        .social-link {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 50px;
            height: 50px;
            background-color: #161b22;
            border-radius: 50%;
            transition: all 0.3s;
        }
        
        .social-link:hover {
            background-color: #238636;
            transform: scale(1.1);
        }
        
        .social-link img {
            width: 24px;
            height: 24px;
        }
        
        .flag {
            display: inline-block;
            margin-left: 10px;
            font-size: 1.5rem;
            vertical-align: middle;
        }
        
        @media (max-width: 768px) {
            .stats {
                flex-direction: column;
            }
            
            .projects {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <header>
        <img class="profile-img" src="https://avatars.githubusercontent.com/u/123456789" alt="Hazem Mahmoud">
        <h1>Hazem Mahmoud</h1>
        <p class="tagline">Flutter Developer from Egypt 🇪🇬</p>
    </header>
    
    <div class="container">
        <h2>👋 About Me</h2>
        <p>I'm a passionate Flutter developer with experience in building cross-platform mobile applications. I enjoy creating clean, efficient code and solving complex problems.</p>
        
        <ul>
            <li>💻 Building apps with <strong>Flutter & Dart</strong></li>
            <li>📱 Experienced in <strong>Todo apps, News apps</strong>, and other Flutter projects</li>
            <li>❤️ Love writing clean code, solving problems & building interactive UIs</li>
            <li>💬 Ask me about <strong>Flutter, Dart, OpenGL, DSP</strong> or anything tech-related</li>
            <li>📫 Contact me via <a href="https://github.com/hazemmahmoudfathy/issues" style="color: #58a6ff;">GitHub Issues</a></li>
        </ul>
    </div>
    
    <hr class="divider">
    
    <div class="container">
        <h2>🛠 Technical Skills</h2>
        <div class="skills">
            <div class="skill">
                <img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/dart/dart.png" alt="Dart">
                Dart
            </div>
            <div class="skill">
                <img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/flutter/flutter.png" alt="Flutter">
                Flutter
            </div>
            <div class="skill">
                <img src="https://raw.githubusercontent.com/github/explore/06ce7c91f8f7a7bcb1c5a9b46b7d81f1e142a7e3/topics/cpp/cpp.png" alt="C++">
                C++
            </div>
            <div class="skill">
                <img src="https://raw.githubusercontent.com/github/explore/5c058a388828bb5fde0bcafd4bc867b5bb3f26f3/topics/opengl/opengl.png" alt="OpenGL">
                OpenGL
            </div>
            <div class="skill">
                <img src="https://raw.githubusercontent.com/github/explore/06ce7c91f8f7a7bcb1c5a9b46b7d81f1e142a7e3/topics/python/python.png" alt="Python">
                Python
            </div>
        </div>
    </div>
    
    <hr class="divider">
    
    <div class="container">
        <h2>📊 GitHub Stats</h2>
        <div class="stats">
            <div class="stat-box">
                <h3>Profile Stats</h3>
                <p>Commits: 542</p>
                <p>Repositories: 18</p>
                <p>Contributions: 327</p>
            </div>
            <div class="stat-box">
                <h3>Top Languages</h3>
                <p>Dart: 65%</p>
                <p>C++: 20%</p>
                <p>Python: 10%</p>
                <p>Other: 5%</p>
            </div>
        </div>
    </div>
    
    <hr class="divider">
    
    <div class="container">
        <h2>📂 Top Projects</h2>
        <div class="projects">
            <div class="project">
                <h3>TodoApp-Flutter</h3>
                <p>A feature-rich Todo application built with Flutter with local storage and beautiful UI.</p>
                <p><strong>Tech:</strong> Flutter, Dart, Hive</p>
                <a href="https://github.com/hazemmahmoudfathy/TodoApp-Flutter" style="color: #58a6ff;">View Project →</a>
            </div>
            <div class="project">
                <h3>NewsApp-Flutter</h3>
                <p>A news application that fetches latest news from various sources with category filtering.</p>
                <p><strong>Tech:</strong> Flutter, Dart, REST API</p>
                <a href="https://github.com/hazemmahmoudfathy/NewsApp-Flutter" style="color: #58a6ff;">View Project →</a>
            </div>
        </div>
    </div>
    
    <hr class="divider">
    
    <div class="container">
        <h2>📫 Connect With Me</h2>
        <div class="social-links">
            <a href="https://twitter.com/your-twitter" class="social-link">
                <img src="https://raw.githubusercontent.com/hazemmahmoudfathy/Flutter-Repo/main/assets/twitter.svg" alt="Twitter">
            </a>
            <a href="https://codesandbox.io/u/hazemmahmoudfathy" class="social-link">
                <img src="https://raw.githubusercontent.com/hazemmahmoudfathy/Flutter-Repo/main/assets/codesandbox.svg" alt="CodeSandbox">
            </a>
            <a href="https://github.com/hazemmahmoudfathy" class="social-link">
                <img src="https://raw.githubusercontent.com/github/explore/78df643247d429f6cc873026c0622819ad797942/topics/github/github.png" alt="GitHub">
            </a>
            <a href="https://linkedin.com/in/yourprofile" class="social-link">
                <img src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/linkedin/linkedin.png" alt="LinkedIn">
            </a>
        </div>
    </div>
</body>
</html>
