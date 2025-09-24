# voiceBox

|  Voice | Chat |
|-------------|-------------|
| <img src="https://github.com/user-attachments/assets/cb4c7806-76d7-438d-b7d9-9dc5e1b5df7c" width="350" /> | <img src="https://github.com/user-attachments/assets/8b617c65-0895-4123-8604-02858795b9a8" width="350" /> |

---

1. **Colab – Chatterbox**  
   - Provides **Text-to-Voice generation**.  
   - Runs along with FastAPI inside Colab.  

2. **FastAPI (Running in Colab)**  
   - Exposes endpoints for **Voice-to-Text** and **Text-to-Voice**.  
   - Handles requests inside the Kaggle environment.  
   - Data is **parsed back to local VS Code project** through HTTP requests.  

3. **Local Project (VS Code)**  
   - Connects to the Colab FastAPI server.  
   - Parses and processes the API responses.  
   - Uses **MCP** for communication logic:  
     - Confirm booking  
     - Cancel booking  
     - Answer user requests  
