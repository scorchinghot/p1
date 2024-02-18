Project Name: NIKE Landing Page Project for Learning TailwindCSS

Description: This landing page project serves as a learning exercise for mastering TailwindCSS. It's designed to provide hands-on experience in using TailwindCSS to create clean UI/UX designs and ensure excellent responsiveness across various devices.

Tech Stack: TailwindCSS

Installation: For installation, please refer to the official TailwindCSS documentation guide for Vite: https://tailwindcss.com/docs/guides/vite

Project Structure: This project follows the structure of a Vite app, similar to React. The src folder is the main directory, containing main.jsx as the root file and app.jsx as the layout file. Components are used within the components folder to represent different parts of the webpage.

Usage: This project serves as a simple landing page example created using TailwindCSS.

Key Features: The landing page boasts a clean UI/UX design and exceptional responsiveness on various devices.

Lesson Learned: Through this project, gained valuable experience and proficiency in using TailwindCSS for styling and designing web pages.

Credits: Special thanks to JavaScript Mastery for their invaluable courses that provided hands-on experience with real-world projects. You can find their tutorials and more on their YouTube channel: https://youtube.com/@javascriptmastery?si=lxy1L3qu9xzbPKSv

Code Snippets:

// Using ReactDOM.createRoot to render the application
ReactDOM.createRoot(document.getElementById('root')).render(
  // Wrapping the App component with React.StrictMode for additional checks and warnings during development
  <React.StrictMode>
    <App />
  </React.StrictMode>,
);

/*
  <React.StrictMode> is a component provided by React that helps identify potential problems in an application by performing additional checks and warnings. 
  It is commonly used during development to catch and fix potential issues early.
  <App /> is the root component of the application, which will be rendered inside the strict mode wrapper.
*/

<div className='relative flex-1 flex justify-center items-center xl:min-h-screen max-xl:py-40 bg-primary bg-hero bg-cover bg-center'></div>

/*
  This snippet represents the Hero component, typically used at the top of a webpage. It contains a div with a variety of CSS classes applied to style it. 
  The className attribute assigns multiple classes to the div, allowing for flexible styling. 
  In this case, the div is set to flex layout, horizontally and vertically centered, and fills the available space. 
  The background image is set using the bg-primary bg-hero bg-cover bg-center classes, ensuring the image covers the entire div and is centered both horizontally and vertically.
*/

<div className='mt-16 grid lg:grid-cols-4 md:grid-cols-3 sm:grid-cols-2 grid-cols-1 sm:gap-6 gap-14'></div>

/*
  This snippet represents the PopularProducts component, which displays a grid of popular products. 
  The className attribute assigns multiple classes to a div to create a responsive grid layout. 
  The grid adjusts its number of columns based on the screen size, with 4 columns on large screens (lg), 
  3 columns on medium screens (md), 2 columns on small screens (sm), and 1 column on extra small screens. 
  The gap classes define the gap between grid items, adjusting it for different screen sizes.
*/

<div className='max-container'>
  <div className='flex justify-between items-start gap-20 flex-wrap max-lg:flex-col'></div>
</div>

/*
  Nested divs are used to create a responsive layout with columns. 
  The outer div has the class max-container, which likely sets the maximum width for its content. 
  Inside, another div is a flex-container with classes flex justify-between items-start gap-20 flex-wrap max-lg:flex-col. 
  This setup allows for flexible styling of columns. 
  The justify-between class evenly distributes items along the main axis with space between them. 
  The items-start class aligns items at the start of the cross axis. 
  The gap-20 class sets the gap between flex items. 
  The max-lg:flex-col class changes the flex direction to column layout on screens larger than large (lg) breakpoint.
*/

<div className='lg:max-w-[40%] w-full flex items-center max-sm:flex-col gap-5 p-2.5 sm:border sm:border-slate-gray rounded-full'>
  <input type='text' placeholder='subscribe@nike.com' className='input' />
  <div className='flex max-sm:justify-end items-center max-sm:w-full'>
    {/* Button Component */}
  </div>
</div>

/*
  This snippet demonstrates the styling of an input field and a button within a nested div structure. 
  The outer div has classes for layout (flex, items-center) and spacing (gap-5, p-2.5). 
  It also applies border styling for small screens (sm:border sm:border-slate-gray) and rounds the corners (rounded-full). 
  Inside, the input field has the class input, which likely applies specific styling defined in Tailwind CSS for input elements. 
  The inner div wraps the button component and adjusts its alignment and width based on screen size using Tailwind's responsive classes (max-sm:justify-end, max-sm:w-full).
*/
