***GenAI-Powered Aerospace Document Similarity Search***

*Use Case Overview*

Aerospace programs generate large volumes of highly structured technical data—ranging from maintenance procedures to visual diagrams. However, due to siloed systems and inconsistent formats, valuable content is often recreated instead of reused. This leads to inefficiencies, duplication of effort, and delays in publication timelines.

This project addresses the problem by implementing a GenAI-powered similarity search system that uses retrieval agents to search across historical documentation and illustrations. It detects patterns, surfaces relevant matches, and recommends reusable content, enabling teams to build new publications faster and with greater consistency.

**What Has Been Built**

- A full-stack web application with a React frontend and Flask backend.
- Integration with Google Cloud Vertex AI for generating text and image embeddings.
- Semantic search using cosine similarity on text embeddings.
- Visual similarity search using image embeddings.
- Metadata filtering (aircraft type, system, version) to refine search results.
- Template suggestion based on query context.
- Preloading and caching of dataset and embeddings for performance.
  
**What Users Will Get**

- Ability to search aerospace documents using natural language queries.
- Visual search capability by uploading an image or providing an image URL.
- Suggested templates based on the query content.
- Filtered and ranked results based on semantic and visual similarity.
- A responsive and user-friendly interface with dark mode support.
  
**How to Run the App**

*Prerequisites*
- Python 3.8+
- Node.js and npm
- Google Cloud account with Vertex AI and Cloud Storage enabled
- Service account key JSON file
  
**Backend Setup**

1) Clone the repository and navigate to the backend directory.
   
             🧑‍💻 git clone <repository-url>
   
             🧑‍💻 cd <repository-folder>/backend

3) Create a .env file and add:
-        GOOGLE_APPLICATION_CREDENTIALS=path/to/your/service-account.json
  
3) Install dependencies:
   
             🧑‍💻 pip install -r requirements.txt
   
5) Run the backend:
   
             🧑‍💻 python app.py
   
**Frontend Setup**

1) Navigate to the frontend directory.
   
            🧑‍💻 cd <repository-folder>/frontend
   
2) Install dependencies
    
            🧑‍💻 npm install
   
3) Start the frontend:

            🧑‍💻 npm start
   
**Technologies Used**

- React (Frontend)
  
- Flask (Backend)
  
- Google Cloud Vertex AI (Text and Image Embeddings)
  
- Google Cloud Storage
  
- Pandas, NumPy, Requests
  
- dotenv, flask-cors
