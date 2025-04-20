# reCAPTCHA Phishing 
This is an attempt to recreate the reCAPTCHA phishing technique that is seen in the wild. Companies are free to use this as reference to train internal staff.

Instructions:
- To use just run the HTML files.
- Dummy login details are as follows --usrname:admin --pw:password
- Please change the data-sitekey to your own in real_captcha.html for the reCAPTCHA to work (get it from google)


Credits to John Hammond: https://github.com/JohnHammond/recaptcha-phish

# Comparison between real and phishing reCAPTCHA

![dual](https://github.com/user-attachments/assets/2649571d-154a-4ab0-9ef4-877a27413528)


### Real

Does what a normal website would do, ensure user is not a bot and logging in would take user to the website.


![real](https://github.com/user-attachments/assets/54879472-2275-4f9b-8963-40b7df631c9a)



### Phishing 

Instruct user to perform a set of actions, to enter a command into user's powershell which eventually download the payload.

![fake](https://github.com/user-attachments/assets/26ea082c-523d-42ee-87b4-1373889e9e9e)
