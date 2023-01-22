# serve

## Getting Started

```
# Get this serve config file
curl -fsSL https://github.com/abhijithvijayan/serve-no-cors/archive/main.tar.gz | tar -xz --strip-components=1 serve-no-cors-main/serve.json

# serve the current folder
serve . -p 49241

# generate a secure tunnel with ngrok. ref: https://ngrok.com/
ngrok http 49241
```

Now the folder will be able to server javascripts across ngrok URL without cors issue

eg:
```
https://bda7-103-165-22-230.in.ngrok.io/main.js
```
