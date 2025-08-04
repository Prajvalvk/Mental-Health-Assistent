# Mental-Health-Assistent
🧠 What does it do?
It's a chatbot that talks to users about their feelings.

It can understand how someone feels (e.g., happy, sad, angry).

It responds with supportive messages based on detected emotions.

It supports text input and voice input.

It saves the chat history locally on the browser.

🖥️ How does it work?
User Interface (HTML + CSS):

Three views:

Home screen

Chat screen

History screen

Buttons for navigation and starting speech recognition.

Chat messages styled differently for user and bot.

JavaScript Functionality:

Sentiment Detection:

It uses a neural network (from brain.js) trained with example phrases (like "I'm happy", "I'm sad").

It checks for emotion keywords if the AI is unsure.

Speech Recognition:

Converts voice to text using the browser’s microphone.

Speech Synthesis:

The bot can speak its responses out loud.

Local Storage:

Saves chat messages so you can view them later under “View History.”

🔍 How emotions are detected:
Example training phrases are tagged (like “I’m anxious” → anxious).

Your message is converted into word frequency (e.g., how many times you used "happy", "sad", etc.).

The model compares it with the training examples and guesses your dominant emotion.

Then it gives a tailored response based on your mood.

✅ Summary:
It’s an emotion-aware chatbot built using plain HTML, CSS, and JavaScript.

Uses machine learning to understand emotions.

Works with speech and text.

No server needed—it runs fully in the browser.
