📄 Project Tagline
“I Fed My CV to an LLM — and It Answered Questions About Me!”

💡 Project Description
  - This project demonstrates how to build a Retrieval-Augmented Generation (RAG) Agent using LangGraph.
The RAG agent can read and understand your PDF documents — in this case, my CV — and answer questions related to its content.

  - You can also feed any PDF into this system and query it using just a few lines of code provided in this repository.

🖼️ Images (Outputs):


🧩 Steps that I followed to make this RAG Agent
  - Load my LLM
  - Load my CV.pdf (A_Flutter_Developer_cv_Tarikul_Islam.pdf) using pypdfloader
  - Split my CV in different chunks to reduce token size
  - Embedded the splitted chunks for vector representation (Using GoogleGenerativeAIEmbeddings)
  - Store the Embedded part into Chroma Database
  - Retrieve the relevent context from the Chroma Database when user asks any question and LLM answers the relevant context

🧠 Tech Stack
  - LangGraph – For workflow orchestration
  - Gemini (Google Generative AI) – As the LLM
  - PyPDFLoader – To load and extract text from PDFs
  - ChromaDB – For vector storage and retrieval
  - GoogleGenerativeAIEmbeddings – To create text embeddings