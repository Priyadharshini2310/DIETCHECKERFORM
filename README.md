#  Diet Form Tracker

A comprehensive web-based diet tracking application designed to help users monitor their eating habits, health goals, and lifestyle choices. Built with modern HTML, CSS, and JavaScript for tracking fitness of the modern youngster.

## Features

### Core Functionality
- **Personal Information Tracking** - Age, gender, height, weight, activity level
- **Goal Setting** - Weight management, muscle gain, health improvement, stamina building
- **Dietary Preferences** - Vegetarian, vegan, keto, paleo, gluten-free options
- **Meal Tracking** - Breakfast, lunch, dinner, snacks, and beverages
- **Health History** - Medical conditions, medications, supplements, family history
- **Physical Activity Monitoring** - Exercise frequency, type, and duration
- **Sleep & Stress Analysis** - Sleep quality, stress levels, emotional eating patterns

### User Interface
- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Modern Styling** - Clean, professional interface with gradients and animations
- **Interactive Elements** - Hover effects, smooth transitions, and visual feedback
- **Accessibility** - Proper form labels, semantic HTML, and keyboard navigation

##  Design Highlights

### Visual Elements
- **Inspirational Quote** - Motivational header with custom typography
- **Diet Tips Gallery** - Beautiful image grid with hover effects and captions
- **Progress Indicators** - Visual progress bars for sleep and stress levels
- **Gradient Backgrounds** - Modern color schemes throughout the application
- **Card-Based Layout** - Clean, organized sections with proper spacing

### Styling Features
- **Curved Edges** - Rounded corners on images and containers (15-25px radius)
- **Glassmorphism Effects** - Translucent, blurred backgrounds for modern appeal
- **Smooth Animations** - CSS transitions and hover effects for better UX
- **Color-Coded Sections** - Different accent colors for easy visual distinction
- **Typography** - Consistent font hierarchy with proper spacing and readability

## Project Structure

```
diet-form-tracker/
├── index.html              # Main HTML file with form structure
├── dietform.css            # Core styling (external file)
├── images/
│   ├── diet_quotes.jpg     # Header inspiration image
│   ├── chose.png          # Diet tip: Choose local foods
│   ├── vegrule.png        # Diet tip: One third veg rule
│   ├── packaging.png      # Diet tip: Packaging awareness
│   ├── cereals.png        # Diet tip: Legumes and nuts
│   ├── brownrice.png      # Diet tip: Brown rice benefits
│   ├── lessmore.png       # Diet tip: Portion control
│   ├── nojunk.png         # Diet tip: Avoid junk food
│   ├── fats.png           # Diet tip: Healthy fats
│   └── exercise.jpeg      # Diet tip: Regular exercise
└── README.md              # Project documentation
```

##  Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Basic understanding of HTML/CSS for customization

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/diet-form-tracker.git
   ```

2. Navigate to the project directory:
   ```bash
   cd diet-form-tracker
   ```

3. Open `index.html` in your web browser:
   ```bash
   open index.html
   # or
   python -m http.server 8000  # For local server
   ```

### Quick Setup
1. Ensure all image files are in the correct paths
2. Verify CSS files are properly linked
3. Test form functionality across different browsers
4. Customize colors and styling as needed

##  Usage

### For Users
1. **Fill Personal Information** - Enter basic demographic and physical data
2. **Set Goals** - Select primary health and fitness objectives
3. **Configure Preferences** - Choose diet type and specify allergies
4. **Track Meals** - Log daily food intake and beverages
5. **Monitor Health** - Record medical history and current medications
6. **Log Activity** - Track exercise routines and sleep patterns
7. **Submit Data** - Save information for analysis and tracking

### For Developers
1. **Customize Forms** - Add new fields or modify existing ones
2. **Enhance Styling** - Use provided CSS classes for consistent design
3. **Add Functionality** - Implement JavaScript for form validation
4. **Integrate Backend** - Connect to database for data persistence
5. **Mobile Optimization** - Test and enhance mobile responsiveness

##  Customization

### Styling Options
```css
/* Basic customization */
.diet-images {
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 25px;
}

/* Color scheme modification */
.diet-image-card:nth-child(1) .diet-caption {
  border-bottom: 4px solid #your-color;
}
```

### Adding New Sections
```html
<fieldset>
  <legend><b>Your New Section</b></legend>
  <label for="new-field"><strong>Label:</strong></label>
  <input type="text" id="new-field" placeholder="Placeholder text"/>
</fieldset>
```

##  Responsive Design

The application is built with mobile-first approach:
- **Desktop** (1200px+): 4-column grid layout
- **Tablet** (768px-1199px): 2-3 column adaptive layout
- **Mobile** (up to 767px): Single column, touch-friendly interface

### Breakpoints
```css
@media (max-width: 768px) { /* Tablet styles */ }
@media (max-width: 480px) { /* Mobile styles */ }
```

##  Image Gallery Styles

Multiple layout options available:

### Standard Grid
```html
<div class="diet-images">
  <div class="diet-image-card">
    <img src="image.png" alt="Description">
    <div class="diet-caption">
      <h3>Image Title</h3>
    </div>
  </div>
</div>
```

### Glassmorphism Effect
```html
<div class="diet-images-glass">
  <!-- Same structure -->
</div>
```

### Overlay Captions
```html
<div class="diet-overlay-style">
  <div class="diet-overlay-card">
    <img src="image.png" alt="Description">
    <div class="overlay-caption">
      <h3>Image Title</h3>
    </div>
  </div>
</div>
```

##  Browser Support

| Browser | Version | Status |
|---------|---------|--------|
| Chrome | 70+ |  Full Support |
| Firefox | 65+ |  Full Support |
| Safari | 12+ |  Full Support |
| Edge | 79+ |  Full Support |
| IE | 11 |  Limited Support |

##  Form Data Structure

The form collects data in the following categories:
- Personal Information (name, age, gender, height, weight, activity level)
- Health Goals (weight management, muscle gain, health improvement)
- Dietary Preferences (diet type, allergies, restrictions)
- Meal Tracking (breakfast, lunch, dinner, snacks, beverages)
- Eating Habits (meal frequency, snacking, water intake)
- Health History (conditions, medications, supplements)
- Physical Activity (exercise frequency, type, duration)
- Sleep & Stress (sleep quality, stress levels, emotional eating)

##  Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Contribution Guidelines
- Follow existing code style and structure
- Add comments for complex functionality
- Test across multiple browsers
- Update documentation for new features
- Maintain responsive design principles

##  Todo List

- [ ] Add JavaScript form validation
- [ ] Implement local storage for data persistence
- [ ] Create data visualization charts
- [ ] Add export functionality (PDF/CSV)
- [ ] Integrate with fitness APIs
- [ ] Multi-language support
- [ ] Dark mode theme
- [ ] Progressive Web App features
- [ ] Accessibility improvements
- [ ] Advanced analytics dashboard

##  Known Issues

- Form submission currently has no backend integration
- Some images may need optimization for faster loading
- IE11 may have limited CSS support for advanced animations
- Mobile keyboards may obscure form fields in landscape mode

##  Future Enhancements

### Version 2.0 Features
- **Database Integration** - Store and retrieve user data
- **Progress Tracking** - Visual charts and trend analysis
- **Meal Planning** - AI-powered meal suggestions
- **Social Features** - Share progress with friends
- **Notifications** - Reminders for meals and exercise
- **Wearable Integration** - Sync with fitness trackers

##  License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

##  Author

**Priyadharshini VN**
- Developed for tracking fitness of the modern youngster
- Focus on clean design and user experience
- Committed to helping users achieve their health goals

##  Acknowledgments

- Inspiration from modern diet and fitness applications
- CSS animations and effects from contemporary web design trends
- Form structure based on comprehensive health assessment practices
- Image styling inspired by material design principles

##  Support

If you encounter any issues or have questions:
1. Check the [Issues](https://github.com/yourusername/diet-form-tracker/issues) section
2. Create a new issue with detailed description
3. Include browser version and operating system
4. Provide screenshots if applicable

---

**Made with ❤️ for healthier living**

*"Every healthy choice you make is a vote for the person you want to become."*