# 🤖 AWS Chatbot with Lex + Bedrock RAG

A chatbot built using Amazon Lex and Amazon Bedrock with Retrieval-Augmented Generation (RAG). It answers questions based on documents stored in S3 using Claude 3 Haiku and Titan Embeddings.

---

## ⚙️ Tech Stack

- **Amazon Lex** – Chatbot interface
- **Amazon Bedrock**
  - **Claude 3 Haiku** – Large language model
  - **Titan Embeddings G1** – Vector embedding model for search
- **Amazon S3** – Stores PDF documents
- **Bedrock Knowledge Base** – Connects documents to the LLM for RAG

---

## 🧪 Example Questions

- What items can I expense?  
- Can I bring pets to Mars?  
- Is there travel insurance?

---

## 📝 Notes

- This was built for learning purposes by following [this YouTube tutorial](https://www.youtube.com/watch?v=4esqnMlMo8I)
- I used **Claude 3 Haiku** instead of Claude V2
- All services were deployed in **N. Virginia (us-east-1)** to support Lex
- IAM and model access errors were resolved during setup

---

## 👤 Author

Made by [edmon-ui](https://github.com/edmon-ui)
