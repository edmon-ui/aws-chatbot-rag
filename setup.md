# 🛠️ How I Built This Project (AWS Chatbot with RAG)

This file documents the steps I took to build a chatbot using Amazon Lex, Bedrock, and S3 with Retrieval-Augmented Generation (RAG). I followed a YouTube tutorial and adjusted the process to work with currently available models and regions.

---

## 1. 📂 Set Up Amazon S3

- Created a bucket in **us-east-1 (N. Virginia)**
- Uploaded 4 PDF documents related to fictional Mars travel policies

---

## 2. 🧠 Enabled Amazon Bedrock

- Region: **us-east-1 (N. Virginia)** to support Lex
- Requested access to:
  - **Titan Embeddings G1**
  - **Claude 3 Haiku**
- Waited for access approval before proceeding

---

## 3. 📚 Created Knowledge Base

- Selected **“Knowledge Base with Vector Store”**
- Used **Titan Embeddings G1 – Text V1.2** as the embedding model
- Connected to my S3 bucket
- Synced documents successfully

---

## 4. 🤖 Built Amazon Lex Bot

- Created a bot directly in Lex using the Bedrock Knowledge Base (no Lambda)
- Set up intents and fallback to trigger Claude via the KB
- Tested responses using sample questions

---

## 5. ✅ Wrap-Up

- Made sure all services were in **N. Virginia**
- Verified everything worked
- Deleted all AWS resources after testing to avoid charges

---

> This was a hands-on learning project based on a YouTube tutorial, adapted to current AWS service availability.
