Backend logic to interact with the model (random currently to test connection) hosted on Hugging Face Spaces and the Frontend.

1. Activate the virtual env : venv\Scripts\activate
2. run the server: uvicorn main:app --reload
3. Test the post /analyze endpoint, with the body (raw json)
   {
      "text": "insert text here..."   (will determine whether the text is positive or negative)
   }
