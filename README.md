## **🎓 CSS Basics Assignment**  

### **Assignment Title**  
**"Mastering CSS Basics: Styling Your First Web Page"**  

---

### **📋 Objectives**  
- Understand the use of CSS selectors, properties, and values.  
- Apply inline, internal, and external CSS to style web pages.  
- Utilize basic CSS properties to control colors, fonts, alignment, padding, and margins.  

---

### **📂 Assignment Tasks**  

#### **Part 1: CSS Basics - Selectors, Properties, and Values (20 Points)**  
1. Create an HTML file with at least three different types of elements (e.g., `<h1>`, `<p>`, `<div>`).  
2. Style these elements using:  
   - **Element Selector**: Change the font size of all headings.  
   - **Class Selector**: Apply a background color to specific sections.  
   - **ID Selector**: Add a border to an element with a unique ID.  

---

#### **Part 2: Inline, Internal, and External CSS (30 Points)**  
1. Use **inline CSS** to style one element (e.g., change the text color).  
2. Add **internal CSS** in the `<style>` tag within the `<head>` section to style at least three elements.  
3. Create a separate **external CSS file** and link it to your HTML. Use it to:  
   - Change the background color of the webpage.  
   - Style links with hover effects.  

---

#### **Part 3: Basic Styling Properties (50 Points)**  
1. Apply the following styles:  
   - **Colors**: Set text and background colors for different elements.  
   - **Font Styles**: Change the font family, size, and weight of text.  
   - **Text Alignment**: Center-align, left-align, or justify text in paragraphs.  
   - **Spacing**: Add padding and margin to elements for proper spacing.  

2. Create a **simple card component** using these styles:  
   - A heading for the card title.  
   - A paragraph with some description.  
   - Add padding inside the card and a margin around it.  
   - Use a light background color and a subtle border.  
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Styling Example</title>
    
    <!-- Internal CSS -->
    <style>
        /* Internal CSS */
        h1, h2 {
            font-size: 2em;
        }

        .section {
            background-color: lightblue;
            padding: 20px;
        }

        #uniqueElement {
            border: 2px solid red;
            padding: 15px;
        }

        /* Styling for colors, font styles, text alignment, and spacing */
        body {
            background-color: #fff3e6;
        }

        h1 {
            color: darkblue;
            font-family: 'Arial', sans-serif;
            font-size: 36px;
            font-weight: bold;
        }

        p {
            color: #333;
            text-align: justify;
            font-family: 'Georgia', serif;
            font-size: 18px;
            margin: 10px 0;
        }

        .card {
            background-color: #fff;
            padding: 20px;
            margin: 30px;
            border: 1px solid #ddd;
            border-radius: 8px;
        }
    </style>

    <!-- Link to External CSS -->
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <h1>Welcome to My Webpage</h1>

    <p>This is a paragraph that explains something interesting on the webpage.</p>

    <!-- Section with class selector -->
    <div class="section">
        <h2>Special Section</h2>
        <p>This section has a light blue background, set with a class selector.</p>
    </div>

    <!-- Section with unique ID -->
    <div id="uniqueElement">
        <p>This section has a unique red border, set using an ID selector.</p>
    </div>

    <!-- Card component -->
    <div class="card">
        <h2>Card Title</h2>
        <p>This is a simple card component. It contains a heading and a description, styled with padding and a border for emphasis.</p>
    </div>

    <!-- Inline CSS applied directly -->
    <p style="color: green;">This paragraph has inline CSS applied to change its text color to green.</p>

</body>
</html>

```

This assignment will solidify your CSS basics while giving you a chance to style your first webpage creatively. Good luck and happy styling! 🎨🚀
