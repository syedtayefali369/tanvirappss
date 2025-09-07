<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Full-Stack Developer | Digital Marketing & AI Expert</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #0f2027, #203a43, #2c5364);
            color: #f0f6fc;
            line-height: 1.6;
            padding: 20px;
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
            background: rgba(13, 17, 23, 0.85);
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.5);
            border: 1px solid #30363d;
        }
        
        header {
            text-align: center;
            padding: 40px 20px;
            background: linear-gradient(120deg, #1a1f29, #0d1117);
            position: relative;
            overflow: hidden;
        }
        
        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 4px solid #58a6ff;
            margin: 0 auto 20px;
            overflow: hidden;
            background: #30363d;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        
        .profile-img i {
            font-size: 70px;
            color: #58a6ff;
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            color: #f0f6fc;
            text-shadow: 0 0 10px rgba(88, 166, 255, 0.5);
        }
        
        .tagline {
            font-size: 1.2rem;
            color: #8b949e;
            margin-bottom: 20px;
        }
        
        .social-icons {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-top: 20px;
        }
        
        .social-icons a {
            display: inline-flex;
            align-items: center;
            justify-content: center;
            width: 40px;
            height: 40px;
            border-radius: 50%;
            background: #21262d;
            color: #c9d1d9;
            text-decoration: none;
            transition: all 0.3s ease;
        }
        
        .social-icons a:hover {
            background: #58a6ff;
            color: #0d1117;
            transform: translateY(-3px);
        }
        
        .main-content {
            padding: 30px;
        }
        
        .section {
            margin-bottom: 30px;
        }
        
        h2 {
            font-size: 1.8rem;
            margin-bottom: 20px;
            color: #58a6ff;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        h2 i {
            background: linear-gradient(120deg, #1a1f29, #0d1117);
            width: 40px;
            height: 40px;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            border-radius: 50%;
        }
        
        .skills {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
        }
        
        .skill-category {
            background: #161b22;
            padding: 20px;
            border-radius: 10px;
            border: 1px solid #30363d;
        }
        
        .skill-category h3 {
            font-size: 1.2rem;
            margin-bottom: 15px;
            color: #f0f6fc;
            display: flex;
            align-items: center;
            gap: 10px;
        }
        
        .skill-list {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
        }
        
        .skill {
            background: #0d1117;
            padding: 8px 15px;
            border-radius: 20px;
            font-size: 0.9rem;
            display: flex;
            align-items: center;
            gap: 5px;
            border: 1px solid #30363d;
        }
        
        .projects {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
        }
        
        .project {
            background: #161b22;
            border-radius: 10px;
            overflow: hidden;
            border: 1px solid #30363d;
            transition: transform 0.3s ease;
        }
        
        .project:hover {
            transform: translateY(-5px);
        }
        
        .project-img {
            height: 160px;
            background: linear-gradient(120deg, #1a1f29, #0d1117);
            display: flex;
            align-items: center;
            justify-content: center;
            color: #58a6ff;
            font-size: 50px;
        }
        
        .project-info {
            padding: 20px;
        }
        
        .project-info h3 {
            font-size: 1.2rem;
            margin-bottom: 10px;
            color: #f0f6fc;
        }
        
        .project-info p {
            color: #8b949e;
            font-size: 0.9rem;
            margin-bottom: 15px;
        }
        
        .project-tech {
            display: flex;
            flex-wrap: wrap;
            gap: 5px;
            margin-bottom: 15px;
        }
        
        .tech {
            background: #0d1117;
            padding: 5px 10px;
            border-radius: 15px;
            font-size: 0.8rem;
            color: #58a6ff;
            border: 1px solid #30363d;
        }
        
        .btn {
            display: inline-block;
            padding: 8px 15px;
            background: #238636;
            color: white;
            text-decoration: none;
            border-radius: 5px;
            font-size: 0.9rem;
            transition: background 0.3s ease;
        }
        
        .btn:hover {
            background: #2ea043;
        }
        
        .stats {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 20px;
            text-align: center;
        }
        
        .stat {
            background: #161b22;
            padding: 20px;
            border-radius: 10px;
            border: 1px solid #30363d;
        }
        
        .stat i {
            font-size: 2rem;
            color: #58a6ff;
            margin-bottom: 10px;
        }
        
        .stat h3 {
            font-size: 2rem;
            margin-bottom: 5px;
            color: #f0f6fc;
        }
        
        .stat p {
            color: #8b949e;
        }
        
        footer {
            text-align: center;
            padding: 20px;
            background: #0d1117;
            color: #8b949e;
            font-size: 0.9rem;
            border-top: 1px solid #30363d;
        }
        
        .highlight {
            color: #58a6ff;
            font-weight: 500;
        }
        
        @media (max-width: 768px) {
            h1 {
                font-size: 2rem;
            }
            
            .skills, .projects, .stats {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <div class="profile-img">
                <i class="fas fa-user"></i>
            </div>
            <h1>John Doe</h1>
            <p class="tagline">Full-Stack Developer | Digital Marketing Expert | AI Specialist</p>
            <div class="social-icons">
                <a href="#"><i class="fab fa-github"></i></a>
                <a href="#"><i class="fab fa-linkedin"></i></a>
                <a href="#"><i class="fab fa-twitter"></i></a>
                <a href="#"><i class="fab fa-dev"></i></a>
                <a href="#"><i class="fas fa-envelope"></i></a>
            </div>
        </header>
        
        <div class="main-content">
            <div class="section">
                <h2><i class="fas fa-user"></i> About Me</h2>
                <p>I'm a passionate Full-Stack Developer with expertise in Digital Marketing and Artificial Intelligence. With over 5 years of experience, I create innovative web solutions that combine cutting-edge technology with data-driven marketing strategies to deliver exceptional user experiences and business growth.</p>
                <p>My approach integrates technical excellence with marketing insights to build products that not only function flawlessly but also achieve market success.</p>
            </div>
            
            <div class="section">
                <h2><i class="fas fa-laptop-code"></i> Skills & Expertise</h2>
                <div class="skills">
                    <div class="skill-category">
                        <h3><i class="fas fa-code"></i> Full-Stack Development</h3>
                        <div class="skill-list">
                            <div class="skill"><i class="fab fa-react"></i> React</div>
                            <div class="skill"><i class="fab fa-node-js"></i> Node.js</div>
                            <div class="skill"><i class="fab fa-python"></i> Python</div>
                            <div class="skill"><i class="fas fa-database"></i> MongoDB</div>
                            <div class="skill"><i class="fas fa-database"></i> PostgreSQL</div>
                            <div class="skill"><i class="fab fa-js"></i> JavaScript</div>
                            <div class="skill"><i class="fab fa-html5"></i> HTML5</div>
                            <div class="skill"><i class="fab fa-css3-alt"></i> CSS3</div>
                        </div>
                    </div>
                    
                    <div class="skill-category">
                        <h3><i class="fas fa-chart-line"></i> Digital Marketing</h3>
                        <div class="skill-list">
                            <div class="skill"><i class="fas fa-search"></i> SEO</div>
                            <div class="skill"><i class="fas fa-ad"></i> PPC</div>
                            <div class="skill"><i class="fas fa-hashtag"></i> Social Media</div>
                            <div class="skill"><i class="fas fa-chart-pie"></i> Analytics</div>
                            <div class="skill"><i class="fas fa-mail-bulk"></i> Email Marketing</div>
                            <div class="skill"><i class="fas fa-funnel-dollar"></i> Conversion Optimization</div>
                        </div>
                    </div>
                    
                    <div class="skill-category">
                        <h3><i class="fas fa-robot"></i> Artificial Intelligence</h3>
                        <div class="skill-list">
                            <div class="skill"><i class="fas fa-brain"></i> Machine Learning</div>
                            <div class="skill"><i class="fas fa-comment-alt"></i> NLP</div>
                            <div class="skill"><i class="fas fa-eye"></i> Computer Vision</div>
                            <div class="skill"><i class="fas fa-chart-bar"></i> Predictive Analytics</div>
                            <div class="skill"><i class="fas fa-robot"></i> Chatbots</div>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="section">
                <h2><i class="fas fa-project-diagram"></i> Featured Projects</h2>
                <div class="projects">
                    <div class="project">
                        <div class="project-img">
                            <i class="fas fa-shopping-cart"></i>
                        </div>
                        <div class="project-info">
                            <h3>E-Commerce AI Platform</h3>
                            <p>An intelligent e-commerce platform with personalized recommendations and AI-powered marketing automation.</p>
                            <div class="project-tech">
                                <span class="tech">React</span>
                                <span class="tech">Node.js</span>
                                <span class="tech">MongoDB</span>
                                <span class="tech">TensorFlow</span>
                            </div>
                            <a href="#" class="btn">View Project</a>
                        </div>
                    </div>
                    
                    <div class="project">
                        <div class="project-img">
                            <i class="fas fa-chart-line"></i>
                        </div>
                        <div class="project-info">
                            <h3>Marketing Analytics Dashboard</h3>
                            <p>A comprehensive dashboard that tracks and analyzes marketing performance across multiple channels.</p>
                            <div class="project-tech">
                                <span class="tech">Vue.js</span>
                                <span class="tech">Python</span>
                                <span class="tech">PostgreSQL</span>
                                <span class="tech">D3.js</span>
                            </div>
                            <a href="#" class="btn">View Project</a>
                        </div>
                    </div>
                    
                    <div class="project">
                        <div class="project-img">
                            <i class="fas fa-robot"></i>
                        </div>
                        <div class="project-info">
                            <h3>AI Content Assistant</h3>
                            <p>An AI-powered tool that helps marketers create optimized content and predict engagement metrics.</p>
                            <div class="project-tech">
                                <span class="tech">React</span>
                                <span class="tech">NLP</span>
                                <span class="tech">FastAPI</span>
                                <span class="tech">AWS</span>
                            </div>
                            <a href="#" class="btn">View Project</a>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="section">
                <h2><i class="fas fa-chart-bar"></i> Achievements</h2>
                <div class="stats">
                    <div class="stat">
                        <i class="fas fa-code-branch"></i>
                        <h3>150+</h3>
                        <p>Projects Completed</p>
                    </div>
                    <div class="stat">
                        <i class="fas fa-users"></i>
                        <h3>95%</h3>
                        <p>Client Satisfaction</p>
                    </div>
                    <div class="stat">
                        <i class="fas fa-rocket"></i>
                        <h3>200%</h3>
                        <p>Average ROI Increase</p>
                    </div>
                    <div class="stat">
                        <i class="fas fa-award"></i>
                        <h3>12</h3>
                        <p>Industry Awards</p>
                    </div>
                </div>
            </div>
            
            <div class="section">
                <h2><i class="fas fa-envelope"></i> Contact Me</h2>
                <p>I'm always interested in new opportunities and challenges. Feel free to reach out if you want to collaborate on an exciting project or just want to connect!</p>
                <p>📧 Email: <span class="highlight">john.doe@example.com</span></p>
                <p>🔗 LinkedIn: <span class="highlight">linkedin.com/in/johndoe</span></p>
            </div>
        </div>
        
        <footer>
            <p>© 2023 John Doe | Full-Stack Developer & Digital Marketing Expert</p>
            <p>Made with <i class="fas fa-heart" style="color: #cc241d;"></i> and <i class="fas fa-code" style="color: #58a6ff;"></i></p>
        </footer>
    </div>
</body>
</html>
