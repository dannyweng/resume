# Resume  

View the [PDF](https://docs.google.com/viewer?url=https://raw.githubusercontent.com/dannyweng/resume/master/resume.pdf).

<div align="center">
  <img alt="Résumé" src="https://raw.githubusercontent.com/dannyweng/resume/master/resume.png" width="70%" />
</div>

```
MiKTeX/proTeXt/TeX Live
xelatex resume.tex
convert -density 300 resume.pdf -quality 90 -append resume.png

MacTex
lualatex resume.tex
magick convert -density 300 -background white -alpha remove resume.pdf -quality 90 -append resume2.png
```   
