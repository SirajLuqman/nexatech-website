# NexaTech Website

A four-page responsive website built with semantic HTML and vanilla CSS.

## Pages

- `index.html` — Landing page
- `services.html` — Services offered by NexaTech
- `about.html` — About NexaTech
- `contact.html` — Contact page with a front-end demonstration form

## Run Locally

1. Open the project folder in Visual Studio Code.
2. Install the **Live Server** extension if it is not already installed.
3. Right-click `index.html` and select **Open with Live Server**.

## Assignment Constraints

- No JavaScript.
- No CSS Grid; layouts use Flexbox.
- Roboto is imported from Google Fonts.
- Mobile navigation uses a checkbox and CSS selectors.
- All four pages share one external stylesheet: `css/style.css`.

## Responsive Image

The landing page hero uses `srcset` and `sizes` to let the browser select an appropriate image resource based on the rendered image size and viewport. CSS uses `object-fit: cover` to fit the image within its container.

The current image URLs require an internet connection. If the assignment requires offline access or local assets, replace the external URLs with images stored in the project folder.

## Contact Form Limitation

The contact form is a front-end demonstration only. It is not connected to a backend service, so submitting the form will not deliver messages to NexaTech.