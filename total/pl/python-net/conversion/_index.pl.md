---
title: Konwersja dokumentów za pomocą Pythona 
url: /pl/python-net/conversion/
description: Konwertuj formaty Microsoft Word DOC, DOCX na PDF, obrazy i inne, a także slajdy prezentacji, wiadomości e-mail i obrazy 3D tylko kilka linijek kodu Python.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konwersja dokumentów przy użyciu API Pythona" h2="Konwertuj Microsoft<sup>&reg;</sup> Office Word, PDF, obrazy i różne inne formaty za pomocą Aspose.Words for Python via .NET." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Total Python APIs](https://products.aspose.com/total/python-net/) przyspiesza tworzenie od podstaw rozwiązań do automatyzacji dokumentów lub ulepszanie istniejących aplikacji w celu tworzenia, edytowania lub konwertowania dokumentów, prezentacji, e-maili i plików 3D. Python API nie tylko obsługuje slajdy Microsoft Office Word i Presentation, ale także obsługuje pliki PDF, HTML, obrazy i wiadomości e-mail oraz wiele więcej. API nie zależy od żadnego oprogramowania i jest pełnym zestawem rozwiązań do zarządzania i manipulacji dokumentami.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj Microsoft Word na PDF" %}}
Total Python API obsługuje wiele konwersji formatów, takich jak Microsoft Word na PDF, obrazy, Markdown i HTML. API sprawia, że proces konwersji dokumentu Word do formatu PDF jest prosty, a jakość wyjściowa jest tak zbliżona do dokumentu, jak w pliku DOC, DOCX. Proces polega na załadowaniu pliku DOC lub DOCX do obiektu [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) i wywołaniu po prostu [save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) z docelowym formatem PDF wraz ze ścieżką do jego katalogu. To takie proste. W przypadku konieczności określenia standardów PDF, takich jak PDF 1.7 lub 1.5, API zapewnia wyliczenie [PdfComplaince](https://reference.aspose.com/words/python-net/aspose.words.saving/pdfcompliance/) do ustawienia [PdfSaveOptions()](https://reference.aspose.com/words/python-net/aspose.words.saving/pdfsaveoptions/). 

{{% blocks/products/pf/feature-page-code h3="Python — konwersja Worda do PDF" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-word-document-to-pdf-using-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konwersja Microsoft Word do obrazów" %}}
Konwersja Word to Images to jedna z funkcji API Pythona. Oprócz samej konwersji, można łatwo ustawić różne opcje zapisywania, takie jak jasność, kontrast, rozdzielczość pozioma i pionowa itp. Proces polega na załadowaniu dokumentu przez obiekt Dokument, a następnie wywołaniu metody zapisu z żądanym rozszerzeniem pliku obrazu o określonej ścieżce. Aby określić różne opcje zapisywania, API udostępnia [ImageSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/imagesaveoptions/), [FixedPageSaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/fixedpagesaveoptions/) lub [SaveOptions](https://reference.aspose.com/words/python-net/aspose.words.saving/saveoptions/) mogą być używane zgodnie z wymaganym scenariuszem. Poniższy przykładowy kod demonstruje tworzenie podglądu pierwszej strony dokumentu z zastosowaniem kilku dodatkowych ustawień.

{{% blocks/products/pf/feature-page-code h3="Python - konwersja słowa na obraz" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-word-to-images-via-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Konwertuj Microsoft PowerPoint na Word" %}}
Python API obsługuje konwertowanie plików Microsoft PowerPoint PPT / PPTX na pliki Word DOC / DOCX. Dwa interfejsy API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) i [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) użyte do wykonania tej konwersji. Załaduj plik PPT / PPTX za pomocą [Prezentacja](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/). Pobierz obiekt klasy Words Document. Iteruj przez każdy slajd, generuje i wstawia obraz slajdu, a następnie wstawia tekst slajdu, przechodząc przez kształty slajdów.

{{% blocks/products/pf/feature-page-code h3="Python — konwersja slajdów PowerPoint na Word" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-powerpoint-presentation-to-word-via-python.py" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}


{{< blocks/products/pf/feature-page-options pairs="powerpoint-to-word ppsx-to-doc pptx-to-docx ppt-to-docm pot-to-dotx potx-to-dotm potm-to-rtf pptm-to-word pps-to-docx odp-to-doc word-to-powerpoint doc-to-odp dot-to-pps docx-to-ppsm docm-to-pptm dotx-to-potm dotm-to-potx rtf-to-pot wordml-to-pptx odt-to-ppsx ott-to-pps txt-to-powerpoint md-to-ppsm" >}}