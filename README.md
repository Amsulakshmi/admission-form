# 📝 College Admission Form — AWS S3 Static Website

A static web application built with **HTML and CSS**, deployed on **Amazon S3** as a publicly accessible website. This project demonstrates cloud-based static website hosting using AWS S3 bucket policies.

---

## 🎯 Project Overview

This project was developed as part of the **Cloud Computing domain** during my internship at **Corizo Edutech**. It demonstrates how to host a fully functional static website on AWS S3 with public access configuration.

---

## ✨ Features

- 📋 Clean college admission form UI
- 👤 Fields: Name, Email, Date of Birth, Course selection
- 🎨 Styled with CSS (card layout, shadows, responsive design)
- ☁️ Hosted on AWS S3 with public bucket policy
- 🌐 Accessible via public S3 URL

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| HTML5 | Form structure and content |
| CSS3 | Styling and layout |
| AWS S3 | Static website hosting |
| AWS Bucket Policy | Public access configuration |

---

## ☁️ AWS Deployment Steps

1. Created an S3 bucket on AWS Console
2. Enabled **Static Website Hosting** on the bucket
3. Uploaded `index.html` and `style.css` as objects
4. Applied **Bucket Policy** to make objects publicly accessible:

```json
{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Sid": "PublicReadAccess",
            "Effect": "Allow",
            "Principal": "*",
            "Action": "s3:GetObject",
            "Resource": "arn:aws:s3:::bucket-name/*"
        }
    ]
}
```

5. Accessed the form via the public S3 endpoint URL

---

## 📁 Project Structure

```
admission-form/
│
├── index.html       # Admission form HTML
├── style.css        # Styling for the form
└── README.md        # Project documentation
```

---

## 🎓 Internship Context

- **Organization:** Corizo Edutech
- **Domain:** Cloud Computing (AWS)
- **Duration:** April 2025 – August 2025

---

## 👩‍💻 Author

**Amsulakshmi K J**  
B.Sc Statistics — Vimala College, Thrissur  
B.Sc Data Science & Programming — IIT Madras  
📧 amsulakshmijagadeesan@gmail.com  
🔗 https://www.linkedin.com/in/amsulakshmi-jagadeesan

