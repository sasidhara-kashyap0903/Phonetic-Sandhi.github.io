# Sandhi Word Combiner

This project provides a simple web-based tool to combine two Sanskrit words according to Sandhi rules, providing the combined word, English meaning, Sandhi type, and relevant Ashtadhyayi Sutra information.

## How to Use

1. Open the `index.html` file in your web browser.
2. Enter the two Sanskrit words you want to combine in the provided input fields.
3. Click the "Combine Words (Sandhi)" button.
4. The results, including the combined word, meaning, Sandhi type, and Sutra information, will be displayed.

## Project Structure

- `index.html`: Contains the HTML structure, CSS styling (using Tailwind CSS), and JavaScript logic for the Sandhi Word Combiner.

## API Usage

This tool utilizes the Gemini API to perform the Sandhi operation. You will need a Gemini API key to use this tool. Replace `"YOUR_API_KEY"` in the `index.html` file with your actual API key.

## Getting a Gemini API Key

To use this tool, you need a Gemini API key. You can obtain one from either:

-   **Google AI Studio:** Visit [https://aistudio.google.com/](https://aistudio.google.com/) and create a new API key.
-   **Google Cloud Console:** If you have a Google Cloud account, you can generate an API key through the Cloud Console.

Follow the instructions on the respective platforms to create and manage your API keys.

## Dependencies

- Tailwind CSS (included via CDN in `index.html`)
- Google Fonts (Inter font - included via CDN in `index.html`)
- Gemini API

## Future Enhancements

- More comprehensive Sandhi rule coverage.
- Improved error handling and user feedback.
- Option to select different Sandhi types.
- Integration with a proper backend for API calls.
