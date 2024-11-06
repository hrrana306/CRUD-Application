

# CRUD Functions Flutter App

This Flutter application is a basic CRUD (Create, Read, Update, Delete) demo. It allows users to input and manage personal details such as name, email, city, and phone number. This project is designed with a focus on simplicity and ease of use, and it’s deployed on Vercel for easy access.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Deployment](#deployment)
- [Technologies Used](#technologies-used)
- [Acknowledgments](#acknowledgments)

## Features

- **Create**: Add new user data with fields such as name, email, city, and phone number.
- **Read**: Retrieve and view user data by name.
- **Update**: Modify existing user data.
- **Delete**: Remove user data from the list.
- **Vercel Deployment**: Access the web version of the app hosted on Vercel.

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/flutter-crud-app.git
   cd flutter-crud-app
   ```

2. **Install Dependencies**
   Ensure you have Flutter installed and then run:
   ```bash
   flutter pub get
   ```

3. **Run the Application**
   ```bash
   flutter run
   ```

## Deployment

This application is deployed on Vercel. You can access it [here](https://your-vercel-deployment-link.vercel.app/).

### Steps for Deployment with Vercel

1. **Setup Vercel**:
   - Create a Vercel account if you haven't already and install the Vercel CLI using `npm`:
     ```bash
     npm install -g vercel
     ```
   - Log in to Vercel with:
     ```bash
     vercel login
     ```

2. **Deploy**:
   - Run the following command in the project directory to deploy:
     ```bash
     vercel --prod
     ```
   - Vercel will provide a link where your app is hosted once deployment is complete.

## Technologies Used

- **Flutter**: Frontend development framework
- **Vercel**: For deploying the web version of the Flutter app

## Acknowledgments

Special thanks to the Flutter and Vercel communities for their documentation and resources. This project utilizes Firebase for real-time data storage and state management and is deployed seamlessly through Vercel’s robust frontend hosting services.
