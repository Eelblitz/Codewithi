<!DOCTYPE html>
<html lang="en">
<body>
  <header>
    <h1>MOHAMMED ISAH ATTAH</h1>
    <p>Website Designer | UI/UX Designer | Software Engineer | Data Analyst</p>
  </header>

  <nav>
    <a onclick="showPage('home')">Home</a>
    <a onclick="showPage('about')">About</a>
    <a onclick="showPage('skills')">Skills</a>
    <a onclick="showPage('services')">Services</a>
    <a onclick="showPage('projects')">Projects</a>
    <a onclick="showPage('testimonials')">Testimonials</a>
    <a onclick="showPage('contact')">Contact</a>
  </nav>

  <section id="home" class="section active">
    <h2>Introduction</h2>
    <p>I am a Website Designer, UI/UX Designer, Software Engineer, Content Creator, Database Manager, and Data Analyst dedicated to building digital experiences that help people connect with the products and services they need.</p>
    <p>I specialize in user‑centered interfaces, scalable web solutions, and data insights that support business growth.</p>
    <p>I have contributed to projects for CCigol System, Nasarawa State College of Health Sciences and Technology, and BusinessInward.</p>
  </section>
  
  <section id="skills" class="section">
    <h2>Skills</h2>
    <div class="skills-list">
      <div class="card">HTML, CSS, JavaScript</div>
      <div class="card">Python, R Programming</div>
      <div class="card">UI/UX Design</div>
      <div class="card">WordPress Development</div>
      <div class="card">Database Management</div>
      <div class="card">Data Analysis</div>
    </div>
  </section>

  <section id="services" class="section">
    <h2>Services</h2>
    <div class="services-list">
      <div class="card">Website Design</div>
      <div class="card">Custom Web Development</div>
      <div class="card">Business Websites</div>
      <div class="card">Portfolio Sites</div>
      <div class="card">Website Maintenance</div>
      <div class="card">UI/UX Improvements</div>
    </div>
  </section>
  <section id="testimonials" class="section">
    <h2>Testimonials</h2>
    <div class="testimonials">
      <div class="card">“Reliable and creative. Delivers exactly what we need.”</div>
      <div class="card">“Strong technical skill and easy to work with.”</div>
      <div class="card">“Our digital engagement improved after his work.”</div>
      <div class="card">“Professional, responsive, and detail‑oriented.”</div>
    </div>
  </section>

  <section id="contact" class="section">
    <h2>Contact</h2>
    <p>Phone: 07088880704</p>
    <p>Email: codewithiman@gmail.com</p>
    <form>
      <input type="text" placeholder="Your Name" required>
      <input type="email" placeholder="Your Email" required>
      <textarea placeholder="Message" rows="4" required></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>© 2025 Mohammed Isah Attah | codewithiman@gmail.com</p>
  </footer>

  <script>
    function showPage(pageId) {
      document.querySelectorAll('.section').forEach(sec => sec.classList.remove('active'));
      document.getElementById(pageId).classList.add('active');
    }
  </script>
</body>
</html>
