Report on Personal Website

1. Objective
The objective of this webpage is to design a personal portfolio-style interactive website with multiple sections: Welcome, About Me, and Hobbies. It introduces the creator, collects a visitor’s name, and displays personalized content.

2. Structure of the Webpage
- HTML5 is used to build the structure of the website.
- The content is divided into three “cards”:
  1. Page 1 (Welcome Page) – Contains introduction and input box for visitor’s name.
  2. Page 2 (About Me Page) – Displays personal educational background and greets the visitor by name.
  3. Page 3 (Hobbies Page) – Shows a list of hobbies in bullet points.

3. Styling (CSS)
- The background uses a light lavender shade (#F3E5F5) for a clean look.
- Content is centered both vertically and horizontally using Flexbox.
- Each section is styled as a card with:
  - White background
  - Rounded corners (16px)
  - Shadow effect for depth
- Buttons use a gradient purple theme for attractiveness.
- Typography is consistent with the Inter font.

4. Functionality (JavaScript)
- Navigation between pages is handled with functions that show/hide cards by toggling the .hidden class.
- Visitor Name Input:
  - On the first page, the visitor enters their name.
  - If no name is entered, an alert appears.
  - If a name is entered, it is displayed on the “About Me” page.
- Escape Function ensures user input is safe by preventing HTML injection.
- Buttons:
  - "Continue" → Goes from Welcome to About Me.
  - "Go to My Hobbies" → Switches to Hobbies page.
  - "Back" or "Back to Home" → Returns to Welcome page.

5. Features Highlight
- Interactive and personalized (asks for visitor’s name).
- Clean, responsive design with a professional card layout.
- Safe handling of input with escapeHtml() function.
- Simple, beginner-friendly navigation logic using JavaScript DOM manipulation.

6. Conclusion
The webpage successfully demonstrates a mini personal portfolio website with interactive navigation. It is built using only HTML, CSS, and JavaScript without external libraries. It shows personal introduction, education details, and hobbies in a user-friendly manner.
