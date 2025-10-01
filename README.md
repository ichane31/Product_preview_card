# Frontend Mentor - Product Preview Card Component

![Design preview for the Product preview card component coding challenge](./design/desktop-preview.jpg)

## The Challenge

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

### Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover and focus states for interactive elements
- View product details including image, title, description, and pricing
- See the discount price clearly displayed

## Screenshot

![Screenshot web](./images/screen_web.png)

![Screenshot mobile](./images/screen_mobile.png)

## Built With

- Semantic HTML5 markup
- CSS custom properties
- CSS Flexbox
- CSS Grid
- Mobile-first workflow
- Responsive design with media queries
- BEM methodology for CSS

## What I Learned

Through this project, I enhanced my skills in:

- Creating responsive layouts using CSS Grid and Flexbox
- Implementing CSS custom properties for maintainable theming
- Building accessible UI components with proper ARIA attributes
- Using the `<picture>` element for responsive images
- Implementing smooth transitions and hover effects
- Mobile-first responsive design approach

### Code Snippets

```html
<picture class="product__img">
  <source srcset="images/image-product-desktop.jpg" media="(min-width: 600px)">
  <img src="images/image-product-mobile.jpg" alt="Gabrielle Essense perfume bottle">
</picture>
```

```css
:root {
  --primary-color: hsl(158, 36%, 37%);
  --primary-dark: hsl(158, 36%, 20%);
  --cream: hsl(30, 38%, 92%);
  --dark-blue: hsl(212, 21%, 14%);
  --grayish-blue: hsl(228, 12%, 48%);
  --white: hsl(0, 0%, 100%);
}

.product {
  display: grid;
  max-width: 600px;
  border-radius: 10px;
  overflow: hidden;
  background: var(--white);
  margin: 1rem;
}
```

## Getting Started

### Prerequisites

- Web browser (Chrome, Firefox, Safari, etc.)
- Code editor (VS Code, Sublime Text, etc.)

### Installation

1. Clone the repository
   ```sh
   git clone https://github.com/your-username/product-preview-card-component.git
   ```
2. Open `index.html` in your browser

## Usage

Simply open the `index.html` file in your preferred web browser to view the product preview card.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Author

- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- GitHub - [@yourusername](https://github.com/yourusername)
- Twitter - [@yourtwitter](https://twitter.com/yourtwitter)

## Acknowledgments

- [Frontend Mentor](https://www.frontendmentor.io) for the challenge
- [Google Fonts](https://fonts.google.com/) for the typography
- [MDN Web Docs](https://developer.mozilla.org/) for documentation
