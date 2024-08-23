# Testing Google Gemini API 

```
curl \
  -H 'Content-Type: application/json' \
  -d '{"contents":[{"parts":[{"text":"Explain how AI works"}]}]}' \
  -X POST 'https://generativelanguage.googleapis.com/v1beta/models/gemini-1.5-flash-latest:generateContent?key=YourAPIKey'
```

#To run the colab notebook, include your google_api_key 

`os.environ["GOOGLE_API_KEY"] =  "<your_google_api_key"`
