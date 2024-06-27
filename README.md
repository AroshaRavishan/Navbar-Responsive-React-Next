# Navbar Component

This is a React component that renders a navigation bar with various features.

## Previews

![Large Screen Preview](https://github.com/AroshaRavishan/Navbar-Responsive-React-Next/raw/main/Large%20screen%20view.png)

![Mobile View Preview](https://github.com/AroshaRavishan/Navbar-Responsive-React-Next/raw/main/mobile%20view.png)

## Features

- **Sticky Navigation:** The navigation bar is sticky with a blue background.
- **Logo Integration:** Includes a logo on the left side that links to the homepage.
- **Navigation Links:** Provides links to different sections:
  - "Why choose us"
  - "Essential Offerings"
  - "Services" (with a dropdown menu)
  - "Testimonials"
  - "FAQ's"
  - "Contact"
- **Dropdown Menu:** The "Services" link has a dropdown menu with three sub-links:
  - "LMS Solutions"
  - "Custom e-Learning"
  - "Certification Programmes"
- **Responsive Design:** The component adapts its layout for mobile devices.
- **Mobile Menu Toggle:** On mobile devices, the navigation bar can be toggled open and closed using a button.
- **Consistent Links:** Both desktop and mobile menus have the same links, adjusted for layout.

## How it Works

- **React Hooks:** Uses useState and useRef to manage state and handle events.
- **Next.js Integration:** Utilizes the Link component from next/link to create efficient client-side navigation.
- **CSS Styling:** Uses CSS classes for styling the navigation bar and its components.
- **Event Handling:** Uses JavaScript events like onMouseEnter and onMouseLeave to manage hover effects and toggle the dropdown menu.

## Usage

1. **Installation:**
   - Clone the repository: `git clone https://github.com/AroshaRavishan/Navbar-Responsive-React-Next.git`
   - Install dependencies: `npm install`

2. **Integration:**
   - Import the `Navbar` component into your project.
   - Customize navigation links and dropdown items as needed.

3. **Example:**

   ```jsx
   import Navbar from './path/to/Navbar';

   function App() {
       return (
           <div className="App">
               <Navbar />
               {/* Your other components */}
           </div>
       );
   }

   export default App;
