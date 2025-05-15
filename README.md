# milestone-project1

Milestone Project 1 based on Camley Street Natural Park

# Camley Street Natural Park

Welcome to the **Camley Street Natural Park** project! This is a milestone project showcasing a website for a natural park, designed to provide information about the park, its events, and opportunities for visitors to engage with nature.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Setup Instructions](#setup-instructions)
- [Testing](#testing)
- [Credits](#credits)
- [License](#license)

---

## Project Overview

The **Camley Street Natural Park** website is a single-page application designed to:

- Provide visitors with information about the park's opening times, events, and volunteering opportunities.
- Be clear, simple and easy to use and read for the visually impaired, yet hopefully remain elegant.
- Showcase a gallery of images highlighting the qualities and feel of the park.
- Allow users to subscribe to a newsletter for updates.
- Include social media links for further engagement.


---

## Features

### 1. **Navigation Bar**

- A responsive navigation bar with links to different sections of the page.
- Includes a "Camley Street" brand link that scrolls to the top of the page.

### 2. **About Section**

- Uses a satellite image to place the park in context of its surrounding area.
- A brief description of the park and a link to an article that delves more deeply into its history.

### 3. **Gallery Section**

- A collection of images showcasing the park's natural qualities, taken by myself.
- Images are responsive and adapt to different screen sizes.

### 3. **Events Section**

- Provides details about the park's opening times, school nature trails, and volunteering opportunities.

### 4. **Subscribe Section**

- A subscription form with input fields for Name, Email, and Phone.
- Includes a "Join Us" button.

### 5. **Footer**

- Social media links with icons for Facebook, Twitter, Instagram, and LinkedIn.
- Includes a favicon for branding.

---

## Technologies Used

- **HTML5**: For structuring the content.
- **CSS3**: For further styling.
- **Bootstrap 5**: For responsive design and prebuilt components.
- **Font Awesome**: For social media icons.
- **Google Fonts**: For custom typography.
- **QGIS**: For download from Google Satellite.
- **TinyPNG**: For image optimisation

---

## Testing

### Manual Testing

- Verified responsiveness on different screen sizes (mobile, tablet, desktop).
- Tested all navigation links to ensure they scroll to the correct sections.
- Checked the subscription form for validation:
  - Ensured the "Name" and "Email" fields are required.
  - Verified that the "Email" field only accepts valid email addresses.
- Tested social media links to ensure they open in a new tab and direct to the correct platforms.
- Used W3C Validator to check for and correct html syntax.

### Browser Compatibility

- Tested the website on the following browsers:
  - Google Chrome
  - Mozilla Firefox
  - Safari

### Accessibility

- Verified that the website is accessible for visually impaired users:

  - Used semantic HTML for better screen reader support.
  - Ensured sufficient color contrast for text and background.
  - Used a WAVE Google Chrome extension to check for accessibility and noted low contrast was flagged regarding the 'Join Us' button text.
  - Tested keyboard navigation to ensure all interactive elements are accessible.
  - Added aria-labels to Navigation Bar, Social Media links and Subscribe button.

  ### Lighthouse Results

The website was tested using Google Chrome Lighthouse, and the following scores were achieved:

| Category           | Score |
| ------------------ | ----- |
| **Performance**    | 68    |
| **Accessibility**  | 91    |
| **Best Practices** | 79    |
| **SEO**            | 91    |

While the Accessibilty and SEO scores are good, Performance could be improved as this is likely to impact loading times and potentially frustrate users.

There are various ways this could be achieved such as further optimisation of images with tools like TinyPNG (images are already saved as .webp). Minify CSS files with tools like CSSNano; Enable caching by adding caching headers to the configuration to reduce load times for returning visitors; Lazy Load images to defer loading images until they are visible in the viewport; use a content Delivery Network (CDN) to reduce latency.

---

## Credits

- I would like to acknowledge the invaluable help of my mentor, Victor Miclovich, for his guidance and assistance.
- Invaluable too is the Code Institute coursework that has led up to this milestone project.
- Perplexity.ai has been a very useful resource for researching and asking project related questions and helping my understanding.
- Visual Studio Code co-pilot has been a very useful tool for helping me correct and structure syntax.

### Content

- Information about Camley Street Natural Park was inspired by [London Wildlife Trust](https://www.wildlondon.org.uk/) and past visits to the site.

### Images

- All images used in the gallery were taken by myself.

### Tools and Libraries

- [Bootstrap 5](https://getbootstrap.com/) for responsive design.
- [Font Awesome](https://fontawesome.com/) for social media icons.
- [Google Fonts](https://fonts.google.com/) for typography.
- [QGIS](https://qgis.org/) for downloading satellite imagery.

### Acknowledgements

- Special thanks to Code Institute for providing guidance and inspiration for this project.

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/GavinKingcome/milestone-project1.git
   ```
2. Navigate to the project directory:
   ```bash
   cd milestone-project1
   ```
3. Open `index.html` in your browser to view locally.

---

## Deployment

This project was deployed using **GitHub Pages**:

1. Pushed all project files to the GitHub repository:  
   [https://github.com/GavinKingcome/milestone-project1](https://github.com/GavinKingcome/milestone-project1)
2. In the repository, went to **Settings** > **Pages**.
3. Under **Source**, selected the `main` branch and `/ (root)` folder, then clicked **Save**.
4. After a few moments, GitHub provided a link to the live site:  
   [https://gavinkingcome.github.io/milestone-project1/](https://gavinkingcome.github.io/milestone-project1/)

Any changes pushed to the repository are automatically deployed to GitHub Pages.

---


