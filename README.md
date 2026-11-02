
<!DOCTYPE html>
<html lang="bn">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<meta name="description" content="Black Technologies Ltd. - Technology, Innovation and Future.">

<title>Black Technologies Ltd. | Official Website</title>

<style>

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    scroll-behavior: smooth;
}

body {
    background: #050505;
    color: #ffffff;
    font-family: Arial, sans-serif;
}

/* NAVBAR */

header {
    width: 100%;
    padding: 22px 7%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    background: rgba(5,5,5,0.96);
    border-bottom: 1px solid #242424;
    position: sticky;
    top: 0;
    z-index: 100;
}

.logo {
    font-size: 21px;
    font-weight: bold;
    letter-spacing: 1px;
}

.logo span {
    color: #d4af37;
}

nav a {
    color: #ddd;
    text-decoration: none;
    margin-left: 22px;
    font-size: 13px;
    transition: 0.3s;
}

nav a:hover {
    color: #d4af37;
}

/* HERO */

.hero {
    min-height: 88vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;
    padding: 50px 20px;
    background:
    radial-gradient(ellipse at center, #252016 0%, #101010 40%, #050505 75%);
}

.hero small {
    color: #d4af37;
    letter-spacing: 5px;
    margin-bottom: 25px;
}

.hero h1 {
    font-size: clamp(36px, 7vw, 75px);
    line-height: 1.15;
    margin-bottom: 25px;
}

.hero h1 span {
    color: #d4af37;
}

.hero p {
    color: #aaa;
    font-size: 17px;
    line-height: 1.9;
    max-width: 650px;
}

.hero-button {
    display: inline-block;
    margin-top: 35px;
    padding: 15px 35px;
    border: 1px solid #d4af37;
    color: #d4af37;
    text-decoration: none;
    letter-spacing: 2px;
    transition: 0.3s;
}

.hero-button:hover {
    background: #d4af37;
    color: #000;
}

.coming {
    margin-top: 25px;
    color: #888;
    letter-spacing: 5px;
    font-size: 12px;
}

/* GENERAL SECTION */

.section {
    padding: 85px 7%;
    text-align: center;
}

.section-title {
    font-size: 32px;
    margin-bottom: 15px;
}

.section-title span {
    color: #d4af37;
}

.section-subtitle {
    color: #888;
    margin-bottom: 45px;
    line-height: 1.8;
}

/* PRODUCTS */

.products {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 25px;
    max-width: 1100px;
    margin: auto;
}

.product-card {
    background: linear-gradient(145deg, #171717, #090909);
    border: 1px solid #292929;
    border-radius: 12px;
    padding: 30px 20px;
    transition: 0.3s;
}

.product-card:hover {
    transform: translateY(-7px);
    border-color: #d4af37;
}

.product-image {
    height: 170px;
    display: flex;
    align-items: center;
    justify-content: center;
    margin-bottom: 20px;
    background: #101010;
    border-radius: 8px;
    color: #d4af37;
    font-size: 65px;
}

.product-card h3 {
    font-size: 22px;
    margin-bottom: 12px;
}

.product-card p {
    color: #999;
    font-size: 14px;
    line-height: 1.8;
}

.product-status {
    display: inline-block;
    margin-top: 20px;
    padding: 9px 18px;
    border: 1px solid #d4af37;
    color: #d4af37;
    font-size: 11px;
    letter-spacing: 2px;
}

/* VISION */

.vision {
    background: #101010;
    border-top: 1px solid #222;
    border-bottom: 1px solid #222;
}

.vision p,
.about p {
    max-width: 750px;
    margin: auto;
    color: #aaa;
    line-height: 2;
    font-size: 16px;
}

/* UPCOMING */

.upcoming {
    padding: 90px 20px;
    text-align: center;
    background: linear-gradient(120deg, #17130b, #050505);
}

.upcoming h2 {
    font-size: 35px;
    margin-bottom: 20px;
}

.upcoming h2 span {
    color: #d4af37;
}

.upcoming p {
    color: #aaa;
    line-height: 1.8;
}

/* ABOUT */

.about {
    background: #0b0b0b;
}

/* CONTACT */

.contact {
    background: #101010;
}

.contact p {
    color: #aaa;
    line-height: 2;
}

/* FOOTER */

footer {
    padding: 35px 15px;
    text-align: center;
    color: #777;
    border-top: 1px solid #242424;
    font-size: 13px;
    line-height: 2;
}

footer span {
    color: #d4af37;
}

/* MOBILE */

@media(max-width: 700px) {

    header {
        flex-direction: column;
        gap: 18px;
        padding: 20px 10px;
    }

    nav a {
        margin: 0 8px;
        font-size: 12px;
    }

    .hero {
        min-height: 75vh;
    }

    .hero p {
        font-size: 15px;
    }

    .section {
        padding: 65px 18px;
    }

    .section-title {
        font-size: 27px;
    }

}

</style>
</head>

<body>

<!-- NAVIGATION -->

<header>

    <div class="logo">
        BLACK <span>TECHNOLOGIES</span>
    </div>

    <nav>
        <a href="#home">HOME</a>
        <a href="#products">PRODUCTS</a>
        <a href="#about">ABOUT</a>
        <a href="#contact">CONTACT</a>
    </nav>

</header>


<!-- HOMEPAGE -->

<section class="hero" id="home">

    <small>WELCOME TO THE FUTURE</small>

    <h1>
        THE FUTURE OF
        <span>TECHNOLOGY</span>
    </h1>

    <p>
        প্রযুক্তির নতুন সম্ভাবনা, আধুনিক উদ্ভাবন
        এবং ভবিষ্যতের নতুন অধ্যায় নিয়ে আসছে
        Black Technologies Ltd.
    </p>

    <a href="#products" class="hero-button">
        EXPLORE OUR WORLD
    </a>

    <div class="coming">
        SOMETHING BIG IS COMING
    </div>

</section>


<!-- PRODUCTS -->

<section class="section" id="products">

    <h2 class="section-title">
        OUR <span>PRODUCTS</span>
    </h2>

    <p class="section-subtitle">
        Discover our upcoming technology ecosystem.
    </p>

    <div class="products">

        <div class="product-card">

            <div class="product-image">B</div>

            <h3>Black Phone</h3>

            <p>
                A new vision of smartphones.
                Modern design and future technology.
            </p>

            <div class="product-status">
                COMING SOON
            </div>

        </div>


        <div class="product-card">

            <div class="product-image">P</div>

            <h3>Black Pad</h3>

            <p>
                Discover a new generation
                of tablet technology.
            </p>

            <div class="product-status">
                COMING SOON
            </div>

        </div>


        <div class="product-card">

            <div class="product-image">B</div>

            <h3>Black Book</h3>

            <p>
                Explore the future of
                modern computing.
            </p>

            <div class="product-status">
                COMING SOON
            </div>

        </div>

    </div>

</section>


<!-- VISION -->

<section class="section vision">

    <h2 class="section-title">
        OUR <span>VISION</span>
    </h2>

    <p>
        আমাদের লক্ষ্য আধুনিক প্রযুক্তির মাধ্যমে
        নতুন সম্ভাবনা তৈরি করা এবং ভবিষ্যতের
        প্রযুক্তি জগতে নতুন কিছু উপহার দেওয়া।

        উদ্ভাবন, সৃজনশীলতা এবং উন্নত প্রযুক্তির
        সমন্বয়ে আমরা তৈরি করতে চাই নতুন এক
        প্রযুক্তির যাত্রা।
    </p>

</section>


<!-- UPCOMING -->

<section class="upcoming">

    <h2>
        A NEW ERA IS <span>COMING</span>
    </h2>

    <p>
        Stay Connected.
        Something Big Is Coming Soon.
        <br>
        Follow Our Journey.
    </p>

</section>


<!-- ABOUT -->

<section class="section about" id="about">

    <h2 class="section-title">
        ABOUT <span>US</span>
    </h2>

    <p>
        Black Technologies Ltd. is an emerging
        technology brand focused on innovation,
        modern design and future possibilities.

        Our journey is just beginning.
        We are preparing for a new chapter
        in the world of technology.
    </p>

</section>


<!-- CONTACT -->

<section class="section contact" id="contact">

    <h2 class="section-title">
        CONTACT <span>US</span>
    </h2>

    <p>
        Stay Connected With Black Technologies Ltd.
        <br>
        Official Website | Coming Soon
    </p>

</section>


<!-- FOOTER -->

<footer>

    © 2026 Black Technologies Ltd.
    All Rights Reserved.

    <br>

    <span>TECHNOLOGY • INNOVATION • FUTURE</span>

</footer>

</body>
</html>
