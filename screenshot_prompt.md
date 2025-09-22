Comprehensive Prompt: Create a React Mockup from a Screenshot

Role & Goal

You are an expert front-end developer specializing in React and modern UI/UX principles. Your goal is to analyze the provided screenshot and create a high-quality, pixel-perfect, and functional React component mockup based on its design. The final output should be clean, production-ready code that follows modern best practices.

Primary Task

Given the attached screenshot, perform the following steps:

Analyze the UI: Meticulously examine the layout, structure, color palette, typography, spacing, and individual UI elements (buttons, inputs, cards, icons, etc.) in the image.

Deconstruct into Components: Logically break down the UI into a hierarchy of reusable React components. Identify a main parent component and the smaller, self-contained child components it will render.

Generate the Code: Write the corresponding JSX code for each component, applying the specified styling, interactivity, and data placeholders.

Technical Specifications

Framework: React

Language: JavaScript (ES6+)

Styling:

Primary Method: Use [Tailwind CSS] for all styling. Implement the design using utility classes directly in the JSX. Make sure the layout is responsive using Tailwind's breakpoint prefixes (e.g., md:, lg:).

Alternative Methods (if you change the primary): [CSS Modules, Styled-Components, Emotion]. If you choose one of these, generate the corresponding CSS/style files.

Component Structure:

Create a main parent component (e.g., UserProfileScreen, DashboardView).

Create separate child components for reusable elements (e.g., Button, StatCard, SideNavigation, Header).

Use functional components with React Hooks (useState, useEffect).

Icons: Use a popular icon library like [Heroicons or react-icons]. Analyze the icons in the screenshot and select the closest matching icons from the library. Do not use SVG code directly unless absolutely necessary.

Content & Data

Text: All text content from the screenshot should be included as-is.

Images: For user avatars, product images, or other dynamic images, use a placeholder service like https://picsum.photos/ for random images or https://via.placeholder.com/ for dimension-specific placeholders. Ensure you use appropriate dimensions that match the screenshot.

Dynamic Data: For lists, tables, or repeated elements, create a mock data array (e.g., an array of user objects) and map over it to render the components. This demonstrates how the component would work with real data.

Interactivity & State

Buttons & Links: All buttons, links, and clickable elements should be implemented with placeholder onClick handlers or href="#". For example: onClick={() => console.log('Button clicked!')}.

Form Elements: Inputs, text areas, checkboxes, and toggles should be controlled components using the useState hook to manage their state.

Stateful UI: If the UI suggests state changes (e.g., an active tab, a selected item, a dropdown menu), implement the necessary useState logic to manage that state.

Code Quality & Best Practices

Readability: Write clean, well-formatted, and commented code where necessary.

Props: Use propTypes or TypeScript interfaces (if specified) for component props to ensure type safety and clarity. For this task, propTypes is sufficient.

Accessibility (A11y): Use semantic HTML5 tags (<nav>, <main>, <button>, etc.). Add alt attributes to all images and use aria-label for icon-only buttons where appropriate.

File Naming: Use PascalCase for component file names (e.g., UserProfile.jsx).

Output Format

Please provide your response in the following structured format:

Component Analysis: Briefly describe the component hierarchy you've identified (e.g., "The UI consists of a Dashboard parent component which renders a Header, Sidebar, and a ContentGrid containing multiple InfoCard components.").

Dependencies: List the npm or yarn packages required to run this code (e.g., react, tailwindcss, heroicons).

Code Blocks: Provide the complete code for each component in a separate, clearly labeled markdown code block. Start with the child components and end with the main parent component.

Example Structure:

JavaScript
// FILE: src/components/Button.jsx
// ... code for Button component
JavaScript
// FILE: src/components/InfoCard.jsx
// ... code for InfoCard component
JavaScript
// FILE: src/screens/Dashboard.jsx
// ... code for the main Dashboard component
