# installtools
A Simple script that is used to install and run all the tools that Cappricio Securities develop

## Installation 

1. Install Python3 and pip [Instructions Here](https://www.python.org/downloads/) (If you can't figure this out, you shouldn't really be using this)

   - Install via git
     - ```bash
          git clone https://github.com/Cappricio-Securities/installtools.git 
        ```
   - Run the below command to check
     - `chmod +x install.sh`

## Configurations 
2. We integrated with the Telegram API to receive instant notifications for vulnerability detection.
   
   - For Getting Instant Telegram Notification
     - ```bash
          crlfi --chatid <YourTelegramChatID>
        ```
   - Open your telegram and search for [`@CappricioSecuritiesTools_bot`](https://web.telegram.org/k/#@CappricioSecuritiesTools_bot) and click start

## Usages 
3. This tool has multiple use cases.
   
   - To Check Single URL
     - ```bash
          crlfi -u http://example.com 
        ```
   - To Check List of URL 
      - ```bash
          crlfi -i urls.txt 
        ```
   - Save output into TXT file
      - ```bash
          crlfi -i urls.txt -o out.txt
        ```
   - Want to Learn about [`Our Tools and Bugs`](https://blogs.cappriciosec.com/)? Then Type Below command
      - ```bash
          crlfi -b
        ```
     
<p align="center">
  <b>🚨 Disclaimer</b>
  
</p>
<p align="center">
<b>This tool is created for security bug identification and assistance; Cappricio Securities is not liable for any illegal use. 
  Use responsibly within legal and ethical boundaries. 🔐🛡️</b></p>



## 🔗 Links
[![Website](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://cappriciosec.com/)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/karthikeyan--v/)
[![twitter](https://img.shields.io/badge/twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/karthithehacker)



## Author

- [@karthithehacker](https://github.com/karthi-the-hacker/)



## Feedback

If you have any feedback, please reach out to us at contact@karthithehacker.com
