Qrcode
======

[![GitHub issues](https://img.shields.io/github/issues/ta-verma/qrcode.svg)](https://github.com/ta-verma/qrcode/issues)
[![GitHub forks](https://img.shields.io/github/forks/ta-verma/qrcode.svg)](https://github.com/ta-verma/qrcode/network)
[![GitHub stars](https://img.shields.io/github/stars/ta-verma/qrcode.svg)](https://github.com/ta-verma/qrcode/stargazers)
[![GitHub license](https://img.shields.io/github/license/ta-verma/qrcode.svg)](https://github.com/ta-verma/qrcode/blob/master/License.md)
[![Twitter](https://img.shields.io/twitter/url/https/github.com/ta-verma/qrcode.svg?label=qrcode&style=social)](https://twitter.com/intent/tweet?text=qrcode:&url=https%3A%2F%2Fgithub.com%2Fta-verma%2FQrcode)

A HTML and java script Code Snippet to generate customise Qr-code.


## Table of Contents

* [Features](#features)
* [Usage](#api-usage)
* [Contributing](#contributing)

# Features

* Qr Code
  * Generate your custom qr code.
  * Get generated Qr-code as png.

# Usage

Manipulate **generateQR.html** File in the repository to generate Qr code by

* changing the "qrString" variable value accordingly.

~~~html
<!DOCTYPE html>
<html>
   <head>
      <script src="jquery.min.js"></script>
      <script src="qrcode.min.js"></script>
   </head>
   <body>
      <div id="qrcode"></div>
      <script type="text/javascript">
         var qrString = "Your custom string";
         new QRCode(document.getElementById("qrcode"), qrString);
      </script>
   </body>
</html>
~~~

![alt text](https://raw.githubusercontent.com/ta-verma/qrcode/master/qr%20code.png)



# Contributing

Feel free to submit a pull request or an issue!


#### Note : If the snippet stop working, please open a issue or comment on already existing one with the problem(s) that you are facing. 
