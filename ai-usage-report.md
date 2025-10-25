# AI Usage & Learning Report

This document details how AI tools, specifically a large language model (ChatGPT), were used in the development of my personal portfolio website for Assignment 1.

## 1. AI Tools Used

-   **Primary Tool**: ChatGPT (GPT-4)
-   **Use Cases**:
    -   Code Generation & Scaffolding
    -   Debugging & Problem Solving
    -   UX/UI & Design Ideation
    -   Documentation Assistance

## 2. Benefits & Challenges

### Benefits
-   **Accelerated Development**: The AI provided initial boilerplate code for HTML structure and a CSS theming system using custom properties, which saved significant setup time.
-   **Innovative Ideas**: I prompted the AI for modern and visually appealing theme ideas. It suggested concepts like "Neon Sunset" and "Arctic Night," complete with color palettes, which I then refined.
-   **Deeper Understanding**: When I encountered a bug with my theme switcher's `localStorage` logic, I asked the AI to explain the solution step-by-step. This helped me understand the concept better than just copying code.

### Challenges
-   **Overly Complex Suggestions**: Initially, the AI's JavaScript suggestions were more complex than necessary. I had to refine my prompts to ask for simpler, more readable vanilla JS solutions appropriate for this assignment.
-   **Generic Design**: The first few CSS layouts it produced were quite generic. It required specific prompting about using CSS Grid for the main layout and Flexbox for component alignment to get a more professional result.

## 3. Learning Outcomes

-   **CSS Theming**: I learned a highly effective method for creating multiple themes using CSS custom properties (`--var`) and a `data-theme` attribute on the body tag. This was a concept suggested and explained by the AI.
-   **JavaScript `localStorage`**: I gained practical experience using `localStorage` to persist user settings across sessions, a direct result of implementing the theme-saving feature.
-   **Responsible Modification**: This process taught me the importance of not just accepting AI-generated code blindly. I reviewed every line, ensuring I understood its purpose and adapted it to fit the project's specific needs and coding standards. For example, I modified the generated JavaScript to be more readable by adding comments and wrapping it in a `DOMContentLoaded` listener, which was my own contribution to ensure robustness.