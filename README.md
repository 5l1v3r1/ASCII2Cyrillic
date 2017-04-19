# ASCII2Cyrillic
ASCII2Cyrillic - Exploiting the Punycode Vulnerability...

# Description
ASCII2Cyrillic is a tool that allows you convert your ASCII text into Cyrillic characters. This can be used to exploit the Punycode Browser Vulnerability: https://www.xudongz.com/blog/2017/idn-phishing/

ASCII2Cyrillic is compatible with Python version 3.x.

# Preview
![Preview](http://i.imgur.com/sFUME7t.png)

# Getting Started
#### Installation
```git clone https://github.com/0xCoto/PyInfect```

#### Usage

```
cd ASCII2Cyrillic
python ASCII2Cyrillic.py
```

# Mechanism
The way this tool works is by reading the user's ASCII input and each (ASCII) character gets replaced by a Unicode (Cyrillic) one. As you can see in the Preview Screenshot above, every character looks identical, making Cyrillic usage applicable for Social Engineering & Phishing attacks.

# Credits
PyInfect was created by [@0xCoto](https://github.com/0xCoto).
