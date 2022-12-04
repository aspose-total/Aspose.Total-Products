---
title: Konvertieren Sie DOT in FODS mit Python
description: Konvertierung von DOT in FODS in Ihren Python-Anwendungen ohne Verwendung von Microsoft Word oder Excel 

family: total
platformtag: Python
feature: conversion
informat: DOT
outformat: FODS
otherformats: Excel XLS XLSX CSV DIF FODS ODS SXC TSV XLAM XLSB XLT XLTM XLSM XLTX

---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertieren Sie DOT über Python in FODS" h2="Konvertierung von DOT in FODS in Ihren Python-Anwendungen ohne Installation von Microsoft Word<sup>&reg;</sup> oder Excel" >}}

{{% blocks/products/pf/feature-page-summary %}}

Für einen Python-Entwickler, der versucht, eine DOT-zu-FODS-Konvertierungsfunktion in der Anwendung hinzuzufügen. [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API kann helfen, den Konvertierungsprozess zu automatisieren. Es ist ein vollständiges Paket verschiedener APIs, die unterschiedliche Formate verarbeiten.

Es ist hauptsächlich in zwei Schritten. Verwenden Sie zunächst die [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/)-API, um die DOT-Datei in HTML zu konvertieren. Speichern Sie danach mit der Excel-Python-API [Aspose.Cells for Python via .NET](https://products.aspose.com/cells/python-net/) den erstellten HTML-Code im gewünschten Microsoft Excel-Format. 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="So konvertieren Sie DOT in FODS in Python" %}}
- **Schritt 1** Öffnen Sie die Quell-DOT-Datei mit der [Document](https://reference.aspose.com/words/python-net/aspose.words/document/)-Klasse
- Speichern Sie die DOT-Datei in HTML mit der [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/)-Methode, indem Sie den Dateinamen und den gewünschten Verzeichnispfad angeben
-  **Schritt 2** Laden Sie die HTML-Datei mit einer Instanz der Workbook-Klasse mit file und LoadOptions als Parameter
-  Rufen Sie die `save`-Methode auf, während Sie den Ausgabe-FODS-Dateipfad angeben. Ihre DOT-Datei wird also unter dem angegebenen Pfad in FODS konvertiert

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}

- Für die Konvertierung von DOT in FODS ist Python 3.5 oder höher erforderlich
- Referenz-APIs innerhalb des Projekts direkt von PyPI ([Aspose.Words](https://pypi.org/project/aspose-words/) und [Aspose.Cells](https://pypi.org/project/aspose-cells-python/))
-  Oder verwenden Sie die folgenden Pip-Befehle ```pip install aspose.words``` und ```pip install aspose-cells-python``` 
-  Darüber hinaus überprüfen Microsoft Windows- oder Linux-basierte Betriebssysteme (siehe mehr für [Words](https://docs.aspose.com/words/python-net/system-requirements/) und [Cells](https://docs.aspose.com/cells/python-net/getting-started/#installation)) und für Linux die zusätzlichen Anforderungen für gcc und libpython und folgen [Schritt für Schritt Anweisungen](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Speichern Sie DOT in HTML in Python – Schritt 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-microsoft-word-documents-to-html-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="HTML als FODS in Python speichern – Schritt 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "ac76f428602a8791ecc4f957e2309bb6" "convert-html-files-to-excel-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}