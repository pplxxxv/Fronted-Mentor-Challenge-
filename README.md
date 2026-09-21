# Frontend Mentor — Blog Preview Card

A simple and responsive **Blog Preview Card** project built with HTML and CSS based on a [Frontend Mentor](https://www.frontendmentor.io/) challenge.

## 📌 About the Project

This project contains a blog preview card with:

- Article illustration
- `Learning` category label
- Publication date
- Article title
- Description
- Author avatar and name
- Responsive layout for mobile devices

The card is centered on the page and includes a yellow background, black border, rounded corners, and a shadow effect.

## 🛠️ Technologies Used

- HTML5
- CSS3
- Flexbox
- CSS Media Queries
- SVG
- WebP

## 📂 Project Structure

```text
.
├── index.html
├── README.md
├── illustration-article.svg
├── image-avatar.webp
└── assets/
    └── images/
        └── favicon-32x32.png
```

## 🎨 Features

### Desktop

On larger screens, the card is displayed in the center of the page with a fixed relative width.

### Mobile

For screens smaller than `500px`, the card becomes wider to fit mobile devices:

```css
@media (max-width: 500px) {
  .card {
    width: 75%;
  }
}
```

## 🚀 Getting Started

1. Clone or download the repository.
2. Make sure all image files are located in the correct directories.
3. Open `index.html` in your browser.

No additional dependencies or build tools are required.

## 📱 Responsive Design

The project is designed to work on both desktop and mobile devices.

Responsive behavior is implemented using CSS media queries.

## 🎯 Frontend Mentor

This project was created as part of the following Frontend Mentor challenge:

[Blog Preview Card](https://www.frontendmentor.io/challenges/blog-preview-card-2Kj4yK8XnT)

## 👤 Author

**pplxvvvn**

- Frontend Mentor: https://www.frontendmentor.io/
