# Simple Flashcard Plugin

The Simple Flashcard plugin for WordPress allows you to easily create and embed interactive flashcards on your website. This plugin is perfect for educational sites, tutorials, or any content that benefits from a Q&A format.

## Features

- **Interactive Flashcards**: Click to flip between the question and answer.
- **Customizable Colors**: Set colors for both the front and back of the flashcards.
- **Shortcode Support**: Easily embed flashcards using a simple shortcode.

## Installation

1. **Download the Plugin**:
   - Download the zip file containing the Simple Flashcard plugin from the provided URL or from your WordPress plugin repository.
   
2. **Upload and Activate**:
   - Go to your WordPress dashboard.
   - Navigate to `Plugins` > `Add New` > `Upload Plugin`.
   - Upload the zip file and click `Install Now`.
   - After the installation is complete, click `Activate` to activate the plugin on your WordPress site.

3. **Include Required Files**:
   - Ensure the plugin’s CSS and JavaScript files are being loaded. This should be handled automatically upon activation.

## Usage

To use the Simple Flashcard plugin, simply insert the shortcode into any post, page, or widget where you want a flashcard to appear:

```shortcode
[simple_flashcard question="Your Question Here" answer="Your Answer Here" front_color="#ffffff" back_color="#007bff"]
```

### Shortcode Parameters

You can customize each flashcard using the following parameters in the shortcode:

- **question**: The text that appears on the front of the flashcard.
- **answer**: The text that appears on the back of the flashcard.
- **front_color** (optional): The background color of the front of the flashcard. Default is `#ffffff` (white).
- **back_color** (optional): The background color of the back of the flashcard. Default is `#007bff` (blue).

## Customization

To further tailor the flashcards to fit the style and functionality of your site, you can modify the CSS and JavaScript files:

- **CSS Customization**: Edit the `flashcard-style.css` to adjust the dimensions, fonts, or other styling elements of the flashcards.
  - **Location**: `wp-content/plugins/simple-flashcard/flashcard-style.css`

- **JavaScript Behavior**: Modify the `flashcard-script.js` to change how the flashcards behave on interaction.
  - **Location**: `wp-content/plugins/simple-flashcard/flashcard-script.js`

## Support

Need help? If you encounter any issues or have questions regarding the Simple Flashcard plugin, you can:

- Visit our website for FAQs and troubleshooting tips: [https://charangudla.com/contact](https://charangudla.com/contact)
- Reach out for support via the WordPress plugin support forum where our team regularly monitors and responds to inquiries.
