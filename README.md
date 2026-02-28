# stem-quiz-1q
Prompt 1: Planning Prompt (No Code)

Prompt sent to ChatGPT:

“Give me a step-by-step plan to implement responsive breakpoints for a portfolio website using only HTML and CSS. The plan should cover header layout, hero section behavior, and a responsive grid. Do not include any code — only layout and design guidance.”

Items Accepted from the Plan

I accepted the suggestion to define clear breakpoints for desktop, tablet, and mobile (desktop > 900px, tablet 601–900px, mobile ≤ 600px).

I accepted the recommendation to stack the hero section vertically on mobile while keeping a two-column layout on desktop.

Item Rejected from the Plan

I rejected the suggestion to use CSS frameworks or utility classes because the assignment explicitly required HTML and CSS only with no frameworks.

Prompt 2: Debug Prompt

Problem Description Sent to ChatGPT:

“My hero section is not stacking vertically on mobile screens even though I am using flexbox. The layout stays in two columns below 600px. Here is the CSS I am using for the hero section. What is wrong and how can I fix it?”

CSS Snippet Included in the Prompt:

.hero {
  display: flex;
  gap: 20px;
}
Key Part of ChatGPT’s Response

“When using flexbox, the layout will remain horizontal unless you explicitly change the flex-direction at a smaller breakpoint. You should add a media query that sets flex-direction: column for mobile screen sizes.”

What I Changed Afterward

I added a mobile media query that changes the hero section’s flex-direction to column at widths of 600px and below, which fixed the stacking issue.

Verification Checklist

Viewport Sizes Tested:

375px (mobile)

768px (tablet)

1200px (desktop)

What I Verified Visually:

Header navigation stacked and centered on mobile, aligned horizontally on desktop

Hero section stacked vertically on mobile and displayed in two columns on desktop

Grid layout displayed 1 column on mobile, 2 columns on tablet, and 4 columns on desktop

Hover styles worked on buttons and cards

Q4:
- Chart caption:
  This chart shows a positive relationship between study hours and exam scores.
  Based on this trend, I would encourage students to increase consistent study time to improve performance.

- Decision based on chart:
  Students who study fewer than five hours should prioritize structured study schedules to improve exam outcomes.
