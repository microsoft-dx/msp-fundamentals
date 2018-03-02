# Certification creation process for Microsoft Academy

This is to be viewed as a how-to approach for any new certification template that is to be designed for Microsoft Academy

## Design a new template
Unleash your creative self and start by designing, in Photoshop or GIMP, a new template for certifications. We *recommend* taking in consideration the following:
- clearly display the **student's name**, the **course** and the **issue date**
- have ([our](https://github.com/microsoft-dx/msp-fundamentals/blob/master/MicrosoftAcademy/Images/mic-logo.png?raw=true)) the Microsoft Innovation Center logo displayed
- display competencies obtained by following the course
- have it signed by someone important from Microsoft
- display the instructors name

After that, have it exported in any high resolution format, we recommend bitmap.

## Adobe Forms
This feature is available only in Adobe Acrobat so in order for you to create forms you will have to get a hold of a commercial license or download as a trial. The tutorials from [Resources](#resources) are more than enough (and updated) to get you started on understating how Adobe handles forms and how you can create interactive PDFs.

There are several things you have to take into consideration:
- remove any mock text from the template so that you can place the forms
- adjust the **width** and **height** of the imaginary box you place in the Adobe Forms designer as longer names will not be displayed
- make sure the font used has support for any special characters (Cyrillic, Unicode etc.) as special names will not be displayed correctly
- test and test and test :muscle: - seriously !

## Technical aspects
At the time of development of the Moodle plugin for certification automatic generation (2010-2012) this was the only viable solution. If you can come up with an open-source solution that does not require a commercial version of a product you are free to try and let us know :sweat_smile:

The plugin uses the [PDF toolkit](https://www.pdflabs.com/tools/pdftk-the-pdf-toolkit/) to insert student data into the interactive PDF document. You can follow the tutorial from [Resources](#resources) to get more familiar with how it was developed.

## Resources
 1. [Adobe official docs](https://helpx.adobe.com/reader/using/fill-forms.html)
 2. [Creating a PDF file with variables](https://graphicdesign.stackexchange.com/questions/29437/creating-a-pdf-file-with-variables)
 3. [Tutorial on PDFtk](https://www.sitepoint.com/filling-pdf-forms-pdftk-php/)