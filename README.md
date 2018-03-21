# Application for Lecturer at the UBC Master of Data Science program

**Candidate:** [Leonardo Uieda](http://www.leouieda.com/)

**Position advertisement:** https://www.stat.ubc.ca/lecturer-ubc-master-data-science-program

These are my application documents for the position of Lecturer in the Masters
of Data Science Program of the University of British Columbia, as advertised on
the website of the Department of Statistics.

The documents can be downloaded as individual PDF files or as a single combined file:

**Cover letter and references:** [cover-letter.pdf](https://github.com/leouieda/ubc-lecturer-data-science-application/blob/pdf/cover-letter.pdf)

**Curriculum Vitae:** [curriculum-vitae.pdf](https://github.com/leouieda/ubc-lecturer-data-science-application/blob/pdf/curriculum-vitae.pdf)

**Combined document:** [leonardo_uieda_coverletter_and_cv.pdf](https://github.com/leouieda/ubc-lecturer-data-science-application/blob/pdf/leonardo_uieda_coverletter_and_cv.pdf)


## Build instructions

Documents are typeset in LaTeX using the standard `article` and `letter`
classes.
Running `make` will build the individual PDFs and use `pdfunite` to generate
the combined document.
On Linux and MacOS, use `make show` to open the combined PDF in the default
viewer.
Documents are built automatically on TravisCI and uploaded to the
[pdf branch](https://github.com/leouieda/ubc-lecturer-data-science-application/tree/pdf)
of this repository.

[![Travis CI build status](http://img.shields.io/travis/leouieda/ubc-lecturer-data-science-application/master.svg?style=flat-square&label=build)](https://travis-ci.org/leouieda/ubc-lecturer-data-science-application)

## License

All LaTeX template source code and continuous integration build scripts are
distributed under the
[BSD 3-clause License](https://opensource.org/licenses/BSD-3-Clause).
