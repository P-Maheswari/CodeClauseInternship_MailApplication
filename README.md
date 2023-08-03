# CodeClauseInternship_MailApplication
In this project, I have created a GUI with Tkinter. 
This GUI includes receiver's email where the user can enter the receiver's email ID, Subject, Message or Content of the particular email.
Along with these there are two buttons named as "send" and "exit from the applicattion".
Send button can used to send the email which is written by the user.
Exit from the application button helps to come out of the Mail Application Window.<br>
**you might get error while sending an email because of the following reasons:** <br><br>
1.**Authentication Error:** If the Gmail credentials (email and password) are incorrect, smtplib.SMTPAuthenticationError can occur. Make sure the email and password provided in the code are correct.<br>
2.**Gmail Security Settings:** Gmail may block access to "less secure apps." Ensure that you have enabled "Allow less secure apps" in your Gmail settings. However, this is not recommended for production systems due to security concerns.<br>
3.**Network Issues:** If there are network connectivity problems, smtplib.SMTPConnectError or smtplib.SMTPServerDisconnected errors may occur.<br>
4.**Firewall or Proxy Restrictions:** Firewalls or proxy servers might block the connection to the SMTP server, leading to smtplib.SMTPConnectError or other connection-related errors.<br>
5.**SMTP Server Settings:** The SMTP server address or port might be incorrect, causing smtplib.SMTPConnectError.<br>
