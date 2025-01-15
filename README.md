# Traveling Website

Welcome to the Traveling Website! This project showcases a parallax-based responsive travel-themed website, ideal for exploring and discovering new destinations.

## Features

- **Parallax Scrolling Effect**: Smooth transitions between sections with beautiful background images.
- **Responsive Design**: Optimized for both desktop and mobile viewing.
- **Interactive Navigation**: Easy-to-use navigation buttons.
- **Customizable Content**: Flexible sections for destinations, tips, and travel highlights.

## Demo

<a href="file:///Users/mehedihasan/4th%20semester/Web%20Development/Traveling%20Website/index.html">Live Demo </a>  
link: 
```
file:///Users/mehedihasan/4th%20semester/Web%20Development/Traveling%20Website/index.html
```

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/traveling-website.git
   ```
2. Navigate to the project directory:
   ```bash
   cd traveling-website
   ```
3. Open `index.html` in your browser to view the website.

## Folder Structure

```
traveling-website/
|-- index.html       # Main HTML file
|-- style.css        # Main CSS file
|-- /images          # Folder for background images
```

## Technologies Used

- HTML5
- CSS3

## Customization

1. **Background Images**:
   Replace the images in the `/images` folder and update their references in the CSS:
   ```css
   .pimg1 {
       background-image: url('images/image1.png');
   }
   ```

2. **Text and Links**:
   Update the content directly in the `index.html` file.

## Responsive Design

This website uses CSS media queries to ensure it looks great on devices of all sizes. Modify the styles in the `<style>` tag for specific screen sizes if needed.

```css
@media (max-width: 768px) {
    .ptext {
        font-size: 1.8rem;
    }
    .nav-buttons {
        flex-direction: column;
    }
}
```

## Contributing

Contributions are welcome! If you find any issues or want to improve this project:

1. Fork the repository.
2. Create a new branch.
3. Make your changes and submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

---

Happy Traveling! 🌍
