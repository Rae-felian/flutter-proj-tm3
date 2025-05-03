# Flutter Form Application

A Flutter project demonstrating form input functionality with validation and result display.

## Project Overview

This Flutter application demonstrates a form application with navigation functionality. It includes:

- Welcome page with circular image and navigation button
- Multi-field form with comprehensive validation
- Result page displaying all submitted data
- Social media integration in the footer

## Features

- **Welcome Page**: Landing page with introduction and navigation to form
- **Form Input Page**: Multiple input fields with validation including:
  - Text inputs (Name, NIM, Email)
  - Numeric inputs (Age, Phone) with validation
  - Text area inputs (Address, Message)
  - Input filtering for numeric fields
- **Result Page**: Display of all submitted form data in a structured format
- **Custom Components**: Consistent styling and reusable components
- **Input Validation**: Comprehensive form validation for all fields

## Project Structure

```
lib/
├── main.dart              # App entry point and routing
├── welcome_page.dart      # Welcome/landing page
├── form_input_page.dart   # Form input with validation
└── result_page.dart       # Results display page
```

## How to Run

1. Ensure Flutter is installed on your system
2. Clone this repository
3. Navigate to the project directory
4. Run `flutter pub get` to install dependencies
5. Run `flutter run` to start the application

## Form Fields

The application includes the following form fields with validation:

- **Name**: Text input (required)
- **NIM**: Numeric input, minimum 8 digits (required)
- **Age**: Numeric input, must be between 17-80 years (required)
- **Email**: Email format validation (required)
- **Phone**: Numeric input, 10-13 digits (required)
- **Address**: Multi-line text input, minimum 10 characters (required)
- **Message**: Multi-line text input (required)

## Key Features

### Input Validation
- Numeric fields only accept numbers
- Email format validation
- Age range validation (17-80)
- Minimum character requirements
- Required field validation

### UI Features
- Gradient backgrounds
- Shadow effects on cards and buttons
- Responsive design
- Social media icons
- Form submission with loading indicator

### Navigation
- Welcome → Form Input → Result
- Back navigation to home
- Close buttons for quick exit

## Color Theme

The application uses a blue water theme with:
- Primary: Blue (#1976D2)
- Accent: Light Blue (#BBDEFB)
- Background: Gradient from light blue shades

## Dependencies

```yaml
dependencies:
  flutter:
    sdk: flutter
