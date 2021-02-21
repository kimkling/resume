# Resume for Kim Kling

## Build
In the project base run this command with `<language>` being changed to either `english` or `swedish`.
```
docker run -it --rm -v "$(pwd)":/project ghcr.io/xu-cheng/texlive-full pdflatex -output-directory /project/software-engineer/output /project/software-engineer/<language>.tex
```
