<template>
  <div>
    <!-- <NuxtRouteAnnouncer />
    <NuxtWelcome /> -->

    <header>
      <div class="wrap nav">
        <a class="brand" href="#top" aria-label="Mediverse Polyclinic Home">
          <img src="" alt="Mediverse Polyclinic logo" />
          <div class="name">Mediverse Polyclinic</div>
        </a>

        <nav aria-label="Primary">
          <ul>
            <li><a href="#services">Services</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
            <li><a class="btn primary" href="#contact">Book Appointment</a></li>
          </ul>
        </nav>
      </div>
    </header>

    <main id="top">
      <div class="wrap hero">
        <div class="hero-grid">
          <div class="hero-card">
            <div class="badge">● Open Today • Walk-ins Welcome</div>
            <h1>Modern care, close to home.</h1>
            <p class="lead">
              Welcome to <b>Mediverse Polyclinic</b>. We provide compassionate, reliable medical services with a
              patient-first approach.
              Book an appointment, or visit us for walk-in consultations.
            </p>

            <div class="actions">
              <a class="btn primary" href="#contact">Book Now</a>
              <a class="btn ghost" href="#services">View Services</a>
            </div>

            <!-- <p class="muted" style="margin-top:14px; font-size:13px;">
              Tip: Replace phone, address, hours, and services with your real clinic details.
            </p> -->
          </div>

          <aside class="info-card">
            <div class="info-row">
              <b>Phone</b>
              <div class="muted">+91 98342 47540 / +91 90280 96828</div>
            </div>
            <div class="info-row">
              <b>Address</b>
              <div class="muted">S.no 63/2, 64/7, Silver Residency, Shop no. 2, Ravet, Pune</div>
            </div>
            <div class="info-row">
              <b>Hours</b>
              <div class="muted">Mon–Sat: 9:00 AM – 8:00 PM</div>
            </div>
            <div class="info-row">
              <b>Email</b>
              <div class="muted">sachincharhate@gmail.com</div>
            </div>
          </aside>
        </div>
      </div>

      <section id="services">
        <div class="wrap">
          <div class="section-title">
            <div>
              <h2>Services</h2>
              <p>Common services offered at a polyclinic (edit as needed).</p>
            </div>
          </div>

          <div class="grid">
            <div class="card">
              <div class="pill">General Medicine</div>
              <h3>Consultations & Follow-ups</h3>
              <p class="muted">Diagnosis, treatment plans, chronic condition management, and preventive care.</p>
            </div>

            <div class="card">
              <div class="pill">Diagnostics</div>
              <h3>Basic Lab Tests</h3>
              <p class="muted">Routine blood work and common screenings (availability depends on your setup).</p>
            </div>

            <div class="card">
              <div class="pill">Primary Care</div>
              <h3>Vaccinations & Wellness</h3>
              <p class="muted">Health checks, immunizations, and lifestyle guidance for long-term wellbeing.</p>
            </div>
          </div>
        </div>
      </section>

      <section id="about">
        <div class="wrap">
          <div class="section-title">
            <div>
              <h2>About Mediverse Polyclinic</h2>
              <p>Short intro about your clinic, team, and mission.</p>
            </div>
          </div>

          <div class="card">
            <p class="muted" style="margin:0;">
              Mediverse Polyclinic is dedicated to providing accessible, high-quality healthcare with a focus on
              comfort, clarity,
              and continuity of care. Add your doctors’ names, qualifications, and specialties here.
            </p>
          </div>
        </div>
      </section>

      <section id="contact">
        <div class="wrap">
          <div class="section-title">
            <div>
              <h2>Contact & Appointment</h2>
              <p>Use this form for inquiries (connect it to your backend/email service).</p>
            </div>
          </div>

          <div class="contact">
            <div class="card">
              <h3 style="margin-top:0;">Send a message</h3>
              <form class="form"
                onsubmit="event.preventDefault(); alert('Thanks! Connect this form to email/WhatsApp/CRM.');">
                <input required type="text" placeholder="Full Name" />
                <input required type="tel" placeholder="Phone Number" />
                <input type="email" placeholder="Email (optional)" />
                <textarea rows="4" placeholder="How can we help?"></textarea>
                <button class="btn primary" type="submit">Submit</button>
              </form>
            </div>

            <div class="card">
              <h3 style="margin-top:0;">Visit us</h3>
              <p class="muted"><b>Address:</b> S.no 63/2, 64/7, Silver Residency, Shop no. 2, Ravet, Pune</p>
              <p class="muted"><b>Phone:</b> +91 98342 47540 / +91 90280 96828</p>
              <p class="muted"><b>Hours:</b> Mon–Sat: 9:00 AM – 8:00 PM</p>
              <p class="muted"><b>Directions:</b> 
              <a href="https://www.justdial.com/Pune/Mediverse-Polyclinic-Near-Sameer-Lawns-Ravet/020PXX20-XX20-230304231204-G5H5_BZDET" target="_blank" style="text-decoration: underline;">Directions</a></p>

              <div style="display:flex; gap:12px; flex-wrap:wrap; margin-top:10px;">
                <a class="btn ghost" href="tel:+919834247540">Call Now</a>
                <a class="btn ghost" href="mailto:sachincharhate@gmail.com">Email</a>
                <a class="btn primary" href="#top">Back to Top</a>
              </div>
            </div>
          </div>
        </div>
      </section>
    </main>

    <footer>
      <div class="wrap">
        <div style="display:flex; align-items:center; justify-content:space-between; gap:12px; flex-wrap:wrap;">
          <div>© <span id="y"></span> Mediverse Polyclinic. All rights reserved.</div>
          <div class="muted">Designed with your logo • Background: transparent</div>
        </div>
      </div>
    </footer>

  </div>
</template>


<style>
:root {
  --brand-blue: #132573;
  --brand-green: #6bbf3a;
  --text: #0f172a;
  --muted: #475569;
  --card: #ffffff;
  --border: rgba(15, 23, 42, .10);
  --shadow: 0 10px 30px rgba(2, 6, 23, .10);
  --radius: 18px;
  --max: 1100px;
}

/* Transparent background (requested) */
html,
body {
  background: transparent;
}

* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, "Apple Color Emoji", "Segoe UI Emoji";
  color: var(--text);
  line-height: 1.55;
}

a {
  color: inherit;
  text-decoration: none;
}

.wrap {
  max-width: var(--max);
  margin: 0 auto;
  padding: 0 18px;
}

/* Top bar */
header {
  position: sticky;
  top: 0;
  z-index: 50;
  backdrop-filter: blur(10px);
  background: rgba(255, 255, 255, .72);
  border-bottom: 1px solid var(--border);
}

.nav {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 14px;
  padding: 12px 0;
}

.brand {
  display: flex;
  align-items: center;
  gap: 12px;
  min-width: 240px;
}

.brand img {
  height: 44px;
  width: auto;
  display: block;
}

.brand .name {
  font-weight: 800;
  letter-spacing: .2px;
}

nav ul {
  display: flex;
  gap: 14px;
  align-items: center;
  list-style: none;
  padding: 0;
  margin: 0;
  flex-wrap: wrap;
  justify-content: flex-end;
}

nav a {
  padding: 10px 10px;
  border-radius: 12px;
  color: var(--muted);
  font-weight: 600;
}

nav a:hover {
  background: rgba(42, 163, 214, .10);
  color: var(--text);
}

.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 10px 14px;
  border-radius: 14px;
  border: 1px solid var(--border);
  background: #fff;
  box-shadow: 0 8px 18px rgba(2, 6, 23, .06);
  font-weight: 800;
  gap: 10px;
  cursor: pointer;
}

.btn.primary {
  background: var(--brand-blue);
  color: #fff;
  border-color: rgba(255, 255, 255, .25);
}

.btn.primary:hover {
  filter: brightness(.98);
}

.btn.ghost:hover {
  background: rgba(42, 163, 214, .10);
}

/* Hero */
.hero {
  padding: 42px 0 10px;
}

.hero-grid {
  display: grid;
  grid-template-columns: 1.2fr .8fr;
  gap: 18px;
  align-items: stretch;
}

.hero-card {
  background: rgba(255, 255, 255, .78);
  border: 1px solid var(--border);
  border-radius: var(--radius);
  box-shadow: var(--shadow);
  padding: 24px;
  overflow: hidden;
  position: relative;
}

.badge {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  background: rgba(107, 191, 58, .10);
  border: 1px solid rgba(107, 191, 58, .25);
  color: #14532d;
  padding: 6px 10px;
  border-radius: 999px;
  font-weight: 800;
  font-size: 13px;
}

h1 {
  margin: 14px 0 8px;
  font-size: clamp(28px, 4vw, 46px);
  line-height: 1.05;
  letter-spacing: -.5px;
}

.lead {
  margin: 10px 0 18px;
  color: var(--muted);
  font-size: 16.5px;
  max-width: 62ch;
}

.actions {
  display: flex;
  gap: 12px;
  flex-wrap: wrap;
  margin-top: 8px;
}

.info-card {
  display: flex;
  flex-direction: column;
  gap: 12px;
  background: rgba(255, 255, 255, .78);
  border: 1px solid var(--border);
  border-radius: var(--radius);
  box-shadow: var(--shadow);
  padding: 18px;
}

.info-row {
  border: 1px dashed rgba(15, 23, 42, .18);
  border-radius: 14px;
  padding: 12px 12px;
  background: rgba(255, 255, 255, .55);
}

.info-row b {
  display: block;
}

.muted {
  color: var(--muted);
}

/* Sections */
section {
  padding: 22px 0;
}

.section-title {
  display: flex;
  align-items: end;
  justify-content: space-between;
  gap: 12px;
  margin-bottom: 12px;
}

.section-title h2 {
  margin: 0;
  font-size: 24px;
  letter-spacing: -.2px;
}

.section-title p {
  margin: 0;
  color: var(--muted);
}

.grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 14px;
}

.card {
  background: rgba(255, 255, 255, .78);
  border: 1px solid var(--border);
  border-radius: var(--radius);
  box-shadow: 0 12px 28px rgba(2, 6, 23, .08);
  padding: 16px;
  min-height: 140px;
}

.card h3 {
  margin: 6px 0 8px;
  font-size: 18px;
}

.pill {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  font-weight: 800;
  font-size: 12px;
  color: rgba(15, 23, 42, .80);
  background: rgba(42, 163, 214, .10);
  border: 1px solid rgba(42, 163, 214, .25);
  padding: 5px 10px;
  border-radius: 999px;
}

/* Contact */
.contact {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 14px;
}

.form {
  display: grid;
  gap: 10px;
}

input,
textarea {
  width: 100%;
  padding: 12px 12px;
  border-radius: 14px;
  border: 1px solid var(--border);
  background: rgba(255, 255, 255, .85);
  font: inherit;
  outline: none;
}

input:focus,
textarea:focus {
  border-color: rgba(42, 163, 214, .45);
  box-shadow: 0 0 0 4px rgba(42, 163, 214, .12);
}

footer {
  padding: 22px 0 34px;
  color: var(--muted);
  border-top: 1px solid var(--border);
  background: rgba(255, 255, 255, .55);
}

/* Responsive */
@media (max-width: 900px) {
  .hero-grid {
    grid-template-columns: 1fr;
  }

  .grid {
    grid-template-columns: 1fr;
  }

  .contact {
    grid-template-columns: 1fr;
  }

  .brand .name {
    display: none;
  }
}
</style>