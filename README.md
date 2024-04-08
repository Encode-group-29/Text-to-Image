# Painting Description and Image Generation App

This is a web application built using Python, Streamlit, and the Hugging Face Transformers library. It allows users to generate detailed descriptions of paintings based on a provided theme or prompt, and then generate corresponding images using the Stability AI Inference API.

## Features

- **Painting Description Generation**: Users can input a painting theme or prompt, and the app will use a pre-trained language model from the Hugging Face Transformers library to generate a detailed textual description of a painting based on that theme.
- **Image Generation**: After receiving the painting description, users can choose to generate an image based on the textual description using the Stability AI Inference API.
- **Interactive User Interface**: The app provides a user-friendly interface powered by Streamlit, where users can input their desired painting theme, view the generated description, and initiate the image generation process.
- **Customizable Image Generation Parameters**: Users can customize various parameters for the image generation process, such as image dimensions, number of inference steps, and more.
- **Image Display**: The generated image is displayed on the web page once the generation process is complete.

## Technologies Used

- Python
- Streamlit (for building the web app)
- Hugging Face Transformers (for text generation)
- Stability AI Inference API (for image generation)

## Getting Started

1. Clone the repository: `git clone https://github.com/your-repo/painting-app.git`
2. Install the required Python packages: `pip install -r requirements.txt`
3. Set up your Stability AI API credentials in the appropriate configuration file.
4. Start the Streamlit app: `streamlit run app.py`
5. The app will open in your default web browser.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
