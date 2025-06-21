# Modern Image Gallery

A responsive and interactive image gallery built with HTML, CSS, and JavaScript.

## Features

- Responsive grid layout that adapts to different screen sizes
- Image filtering by categories (Nature, City, People)
- Lightbox view for full-screen image display
- Smooth hover effects and transitions
- Keyboard navigation support
- Touch-friendly interface

## Usage

1. Open `index.html` in your web browser
2. Click on any image to open it in the lightbox view
3. Use the filter buttons to sort images by category
4. Navigate through images in lightbox view using:
   - Arrow buttons on screen
   - Left/Right arrow keys
   - Click outside the image to close
   - Press 'Escape' key to close

## Customization

### Adding New Images

To add new images to the gallery:

1. Add a new `div` with class `gallery-item` in the gallery section
2. Set the `data-category` attribute to match one of the existing categories
3. Add an `img` tag with your image source
4. Add the overlay div with the search icon

Example:
```html
<div class="gallery-item" data-category="nature">
    <img src="path/to/your/image.jpg" alt="Description">
    <div class="overlay">
        <i class="fas fa-search-plus"></i>
    </div>
</div>
```

### Adding New Categories

To add a new category:

1. Add a new filter button in the filters section
2. Set the `data-filter` attribute to match your new category name
3. Add images with the corresponding `data-category` attribute

## Browser Support

The gallery works in all modern browsers that support:
- CSS Grid
- CSS Flexbox
- CSS Transitions
- ES6 JavaScript

## Credits

- Images from [Unsplash](https://unsplash.com)
- Icons from [Font Awesome](https://fontawesome.com) 