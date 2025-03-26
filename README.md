# CyberSecurity Internship - Week 1: Security Assessment

## **Overview**
This repository contains the **Week 1 security assessment task** for my cybersecurity internship.

The objective of this task is to **analyze security vulnerabilities** in a mock web application, identify potential threats, and document the findings.

---

## **Objectives**
- **Set up and explore** a mock web application.
- **Perform basic vulnerability assessments** using:
  - **OWASP ZAP** (Automated security scanning)
  - **Browser Developer Tools** (Manual XSS testing)
  - **SQL Injection testing** (Manual and automated methods)
- **Document security findings** and suggest areas of improvement.

---

## **Setup Instructions**
To replicate the test environment and perform a security assessment, follow these steps:

### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/Mayra-Ahmer/CyberSecurity-Internship-Week1.git
```

### **2️⃣ Navigate to the Project Directory**
```sh
cd CyberSecurity-Internship-Week1
```

### **3️⃣ Install Dependencies**
```sh
npm install
```

### **4️⃣ Start the Application**
```sh
npm start
```

### **5️⃣ Open the App in Your Browser**
Navigate to:
```
http://localhost:3000
```

---

## **Vulnerability Assessment Steps**
### **1. Automated Security Scanning (OWASP ZAP)**
- Run OWASP ZAP and configure it as a proxy for your browser.
- Perform a full scan of the running application.
- Identify vulnerabilities like XSS, SQL Injection, and security misconfigurations.

### **2. Manual XSS Testing (Browser Developer Tools)**
- Inspect input fields for possible XSS vulnerabilities.
- Inject payloads like `<script>alert('XSS')</script>` and check responses.

### **3. SQL Injection Testing**
- Use manual and automated techniques (e.g., SQLmap) to test for SQL injection.
- Try payloads like `admin' --` or `' OR 1=1 --` in login forms.

---

## **Expected Outcomes**
- A security assessment report outlining:
  - Identified vulnerabilities and their severity.
  - Suggested remediation steps.
  - Screenshots of successful exploitations (if applicable).

---

## **Dependencies & Requirements**
- **Node.js** (latest LTS version recommended)
- **OWASP ZAP** (for automated security scanning)
- **SQLmap** (for SQL injection testing, optional)
- **Modern Web Browser** (Chrome/Firefox with Developer Tools)
- **Operating System Compatibility**: Works on Windows, Linux, macOS

---

## **Contribution Guidelines**
If you'd like to contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit (`git commit -m "Added new test case"`).
4. Push to your fork and submit a pull request.

---

## **License**
This project is licensed under the MIT License - .

