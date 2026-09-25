<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Robynlee LLC | God's Chosen Warriors</title>

<meta name="description" content="Faith-based coaching for clarity, spiritual growth, discernment, identity, and personal development.">

<style>
:root{
  --ink:#171717;
  --ink2:#252525;
  --gold:#c9a45c;
  --gold2:#e2c783;
  --cream:#f7f3ea;
  --white:#fffdf8;
  --muted:#68645d;
  --line:#ded7c9;
}

*{
  box-sizing:border-box;
}

html{
  scroll-behavior:smooth;
}

body{
  margin:0;
  font-family:Arial,Helvetica,sans-serif;
  color:var(--ink);
  background:var(--cream);
  line-height:1.65;
}

a{
  text-decoration:none;
  color:inherit;
}

/* NAVIGATION */

.nav{
  position:sticky;
  top:0;
  z-index:20;
  background:linear-gradient(90deg,#241b27,#3a2944);
  color:white;
  border-bottom:1px solid rgba(244,223,215,.35);
}

.nav-inner{
  max-width:1150px;
  margin:auto;
  padding:15px 24px;
  display:flex;
  align-items:center;
  justify-content:space-between;
  gap:20px;
}

.brand{
  font-weight:800;
  letter-spacing:1.5px;
  font-size:15px;
}

.brand span{
  color:var(--gold2);
}

.navlinks{
  display:flex;
  gap:22px;
  font-size:14px;
}

.navlinks a:hover{
  color:var(--gold2);
}

/* HERO */

.hero{
  min-height:720px;
  background:
  linear-gradient(
    90deg,
    rgba(43,20,31,.92),
    rgba(83,35,55,.78),
    rgba(34,18,25,.92)
  ),
  radial-gradient(
    circle at 75% 35%,
    #9b5274 0,
    #4c2639 38%,
    #24151d 78%
  );
  color:white;
  display:flex;
  align-items:center;
  position:relative;
  overflow:hidden;
}

.hero:after{
  content:"";
  position:absolute;
  inset:0;
  background:
  repeating-linear-gradient(
    120deg,
    transparent 0 70px,
    rgba(201,164,92,.045) 70px 71px
  );
  pointer-events:none;
}

.hero-inner{
  max-width:1150px;
  width:100%;
  margin:auto;
  padding:70px 24px;
  position:relative;
  z-index:2;
  display:grid;
  grid-template-columns:1.1fr .9fr;
  gap:55px;
  align-items:center;
}

.kicker{
  color:#f4dfd7;
  font-weight:800;
  letter-spacing:4px;
  font-size:13px;
  text-transform:uppercase;
}

h1{
  font-family:Georgia,serif;
  font-size:clamp(52px,8vw,92px);
  line-height:.98;
  margin:18px 0 20px;
  max-width:760px;
}

.hero p{
  font-size:20px;
  max-width:640px;
  color:#e8e4da;
}

.buttons{
  display:flex;
  gap:14px;
  flex-wrap:wrap;
  margin-top:32px;
}

.btn{
  display:inline-block;
  padding:14px 22px;
  border:1px solid var(--gold);
  font-weight:800;
  letter-spacing:.3px;
}

.btn.gold{
  background:linear-gradient(135deg,#c98b78,#f4dfd7);
  color:#241b27;
}

.btn.dark{
  background:transparent;
  color:white;
}

/* HEADSHOT */

.hero-photo-wrap{
  display:flex;
  justify-content:center;
  align-items:center;
}

.hero-photo{
  width:min(430px,100%);
  aspect-ratio:4/5;
  object-fit:cover;
  border:5px solid rgba(244,223,215,.85);
  box-shadow:0 22px 55px rgba(0,0,0,.35);
}

/* SECTIONS */

.section{
  padding:90px 24px;
}

.container{
  max-width:1100px;
  margin:auto;
}

.eyebrow{
  text-transform:uppercase;
  letter-spacing:3px;
  color:#7c8f32;
  font-weight:800;
  font-size:12px;
}

h2{
  font-family:Georgia,serif;
  font-size:44px;
  line-height:1.1;
  margin:10px 0 18px;
}

.intro{
  font-size:18px;
  color:var(--muted);
  max-width:760px;
}

.story{
  display:grid;
  grid-template-columns:1.1fr .9fr;
  gap:60px;
  align-items:center;
}

.quote{
  background:var(--ink);
  color:white;
  padding:40px;
  border-left:5px solid #c98b78;
}

.quote p{
  font-family:Georgia,serif;
  font-size:28px;
  line-height:1.35;
  margin:0 0 18px;
}

.quote small{
  color:#f4dfd7;
  letter-spacing:1px;
}

/* DARK SECTIONS */

.dark-section{
  background:linear-gradient(135deg,#291d31,#3c2743);
  color:white;
}

.dark-section .intro{
  color:#d0ccc3;
}

/* CARDS */

.services{
  display:grid;
  grid-template-columns:repeat(3,1fr);
  gap:20px;
  margin-top:42px;
}

.card{
  background:var(--white);
  color:var(--ink);
  padding:32px;
  border:1px solid var(--line);
  display:flex;
  flex-direction:column;
}

.dark-section .card{
  background:#222;
  color:white;
  border-color:#3c3a35;
}

.card.featured{
  border:2px solid #c98b78;
  transform:translateY(-8px);
}

.card h3{
  font-family:Georgia,serif;
  font-size:27px;
  margin:7px 0;
}

.price{
  font-size:27px;
  font-weight:900;
  margin:6px 0 2px;
}

.duration{
  color:var(--muted);
  font-size:14px;
}

.dark-section .duration{
  color:#b9b5ac;
}

.card ul{
  padding-left:20px;
  color:var(--muted);
}

.dark-section .card ul{
  color:#d0ccc3;
}

.card li{
  margin:8px 0;
}

.perfect{
  margin-top:auto;
  padding-top:18px;
  font-size:14px;
  border-top:1px solid var(--line);
}

.dark-section .perfect{
  border-color:#44413b;
}

.section-title{
  text-align:center;
  max-width:760px;
  margin:0 auto;
}

/* INCLUSIONS */

.inclusions{
  display:grid;
  grid-template-columns:repeat(2,1fr);
  gap:16px;
  margin-top:38px;
}

.pill{
  padding:22px;
  background:white;
  border:1px solid var(--line);
  border-top:4px solid #a8b83f;
}

.pill strong{
  display:block;
  margin-bottom:5px;
}

/* DISCLAIMER */

.disclaimer{
  background:linear-gradient(135deg,#fffdfb,#f5e7ec);
  border:1px solid #dcc4d0;
  padding:30px;
  margin-top:35px;
}

.disclaimer h3{
  margin-top:0;
}

/* CONTACT */

.contact{
  display:grid;
  grid-template-columns:.85fr 1.15fr;
  gap:55px;
}

form{
  background:white;
  padding:32px;
  border:1px solid var(--line);
}

label{
  display:block;
  font-weight:700;
  font-size:14px;
  margin:14px 0 6px;
}

input,
select,
textarea{
  width:100%;
  padding:13px;
  border:1px solid #cfc7b8;
  background:#fffdf9;
  font:inherit;
}

textarea{
  min-height:130px;
  resize:vertical;
}

/* FOOTER */

footer{
  background:#21141a;
  color:#c9c4ba;
  padding:35px 24px;
  text-align:center;
  font-size:13px;
}

footer strong{
  color:var(--gold2);
}

/* ACCESSIBILITY */

.skip-link{
  position:absolute;
  left:-9999px;
  top:auto;
}

.skip-link:focus{
  left:12px;
  top:12px;
  z-index:100;
  padding:10px 14px;
  background:#fff;
  color:#171717;
  border:2px solid #c98b78;
}

a:focus-visible,
button:focus-visible,
input:focus-visible,
select:focus-visible,
textarea:focus-visible{
  outline:3px solid #f4dfd7;
  outline-offset:3px;
}

/* LEGAL */

.legal-links{
  margin-top:12px;
}

.legal-links a{
  text-decoration:underline;
  margin:0 7px;
}

.legal-section{
  background:#fffdf8;
}

.legal-section h3{
  font-family:Georgia,serif;
  font-size:26px;
  margin-top:28px;
}

.legal-section p,
.legal-section li{
  max-width:900px;
}

/* COOKIE */

.cookie{
  position:fixed;
  left:18px;
  right:18px;
  bottom:18px;
  z-index:80;
  background:#fffdf8;
  color:#171717;
  border:1px solid #c98b78;
  box-shadow:0 8px 30px rgba(0,0,0,.2);
  padding:20px;
  display:none;
}

.cookie.show{
  display:flex;
  gap:18px;
  align-items:center;
  justify-content:space-between;
  flex-wrap:wrap;
}

.cookie p{
  margin:0;
  max-width:760px;
}

.cookie-actions{
  display:flex;
  gap:10px;
  flex-wrap:wrap;
}

.cookie button{
  padding:11px 16px;
  border:1px solid #c98b78;
  font-weight:700;
  cursor:pointer;
}

.cookie .accept{
  background:#c98b78;
  color:#241b27;
}

.cookie .decline{
  background:white;
}

/* MOBILE */

@media(max-width:800px){

  .navlinks{
    display:none;
  }

  .hero-inner{
    grid-template-columns:1fr;
    gap:35px;
    padding:60px 24px;
  }

  .hero-photo{
    width:min(350px,100%);
  }

  .story,
  .contact{
    grid-template-columns:1fr;
  }

  .services{
    grid-template-columns:1fr;
  }

  .card.featured{
    transform:none;
  }

  .inclusions{
    grid-template-columns:1fr;
  }

  .hero{
    min-height:650px;
  }

  h2{
    font-size:36px;
  }
}

@media(prefers-reduced-motion:reduce){
  html{
    scroll-behavior:auto;
  }
}
</style>
</head>

<body>

<a class="skip-link" href="#main">
Skip to main content
</a>

<nav class="nav">
  <div class="nav-inner">

    <a class="brand" href="#top">
      ROBYNLEE <span>LLC</span>
    </a>

    <div class="navlinks">
      <a href="#mission">Mission</a>
      <a href="#about">About</a>
      <a href="services.html">Services</a>
      <a href="#sow">Sow</a>
      <a href="#boundaries">Boundaries</a>
      <a href="#contact">Contact</a>
    </div>

  </div>
</nav>

<div style="height:5px;background:linear-gradient(90deg,#c98b78 0%,#f4dfd7 25%,#a8b83f 50%,#7d5aa6 75%,#c98b78 100%);"></div>

<main id="main">

<header class="hero" id="top">

  <div class="hero-inner">

    <div>

      <div class="kicker">
        ROBYNLEE LLC • GOD'S CHOSEN WARRIORS
      </div>

      <h1>
        Warriors<br>
        Rise Here.
      </h1>

      <p>
        Faith-based coaching designed to help you find clarity,
        strengthen your identity, grow spiritually, and move forward
        with purpose.
      </p>

      <div class="buttons">

        <a class="btn gold" href="services.html">
          Explore Services
        </a>

        <a class="btn dark" href="#booking">
          Book a Session
        </a>

      </div>

    </div>

    <div class="hero-photo-wrap">

      <!-- Your existing embedded headshot is placed here -->
      <img
        class="hero-photo"
        src="YOUR_HEADSHOT_IMAGE_HERE"
        alt="Robbin Dale, founder of ROBYNLEE LLC"
      >

    </div>

  </div>

</header>


<!-- MISSION -->

<section class="section" id="mission">

  <div class="container story">

    <div>

      <div class="eyebrow">
        Our Mission
      </div>

      <h2>
        Helping Warriors Walk in Purpose
      </h2>

      <p class="intro">
        God's Chosen Warriors is a faith-based coaching experience
        created to help people gain clarity, grow in confidence,
        strengthen their spiritual foundation, and take intentional
        steps toward the life they are called to live.
      </p>

    </div>

    <div class="quote">

      <p>
        "You don't have to have everything figured out to take your
        next faithful step."
      </p>

      <small>
        GOD'S CHOSEN WARRIORS
      </small>

    </div>

  </div>

</section>


<!-- ABOUT -->

<section class="section dark-section" id="about">

  <div class="container">

    <div class="eyebrow">
      About
    </div>

    <h2>
      Faith. Clarity. Purpose.
    </h2>

    <p class="intro">
      ROBYNLEE LLC / God's Chosen Warriors provides faith-based
      life coaching focused on personal growth, spiritual development,
      identity, clarity, emotional grounding, and purposeful action.
    </p>

    <div class="inclusions">

      <div class="pill">
        <strong>Clarity</strong>
        Work through uncertainty and identify your next steps.
      </div>

      <div class="pill">
        <strong>Identity</strong>
        Build a stronger understanding of who you are and what matters
        to you.
      </div>

      <div class="pill">
        <strong>Spiritual Growth</strong>
        Create space for reflection, faith, and intentional growth.
      </div>

      <div class="pill">
        <strong>Purpose</strong>
        Turn reflection into practical action steps.
      </div>

    </div>

  </div>

</section>


<!-- SERVICES TEASER -->

<section class="section" id="coaching">

  <div class="container section-title">

    <div class="eyebrow">
      Coaching
    </div>

    <h2>
      Coaching for Your Next Chapter
    </h2>

    <p class="intro">
      Explore the coaching options created for different stages
      of your journey.
    </p>

    <div class="buttons" style="justify-content:center;">

      <a class="btn gold" href="services.html">
        View All Services
      </a>

      <a
        class="btn"
        href="https://calendly.com/robynleelife101"
        target="_blank"
        rel="noopener"
      >
        Book on Calendly
      </a>

    </div>

  </div>

</section>


<!-- SOW -->

<section class="section" id="sow">

  <div class="container">

    <div class="section-title">

      <div class="eyebrow">
        Support the Vision
      </div>

      <h2>
        Sow Into the Vision
      </h2>

      <p class="intro">
        If you feel led to support ROBYNLEE LLC / God's Chosen Warriors,
        you can sow through the options below.
      </p>

    </div>

    <div class="services" style="margin-top:42px">

      <article class="card">

        <div class="eyebrow">
          Venmo
        </div>

        <h3>
          Robynlee LLC
        </h3>

        <p>
          Use Venmo to sow into the vision.
        </p>

        <a
          class="btn gold"
          href="https://venmo.com/"
          target="_blank"
          rel="noopener"
        >
          Open Venmo
        </a>

      </article>


      <article class="card">

        <div class="eyebrow">
          Cash App
        </div>

        <h3>
          Robynlee LLC
        </h3>

        <p>
          Use Cash App to sow into the vision.
        </p>

        <a
          class="btn gold"
          href="https://cash.app/"
          target="_blank"
          rel="noopener"
        >
          Open Cash App
        </a>

      </article>

    </div>

  </div>

</section>


<!-- BOUNDARIES -->

<section class="section" id="boundaries">

  <div class="container">

    <div class="eyebrow">
      Important Information
    </div>

    <h2>
      Disclaimer & Boundaries
    </h2>

    <div class="disclaimer">

      <p>
        <strong>
          God's Chosen Warriors provides life coaching,
          not licensed mental-health care.
        </strong>
      </p>

      <p>
        <strong>Cancellation Policy:</strong>
        A minimum of 24 hours’ notice is required to cancel or
        reschedule. Cancellations made with less than 24 hours’
        notice are non-refundable.
      </p>

      <p>
        I am a Certified Life Coach, not a licensed therapist,
        counselor, or mental-health professional. Coaching is not
        a substitute for therapy, crisis intervention, or medical
        treatment.
      </p>

      <p>
        I do not provide psychological diagnosis, legal advice,
        emergency services, or crisis counseling.
      </p>

      <p>
        Coaching is forward-focused, faith-based, and designed to
        support clarity, spiritual growth, emotional grounding,
        and personal development.
      </p>

    </div>

  </div>

</section>


<!-- CALENDLY -->

<section class="section" id="booking">

  <div class="container">

    <div class="section-title">

      <div class="eyebrow">
        Book Your Session
      </div>

      <h2>
        Schedule Your Session
      </h2>

      <p class="intro">
        Use the calendar below to schedule your coaching session
        through Calendly.
      </p>

    </div>

    <div
      style="
      min-width:320px;
      height:760px;
      border-radius:22px;
      overflow:hidden;
      background:#fff;
      box-shadow:0 18px 45px rgba(0,0,0,.12);
      "
    >

      <iframe
        src="https://calendly.com/robynleelife101?hide_gdpr_banner=1"
        width="100%"
        height="100%"
        frameborder="0"
        title="Schedule a coaching session with Robynlee LLC">
      </iframe>

    </div>

  </div>

</section>


<!-- CONTACT -->

<section class="section dark-section" id="contact">

  <div class="container contact">

    <div>

      <div class="eyebrow">
        Take Your Next Step
      </div>

      <h2>
        Ready to rise?
      </h2>

      <p class="intro">
        If you're looking for faith-based coaching and a place
        to work through your next steps with purpose and intention,
        reach out below.
      </p>

      <p>
        <strong>
          Warriors rise here.
        </strong>
      </p>

      <p style="margin-top:24px">

        <a
          class="btn gold"
          href="https://calendly.com/robynleelife101"
          target="_blank"
          rel="noopener"
        >
          Book on Calendly
        </a>

      </p>

      <p class="duration">

        Or email

        <a
          href="mailto:robynleelife101@gmail.com"
          style="text-decoration:underline"
        >
          robynleelife101@gmail.com
        </a>

      </p>

    </div>


    <form
      action="mailto:robynleelife101@gmail.com"
      method="post"
      enctype="text/plain"
    >

      <label for="name">
        Name
      </label>

      <input
        id="name"
        name="Name"
        placeholder="Your name"
        required
      >


      <label for="email">
        Email
      </label>

      <input
        id="email"
        type="email"
        name="Email"
        placeholder="you@example.com"
        required
      >


      <label for="service">
        Interested in
      </label>

      <select
        id="service"
        name="Service"
      >

        <option>
          Warrior Clarity Session — $119
        </option>

        <option>
          Warrior Alignment Package — $335
        </option>

        <option>
          Warrior Restoration Package — $550
        </option>

        <option>
          I'm not sure yet
        </option>

      </select>


      <label for="message">
        Message
      </label>

      <textarea
        id="message"
        name="Message"
        placeholder="Tell me a little about what you're looking for..."
      ></textarea>


      <button
        class="btn gold"
        type="submit"
        style="margin-top:18px;cursor:pointer"
      >
        Send Inquiry
      </button>

      <p
        class="duration"
        style="margin-top:12px"
      >
        Inquiries will be sent to
        robynleelife101@gmail.com.
      </p>

    </form>

  </div>

</section>

</main>


<!-- PRIVACY -->

<section class="section legal-section" id="privacy">

  <div class="container">

    <div class="eyebrow">
      Privacy
    </div>

    <h2>
      Privacy Policy
    </h2>

    <p>
      <strong>
        Effective date: September 18, 2026.
      </strong>
      This Privacy Policy explains how ROBYNLEE LLC /
      God's Chosen Warriors may handle information submitted
      through this website.
    </p>

    <h3>
      Information You Provide
    </h3>

    <p>
      If you submit an inquiry, you may provide your name,
      email address, the coaching service you are interested in,
      and information included in your message.
    </p>

    <h3>
      How Information Is Used
    </h3>

    <p>
      Information may be used to respond to inquiries,
      communicate about requested coaching services,
      schedule services, process transactions when applicable,
      and maintain business records.
    </p>

    <h3>
      Cookies
    </h3>

    <p>
      This website uses a consent banner for non-essential cookies.
      Essential website functions may operate without consent.
    </p>

    <h3>
      Sharing
    </h3>

    <p>
      Information may be shared with service providers needed
      to operate the website or deliver requested services,
      and when required by law.
    </p>

    <h3>
      Contact
    </h3>

    <p>
      For privacy questions or requests concerning information
      submitted through this site, use the website inquiry form
      or the business contact information provided by ROBYNLEE LLC.
    </p>

  </div>

</section>


<!-- TERMS -->

<section class="section legal-section" id="terms">

  <div class="container">

    <div class="eyebrow">
      Website Terms
    </div>

    <h2>
      Terms & Conditions
    </h2>

    <p>
      <strong>
        Effective date: September 18, 2026.
      </strong>
      By using this website, you agree to use it lawfully
      and respectfully.
    </p>

    <h3>
      Coaching Services
    </h3>

    <p>
      God's Chosen Warriors provides faith-based life coaching
      and personal-development support. Coaching is not psychotherapy,
      medical treatment, legal advice, financial advice, emergency care,
      or a substitute for licensed professional services.
    </p>

    <h3>
      Payments, Scheduling & Cancellations
    </h3>

    <p>
      Prices displayed on the website are subject to change.
      A booking is not confirmed until ROBYNLEE LLC confirms it
      through its applicable scheduling or payment process.
      A minimum of 24 hours’ notice is required to cancel or
      reschedule a session. Cancellations made with less than
      24 hours’ notice are non-refundable.
    </p>

    <h3>
      Client Responsibility
    </h3>

    <p>
      Clients are responsible for their own decisions and actions.
      Coaching provides reflection, education, encouragement,
      and practical tools; outcomes are not guaranteed.
    </p>

    <h3>
      Website Content
    </h3>

    <p>
      Website text, branding, graphics, and original materials
      belong to ROBYNLEE LLC unless otherwise indicated and may
      not be reproduced or redistributed without permission.
    </p>

  </div>

</section>


<!-- ACCESSIBILITY -->

<section class="section legal-section" id="accessibility">

  <div class="container">

    <div class="eyebrow">
      Accessibility
    </div>

    <h2>
      Accessibility Statement
    </h2>

    <p>
      ROBYNLEE LLC is committed to making this website usable
      by people with different abilities.
    </p>

    <p>
      If you encounter an accessibility barrier, please contact
      ROBYNLEE LLC through the inquiry form and describe the page
      or feature and the difficulty you experienced.
    </p>

  </div>

</section>


<!-- FOOTER -->

<footer>

  <strong>
    ROBYNLEE LLC
  </strong>

  <br>

  Warriors Rise Here • Faith-based Life Coaching

  <br><br>

  © 2026 God's Chosen Warriors. All rights reserved.

  <div class="legal-links">

    <a href="#privacy">
      Privacy Policy
    </a>

    ·

    <a href="#terms">
      Terms & Conditions
    </a>

    ·

    <a href="#accessibility">
      Accessibility
    </a>

  </div>

</footer>


<!-- COOKIE NOTICE -->

<div
  id="cookieOverlay"
  style="
  position:fixed;
  inset:0;
  z-index:79;
  background:rgba(20,15,20,.58);
  display:none;
  "
></div>


<div
  class="cookie"
  id="cookieBanner"
  role="dialog"
  aria-label="Cookie consent"
>

  <p>

    <strong>
      Cookie Notice:
    </strong>

    This website may use essential cookies and,
    if enabled in the future, non-essential cookies
    such as analytics or embedded service cookies.

  </p>


  <div class="cookie-actions">

    <button
      class="decline"
      type="button"
      onclick="setCookieChoice('declined')"
    >
      Decline
    </button>

    <button
      class="accept"
      type="button"
      onclick="setCookieChoice('accepted')"
    >
      Accept
    </button>

  </div>

</div>


<script>

function setCookieChoice(choice){

  localStorage.setItem(
    'robynleeCookieConsent',
    choice
  );

  document
    .getElementById('cookieBanner')
    .classList.remove('show');

  document
    .getElementById('cookieOverlay')
    .style.display='none';
}


(function(){

  if(!localStorage.getItem('robynleeCookieConsent')){

    document
      .getElementById('cookieBanner')
      .classList.add('show');

    document
      .getElementById('cookieOverlay')
      .style.display='block';

  }

})();

</script>

</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Services | ROBYNLEE LLC</title>

  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: Georgia, "Times New Roman", serif;
      background: linear-gradient(135deg, #fff7fb, #fce4ef, #fffafc);
      color: #4a3040;
      line-height: 1.6;
    }

    header {
      background: linear-gradient(135deg, #d8a0b8, #f3d7e3, #fff);
      padding: 25px 20px;
      text-align: center;
      border-bottom: 2px solid #c58ca6;
    }

    .logo {
      font-size: 32px;
      font-weight: bold;
      letter-spacing: 3px;
      color: #7d405c;
    }

    .tagline {
      margin-top: 5px;
      font-size: 15px;
      color: #684052;
      font-style: italic;
    }

    nav {
      margin-top: 18px;
    }

    nav a {
      text-decoration: none;
      color: #6d3850;
      font-weight: bold;
      margin: 0 12px;
      font-size: 15px;
    }

    nav a:hover {
      color: #b36b8b;
    }

    .hero {
      text-align: center;
      padding: 70px 20px 45px;
    }

    .hero h1 {
      font-size: 48px;
      color: #7d405c;
      margin-bottom: 15px;
    }

    .hero p {
      max-width: 700px;
      margin: auto;
      font-size: 18px;
      color: #654554;
    }

    .services {
      max-width: 1100px;
      margin: 20px auto 70px;
      padding: 0 20px;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 28px;
    }

    .service-card {
      background: rgba(255, 255, 255, 0.9);
      border: 1px solid #e3b7ca;
      border-radius: 20px;
      padding: 32px 28px;
      box-shadow: 0 8px 25px rgba(125, 64, 92, 0.12);
      text-align: center;
      transition: transform 0.25s ease, box-shadow 0.25s ease;
    }

    .service-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 12px 30px rgba(125, 64, 92, 0.18);
    }

    .service-card h2 {
      color: #874964;
      font-size: 25px;
      margin-bottom: 8px;
    }

    .price {
      color: #b06c89;
      font-size: 21px;
      font-weight: bold;
      margin-bottom: 18px;
    }

    .service-card p {
      color: #5e4651;
      margin-bottom: 20px;
    }

    .book-button {
      display: inline-block;
      background: linear-gradient(135deg, #b87592, #d8a0b8);
      color: white;
      padding: 12px 25px;
      border-radius: 30px;
      text-decoration: none;
      font-weight: bold;
      border: none;
      cursor: pointer;
      transition: 0.2s;
    }

    .book-button:hover {
      background: #9f5f7d;
      transform: scale(1.03);
    }

    .bottom-section {
      text-align: center;
      padding: 55px 20px;
      background: linear-gradient(135deg, #f3d7e3, #fff);
      border-top: 1px solid #e1b5c8;
    }

    .bottom-section h2 {
      color: #7d405c;
      font-size: 32px;
      margin-bottom: 12px;
    }

    .bottom-section p {
      max-width: 650px;
      margin: 0 auto 25px;
    }

    footer {
      text-align: center;
      padding: 25px;
      background: #7d405c;
      color: white;
      font-size: 14px;
    }

    @media (max-width: 600px) {
      .hero h1 {
        font-size: 38px;
      }

      .logo {
        font-size: 26px;
      }

      nav a {
        display: inline-block;
        margin: 5px 8px;
      }
    }
  </style>
</head>

<body>

  <!-- HEADER -->
  <header>
    <div class="logo">ROBYNLEE LLC</div>
    <div class="tagline">
      Clarity • Confidence • Purpose
    </div>

    <nav>
      <a href="index.html">Home</a>
      <a href="services.html">Services</a>
      <a href="index.html#about">About</a>
      <a href="index.html#contact">Contact</a>
    </nav>
  </header>


  <!-- HERO -->
  <section class="hero">
    <h1>Services</h1>

    <p>
      Personalized coaching sessions designed to help you gain clarity,
      strengthen your confidence, and move forward with purpose.
    </p>
  </section>


  <!-- SERVICES -->
  <section class="services">

    <!-- SERVICE 1 -->
    <div class="service-card">
      <h2>Warrior Clarity Session</h2>

      <div class="price">
        50 Minutes — $119.00
      </div>

      <p>
        A single, powerful coaching session designed to help you gain
        immediate clarity, identify what may be holding you back, and
        create a focused path forward.
      </p>

      <a
        class="book-button"
        href="YOUR_CALENDLY_LINK_HERE"
        target="_blank"
        rel="noopener noreferrer">
        Book Your Session
      </a>
    </div>


    <!-- SERVICE 2 -->
    <div class="service-card">
      <h2>Personal Growth Session</h2>

      <div class="price">
        50 Minutes
      </div>

      <p>
        A personalized session focused on self-development, confidence,
        mindset, goals, and creating positive steps toward the life you
        want to build.
      </p>

      <a
        class="book-button"
        href="YOUR_CALENDLY_LINK_HERE"
        target="_blank"
        rel="noopener noreferrer">
        Book Your Session
      </a>
    </div>


    <!-- SERVICE 3 -->
    <div class="service-card">
      <h2>Purpose & Direction Session</h2>

      <div class="price">
        50 Minutes
      </div>

      <p>
        Gain perspective on your goals and priorities while creating
        practical next steps that align with your personal direction
        and purpose.
      </p>

      <a
        class="book-button"
        href="YOUR_CALENDLY_LINK_HERE"
        target="_blank"
        rel="noopener noreferrer">
        Book Your Session
      </a>
    </div>

  </section>


  <!-- BOOKING CTA -->
  <section class="bottom-section">

    <h2>Ready to Take the Next Step?</h2>

    <p>
      Your next chapter starts with one decision. Choose a time that works
      for you and let's begin your journey toward greater clarity,
      confidence, and purpose.
    </p>

    <a
      class="book-button"
      href="calendly.com/robynleelife101"
      target="_blank"
      rel="noopener noreferrer">
      Schedule a Session
    </a>

  </section>


  <!-- FOOTER -->
  <footer>
    © 2026 ROBYNLEE LLC. All Rights Reserved.
  </footer>

</body>
</html>