# Glossary for Automated Polyglot Persistence

See the [Glossary Tool](https://github.com/ksm2/glossary) for how the `.glossary` format works.

## Generate the Glossary

You need PHP 7.2 or higher and [Composer](https://getcomposer.org/):

```
composer require corny-phoenix/glossary
```

To generate the glossary with LaTeX, use

```
xelatex glossary 
makeglossaries glossary 
xelatex glossary 
open glossary.pdf
```

([XeLaTeX](https://de.wikipedia.org/wiki/XeTeX) comes with most LaTeX distributions.)
