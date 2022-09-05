---
title: Conversion de documents via C++ 
url: /fr/cpp/conversion/
description: Convertissez divers formats de documents tels que Word, Excel, PowerPoint, PDF, JSON, Images et plus encore à l'aide de l'API C++. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Conversion de documents en C++" h2="Convertissez Microsoft<sup>®</sup> Office Word, Excel, PowerPoint, PDF, Images et divers autres formats à l'aide de la bibliothèque C++." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total C++ Library](https://products.aspose.com/total/cpp/) résout le problème de la conversion des documents et les développeurs peuvent automatiser facilement la solution de gestion et de manipulation des documents en intégrant l'API dans les nouvelles applications développées ou dans les applications existantes. Les programmeurs C++ peuvent ajouter des fonctionnalités telles que créer, éditer ou convertir divers documents de format dans leur solution sans dépendre d'aucun logiciel. Peu de cas génériques comme txt en PDF, SVG en PNG, XLSX en CSV, JSON en CSV, Word en PDF, HTML en PDF, on peut facilement convertir. De plus, peu de cas traités par l'API sont répertoriés ci-dessous et peu de liens sont donnés pour les cas de conversion pertinents. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Convertir Microsoft Word en Excel" %}}
L'API Total C++ prend en charge la conversion de Microsoft Word DOC/DOCX vers Excel.  Le processus consiste à charger le fichier Word DOC / DOCX à l'aide de la référence de classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) et à appeler [Enregistrer](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) fonction membre à convertir en HTML d'abord. Ensuite, chargez le document HTML en utilisant la référence de classe [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) et appelez [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e) fonction membre pour enregistrer le document au format Excel. 

{{% blocks/products/pf/feature-page-code h3="C++ - Conversion de Word en Excel" %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt pot-to-doc potm-to-doc potx-to-doc pps-to-doc ppsm-to-doc ppsx-to-doc ppt-to-doc pptm-to-doc pptx-to-doc doc-to-pptx docm-to-pptx docx-to-pptx dot-to-pptx dotm-to-pptx dotx-to-pptx" >}}

{{% blocks/products/pf/feature-page-section  h2="Conversion PDF en Word" %}}
La bibliothèque de conversion C++ prend également en charge la conversion PDF vers word DOC, DOCX et d'autres formats. Considérant le cas du rendu PDF au format RTF, il s'agit d'un processus en deux étapes, d'abord convertir le PDF au format Word DOC/DOCX, puis le rendre au format RTF. Étapes incluses pour cela, chargement du fichier PDF à l'aide de la référence de classe [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) et appel de [Enregistrer](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) fonction membre pour convertir PDF en Word. Maintenant, chargez à nouveau le fichier Word DOC / DOCX en utilisant la référence de classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) de l'API Aspose.Words et enregistrez-le au format RTF à l'aide Fonction membre [Save](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat).

{{% blocks/products/pf/feature-page-code h3="C++ - Conversion PDF en Word" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="odt-to-pptx ott-to-pptx rtf-to-pptx txt-to-pptx word-to-pptx wordml-to-pptx email-to-bmp email-to-word eml-to-xps emlx-to-image msg-to-doc oft-to-pdf cgm-to-doc cgm-to-csv pot-to-csv pdf-to-tsv pdf-to-csv doc-to-csv" >}}

{{% blocks/products/pf/feature-page-section  h2="Convertir JSON en Word" %}}
Pour la conversion JSON, l'API C++ prend en charge diverses combinaisons telles que JSON vers Word, Json vers PowerPoint, Word vers JSON, etc. Considérant le cas de la conversion Word, le processus consiste à lire les données JSON valides du fichier en utilisant un nouvel objet [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook), puis à appeler [Save](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) méthode pour enregistrer JSON en tant que fichier PDF. Alors maintenant, chargez le fichier enregistré à l'aide de la classe [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) et enregistrez-le au format de document Word à l'aide de [Enregistrer](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat).
{{% blocks/products/pf/feature-page-code h3="C++ - Conversion de JSON en Word" %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="flatopc-to-pptx pdf-to-mhtml mhtml-to-csv tex-to-docm xps-to-gif svg-to-mhtml pptx-to-mhtml ps-to-pcl md-to-rtf epub-to-pptm md-to-ppt pdf-to-ppsx svg-to-ods xps-to-excel docx-to-excel odt-to-fods rtf-to-xlsx json-to-ppsx json-to-word word-to-json powerpoint-to-json powerpoint-to-xlsx ppsm-to-json" >}}