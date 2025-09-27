<svg width="100%" height="300" viewBox="0 0 1200 300" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="heroGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#667eea;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#764ba2;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#f093fb;stop-opacity:1" />
    </linearGradient>
    <filter id="glow">
      <feGaussianBlur stdDeviation="4" result="coloredBlur"/>
      <feMerge>
        <feMergeNode in="coloredBlur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  
  <!-- Animated background -->
  <rect width="100%" height="100%" fill="url(#heroGradient)"/>
  
  <!-- Floating particles -->
  <circle cx="100" cy="50" r="3" fill="white" opacity="0.6">
    <animate attributeName="cy" values="50;250;50" dur="4s" repeatCount="indefinite"/>
  </circle>
  <circle cx="200" cy="100" r="2" fill="white" opacity="0.4">
    <animate attributeName="cy" values="100;200;100" dur="6s" repeatCount="indefinite"/>
  </circle>
  <circle cx="1100" cy="80" r="4" fill="white" opacity="0.5">
    <animate attributeName="cy" values="80;220;80" dur="5s" repeatCount="indefinite"/>
  </circle>
  
  <!-- Medical cross morphing to code brackets -->
  <g transform="translate(300, 100)">
    <rect x="-30" y="-5" width="60" height="10" fill="white" opacity="0.8" filter="url(#glow)">
      <animateTransform attributeName="transform" type="rotate" values="0;360" dur="8s" repeatCount="indefinite"/>
    </rect>
    <rect x="-5" y="-30" width="10" height="60" fill="white" opacity="0.8" filter="url(#glow)">
      <animateTransform attributeName="transform" type="rotate" values="0;360" dur="8s" repeatCount="indefinite"/>
    </rect>
  </g>
  
  <!-- Code brackets -->
  <g transform="translate(900, 150)">
    <text x="0" y="0" fill="white" font-size="40" font-family="monospace" filter="url(#glow)">{</text>
    <text x="30" y="0" fill="white" font-size="40" font-family="monospace" filter="url(#glow)">}</text>
    <animateTransform attributeName="transform" type="translate" values="900,150;920,150;900,150" dur="3s" repeatCount="indefinite"/>
  </g>
  
  <foreignObject width="100%" height="100%">
    <div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: center; justify-content: center; height: 100%; flex-direction: column;">
      <style>
        @media (max-width: 768px) {
          .hero-title { font-size: 28px !important; }
          .hero-subtitle { font-size: 16px !important; }
        }
        @media (min-width: 769px) {
          .hero-title { font-size: 48px !important; }
          .hero-subtitle { font-size: 20px !important; }
        }
      </style>
      <h1 class="hero-title" style="color: white; font-family: 'Arial', sans-serif; font-weight: bold; margin: 0; text-shadow: 2px 2px 4px rgba(0,0,0,0.3); text-align: center;">
        🔬→💻 Melanie Reis
      </h1>
      <p class="hero-subtitle" style="color: rgba(255,255,255,0.9); font-family: 'Arial', sans-serif; margin: 10px 0 0 0; text-align: center;">
        From Surgery to Code | Precision Engineering | Mother & Developer
      </p>
    </div>
  </foreignObject>
</svg>

---

<div align="center">

<!-- Responsive typing animation -->
<svg width="100%" height="150" viewBox="0 0 1000 150" xmlns="http://www.w3.org/2000/svg">
  <foreignObject width="100%" height="100%">
    <div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: center; justify-content: center; height: 100%;">
      <img src="https://readme-typing-svg.demolab.com/?lines=🩺+5+Years+Surgical+Nurse;💻+42+Porto+Graduate+-+110/100+Score;👶+Coded+with+1-month-old+newborn;🎯+Zero-error+mindset;🚀+Starting+SEA:ME+October+2025&font=JetBrains+Mono&size=22&duration=2500&pause=800&color=FF6B9D&center=true&vCenter=true&width=900&height=120" style="max-width: 100%; height: auto;" />
    </div>
  </foreignObject>
</svg>

</div>

---

## 🌟 The Incredible Journey

<div align="center">

<svg width="100%" height="400" viewBox="0 0 1000 400" xmlns="http://www.w3.org/2000/svg">
  <foreignObject width="100%" height="100%">
    <div xmlns="http://www.w3.org/1999/xhtml" style="padding: 20px;">
      <style>
        .journey-container {
          display: grid;
          grid-template-columns: 1fr 1fr;
          gap: 30px;
          height: 100%;
          align-items: center;
        }
        @media (max-width: 768px) {
          .journey-container {
            grid-template-columns: 1fr;
            gap: 20px;
          }
        }
        .journey-text {
          font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
          color: #333;
        }
        .code-block {
          background: #1a1a1a;
          color: #ffffff;
          padding: 20px;
          border-radius: 12px;
          font-family: 'JetBrains Mono', monospace;
          font-size: 14px;
          line-height: 1.6;
          box-shadow: 0 8px 32px rgba(0,0,0,0.1);
          border: 1px solid #333;
        }
        .highlight { color: #FF6B9D; }
        .comment { color: #7C7C7C; }
        @media (max-width: 768px) {
          .code-block { font-size: 12px; padding: 15px; }
        }
      </style>
      <div class="journey-container">
        <div class="journey-text">
          <h3 style="color: #FF6B9D; font-size: 24px; margin: 0 0 15px 0;">🤱 The Ultimate Challenge</h3>
          <p style="margin: 0 0 15px 0; font-size: 16px; line-height: 1.6;">
            <strong>September 2024:</strong> Started 42 Piscine with a <strong>1-month-old newborn</strong> and a <strong>2-year-old son</strong> at home.
          </p>
          <p style="margin: 0 0 15px 0; font-size: 16px; line-height: 1.6;">
            While other students had 8+ hours daily, I coded between feedings, nap times, and sleepless nights. Yet I not only survived but <strong>thrived</strong>.
          </p>
          <p style="margin: 0; font-size: 16px; line-height: 1.6;">
            <strong>Result:</strong> 42 Porto Graduate with <span style="color: #FF6B9D; font-weight: bold;">110/100 final score</span>
          </p>
        </div>
        <div class="code-block">
<span class="comment">// The impossible made possible</span>
<span class="highlight">const</span> impossibleJourney = {
  <span class="highlight">challenges</span>: [
    "👶 1-month-old newborn",
    "🧒 2-year-old toddler",
    "🏥 Full-time surgical nurse", 
    "😴 2-3 hours of sleep",
    "💻 42 School intensity"
  ],
  <span class="highlight">timeManagement</span>: "Master level",
  <span class="highlight">result</span>: "110/100 - Top graduate",
  
  <span class="highlight">getInspiration</span>() {
    <span class="highlight">return</span> "Proving that with determination, " +
           "any challenge is conquerable";
  }
};
        </div>
      </div>
    </div>
  </foreignObject>
</svg>

</div>

---

## 🎯 Professional Timeline

<div align="center">

<svg width="100%" height="600" viewBox="0 0 1000 600" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="timelineGradient" x1="0%" y1="0%" x2="0%" y2="100%">
      <stop offset="0%" style="stop-color:#667eea;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#764ba2;stop-opacity:1" />
    </linearGradient>
  </defs>
  
  <!-- Timeline line -->
  <line x1="500" y1="50" x2="500" y2="550" stroke="url(#timelineGradient)" stroke-width="4"/>
  
  <!-- Timeline dots -->
  <circle cx="500" cy="100" r="12" fill="#667eea"/>
  <circle cx="500" cy="200" r="12" fill="#764ba2"/>
  <circle cx="500" cy="300" r="12" fill="#f093fb"/>
  <circle cx="500" cy="400" r="12" fill="#FF6B9D"/>
  <circle cx="500" cy="500" r="12" fill="#FEE77A"/>
  
  <foreignObject width="100%" height="100%">
    <div xmlns="http://www.w3.org/1999/xhtml" style="font-family: 'Segoe UI', sans-serif;">
      <style>
        .timeline-container {
          display: grid;
          grid-template-rows: repeat(5, 1fr);
          height: 600px;
          padding: 0 50px;
        }
        .timeline-item {
          display: flex;
          align-items: center;
          height: 100px;
        }
        .timeline-content {
          flex: 1;
          padding: 0 30px;
        }
        .timeline-left {
          text-align: right;
          padding-right: 50px;
        }
        .timeline-right {
          text-align: left;
          padding-left: 50px;
        }
        .timeline-date {
          font-weight: bold;
          color: #667eea;
          font-size: 18px;
        }
        .timeline-title {
          font-size: 16px;
          color: #333;
          margin: 5px 0;
        }
        .timeline-desc {
          font-size: 14px;
          color: #666;
          margin: 0;
        }
        @media (max-width: 768px) {
          .timeline-container { padding: 0 20px; }
          .timeline-content { padding: 0 15px; }
          .timeline-left, .timeline-right { 
            text-align: center; 
            padding: 0 10px;
          }
          .timeline-date { font-size: 16px; }
          .timeline-title { font-size: 14px; }
          .timeline-desc { font-size: 12px; }
        }
      </style>
      
      <div class="timeline-container">
        <div class="timeline-item">
          <div class="timeline-content timeline-left">
            <div class="timeline-date">2020</div>
            <div class="timeline-title">🏥 Started Surgical Nursing</div>
            <div class="timeline-desc">OR & Anesthesia specialist</div>
          </div>
        </div>
        
        <div class="timeline-item">
          <div class="timeline-content timeline-right">
            <div class="timeline-date">Sep 2024</div>
            <div class="timeline-title">👶 42 Piscine (with 1-month newborn)</div>
            <div class="timeline-desc">Coding between feedings & sleepless nights</div>
          </div>
        </div>
        
        <div class="timeline-item">
          <div class="timeline-content timeline-left">
            <div class="timeline-date">Oct 2024</div>
            <div class="timeline-title">💻 Started 42 Common Core</div>
            <div class="timeline-desc">20+ projects while raising 2 kids</div>
          </div>
        </div>
        
        <div class="timeline-item">
          <div class="timeline-content timeline-right">
            <div class="timeline-date">Sep 2025</div>
            <div class="timeline-title">🎓 42 Porto Graduate</div>
            <div class="timeline-desc">110/100 Final Score Achieved</div>
          </div>
        </div>
        
        <div class="timeline-item">
          <div class="timeline-content timeline-left">
            <div class="timeline-date">Oct 2025</div>
            <div class="timeline-title">🚀 Starting SEA:ME Automotive</div>
            <div class="timeline-desc">Next chapter: HealthTech meets Automotive</div>
          </div>
        </div>
      </div>
    </div>
  </foreignObject>
</svg>

</div>

---

## 💻 42 Porto Hall of Fame

<div align="center">

<svg width="100%" height="500" viewBox="0 0 1000 500" xmlns="http://www.w3.org/2000/svg">
  <foreignObject width="100%" height="100%">
    <div xmlns="http://www.w3.org/1999/xhtml">
      <style>
        .projects-grid {
          display: grid;
          grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
          gap: 20px;
          padding: 20px;
          font-family: 'Segoe UI', sans-serif;
        }
        .project-card {
          background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
          border-radius: 16px;
          padding: 24px;
          color: white;
          text-align: center;
          box-shadow: 0 10px 30px rgba(102, 126, 234, 0.3);
          transition: transform 0.3s ease;
          position: relative;
          overflow: hidden;
        }
        .project-card::before {
          content: '';
          position: absolute;
          top: -50%;
          left: -50%;
          width: 200%;
          height: 200%;
          background: linear-gradient(45deg, transparent, rgba(255,255,255,0.1), transparent);
          transform: rotate(45deg);
          transition: all 0.5s;
          opacity: 0;
        }
        .project-card:hover::before {
          opacity: 1;
          animation: shine 0.5s ease-in-out;
        }
        @keyframes shine {
          0% { transform: translateX(-100%) translateY(-100%) rotate(45deg); }
          100% { transform: translateX(100%) translateY(100%) rotate(45deg); }
        }
        .project-title {
          font-size: 18px;
          font-weight: bold;
          margin: 0 0 8px 0;
        }
        .project-score {
          font-size: 24px;
          font-weight: 900;
          color: #FEE77A;
          margin: 8px 0;
        }
        .project-desc {
          font-size: 13px;
          opacity: 0.9;
          margin: 0;
        }
        .featured-projects {
          grid-column: 1 / -1;
          display: grid;
          grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
          gap: 20px;
          margin-bottom: 20px;
        }
        .featured-card {
          background: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
          border-radius: 16px;
          padding: 24px;
          color: white;
        }
        @media (max-width: 768px) {
          .projects-grid { 
            grid-template-columns: 1fr; 
            padding: 10px;
          }
          .project-card { padding: 16px; }
          .featured-projects { grid-template-columns: 1fr; }
        }
      </style>
      
      <div class="projects-grid">
        <!-- Featured Projects -->
        <div class="featured-projects">
          <div class="featured-card">
            <h3 class="project-title">🎮 cub3D - 3D Engine</h3>
            <div class="project-score">125/100</div>
            <p class="project-desc">Built complete 3D raycasting engine in C with MLX graphics</p>
          </div>
          <div class="featured-card">
            <h3 class="project-title">🌐 ft_transcendence</h3>
            <div class="project-score">110/100</div>
            <p class="project-desc">Full-stack real-time multiplayer Pong with WebSockets</p>
          </div>
        </div>
        
        <!-- Other Projects -->
        <div class="project-card">
          <h4 class="project-title">⚡ webserv</h4>
          <div class="project-score">100/100</div>
          <p class="project-desc">HTTP Server from scratch</p>
        </div>
        
        <div class="project-card">
          <h4 class="project-title">🐚 minishell</h4>
          <div class="project-score">99/100</div>
          <p class="project-desc">Bash implementation</p>
        </div>
        
        <div class="project-card">
          <h4 class="project-title">📖 get_next_line</h4>
          <div class="project-score">125/100</div>
          <p class="project-desc">File reading function</p>
        </div>
        
        <div class="project-card">
          <h4 class="project-title">🎯 so_long</h4>
          <div class="project-score">115/100</div>
          <p class="project-desc">2D Game Engine</p>
        </div>
      </div>
    </div>
  </foreignObject>
</svg>

</div>

---

## 🛠️ Technical Mastery

<div align="center">

<svg width="100%" height="400" viewBox="0 0 1000 400" xmlns="http://www.w3.org/2000/svg">
  <foreignObject width="100%" height="100%">
    <div xmlns="http://www.w3.org/1999/xhtml">
      <style>
        .skills-container {
          display: grid;
          grid-template-columns: repeat(2, 1fr);
          gap: 40px;
          padding: 30px;
          font-family: 'Segoe UI', sans-serif;
          height: 100%;
        }
        .skill-section {
          display: flex;
          flex-direction: column;
          justify-content: center;
        }
        .skills-icons {
          display: flex;
          flex-wrap: wrap;
          gap: 15px;
          justify-content: center;
          margin: 20px 0;
        }
        .skill-icon {
          width: 60px;
          height: 60px;
          background: linear-gradient(135deg, #667eea, #764ba2);
          border-radius: 12px;
          display: flex;
          align-items: center;
          justify-content: center;
          color: white;
          font-size: 24px;
          box-shadow: 0 8px 20px rgba(102, 126, 234, 0.3);
          transition: transform 0.3s ease;
        }
        .skill-icon:hover {
          transform: translateY(-5px) scale(1.1);
        }
        .code-showcase {
          background: #1a1a1a;
          border-radius: 12px;
          padding: 20px;
          color: #ffffff;
          font-family: 'JetBrains Mono', monospace;
          font-size: 13px;
          line-height: 1.5;
          box-shadow: 0 8px 32px rgba(0,0,0,0.2);
        }
        .keyword { color: #FF6B9D; }
        .string { color: #A8E6CF; }
        .comment { color: #7C7C7C; }
        .number { color: #FFB347; }
        
        @media (max-width: 768px) {
          .skills-container {
            grid-template-columns: 1fr;
            gap: 20px;
            padding: 15px;
          }
          .skill-icon {
            width: 50px;
            height: 50px;
            font-size: 20px;
          }
          .code-showcase {
            font-size: 11px;
            padding: 15px;
          }
        }
      </style>
      
      <div class="skills-container">
        <div class="skill-section">
          <h3 style="text-align: center; color: #333; margin: 0 0 20px 0;">🚀 Core Technologies</h3>
          <div class="skills-icons">
            <div class="skill-icon" title="C/C++">⚙️</div>
            <div class="skill-icon" title="JavaScript">🟨</div>
            <div class="skill-icon" title="TypeScript">🔷</div>
            <div class="skill-icon" title="React">⚛️</div>
            <div class="skill-icon" title="Node.js">💚</div>
            <div class="skill-icon" title="Docker">🐳</div>
            <div class="skill-icon" title="PostgreSQL">🐘</div>
            <div class="skill-icon" title="Linux">🐧</div>
          </div>
        </div>
        
        <div class="skill-section">
          <div class="code-showcase">
<span class="comment">// Unique skill combination</span>
<span class="keyword">class</span> <span class="string">SurgicalDeveloper</span> {
  <span class="keyword">constructor</span>() {
    <span class="keyword">this</span>.background = <span class="string">"5 years surgery"</span>;
    <span class="keyword">this</span>.mindset = <span class="string">"zero-error tolerance"</span>;
    <span class="keyword">this</span>.experience = <span class="number">500</span> + surgeries;
    <span class="keyword">this</span>.coding = <span class="string">"42 Porto Graduate"</span>;
  }
  
  <span class="keyword">solve</span>(problem) {
    <span class="comment">// Apply surgical precision to code</span>
    <span class="keyword">return</span> <span class="keyword">this</span>.preciseProblemSolving(
      problem, 
      <span class="keyword">this</span>.lifeOrDeathAttention
    );
  }
  
  <span class="keyword">getUniqueValue</span>() {
    <span class="keyword">return</span> <span class="string">"Healthcare precision + Tech innovation"</span>;
  }
}
          </div>
        </div>
      </div>
    </div>
  </foreignObject>
</svg>

</div>

---

## 📊 Real-Time GitHub Analytics

<div align="center">

<svg width="100%" height="600" viewBox="0 0 1000 600" xmlns="http://www.w3.org/2000/svg">
  <foreignObject width="100%" height="100%">
    <div xmlns="http://www.w3.org/1999/xhtml">
      <style>
        .stats-container {
          display: grid;
          grid-template-columns: 1fr 1fr;
          gap: 20px;
          padding: 20px;
          height: 100%;
        }
        .stats-row {
          display: grid;
          grid-template-columns: 1fr;
          gap: 20px;
        }
        .stats-wide {
          grid-column: 1 / -1;
          display: flex;
          justify-content: center;
        }
        .stat-card {
          background: linear-gradient(135deg, #667eea, #764ba2);
          border-radius: 16px;
          padding: 16px;
          display: flex;
          align-items: center;
          justify-content: center;
          min-height: 200px;
          box-shadow: 0 10px 30px rgba(102, 126, 234, 0.2);
        }
        .stat-card img {
          max-width: 100%;
          height: auto;
          border-radius: 8px;
        }
        @media (max-width: 768px) {
          .stats-container {
            grid-template-columns: 1fr;
            gap: 15px;
            padding: 10px;
          }
          .stat-card {
            min-height: 180px;
            padding: 12px;
          }
        }
      </style>
      
      <div class="stats-container">
        <div class="stat-card">
          <img src="https://github-readme-stats.vercel.app/api?username=melaniereis&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=FF6B9D&icon_color=FEE77A&text_color=FFFFFF" alt="GitHub Stats" />
        </div>
        
        <div class="stat-card">
          <img src="https://github-readme-streak-stats.herokuapp.com/?user=melaniereis&theme=tokyonight&hide_border=true&background=0D1117&stroke=FF6B9D&ring=FEE77A&fire=FF6B9D&currStreakLabel=FEE77A" alt="GitHub Streak" />
        </div>
        
        <div class="stats-wide">
          <div class="stat-card" style="width: 70%;">
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=melaniereis&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=FF6B9D&text_color=FFFFFF" alt="Top Languages" />
          </div>
        </div>
        
        <div class="stats-wide">
          <div class="stat-card" style="width: 80%;">
            <img src="https://github-readme-activity-graph.vercel.app/graph?username=melaniereis&bg_color=0d1117&color=FF6B9D&line=FEE77A&point=FFFFFF&area=true&hide_border=true&custom_title=Coding%20Journey%20-%20From%20Healthcare%20to%20Code" alt="Activity Graph" />
          </div>
        </div>
      </div>
    </div>
  </foreignObject>
</svg>

</div>

---

## 🚀 Next Chapter: SEA:ME Automotive

<div align="center">

<svg width="100%" height="350" viewBox="0 0 1000 350" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="futureGradient" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" style="stop-color:#f093fb;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#f5576c;stop-opacity:1" />
    </linearGradient>
  </defs>
  
  <rect width="100%" height="100%" fill="url(#futureGradient)" rx="20"/>
  
  <foreignObject width="100%" height="100%">
    <div xmlns="http://www.w3.org/1999/xhtml" style="color: white; padding: 30px; font-family: 'Segoe UI', sans-serif;">
      <style>
        .future-container {
          display: grid;
          grid-template-columns: 1fr 2fr;
          gap: 30px;
          height: 100%;
          align-items: center;
        }
        .future-icon {
          font-size: 120px;
          text-align: center;
          line-height: 1;
        }
        .future-content h2 {
          margin: 0 0 20px 0;
          font-size: 28px;
          font-weight: 700;
        }
        .future-grid {
          display: grid;
          grid-template-columns: repeat(2, 1fr);
          gap: 15px;
          margin: 20px 0;
        }
        .future-item {
          background: rgba(255,255,255,0.1);
          padding: 15px;
          border-radius: 8px;
          text-align: center;
          font-size: 14px;
        }
        .future-item strong {
          display: block;
          font-size: 16px;
          margin-bottom: 5px;
        }
        @media (max-width: 768px) {
          .future-container {
            grid-template-columns: 1fr;
            gap: 20px;
            text-align: center;
          }
          .future-icon { font-size: 80px; }
          .future-content h2 { font-size: 24px; }
          .future-grid { grid-template-columns: 1fr; }
        }
      </style>
      
      <div class="future-container">
        <div class="future-icon">🚗💻</div>
        <div class="future-content">
          <h2>Starting October 2025</h2>
          <p style="font-size: 16px; margin: 0 0 20px 0;">
            Bridging my healthcare precision with automotive innovation at SEA:ME program.
          </p>
          
          <div class="future-grid">
            <div class="future-item">
              <strong>🩺 HealthTech Integration</strong>
              In-vehicle health monitoring systems
            </div>
            <div class="future-item">
              <strong>🚨 Emergency Response</strong>
              Life-saving automotive technology
            </div>
            <div class="future-item">
              <strong>🧠 Driver Wellness</strong>
              Real-time health analytics
            </div>
            <div class="future-item">
              <strong>⚡ Safety-Critical</strong>
              Zero-error automotive software
            </div>
          </div>
          
          <p style="font-size: 14px; margin: 20px 0 0 0; opacity: 0.9;">
            <em>"Applying surgical precision to automotive safety - where every line of code can save lives."</em>
          </p>
        </div>
      </div>
    </div>
  </foreignObject>
</svg>

</div>

---

## 🤝 Connect & Collaborate

<div align="center">

<svg width="100%" height="200" viewBox="0 0 1000 200" xmlns="http://www.w3.org/2000/svg">
  <foreignObject width="100%" height="100%">
    <div xmlns="http://www.w3.org/1999/xhtml">
      <style>
        .connect-container {
          display: flex;
          justify-content: center;
          align-items: center;
          height: 100%;
          gap: 30px;
          flex-wrap: wrap;
          padding: 20px;
          font-family: 'Segoe UI', sans-serif;
        }
        .connect-button {
          display: inline-flex;
          align-items: center;
          gap: 10px;
          background: linear-gradient(135deg, #667eea, #764ba2);
          color: white;
          text-decoration: none;
          padding: 12px 24px;
          border-radius: 50px;
          font-weight: 600;
          font-size: 14px;
          box-shadow: 0 8px 25px rgba(102, 126, 234, 0.3);
          transition: all 0.3s ease;
          border: 2px solid transparent;
        }
        .connect-button:hover {
          transform: translateY(-3px);
          box-shadow: 0 12px 35px rgba(102, 126, 234, 0.4);
          border-color: rgba(255,255,255,0.3);
        }
        .location-info {
          text-align: center;
          color: #333;
          margin-top: 20px;
        }
        @media (max-width: 768px) {
          .connect-container {
            flex-direction: column;
            gap: 15px;
          }
          .connect-button {
            width: 250px;
            justify-content: center;
          }
        }
      </style>
      
      <div class="connect-container">
        <a href="https://www.linkedin.com/in/melanie-ferraz-reis-622229a5" class="connect-button">
          💼 LinkedIn
        </a>
        <a href="mailto:melanie.ferraz@ua.pt" class="connect-button">
          📧 Email
        </a>
        <a href="https://github.com/melaniereis" class="connect-button">
          🐙 GitHub
        </a>
      </div>
      
      <div class="location-info">
        <p style="margin: 0; font-size: 16px; font-weight: 500;">📍 Ovar, Portugal 🇵🇹</p>
        <p style="margin: 5px 0 0 0; font-size: 14px; color: #666;">Open to HealthTech & Automotive opportunities</p>
      </div>
    </div>
  </foreignObject>
</svg>

</div>

---

<div align="center">

<!-- Animated footer wave -->
<svg width="100%" height="150" viewBox="0 0 1000 150" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="footerGradient" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" style="stop-color:#667eea;stop-opacity:1" />
      <stop offset="50%" style="stop-color:#764ba2;stop-opacity:1" />
      <stop offset="100%" style="stop-color:#f093fb;stop-opacity:1" />
    </linearGradient>
  </defs>
  
  <path d="M0,50 Q250,10 500,50 T1000,50 L1000,150 L0,150 Z" fill="url(#footerGradient)">
    <animate attributeName="d" 
             values="M0,50 Q250,10 500,50 T1000,50 L1000,150 L0,150 Z;
                     M0,50 Q250,90 500,50 T1000,50 L1000,150 L0,150 Z;
                     M0,50 Q250,10 500,50 T1000,50 L1000,150 L0,150 Z" 
             dur="4s" 
             repeatCount="indefinite"/>
  </path>
  
  <foreignObject width="100%" height="100%">
    <div xmlns="http://www.w3.org/1999/xhtml" style="display: flex; align-items: center; justify-content: center; height: 100%; color: white; font-family: 'Segoe UI', sans-serif;">
      <div style="text-align: center;">
        <h3 style="margin: 0; font-size: 24px; font-weight: bold;">💭 Ready to Build the Future Together?</h3>
        <p style="margin: 10px 0 0 0; font-size: 16px; opacity: 0.9;">
          "I approach code with the same precision as surgery—focused, reliable, and impactful."
        </p>
      </div>
    </div>
  </foreignObject>
</svg>

<img src="https://komarev.com/ghpvc/?username=melaniereis&label=Profile%20Views&color=FF6B9D&style=for-the-badge&labelColor=0d1117" />

</div>
