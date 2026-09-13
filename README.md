[!DOCTYPE html.html](https://github.com/user-attachments/files/32154440/DOCTYPE.html.html)
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>SDU Consultancy | Papua New Guinea</title>

<meta name="description" content="SDU Consultancy empowers people, supports organizations, and delivers practical solutions for sustainable development in Papua New Guinea.">

<style>
:root {
    --teal: #008f91;
    --teal-dark: #05686b;
    --teal-deep: #073f42;
    --teal-light: #eaf7f6;

    --orange: #f28b20;
    --orange-dark: #d86f08;
    --orange-light: #fff2df;

    --white: #ffffff;
    --cream: #fbfaf7;
    --ink: #173b3d;
    --text: #5d7070;
    --border: #dce9e8;

    --shadow-sm: 0 8px 25px rgba(15, 68, 70, 0.07);
    --shadow-lg: 0 22px 60px rgba(15, 68, 70, 0.12);

    --radius: 24px;
    --max-width: 1180px;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    scroll-behavior: smooth;
}

body {
    font-family:
        Inter,
        -apple-system,
        BlinkMacSystemFont,
        "Segoe UI",
        Roboto,
        Helvetica,
        Arial,
        sans-serif;

    background: var(--cream);
    color: var(--text);
    line-height: 1.7;
}

body,
button,
input,
textarea,
select {
    -webkit-font-smoothing: antialiased;
}

img {
    max-width: 100%;
    display: block;
}

a {
    color: inherit;
    text-decoration: none;
}

button,
input,
textarea,
select {
    font: inherit;
}

.container {
    width: min(var(--max-width), 92%);
    margin: 0 auto;
}

section {
    position: relative;
}

.section {
    padding: 100px 0;
}

.section-white {
    background: var(--white);
}

/* =========================================================
   TOP BAR
========================================================= */

.top-bar {
    background: var(--teal-deep);
    color: #dceeed;
    font-size: 13px;
}

.top-bar-inner {
    min-height: 38px;

    display: flex;
    align-items: center;
    justify-content: space-between;

    gap: 20px;
}

.top-bar a:hover {
    color: var(--white);
}

/* =========================================================
   NAVIGATION
========================================================= */

.header {
    position: sticky;
    top: 0;
    z-index: 1000;

    background: rgba(255, 255, 255, 0.96);
    backdrop-filter: blur(15px);

    border-bottom: 1px solid var(--border);
}

.navbar {
    min-height: 82px;

    display: flex;
    align-items: center;
    justify-content: space-between;

    gap: 30px;
}

.brand {
    display: flex;
    align-items: center;
    gap: 13px;
}

.brand-logo {
    width: 60px;
    height: 60px;

    object-fit: contain;
}

.brand-name {
    color: var(--ink);

    font-size: 19px;
    font-weight: 850;

    letter-spacing: -0.02em;
}

.brand-name span {
    color: var(--orange);
}

.navigation {
    display: flex;
    align-items: center;
    gap: 28px;
}

.navigation a {
    color: var(--ink);

    font-size: 14px;
    font-weight: 700;

    transition: 0.2s ease;
}

.navigation a:hover {
    color: var(--teal);
}

.navigation .nav-contact {
    color: var(--white);
    background: var(--teal);

    padding: 11px 19px;

    border-radius: 999px;
}

.navigation .nav-contact:hover {
    background: var(--teal-dark);
    color: var(--white);
}

.menu-button {
    display: none;

    background: transparent;
    border: 0;

    color: var(--ink);

    font-size: 27px;

    cursor: pointer;
}

/* =========================================================
   HERO
========================================================= */

.hero {
    overflow: hidden;

    background:
        radial-gradient(
            circle at 88% 15%,
            rgba(242, 139, 32, 0.17),
            transparent 26%
        ),
        radial-gradient(
            circle at 8% 85%,
            rgba(0, 143, 145, 0.13),
            transparent 28%
        ),
        linear-gradient(
            135deg,
            #eff9f8 0%,
            #ffffff 58%,
            #fff5e8 100%
        );
}

.hero::before {
    content: "";

    position: absolute;

    width: 500px;
    height: 500px;

    right: -260px;
    top: -260px;

    border: 1px solid rgba(0, 143, 145, 0.12);

    border-radius: 50%;
}

.hero-container {
    min-height: 680px;

    display: grid;
    grid-template-columns: 1.05fr 0.95fr;

    align-items: center;

    gap: 65px;

    padding: 75px 0;
}

.hero-content {
    max-width: 700px;
}

.eyebrow {
    display: inline-flex;
    align-items: center;

    color: var(--orange-dark);

    background: var(--orange-light);

    border: 1px solid #f6d9b2;

    border-radius: 999px;

    padding: 8px 14px;

    font-size: 11px;
    font-weight: 850;

    letter-spacing: 0.13em;
    text-transform: uppercase;

    margin-bottom: 22px;
}

.hero h1 {
    color: var(--ink);

    font-size: clamp(45px, 6vw, 76px);

    line-height: 1.01;

    letter-spacing: -0.06em;

    margin-bottom: 27px;
}

.hero h1 .teal {
    color: var(--teal);
}

.hero h1 .orange {
    color: var(--orange);
}

.hero-description {
    max-width: 650px;

    font-size: 18px;

    color: var(--text);

    margin-bottom: 32px;
}

.hero-buttons {
    display: flex;
    flex-wrap: wrap;

    gap: 13px;
}

.button {
    display: inline-flex;

    align-items: center;
    justify-content: center;

    min-height: 50px;

    padding: 13px 22px;

    border-radius: 999px;

    font-size: 14px;
    font-weight: 800;

    transition:
        transform 0.2s ease,
        background 0.2s ease,
        box-shadow 0.2s ease;
}

.button-primary {
    color: var(--white);

    background: var(--orange);

    box-shadow: 0 10px 25px rgba(242, 139, 32, 0.22);
}

.button-primary:hover {
    background: var(--orange-dark);

    transform: translateY(-2px);
}

.button-secondary {
    color: var(--teal-dark);

    background: rgba(255, 255, 255, 0.7);

    border: 1px solid var(--teal);
}

.button-secondary:hover {
    color: var(--white);
    background: var(--teal);

    transform: translateY(-2px);
}

/* HERO BRAND PANEL */

.hero-visual {
    min-height: 500px;

    position: relative;

    display: flex;
    align-items: center;
    justify-content: center;
}

.hero-circle {
    position: absolute;

    width: 430px;
    height: 430px;

    border-radius: 50%;

    border: 1px solid rgba(0, 143, 145, 0.14);

    background: rgba(255, 255, 255, 0.35);
}

.hero-circle::before {
    content: "";

    position: absolute;

    inset: 40px;

    border-radius: 50%;

    border: 1px solid rgba(242, 139, 32, 0.16);
}

.hero-circle::after {
    content: "";

    position: absolute;

    inset: 85px;

    border-radius: 50%;

    border: 1px solid rgba(0, 143, 145, 0.10);
}

.logo-panel {
    position: relative;
    z-index: 2;

    width: min(390px, 88%);

    padding: 35px;

    text-align: center;

    background: rgba(255, 255, 255, 0.95);

    border: 1px solid var(--border);

    border-radius: 30px;

    box-shadow: var(--shadow-lg);
}

.logo-panel img {
    width: 250px;
    height: 250px;

    object-fit: contain;

    margin: 0 auto 20px;
}

.logo-panel-title {
    color: var(--ink);

    font-size: 18px;
    font-weight: 850;

    padding-top: 18px;

    border-top: 1px solid var(--border);
}

.logo-panel-text {
    margin-top: 7px;

    font-size: 13px;

    color: var(--text);
}

.floating-card {
    position: absolute;
    z-index: 4;

    background: var(--white);

    border: 1px solid var(--border);

    border-radius: 17px;

    padding: 13px 17px;

    box-shadow: var(--shadow-sm);

    color: var(--ink);

    font-size: 12px;
    font-weight: 750;
}

.floating-card strong {
    display: block;

    color: var(--teal);

    font-size: 15px;
}

.floating-card.left {
    left: 0;
    top: 70px;
}

.floating-card.right {
    right: 0;
    bottom: 65px;
}

/* =========================================================
   TRUST STRIP
========================================================= */

.trust-strip {
    background: var(--white);

    border-top: 1px solid var(--border);
    border-bottom: 1px solid var(--border);
}

.trust-grid {
    display: grid;

    grid-template-columns: repeat(3, 1fr);
}

.trust-item {
    padding: 25px;

    text-align: center;

    border-right: 1px solid var(--border);
}

.trust-item:last-child {
    border-right: 0;
}

.trust-item strong {
    display: block;

    color: var(--ink);

    font-size: 14px;
}

.trust-item span {
    font-size: 12px;
}

/* =========================================================
   SECTION HEADINGS
========================================================= */

.section-heading {
    max-width: 760px;

    text-align: center;

    margin: 0 auto 55px;
}

.section-heading .label {
    color: var(--orange-dark);

    font-size: 12px;

    font-weight: 850;

    text-transform: uppercase;

    letter-spacing: 0.14em;
}

.section-heading h2 {
    color: var(--ink);

    font-size: clamp(32px, 4vw, 49px);

    line-height: 1.1;

    letter-spacing: -0.04em;

    margin: 10px 0 17px;
}

.section-heading p {
    font-size: 16px;
}

/* =========================================================
   ABOUT
========================================================= */

.about-grid {
    display: grid;

    grid-template-columns: 0.85fr 1.15fr;

    align-items: center;

    gap: 70px;
}

.about-purpose {
    position: relative;

    overflow: hidden;

    background:
        linear-gradient(
            145deg,
            var(--teal),
            var(--teal-dark)
        );

    color: var(--white);

    padding: 45px;

    border-radius: 30px;

    box-shadow: var(--shadow-lg);
}

.about-purpose::after {
    content: "";

    position: absolute;

    width: 230px;
    height: 230px;

    right: -120px;
    bottom: -120px;

    border: 1px solid rgba(255,255,255,.15);

    border-radius: 50%;
}

.about-purpose h3 {
    font-size: 27px;

    margin-bottom: 15px;
}

.about-purpose p {
    color: #e5f5f4;
}

.motto {
    margin-top: 30px;

    padding: 19px;

    background: rgba(255,255,255,.10);

    border: 1px solid rgba(255,255,255,.18);

    border-radius: 16px;

    color: #fff;

    font-size: 13px;

    font-weight: 700;
}

.about-copy h3 {
    color: var(--ink);

    font-size: 32px;

    line-height: 1.15;

    margin-bottom: 18px;
}

.about-copy p {
    margin-bottom: 17px;
}

.check-grid {
    display: grid;

    grid-template-columns: repeat(2, 1fr);

    gap: 14px;

    margin-top: 28px;
}

.check-item {
    display: flex;

    align-items: flex-start;

    gap: 10px;

    color: var(--ink);

    font-size: 13px;

    font-weight: 750;
}

.check-mark {
    flex: 0 0 23px;

    width: 23px;
    height: 23px;

    display: grid;
    place-items: center;

    color: var(--teal);

    background: var(--teal-light);

    border-radius: 50%;

    font-size: 13px;
    font-weight: 900;
}

/* =========================================================
   SERVICES
========================================================= */

.services-section {
    background: var(--cream);
}

.services-grid {
    display: grid;

    grid-template-columns: repeat(3, 1fr);

    gap: 20px;
}

.service-card {
    position: relative;

    background: var(--white);

    border: 1px solid var(--border);

    border-radius: 23px;

    padding: 30px;

    box-shadow: 0 6px 22px rgba(15,68,70,.035);

    transition:
        transform .25s ease,
        box-shadow .25s ease,
        border-color .25s ease;
}

.service-card:hover {
    transform: translateY(-7px);

    box-shadow: var(--shadow-lg);

    border-color: #c7dfdd;
}

.service-icon {
    width: 54px;
    height: 54px;

    display: grid;
    place-items: center;

    color: var(--teal);

    background: var(--teal-light);

    border-radius: 15px;

    margin-bottom: 21px;
}

.service-card:nth-child(even) .service-icon {
    color: var(--orange-dark);

    background: var(--orange-light);
}

.service-icon svg {
    width: 26px;
    height: 26px;
}

.service-card h3 {
    color: var(--ink);

    font-size: 18px;

    margin-bottom: 10px;
}

.service-card p {
    font-size: 13px;
}

.service-link {
    display: inline-flex;

    margin-top: 18px;

    color: var(--teal-dark);

    font-size: 12px;

    font-weight: 850;
}

/* =========================================================
   APPROACH
========================================================= */

.approach-section {
    background: var(--teal-light);
}

.approach-grid {
    display: grid;

    grid-template-columns: repeat(4, 1fr);

    gap: 18px;
}

.approach-card {
    background: var(--white);

    border: 1px solid rgba(0,143,145,.10);

    border-radius: 20px;

    padding: 28px;
}

.step-number {
    color: var(--orange);

    font-size: 12px;

    font-weight: 900;

    letter-spacing: .12em;
}

.approach-card h3 {
    color: var(--ink);

    margin: 9px 0 7px;

    font-size: 18px;
}

.approach-card p {
    font-size: 13px;
}

/* =========================================================
   CAREERS
========================================================= */

.careers-grid {
    display: grid;

    grid-template-columns: .85fr 1.15fr;

    gap: 42px;

    align-items: start;
}

.career-intro {
    padding: 40px;

    border-radius: 28px;

    background:
        linear-gradient(
            145deg,
            #fff5e7,
            #eef9f8
        );

    border: 1px solid var(--border);
}

.career-intro h3 {
    color: var(--ink);

    font-size: 31px;

    line-height: 1.13;

    margin-bottom: 16px;
}

.career-list {
    list-style: none;

    margin-top: 25px;
}

.career-list li {
    display: flex;

    align-items: flex-start;

    gap: 10px;

    margin: 13px 0;

    color: var(--ink);

    font-size: 13px;

    font-weight: 650;
}

.career-list span {
    color: var(--teal);

    font-weight: 900;
}

.form-card {
    background: var(--white);

    border: 1px solid var(--border);

    border-radius: 28px;

    padding: 36px;

    box-shadow: var(--shadow-lg);
}

.form-card h3 {
    color: var(--ink);

    font-size: 24px;

    margin-bottom: 23px;
}

.form-grid {
    display: grid;

    grid-template-columns: repeat(2, 1fr);

    gap: 17px;
}

.form-field {
    margin-bottom: 3px;
}

.form-field.full {
    grid-column: 1 / -1;
}

.form-field label {
    display: block;

    color: var(--ink);

    font-size: 12px;

    font-weight: 800;

    margin-bottom: 7px;
}

.form-field input,
.form-field textarea,
.form-field select {
    width: 100%;

    padding: 13px 14px;

    border: 1px solid var(--border);

    border-radius: 12px;

    background: #fcfefe;

    color: var(--ink);

    outline: none;
}

.form-field input:focus,
.form-field textarea:focus,
.form-field select:focus {
    border-color: var(--teal);

    box-shadow: 0 0 0 3px rgba(0,143,145,.09);
}

.form-field textarea {
    min-height: 120px;

    resize: vertical;
}

.form-note {
    color: #7b8d8d;

    font-size: 11px;

    margin-top: 6px;
}

.form-submit {
    margin-top: 17px;
}

/* =========================================================
   CONTACT
========================================================= */

.contact-section {
    background: var(--white);
}

.contact-grid {
    display: grid;

    grid-template-columns: 1fr 1fr;

    gap: 24px;
}

.contact-card {
    background: var(--cream);

    border: 1px solid var(--border);

    border-radius: 26px;

    padding: 35px;
}

.contact-card.dark {
    color: #dff1f0;

    background:
        linear-gradient(
            145deg,
            var(--teal-dark),
            var(--teal-deep)
        );

    border: 0;
}

.contact-card h3 {
    color: var(--ink);

    font-size: 24px;

    margin-bottom: 24px;
}

.contact-card.dark h3 {
    color: var(--white);
}

.contact-item {
    display: flex;

    gap: 14px;

    margin: 19px 0;
}

.contact-icon {
    flex: 0 0 44px;

    width: 44px;
    height: 44px;

    display: grid;
    place-items: center;

    border-radius: 12px;

    color: var(--teal);

    background: var(--teal-light);
}

.contact-card.dark .contact-icon {
    color: var(--white);

    background: rgba(255,255,255,.10);
}

.contact-item strong {
    display: block;

    color: var(--ink);

    font-size: 12px;
}

.contact-card.dark .contact-item strong {
    color: var(--white);
}

.contact-item a {
    font-size: 13px;
}

.contact-item a:hover {
    color: var(--orange);
}

.contact-card.dark a:hover {
    color: var(--white);
}

/* =========================================================
   CTA
========================================================= */

.cta-section {
    padding: 35px 0 100px;

    background: var(--white);
}

.cta-box {
    display: flex;

    align-items: center;

    justify-content: space-between;

    gap: 30px;

    padding: 52px;

    color: var(--white);

    border-radius: 30px;

    background:
        linear-gradient(
            110deg,
            var(--teal-deep),
            var(--teal)
        );

    box-shadow: var(--shadow-lg);
}

.cta-box h2 {
    font-size: clamp(28px, 4vw, 43px);

    line-height: 1.08;

    letter-spacing: -.035em;

    margin-bottom: 10px;
}

.cta-box p {
    max-width: 680px;

    color: #dceeed;

    font-size: 14px;
}

/* =========================================================
   FOOTER
========================================================= */

.footer {
    padding: 60px 0 25px;

    color: #c8dcdc;

    background: #103f40;
}

.footer-grid {
    display: grid;

    grid-template-columns: 1.3fr .7fr .9fr;

    gap: 55px;

    padding-bottom: 40px;
}

.footer-brand {
    display: flex;

    align-items: center;

    gap: 12px;

    margin-bottom: 17px;
}

.footer-brand img {
    width: 56px;
    height: 56px;

    object-fit: contain;

    background: var(--white);

    border-radius: 11px;

    padding: 3px;
}

.footer h3 {
    color: var(--white);

    font-size: 16px;

    margin-bottom: 14px;
}

.footer p,
.footer a,
.footer span {
    font-size: 12px;
}

.footer-links {
    display: grid;

    gap: 7px;
}

.footer a:hover {
    color: var(--orange);
}

.footer-bottom {
    padding-top: 22px;

    border-top: 1px solid rgba(255,255,255,.12);

    text-align: center;

    font-size: 11px;

    color: #abc4c3;
}

/* =========================================================
   WHATSAPP
========================================================= */

.whatsapp-button {
    position: fixed;

    right: 22px;
    bottom: 22px;

    z-index: 2000;

    width: 58px;
    height: 58px;

    display: grid;
    place-items: center;

    border-radius: 50%;

    background: #25d366;

    box-shadow: 0 10px 30px rgba(0,0,0,.18);

    transition: .2s ease;
}

.whatsapp-button:hover {
    transform: translateY(-3px) scale(1.04);
}

.whatsapp-button svg {
    width: 31px;
    height: 31px;

    fill: white;
}

/* =========================================================
   RESPONSIVE
========================================================= */

@media (max-width: 1000px) {

    .navigation {
        display: none;

        position: absolute;

        top: 82px;
        left: 0;
        right: 0;

        padding: 18px 4%;

        flex-direction: column;
        align-items: stretch;

        gap: 3px;

        background: var(--white);

        border-bottom: 1px solid var(--border);

        box-shadow: 0 15px 35px rgba(0,0,0,.07);
    }

    .navigation.active {
        display: flex;
    }

    .navigation a {
        padding: 11px;
    }

    .menu-button {
        display: block;
    }

    .hero-container,
    .about-grid,
    .careers-grid {
        grid-template-columns: 1fr;
    }

    .hero-container {
        padding: 65px 0 35px;
    }

    .hero-content {
        text-align: center;
        margin: 0 auto;
    }

    .hero-description {
        margin-left: auto;
        margin-right: auto;
    }

    .hero-buttons {
        justify-content: center;
    }

    .hero-visual {
        min-height: 450px;
    }

    .services-grid {
        grid-template-columns: repeat(2, 1fr);
    }

    .approach-grid {
        grid-template-columns: repeat(2, 1fr);
    }

    .footer-grid {
        grid-template-columns: 1fr 1fr;
    }
}

@media (max-width: 680px) {

    .top-bar-inner {
        justify-content: center;
        text-align: center;
    }

    .top-bar-inner span:first-child {
        display: none;
    }

    .navbar {
        min-height: 74px;
    }

    .navigation {
        top: 74px;
    }

    .brand-logo {
        width: 52px;
        height: 52px;
    }

    .brand-name {
        font-size: 16px;
    }

    .section {
        padding: 72px 0;
    }

    .hero h1 {
        font-size: 44px;
    }

    .hero-description {
        font-size: 15px;
    }

    .hero-circle {
        width: 310px;
        height: 310px;
    }

    .logo-panel {
        width: 300px;

        padding: 24px;
    }

    .logo-panel img {
        width: 200px;
        height: 200px;
    }

    .floating-card.left {
        left: 0;
        top: 35px;
    }

    .floating-card.right {
        right: 0;
        bottom: 35px;
    }

    .trust-grid {
        grid-template-columns: 1fr;
    }

    .trust-item {
        border-right: 0;
        border-bottom: 1px solid var(--border);
    }

    .trust-item:last-child {
        border-bottom: 0;
    }

    .services-grid,
    .approach-grid,
    .contact-grid,
    .footer-grid {
        grid-template-columns: 1fr;
    }

    .check-grid {
        grid-template-columns: 1fr;
    }

    .form-grid {
        grid-template-columns: 1fr;
    }

    .form-field.full {
        grid-column: auto;
    }

    .cta-box {
        flex-direction: column;

        align-items: flex-start;

        padding: 35px 27px;
    }

    .about-purpose,
    .career-intro,
    .form-card,
    .contact-card {
        padding: 27px;
    }

    .whatsapp-button {
        width: 55px;
        height: 55px;

        right: 15px;
        bottom: 15px;
    }
}
</style>
</head>

<body>

<!-- =========================================================
     TOP BAR
========================================================= -->

<div class="top-bar">
    <div class="container top-bar-inner">

        <span>
            Practical solutions for people, businesses and organizations
        </span>

        <span>
            <a href="mailto:stephanie_urae@sduconsultancy.com">
                stephanie_urae@sduconsultancy.com
            </a>
            &nbsp; | &nbsp;
            Papua New Guinea
        </span>

    </div>
</div>


<!-- =========================================================
     HEADER
========================================================= -->

<header class="header">

    <div class="container navbar">

        <a href="#home" class="brand">

            <!--
                IMPORTANT:
                Place your SDU logo in the same folder as this HTML file
                and name it:

                sdu-logo.png
            -->

            <img
                class="brand-logo"
                src="sdu-logo.png"
                alt="SDU Consultancy Logo"
                onerror="this.style.display='none';"
            >

            <div class="brand-name">
                SDU <span>Consultancy</span>
            </div>

        </a>


        <button
            class="menu-button"
            id="menuButton"
            type="button"
            aria-label="Open navigation"
        >
            &#9776;
        </button>


        <nav class="navigation" id="navigation">

            <a href="#home">Home</a>

            <a href="#about">About</a>

            <a href="#services">Services</a>

            <a href="#careers">Careers</a>

            <a href="#contact">Contact</a>

            <a
                href="https://wa.me/67578275501"
                target="_blank"
                rel="noopener"
                class="nav-contact"
            >
                WhatsApp Us
            </a>

        </nav>

    </div>

</header>


<main>


<!-- =========================================================
     HERO
========================================================= -->

<section class="hero" id="home">

    <div class="container hero-container">

        <div class="hero-content">

            <div class="eyebrow">
                Consultancy • Training • Business Support
            </div>

            <h1>
                Empowering people.
                <span class="teal">
                    Supporting organizations.
                </span>
                <span class="orange">
                    Creating opportunity.
                </span>
            </h1>

            <p class="hero-description">
                SDU Consultancy provides practical, people-focused
                solutions that help individuals, entrepreneurs,
                businesses and organizations move from ideas to
                meaningful action.
            </p>

            <div class="hero-buttons">

                <a
                    href="#services"
                    class="button button-primary"
                >
                    Explore Our Services
                </a>

                <a
                    href="#contact"
                    class="button button-secondary"
                >
                    Talk to SDU Consultancy
                </a>

            </div>

        </div>


        <div class="hero-visual">

            <div class="hero-circle"></div>

            <div class="floating-card left">
                <strong>PNG</strong>
                Local insight
            </div>

            <div class="floating-card right">
                <strong>SDU</strong>
                Practical solutions
            </div>


            <div class="logo-panel">

                <img
                    src="sdu-logo.png"
                    alt="SDU Consultancy Logo"
                    onerror="
                        this.src='data:image/svg+xml;charset=UTF-8,' +
                        encodeURIComponent(
                        '<svg xmlns=\'http://www.w3.org/2000/svg\' viewBox=\'0 0 500 300\'><rect width=\'500\' height=\'300\' rx=\'30\' fill=\'#ffffff\'/><text x=\'250\' y=\'135\' text-anchor=\'middle\' font-family=\'Arial\' font-size=\'48\' font-weight=\'700\' fill=\'#008f91\'>SDU</text><text x=\'250\' y=\'185\' text-anchor=\'middle\' font-family=\'Arial\' font-size=\'26\' fill=\'#f28b20\'>CONSULTANCY</text></svg>'
                        );
                    "
                >

                <div class="logo-panel-title">
                    SDU Consultancy
                </div>

                <div class="logo-panel-text">
                    Papua New Guinea
                </div>

            </div>

        </div>

    </div>

</section>


<!-- =========================================================
     TRUST STRIP
========================================================= -->

<section class="trust-strip">

    <div class="container trust-grid">

        <div class="trust-item">

            <strong>
                People Focused
            </strong>

            <span>
                Building skills, confidence and opportunity
            </span>

        </div>


        <div class="trust-item">

            <strong>
                Practical Support
            </strong>

            <span>
                Clear guidance designed for action
            </span>

        </div>


        <div class="trust-item">

            <strong>
                Papua New Guinea
            </strong>

            <span>
                Solutions grounded in local needs
            </span>

        </div>

    </div>

</section>


<!-- =========================================================
     ABOUT
========================================================= -->

<section class="section section-white" id="about">

    <div class="container">

        <div class="section-heading">

            <div class="label">
                About SDU Consultancy
            </div>

            <h2>
                Turning ideas into practical action.
            </h2>

            <p>
                We support individuals, entrepreneurs,
                businesses and organizations with practical
                services designed to help them move forward.
            </p>

        </div>


        <div class="about-grid">

            <div class="about-purpose">

                <h3>
                    Our Purpose
                </h3>

                <p>
                    To empower people, support organizations
                    and deliver practical solutions that
                    contribute to sustainable development.
                </p>

                <div class="motto">

                    “empowering people, supporting organizations,
                    and delivering practical solutions for
                    sustainable development”

                </div>

            </div>


            <div class="about-copy">

                <h3>
                    Support that moves you forward.
                </h3>

                <p>
                    SDU Consultancy works with individuals,
                    entrepreneurs, businesses and organizations
                    to turn needs and ideas into clear and
                    practical next steps.
                </p>

                <p>
                    From business development and registration
                    to training, product sourcing, career
                    opportunities and travel support, our focus
                    is on making processes clearer and more
                    accessible.
                </p>


                <div class="check-grid">

                    <div class="check-item">
                        <span class="check-mark">✓</span>
                        <span>
                            Practical and actionable guidance
                        </span>
                    </div>

                    <div class="check-item">
                        <span class="check-mark">✓</span>
                        <span>
                            People-centred support
                        </span>
                    </div>

                    <div class="check-item">
                        <span class="check-mark">✓</span>
                        <span>
                            Business and organizational focus
                        </span>
                    </div>

                    <div class="check-item">
                        <span class="check-mark">✓</span>
                        <span>
                            Development-oriented solutions
                        </span>
                    </div>

                </div>

            </div>

        </div>

    </div>

</section>


<!-- =========================================================
     SERVICES
========================================================= -->

<section
    class="section services-section"
    id="services"
>

    <div class="container">

        <div class="section-heading">

            <div class="label">
                Our Services
            </div>

            <h2>
                Practical services for real-world needs.
            </h2>

            <p>
                Our services are designed around helping
                people and organizations take the next step.
            </p>

        </div>


        <div class="services-grid">


            <!-- BUSINESS CONSULTANCY -->

            <article class="service-card">

                <div class="service-icon">

                    <svg
                        viewBox="0 0 24 24"
                        fill="none"
                        stroke="currentColor"
                        stroke-width="1.8"
                    >
                        <path d="M4 20V8l8-4 8 4v12"/>
                        <path d="M8 20v-6h8v6"/>
                        <path d="M9 9h.01"/>
                        <path d="M12 9h.01"/>
                        <path d="M15 9h.01"/>
                    </svg>

                </div>

                <h3>
                    Business Consultancy
                </h3>

                <p>
                    Practical guidance for business planning,
                    development, organizational support and
                    business improvement.
                </p>

                <a
                    href="#contact"
                    class="service-link"
                >
                    Enquire about this service
                </a>

            </article>


            <!-- TRAINING -->

            <article class="service-card">

                <div class="service-icon">

                    <svg
                        viewBox="0 0 24 24"
                        fill="none"
                        stroke="currentColor"
                        stroke-width="1.8"
                    >
                        <path d="M4 19h16"/>
                        <path d="M6 17V5h12v12"/>
                        <path d="M9 9h6"/>
                        <path d="M9 12h4"/>
                    </svg>

                </div>

                <h3>
                    Training &amp; Workshops
                </h3>

                <p>
                    Practical learning experiences designed
                    to build skills, confidence, entrepreneurship
                    capacity and knowledge.
                </p>

                <a
                    href="#contact"
                    class="service-link"
                >
                    Discuss a workshop
                </a>

            </article>


            <!-- REGISTRATION -->

            <article class="service-card">

                <div class="service-icon">

                    <svg
                        viewBox="0 0 24 24"
                        fill="none"
                        stroke="currentColor"
                        stroke-width="1.8"
                    >
                        <path d="M7 3h10v18H7z"/>
                        <path d="M9 7h6"/>
                        <path d="M9 11h6"/>
                        <path d="M9 15h3"/>
                    </svg>

                </div>

                <h3>
                    Business Registration
                </h3>

                <p>
                    Assistance with formalizing your business
                    idea and navigating the business registration
                    process.
                </p>

                <a
                    href="#contact"
                    class="service-link"
                >
                    Get registration assistance
                </a>

            </article>


            <!-- PRODUCT SOURCING -->

            <article class="service-card">

                <div class="service-icon">

                    <svg
                        viewBox="0 0 24 24"
                        fill="none"
                        stroke="currentColor"
                        stroke-width="1.8"
                    >
                        <circle cx="10" cy="10" r="6"/>
                        <path d="m15 15 5 5"/>
                        <path d="M7 10h6"/>
                        <path d="M10 7v6"/>
                    </svg>

                </div>

                <h3>
                    Product Sourcing
                </h3>

                <p>
                    Support identifying products, suppliers
                    and online sourcing opportunities for
                    new and existing businesses.
                </p>

                <a
                    href="#contact"
                    class="service-link"
                >
                    Start sourcing
                </a>

            </article>


            <!-- TRAVEL -->

            <article class="service-card">

                <div class="service-icon">

                    <svg
                        viewBox="0 0 24 24"
                        fill="none"
                        stroke="currentColor"
                        stroke-width="1.8"
                    >
                        <path d="m3 17 8-8 5 5 5-7"/>
                        <path d="M14 7h7v7"/>
                    </svg>

                </div>

                <h3>
                    Travel &amp; Visa Support
                </h3>

                <p>
                    Practical assistance with travel documentation,
                    visa application support and related travel
                    arrangements.
                </p>

                <a
                    href="#contact"
                    class="service-link"
                >
                    Make an enquiry
                </a>

            </article>


            <!-- CAREERS -->

            <article class="service-card">

                <div class="service-icon">

                    <svg
                        viewBox="0 0 24 24"
                        fill="none"
                        stroke="currentColor"
                        stroke-width="1.8"
                    >
                        <circle cx="12" cy="8" r="3"/>
                        <path d="M5 21a7 7 0 0 1 14 0"/>
                        <path d="m18 14 2 2 3-3"/>
                    </svg>

                </div>

                <h3>
                    Career Opportunities
                </h3>

                <p>
                    Connecting people with employment,
                    professional development and other
                    career-related opportunities.
                </p>

                <a
                    href="#careers"
                    class="service-link"
                >
                    Submit your CV
                </a>

            </article>

        </div>

    </div>

</section>


<!-- =========================================================
     APPROACH
========================================================= -->

<section class="section approach-section">

    <div class="container">

        <div class="section-heading">

            <div class="label">
                Our Approach
            </div>

            <h2>
                Simple. Practical. Focused on progress.
            </h2>

            <p>
                We focus on understanding your needs and
                helping you move from where you are to
                where you want to be.
            </p>

        </div>


        <div class="approach-grid">

            <div class="approach-card">

                <div class="step-number">
                    01 / UNDERSTAND
                </div>

                <h3>
                    Listen
                </h3>

                <p>
                    We understand your needs, goals and
                    challenges.
                </p>

            </div>


            <div class="approach-card">

                <div class="step-number">
                    02 / PLAN
                </div>

                <h3>
                    Clarify
                </h3>

                <p>
                    We identify practical options and
                    clear next steps.
                </p>

            </div>


            <div class="approach-card">

                <div class="step-number">
                    03 / ACT
                </div>

                <h3>
                    Implement
                </h3>

                <p>
                    We support you in turning the plan
                    into action.
                </p>

            </div>


            <div class="approach-card">

                <div class="step-number">
                    04 / GROW
                </div>

                <h3>
                    Develop
                </h3>

                <p>
                    We focus on sustainable growth and
                    continued opportunity.
                </p>

            </div>

        </div>

    </div>

</section>


<!-- =========================================================
     CAREERS
========================================================= -->

<section class="section section-white" id="careers">

    <div class="container">

        <div class="section-heading">

            <div class="label">
                Career Opportunities
            </div>

            <h2>
                Your next opportunity could start here.
            </h2>

            <p>
                Submit your details and CV to SDU Consultancy
                for consideration for suitable future opportunities.
            </p>

        </div>


        <div class="careers-grid">


            <div class="career-intro">

                <h3>
                    Build your next opportunity.
                </h3>

                <p>
                    We welcome people who are seeking
                    employment, professional opportunities,
                    training and career development.
                </p>


                <ul class="career-list">

                    <li>
                        <span>✓</span>
                        <span>
                            Submit your current CV
                        </span>
                    </li>

                    <li>
                        <span>✓</span>
                        <span>
                            Keep your contact details up to date
                        </span>
                    </li>

                    <li>
                        <span>✓</span>
                        <span>
                            Tell us the opportunities that interest you
                        </span>
                    </li>

                    <li>
                        <span>✓</span>
                        <span>
                            We may contact you when suitable
                            opportunities arise
                        </span>
                    </li>

                </ul>

            </div>


            <div class="form-card">

                <h3>
                    CV Submission
                </h3>

                <form
                    id="cvForm"
                    action="mailto:stephanie_urae@sduconsultancy.com"
                    method="post"
                    enctype="text/plain"
                >

                    <div class="form-grid">


                        <div class="form-field">

                            <label for="fullName">
                                Full Name
                            </label>

                            <input
                                id="fullName"
                                type="text"
                                name="Full Name"
                                placeholder="Enter your full name"
                                required
                            >

                        </div>


                        <div class="form-field">

                            <label for="email">
                                Email Address
                            </label>

                            <input
                                id="email"
                                type="email"
                                name="Email"
                                placeholder="Enter your email address"
                                required
                            >

                        </div>


                        <div class="form-field">

                            <label for="phone">
                                Phone Number
                            </label>

                            <input
                                id="phone"
                                type="tel"
                                name="Phone Number"
                                placeholder="+675"
                                required
                            >

                        </div>


                        <div class="form-field">

                            <label for="interest">
                                Area of Interest
                            </label>

                            <select
                                id="interest"
                                name="Area of Interest"
                            >

                                <option value="">
                                    Select an area
                                </option>

                                <option>
                                    Employment Opportunities
                                </option>

                                <option>
                                    Business Opportunities
                                </option>

                                <option>
                                    Training &amp; Development
                                </option>

                                <option>
                                    Consultancy Opportunities
                                </option>

                                <option>
                                    Other
                                </option>

                            </select>

                        </div>


                        <div class="form-field full">

                            <label for="message">
                                Short Message
                            </label>

                            <textarea
                                id="message"
                                name="Message"
                                placeholder="Tell us briefly about yourself and the opportunity you are interested in."
                            ></textarea>

                        </div>


                        <div class="form-field full">

                            <label for="cv">
                                CV File
                            </label>

                            <input
                                id="cv"
                                type="file"
                                name="CV"
                                accept=".pdf,.doc,.docx"
                                required
                            >

                            <div class="form-note">
                                Accepted formats: PDF, DOC and DOCX.
                                Maximum file size: 5 MB.
                            </div>

                        </div>

                    </div>


                    <div class="form-submit">

                        <button
                            type="submit"
                            class="button button-primary"
                        >
                            Prepare CV Submission
                        </button>

                    </div>

                </form>

            </div>

        </div>

    </div>

</section>


<!-- =========================================================
     CONTACT
========================================================= -->

<section
    class="section contact-section"
    id="contact"
>

    <div class="container">

        <div class="section-heading">

            <div class="label">
                Contact Us
            </div>

            <h2>
                Let's work together.
            </h2>

            <p>
                Have a business idea, need consultancy support,
                or want to learn more about our services?
                Get in touch with SDU Consultancy.
            </p>

        </div>


        <div class="contact-grid">


            <div class="contact-card dark">

                <h3>
                    SDU Consultancy
                </h3>


                <div class="contact-item">

                    <div class="contact-icon">

                        <svg
                            width="20"
                            height="20"
                            viewBox="0 0 24 24"
                            fill="none"
                            stroke="currentColor"
                            stroke-width="1.8"
                        >
                            <path d="M12 21s7-6.2 7-12a7 7 0 1 0-14 0c0 5.8 7 12 7 12Z"/>
                            <circle cx="12" cy="9" r="2.2"/>
                        </svg>

                    </div>

                    <div>

                        <strong>
                            Location
                        </strong>

                        Papua New Guinea

                    </div>

                </div>


                <div class="contact-item">

                    <div class="contact-icon">

                        <svg
                            width="20"
                            height="20"
                            viewBox="0 0 24 24"
                            fill="none"
                            stroke="currentColor"
                            stroke-width="1.8"
                        >
                            <path d="M22 16.9v3a2 2 0 0 1-2.2 2A19.8 19.8 0 0 1 3.1 5.2 2 2 0 0 1 5.1 3h3a2 2 0 0 1 2 1.7c.1.9.3 1.7.6 2.5a2 2 0 0 1-.5 2.1L9 10.6a16 16 0 0 0 4.4 4.4l1.3-1.2a2 2 0 0 1 2.1-.5c.8.3 1.6.5 2.5.6a2 2 0 0 1 1.7 2Z"/>
                        </svg>

                    </div>

                    <div>

                        <strong>
                            Phone
                        </strong>

                        <a href="tel:+67578275501">
                            +675 78275501
                        </a>

                        <br>

                        <a href="tel:+67571948318">
                            +675 71948318
                        </a>

                    </div>

                </div>


                <div class="contact-item">

                    <div class="contact-icon">

                        <svg
                            width="20"
                            height="20"
                            viewBox="0 0 24 24"
                            fill="none"
                            stroke="currentColor"
                            stroke-width="1.8"
                        >
                            <rect x="3" y="5" width="18" height="14" rx="2"/>
                            <path d="m3 7 9 6 9-6"/>
                        </svg>

                    </div>

                    <div>

                        <strong>
                            Email
                        </strong>

                        <a href="mailto:stephanie_urae@sduconsultancy.com">
                            stephanie_urae@sduconsultancy.com
                        </a>

                    </div>

                </div>

            </div>


            <div class="contact-card">

                <h3>
                    Send an Enquiry
                </h3>


                <form
                    action="mailto:stephanie_urae@sduconsultancy.com"
                    method="post"
                    enctype="text/plain"
                >

                    <div class="form-field">

                        <label for="contactName">
                            Name
                        </label>

                        <input
                            id="contactName"
                            type="text"
                            name="Name"
                            placeholder="Your name"
                            required
                        >

                    </div>


                    <div class="form-field">

                        <label for="contactEmail">
                            Email
                        </label>

                        <input
                            id="contactEmail"
                            type="email"
                            name="Email"
                            placeholder="Your email"
                            required
                        >

                    </div>


                    <div class="form-field">

                        <label for="contactMessage">
                            Message
                        </label>

                        <textarea
                            id="contactMessage"
                            name="Message"
                            placeholder="How can SDU Consultancy help you?"
                            required
                        ></textarea>

                    </div>


                    <button
                        type="submit"
                        class="button button-primary"
                    >
                        Send Enquiry
                    </button>

                </form>

            </div>

        </div>

    </div>

</section>


<!-- =========================================================
     CTA
========================================================= -->

<section class="cta-section">

    <div class="container">

        <div class="cta-box">

            <div>

                <h2>
                    Have an idea? Let's make it happen.
                </h2>

                <p>
                    Talk to SDU Consultancy about your business,
                    training, sourcing, career or consultancy needs.
                </p>

            </div>


            <a
                href="https://wa.me/67578275501"
                target="_blank"
                rel="noopener"
                class="button button-primary"
            >
                Chat on WhatsApp
            </a>

        </div>

    </div>

</section>

</main>


<!-- =========================================================
     FOOTER
========================================================= -->

<footer class="footer">

    <div class="container">

        <div class="footer-grid">


            <div>

                <div class="footer-brand">

                    <img
                        src="sdu-logo.png"
                        alt="SDU Consultancy Logo"
                    >

                    <h3>
                        SDU Consultancy
                    </h3>

                </div>

                <p>
                    Empowering people, supporting organizations,
                    and delivering practical solutions for
                    sustainable development.
                </p>

            </div>


            <div>

                <h3>
                    Quick Links
                </h3>

                <div class="footer-links">

                    <a href="#home">Home</a>

                    <a href="#about">About</a>

                    <a href="#services">Services</a>

                    <a href="#careers">Careers</a>

                    <a href="#contact">Contact</a>

                </div>

            </div>


            <div>

                <h3>
                    Contact
                </h3>

                <div class="footer-links">

                    <a href="tel:+67578275501">
                        +675 78275501
                    </a>

                    <a href="tel:+67571948318">
                        +675 71948318
                    </a>

                    <a href="mailto:stephanie_urae@sduconsultancy.com">
                        stephanie_urae@sduconsultancy.com
                    </a>

                    <span>
                        Papua New Guinea
                    </span>

                </div>

            </div>

        </div>


        <div class="footer-bottom">

            © <span id="year"></span>
            SDU Consultancy.
            All Rights Reserved.

        </div>

    </div>

</footer>


<!-- =========================================================
     WHATSAPP BUTTON
========================================================= -->

<a
    href="https://wa.me/67578275501"
    target="_blank"
    rel="noopener"
    class="whatsapp-button"
    aria-label="Contact SDU Consultancy on WhatsApp"
    title="Contact SDU Consultancy on WhatsApp"
>

    <svg
        viewBox="0 0 32 32"
        xmlns="http://www.w3.org/2000/svg"
    >

        <path d="
        M16 3C8.82 3 3 8.82 3 16
        c0 2.29.6 4.44 1.65 6.3L3 29l6.91-1.61
        A12.94 12.94 0 0 0 16 29
        c7.18 0 13-5.82 13-13S23.18 3 16 3zm0 23.6
        c-2.03 0-3.91-.59-5.5-1.61l-.39-.24-4.1.95
        .98-3.99-.25-.41A10.56 10.56 0 1 1 16 26.6zm5.81-7.92
        c-.32-.16-1.89-.93-2.18-1.04
        -.29-.11-.5-.16-.71.16
        -.21.32-.81 1.04-.99 1.25
        -.18.21-.37.24-.69.08
        -.32-.16-1.34-.49-2.55-1.56
        -.94-.84-1.57-1.87-1.75-2.19
        -.18-.32-.02-.49.14-.65
        .14-.14.32-.37.48-.55
        .16-.18.21-.32.32-.53
        .11-.21.05-.4-.03-.56
        -.08-.16-.71-1.71-.97-2.34
        -.26-.62-.52-.54-.71-.55
        -.18-.01-.4-.01-.61-.01
        -.21 0-.55.08-.84.4
        -.29.32-1.1 1.07-1.1 2.62
        s1.13 3.04 1.29 3.25
        c.16.21 2.22 3.39 5.38 4.76
        .75.32 1.34.51 1.8.65
        .76.24 1.45.21 2 .13
        .61-.09 1.89-.77 2.16-1.51
        .27-.74.27-1.38.19-1.51
        -.08-.13-.29-.21-.61-.37z"/>

    </svg>

</a>


<!-- =========================================================
     JAVASCRIPT
========================================================= -->

<script>

/* Mobile Navigation */

const menuButton =
    document.getElementById("menuButton");

const navigation =
    document.getElementById("navigation");


menuButton.addEventListener("click", function () {

    navigation.classList.toggle("active");

});


document
    .querySelectorAll("#navigation a")
    .forEach(function (link) {

        link.addEventListener("click", function () {

            navigation.classList.remove("active");

        });

    });


/* Current Year */

document.getElementById("year").textContent =
    new Date().getFullYear();


/* CV Validation */

const cvForm =
    document.getElementById("cvForm");


cvForm.addEventListener("submit", function (event) {

    const file =
        document.getElementById("cv").files[0];


    if (!file) {

        event.preventDefault();

        alert("Please select your CV.");

        return;

    }


    const allowedExtensions = [
        ".pdf",
        ".doc",
        ".docx"
    ];


    const filename =
        file.name.toLowerCase();


    const validExtension =
        allowedExtensions.some(function (extension) {

            return filename.endsWith(extension);

        });


    if (!validExtension) {

        event.preventDefault();

        alert(
            "Please upload your CV in PDF, DOC or DOCX format."
        );

        return;

    }


    const maximumSize =
        5 * 1024 * 1024;


    if (file.size > maximumSize) {

        event.preventDefault();

        alert(
            "Your CV is larger than 5 MB. Please upload a smaller file."
        );

        return;

    }


    alert(
        "Your email application will now open. Please review the message and attach your CV before sending."
    );

});

</script>

</body>
</html>
