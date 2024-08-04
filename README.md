# VTS LLM ChatBot 🤖

The **VTS LLM Chatbot** is a advanced interactive application that harnesses the power of Google Generative AI and Streamlit to offer engaging and versatile conversations. Designed to handle multimodal inputs and outputs, this chatbot provides users with a dynamic experience, supporting text and image interactions, and features customizable responses and robust language support.

## 🚀 Key Features

- **Real-time Chat:** Engage with AI by typing questions or prompts and receive immediate responses.
- **Image Upload:** Analyze and generate information based on uploaded images.
- **Multilingual Support:** Interact in 10 Indian languages and 7 foreign languages.
- **Response Translation:** Receive responses in the selected language, with optional transliteration.
- **Customizable Model Parameters:** Adjust response generation with parameters such as temperature, maximum output tokens, top-p, and top-k.
- **Safety Settings:** Configure content moderation to manage responses based on safety categories.
- **Audio Features:** Download responses as text or MP3 files, and listen to them with integrated text-to-speech.
- **Response Management:** Save responses as text files, copy text to clipboard, and view chat history.
- **Clear Chat History:** Reset chat sessions to start fresh with cleared history.

## 📷 Chatbot Interface
**User Input & Customization**

![1](https://github.com/user-attachments/assets/f48aff5b-9de7-4df5-9757-538f3d426553)

**Generated Response**

![2](https://github.com/user-attachments/assets/bc6fa76f-e6ec-4a32-9770-269f18f976e4)
![3](https://github.com/user-attachments/assets/c7f0b2ad-b55f-42a3-b61a-1a75606356c4)


## 🛠 Technical Specifications

- **Backend:** Google Generative AI API
- **Frontend:** Streamlit
- **Text-to-Speech:** Google Text-to-Speech (gTTS)
- **Image Processing:** PIL (Python Imaging Library)
- **Language Transliteration:** Google Translator Library
- **Environment Management:** Python `dotenv` for managing environment variables
- **Cloud Hosting:** Hosted on [Hugging Face](https://huggingface.co/spaces/AnkitKrishna/VTS-LLM-ChatBot)

## 📦 Getting Started

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/CodeWizardl/VTS-LLM-ChatBot.git
   cd VTS-LLM-ChatBot
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set Up Environment Variables:**
   Create a `.env` file in the root directory and add your environment variables:
   ```
   GOOGLE_API_KEY=your_google_api_key
   ```

4. **Run the Application:**
   ```bash
   streamlit run app.py
   ```

5. **Access the Application:**
   Open your browser and navigate to `http://localhost:8501` to start interacting with the chatbot.

## ⚙️ Challenges and Solutions

- **Content Moderation:** Implemented customizable safety settings to filter out harmful content effectively.
- **Multilingual Support:** Integrated comprehensive language selection and transliteration using the Indic Transliteration library.
- **User Experience:** Added features for downloading, copying, and audio playback to enhance accessibility and user interaction.

## 💰 Pricing

- **VTS LLM Chatbot:** Pricing varies based on API usage, storage, and processing needs. Custom pricing options are available based on specific requirements.
- **Other Chatbots:**
  - **ChatGPT:** Free tier available with limited usage; subscription plans offer enhanced features and higher limits.
  - **Gemini:** Offers both free and paid plans with different levels of access.
  - **Other Market Chatbots:** Pricing models vary widely, including free tiers, subscription plans, or pay-per-use options.

## 📚 Conclusion

The VTS LLM Chatbot represents a significant leap forward in AI-driven interactive applications. It combines advanced AI capabilities with an intuitive interface, providing a comprehensive suite of features for a rich and interactive chatbot experience. This project lays the groundwork for future enhancements and scalability, aiming to deliver an exceptional user experience.

## 📄 License

This project is licensed under the [MIT License](LICENSE).
