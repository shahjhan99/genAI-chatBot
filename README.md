
### 📖 **README for GenAI-ChatBot**

# GenAI-ChatBot

This project is an **AI-powered chatbot** built using **Gradio** for the user interface and **Groq's LLaMA3 model** for generating responses. It securely retrieves the **API key** from **Google Colab's `userdata`** and includes features like structured responses with headings, a **Submit** button for user input, and a **Clear** button to reset the conversation.

## 🔧 **Requirements**

To set up and run this project, make sure you have the following dependencies installed:

```
gradio>=4.18.0
groq>=0.4.2
google-colab  # Only if you're running on Colab
```

Create a `requirements.txt` by saving the above lines to the file.

## 🚀 **Installation and Usage**

1.  Download the project files.

   [ https://github.com/shahjhan99/genAI-chatBot  ]

2. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the app:

   ```bash
   python app.py
   ```

   Alternatively, you can run it in **Google Colab** directly by uploading the notebook and running it there.

4. **Hugging Face Inference:**
   For Hugging Face deployment, you can push your model and UI directly to Hugging Face using their hosted inference pipelines.

## 🌐 **How it Works**

1. The chatbot uses **Groq's LLaMA3 model** for generating conversational responses.
2. The **Gradio** interface is used to accept user input and show responses from the model.
3. The chatbot is initialized securely using an API key stored in **Google Colab's `userdata`**.

## 💬 **Features**

* **Submit Button**: Sends user input to the chatbot for a response.
* **Clear Button**: Resets both the input and output areas for a fresh start.
* **Structured Responses**: The chatbot formats responses with headings where applicable for better readability.

## 💡 **Contributing**

Feel free to fork the repository, make improvements, and submit pull requests. Contributions are welcome!

## 📧 **Contact**

* Developer: **M. Shahjhan Gondal**
* Email: [shahjhangondal99@gmail.com](mailto:shahjhangondal99@gmail.com)

## 📄 **License**

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


