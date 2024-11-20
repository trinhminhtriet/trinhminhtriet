# Resume

### Markdown to HTML

```bash
pandoc resume.md -f markdown -t html -c style.css -s -o resume.html
pandoc TrinhMinhTriet-SrPHP.md -f markdown -t html -c style.css -s -o TrinhMinhTriet-SrPHP.html
pandoc TrinhMinhTriet-TechLead.md -f markdown -t html -c style.css -s -o TrinhMinhTriet-TechLead.html
```

### HTML to PDF

```bash
pandoc resume.md -f markdown -t pdf --pdf-engine=wkhtmltopdf -c style.css -s -o resume.pdf
pandoc resume.html -f html -t pdf --pdf-engine=wkhtmltopdf -c style.css -s -o resume.pdf
```
