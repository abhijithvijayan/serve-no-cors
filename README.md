# serve

## Getting Started

```
curl -fsSL https://github.com/abhijithvijayan/serve/archive/main.tar.gz | tar -xz --strip-components=1 serve-main/serve.json

serve . -p 49241

ngrok http 49241
```

Now the folder will be able to server javascripts across ngrok URL without cors issue

eg:
```
https://bda7-103-165-22-230.in.ngrok.io/main.js
```
