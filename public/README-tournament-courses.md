# Tournament Courses Section

This is a modern, responsive design for showcasing tournament golf courses. The design includes three different implementation options for easy integration into any project.

## Files Created

1. **`tournament-courses.html`** - Complete standalone HTML page
2. **`css/tournament-courses.css`** - Standalone CSS component
3. **`components/tournament-courses-section.html`** - Reusable HTML component

## Features

- ✨ Modern, clean design with beautiful typography
- 📱 Fully responsive (mobile, tablet, desktop)
- 🎨 Smooth hover animations and transitions
- 🖼️ High-quality placeholder images from Unsplash
- 📊 Statistical highlights for each course
- 🎯 Call-to-action section
- 🔧 Easy customization and integration

## Usage Options

### Option 1: Standalone Page
Use `tournament-courses.html` as a complete page. Just open it in a browser or serve it directly.

### Option 2: Component Integration
For Laravel or other web frameworks:

1. Include the CSS file in your layout:
```html
<link rel="stylesheet" href="/css/tournament-courses.css">
```

2. Include the Google Fonts (recommended):
```html
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

3. Include the component HTML in your view:
```html
<!-- Include the content from components/tournament-courses-section.html -->
```

### Option 3: Laravel Blade Template
Convert the component to a Laravel Blade template:

1. Copy `components/tournament-courses-section.html` to `resources/views/components/tournament-courses.blade.php`
2. Include the CSS in your main layout
3. Use in any Blade template:
```blade
@include('components.tournament-courses')
```

## Customization

### Colors
The design uses a modern color palette:
- Primary Blue: `#4299e1`
- Dark Text: `#1a202c`
- Light Text: `#718096`
- Background: `#f8fafb`

### Images
Replace the Unsplash URLs with your own golf course images:
- Recommended size: 2070x1380px or similar aspect ratio
- Format: JPG or WebP for best performance

### Content
Update the course information, statistics, and descriptions to match your specific golf courses.

### Layout
The layout uses CSS Grid and is fully customizable:
- Adjust `gap` values for spacing
- Modify `max-width` on `.container` for different layouts
- Change grid columns on `.course-content` for different arrangements

## Browser Support

- Chrome/Edge: Full support
- Firefox: Full support
- Safari: Full support (iOS 12+)
- IE11: Basic support (no backdrop-filter)

## Performance

- Optimized CSS with efficient selectors
- Minimal JavaScript required (none currently)
- Responsive images with proper sizing
- Modern CSS features with fallbacks

## Accessibility

- Semantic HTML structure
- Proper heading hierarchy
- Alt text for images
- Keyboard navigation support
- Screen reader friendly

## License

Feel free to modify and use in your projects.