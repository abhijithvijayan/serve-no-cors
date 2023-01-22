<h1 align="center">serve-no-cors</h1>
<p align="center">Serve JavaScript from your local machine to the internet without CORS disturbing your inner peace.</p>
<div align="center">
  <a href="https://github.com/abhijithvijayan/serve-no-cors/blob/main/license">
    <img src="https://img.shields.io/github/license/abhijithvijayan/serve-no-cors.svg" alt="LICENSE" />
  </a>
  <a href="https://twitter.com/intent/tweet?text=Check+out+serve-no-cors%21+by+%40_abhijithv%0D%0A%0D%0AServe+JavaScript+from+your+local+machine+to+the+internet+without+CORS+disturbing+your+inner+peace.%0D%0Ahttps%3A%2F%2Fgithub.com%2Fabhijithvijayan%2Fserve-no-cors%0D%0A%0D%0A%23cors+%23serve+%23javascript+%23ngrok">
     <img src="https://img.shields.io/twitter/url/http/shields.io.svg?style=social" alt="TWEET" />
  </a>
</div>
<h3 align="center">🙋‍♂️ Made by <a href="https://twitter.com/_abhijithv">@abhijithvijayan</a></h3>
<p align="center">
  Donate:
  <a href="https://www.paypal.me/iamabhijithvijayan" target='_blank'><i><b>PayPal</b></i></a>,
  <a href="https://www.patreon.com/abhijithvijayan" target='_blank'><i><b>Patreon</b></i></a>
</p>
<p align="center">
  <a href='https://www.buymeacoffee.com/abhijithvijayan' target='_blank'>
    <img height='36' style='border:0px;height:36px;' src='https://bmc-cdn.nyc3.digitaloceanspaces.com/BMC-button-images/custom_images/orange_img.png' border='0' alt='Buy Me a Coffee' />
  </a>
</p>
<hr />

❤️ it? ⭐️ it on [GitHub](https://github.com/abhijithvijayan/serve-no-cors/stargazers) or [Tweet](https://twitter.com/intent/tweet?text=Check+out+serve-no-cors%21+by+%40_abhijithv%0D%0A%0D%0AServe+JavaScript+from+your+local+machine+to+the+internet+without+CORS+disturbing+your+inner+peace.%0D%0Ahttps%3A%2F%2Fgithub.com%2Fabhijithvijayan%2Fserve-no-cors%0D%0A%0D%0A%23cors+%23serve+%23javascript+%23ngrok) about it.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Issues](#issues)
    - [🐛 Bugs](#-bugs)
- [LICENSE](#license)

## Installation

[Download and setup ngrok](https://ngrok.com/download)

Ensure you have [Node.js](https://nodejs.org) 10 or later installed. Then run the following:

```
# via npm
npm install --global serve
```

## Usage

```bash
# Get this serve config file
curl -fsSL https://github.com/abhijithvijayan/serve-no-cors/archive/main.tar.gz | tar -xz --strip-components=1 serve-no-cors-main/serve.json

# serve the current folder. refer: https://github.com/vercel/serve#readme
serve . -p 49241

# generate a secure tunnel with ngrok. refer: https://ngrok.com/
ngrok http 49241
```

Now use javascript files across web.

Sample Usage with an ngrok tunnel
```html
<script defer src="https://bda2-103-164-21-230.in.ngrok.io/assets/main.js"></script>
```

## Issues

_Looking to contribute? Look for the [Good First Issue](https://github.com/abhijithvijayan/serve-no-cors/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc+label%3A%22good+first+issue%22)
label._

### 🐛 Bugs

Please file an issue [here](https://github.com/abhijithvijayan/serve-no-cors/issues/new) for bugs, missing documentation, or unexpected behavior.

[**See Bugs**](https://github.com/abhijithvijayan/serve-no-cors/issues?q=is%3Aissue+is%3Aopen+sort%3Aupdated-desc+label%3A%22type%3A+bug%22)

## License

MIT © [Abhijith Vijayan](https://abhijithvijayan.in)
