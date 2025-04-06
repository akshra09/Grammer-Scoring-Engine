
# 🗣️ Grammar Scoring Engine (Multilingual)

This is a voice-based grammar scoring engine that:
- Transcribes spoken audio using OpenAI's Whisper
- Scores the grammar using LanguageTool
- Provides suggestions for improvements
- Visualizes your score history

## 🚀 How It Works

1. Record or upload a voice file 🎤
2. Transcription is done using **Whisper**
3. Grammar is checked using **LanguageTool**
4. Score is calculated (0 to 10)
5. Feedback + grammar chart is shown

✅ You can **use your actual microphone** when launching the **live Gradio link** — it allows real-time testing.

---

## 📂 Dataset for Testing (Optional)

You can also test this engine using a Kaggle-hosted dataset like:

🔗[Speech Emotion Recognition Voice Dataset](https://www.kaggle.com/datasets/tapakah68/emotions-on-audio-dataset)

To load it on Colab:

```python
!kaggle datasets download tapakah68/emotions-on-audio-dataset
!unzip emotions-on-audio-dataset.zip

```
# 📦 Setup

Install the dependencies:

```python 
pip install -r requirements.txt

```
Launch on Google Colab with GPU enabled.




## Demo

![Screenshot 2025-04-06 231452](https://github.com/user-attachments/assets/c4ddd878-4dd5-408b-a365-b667b8ad7113)

# Video Demo 
![a1c30e37-a60d-489d-ae2f-ce7864314461](https://github.com/user-attachments/assets/33861ee2-8941-4de8-bf1f-9db07010b852)

# 🌐 Try It Live
Once deployed using Gradio with share=True, you'll get a public link that will run it on the Gradio itself.

This allows you to:

- Record your voice live via mic
- Test in real-time
- Share with others!

