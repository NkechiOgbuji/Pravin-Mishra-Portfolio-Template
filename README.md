# DMI Portfolio Website (Static HTML/CSS)

This repository contains a clean, professional-looking **static portfolio website** used in **DevOps Micro Internship (DMI)** Week 1 to practice:
- Linux basics
- Nginx hosting
- Deployment proof / ownership
- Production-style checks

✅ Students deploy this website on an Ubuntu VM using Nginx and keep it live for 24 hours.

---

## Who is this for?
- DMI students (beginner → intermediate)
- Anyone learning how to host a static site with Nginx on Linux

---

## What you will build
A portfolio-style website hosted on:
- **Ubuntu VM**
- **Nginx**
- Accessible via: `http://<public-ip>`

---

## Mandatory Ownership Proof (DMI Rule)
Before you deploy, you MUST edit the footer and add your details:

Original:

```html
<p>Crafted with <span>cloud</span> excellence by Pravin Mishra</p>
```

Add this line (example):

```html
<p><strong>Deployed by:</strong> DMI Cohort 2 | Rahul Sharma | Group 4 | Week 1 | 16-01-2026</p>## 📅 Deployment Date Automation

As part of this portfolio deployment task, I implemented a dynamic deployment date in the website footer to automatically reflect the current deployment date.

Instead of manually updating the date each time changes are deployed, JavaScript was used to fetch and display the current system date in real time.
---

### Implementation Details
The deployment date is displayed in the footer using a `<span>` element:

```html
<span id="deployDate"></span>

## A JavaScript snippet was added inside the index.html file to generate and inject the current date:
<script>
  const d = new Date();
  const formattedDate = d.toISOString().split("T")[0];
  document.getElementById("deployDate").textContent = formattedDate;
</script>





✅ This proof must be visibA JavaScript snippet was added inside the index.html file to generate and inject the current date:le in your browser screenshot submission.