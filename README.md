[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/Hps6w29T)
# MP1: Static Web Page Development

**Due Date: April 11th, End of Day**

## Objective

Your task is to create a visually engaging **static website** using only HTML and CSS. This assignment will help you demonstrate your understanding of fundamental web development concepts including semantic HTML structure, CSS styling techniques, and design principles.

## Requirements

### Technical Requirements

- **HTML**
  - Use semantic HTML5 elements (`header`, `nav`, `main`, `section`, `article`, `footer`, etc.)
  - Include proper document structure with `<!DOCTYPE html>`, `<html>`, `<head>`, and `<body>` tags
  - Implement well-organized content hierarchy with appropriate heading levels
  - Add images with appropriate alt text for accessibility
  - Implement links (internal, external, or both)
  - Include at least one list (ordered or unordered)          ---- OPTIONAL
  - Include a contact form (non-functional is fine)           ---- OPTIONAL

- **CSS**
  - Create a separate CSS file linked to your HTML document
  - Use class and ID selectors appropriately
  - Implement at least two hover effects
  - Use Flexbox or Grid (or both) for layout purposes
  - Apply thoughtful typography (font families, sizes, weights, etc.)
  - Create a cohesive color scheme (at least 3-4 colors)
  - Include appropriate spacing (margin, padding) and borders

### Submission
  - Push the code to Github (all files)
  - Add a small quick recording to the readme file on the repository (assignment repo) of the website you have built, displaying hover effects, links (by clicking stuff), etc

## Project Ideas

Choose ONE of the following project ideas:

1. **Google Drive Clone Homepage**
   - Recreate a simplified version of the Google Drive interface
   - Focus on layout, images, links, and borders
   - No functionality required, just the visual interface

2. **Personal Recipe Collection**
   - Create a page featuring 3-5 recipes
   - Include images, ingredients lists, and step-by-step instructions
   - Organize with a clean, user-friendly layout

3. **Band/Musician Showcase**
   - Design a promotional page for a band or musician (real or fictional)
   - Include sections for bio, music samples, tour dates, images
   - Create a visually appealing layout that matches the music style

4. **Travel Destination Guide**
   - Create a page for a travel destination
   - Include sections for attractions, accommodations, and travel tips
   - Use images and descriptions to make the destination appealing

5. **Product Landing Page**
   - Design a page showcasing a product (real or fictional)
   - Include product features, pricing, testimonials
   - Create a compelling call-to-action

6. **Event Announcement Page**
   - Design a page for an upcoming event
   - Include event details, schedule, speakers/performers, registration info
   - Create excitement through design elements

**Feel free to propose your own idea** if none of these appeal to you. (Keep the idea simple)

## Getting Started

### Setting Up Your Project

1. Clone the repository to your local machine
2. Create your project files:
   - `index.html` (main HTML file)
   - `styles.css` (CSS file) ---- YOU CAN ALSO CREATE AND LINK MULTIPLE CSS FILES IF YOU WOULD LIKE
   - `images/` folder (for storing your local images)
3. Begin coding your HTML structure before adding CSS

### File Structure Example

```
project-folder/
│
├── index.html
├── styles.css
└── images/
    ├── image1.jpg
    ├── image2.jpg
    └── ...
```

### HTML Template

Here's a basic HTML template to get you started:
This is just an example, you are in no way bound to use this, this is just an example to help you, feel free to start from scratch if you would like

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Project Title</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Your Website Title</h1>
        <nav>
            <ul>
                <li><a href="#section1">Section 1</a></li>
                <li><a href="#section2">Section 2</a></li>
                <li><a href="#section3">Section 3</a></li>
            </ul>
        </nav>
    </header>
    
    <main>
        <section id="section1">
            <h2>Section 1 Heading</h2>
            <p>Your content here...</p>
        </section>
        
        <section id="section2">
            <h2>Section 2 Heading</h2>
            <p>Your content here...</p>
        </section>
        
        <section id="section3">
            <h2>Section 3 Heading</h2>
            <p>Your content here...</p>
        </section>
    </main>
    
    <footer>
        <p>&copy; 2025 Your Name</p>
    </footer>
</body>
</html>
```

### CSS Linking Example

Make sure to link your CSS file in the `<head>` section of your HTML:

```html
<link rel="stylesheet" href="styles.css">
```

### CSS Techniques

Here are some CSS techniques you should implement:

#### Class and ID Selectors

```css
/* Class selector (can be used multiple times) */
.card {
    border: 1px solid #ddd;
    border-radius: 8px;
    padding: 20px;
    margin-bottom: 20px;
}

/* ID selector (should be unique) */
#hero-section {
    background-color: #f5f5f5;
    padding: 50px 0;
    text-align: center;
}
```

#### Flexbox Example

```css
.container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
}

.item {
    flex: 1 0 300px;
    margin: 10px;
    padding: 20px;
    background-color: #f0f0f0;
}
```

#### Grid Example

```css
.grid-container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-gap: 20px;
    padding: 20px;
}

.grid-item {
    background-color: #e0e0e0;
    padding: 20px;
    border-radius: 5px;
}
```

#### Hover Effects

```css
.button {
    background-color: #3498db;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 4px;
    cursor: pointer;
    transition: background-color 0.3s ease;
}

.button:hover {
    background-color: #2980b9;
}

.card {
    border: 1px solid #ddd;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.card:hover {
    transform: translateY(-5px);
    box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
}
```

## Design Considerations

### Typography

- Choose 1-2 font families for your website (e.g., one for headings, one for body text)
- Establish a clear hierarchy with different font sizes for headings and body text
- Consider line height and letter spacing for readability
- You can use Google Fonts by adding the appropriate link in your HTML head:
  ```html
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
  ```

### Color Scheme

- Choose a primary color, a secondary color, and 1-2 accent colors
- Use colors consistently throughout your website
- Ensure sufficient contrast between text and background colors for readability
- Consider using tools like [Coolors](https://coolors.co/) or [Adobe Color](https://color.adobe.com/) to generate harmonious color schemes

### Layout

- Use a consistent layout throughout your pages
- Implement appropriate whitespace to avoid cluttered designs
- Consider the visual hierarchy of your content
- Make intentional decisions about alignment and spacing

### Responsive Design (Optional)

- Use media queries to adapt your layout to different screen sizes:
  ```css
  /* For tablets */
  @media (max-width: 768px) {
      .grid-container {
          grid-template-columns: repeat(2, 1fr);
      }
  }

  /* For mobile phones */
  @media (max-width: 480px) {
      .grid-container {
          grid-template-columns: 1fr;
      }
      
      .header {
          flex-direction: column;
      }
  }
  ```

## Evaluation Criteria

Your assignment will be evaluated based on the following criteria:

### Code Quality (30%)
- Proper use of semantic HTML
- Efficient and logical CSS
- Separation of structure (HTML) and presentation (CSS)

### Design Aesthetics (30%)
- Visual appeal and coherence
- Thoughtful typography and color choices
- Appropriate use of whitespace and layout
- Overall user experience

### Technical Implementation (25%)
- Correct implementation of required features
- Proper use of CSS techniques (flexbox/grid, selectors, etc.)
- Code functionality (all links work, no broken images, etc.)

### Accessibility Considerations (5%)
- Proper use of semantic HTML for screen readers
- Sufficient color contrast
- Alternative text for images
- Logical tab order for keyboard navigation

### Demo Video Showing Functionality
- 30 sec - 1.5 min video
- Talk about your use case (project idea you are building)

## Submission Instructions

1. Push your final code to your GitHub repository
3. Submit the following on Canvas:
   - Link to your GitHub repository (once all commits are pushed) - this way we will know you've submitted the assignment
   - Brief explanation of any challenges you faced (OPTIONAL, but we would like to know how has your experience been, in order to tweak future assignments, maybe offer less/more help as requested)

## Tips for Success

- **Start early** - Don't wait until the last minute
- **Plan your design** - Sketch your layout before coding
- **Keep it simple** - Focus on meeting the requirements well rather than adding many features
- **Test regularly** - Check your website in different browsers and screen sizes
- **Ask questions** - Use office hours and class time to get help when needed
- **Validate your code** - Use tools like [HTML Validator](https://validator.w3.org/) and [CSS Validator](https://jigsaw.w3.org/css-validator/)

## Resources

### HTML & CSS References
- [MDN Web Docs (HTML)](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [MDN Web Docs (CSS)](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [CSS-Tricks Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
- [CSS-Tricks Grid Guide](https://css-tricks.com/snippets/css/complete-guide-grid/)

### Design Resources
- [Google Fonts](https://fonts.google.com/)
- [Font Pair](https://fontpair.co/) (for font pairing ideas)
- [Coolors](https://coolors.co/) (color scheme generator)
- [Unsplash](https://unsplash.com/) (free high-quality images)

### Tools
- [Can I Use](https://caniuse.com/) (browser compatibility checker)
- [HTML Color Codes](https://htmlcolorcodes.com/) (color picker)

Good luck, and have fun creating your static website!
