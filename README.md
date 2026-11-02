
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#080808">
<meta name="description" content="Black Technologies Ltd. — A new vision of technology, innovation and the future.">

<title>Black Technologies Ltd. | Coming Soon</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    scroll-behavior: smooth;
}

body {
    background: #080808;
    color: #fff;
    font-family: Arial, Helvetica, sans-serif;
    line-height: 1.6;
}

:root {
    --gold: #d6b46a;
    --dark: #080808;
    --card: #141414;
}

header {
    width: 100%;
    padding: 20px 8%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: rgba(8,8,8,.95);
    border-bottom: 1px solid #292929;
    position: sticky;
    top: 0;
    z-index: 100;
}

.logo {
    color: var(--gold);
    font-size: 21px;
    font-weight: bold;
    letter-spacing: 1px;
}

nav {
    display: flex;
    gap: 25px;
}

nav a {
    color: #ddd;
    text-decoration: none;
    font-size: 13px;
    transition: .3s;
}

nav a:hover {
    color: var(--gold);
}

.hero {
    min-height: 90vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 60px 20px;
    background:
    radial-gradient(ellipse at center, #292015 0%, #111 42%, #080808 75%);
}

.hero-content {
    max-width: 850px;
}

.tag {
    color: var(--gold);
    letter-spacing: 5px;
    font-size: 12px;
    margin-bottom: 22px;
}

.hero h1 {
    font-size: clamp(38px, 7vw, 76px);
    line-height: 1.15;
    margin-bottom: 22px;
    letter-spacing: 2px;
}

.hero h1 span {
    color: var(--gold);
}

.hero p {
    color: #bbb;
    font-size: 16px;
    max-width: 650px;
    margin: auto;
}

.coming {
    display: inline-block;
    margin-top: 35px;
    padding: 13px 32px;
    border: 1px solid var(--gold);
    color: var(--gold);
    letter-spacing: 3px;
    font-size: 13px;
}

section {
    padding: 90px 8%;
}

.section-title {
    text-align: center;
    margin-bottom: 50px;
}

.section-title h2 {
    color: var(--gold);
    font-size: 32px;
    margin-bottom: 12px;
}

.section-title p {
    color: #999;
    font-size: 14px;
}

.products {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 25px;
}

.product-card {
    background: var(--card);
    border: 1px solid #292929;
    padding: 35px 25px;
    text-align: center;
    border-radius: 10px;
    transition: .3s;
}

.product-card:hover {
    transform: translateY(-8px);
    border-color: var(--gold);
}

.product-icon {
    width: 95px;
    height: 115px;
    margin: 0 auto 25px;
    border: 2px solid var(--gold);
    border-radius: 15px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 30px;
    color: var(--gold);
    background: linear-gradient(145deg, #242018, #090909);
}

.product-card h3 {
    color: var(--gold);
    font-size: 23px;
    margin-bottom: 10px;
}

.product-card p {
    color: #aaa;
    font-size: 14px;
}

.status {
    display: inline-block;
    color: var(--gold);
    border: 1px solid #806b40;
    padding: 6px 16px;
    margin-top: 20px;
    font-size: 11px;
    letter-spacing: 1px;
}

.vision {
    background: #101010;
    text-align: center;
}

.vision-text {
    max-width: 800px;
    margin: auto;
    color: #bbb;
    font-size: 16px;
}

.vision-text strong {
    color: var(--gold);
}

.upcoming {
    text-align: center;
    background: linear-gradient(135deg, #17130c, #080808);
}

.upcoming h2 {
    font-size: 35px;
    color: var(--gold);
    margin-bottom: 15px;
}

.upcoming p {
    color: #bbb;
}

.about {
    text-align: center;
}

.about-content {
    max-width: 800px;
    margin: auto;
    color: #aaa;
}

.about-content h3 {
    color: var(--gold);
    font-size: 24px;
    margin-bottom: 18px;
}

.contact {
    background: #111;
    text-align: center;
}

.contact p {
    color: #aaa;
    margin: 10px 0;
}

footer {
    padding: 35px 15px;
    text-align: center;
    border-top: 1px solid #292929;
    background: #050505;
}

footer h3 {
    color: var(--gold);
    letter-spacing: 2px;
    margin-bottom: 10px;
}

footer p {
    color: #777;
    font-size: 12px;
}

@media(max-width: 750px) {
    header {
        padding: 18px 5%;
        flex-direction: column;
        gap: 15px;
    }

    nav {
        gap: 15px;
        flex-wrap: wrap;
        justify-content: center;
    }

    nav a {
        font-size: 12px;
    }

    .products {
        grid-template-columns: 1fr;
    }

    section {
        padding: 65px 6%;
    }

    .hero {
        min-height: 75vh;
    }
}
</style>
</head>

<body>

<header>
    <div class="logo">BLACK TECHNOLOGIES</div>

    <nav>
        <a href="#home">Home</a>
        <a href="#products">Products</a>
        <a href="#vision">Vision</a>
        <a href="#about">About</a>
        <a href="#contact">Contact</a>
    </nav>
</header>

<main>

<section class="hero" id="home">
    <div class="hero-content">
        <div class="tag">INNOVATION • TECHNOLOGY • FUTURE</div>

        <h1>
            THE FUTURE<br>
            OF <span>TECHNOLOGY</span>
        </h1>

        <p>
            A new vision of technology is coming.
            Discover innovation, creativity and
            the possibilities of tomorrow.
        </p>

        <div class="coming">COMING SOON</div>
    </div>
</section>

<section id="products">
    <div class="section-title">
        <h2>OUR PRODUCTS</h2>
        <p>Introducing a new generation of technology.</p>
    </div>

    <div class="products">

        <div class="product-card">
            <div class="product-icon">B</div>
            <h3>Black Phone</h3>
            <p>
                A new smartphone vision focused on
                modern design and innovation.
            </p>
            <div class="status">COMING SOON</div>
        </div>

        <div class="product-card">
            <div class="product-icon">P</div>
            <h3>Black Pad</h3>
            <p>
                Exploring a smarter and more
                creative tablet experience.
            </p>
            <div class="status">COMING SOON</div>
        </div>

        <div class="product-card">
            <div class="product-icon">B</div>
            <h3>Black Book</h3>
            <p>
                A new concept for modern computing
                and productivity.
            </p>
            <div class="status">COMING SOON</div>
        </div>

    </div>
</section>

<section class="vision" id="vision">
    <div class="section-title">
        <h2>OUR VISION</h2>
        <p>Building possibilities for tomorrow.</p>
    </div>

    <div class="vision-text">
        <p>
            Our vision is to explore new possibilities
            in the world of technology. We believe in
            <strong>innovation, creativity and progress</strong>.
            Our goal is to develop ideas that can make
            technology more accessible and meaningful
            for the future.
        </p>
    </div>
</section>

<section class="upcoming">
    <h2>A NEW CHAPTER BEGINS</h2>
    <p>
        Something exciting is in development.
        Stay connected for upcoming announcements.
    </p>
    <div class="coming">BIG UPDATES COMING SOON</div>
</section>

<section class="about" id="about">
    <div class="section-title">
        <h2>ABOUT US</h2>
        <p>Discover Black Technologies Ltd.</p>
    </div>

    <div class="about-content">
        <h3>Black Technologies Ltd.</h3>
        <p>
            Black Technologies Ltd. is an upcoming
            technology brand concept focused on
            exploring innovative ideas, modern
            technology and future possibilities.
            This is the beginning of a new journey.
        </p>
    </div>
</section>

<section class="contact" id="contact">
    <div class="section-title">
        <h2>STAY CONNECTED</h2>
        <p>More information and announcements coming soon.</p>
    </div>

    <p>Black Technologies Ltd.</p>
    <p>Official Website — Coming Soon</p>
</section>

</main>

<footer>
    <h3>BLACK TECHNOLOGIES LTD.</h3>
    <p>Innovation • Technology • Future</p>
    <p>© 2026 Black Technologies Ltd. All Rights Reserved.</p>
</footer>

</body>
</html>
