# Text Summarization with Seq2Seq Models (T5)

## **Overview**
This project demonstrates how to perform **Text Summarization** using a **Sequence-to-Sequence (Seq2Seq)** model, specifically the **T5 (Text-to-Text Transfer Transformer)** model from Hugging Face. T5 is a versatile NLP model trained to handle a wide variety of text-related tasks, including summarization.

---

## **How It Works**
1. **Input Text**:
   - Any given text (e.g., paragraphs or articles) is provided as input.
2. **Task Specification**:
   - The prefix **"summarize:"** is added to the input text to specify the summarization task to the T5 model.
3. **Model**:
   - A pre-trained **T5 model** is used to generate a concise summary from the input text.
4. **Output**:
   - The generated summary is returned as a shorter sequence of text, retaining the core information.

