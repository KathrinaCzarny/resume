# KathrinaCzarny / resume
## Resume in markdown, HTML (with CSS styling), PDF, and Word

**Download or clone repo**
```
git clone https://github.com/kathrinaczarny/resume.git
```

**In the correct directory.**
```
cd resume
```
**Needed: Pandoc and wkhtmltopdf.**

Pandoc converts md to html (with CSS styling)
Wkhtmltopdf converts html to PDF
```
pandoc -o resume.html -c resume-css-stylesheet.css resume.md
wkhtmltopdf resume.html resume.pdf 
pandoc -o resume.docx --reference-docx=resume-docx-reference.docx resume.md
```
Commands also part of mdconvert.sh

---
Credit for instructions for this project: http://sdsawtelle.github.io/ _Gracias._ 
