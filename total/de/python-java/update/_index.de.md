---
title: Aktualisieren Sie Excel-Dateien mit Python 

description: Bearbeiten Sie Microsoft Excel XLSX-, XLS- und CSV-Dokumente, ohne Microsoft Office in Python-Anwendungen zu installieren
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Aktualisieren Sie Excel-Dokumente über Python" h2="Ändern Sie Microsoft Excel XLSX- und XLS-Dateien in Python-Anwendungen, ohne Microsoft Office<sup>&reg;</sup> zu installieren." >}}

{{% blocks/products/pf/feature-page-summary %}}
Es ist üblich, dass Organisationen ihre in Excel-Dateien gespeicherten Daten wie Studentendaten, Patientenakten und Lagerartikellisten usw. über Unternehmenssoftware aktualisieren. [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/) API bietet die Funktionalität, die Tabellenkalkulationen über die Software zu modifizieren. Programmierer können die Software mit den Modifikationsfunktionen erweitern, indem sie die API integrieren und wenige Codezeilen schreiben. Die [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/)-API, die Teil des [Aspose.Total for Python via Java](https://products.aspose.com/total/python-java/)-Pakets ist, vereinfacht diesen Änderungsprozess. Nachfolgend ist der Vorgang zum Aktualisieren des Excel-Dokuments beschrieben.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Aktualisieren Sie Excel-Dokumente mit Python" %}}

Die [Aspose.Cells for Python via Java](https://products.aspose.com/cells/python-java/)-API stellt eine Workbook-Klasse bereit, die das Laden von Excel-Tabellen verarbeitet. Der Prozess ist einfach. Erstellen Sie das [Workbook](https://reference.aspose.com/cells/python-java/asposecells.api/Workbook)-Klassenobjekt, indem Sie die Quelldatei als Parameter angeben. Verwenden Sie die [getWorksheets().get(index)](https://reference.aspose.com/cells/python/asposecells.api/workbook#Worksheets)-Methode, um auf das relevante Arbeitsblatt zuzugreifen, indem Sie dessen Index angeben. Rufen Sie die [Worksheet.getCells().get(indexValue).putValue()](https://reference.aspose.com/cells/python/asposecells.api/worksheet#Cells)-Methode auf, um den Inhalt in der aufgerufenen Zelle zu ändern, und rufen Sie schließlich die save()-Methode auf, um das Dokument zu speichern.

{{% blocks/products/pf/feature-page-code h3="Python - Excel-Dokumente aktualisieren" %}}

{{< gist "aspose-com-gists" "f16dc7586917c051564eaebbb159c63f" "update-excel-file.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Aktualisieren">}}