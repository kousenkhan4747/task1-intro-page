# task1-intro-page
Personal Introduction Page  Webora Tec Internship Task 1
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kousen Khan | Personal Introduction</title>
  <style>
* { box-sizing: border-box; margin: 0; padding: 0; }

body {
  font-family: "Segoe UI", Arial, sans-serif;
  background: #f1f5f9;
  color: #1e293b;
  line-height: 1.6;
}

.hero {
  background: linear-gradient(135deg, #4f46e5, #06b6d4);
  color: #fff;
  text-align: center;
  padding: 50px 20px 40px;
}
.avatar {
  width: 140px; height: 140px;
  border-radius: 50%;
  border: 5px solid #fff;
  margin-bottom: 15px;
}
.hero h1 { font-size: 2.4rem; }
.tagline { font-size: 1.15rem; opacity: .95; margin-bottom: 12px; }
.intro { max-width: 560px; margin: 0 auto; }

main { max-width: 800px; margin: 30px auto; padding: 0 16px; }

.card {
  background: #fff;
  border: 1px solid #e2e8f0;
  border-left: 6px solid #4f46e5;
  border-radius: 10px;
  padding: 24px;
  margin-bottom: 24px;
}
.card h2 { color: #4f46e5; margin-bottom: 12px; }
.card ul { padding-left: 20px; margin-top: 10px; }
.card li { margin-bottom: 6px; }

.skill { margin-bottom: 14px; }
.skill-head { display: flex; justify-content: space-between; font-weight: 600; margin-bottom: 4px; }
.bar { background: #e2e8f0; border-radius: 20px; height: 12px; overflow: hidden; }
.fill { background: linear-gradient(90deg, #4f46e5, #06b6d4); height: 100%; border-radius: 20px; }

.tags { margin-top: 18px; display: flex; flex-wrap: wrap; gap: 8px; }
.tags span {
  background: #eef2ff; color: #4338ca;
  border: 1px solid #c7d2fe;
  padding: 4px 12px; border-radius: 20px; font-size: .9rem;
}

.contact-list { list-style: none; padding-left: 0 !important; }
.contact-list a { color: #4f46e5; text-decoration: none; word-break: break-all; }
.contact-list a:hover { text-decoration: underline; }

footer { text-align: center; padding: 20px; color: #64748b; font-size: .9rem; }

@media (max-width: 600px) {
  .hero h1 { font-size: 1.8rem; }
  .avatar { width: 110px; height: 110px; }
  .card { padding: 18px; }
}

/* extra rules for updated content */
.hello { opacity: .9; }
.card p { margin-bottom: 10px; }
.other { margin-top: 16px; color: #475569; }
.card a { color: #4f46e5; word-break: break-all; }
</style>
</head>
<body>

  <header class="hero">
    <img src="data:image/svg+xml;charset=utf-8,%3Csvg%20xmlns%3D%22http%3A//www.w3.org/2000/svg%22%20viewBox%3D%220%200%20200%20200%22%20width%3D%22200%22%20height%3D%22200%22%3E%0A%20%20%3Cdefs%3E%3ClinearGradient%20id%3D%22g%22%20x1%3D%220%22%20y1%3D%220%22%20x2%3D%221%22%20y2%3D%221%22%3E%3Cstop%20offset%3D%220%22%20stop-color%3D%22%234f46e5%22/%3E%3Cstop%20offset%3D%221%22%20stop-color%3D%22%2306b6d4%22/%3E%3C/linearGradient%3E%3C/defs%3E%0A%20%20%3Crect%20width%3D%22200%22%20height%3D%22200%22%20rx%3D%22100%22%20fill%3D%22url%28%23g%29%22/%3E%0A%20%20%3Ctext%20x%3D%22100%22%20y%3D%22122%22%20text-anchor%3D%22middle%22%20font-family%3D%22Arial%2C%20sans-serif%22%20font-size%3D%2272%22%20font-weight%3D%22700%22%20fill%3D%22%23fff%22%3EKK%3C/text%3E%0A%3C/svg%3E%0A" alt="Profile picture of Kousen Khan" class="avatar">
    <p class="hello">Hello, I’m</p>
    <h1>Kousen Khan</h1>
    <p class="tagline">First Year Computer Science Engineering Student | Web Development Intern at Webora Tec</p>
  </header>

  <main>
    <section id="about" class="card">
      <h2>About</h2>
      <p>I’m a first-year Computer Science Engineering student interested in Artificial Intelligence and web development.</p>
      <p>I’m currently a Web Development intern at Webora Tec, where I work on assigned tasks to build my practical skills.</p>
      <p>My goal is to strengthen my technical knowledge, build projects, and gain hands-on experience in tech. I’m eager to learn new technologies and explore future internship opportunities.</p>
    </section>

    <section id="skills" class="card">
      <h2>Skills</h2>
      <div class="skill">
        <div class="skill-head"><span>HTML</span><span>70%</span></div>
        <div class="bar"><div class="fill" style="width:70%"></div></div>
      </div>
      <div class="skill">
        <div class="skill-head"><span>CSS</span><span>60%</span></div>
        <div class="bar"><div class="fill" style="width:60%"></div></div>
      </div>
      <div class="skill">
        <div class="skill-head"><span>JavaScript</span><span>50%</span></div>
        <div class="bar"><div class="fill" style="width:50%"></div></div>
      </div>
      <div class="skill">
        <div class="skill-head"><span>Problem Solving</span><span>60%</span></div>
        <div class="bar"><div class="fill" style="width:60%"></div></div>
      </div>
      <p class="other">Also: Canva designing, basic web development, creativity.</p>
    </section>

    <section id="contact" class="card">
      <h2>Contact</h2>
      <p>Email: <a href="mailto:kousenkhan47@gmail.com">kousenkhan47@gmail.com</a></p>
      <p>LinkedIn: <a href="https://www.linkedin.com/in/kousen-khan" target="_blank" rel="noopener">linkedin.com/in/kousen-khan</a></p>
      <p>GitHub: <a href="https://github.com/kousenkhan4747" target="_blank" rel="noopener">github.com/kousenkhan4747</a></p>
    </section>
  </main>

  <footer>© 2026 Kousen Khan</footer>
</body>
</html>
