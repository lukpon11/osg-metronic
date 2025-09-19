# Metronic Admin Template - Light Theme Customization

This project contains a customized version of the Metronic admin template with light theme modifications.

## 🎨 Customizations Made

### Light Theme Implementation
- **Page Header**: Converted from dark theme to clean white background with subtle borders
- **Sidebar Menu**: Transformed to light gray theme with improved contrast
- **Card Elements**: Removed box-shadows and added gray borders with 8px border-radius for modern look

### Files Modified
- `theme/admin_1_material_design/index.html` - Updated to reference the light theme override and OSG logos
- `theme/assets/global/css/light-theme-override.css` - Custom CSS overrides for light theme
- `theme/assets/layouts/layout/img/osg_logo.svg` - OSG logo (primary)
- `theme/assets/layouts/layout/img/osg_logo2.svg` - OSG logo (secondary)

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone [repository-url]
   cd osg-metronic
   ```

2. **Open the demo**
   - Navigate to `theme/admin_1_material_design/index.html`
   - Open in your web browser to see the light theme in action

## 📁 Project Structure

```
osg-metronic/
├── theme/
│   ├── admin_1_material_design/
│   │   └── index.html              # Main demo page with light theme
│   ├── admin_1/                    # Original dark theme
│   ├── admin_1_rounded/            # Rounded theme variant
│   └── assets/                     # Shared assets and resources
│       ├── global/css/
│       │   └── light-theme-override.css  # Custom light theme styles
│       └── layouts/layout/img/
│           ├── osg_logo.svg        # OSG logo (primary)
│           └── osg_logo2.svg       # OSG logo (secondary)
├── _documentation/                 # Template documentation
├── _start/                        # Getting started files
└── README.md                      # This file
```

## 🎯 Key Features

- **Clean Light Design**: Modern, professional appearance
- **Responsive Layout**: Works on all device sizes
- **Maintainable Code**: Separate CSS override file for easy customization
- **Original Template Preserved**: All original functionality maintained

## 🛠️ Customization

The light theme is implemented through a separate CSS override file (`theme/assets/global/css/light-theme-override.css`), making it easy to:
- Modify colors and styling
- Add new customizations
- Revert to original theme if needed

## 📄 License

This project is based on the Metronic admin template. Please refer to the original template's license terms.

## 👨‍💻 Developer

Customized for client requirements with light theme implementation.

---

**Note**: This is a customized version of the Metronic admin template with light theme modifications. The original template structure and functionality have been preserved while implementing the requested design changes.