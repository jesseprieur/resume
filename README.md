## Usage

```
docker build -t jesse/latex ./latex
docker run --rm -it --privileged --volume /Users/jesse.prieur/src/personal/resume:/resume jesse/latex
xelatex resume.tex
```