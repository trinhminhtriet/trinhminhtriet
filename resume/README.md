# Resume

### Markdown to HTML

```bash
pandoc TrinhMinhTriet-TechLead_Java.md -f markdown -t html -c style.css -s -o html/TrinhMinhTriet-TechLead_Java.html

TrinhMinhTriet-Senior_Golang_Developer.md
```

### HTML to PDF

```bash
pandoc resume.md -f markdown -t pdf --pdf-engine=wkhtmltopdf -c style.css -s -o resume.pdf
pandoc resume.html -f html -t pdf --pdf-engine=wkhtmltopdf -c style.css -s -o resume.pdf
```
