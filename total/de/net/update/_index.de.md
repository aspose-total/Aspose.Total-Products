---
title: Aktualisieren Sie Excel-Dateien mit .NET 

description: Bearbeiten Sie Microsoft Excel XLSX-, XLS- und CSV-Dokumente, ohne Microsoft Office mit C# .NET-basierten Anwendungen zu installieren.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Aktualisieren Sie Excel-Dokumente über .NET" h2="Ändern Sie Microsoft Excel XLSX- und XLS-Dateien in .NET-basierten Anwendungen, ohne Microsoft Office<sup>&reg;</sup> zu installieren." >}}

{{% blocks/products/pf/feature-page-summary %}}
Es ist üblich, dass Organisationen ihre in Excel-Dateien gespeicherten Daten wie Studentendaten, Patientenakten und Lagerartikellisten usw. über Unternehmenssoftware aktualisieren. Die [Aspose.Total for .NET](https://products.aspose.com/total/net/)-API bietet die Funktionalität zum Ändern der Tabellenkalkulationen mithilfe der Software. Programmierer können die Software mit Modifikationsfunktionen erweitern, indem sie nur wenige Zeilen API-Code schreiben. Die [Aspose.Cells for .NET](https://products.aspose.com/cells/net/)-API, die Teil des [Aspose.Total for .NET](https://products.aspose.com/total/net/)-Pakets ist, vereinfacht diesen Änderungsprozess. Nachfolgend ist der Vorgang zum Aktualisieren des Excel-Dokuments beschrieben.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Aktualisieren Sie Excel-Dokumente mit .NET" %}}

Die [Aspose.Cells for .NET](https://products.aspose.com/cells/net/)-API stellt eine Workbook-Klasse bereit, die das Laden von Excel-Tabellen verarbeitet. Der Prozess ist einfach. Erstellen Sie das [Workbook](https://reference.aspose.com/cells/net/aspose.cells/workbook/)-Objekt, indem Sie die Quelldatei als Parameter angeben. Greifen Sie auf das relevante Arbeitsblatt zu, indem Sie seinen Index mithilfe der [Worksheets[0].Cells[column]](https://reference.aspose.com/cells/net/aspose.cells/worksheet/cells/)-Methode bereitstellen. Verwenden Sie die [PutValue(data)](https://reference.aspose.com/cells/net/aspose.cells/cell/putvalue/)-Methode, um den Inhalt in der aufgerufenen Zelle zu ändern, und rufen Sie schließlich die save()-Methode auf, um das Dokument zu speichern.

{{% blocks/products/pf/feature-page-code h3=".NET-Code - Excel-Dokumente aktualisieren" %}}

{{< gist "aspose-com-gists" "800f8b626c3129d4682bc58338b93ecc" "update-excel-file-using-net.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Aktualisieren">}}