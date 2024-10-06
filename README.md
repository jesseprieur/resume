## Usage
_Assuming current directory is `resume`:_

```
docker build -t jesse/latex ./latex
docker run --rm -it --privileged --volume ./:/resume jesse/latex
cd /resume/latex/
xelatex resume.tex
```