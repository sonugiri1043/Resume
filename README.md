A single-page resume for software developers.
### Build using Docker

```sh
docker build -t latex .
docker run --rm -i -v "$PWD":/data latex pdflatex sonu_giri.tex
```
