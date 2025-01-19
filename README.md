
# CARE: Customer Assistance and Response Engine

## Overview

CARE (Customer Assistance and Response Engine) is an advanced AI-powered chatbot designed to provide efficient, empathetic, and domain-specific support across various industries, including:

- **Banking**
- **Healthcare**
- **E-commerce**
- **Telecommunications**

The chatbot leverages **Phi 3.5 Mini Instruct**, a compact, instruction-tuned language model, optimized for efficient fine-tuning and deployment. CARE aims to automate customer interactions, analyze sentiment, and escalate unresolved issues seamlessly.

---

## Features

- **Domain-Specific Responses**: Customized support for diverse industries like healthcare, banking, telecommunications, and e-commerce.
- **Sentiment Analysis**: Provides empathetic responses by analyzing user sentiment.
- **Efficient Performance**: Built using a compact model optimized for faster inference and lower memory requirements.
- **Extensible Framework**: Easily expandable to support additional industries or integrate with new systems.

---

## Execution Framework

The project employs the following workflow:

1. **Input**: User prompts specific to the industry (e.g., banking, healthcare).
2. **Processing**:
   - Sentiment analysis for empathetic responses.
   - Fine-tuned language model tailored for the respective domain.
3. **Output**: Generates accurate, domain-specific responses and escalates issues if needed.

**Phi 3.5 Mini Instruct** ensures:
- Instruction-tuned training for contextual understanding.
- Transformer architecture for balanced performance and efficiency.

---

## Datasets Used

CARE is trained on domain-specific datasets to enhance accuracy:

- **Banking**: [Consumer Complaints Dataset](https://www.kaggle.com/datasets/shashwatwork/consume-complaints-dataset-fo-nlp)
- **Healthcare**: [AI Medical Chatbot Dataset](https://huggingface.co/datasets/ruslanmv/ai-medical-chatbot?row=0)
- **Telecommunications**: [Telco LLM Chatbot Training Dataset](https://huggingface.co/datasets/bitext/Bitext-telco-llm-chatbot-training-dataset)
- **E-commerce**: [E-commerce FAQs](https://github.com/imsoumya18/E-commerce_FAQ/blob/main/Ecommerce_FAQs.csv)

Custom datasets were also utilized for enhanced domain adaptation.

---

## Methodology

- **Model Architecture**: Fine-tuning and QLoRA techniques were used to optimize **Phi 3.5 Mini Instruct**.
- **Training Pipeline**:
  - Data preprocessing: Addressed dataset skewness using oversampling and undersampling techniques.
  - Model merging: Combined fine-tuned domain-specific models into a unified framework.
- **Final Model**: [Phi-3.5-mini-instruct-Combined-Model](https://huggingface.co/ankitruler567/Phi-3.5-mini-instruct-Combined-Model)
- **Testing**: [Testing Notebook](https://www.kaggle.com/code/ankitd7752/testing-production-code-tensor-decomposition)

---

## Possible Improvements

Future enhancements for CARE could include:

1. **Multi-Language Support**: Expand capabilities to handle queries in multiple languages.
2. **Voice Integration**: Real-time voice-to-text and text-to-voice for improved accessibility.
3. **Reinforcement Learning with Human Feedback (RLHF)**: Continuously improve chatbot accuracy using RLHF and Retrieval-Augmented Generation (RAG).
4. **Knowledge Base Expansion**: Regularly update databases for better accuracy and relevance.
5. **API Deployment**: Make the chatbot available as an API to expand accessibility and impact.

---

## Conclusion

CARE represents a step forward in smart customer service, providing solutions tailored to diverse industries. By leveraging advanced NLP techniques and domain-specific training, CARE enhances customer satisfaction and streamlines issue resolution.

---

## Authors

- **Ankit Dutta**
- **Nabarup Ghosh**
- **Ankush Chatterjee**
- **Abhishek Das**

Special thanks to **Genpact** and **Kshitij** for providing the opportunity to develop this impactful project.

---

## License

This project is licensed under the AGPL-3.0 License. See the [LICENSE](https://github.com/ankitdutta428/smart-chatbot/blob/main/LICENSE) file for details.

---
