
# CODSOFT UI/UX

Welcome to the CODSOFT UI/UX project repository. This repository showcases a collection of UI/UX projects aimed at enhancing user experiences through intuitive and visually appealing designs.

## Table of Contents

- [Introduction](#introduction)
- [Projects](#projects)
  - [User Authentication App](#user-authentication-app)
  - [Food Delivery App](#food-delivery-app)
- [Project Structure](#project-structure)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The CODSOFT UI/UX repository contains various projects focused on developing user-friendly interfaces and experiences. Each project demonstrates a different aspect of UI/UX design, ranging from authentication flows to comprehensive application designs.

## Projects

### User Authentication App

This project demonstrates a seamless user authentication flow, including:
- Welcome Screen
- Sign Up (Email or Google)
- Log In (Email or Google)
- Password Management (Reset and Change)

### Food Delivery App

A comprehensive food delivery application that includes:
- Browsing and selecting food items
- Detailed item descriptions
- Order customization options
- Order summary and review
- Secure payment gateway integration
- Real-time order tracking

## Project Structure

Here is an overview of the project's structure:

```
CODSOFT-UI-UX/
├── Authentication/
│   ├── assets/
│   │   ├── Login.png
│   │   ├── Register.png
│   │   ├── SplashScreen.png
│   │   └── Wallpaper.png
│   ├── .DS_Store
│   ├── fonts/
│   │   ├── OpenSans-Bold.ttf
│   │   ├── OpenSans-Light.ttf
│   │   ├── OpenSans-Regular.ttf
│   │   └── OpenSans-Semibold.ttf
│   ├── .gitignore
│   ├── LICENSE
│   ├── pubspec.lock
│   ├── pubspec.yaml
│   ├── README.md
│   ├── screenshots/
│   │   ├── img1.png
│   │   ├── img2.png
│   │   ├── img3.png
│   │   ├── img4.png
│   │   ├── img5.png
│   │   └── img6.png
│   └── test/
│       ├── widget_test.dart
├── Food_Delivery_App/
│   ├── .vscode/
│   │   ├── settings.json
│   ├── assets/
│   │   ├── fonts/
│   │   │   ├── Poppins-Bold.ttf
│   │   │   ├── Poppins-Light.ttf
│   │   │   ├── Poppins-Medium.ttf
│   │   │   ├── Poppins-Regular.ttf
│   │   │   ├── Poppins-SemiBold.ttf
│   │   ├── images/
│   │   │   ├── bg.png
│   │   │   ├── delivery.png
│   │   │   ├── discount.png
│   │   │   ├── home.png
│   │   │   ├── logo.png
│   │   │   ├── offer.png
│   │   │   ├── profile.png
│   │   │   ├── search.png
│   │   │   ├── shopping-bag.png
│   │   │   ├── splash_bg.png
│   │   │   ├── star.png
│   ├── lib/
│   │   ├── main.dart
│   │   ├── models/
│   │   │   ├── category_model.dart
│   │   │   ├── food_model.dart
│   │   ├── pages/
│   │   │   ├── cart_page.dart
│   │   │   ├── details_page.dart
│   │   │   ├── home_page.dart
│   │   │   ├── login_page.dart
│   │   │   ├── profile_page.dart
│   │   │   ├── search_page.dart
│   │   │   ├── signup_page.dart
│   │   │   ├── splash_page.dart
│   │   ├── utils/
│   │   │   ├── constants.dart
│   │   │   ├── themes.dart
│   ├── test/
│   │   ├── widget_test.dart
│   ├── .gitignore
│   ├── LICENSE
│   ├── pubspec.lock
│   ├── pubspec.yaml
│   └── README.md
├── README.md
└── LICENSE
```

## Features

- **Responsive Design**: Ensures compatibility with various screen sizes and devices.
- **Interactive Elements**: Provides a rich set of UI components for better user engagement.
- **Modular Architecture**: Promotes reusability and maintainability of code.
- **Built-in Security**: Incorporates security best practices to safeguard user data.
- **Integration with GitHub Actions**: Automates workflows including testing, building, and deploying.

## Installation

To set up the project locally, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/raaichu121/CODSOFT-UI-UX.git
   cd CODSOFT-UI-UX
   ```

2. **Install Dependencies:**
   ```bash
   npm install
   ```

3. **Run the Project:**
   ```bash
   npm start
   ```

## Usage

After setting up the project, you can start developing new features or improving the existing ones. The project is structured to facilitate easy development and testing.

## Contributing

We welcome contributions from the community. To contribute:

1. **Fork the repository** and create your branch from `main`.
2. **Clone the forked repository** to your local machine.
3. **Commit your changes** with clear and concise messages.
4. **Push to the branch** and open a pull request.

Please make sure to update tests as appropriate.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
