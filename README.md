# Rapid URL (By Pass Captcha) 
 
This Python program allows you to retrieve comprehensive information about a website, including its title, last modified date, DNS information, subdomains, firewall names, technologies used, and certificate information.

### OUTPUT 
<a href="https://ibb.co/NNTtpC9"><img src="https://i.ibb.co/s1WbQRK/IMG-5871.jpg" alt="IMG-5871" border="0"></a>
 
## Prerequisites

Before using this program, make sure you have the required Python packages installed. You can install them using pip:

```
pip install -r requirements.txt
```

## Usage

1. Clone this repository to your local machine:

   ```
   git clone https://github.com/AIGptCode/Rapid-Url.git
   ```

2. Navigate to the project directory:

   ```
   cd Rapid-Url
   ```

3. Run the program by providing a URL as an argument:

   ```
   python rapid_url.py <URL>
   ```

   Replace `<URL>` with the website URL you want to analyze.

## Features

- Page Title:** Retrieve the title of the web page.
- Last Modified Date:** Get the last modified date of the website.
- Creation Date:** Find the domain creation date using WHOIS information.
- DNS Information:** Discover the IP addresses associated with the domain.
- Subdomains:** List subdomains associated with the domain.
- Firewall Names:** Detect firewall information from HTTP response headers.
- Technologies Used:** Identify technologies and programming languages used in the website.
- Certificate Information:** Get details about the SSL certificate, including issuer and validity period.

## Output

The program provides detailed information about the website, including programming languages used and certificate information.

## Example

To analyze a website, run the program as follows:

```
python rapid_url.py https://example.com
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

