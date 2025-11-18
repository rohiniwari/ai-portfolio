Personal Portfolio Webpage
https://rohini-ai-portfoli.netlify.app/

This repository contains the source code for a responsive personal portfolio webpage built using only HTML and CSS. The webpage meets specific requirements for structure and responsiveness across different device sizes.

📝 Requirements Met
Structure: Includes Header, Hero Section, Skills Section, and Footer.
Content: Features a logo/name, navigation links (Home, About, Skills, Contact), a headline, description, "Contact Me" button, a list of 6 skills, and social media links.
Responsiveness: Fully responsive on desktop, tablet, and mobile views, adhering to specified layout changes (navigation style, column counts for skills).

AI Tools: An AI website builder was used to generate an initial template.

Manual Edits: The AI-generated code was manually reviewed, fixed, and customized.

🤖 AI Tool Usage
The initial template for the index.html and style.css files was generated using v0.dev, a generative UI tool by Vercel and published by netlify.
The following prompt was used to generate the base code:
Create a personal portfolio website with these sections:
1. Header with my name and navigation links
2. Hero section with headline + description + contact button
3. Skills section with at least 6 skill boxes
4. Footer with social links
Make it responsive for desktop, tablet, and mobile.

🧑‍💻 Manual Edits & Customization
The AI-generated code provided a functional starting point, but required significant manual intervention to meet all specific requirements, improve code structure, and add custom styling.
Key manual edits and improvements include:
Hamburger Menu Implementation: The AI provided a simple stacked menu for mobile. This was replaced with a proper, functional hamburger menu using a checkbox hack for pure CSS functionality to hide/show navigation links on mobile devices.

Refining Responsiveness:
Explicitly defined @media queries in style.css for tablet (768px min-width) and desktop (1024px min-width) breakpoints to ensure the skills grid changes from 1-column (mobile) to 2-column (tablet) to 3-column (desktop) as required.
Ensured consistent padding and margin adjustments across breakpoints to prevent horizontal scrolling.

Styling and UX Enhancements:

Applied a unique color theme (dark background with accent colors).
Added subtle CSS-only animations and hover effects (e.g., button hover, skill card hover effect, link transitions) for a better user experience.
Adjusted font sizes, line heights, and element spacing for better visual hierarchy and readability.

Semantic HTML Structure: Verified and improved the use of semantic HTML5 tags (<header>, <main>, <section>, <footer>, <nav>, <article>) for better accessibility and SEO.

Content Replacement: Replaced all placeholder content with actual portfolio details and skill names.
