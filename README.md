# Scam Site Filter

This project aims to automate the process of identifying and filtering scam crypto airdrop links shared on Twitter. It involves monitoring tweets that mention "@addtofilter," extracting relevant information, checking the redirection of links, and creating a list of verified scam site URLs. The list can then be used with ad-blocking tools like uBlock to protect users from accessing scam sites.

## Overview

The project consists of several steps:

1. **Twitter Monitoring**: The Twitter API is used to monitor tweets that mention "@addtofilter." This allows you to capture tweets where users suspect a scam crypto airdrop and provide a link.

2. **Link Redirection Check**: The script checks the redirection of the links shared in the tweets. It determines the final destination URL to verify if it is a scam site or not.

3. **Manual Verification**: A temporary list of redirected scam site URLs is generated. You manually review and validate the list to remove any false positives or non-scam sites.

4. **GitHub Integration**: The script interacts with the GitHub API to create a new repository and a file to store the verified scam site URLs. The file is programmatically updated with the URLs from the temporary list.

5. **Filtering with uBlock**: The final list of verified scam site URLs can be exported from the repository and used as a filter with ad-blocking tools like uBlock. This helps protect users from accessing scam sites.

## Disclaimer

This project is provided as-is with no warranties or guarantees. It is intended for educational and informational purposes only. Use it responsibly and adhere to all relevant laws and regulations. The project authors and contributors are not responsible for any misuse or consequences arising from the use of this project.

## Contributions

Contributions to this project are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
