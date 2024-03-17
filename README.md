# QuantumLEX
Legal Research Engine Insight

# QuantumLEX: AI Legal Engine

## Overview
QuantumLEX is an offline legal engine that assists attorneys in analyzing cases through audio instructions, image descriptions, and text prompts. It utilizes state-of-the-art natural language processing models, audio transcription, and image analysis to provide comprehensive responses to user queries.

## Note: Each prompt takes approx 25 minutes to respond, and moreover the file is 28-29 GB in size, therefore it cannot be uploaded in github, so googledrive link is provided

## Technology Used
- Streamlit: For the interactive web-based user interface.
- PyTorch and Transformers: For audio transcription using the Whisper model.
- Llama and Llavender: For handling image-related queries.
- Mistral: For handling text prompts.
- Langchain: A framework for building multimodal AI chat system for legal assistance.
- ChromaDB: For managing embeddings and vector stores.
- PyPDFium2: For extracting text from PDF documents.

## Setup

1. Download the Folder:
      ```bash
      https://drive.google.com/drive/folders/1v-0aVG3xIncN1RGNdtag7CoBFjBQcVwL?usp=sharing

  
2. Videolink for product Demo (In video at time 3:58 the oral instruction was given to modal which transcribed by whisper and later processed, you may pause the video and read the output, due to exceeding time limit of 2 minutes, I cant explain the output)

    ```bash
    https://youtu.be/1hRJgASxdtI

3. Open the folder in visual studio

4.  ```bash
    pip install -r requirements.txt

5.  ```bash
     streamlit run app.py

If you are facing error with llava part (i.e. image upload error), then run app2.py (Note: Due to excessive processsing time due to no gpu , streamlit may timeout) 
   ```bash
     streamlit run app2.py
