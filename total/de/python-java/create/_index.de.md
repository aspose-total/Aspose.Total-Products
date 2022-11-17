---
title: Erstellen und aktualisieren Sie Microsoft Excel-Dateien mit Python 

description: Erstellen Sie Microsoft Excel-Arbeitsblattberichte, ohne Microsoft Office zu installieren 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Erstellen Sie Excel-Berichte mit Python" h2="Erstellen und aktualisieren Sie Microsoft Excel SpreadSheets XLS-, XLSX-Dokumente in Python-Anwendungen, ohne Microsoft Office<sup>&reg;</sup> zu installieren." >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/) ist eine Python-API zum Erstellen, Lesen und Schreiben von Dokumenten in Microsoft Excel-Formaten, einschließlich XLS und XLSX. Diese API ist Teil des [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/)-Pakets. Darüber hinaus können Entwickler problemlos Code zum Einfügen von Daten, Bildern, Diagrammen, Pivot-Tabellen in Arbeitsblätter und viele andere Funktionen schreiben. Die Python-API unterstützt auch Funktionen wie das Festlegen verschiedener [Formeln](https://docs.aspose.com/cells/python-java/supported-formula-functions/), das Konvertieren von Text in Spalten, intelligente Markierungen und dynamische Formeloptionen. Nachfolgend finden Sie einige Beispielcodes zum Erstellen und Ändern von Tabellenkalkulationen.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="So erstellen Sie Excel-Dateien mit Python" %}}

Die [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/)-API stellt eine Workbook-Klasse bereit, die die Erstellung von Dateien handhabt. Der Prozess ist einfach. Erstellen Sie das Workbook-Klassenobjekt und greifen Sie auf das relevante Worksheet zu, indem Sie seinen Index angeben. Verwenden Sie die putValue-Methode, um den Inhalt in die aufgerufene Zelle einzufügen, und rufen Sie schließlich die save()-Methode auf, um das Dokument mit einem bestimmten Namen zu speichern.

{{% blocks/products/pf/feature-page-code h3="Code 1 - Erstellen Sie eine einfache Excel-Datei" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "create-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% blocks/products/pf/feature-page-code h3="Code 2 - Bilder in Microsoft Excel-Dokumente einfügen" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "create-excel-file-with-image.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="So aktualisieren Sie Microsoft Excel-Dateien mit Python" %}}

Der Prozess zum Erstellen und Aktualisieren der Excel-Datei ist bis auf den einzigen Unterschied fast gleich. Der Unterschied besteht darin, dass während des Erstellungsprozesses ein leeres Arbeitsmappenobjekt erstellt wird, während während des Aktualisierungsprozesses eine vorhandene Excel-Datei benötigt wird. Übergeben Sie also die vorhandene Datei als Parameter an die Workbook-Klasse. Rest das Verfahren ist das gleiche

{{% blocks/products/pf/feature-page-code h3="Code 3 – Microsoft Excel-Dokumente aktualisieren" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}