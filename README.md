# FB-KOMEN - FACEBOOK TIMELINE AUTO COMMENTS

![Fb-Komen](https://github.com/user-attachments/assets/aa09c896-3dff-4d54-bca7-37264c9eb75c)

Fb-Komen is a Python script designed to comment on Facebook posts with images generated by AI. This project leverages AI to create unique and engaging comments, enhancing your social media interaction.

## Features
- **Comment and React with Images**: Automatically comment on posts with images generated by AI from Koala.sh and Ephoto360.com.
- **Targeted Comments and Reactions**: Comment and react to specific posts.
- **Custom Comment Texts**: Modify the default comment texts to your preference.
- **Like Posts**: Automatically like posts on your Facebook feed.
- **User Authentication**: Secure login with cookies validation.

## Installation

- Required Python packages: Install them using `pip install -r requirements.txt`
- Python 3.x
- [Termux](https://f-droid.org/repo/com.termux_1020.apk) v118/v119

```
$ apt update -y && apt upgrade -y
$ pkg install git python-pip
$ git clone https://github.com/RozhakXD/Fb-Komen
$ cd "Fb-Komen"
$ python -m pip install -r requirements.txt
$ python Run.py
```

## Usage
Upon running the script, you will be prompted to select from various features:

1. Comment and React with Images (Koala.sh)
2. Comment with Images (Ephoto360.com)
3. Comment and React to Specific Post
4. Change Comment Text
5. Like Feed Posts
6. Exit

Follow the on-screen instructions to input the necessary details such as delay time, comment texts, or specific post links.

**Example**:
To comment on the latest posts with images generated by Koala.sh, select option 1 and follow the prompts to set your delay time and start the process.

## Support
If you enjoy using this project, consider supporting its development:

- [Trakteer](https://trakteer.id/rozhak_official/tip)
- [PayPal](https://paypal.me/rozhak9)

## Screenshot
![Komentar](https://github.com/user-attachments/assets/f1684a61-2436-4984-8aab-67fb4dd4afee)

## Troubleshooting
- **Comment Failure**: If the script fails to comment, the post might not be commentable, the post ID might be unavailable, or your Facebook account could be blocked.
- **Connection Problems**: Ensure you have a stable internet connection. If you encounter connection issues, the script will notify you and attempt to reconnect.
- **Invalid Cookies**: If you receive an error related to cookies, ensure your cookies are correctly saved in `Penyimpanan/Cookie.json`. Re-run the login process if necessary.
- **Script Stuck**: If the script gets stuck, you can stop it using `CTRL + C` and restart it.
- **Login Issues**: If you fail to log in, ensure that your Facebook account language is set to Indonesian and that you are not using the free mode on your account.
- **Image Generation Failure**: If the script fails to create images, there might be an issue with the AI server.

## Warning
Users should exercise caution and avoid setting the delay too short, as this may result in your account being blocked. Always enable two-factor authentication for added security, and ensure your email and phone number are updated and verified.

## Contact
For further assistance, feel free to open an issue on the [GitHub repository](https://github.com/RozhakXD/Fb-Komen/issues).
