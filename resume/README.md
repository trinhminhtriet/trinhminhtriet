# Resume

### Markdown to HTML

```bash
pandoc TrinhMinhTriet-TechLead.md -f markdown -t html -c style.css -s -o html/TrinhMinhTriet-TechLead.html
pandoc TrinhMinhTriet-Senior_JS_Developer.md -f markdown -t html -c style.css -s -o html/TrinhMinhTriet-Senior_JS_Developer.html
pandoc TrinhMinhTriet-Senior_PHP_Developer.md -f markdown -t html -c style.css -s -o html/TrinhMinhTriet-Senior_PHP_Developer.html
pandoc TrinhMinhTriet-Senior_Java_Developer.md -f markdown -t html -c style.css -s -o html/TrinhMinhTriet-Senior_Java_Developer.html
pandoc TrinhMinhTriet-Java_Rakuten.md -f markdown -t html -c style.css -s -o html/TrinhMinhTriet-Java_Rakuten.html
pandoc TrinhMinhTriet-SSE-ELSA.md -f markdown -t html -c style.css -s -o html/TrinhMinhTriet-SSE-ELSA.html
pandoc TrinhMinhTriet-TL-CoverGo.md -f markdown -t html -c style.css -s -o html/TrinhMinhTriet-TL-CoverGo.html
pandoc TrinhMinhTriet-SSE-GetLinks.md -f markdown -t html -c style.css -s -o html/TrinhMinhTriet-SSE-GetLinks.html
pandoc TrinhMinhTriet-SeniorWordpressDeveloper-KellerExecutiveSearch.md -f markdown -t html -c style.css -s -o html/SeniorWordpressDeveloper-KellerExecutiveSearch.html
pandoc TrinhMinhTriet-SSE-Metadata.md -f markdown -t html -c style.css -s -o html/TrinhMinhTriet-SSE-Metadata.html
pandoc TrinhMinhTriet-TL.md -f markdown -t html -c style.css -s -o html/TrinhMinhTriet-TL.html
pandoc TrinhMinhTriet-TechnicalLead-TS.md -f markdown -t html -c style.css -s -o html/TrinhMinhTriet-TechnicalLead-TS.html
pandoc TrinhMinhTriet-SolutionArchitect.md -f markdown -t html -c style.css -s -o html/TrinhMinhTriet-SolutionArchitect.html
pandoc TrinhMinhTriet-Senior_FullStack_Engineer.md -f markdown -t html -c style.css -s -o html/TrinhMinhTriet-Senior_FullStack_Engineer.html

pandoc TrinhMinhTriet-Lead-Backend-Engineer.md -f markdown -t html -c style.css -s -o html/TrinhMinhTriet-Lead-Backend-Engineer.html
```

### HTML to PDF

```bash
pandoc resume.md -f markdown -t pdf --pdf-engine=wkhtmltopdf -c style.css -s -o resume.pdf
pandoc resume.html -f html -t pdf --pdf-engine=wkhtmltopdf -c style.css -s -o resume.pdf
```
