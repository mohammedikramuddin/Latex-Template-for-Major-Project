# RVCE-Latex-Project-Report-Template modified by ikram
This is a Latex template is only for RV College of Engineering students for their report writing in latex. You can use this template for both UG and PG mini/major project report writing in Latex.

The template, by defalut generates UG main project.

## For PG project report, uncomment the following command in `Main.tex` file

```
 %\pgProgram%
```

This will automatically takes in the values specified in the commands given below, for PG: 
```
 \MastersIn[M.Tech]{Master of Technology} 
 \pgProgramName{VLSI Design & Embedded Systems}
```
>> Note: `\MastersIn` command has 2 fields, where the field inside `[]` is used for specifying the shorter form of the type of master you are studying and is used inside the document for processing. So do specify this value for generating successful report.

## For mini project generation, uncomment the following command in "Main.tex" file
```
 %\MinorProject
```
## To add Appendix chapter
Uncomment the following lines in "Main.tex" file
```
%\appendix
%\input{./Appendix/Apndx}%Appendix Chapter 1
```
Add contents to ``Apndx.tex`` file under `Appendix` folder

---
>Use the youtube play list to know how to use this template: https://youtube.com/playlist?list=PLXnaDu1KFWvaIh-jh9ME8mp5ca-PEtch4
---

# Readme(ikram)
## Installation of Latex
1) Install 'MiKTeX' compiler
2) Install 'TexMaker/Texstudio' editor

## Table Generator
Open website https://www.tablesgenerator.com/ and create your table and copy the latex code and paste in your TexMaker editor.

'''
To make latex code of tablegenerator to work, do the following
1) Download Booktabs package from http://mirrors.ctan.org/macros/latex/contrib/booktabs.zip
2) unzip the package and paste the 'booktabs' folder in the path C:\Program Files\MiKTeX\tex\latex
'''


## Adding References to ProjectBib.bib

1) Open google scholar
2) type 'title of the reference paper you need to add' in the search bar
3) click 'cite'
4) click 'BibTeX'
5) copy the code and paste in ProjectBib.bib file


## How to make Bibliography visible in pdf.

1) RUN PDFLateX
2) RUN BibTeX
3) RUN PDFLateX
4) RUN PDFLateX
5) RUN viewpdf
6) RUN QuickBuild
