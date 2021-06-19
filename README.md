# ABCEquations.js

- Electrical Current Calculation Example
https://39363.org/NOTES/WSU/2021/Spring/NEURO3200/Calculators/Current/
https://github.com/0187773933/Notes/blob/master/WSU/2021/Spring/NEURO3200/Calculators/Current/index.html

- This is a thing for making interactive equations

- [google python notebooks](https://colab.research.google.com/) or [streamlit](https://www.streamlit.io/)

- There are tons of markdown editors like [typora](https://typora.io/) that have katex and chemistry typesetting built in.

- This is a minimal auto-updating latex equation editor with [markdown](https://en.wikipedia.org/wiki/Markdown) , [katex](https://katex.org/) , [mchem](https://mhchem.github.io/MathJax-mhchem/) , [units manager](https://github.com/gentooboontoo/js-quantities) , and [ABCEquation.js](https://39363.org/CDN/NOTES/ABCEquations.js)



#### Two things you have to do to "build" an interactive equation:

1. Define all of the "operators" or variables involved
2. Setup a function that "solves" the equation
`let current = ( voltage / resistance );`

<br>

Two examples of the minimum html/js needed make equations using ABCEquations.js

https://gist.github.com/0187773933/278b659f1a111bcb473cfb1a5715d0fa
https://gist.github.com/0187773933/34855dbdd4954b05e8576a175aeb2aa5