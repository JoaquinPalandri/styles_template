# Angular Styles Template

## 📌 Description
This project provides an **SCSS styles template** for Angular applications. It includes variables, mixins, and reusable styles to facilitate customization and maintainability.

## 🚀 Features
- **SCSS variables** for colors, typography, spacing, and shadows.
- **Reusable mixins** for alignments, shadows, and button sizes.
- **Modular styles** organized into separate files.

## 📁 Project Structure
```
📂 src/
 ├── 📄 _variables.scss   # Global variables
 ├── 📄 _mixins.scss      # Reusable mixins
 ├── 📄 styles.scss       # Main styles file
```

## 📦 Installation & Usage
1. Clone this repository:
   ```sh
   git clone https://github.com/your-username/angular-styles-template.git
   ```
2. Import the styles into your Angular project:
   ```scss
   @import 'path/to/directory/_variables';
   @import 'path/to/directory/_mixins';
   ```

## 🎨 Using Mixins
### 📌 Alignments
```scss
.element {
    @include align-center;
}
```

### 🏆 Shadows
```scss
.element {
    @include box-shadow("medium");
}
```

### 🔘 Buttons
```scss
.button-large {
    @include button-size(16px, 20px);
}
```

## 📜 License
This project is licensed under the MIT License. Feel free to use and improve it! 🚀

