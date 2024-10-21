# Nav Bar
* **NSIT Acronym**: NSIT should be spelt out in the about section and the pronounication
* **Dark Mode Toggle**: Mood toggle with different themes (e.g. skeleton.dev)
# Hero Section
* **Slogan**: Better Slogan & Aiignment with company name
* **Slogan Design**: One word can be coloured to bring out the central idea of the company (e.g. Transforming)
* **Services Offered**: Users should be clear on what the company offer in Hero Section. (e.g. carousell of random AI generated image on skills learnt, cooking -> programming -> writing)
# Customer Segments
* **Strange Categorisation**: Government is promoting skills rather than qualifications and striving for lifelong learning. Customers should not be segregated by age groups as courses are applicable for any age.
* **Skillsets**: Instead of categorising, we can show them the tangible results after attaining the course (e.g. applying AI in life).
* **Example**: Are you considering a career switch but do not have the right background? | Do you know the basics of web development and want to learn blockchain development? (Categories are not exhaustive, new categories can be created when customers start to ask questions about their suitability)
# Customer Segment
**AI Generated Image**: Image used in `Our Customer Segment` potrays Westerners working in a office. Better image can be used with Singaporeans working instead.
**Images used in Trainers**: Extra Hover effect can be added to showcase the companies / projects the trainers have done.
# Course Routes:
**Career Tracks / Course Path**: Recommend a progression path for people to follow which need not be linearlly followed. (e.g. students can take multiple courses of different discipline in parallel)
# User's Perspective
* **Advertising**: Site is filled with advertising, consider a fun fact section for people to visit more often
# Market Reseach
* **In Demand Courses**: What are the most in demand course now? If no courses are done by the organisation, free courses can be shown. If courses are done already, we can tell people how we value-add to the free resources online and the contexualisation to Singapore.
# Concerns
* **Numbers** should not be put publicly in order to prevent spam & doxxing. The number on the site should be a buisness number.
* **Emergency**: They should not be calling you in an emergecy.
* **Contact**: When contacts / email is left on the site, it should be actionable. (e.g. click and there is a link to email)
* **Missing Contact**: There is no email address written in Contact.
* **Mobile Friendly**: The address is not clearly shown in mobile view. An address with link to a map can be created for greater convenience.
* **Social Media Icons**: Social media should be left more visible in the contact page.
* **Testimonial Section**: Testimonials content should be targetted to answering the SkillsFuture question: "Do you find the course content useful?" | "Are you able to apply what you have learnt in the workplace?" | "I am now able to progress futher in my career path."
# From claude.ai
The JavaScript in this HTML document performs several important functions:

Lazy Loading:
- It sets up lazy loading for images and background images using the LazyLoad library.
- A LazyLoad instance is created with custom settings.
- It updates the lazy loading on scroll and after AJAX requests to handle dynamically loaded content.


Animation:
- Sets up an Intersection Observer to detect when elements with the class "elementor-invisible" come into view.
- When visible, it removes the "elementor-invisible" class and adds animation classes based on settings in the data-settings attribute.


Elementor Framework:
- Loads various Elementor scripts for the page builder functionality.
- Initializes Elementor frontend modules and widgets.


Other Functionality:
- Loads scripts for social icons, forms, and other Elementor widgets.
- Sets up event listeners for things like the newsletter subscription form.


Performance Optimization:
- Many scripts use data-two_delay attributes, likely for deferred loading to improve page load performance.
- There's a worker script that seems to handle some background tasks, possibly related to resource loading or optimization.


Custom Behaviors:
- There are some custom scripts for specific functionality, like the section generation embed script.


Third-party Integrations:
- Loads scripts for libraries like jQuery UI, Underscore.js, and Masonry for layout.


WordPress Integration:
- Loads WordPress core scripts and handles WordPress-specific functionality.

The overall structure suggests this is a WordPress site using the Elementor page builder with various optimizations and custom functionality added. The JavaScript works together to create an interactive, animated, and optimized user experience.
