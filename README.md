# Python for Cybersecurity Automation

## 📌 Project Overview
In this project, I applied Python programming to cybersecurity tasks such as log analysis, pattern detection, and file handling.

Python is widely used in cybersecurity to automate repetitive tasks, analyze logs, and detect suspicious activity efficiently.

---

## 🛠️ Tools Used
- Python
- File handling
- Regular expressions (re)

---

## 🔐 Example: Login Attempt Analyzer

This script analyzes login attempts and detects suspicious activity.

### Code Example:
```python
# List of approved users
approved_users = ["admin", "analyst", "security"]

# Simulated login attempts
login_attempts = ["admin", "guest", "analyst", "hacker"]

# Check access
for user in login_attempts:
    if user in approved_users:
        print(user + " access granted")
    else:
        print(user + " access denied")
```

📖 This simulates how systems check user access.

---

## 🔁 Loops and Conditions

I used loops and conditional statements to automate decisions.

```python
for i in range(5):
    print("Checking system...")

if attempts > 5:
    print("Too many login attempts")
```

📖 This is important for detecting brute-force attacks.

---

## 📂 File Handling

I learned how to read and write files.

```python
with open("log.txt", "r") as file:
    content = file.read()

with open("alerts.txt", "a") as file:
    file.write("Suspicious activity detected\n")
```

📖 This is used for log analysis and incident reporting.

---

## 🔍 Regular Expressions (Pattern Detection)

I used regex to find patterns in data.

```python
import re

data = "user123 logged in from 192.168.1.1"
matches = re.findall(r"\d+", data)

print(matches)
```

📖 This helps detect IP addresses, IDs, and suspicious patterns.

---

## 🧠 Data Parsing

I learned how to process data using split and join.

```python
users = "admin,analyst,guest"
user_list = users.split(",")

print(user_list)
```

📖 Parsing is important when working with logs and datasets.

---

## 🧠 What I Learned

- How to automate cybersecurity tasks using Python  
- How to analyze logs and detect patterns  
- How to use loops and conditions for security logic  
- How to work with files and data  

---

## 🔐 Why This Is Important in Cybersecurity

Python is used by security professionals to:
- automate tasks  
- analyze logs  
- detect threats  
- process large data  

This is especially useful in roles like:
- SOC Analyst  
- Security Analyst  
- Incident Responder  

---

## 🚀 Future Improvements

- Build a real log analyzer  
- Detect brute-force attacks automatically  
- Combine Python with SIEM tools  
- Analyze real datasets  
