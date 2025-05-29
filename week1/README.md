# huggingfacebrochure

# 🤖 Edward Donner + Hugging Face Brochure Generator

This project creates a polished brochure in PDF format showcasing content from [Edward Donner's website](https://edwarddonner.com) and key Hugging Face AI contributions.

The content is manually or dynamically added in Markdown, converted to HTML, and then exported as a professionally styled brochure using `markdown2` and `pdfkit`.

---

## 📄 Project Files

- [View Brochure (PDF)](brochure.pdf)
- [Brochure Source (Markdown)](brochure.md)
- [Brochure html(html)](brochure.html)

---

## 📸 Screenshots

### ✅ Generated PDF Brochure  
![Brochure Preview](screenshots/brochure.pdf)

### 🐍 Python Script in Action  
![Brochure html](screenshots/brochure.html)

### 📄 Markdown Source  
![Markdown File](screenshots/brochure.md)

> Place these images in a folder named `screenshots/` in the root of your project.

---

## 🚀 How It Works

### Step-by-step:

1. Content is added or scraped from [Edward Donner](https://edwarddonner.com) & Hugging Face.
2. Markdown is written and saved as `brochure.md`.
3. Python reads the Markdown and converts it to HTML.
4. HTML is rendered into a high-quality PDF using `wkhtmltopdf`.

---

## 🛠️ Setup Instructions

### 📦 Dependencies

Install required packages:

```bash
pip install markdown2 pdfkit

Install wkhtmltopdf from wkhtmltopdf.org

Be sure to note the install path (e.g., C:\Program Files\wkhtmltopdf\bin\wkhtmltopdf.exe)

🧠 Technologies Used
Python 3.x

markdown2 – Markdown to HTML

pdfkit – HTML to PDF conversion

wkhtmltopdf – External engine for rendering
