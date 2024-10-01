## Usage

```
docker build -t jesse/latex ./latex
docker run --rm -it --privileged --volume ./resume:/resume jesse/latex
cd latex/
xelatex resume.tex
```