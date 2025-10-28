# TechLearn - Vue.js Interactive Learning Platform

## 📚 Project Overview

TechLearn is an interactive web application built with Vue.js 3 that demonstrates modern JavaScript framework capabilities. The project features a dynamic learning platform where users can explore various technology topics through an engaging card-flipping interface.

## ✨ Features

### Core Functionality
- **Toggle Display**: Click on the card to toggle between showing the topic title and its detailed description
- **Navigation System**: Navigate through 8 different technology topics using Previous/Next buttons
- **Dynamic Images**: Each topic displays a relevant image from online resources
- **Progress Counter**: Shows current position (e.g., "3 / 8")
- **Keyboard Support**: Use arrow keys (← →) to navigate and Space/Enter to flip cards

### Technology Topics Covered
1. Vue.js Framework
2. React Development
3. Node.js Backend
4. Python Programming
5. Machine Learning
6. Web Development
7. Database Management
8. Cloud Computing

## 🎨 Design Features

- **Responsive Web Design (RWD)**: Fully responsive layout that adapts to:
  - Desktop (1024px+)
  - Tablet (768px-1023px)
  - Mobile (767px and below)
- **Modern UI**: Gradient backgrounds, smooth animations, and hover effects
- **Accessibility**: Keyboard navigation, focus indicators, and reduced motion support
- **Grid Layout**: CSS Grid for flexible, organized content structure

## 🚀 Live Demo

**[View Live Demo](https://mathieugb9.github.io/HTML-Project-Ilac-BarbierMathieu/BS-MAth/index.html)**

## 📁 Project Structure

```
BS-MAth/
├── index.html          # Main HTML file with Vue.js application
├── css/
│   └── style.css      # Complete responsive stylesheet
├── data/
│   └── data.js        # JavaScript data array with 8 topic objects
└── assets/
    └── images/        # Project images (used in previous version)
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Grid, Flexbox, and animations
- **Vue.js 3**: Progressive JavaScript framework (CDN)
- **JavaScript ES6**: Modern JavaScript features

## 💻 How It Works

### Vue.js Implementation

The application uses Vue.js 3 with the following key features:

1. **Data Management**:
   ```javascript
   data() {
       return {
           mainHeading: 'Explore Technology Topics',
           techTopics,  // Array from data.js
           isFlipped: false,
           index: 0
       }
   }
   ```

2. **Methods**:
   - `move(change)`: Handles navigation between topics
   - Validates index boundaries
   - Resets flip state on navigation

3. **Event Handling**:
   - Click events for card flipping
   - Button clicks for navigation
   - Keyboard event listeners

4. **Data Binding**:
   - `v-text`: For dynamic text content
   - `:src` and `:alt`: For dynamic image binding
   - `{{ }}`: For interpolation in counter

## 📖 Usage Instructions

1. **View Content**: By default, the card shows the topic title with an image
2. **Read Description**: Click anywhere on the card to flip and read the full description
3. **Navigate**: 
   - Click "Previous" (←) to go to the previous topic
   - Click "Next" (→) to go to the next topic
   - Use keyboard arrows for quick navigation
4. **Track Progress**: Check the counter to see which topic you're viewing

## 🎯 Project Requirements Met

✅ Single page `index.html` with Vue.js framework  
✅ Full CSS with RWD in separate `css` folder  
✅ Separate `data.js` file in `data` folder with array of objects  
✅ Each object has 3+ properties (title, description, image)  
✅ Vue CDN connection implemented  
✅ Vue app object with all required properties  
✅ Toggle functionality between title and description  
✅ Image display always visible  
✅ Next and Previous navigation buttons  
✅ GitHub repository with live demo link  
✅ Responsive design for all devices  

## 👨‍💻 Group Members

- Mathieu Barbier

## 📱 Responsive Breakpoints

- **Desktop**: 1024px and above (2-column grid layout)
- **Tablet**: 768px - 1023px (single column layout)
- **Mobile**: 767px and below (optimized spacing and typography)
- **Small Mobile**: 480px and below (stack buttons vertically)

## 🎨 Color Palette

- **Primary**: #667eea (Purple-blue)
- **Secondary**: #764ba2 (Deep purple)
- **Accent**: #f093fb (Light pink)
- **Success**: #4facfe (Blue)
- **Text Dark**: #2c3e50
- **Text Light**: #6c757d

## 📄 License

This project is created for educational purposes as part of the ILAC Web Development course.

## 🙏 Acknowledgments

- Vue.js Framework Documentation
- Wikipedia for technology logos
- ILAC College for project requirements and guidance
- Based on course example from: [vue.js-intro](https://github.com/anmarjarjees/vue.js-intro)

---

**Last Updated**: October 2025