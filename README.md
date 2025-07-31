# 📘 Assignment: HTML5 + Accessibility & SEO Basics

## Overview

This assignment will help you solidify your understanding of modern HTML5 structure while applying foundational concepts of web accessibility and search engine optimization (SEO). You’ll create a simple, semantically correct web page that prioritizes both human and machine readability—two pillars of great web design.

## Objective

Build a basic web page using HTML5 semantic tags, applying accessibility best practices and beginner-friendly SEO principles. Your final output should demonstrate a well-structured layout that supports screen readers and is optimized for discoverability.

## Guidelines

Use only HTML5. No CSS or JavaScript is required at this stage. Focus on using meaningful semantic elements to structure your page. Avoid using `<div>` or `<span>` unless absolutely necessary. Ensure your page has clearly defined sections such as a header, navigation, main content, and a footer.

Incorporate accessibility by using proper HTML5 landmarks and attributes that improve navigation for assistive technologies. Your HTML should reflect thoughtful planning of hierarchy and readability, both for users and search engines.

For SEO, emphasize the use of heading tags in the correct order, provide descriptive text, and ensure your content is both human-readable and crawler-friendly. Consider how a search engine would interpret your page in terms of structure and content clarity.

## Deliverables

A single HTML file named `index.html`. It should include:

* A semantic structure using appropriate HTML5 elements.
* Clear headings in a logical hierarchy.
* Accessibility enhancements using proper tags and attributes.
* SEO-friendly metadata and content.

## Tips

* Use HTML5 semantic tags appropriately.
* Organize content with accessibility in mind.
* Apply basic on-page SEO techniques.
* Follow clean, readable HTML code structure.


HTML CODE:
<!DOCTYPE html>
<html>

     <head>
         <title>Nigeria and its states</title>
     </head>
     <body>
         <header>
             <h1>Nigeria and its states</h1>

             <nav>
                <a href="#">History</a>
                <a href="#">Culture</a>
                <a href="#">Economy</a>
                <a href="#">Tourism</a>
              </nav>
         </header>

         <header>
            <h2>Nigeria</h2>
            <img src="Map of Nigeria.png" alt="Map of Nigeria" width="300" height="200">
   
              <p id="author"> Posted by <strong>Olaleye Ibrahim</strong> </p>
         </header>

         <h2>Geography of Nigeria</h2>
         <p>
             Nigeria is a country in West Africa located at Latitude 9.08'N and Longitude 
             8.67'E, these coordinates place Nigeria in both the Northern and Eastern hemispheres,
             bordering the Gulf of Guinea in the South, Benin in the West, Chad and Cameroon in the East,
             and Niger in the North.
         </p>
         <p>
             Nigeria has a tropical climate, with high temperatures and high humidity throughout
             the year. The country experiences two main seasons: a rainy season (April - October)
             and a dry season (November - March).
         </p>

         <h3>Nigeria and Its Geopolitical Zones</h3>
         <p>
            Nigeria is divided into six geopolitical zones, each with distinct
            characteristics and states.
         </p>
         <ol>
            <li>North Central Zone</li>
            <li>North East Zone</li>
            <li>North West Zone</li>
            <li>South East Zone</li>
            <li>South South Zone</li>
            <li>South West Zone</li>
       </ol>

       <P>
        You can learn more from
          <a href="www.withinnigeria.com"
         target="_blank">Nigeria and its Region</a>
     </P>
         
     <h3>Geopolitical Zone and characteristics its States</h3>
     <p>
         <strong>North Central Zone:</strong> Diverse topography, including Niger and Benue river valleys,
         expansive savannas, and the Jos plateau. This Zone is a transition area transition 
         area between the predominantly Muslim North and the largely Christian South.
     </p>
     <ul>
         <li>Benue</li>
         <li>Kogi</li>
         <li>Kwara</li>
         <li>Nasarawa</li>
         <li>Niger</li>
         <li>Plateu</li>
         <li>Federal Capital City(Abuja)</li>
     </ul>

     <p>
        <strong>North East Zone:</strong> Known for farming and animal husbandry. The region is home to the 
        Mandara Mountains have a mix of savannas and semi-arid landscapes.
    </p>
    <ul>
        <li>Adamawa</li>
        <li>Bauchi</li>
        <li>Borno</li>
        <li>Gombe</li>
        <li>Taraba</li>
        <li>Yobe</li>
    </ul>

    <p>
        <strong>North West Zone:</strong> Largest Zone in the country, known for cereal production
        like rice and sorghum.
    </p>
    <ul>
        <li>Jigawa</li>
        <li>Kaduna</li>
        <li>Kano</li>
        <li>Kastina</li>
        <li>Kebbi</li>
        <li>Sokoto</li>
        <li>Zamfara</li>
    </ul>

    <p>
        <strong>South East Zone:</strong> Predominatlyinhabited by the igbo people, known for rich
        cultural heritage and economic significance. Major cities include Aba and Onitsha.
    </p>
    <ul>
        <li>Abia</li>
        <li>Anambra</li>
        <li>Ebonyi</li>
        <li>Enugu</li>
        <li>Imo</li>
    </ul>

    <p>
        <strong>South South Zone:</strong> Characterised by mangroove swamps, lagoons and creeks.
        The region is crucial for Nigeria's oil industry and has significant environmental challenges. 
    </p>
    <ul>
        <li>Akwa Ibom</li>
        <li>Bayelsa</li>
        <li>Cross River</li>
        <li>Delta</li>
        <li>Edo</li>
        <li>Rivers</li>
    </ul>
    <P>
    <strong>South West Zone:</strong> Known for its Yoruba-speaking majority, academic institutions
    and economic hubs like Lagos. 
    </p>
    <ul>
        <li>Ekiti</li>
        <li>Lagos</li>
        <li>Ogun</li>
        <li>Ondo</li>
        <li>Osun</li>
        <li>Oyo</li>
    </ul>
    <footer>
        <p>
       Copyright &copy; 2025 by <strong>Olaleye Ibrahim</strong>
       </p>
    </footer>

     </body>

</html>
