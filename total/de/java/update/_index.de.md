---
title: Aktualisieren Sie Excel-Dateien mit Java 

description: Bearbeiten Sie Microsoft Excel XLSX-, XLS- und CSV-Dokumente, ohne Microsoft Office in Java-basierten Anwendungen zu installieren.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Aktualisieren Sie Excel-Dokumente über Java" h2="Ändern Sie Microsoft Excel XLSX- und XLS-Dateien in Java-basierten Anwendungen, ohne Microsoft Office<sup>&reg;</sup> zu installieren." >}}

{{% blocks/products/pf/feature-page-summary %}}
Es ist üblich, dass Organisationen ihre in Excel-Dateien gespeicherten Daten wie Studentendaten, Patientenakten und Lagerartikellisten usw. über Unternehmenssoftware aktualisieren. [Aspose.Total for Java](https://products.aspose.com/total/java/) API bietet die Funktionalität, die Tabellenkalkulationen mit ihrer eigenen Software zu modifizieren. Programmierer können die Software mit Modifikationsfunktionen erweitern, indem sie nur wenige Zeilen API-Code schreiben. Die [Aspose.Cells for Java](https://products.aspose.com/cells/java/)-API, die Teil des [Aspose.Total for Java](https://products.aspose.com/total/java/)-Pakets ist, vereinfacht diesen Änderungsprozess. Nachfolgend ist der Vorgang zum Aktualisieren des Excel-Dokuments beschrieben.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Aktualisieren Sie Excel-Dokumente mit Java" %}}

Die [Aspose.Cells for Java](https://products.aspose.com/cells/java/)-API stellt eine [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)-Klasse bereit, die das Laden von Excel-Tabellen handhabt. Der Prozess ist einfach. Erstellen Sie das Workbook-Klassenobjekt, indem Sie die Quelldatei als Parameter angeben. Greifen Sie mit der [getWorksheets().get(index).getCells().get(column)](https://reference.aspose.com/cells/java/com.aspose.cells/cells#Item%20(int))-Methode auf das relevante Arbeitsblatt und die relevante Zelle zu. Verwenden Sie die [getCells().get(indexValue).setValue(data)](https://reference.aspose.com/cells/java/com.aspose.cells/cell#Value)-Methode, um den Inhalt in der aufgerufenen Zelle zu ändern, und rufen Sie schließlich die save()-Methode auf, um das Dokument zu speichern.

{{% blocks/products/pf/feature-page-code h3="Java-Code - Excel-Dokumente aktualisieren" %}}

{{< gist "aspose-com-gists" "a9643fb7de748fcd7904675f4f1b2144" "update-excel-file-via-java.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Aktualisieren">}}