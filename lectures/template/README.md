# Head Section

1. **DOCTYPE Declaration**: Defines the document as HTML5 (`<!DOCTYPE html>`).
2. **Language Declaration**: Sets the language of the document to English (`<html lang="en">`).
3. **Meta Tags**:
    - `<meta charset="utf-8">`: Defines the character encoding as UTF-8.
    - `<meta content="width=device-width, initial-scale=1.0" name="viewport">`: Ensures proper scaling on mobile devices.
    - `<meta content="" name="keywords">` and `<meta content="" name="description">`: Placeholder meta tags for SEO.
4. **Google Web Fonts**: Links to Google Fonts, specifically the `Open Sans` and `Playfair Display` fonts.
5. **Icon Font Stylesheets**: Links to external icon libraries:
    - FontAwesome for icon fonts.
    - Bootstrap Icons for additional iconography.
6. **Libraries Stylesheets**:
    - `animate.min.css`: Provides animations.
    - `owl.theme.default.min.css`: Provides styling for the Owl Carousel plugin.
7. **Custom Template Stylesheets**:
    - `bootstrap.min.css`: Core Bootstrap CSS file for responsive design and components.
    - `style.css`: The custom stylesheet for overriding and adding styles specific to the template.

# Body Section

1. **Spinner Section (`#spinner`)**: 
    - This section adds a loading spinner that displays while the page is loading. It uses a spinner border and is centered on the screen.
    - The spinner is styled with Bootstrap’s `text-primary` class and animated with CSS transitions. This div fades out once the page is fully loaded.
    
2. **Navbar & Hero Section (`navbar`, `carousel`)**:
    - The navbar is responsive and uses Bootstrap classes. It contains links to the homepage, about page, services, blog, and other pages.
    - Inside the hero section, a carousel is created using Bootstrap’s carousel component, with controls for switching between slides.
    - The carousel slides contain images and text, which include animated text and buttons using the `fadeInLeft` and `fadeInRight` animations.
    
3. **Feature Section (`container-fluid.feature`)**:
    - This section highlights four main features of the site (e.g., Quality Check, 5 Steps Filtration, etc.) with icons and short descriptions. 
    - The `.feature-item` class is used to style these items with padding, and animations are applied using the `wow fadeInUp` library to animate elements when they appear on the screen.

4. **About Section (`container-fluid.about`)**:
    - The about section includes an image on the left and text on the right.
    - The image is styled with a border and hover effects, while the text provides an overview of the company.
    - Within this section, there are two highlighted cards. These items are wrapped inside flex containers.

5. **Fact Counter Section (`container-fluid.counter`)**:
    - This section contains counters that count up to display statistics like "Happy Clients," "Transport," "Employees," and "Years of Experience."
    - Each counter item includes an icon, a title, and the counting number. The counter numbers are animated using JavaScript.

6. **Service Section (`container-fluid.service`)**:
    - Displays various service items like Residential Waters, Commercial Waters, etc. 
    - The layout uses flexbox to position the icon and text for each service. Hover effects and animations are applied.

7. **Products Section (`container-fluid.product`)**:
    - Showcases products (e.g., different types of water bottles) with images, names, descriptions, and prices. The items are presented in card-style blocks with rounded corners.
    - The products are wrapped inside a grid layout, and each product has a "Read More" button for more information.

8. **Team Section (`container-fluid.team`)**:
    - Displays the team members with images, names, roles, and social media links.
    - The team cards include hover effects where additional options (social media links) appear when the card is hovered over.

9. **Testimonial Section (`container-fluid.testimonial`)**:
    - This section features reviews in a carousel format, displaying images, names, and reviews.
    - The Owl Carousel library is used to rotate through the testimonials.

10. **Footer & Copyright Section**:
    - The footer contains links to informational pages (e.g., Why Choose Us, Terms & Conditions) and a newsletter subscription form.
    - Social media icons are also displayed in the footer.
    - The copyright section includes links and attributions to the site designer.
    
11. **JavaScript Libraries**:
    - jQuery, Bootstrap, and several other JavaScript libraries are linked at the bottom of the file (e.g., carousel, animations).

---

**Div Usage**:
- The template heavily relies on `div` containers to structure the layout, using Bootstrap’s grid system with classes like `container-fluid`, `row`, and `col-*`. This gives a responsive design.
- I noticed that nearly every section is wrapped in a `div` container, with additional inner containers for items like text, images, and buttons. 