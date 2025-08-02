fork https://github.com/sb2nov/resume

### Quick start

Get started quickly using [Overleaf](https://www.overleaf.com/latex/templates/software-engineer-resume/gqxmqsvsbdjf) template.

### Build using Docker

```sh
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex jaejun_lee_resume.tex
```

### Docker w/ vscode Latex Workshop

```sh
docker pull --platform linux/amd64 ghcr.io/xu-cheng/texlive-full:latest
```

### License

Format is MIT but all the data is owned by Sourabh Bajaj.
