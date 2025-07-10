# CSS Layout Assignment

A simple CSS layout project demonstrating fundamental web layout techniques using HTML and CSS.

## 🌐 Live Demo

Check out the live version here: ****

## 📋 Project Overview

This project showcases a multi-section layout with positioned elements, demonstrating various CSS properties including:
- Flexbox layout
- Absolute positioning
- Color schemes and backgrounds
- Responsive design principles

## 🎨 Layout Structure

The webpage consists of several distinct sections:

### Header Section
- **Red header bar** (70px height)
- Clean, minimalist design

### Main Content Area
- **Cream-colored background** (`rgb(247, 233, 215)`)
- Centered "Main Content" heading
- Contains the main layout container

### Container Section
- **Aquamarine background** with padding
- Houses the flexible content area

### Content Area
- **Cadet blue background** (300px height)
- Flexbox display for responsive layout
- Contains three positioned boxes:

#### Blue Box
- **Primary content area** (400px width, full height)
- Positioned on the left side

#### Yellow Box
- **80x80px yellow square**
- Absolutely positioned at top-left of content area (400px from left)

#### Green Box
- **80x80px yellow-green square**
- Absolutely positioned at bottom-right corner

## 🛠️ Technologies Used

- **HTML5** - Semantic markup structure
- **CSS3** - Styling and layout
  - Flexbox for main layout
  - Absolute positioning for overlay elements
  - Custom color schemes

## 📁 File Structure

```
css-assignment/
├── index.html          # Main HTML file
├── style.css           # CSS stylesheet
└── README.md          # Project documentation
```

## 🚀 Getting Started

### Prerequisites
- Any modern web browser
- Basic understanding of HTML/CSS (for modifications)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/jiyasaraf/css-assignment.git
   ```

2. Navigate to the project directory:
   ```bash
   cd css-assignment
   ```

3. Open `index.html` in your web browser:
   ```bash
   open index.html
   ```

## 🎯 Key Features

- **Responsive Layout**: Uses flexbox for adaptable content arrangement
- **Absolute Positioning**: Demonstrates precise element placement
- **Color Coordination**: Thoughtful color scheme across sections
- **Clean Structure**: Well-organized HTML and CSS code

## 🔧 Customization

Feel free to modify the colors, dimensions, or layout by editing the `style.css` file:

- **Colors**: Update background-color properties
- **Dimensions**: Modify width/height values
- **Positioning**: Adjust left/right/top/bottom values for boxes
- **Layout**: Change display properties or add new sections

## 📝 Code Highlights

### Flexbox Implementation
```css
.content {
    display: flex;
    position: relative;
}
```

### Absolute Positioning
```css
.yellow-box {
    position: absolute;
    left: 400px;
    top: 0;
}
```

## 🤝 Contributing

This is a learning project, but suggestions and improvements are welcome! Feel free to:
- Fork the repository
- Create a feature branch
- Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👤 Author

**Jiya Saraf**
- GitHub: [@jiyasaraf](https://github.com/jiyasaraf)
- Project Link: [https://github.com/jiyasaraf/css-assignment](https://github.com/jiyasaraf/css-assignment)

---

⭐ **Don't forget to star this repository if you found it helpful!**