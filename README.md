<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Jawad Ahmad - MERN Stack Developer</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
        }
        
        body {
            background: linear-gradient(135deg, #0a192f 0%, #172a45 100%);
            color: #e6f1ff;
            line-height: 1.6;
            overflow-x: hidden;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        header {
            text-align: center;
            padding: 80px 0 40px;
            position: relative;
        }
        
        h1 {
            font-size: 3.5rem;
            margin-bottom: 15px;
            background: linear-gradient(45deg, #64ffda, #00a3ff);
            -webkit-background-clip: text;
            background-clip: text;
            color: transparent;
            font-weight: 700;
        }
        
        h2 {
            font-size: 1.8rem;
            margin-bottom: 25px;
            color: #ccd6f6;
            font-weight: 500;
        }
        
        h3 {
            font-size: 1.5rem;
            margin: 30px 0 15px;
            color: #64ffda;
        }
        
        p {
            margin-bottom: 20px;
            font-size: 1.1rem;
            color: #a8b2d1;
        }
        
        .badges {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 10px;
            margin: 30px 0;
        }
        
        .badge {
            display: inline-block;
            padding: 8px 16px;
            border-radius: 50px;
            font-size: 0.9rem;
            font-weight: 500;
            text-decoration: none;
            transition: all 0.3s ease;
            background: rgba(100, 255, 218, 0.1);
            color: #64ffda;
            border: 1px solid rgba(100, 255, 218, 0.2);
        }
        
        .badge:hover {
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(100, 255, 218, 0.2);
            background: rgba(100, 255, 218, 0.2);
        }
        
        .section {
            padding: 60px 0;
            border-bottom: 1px solid rgba(100, 255, 218, 0.1);
        }
        
        .tagline {
            text-align: center;
            font-style: italic;
            font-size: 1.2rem;
            padding: 20px;
            background: rgba(100, 255, 218, 0.05);
            border-radius: 10px;
            margin: 40px 0;
            border-left: 3px solid #64ffda;
        }
        
        .stats {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            margin: 40px 0;
        }
        
        .stat-item {
            flex: 1;
            min-width: 250px;
            text-align: center;
            padding: 20px;
            background: rgba(100, 255, 218, 0.05);
            border-radius: 10px;
            transition: transform 0.3s ease;
        }
        
        .stat-item:hover {
            transform: translateY(-5px);
            background: rgba(100, 255, 218, 0.1);
        }
        
        .wave {
            width: 100%;
            height: 150px;
            margin-bottom: -10px;
        }
        
        .links {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 15px;
            margin: 30px 0;
        }
        
        .link {
            display: inline-flex;
            align-items: center;
            padding: 12px 24px;
            border-radius: 50px;
            font-size: 1rem;
            font-weight: 500;
            text-decoration: none;
            transition: all 0.3s ease;
            background: rgba(100, 255, 218, 0.1);
            color: #64ffda;
            border: 1px solid rgba(100, 255, 218, 0.2);
        }
        
        .link:hover {
            transform: translateY(-3px);
            box-shadow: 0 5px 15px rgba(100, 255, 218, 0.3);
            background: rgba(100, 255, 218, 0.2);
        }
        
        .link i {
            margin-right: 8px;
        }
        
        @keyframes waveAnimation {
            0% { transform: translateX(0); }
            50% { transform: translateX(-30px); }
            100% { transform: translateX(0); }
        }
        
        .wave-path {
            animation: waveAnimation 8s ease-in-out infinite;
        }
        
        @media (max-width: 768px) {
            h1 { font-size: 2.5rem; }
            h2 { font-size: 1.5rem; }
            h3 { font-size: 1.3rem; }
            
            .stat-item {
                min-width: 100%;
            }
        }
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
    <!-- Animated Wave Header -->
    <svg class="wave" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
        <path fill="#0a192f" fill-opacity="1" d="M0,128L20,117.3C40,107,80,85,120,106.7C160,128,200,192,240,197.3C280,203,320,149,360,122.7C400,96,440,96,480,128C520,160,560,224,600,256C640,288,680,288,720,245.3C760,203,800,117,840,80C880,43,920,53,960,90.7C1000,128,1040,192,1080,208C1120,224,1160,192,1200,197.3C1240,203,1280,245,1320,229.3C1360,213,1400,139,1420,101.3L1440,64L1440,320L1420,320C1400,320,1360,320,1320,320C1280,320,1240,320,1200,320C1160,320,1120,320,1080,320C1040,320,1000,320,960,320C920,320,880,320,840,320C800,320,760,320,720,320C680,320,640,320,600,320C560,320,520,320,480,320C440,320,400,320,360,320C320,320,280,320,240,320C200,320,160,320,120,320C80,320,40,320,20,320L0,320Z">
            <animate attributeName="d" dur="8s" repeatCount="indefinite" values="
            M0,128L20,117.3C40,107,80,85,120,106.7C160,128,200,192,240,197.3C280,203,320,149,360,122.7C400,96,440,96,480,128C520,160,560,224,600,256C640,288,680,288,720,245.3C760,203,800,117,840,80C880,43,920,53,960,90.7C1000,128,1040,192,1080,208C1120,224,1160,192,1200,197.3C1240,203,1280,245,1320,229.3C1360,213,1400,139,1420,101.3L1440,64L1440,320L1420,320C1400,320,1360,320,1320,320C1280,320,1240,320,1200,320C1160,320,1120,320,1080,320C1040,320,1000,320,960,320C920,320,880,320,840,320C800,320,760,320,720,320C680,320,640,320,600,320C560,320,520,320,480,320C440,320,400,320,360,320C320,320,280,320,240,320C200,320,160,320,120,320C80,320,40,320,20,320L0,320Z;
            
            M0,128L20,138.7C40,149,80,171,120,170.7C160,171,200,149,240,133.3C280,117,320,107,360,122.7C400,139,440,181,480,192C520,203,560,181,600,165.3C640,149,680,139,720,138.7C760,139,800,149,840,165.3C880,181,920,203,960,197.3C1000,192,1040,160,1080,149.3C1120,139,1160,149,1200,154.7C1240,160,1280,160,1320,144C1360,128,1400,96,1420,80L1440,64L1440,320L1420,320C1400,320,1360,320,1320,320C1280,320,1240,320,1200,320C1160,320,1120,320,1080,320C1040,320,1000,320,960,320C920,320,880,320,840,320C800,320,760,320,720,320C680,320,640,320,600,320C560,320,520,320,480,320C440,320,400,320,360,320C320,320,280,320,240,320C200,320,160,320,120,320C80,320,40,320,20,320L0,320Z;
            
            M0,128L20,117.3C40,107,80,85,120,106.7C160,128,200,192,240,197.3C280,203,320,149,360,122.7C400,96,440,96,480,128C520,160,560,224,600,256C640,288,680,288,720,245.3C760,203,800,117,840,80C880,43,920,53,960,90.7C1000,128,1040,192,1080,208C1120,224,1160,192,1200,197.3C1240,203,1280,245,1320,229.3C1360,213,1400,139,1420,101.3L1440,64L1440,320L1420,320C1400,320,1360,320,1320,320C1280,320,1240,320,1200,320C1160,320,1120,320,1080,320C1040,320,1000,320,960,320C920,320,880,320,840,320C800,320,760,320,720,320C680,320,640,320,600,320C560,320,520,320,480,320C440,320,400,320,360,320C320,320,280,320,240,320C200,320,160,320,120,320C80,320,40,320,20,320L0,320Z">
            </animate>
        </path>
    </svg>

    <div class="container">
        <header>
            <h1>Jawad Ahmad</h1>
            <h2>MERN Stack Developer | Founder of <a href="https://goatnova.online" target="_blank" style="color: #64ffda; text-decoration: none;">GoatNova</a> | Entrepreneur</h2>
            
            <div class="badges">
                <span class="badge"><i class="fas fa-globe"></i> jawadahmad.me</span>
                <span class="badge"><i class="fas fa-briefcase"></i> GoatNova Agency</span>
                <span class="badge"><i class="fab fa-github"></i> Jawadahmad9938</span>
                <span class="badge"><i class="fab fa-linkedin"></i> Jawad Ahmad</span>
                <span class="badge"><i class="fab fa-instagram"></i> @jawad__ahmad__007</span>
            </div>
        </header>

        <div class="section">
            <h3><i class="fas fa-user"></i> About Me</h3>
            <p>I'm Jawad Ahmad — a passionate MERN Stack Developer and the founder of GoatNova, a creative digital agency helping brands grow online.</p>
            <p>I craft sleek user interfaces, scalable web apps, and modern digital experiences that don't just look good but perform flawlessly. From responsive frontends to robust backends, I focus on clean code, performance, and user-first design.</p>
        </div>

        <div class="section">
            <h3><i class="fas fa-code"></i> What I Do</h3>
            <p>⚡ <strong>MERN Development</strong> → Full-stack apps with modern architecture</p>
            <p>🎨 <strong>UI/UX Crafting</strong> → Sleek, intuitive, and user-friendly interfaces</p>
            <p>🚀 <strong>Scalable Apps</strong> → From startups to growing businesses</p>
            <p>🌐 <strong>Agency Work (GoatNova)</strong> → Helping brands with digital presence & growth</p>
        </div>

        <div class="section">
            <h3><i class="fas fa-star"></i> Why Work With Me</h3>
            <p>✔ Blend of technical skills + business mindset</p>
            <p>✔ Experience building both personal projects & client solutions</p>
            <p>✔ Strong passion for open source & continuous learning</p>
            <p>✔ Believe in delivering impactful solutions, not just code</p>
        </div>

        <div class="tagline">
            <i class="fas fa-quote-left"></i> Turning ideas into sleek UIs & scalable apps 🚀 | Developer × Entrepreneur × Dreamer <i class="fas fa-quote-right"></i>
        </div>

        <div class="stats">
            <div class="stat-item">
                <h3>GitHub Stats</h3>
                <img src="https://github-readme-stats.vercel.app/api?username=Jawadahmad9938&show_icons=true&theme=radical" alt="GitHub stats" style="width: 100%">
            </div>
            <div class="stat-item">
                <h3>Top Languages</h3>
                <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Jawadahmad9938&layout=compact&theme=radical" alt="Top Languages" style="width: 100%">
            </div>
        </div>

        <div class="section">
            <h3><i class="fas fa-link"></i> Connect With Me</h3>
            <div class="links">
                <a href="https://jawadahmad.me" class="link" target="_blank"><i class="fas fa-globe"></i> Portfolio</a>
                <a href="https://goatnova.online" class="link" target="_blank"><i class="fas fa-briefcase"></i> GoatNova</a>
                <a href="https://linkedin.com/in/jawad-ahmad-376a48245" class="link" target="_blank"><i class="fab fa-linkedin"></i> LinkedIn</a>
                <a href="https://instagram.com/jawad__ahmad_007" class="link" target="_blank"><i class="fab fa-instagram"></i> Instagram</a>
                <a href="https://github.com/Jawadahmad9938" class="link" target="_blank"><i class="fab fa-github"></i> GitHub</a>
                <a href="https://facebook.com/profile.php?id=100016260699449" class="link" target="_blank"><i class="fab fa-facebook"></i> Facebook</a>
            </div>
        </div>
    </div>

    <!-- Animated Wave Footer -->
    <svg class="wave" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320" style="transform: rotate(180deg);">
        <path fill="#0a192f" fill-opacity="1" d="M0,128L20,117.3C40,107,80,85,120,106.7C160,128,200,192,240,197.3C280,203,320,149,360,122.7C400,96,440,96,480,128C520,160,560,224,600,256C640,288,680,288,720,245.3C760,203,800,117,840,80C880,43,920,53,960,90.7C1000,128,1040,192,1080,208C1120,224,1160,192,1200,197.3C1240,203,1280,245,1320,229.3C1360,213,1400,139,1420,101.3L1440,64L1440,320L1420,320C1400,320,1360,320,1320,320C1280,320,1240,320,1200,320C1160,320,1120,320,1080,320C1040,320,1000,320,960,320C920,320,880,320,840,320C800,320,760,320,720,320C680,320,640,320,600,320C560,320,520,320,480,320C440,320,400,320,360,320C320,320,280,320,240,320C200,320,160,320,120,320C80,320,40,320,20,320L0,320Z">
            <animate attributeName="d" dur="8s" repeatCount="indefinite" values="
            M0,128L20,117.3C40,107,80,85,120,106.7C160,128,200,192,240,197.3C280,203,320,149,360,122.7C400,96,440,96,480,128C520,160,560,224,600,256C640,288,680,288,720,245.3C760,203,800,117,840,80C880,43,920,53,960,90.7C1000,128,1040,192,1080,208C1120,224,1160,192,1200,197.3C1240,203,1280,245,1320,229.3C1360,213,1400,139,1420,101.3L1440,64L1440,320L1420,320C1400,320,1360,320,1320,320C1280,320,1240,320,1200,320C1160,320,1120,320,1080,320C1040,320,1000,320,960,320C920,320,880,320,840,320C800,320,760,320,720,320C680,320,640,320,600,320C560,320,520,320,480,320C440,320,400,320,360,320C320,320,280,320,240,320C200,320,160,320,120,320C80,320,40,320,20,320L0,320Z;
            
            M0,128L20,138.7C40,149,80,171,120,170.7C160,171,200,149,240,133.3C280,117,320,107,360,122.7C400,139,440,181,480,192C520,203,560,181,600,165.3C640,149,680,139,720,138.7C760,139,800,149,840,165.3C880,181,920,203,960,197.3C1000,192,1040,160,1080,149.3C1120,139,1160,149,1200,154.7C1240,160,1280,160,1320,144C1360,128,1400,96,1420,80L1440,64L1440,320L1420,320C1400,320,1360,320,1320,320C1280,320,1240,320,1200,320C1160,320,1120,320,1080,320C1040,320,1000,320,960,320C920,320,880,320,840,320C800,320,760,320,720,320C680,320,640,320,600,320C560,320,520,320,480,320C440,320,400,320,360,320C320,320,280,320,240,320C200,320,160,320,120,320C80,320,40,320,20,320L0,320Z;
            
            M0,128L20,117.3C40,107,80,85,120,106.7C160,128,200,192,240,197.3C280,203,320,149,360,122.7C400,96,440,96,480,128C520,160,560,224,600,256C640,288,680,288,720,245.3C760,203,800,117,840,80C880,43,920,53,960,90.7C1000,128,1040,192,1080,208C1120,224,1160,192,1200,197.3C1240,203,1280,245,1320,229.3C1360,213,1400,139,1420,101.3L1440,64L1440,320L1420,320C1400,320,1360,320,1320,320C1280,320,1240,320,1200,320C1160,320,1120,320,1080,320C1040,320,1000,320,960,320C920,320,880,320,840,320C800,320,760,320,720,320C680,320,640,320,600,320C560,320,520,320,480,320C440,320,400,320,360,320C320,320,280,320,240,320C200,320,160,320,120,320C80,320,40,320,20,320L0,320Z">
            </animate>
        </path>
    </svg>

    <script>
        // Simple animation for elements on scroll
        document.addEventListener('DOMContentLoaded', function() {
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.style.opacity = 1;
                        entry.target.style.transform = 'translateY(0)';
                    }
                });
            }, { threshold: 0.1 });
            
            // Observe all sections for animation
            document.querySelectorAll('.section, .tagline, .stat-item').forEach((el) => {
                el.style.opacity = 0;
                el.style.transform = 'translateY(20px)';
                el.style.transition = 'opacity 0.5s ease, transform 0.5s ease';
                observer.observe(el);
            });
        });
    </script>
</body>
</html>
