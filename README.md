# NexaTech Website

A four-page responsive website built with semantic HTML and vanilla CSS.

## Pages

- `index.html` — landing page
- `services.html` — services
- `about.html` — about NexaTech
- `contact.html` — contact page with a front-end demo form

## Run locally

1. Open this folder in Visual Studio Code.
2. Install the **Live Server** extension if needed.
3. Right-click `index.html` and select **Open with Live Server**.

## Assignment constraints

- No JavaScript.
- No CSS Grid.
- Layouts use Flexbox.
- Roboto is imported from Google Fonts.
- Mobile navigation uses a checkbox and CSS selectors only.
- One external stylesheet is shared by all pages.

## Responsive image note

The landing page hero uses `srcset` and `sizes` so the browser can choose an image resource suitable for the rendered slot. CSS makes it fit its container with `object-fit: cover`. The current image URLs need an internet connection; replace them with local assets if required by your course.

## Contact form limitation

The contact form is a visual demonstration only. No server or JavaScript is configured to deliver messages.
