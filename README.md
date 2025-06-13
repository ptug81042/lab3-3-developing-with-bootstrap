# Lab 3.3: Developing with Bootstrap

## Reflection
After refactoring these challenges to use Bootstrap, take a few minutes to answer the following questions:

1. **What challenges did you face when refactoring your code to use Bootstrap?**  
   When refactoring to use Bootstrap, one challenge was translating custom CSS layouts and spacing into Bootstrap’s grid system and utility classes. It required rethinking the structure of the HTML to take full advantage of Bootstrap’s components and utilities. Sometimes, finding the right combination of Bootstrap classes to match the original design took some experimentation, especially for precise alignment and spacing.

2. **How did using Bootstrap utility classes and components simplify your styling process?**  
   Bootstrap utility classes and components greatly simplified the styling process by providing ready-made solutions for layout, spacing, and alignment. Instead of writing custom CSS for margins, padding, centering, and card layouts, I could use Bootstrap’s classes directly in the HTML. This reduced the amount of custom CSS needed, made the code more maintainable, and sped up the development process.

3. **In what scenarios might you choose not to use Bootstrap and write custom CSS instead?**  
   I might choose not to use Bootstrap when a project requires a highly unique or branded design that doesn’t fit Bootstrap’s default styles, or when minimizing file size and dependencies is critical. For small, simple components or when fine-grained control over every aspect of the design is needed, writing custom CSS can offer more flexibility.

---

## Challenge Summaries

### QR Code Component ([qr-code-component-main](qr-code-component-main/))
- **Description:**  
  This challenge involved building a simple and clean QR code card component based on a Figma design. The component displays a QR code image, a heading, and a short description, all centered within a card.
- **Key Features:**  
  - Responsive card layout using **Bootstrap's grid system** and utility classes  
  - Use of **Bootstrap's card component** for simplified markup and styling  
  - Custom CSS properties for colors and spacing  
  - Google Fonts integration (Outfit)  
  - Mobile-first design and accessibility considerations
- **What I Learned:**  
  I learned how to use Bootstrap's grid and flex utilities to center content responsively, and how to simplify markup using Bootstrap's card component.  
  I practiced using semantic HTML, CSS custom properties, and improved my ability to match a design exactly and ensure responsiveness across devices.

### Blog Preview Card ([blog-preview-card-main](blog-preview-card-main/))
- **Description:**  
  This challenge required creating a blog preview card component that includes an image, category label, publish date, title, description, and author info. The card features interactive hover and focus states.
- **Key Features:**  
  - Responsive card layout with Bootstrap's grid system and utility classes  
  - Use of Bootstrap's card component for simplified markup and styling  
  - Custom properties for consistent theming  
  - Interactive hover and focus states  
  - Use of the Figtree font from Google Fonts  
  - Accessible, semantic HTML structure
- **What I Learned:**  
  I learned how to implement interactive states for better UX, use CSS variables for theming, and structure HTML for accessibility.  
  I also gained experience in translating detailed Figma designs into code, ensuring the component looks good on all screen sizes, and leveraging Bootstrap
