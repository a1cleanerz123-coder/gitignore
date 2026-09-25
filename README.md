<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<meta name="description"
content="A-1 Cleanerz123 LLC — Professional property care, cleaning, flooring, maintenance, painting, drywall and pressure washing services.">

<title>A-1 Cleanerz123 LLC | Professional Property Care</title>

<style>

/* =========================================================
   A-1 CLEANERZ123 LLC
   PREMIUM WEBSITE
========================================================= */

:root {
    --red: #e00000;
    --red-dark: #9b0000;
    --gold: #d4af37;
    --gold-light: #f0d46a;
    --black: #050505;
    --black-2: #0b0b0b;
    --black-3: #151515;
    --gray: #aaaaaa;
    --white: #ffffff;
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
        Arial,
        Helvetica,
        sans-serif;

    background: var(--black);
    color: var(--white);
    line-height: 1.6;
}

a {
    color: inherit;
    text-decoration: none;
}

.container {
    width: min(1200px, 92%);
    margin: auto;
}


/* =========================================================
   NAVIGATION
========================================================= */

.navbar {
    position: sticky;
    top: 0;
    z-index: 1000;

    background: rgba(5,5,5,.94);
    backdrop-filter: blur(12px);

    border-bottom: 1px solid rgba(212,175,55,.2);
}

.nav-inner {
    min-height: 75px;

    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 25px;
}

.nav-logo {
    display: flex;
    align-items: center;
    gap: 10px;

    font-weight: 900;
    letter-spacing: 1px;
}

.nav-logo strong {
    color: var(--red);
    font-size: 30px;
}

.nav-logo span {
    font-size: 14px;
}

.nav-links {
    display: flex;
    gap: 25px;
    align-items: center;
}

.nav-links a {
    font-size: 13px;
    font-weight: 800;
    letter-spacing: .7px;
    color: #ddd;

    transition: .2s ease;
}

.nav-links a:hover {
    color: var(--gold);
}

.nav-call {
    padding: 11px 18px;

    background: var(--red);
    border-radius: 7px;

    font-weight: 900 !important;
    color: white !important;
}


/* =========================================================
   HERO
========================================================= */

.hero {
    min-height: 88vh;

    display: flex;
    align-items: center;

    position: relative;
    overflow: hidden;

    background:
        radial-gradient(
            circle at 85% 25%,
            rgba(224,0,0,.25),
            transparent 30%
        ),
        radial-gradient(
            circle at 10% 80%,
            rgba(212,175,55,.08),
            transparent 25%
        ),
        linear-gradient(
            135deg,
            #050505,
            #111111
        );
}

.hero::before {
    content: "";

    position: absolute;
    inset: 0;

    background:
        linear-gradient(
            120deg,
            transparent 45%,
            rgba(224,0,0,.06) 45%,
            rgba(224,0,0,.06) 46%,
            transparent 46%
        );

    pointer-events: none;
}

.hero-content {
    position: relative;
    z-index: 2;

    max-width: 850px;

    padding: 80px 0;
}

.hero-kicker {
    display: inline-block;

    padding: 8px 15px;

    border: 1px solid var(--gold);
    border-radius: 30px;

    color: var(--gold-light);

    font-size: 12px;
    font-weight: 900;
    letter-spacing: 2px;
}

.hero-logo {
    margin-top: 25px;

    color: var(--red);

    font-size: clamp(80px, 15vw, 160px);

    font-weight: 1000;

    line-height: .75;

    letter-spacing: -9px;

    text-shadow:
        4px 4px 0 #000,
        0 0 35px rgba(224,0,0,.35);
}

.hero-name {
    margin-top: 20px;

    font-size: clamp(30px, 5vw, 58px);

    font-weight: 1000;

    letter-spacing: 2px;
}

.hero-name span {
    color: var(--gold);
}

.hero-subtitle {
    margin-top: 18px;

    color: #ddd;

    font-size: clamp(18px, 3vw, 24px);

    font-weight: 700;
}

.hero-description {
    max-width: 680px;

    margin-top: 15px;

    color: #aaa;

    font-size: 16px;
}

.hero-buttons {
    display: flex;

    gap: 15px;

    flex-wrap: wrap;

    margin-top: 30px;
}

.btn {
    display: inline-flex;

    align-items: center;
    justify-content: center;

    padding: 15px 25px;

    border-radius: 8px;

    font-weight: 900;

    letter-spacing: .8px;

    transition: .25s ease;
}

.btn-red {
    background: var(--red);
}

.btn-red:hover {
    background: #ff1717;
    transform: translateY(-3px);
}

.btn-gold {
    background: var(--gold);
    color: #050505;
}

.btn-gold:hover {
    background: var(--gold-light);
    transform: translateY(-3px);
}

.hero-trust {
    display: flex;

    gap: 30px;

    flex-wrap: wrap;

    margin-top: 40px;

    color: #aaa;

    font-size: 12px;

    font-weight: 800;

    letter-spacing: 1px;
}

.hero-trust span::before {
    content: "✓";

    color: var(--gold);

    margin-right: 7px;
}


/* =========================================================
   STATS
========================================================= */

.stats {
    background: var(--red);

    border-top: 1px solid rgba(255,255,255,.15);
    border-bottom: 1px solid rgba(255,255,255,.15);
}

.stats-grid {
    display: grid;

    grid-template-columns:
        repeat(4, 1fr);
}

.stat {
    padding: 25px 15px;

    text-align: center;

    border-right:
        1px solid rgba(255,255,255,.18);
}

.stat:last-child {
    border-right: none;
}

.stat strong {
    display: block;

    font-size: 28px;
    font-weight: 1000;
}

.stat span {
    font-size: 11px;

    text-transform: uppercase;

    letter-spacing: 1px;
}


/* =========================================================
   SECTION HEADER
========================================================= */

.section {
    padding: 90px 0;
}

.section-header {
    max-width: 760px;

    margin: 0 auto 50px;

    text-align: center;
}

.badge {
    display: inline-block;

    padding: 8px 17px;

    border-radius: 30px;

    background: var(--gold);

    color: #050505;

    font-size: 12px;

    font-weight: 1000;

    letter-spacing: 1.5px;
}

.section-header h2 {
    margin-top: 18px;

    font-size: clamp(32px, 5vw, 52px);

    line-height: 1.05;
}

.section-header h2 span {
    color: var(--red);
}

.section-header p {
    margin-top: 15px;

    color: var(--gray);
}


/* =========================================================
   SERVICES
========================================================= */

.services-section {
    background: #080808;
}

.services-grid {
    display: grid;

    grid-template-columns:
        repeat(3, 1fr);

    gap: 22px;
}

.service-card {
    padding: 30px;

    background:
        linear-gradient(
            145deg,
            #191919,
            #0d0d0d
        );

    border:
        1px solid #292929;

    border-top:
        4px solid var(--red);

    border-radius: 15px;

    transition: .25s ease;
}

.service-card:hover {
    transform: translateY(-7px);

    border-color: var(--gold);

    box-shadow:
        0 20px 45px rgba(0,0,0,.5);
}

.service-icon {
    font-size: 35px;

    margin-bottom: 18px;
}

.service-card h3 {
    font-size: 21px;

    margin-bottom: 10px;
}

.service-card p {
    color: #aaa;

    font-size: 14px;
}

.service-card ul {
    list-style: none;

    margin-top: 18px;
}

.service-card li {
    padding: 7px 0;

    color: #ddd;

    font-size: 13px;
}

.service-card li::before {
    content: "✓";

    color: var(--gold);

    font-weight: 900;

    margin-right: 8px;
}


/* =========================================================
   ABOUT
========================================================= */

.about-section {
    background:
        radial-gradient(
            circle at 90% 20%,
            rgba(224,0,0,.12),
            transparent 30%
        ),
        #0b0b0b;
}

.about-grid {
    display: grid;

    grid-template-columns:
        1.15fr .85fr;

    gap: 60px;

    align-items: center;
}

.about-logo {
    color: var(--red);

    font-size: 90px;

    font-weight: 1000;

    line-height: .75;

    letter-spacing: -6px;
}

.about-content h2 {
    margin: 20px 0;

    font-size: clamp(32px, 5vw, 52px);

    line-height: 1.05;
}

.about-content h2 span {
    color: var(--red);
}

.about-content p {
    color: #bbb;

    margin-bottom: 18px;
}

.about-points {
    display: grid;

    grid-template-columns:
        repeat(2,1fr);

    gap: 12px;

    margin-top: 28px;
}

.about-point {
    padding: 17px;

    background: #141414;

    border:
        1px solid #282828;

    border-radius: 9px;
}

.about-point strong {
    display: block;

    color: var(--gold);

    margin-bottom: 4px;
}

.about-point span {
    color: #aaa;

    font-size: 12px;
}

.about-panel {
    padding: 35px;

    background:
        linear-gradient(
            145deg,
            #1a1a1a,
            #080808
        );

    border:
        1px solid #333;

    border-top:
        5px solid var(--gold);

    border-radius: 18px;
}

.about-panel h3 {
    font-size: 25px;

    margin-bottom: 20px;
}

.about-panel h3 span {
    color: var(--red);
}

.about-panel li {
    list-style: none;

    padding: 12px 0;

    border-bottom: 1px solid #292929;

    color: #ddd;
}

.about-panel li::before {
    content: "A-1";

    color: var(--gold);

    font-weight: 900;

    margin-right: 10px;
}


/* =========================================================
   PRICING
========================================================= */

.pricing-section {
    background: #050505;
}

.pricing-notice {
    max-width: 900px;

    margin:
        0 auto 45px;

    padding: 20px 25px;

    background: #151515;

    border-left:
        5px solid var(--red);

    border-radius: 10px;

    text-align: center;

    color: #bbb;
}

.pricing-notice strong {
    color: var(--gold);
}

.pricing-grid {
    display: grid;

    grid-template-columns:
        repeat(2,1fr);

    gap: 22px;
}

.price-card {
    padding: 28px;

    background:
        linear-gradient(
            145deg,
            #191919,
            #0c0c0c
        );

    border:
        1px solid #292929;

    border-top:
        4px solid var(--red);

    border-radius: 15px;
}

.price-card h3 {
    font-size: 23px;

    margin-bottom: 20px;
}

.price-card h3 span {
    color: var(--red);
}

.price-row {
    display: flex;

    justify-content: space-between;

    align-items: center;

    gap: 15px;

    padding: 13px 0;

    border-bottom:
        1px solid #292929;
}

.price-row:last-child {
    border-bottom: none;
}

.price-name {
    color: #ddd;

    font-size: 14px;
}

.price-value {
    white-space: nowrap;

    color: var(--gold);

    font-weight: 1000;
}

.price-labor {
    display: block;

    color: #777;

    font-size: 10px;

    font-weight: 500;

    margin-top: 2px;
}


/* =========================================================
   TESTIMONIALS
========================================================= */

.testimonials-section {
    background:
        linear-gradient(
            180deg,
            #090909,
            #050505
        );
}

.testimonials {
    display: grid;

    grid-template-columns:
        repeat(3,1fr);

    gap: 22px;
}

.testimonial {
    padding: 30px;

    background: #111;

    border:
        1px solid #292929;

    border-radius: 15px;

    position: relative;
}

.testimonial.featured {
    border-top:
        4px solid var(--gold);
}

.stars {
    color: var(--gold);

    letter-spacing: 3px;
}

.quote {
    color: var(--red);

    font-family: Georgia, serif;

    font-size: 60px;

    line-height: .7;

    margin:
        20px 0 10px;
}

.testimonial p {
    color: #bbb;

    font-size: 14px;

    min-height: 90px;
}

.customer {
    margin-top: 22px;

    padding-top: 17px;

    border-top:
        1px solid #292929;
}

.customer strong {
    display: block;
}

.customer span {
    color: #777;

    font-size: 11px;
}


/* =========================================================
   CTA
========================================================= */

.final-cta {
    padding: 90px 20px;

    text-align: center;

    background:
        radial-gradient(
            circle,
            rgba(224,0,0,.2),
            transparent 45%
        ),
        #090909;
}

.final-cta h2 {
    font-size: clamp(35px, 6vw, 60px);

    line-height: 1;
}

.final-cta h2 span {
    color: var(--red);
}

.final-cta p {
    max-width: 650px;

    margin:
        18px auto 30px;

    color: #aaa;
}


/* =========================================================
   FOOTER
========================================================= */

footer {
    background: #020202;

    border-top:
        1px solid #222;

    padding: 45px 0 25px;
}

.footer-grid {
    display: grid;

    grid-template-columns:
        1.3fr 1fr 1fr;

    gap: 40px;
}

.footer-brand strong {
    display: block;

    color: var(--red);

    font-size: 38px;

    font-weight: 1000;
}

.footer-brand p {
    margin-top: 10px;

    color: #777;

    font-size: 13px;
}

.footer-column h4 {
    color: var(--gold);

    margin-bottom: 12px;
}

.footer-column a {
    display: block;

    color: #aaa;

    font-size: 13px;

    margin: 7px 0;
}

.footer-column a:hover {
    color: white;
}

.footer-bottom {
    margin-top: 35px;

    padding-top: 20px;

    border-top: 1px solid #222;

    text-align: center;

    color: #666;

    font-size: 11px;
}


/* =========================================================
   MOBILE
========================================================= */

@media (max-width: 900px) {

    .nav-links {
        display: none;
    }

    .services-grid,
    .testimonials {
        grid-template-columns: 1fr 1fr;
    }

    .about-grid {
        grid-template-columns: 1fr;
    }

    .footer-grid {
        grid-template-columns: 1fr 1fr;
    }
}

@media (max-width: 650px) {

    .hero {
        min-height: auto;
    }

    .hero-content {
        padding: 65px 0;
    }

    .hero-logo {
        font-size: 95px;
    }

    .stats-grid {
        grid-template-columns: 1fr 1fr;
    }

    .stat:nth-child(2) {
        border-right: none;
    }

    .stat:nth-child(-n+2) {
        border-bottom:
            1px solid rgba(255,255,255,.18);
    }

    .services-grid,
    .pricing-grid,
    .testimonials,
    .footer-grid {
        grid-template-columns: 1fr;
    }

    .about-points {
        grid-template-columns: 1fr;
    }

    .section {
        padding: 65px 0;
    }

    .hero-buttons {
        flex-direction: column;
    }

    .btn {
        width: 100%;
    }

}

</style>
</head>


<body>


<!-- =========================================================
     NAVIGATION
========================================================= -->

<nav class="navbar">

<div class="container nav-inner">

    <a href="#home" class="nav-logo">
        <strong>A-1</strong>
        <span>CLEANERZ123 LLC</span>
    </a>

    <div class="nav-links">

        <a href="#about">ABOUT</a>

        <a href="#services">SERVICES</a>

        <a href="#pricing">PRICING</a>

        <a href="#reviews">REVIEWS</a>

        <a href="#contact" class="nav-call">
            GET A QUOTE
        </a>

    </div>

</div>

</nav>



<!-- =========================================================
     HERO
========================================================= -->

<section class="hero" id="home">

<div class="container">

<div class="hero-content">

    <div class="hero-kicker">
        GENERAL MAINTENANCE & FLOORING SOLUTIONS
    </div>

    <div class="hero-logo">
        A-1
    </div>

    <div class="hero-name">
        CLEANERZ<span>123</span> LLC
    </div>

    <div class="hero-subtitle">
        Professional Property Care • Reliable Service • Quality Workmanship
    </div>

    <p class="hero-description">
        From cleaning and turnovers to flooring, repairs,
        painting, drywall and pressure washing, A-1 Cleanerz123 LLC
        helps keep your property clean, functional and looking its best.
    </p>

    <div class="hero-buttons">

        <a
            href="tel:+12702285831"
            class="btn btn-red">
            CALL A-1 TODAY
        </a>

        <a
            href="mailto:a1cleanerz123@gmail.com"
            class="btn btn-gold">
            REQUEST A FREE ESTIMATE
        </a>

    </div>

    <div class="hero-trust">

        <span>Professional Service</span>

        <span>Quality Workmanship</span>

        <span>Free Estimates</span>

    </div>

</div>

</div>

</section>



<!-- =========================================================
     STATS
========================================================= -->

<section class="stats">

<div class="container stats-grid">

    <div class="stat">
        <strong>A-1</strong>
        <span>Property Care</span>
    </div>

    <div class="stat">
        <strong>123</strong>
        <span>Built For Service</span>
    </div>

    <div class="stat">
        <strong>100%</strong>
        <span>Customer Focused</span>
    </div>

    <div class="stat">
        <strong>FREE</strong>
        <span>Estimates</span>
    </div>

</div>

</section>



<!-- =========================================================
     SERVICES
========================================================= -->

<section class="section services-section" id="services">

<div class="container">

<div class="section-header">

    <div class="badge">
        WHAT WE DO
    </div>

    <h2>
        Complete Property
        <span>Solutions</span>
    </h2>

    <p>
        One company for cleaning, maintenance, flooring
        and property improvement needs.
    </p>

</div>


<div class="services-grid">


<div class="service-card">

    <div class="service-icon">🧹</div>

    <h3>Cleaning & Turnovers</h3>

    <p>
        Professional cleaning services for homes,
        rentals and property turnovers.
    </p>

    <ul>
        <li>Residential Cleaning</li>
        <li>Deep Cleaning</li>
        <li>Move-In / Move-Out</li>
        <li>Rental Turnovers</li>
    </ul>

</div>


<div class="service-card">

    <div class="service-icon">🛠️</div>

    <h3>Flooring Solutions</h3>

    <p>
        Flooring installation, preparation and
        repair services.
    </p>

    <ul>
        <li>Vinyl Plank</li>
        <li>Laminate</li>
        <li>Floor Repairs</li>
        <li>Floor Preparation</li>
    </ul>

</div>


<div class="service-card">

    <div class="service-icon">🔧</div>

    <h3>General Maintenance</h3>

    <p>
        Keep your property maintained and ready
        with dependable repair services.
    </p>

    <ul>
        <li>Property Repairs</li>
        <li>Baseboards & Trim</li>
        <li>Rental Maintenance</li>
        <li>Property Upkeep</li>
    </ul>

</div>


<div class="service-card">

    <div class="service-icon">🎨</div>

    <h3>Painting & Drywall</h3>

    <p>
        Interior improvement services that help
        refresh and restore your property.
    </p>

    <ul>
        <li>Interior Painting</li>
        <li>Drywall Repairs</li>
        <li>Wall Preparation</li>
        <li>Touch-Ups</li>
    </ul>

</div>


<div class="service-card">

    <div class="service-icon">💦</div>

    <h3>Pressure Washing</h3>

    <p>
        Exterior cleaning for surfaces that need
        a fresh, clean appearance.
    </p>

    <ul>
        <li>Driveways</li>
        <li>Sidewalks</li>
        <li>Patios & Decks</li>
        <li>Exterior Cleaning</li>
    </ul>

</div>


<div class="service-card">

    <div class="service-icon">⭐</div>

    <h3>Custom Services</h3>

    <p>
        Flexible property-care solutions for
        projects that don't fit a standard package.
    </p>

    <ul>
        <li>Maintenance Packages</li>
        <li>Property Management</li>
        <li>Commercial Services</li>
        <li>Custom Projects</li>
 # A collection of `.gitignore` templates

This is GitHub’s collection of [`.gitignore`][man] file templates.
We use this list to populate the `.gitignore` template choosers available
in the GitHub.com interface when creating new repositories and files.

For more information about how `.gitignore` files work, and how to use them,
the following resources are a great place to start:

- The [Ignoring Files chapter][chapter] of the [Pro Git][progit] book.
- The [Ignoring Files article][help] on the GitHub Help site.
- The [gitignore(5)][man] manual page.

[man]: https://git-scm.com/docs/gitignore
[help]: https://help.github.com/articles/ignoring-files
[chapter]: https://git-scm.com/book/en/v2/Git-Basics-Recording-Changes-to-the-Repository#_ignoring
[progit]: https://git-scm.com/book

## Folder structure

We support a collection of templates, organized in this way:

- The root folder contains templates in common use, to help people get started
  with popular programming languages and technologies. These define a meaningful
  set of rules to help get started, and ensure you are not committing
  unimportant files into your repository.
- [`Global`](./Global) contains templates for various editors, tools and
  operating systems that can be used in different situations. It is recommended
  that you either [add these to your global template](https://docs.github.com/en/get-started/getting-started-with-git/ignoring-files#configuring-ignored-files-for-all-repositories-on-your-computer)
  or merge these rules into your project-specific templates if you want to use
  them permanently.
- [`community`](./community) contains specialized templates for other popular
  languages, tools, and projects that don't currently belong in the mainstream
  templates. These should be added to your project-specific templates when you
  decide to adopt the framework or tool.

## What makes a good template?

First and foremost, a template contribution must adhere to our
[Contributing Guidelines](CONTRIBUTING.md).

A template should contain a set of rules to help Git repositories work with a
specific programming language, framework, tool or environment.

If it's not possible to curate a small set of useful rules for this situation,
then the template is not a good fit for this collection.

If a template is mostly a list of files installed by a particular version of
some software (e.g. a PHP framework), it could live under the `community`
directory. See [versioned templates](#versioned-templates) for more details.

If you have a small set of rules, or want to support a technology that is not
widely in use, and still believe this will be helpful to others, please read the
section about [specialized templates](#specialized-templates) for more details.

Include details when opening a pull request if the template is important and visible. We
may not accept it immediately, but we can promote it to the root at a later date
based on interest.

Please also understand that we can’t list every tool that ever existed.
Our aim is to curate a collection of the _most common and helpful_ templates,
not to make sure we cover every project possible. If we choose not to
include your language, tool, or project, it’s not because it’s not awesome.

## Contributing guidelines

Please see our [Contributing Guidelines](CONTRIBUTING.md).

## Versioned templates

Some templates can change greatly between versions, and if you wish to contribute
to this repository we need to follow this specific flow:

- the template at the root should be the current supported version
- the template at the root should not have a version in the filename (i.e.
  "evergreen")
- previous versions of templates should live under `community/`
- previous versions of the template should embed the version in the filename,
  for readability

This helps ensure users get the latest version (because they'll use whatever is
at the root) but helps maintainers support older versions still in the wild.

## Specialized templates

If you have a template that you would like to contribute, but it isn't quite
mainstream, please consider adding this to the `community` directory under a
folder that best suits where it belongs.

The rules in your specialized template should be specific to the framework or
tool, and any additional templates should be mentioned in a comment in the
header of the template.

For example, this template might live at `community/DotNet/InforCRM.gitignore`:

```gitignore
# gitignore template for InforCRM (formerly SalesLogix)
# website: https://www.infor.com/products/customer-experience-suite/crm
#
# Recommended: VisualStudio.gitignore

# Ignore model files that are auto-generated
ModelIndex.xml
ExportedFiles.xml

# Ignore deployment files
[Mm]odel/[Dd]eployment

# Force include portal SupportFiles
!Model/Portal/*/SupportFiles/[Bb]in/
!Model/Portal/PortalTemplates/*/SupportFiles/[Bb]in
```

## Contributing workflow

Here’s how we suggest you go about proposing a change to this project:

1. [Fork this project][fork] to your account.
2. [Create a branch][branch] for the change you intend to make.
3. Make your changes to your fork.
4. [Send a pull request][pr] from your fork’s branch to our `main` branch.

Using the web-based interface to make changes is fine too, and will help you
by automatically forking the project and prompting to send a pull request too.

[fork]: https://help.github.com/articles/fork-a-repo/
[branch]: https://help.github.com/articles/creating-and-deleting-branches-within-your-repository
[pr]: https://help.github.com/articles/using-pull-requests/

## License

[CC0-1.0](./LICENSE).

