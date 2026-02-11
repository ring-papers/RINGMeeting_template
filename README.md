# RINGMeeting_template

Version: Feb 2026

This project contains templates for authors who want to contribute to the RING Meeting.
It contains for both LaTeX, Microsoft Word files, including bst and csl file for reference formating built on top of APA bibliographic styles.
The template also contrains guidelines about good writing practice for scientific papers. 

## Microsoft Word template:
Files are available in the "word" folder.
 * RINGMeeting_template.docx contains the instructions --> copy as My_name_RM_year.docx and start writing :-)
 * DO NOT forget to use the custom citation style: RING.csl. This template can be used for example using Word's Zotero plugin. 

## Latex template:
Files are available in the "latex" folder.
* RING_Paper_Instructions.pdf: This file contains some guidelines for writing RING Papers. 
* YourName_RM_202x.tex.: Please rename to match your name and the year, and start editing. 
 Note that this is the source file used to generate RING_Paper_Instructions.pdf
 It can be compiled with: 
 ```
	pdflatex YourName_RM_202x
	bibtex YourName_RM_202x
	pdflatex YourName_RM_202x
 ```
* my_biblio_file.bib: File to edit to include your bibliographic references in BibTeX format.
* figures: folder where to put figures to be included in the paper.
* ring.cls: Implementation of the LaTeX class for the template. DO NOT EDIT!
* RING.bst: implementation of a the bibliographic style (with apacite) for the conference. DO NOT EDIT!
 
## Slides template:
Templates for presentation slides and posters is provided in the slides folder. Feel free to update the acknowledgements depending on your funding sources / sofwtare / collaborators.
 * RINGMeeting_slides.potx: file to initialize your PowerPoint presentation.
 * RINGPoster.potx: A sample PowerPoint template for an A0 poster. 
