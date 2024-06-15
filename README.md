# Textags

## Overview

The **Textags** is a web application designed to create customizable text tags (also referred to as "pills" or "boxes") that can be styled in various ways. Users can add, modify, and visualize these text tags with different style options before saving them as an image.

## Visit Textag

Use Textags, click here: [Visit Textags](#)


## Features

### Style Options
- **Shape**: Users can choose the shape of the tags from three options:
  - Rounded
  - Rectangular
  - Curved
- **Size**: Users can select the size of the tags:
  - Small
  - Medium
  - Large
- **Text Style**: Users can customize the text within the tags:
  - Font weight: Normal, Semi-Bold, Bold
  - Italic
  - Underline

### Text Management
- **Add Texts**: Users can add multiple text entries, which will appear as a list. Each entry can be deleted individually.
- **Generate tags**: Once the texts are added, users can generate the tags with the selected styles and sizes.
- **Save as Image**: The generated tags can be saved as a PNG image.

## HTML Structure

The HTML file sets up the basic structure of the application using Bootstrap for styling and layout. It includes the following components:
- **Head**: Contains metadata, title, and links to Bootstrap CSS, Bootstrap Icons, and custom CSS.
- **Body**: Contains the main content organized within a Bootstrap container. Key sections include:
  - **Title**: Displays the application's name.
  - **Style, Size, and Text Options**: Radio buttons and checkboxes for customizing the appearance of the tags.
  - **Add Texts**: An input field for adding text entries, displayed as a list.
  - **tags**: A display area for the generated tags.
  - **Buttons**: Generate and Save buttons to create tags and save them as an image.

## JavaScript Functionality

The JavaScript file handles the dynamic behavior of the application using jQuery. Key functions include:
- **Initialization**: Prepares the input field for adding texts and sets up initial HTML structure.
- **Adding/Removing Texts**: Functions to add and remove text entries from the list.
- **Generating tags**: Functions to generate the text tags based on selected styles and sizes.
- **Saving as Image**: Utilizes the html2canvas library to capture the tags display area and save it as a PNG file.

## Conclusion

The **Textags** provides a user-friendly interface for creating and customizing text tags, making it easy to generate styled text elements and save them as images. The combination of Bootstrap for styling and jQuery for dynamic interactions results in a smooth user experience.