# Resume

### Markdown to HTML

```bash
pandoc TrinhMinhTriet-TechLead.md -f markdown -t html -c style.css -s -o html/TrinhMinhTriet-TechLead.html
pandoc TrinhMinhTriet-Senior_JS_Developer.md -f markdown -t html -c style.css -s -o html/TrinhMinhTriet-Senior_JS_Developer.html
pandoc TrinhMinhTriet-Senior_PHP_Developer.md -f markdown -t html -c style.css -s -o html/TrinhMinhTriet-Senior_PHP_Developer.html
```

### HTML to PDF

```bash
pandoc resume.md -f markdown -t pdf --pdf-engine=wkhtmltopdf -c style.css -s -o resume.pdf
pandoc resume.html -f html -t pdf --pdf-engine=wkhtmltopdf -c style.css -s -o resume.pdf
```
