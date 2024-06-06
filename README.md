# AI Image Generator

A simple AI Image Generator tool that converts text prompts into images using the OpenAI API. This project demonstrates how to integrate OpenAI's image generation capabilities with a frontend application built with HTML, CSS, and JavaScript.

## Features

- Converts user text prompts into AI-generated images.
- Allows users to select the number of images to generate.
- Provides download links for the generated images.

## Demo

![AI Image Generator Demo](images/demo.gif)

## Getting Started

### Prerequisites

- A modern web browser.
- An OpenAI API key. You can get one by signing up on the [OpenAI website](https://www.openai.com/).

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/ai-image-generator.git
    ```

2. Navigate to the project directory:
    ```bash
    cd ai-image-generator
    ```

3. Open `index.html` in your preferred browser to view the application.

### Usage

1. Enter a text prompt in the input field.
2. Select the number of images you want to generate.
3. Click the "Generate" button.
4. Wait for the images to be generated and displayed in the gallery.
5. Click the download icon to save an image to your device.

### Files

- `index.html`: The main HTML file.
- `style.css`: The CSS file for styling the application.
- `script.js`: The JavaScript file containing the logic for interacting with the OpenAI API and updating the UI.
- `images/loader.svg`: The loader image displayed while images are being generated.
- `images/download.svg`: The download icon for saving images.
- `images/demo.gif`: A demo gif showcasing the functionality of the tool.

### Configuration

Replace the placeholder API key in `script.js` with your actual OpenAI API key:
```javascript
const OPENAI_API_KEY = "YOUR-OPENAI-API-KEY-HERE";
