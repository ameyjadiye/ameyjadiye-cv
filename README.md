

### Build using Docker

```sh
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex resume.tex
```

### Preview

![Resume Screenshot](preview-images/resume-1.png)