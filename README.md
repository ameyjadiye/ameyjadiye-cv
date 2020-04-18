

### Build using Docker

```sh
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex resume.tex
```

### Preview

```sh
pdftoppm resume.pdf preview-images/resume -png
```

![Resume Screenshot](preview-images/resume-1.png)