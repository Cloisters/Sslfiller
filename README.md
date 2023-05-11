# SSL Certificate Checker


This is a Python script to check the SSL certificate of a website. It checks the following information:

*SSL version*

*Issued to*

*Issued by*

*Serial number*

*Valid from*

*Valid until*

*Cipher suites used*

*Version Vulnerability*

# Installation
This script requires Python 3 and the termcolor, ssl, socket. To install requirements run:

`pip install termcolor`

`pip install ssl`

# Usage
Run the script and enter the domain name when prompted:

`python SslFiller`

# Note
• This script is developed by Entity.Network.

• This script only checks for known vulnerabilities and is not a comprehensive SSL security assessment tool.

• The script uses the ssl and socket modules to establish a secure connection with the website and retrieve the SSL certificate. 

• The script uses the termcolor module to output colored text in the terminal
