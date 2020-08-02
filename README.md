    Copyright (c) 2020-
    Author: Chaitanya Tejaswi (github.com/CRTejaswi)    License: MIT

# CV
> Customizable Résumé/CV template in MarkDown. <br>
> Demo available [here](https://crtejaswi.github.io/CV).

## Usage

- Convert to PDF
```
pandoc --metadata title='FirstName LastName' -t html5 --css resume.css -o cv.pdf cv.md
```
- Convert to HTML
```
pandoc --standalone --metadata title='FirstName LastName' --css resume.css --from markdown --to html -o index.html cv.md
```

## License(s)

This work is forked from [markdown-resume-template](https://github.com/aonemd/markdown-resume-template/tree/gh-pages) by [@aonemd](https://github.com/aonemd) released under [LICENSE](https://github.com/aonemd/markdown-resume-template/blob/master/LICENSE). <br>
This work is released under MIT license.


