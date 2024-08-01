# WealthWizard Financial Advisory System

**Note**: The system is not deployed on Azure due to a severe time crunch caused by placement activities and project submissions at college. We kindly request more time until 7th August to complete the deployment.

## Scope
- **Integration of Advanced AI Technologies**: Utilizes NLP and Embedding.
- **Technology Stack**: FastAPI for backend, React for frontend, and MongoDB and Chroma for data management.
- **User Feedback**: Continuous improvement through user feedback.
- **Comprehensive Financial Planning**: Covers subdomains like budgeting, saving, investing, and more.
- **Modularity and Scalability**: Ensures modularity, scalability, and personalization.

## Objectives
1. **Personalized Financial Guidance**: Develop a chatbot for highly personalized financial advice tailored to user profiles and goals.
2. **Scalable, Secure Platform**: Build a scalable platform with robust security for seamless performance and data protection.
3. **Continuous Learning**: Enable the chatbot to learn and adapt from user interactions and feedback over time.
4. **Advanced AI and NLP Integration**: Leverage Langchain and HuggingFace Transformers for sophisticated AI and NLP functionalities.
5. **Integrating Latest Technologies**: Use the latest technologies to ensure more accurate and reliable financial advice.

## Features
1. **Personalization**: WealthWizard provides highly personalized financial advice by leveraging advanced AI technologies, ensuring recommendations are tailored to individual user needs and financial situations.
2. **Continuous Learning**: The chatbot continuously improves its algorithms through machine learning, ensuring that the advice remains relevant and up-to-date with the latest financial trends and user behaviors.
3. **User-Friendly Interface**: With a React frontend and FastAPI backend, WealthWizard ensures a seamless, intuitive user experience, making financial advice easily accessible to everyone.
4. **Comprehensive Financial Guidance**: Unlike other financial chatbots that may focus on specific areas, WealthWizard offers a holistic approach, covering budgeting, savings, investments, and overall financial planning.
5. **Empowering Financial Literacy**: WealthWizard not only provides advice but also educates users, empowering them to make informed financial decisions. This educational aspect enhances its value, helping users build better financial habits and understanding.
6. **Open-Source Toolset**: WealthWizard is built entirely using open-source technologies, ensuring transparency, flexibility, and community-driven improvements.
7. **Real-time Market Insights**: Uses AI algorithms to provide timely and accurate market trend insights.

## Architecture
![System Architecture](https://github.com/Aakashdeep-Srivastava/Financial_Advisory/blob/main/Architecture.PNG)

## Setup Instructions
1. **Clone the Repository**:
   ```sh
   git clone https://github.com/yourusername/wealthwizard.git
   cd wealthwizard

## Backend Setup:

Create a virtual environment and activate it:
sh
Copy code
python3 -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
Install backend dependencies:
sh
Copy code
pip install -r backend/requirements.txt
Start the FastAPI server:
sh
Copy code
uvicorn backend.main:app --reload
Frontend Setup:

Navigate to the frontend directory:
sh
Copy code
cd frontend
Install frontend dependencies:
sh
Copy code
npm install
Start the React development server:
sh
Copy code
npm start

## Database Setup:

Ensure MongoDB is installed and running on your local machine or use a cloud service like MongoDB Atlas.
Configure the database connection in the backend configuration.
Run the Application:

Access the application at http://localhost:3000 for the frontend.
Backend API documentation can be accessed at http://localhost:8000/docs.
