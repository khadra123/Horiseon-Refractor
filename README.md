# Horiseon-Refractor

Commits or changes made in compared to the original file:

*Changed the <title> tag to Horiseon 
*Changed the html code to reflect html scemantics, such as headers, nav, footers, sections
*Added alt attributes to images to allow for accesibilty
*Cleaned up the code and made it more readable and spaced accordingly

Link for the site is https://github.com/khadra123/Horiseon-Refractor.

Below is a screenshot of the final website:
![Horiseon Website] (./assets/images/Horiseon-website-screenshot.png)

Below is the finished updated code:

'''html
<!DOCTYPE html>
<html lang="en-us">

    <head>
        <meta charset="UTF-8" />
        <link rel="stylesheet" href="./assets/css/style.css">
        <title>Horiseon</title>
    </head>

    <body>

        <header class="header">
            <h1><span class="seo">Horiseon</span</h1>
            <nav>
                <ul>
                    <li>
                        <a href="#search-engine-optimization">Search Engine Optimization</a>
                    </li>
                    <li>
                        <a href="#online-reputation-management">Online Reputation Management</a>
                    </li>
                    <li>
                        <a href="#social-media-marketing">Social Media Marketing</a>
                    </li>
                </ul>
            </nav>
        </header>

        <section class="hero"></section>

        <section class="content">
            <div id="search-engine-optimization" class="search-engine-optimization">
                <img src="./assets/images/search-engine-optimization.jpg" class="float-left" alt="Search engine optimization notebook and coffee" />
                <h2>Search Engine Optimization</h2>
                <p>
                    The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
                </p>
            </div>
            <div id="online-reputation-management" class="online-reputation-management">
                <img src="./assets/images/online-reputation-management.jpg" class="float-right" alt="Computer with reputation graph" />
                <h2>Online Reputation Management</h2>
                <p>
                    The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management gives you the control over what potential customers see when they search for your business.
                </p>
            </div>
            <div id="social-media-marketing" class="social-media-marketing">
                <img src="./assets/images/social-media-marketing.jpg" class="float-left" alt="Social media marketing brainstorm session" />
                <h2>Social Media Marketing</h2>
                <p>
                    Social media continues to have a sizable influence on buying habits. Social media marketing helps you determine which platforms are suited to your brand, using analytics to find the right markets and increase your lead generation.
                </p>
            </div>
        </section>

        <section class="benefits">
            <div class="benefit-lead">
                <h3>Lead Generation</h3>
                <img src="./assets/images/lead-generation.png" alt="Gear with arrow icon"/>
                <p>
                    Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
                </p>
            </div>
            <div class="benefit-brand">
                <h3>Brand Awareness</h3>
                <img src="./assets/images/brand-awareness.png" alt="Lightbulb as head that's radiating icon" />
                <p>
                    Users find your business through paid and organic searches, increasing the search ranking and visibility for your business.
                </p>
            </div>
            <div class="benefit-cost">
                <h3>Cost Management</h3>
                <img src="./assets/images/cost-management.png" alt="Gears and dollar coins icon"/>
                <p>
                    As the search ranking for your business increases, your advertising costs decrease, and you no longer need to advertise your page.
                </p>
            </div>
        </section>

        <footer class="footer">
            <h2>Made with ❤️️ by Horiseon</h2>
            <p>
                &copy; 2019 Horiseon Social Solution Services, Inc.
            </p>
        </footer>

    </body>

</html>

'''
