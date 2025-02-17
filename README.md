**Postman API call for Open AI**

    POST Request

   ** URL: https://api.openai.com/v1/chat/completions**

   Request Body:

  ** {
    "model": "gpt-3.5-turbo",
    "messages": [
      {
      "role": "user",
      "content": "Suggest me a name of Indian Restaurants"
      }
    ]
  }**

  Auth Tab -> Bearer Token: My OpenAI API Key


  
  
**  Postman API Call for Gemini AI**


  POST Request

  URL:
**
  https://generativelanguage.googleapis.com/v1beta/models/gemini-1.5-flash:generateContent?key='your key'**

  Request Body:

**  {
  "contents": [{
    "parts":[{"text": "What is the capital of France ?"}]
    }]
}**

