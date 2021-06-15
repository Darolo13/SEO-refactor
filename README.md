# SEO Webpage Refactor </h1>
## Web Accesibility 
 *This challenge is about **Accesibility**, Web accessibility is the inclusive practice of ensuring that websites, 
  tools and technologies are designed and developed so that people with disabilities can use them, in this case with HTML5 using semantic elements like the following:
  Header, Section, Article, Main, Footer, etc. and implementing alt attributes to improve the accesibility of websites.*
## Code Modifcations To Comply With Web Accesibility
In the following section there will be examples of modifications made to improve accesibility.

## <code>header</code> and <code>nav</code>:

This code is the responsible for the creation of the navbar and navigating fast through the page with the keyboard.

* **header:** Specifies a header for a document or section.
* **nav:** Defines navigation links.

 <br>
  
  <!-- changed div to header -->
    <header>
        <h1>Hori<span class="seo">seo</span>n</h1>
        <!-- changed div to nav -->
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
    
 ## <code>section</code>, <code>main</code> and <code>article</code>
 
 * **section:** Defines a section in a document.
 * **main:** Specifies the main content of a document.
 * **article:** Defines independent, self-contained content.

  <br>
  
    <!-- changed div to main to indicate main content of the page for screen readers and removed unnecesary class="content" -->
    <main>
        <!-- changed div to article and removed unecesary class="search-engine-optimization" and changed it for id="search-engine-optimization" -->
        <article id="search-engine-optimization">
            <img src="./assets/images/search-engine-optimization.jpg" class="float-left" />
            <h2>Search Engine Optimization</h2>
            <p>
                The dominance of mobile internet use means that users are searching for the right business as they travel, shop, or sit on their couch at home. Search Engine Optimization (SEO) allows you to increase your visibility and find the right customers for your business.
            </p>
        </article>

        <!-- changed div to article and removed unecessary class="online-reputation-management" -->
        <article id="online-reputation-management">
            <img src="./assets/images/online-reputation-management.jpg" class="float-right" />
            <h2>Online Reputation Management</h2>
            <p>
                The web is full of opinions, and some of these can be negative. Social media allows anyone with an internet connection to say whatever they want about your business. Online Reputation Management gives you the control over what potential customers see when they search for your business.
            </p>
        </article>

        <!-- changed div to article and removed unecessary class="social-media-marketing" -->
        <article id="social-media-marketing">
            <img src="./assets/images/social-media-marketing.jpg" class="float-left" />
            <h2>Social Media Marketing</h2>
            <p>
                Social media continues to have a sizable influence on buying habits. Social media marketing helps you determine which platforms are suited to your brand, using analytics to find the right markets and increase your lead generation.
            </p>
        </article>
    </main>
    <!-- end of main -->
    
   ## <code>jumbotron/hero img</code>
 * **jumbotron/hero img:** allows to understand special content or information in this case through a image also to those with screen readers due to the alt description.   

<!-- <section><img src="./assets/images/digital-marketing-meeting.jpg" alt="Marketing office meeting of four people" class="hero"> </section> -->
    <!-- changed div to section and added digital-marketing-meeting.jpg with alt description for semantics and web accessibility  -->
    <section><img src="./assets/images/digital-marketing-meeting.jpg" alt="Marketing office meeting of four people" class="hero"> </section> 

 ## <code>footer</code> 
* **footer:** Defines a footer for a document or section.

 <!-- changed div to footer for semantics and removed class="footer" -->
    <footer>
        <h2>Made with ❤️️ by Horiseon</h2>
        <p>
            &copy; 2019 Horiseon Social Solution Services, Inc.
        </p>
    </footer>
    
    
  
    
    
  
  
  


  
