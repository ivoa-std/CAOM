# CAOM
## Common Archive Observation Model

The draft version is CAOM-2.5:
[![PDF-Preview](https://img.shields.io/badge/Preview-PDF-blue)](../../releases/download/auto-pdf-preview/CAOM-draft.pdf)

The version of CAOM in use in the community (not an IVOA standard) is CAOM-2.4: 
<a href="http://www.opencadc.org/caom2/">https://www.opencadc.org/caom2/</a>. Previous
non-IVOA standard versions of the VO-DML specification remain in the `src`.

## VO-DML Usage
This module contains a <a href="http://www.ivoa.net/documents/VODML/index.html">VO-DML</a> 
description of the CAOM data model and test code to validate the model using the 
<a href="https://github.com/opencadc/core/tree/master/cadc-vodml">cadc-vodml</a> tools. The model
is currently defined using the VO-DML-1.0 recommendation.

The VO-DML validation requires gradle (6.8 to 8.x). To run the tests locally: `grade test`.

VO-DML source files are in `src/main/resources`.

## UML Diagrams
UML diagrams are created and maintained manually using 
<a href="https://argouml-tigris-org.github.io/tigris/argouml/">ArgoUML</a>.

The UML project file and exported images are in `src/uml`.

## License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">
<img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a>
<br />The Common Archive Observation Model is licensed under the
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">
Creative Commons Attribution-ShareAlike 4.0 International License</a>.
