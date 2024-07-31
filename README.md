# Ella Hotel Assistant

Ella is a chatbot designed to help users find hotels in Nigeria. It provides detailed information about hotels based on user queries and preferences.

## Features

- **Responds to queries about hotels in Nigeria**
- **Provides hotel recommendations based on user budget and destination**
- **Includes sentiment analysis to adjust responses based on user sentiment**
- **Takes feedback to improve development**

All responses are based on information obtained through Google Maps and Gemini AI integration. Real-time information may not always be available due to limited access to hotel data.

## Requirements

- Python 3.x

### Required Python Packages:

- `google-generativeai`
- `textblob`
- `googlemaps`

## Installation

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/KhAyRaH01/ella-python-implementation.git
   cd ella-python-implementation
   ```

2. **Install the Required Packages:**

   Use the following command to install the necessary Python packages:

   ```bash
   pip install -r requirements.txt
   ```

3. **Obtain API Keys:**

   To use Ella, you will need to set up API keys for Google Generative AI and Google Maps. Follow the steps below to obtain these keys:

   - **Google Generative AI API Key**:
     - Visit the [Google Cloud Console](https://console.cloud.google.com/).
     - Create a new project or select an existing one.
     - Enable the Generative AI API in your project.
     - Go to the **APIs & Services** > **Credentials** page and create an API key.
     - Set the API key in your environment variables:

       ```bash
       export GOOGLE_API_KEY=your_api_key_here
       ```

   - **Google Maps API Key**:
     - Go to the [Google Cloud Console](https://console.cloud.google.com/).
     - Enable the **Google Maps JavaScript API** and **Google Places API**.
     - Go to the **Credentials** page and create an API key.
     - Set the API key in your environment variables:

       ```bash
       export GOOGLE_MAPS_API_KEY=your_api_key_here
       ```

4. **Run the Application:**

   Start the chatbot by running the main script:

   ```bash
   python ella.py
   ```

## Usage

- Interact with Ella to find hotels based on your preferences.
- Provide feedback to help improve the chatbot's responses.

## Contributing

Contributions are welcome! Please submit a pull request or open an issue for any changes or improvements.

