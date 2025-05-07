# 🎉 Automated Birthday Wisher (Python)
This is a simple Python script that automatically sends birthday wishes via email to your friends, family, or colleagues based on their birth dates stored in a CSV file.

# 📌 Features
Reads birthday data from a .csv file

Sends personalized email wishes automatically

Runs daily using a scheduler (e.g., cron or Task Scheduler)

Customizable email messages

Easy to configure and use

# 🛠️ Requirements
Python 3.x

Modules:

smtplib

pandas

datetime

email or email.message

ssl

# 📄 birthdays.csv Format
name,email,day,month
John Doe,john@example.com,7,5
Jane Smith,jane@example.com,25,12

# ✉️ How It Works
The script runs and checks the current date.

If any birthday matches today’s date, it selects a random message template.

It personalizes the message and sends it via email.

# ⚠️ Security Tip
Avoid hardcoding your email and password. Use environment variables or a secure vault.

# 📬 To-Do
 Add SMS support (e.g., Twilio)

 Add birthday reminder notifications

 Add GUI to manage birthday entries

 📃 License
This project is licensed under the MIT License – see the LICENSE file for details.

 # 🙋‍♂️ About Me
 👋 Hi, I'm Tejas Nivrutti Divase
🎓 AI & DS Engineer at Dr. J. J. Magdum College of Engineering
🧠 Passionate Data Scientist | 🎬 Creative Animator
🏢 Founder of TejXsTuDiOs – Bridging AI + Animation

🔗 Connect with me:

🌐 LinkedIn (https://www.linkedin.com/in/tejas-divase-897996244?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)

📺 TejXsTuDiOs YouTube Channel (http://www.youtube.com/@TejXsTuDiOs-l1n)
