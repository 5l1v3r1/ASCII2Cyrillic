# ASCII2Cyrillic
ASCII2Cyrillic - Exploiting the Punycode Vulnerability...

### Disclaimer: All information provided are for educational purposes only. The information related to ethical hacking and information security found on this page are not meant to be used maliciously/illegally and the author is not responsible for any misuse of the provided information.

# Description
ASCII2Cyrillic is a tool that allows you convert your ASCII text into Cyrillic characters. This can be used to exploit the Punycode Browser Vulnerability: https://www.xudongz.com/blog/2017/idn-phishing/

ASCII2Cyrillic is compatible with Python version 3.x.

# Preview
![Preview](http://i.imgur.com/sFUME7t.png)

# Getting Started
#### Installation
```git clone https://github.com/0xCoto/ASCII2Cyrillic```

#### Usage

```
cd ASCII2Cyrillic
python3 ASCII2Cyrillic.py
```

# Mechanism
The way this tool works is by reading the user's ASCII input and each (ASCII) character gets replaced by a Unicode (Cyrillic) one. As you can see in the Preview Screenshot above, every character looks identical, making Cyrillic usage applicable for Social Engineering & Phishing attacks.

# Credits
ASCII2Cyrillic was created by [@0xCoto](https://github.com/0xCoto).
