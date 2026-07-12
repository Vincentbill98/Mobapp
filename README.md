# Android Layout Assignment - Profile UI

## 📋 Project Overview
Android app demonstrating **LinearLayout**, **FrameLayout**, and **RelativeLayout** with a professional profile UI.

## 📁 Project Structure
```
app/src/main/
├── res/layout/activity_main.xml        # Main layout file
├── res/drawable/                        # Custom drawable resources
│   ├── header_gradient.xml
│   ├── card_background.xml
│   ├── photo_circle_background.xml
│   ├── edittext_background.xml
│   └── button_gradient.xml
└── res/values/colors.xml               # Color definitions
```

## 🎯 Features
- **Header**: LinearLayout with 3 weighted elements (A, Icon, B)
- **Profile Card**: FrameLayout with name, photo placeholder, and label
- **Form**: LinearLayout with EditText and Submit button
- **Professional Design**: Gradients, shadows, and rounded corners

## 📱 Layout Preview
```
┌─────────────────────────────┐
│  [A]  [Icon]  [B]          │  ← Header (LinearLayout)
│─────────────────────────────│
│  ┌──────────────────────┐   │
│  │  Name                 │   │
│  │     [Photo]          │   │  ← Profile Card (FrameLayout)
│  │     Photo            │   │
│  └──────────────────────┘   │
│─────────────────────────────│
│  [Type your name]           │  ← Form (LinearLayout)
│  [Submit]                   │
└─────────────────────────────┘
```

## 🛠️ Layout Specifications
| Section | Layout | Purpose |
|---------|--------|---------|
| backgroundA | LinearLayout | Header with icons |
| backgroundB | FrameLayout | Profile card |
| backgroundC | LinearLayout | Input form |
| Root | RelativeLayout | 100px padding |

## 🚀 Quick Setup
1. Open project in Android Studio
2. Sync Gradle files
3. Run the app

## 📝 Key Elements
- `textViewA` - Left header text
- `imageViewTop` - Header icon
- `textViewB` - Right header text
- `textViewNameLabel` - Name label
- `imageViewPhoto` - Profile photo
- `editName` - Name input field
- `btnSubmit` - Submit button

## 🎨 Color Palette
- **Primary**: #FF6B6B (Red)
- **Secondary**: #FF8E53 (Orange)
- **Text**: #333333 (Dark)
- **Background**: #F5F7FA (Light gray)
- **White**: #FFFFFF

## 📚 Learning Outcomes
- ✅ LinearLayout (horizontal/vertical)
- ✅ FrameLayout (overlay layouts)
- ✅ Custom drawable resources
- ✅ Layout weights and positioning
- ✅ Material Design principles

## 🤝 Contributing
Fork → Create branch → Commit → Push → Pull Request

## 📄 License
Educational purpose - Layout Design Assignment

## 👨‍💻 Author
Your Name - Android Layout Assignment

---
