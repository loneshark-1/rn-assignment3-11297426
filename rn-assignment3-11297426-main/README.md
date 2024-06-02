# rn-assignment3-11297426

# Task Manager App

This is a React Native application built with Expo CLI that allows users to manage their tasks across various categories. The app closely follows the provided UI design and includes custom components for categories and tasks.

## Components

### Header

The Header component displays the title "Task Manager" at the top of the app with a dark blue background and white text.

### CategoryCard

The CategoryCard component represents a single category card. It displays an icon and a title for the category. This component is used within the horizontal category list.

### TaskCard

The TaskCard component represents a single task card. It displays the task title and description within a white card with a drop shadow. This component is used within the task list.

### App

The App component is the main component that brings together all the other components. It includes the Header, a horizontal FlatList for rendering categories using CategoryCard, and a vertical FlatList for rendering tasks using TaskCard. The tasks and categories are defined as data arrays within the component.

## Screenshots


![Screenshot](assets/screenshot.jpg)

