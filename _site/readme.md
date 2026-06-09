
## export MD file to pdf 
```
pandoc index.md -o cv-fr.pdf \
  --pdf-engine=xelatex \
  --template=cv-template.tex \
  -V secnumdepth=0
  ```

  cv-template.tex is used to format the pdf.