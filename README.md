## 📄 Project Tagline
*I Fed My CV to an LLM, and It Answered Questions About Me!*

## 💡 Project Description
  - This project demonstrates how to build a Retrieval-Augmented Generation (RAG) Agent using LangGraph.
The RAG agent can read and understand any PDF documents, in this case, my CV, and it answer questions related to its content.

  - You can also feed any PDF into this system and query it using just a few lines of code provided in this repository.

## 📽️ Video (Outputs):
https://github.com/user-attachments/assets/184b041f-ab23-4241-9f79-f2ad9007f100

## 🖼️ Screenshots (Outputs):
<img width="1225" height="236" alt="Screenshot 2025-10-18 at 3 59 49 PM" src="https://github.com/user-attachments/assets/195a18ae-54da-4d6f-8bdf-8bbd232cdcbd" />
<img width="1225" height="147" alt="Screenshot 2025-10-18 at 5 02 28 PM" src="https://github.com/user-attachments/assets/fe373ef3-de81-4bee-bce3-41e73e1dce5a" />
<img width="1225" height="319" alt="Screenshot 2025-10-18 at 4 00 48 PM" src="https://github.com/user-attachments/assets/130e9425-5e35-4b80-bb17-0edb37e74b9a" />

*Please feel free to cross-check my CV with the outputs that LLM provides above. Here is the CV* -> 
  - Name: A_Flutter_Developer_cv_Tarikul_Islam.pdf
  - Link: https://github.com/Tarikul-Tuhin/A-Rag-Agent-that-answers-any-questions-related-to-my-CV-LangGraph-/blob/main/A_Flutter_Developer_cv_Tarikul_Islam.pdf

## 🧩 Steps that I followed to make this RAG Agent
  - Load my LLM
  - Load my CV.pdf (A_Flutter_Developer_cv_Tarikul_Islam.pdf) using pypdfloader
  - Split my CV into different chunks to reduce token size
  - Embedded the splitted chunks for vector representation (Using GoogleGenerativeAIEmbeddings)
  - Store the Embedded part into Chroma Database
  - Retrieve the relevant context from the Chroma Database when user asks any question and LLM answers the relevant context

## 🧠 Tech Stack
  - LangGraph – For workflow orchestration
  - Gemini (Google Generative AI) – As the LLM
  - PyPDFLoader – To load and extract text from PDFs
  - ChromaDB – For vector storage and retrieval
  - GoogleGenerativeAIEmbeddings – To create text embeddings

## 🧑‍💻 Author
Tarikul Islam<br>
Contact me on LinkedIn -> https://www.linkedin.com/in/tarikul-islam-a2785118a
