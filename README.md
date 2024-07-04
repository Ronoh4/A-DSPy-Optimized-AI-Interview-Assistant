DSPy-Optimized AI Interview Assistant: A Streamlit App

This readme provides a concise overview of the AI Interview Assistant, a Streamlit application built using DSPy.

What it Does:

Generates interview questions based on a candidate's resume and the job description.
Integrates with LlamaParse to extract text from uploaded PDF documents.
Adapts follow-up questions based on the candidate's previous answers (future implementation).

Key Features:

DSPy for Optimized Question Generation: Leverages DSPy's framework to train and optimize LLM prompts for generating effective interview questions.
Streamlit Integration: Offers a user-friendly interface for uploading resumes, job descriptions, and providing answers.
LlamaParse Integration: Utilizes LlamaParse for efficient text extraction from PDFs.

How to Use:

Upload your resume (PDF) and the job description (PDF).
Click "Generate Interview Question" to receive the initial question.
Provide your answer in the text area.
Click "Submit Your Answer" to generate the next question based on your answer (future implementation).

Technical Notes:

The application utilizes Cohere's c4ai-aya-23 LLM model.
Replace the placeholder API keys with your own for LlamaParse.
The code includes comments and explanations for clarity.

Future Enhancements:

Implement functionalities to handle and track the number of questions asked per skill.
Explore more sophisticated optimizers and metrics for LLM training within DSPy.
Expand the depth and structure of training examples to capture a wider range of interview scenarios.

Benefits:

Streamlines the interview preparation process for recruiters and hiring managers.
Assists in formulating insightful and contextually relevant interview questions.
Enhances the overall interview experience for both interviewers and candidates.
