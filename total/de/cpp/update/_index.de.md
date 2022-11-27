---
title: Aktualisieren Sie Excel-Dateien mit C++ 

description: Bearbeiten Sie Microsoft Excel XLSX-, XLS- und CSV-Dokumente, ohne Microsoft Office mit C++-basierten Anwendungen zu installieren.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Aktualisieren Sie Excel-Dokumente über C++" h2="Ändern Sie Microsoft Excel XLSX- und XLS-Dateien in C++-basierten Anwendungen, ohne Microsoft Office<sup>&reg;</sup> zu installieren." >}}

{{% blocks/products/pf/feature-page-summary %}}
Es ist üblich, dass Organisationen ihre in Excel-Dateien gespeicherten Daten wie Studentendaten, Patientenakten und Lagerartikellisten usw. über Unternehmenssoftware aktualisieren. Die [Aspose.Total for C++](https://products.aspose.com/total/cpp/)-API bietet die Funktionalität zum Ändern der Tabellenkalkulationen mithilfe der Software. Programmierer können die Software mit Modifikationsfunktionen erweitern, indem sie nur wenige Zeilen API-Code schreiben. Die [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/)-API, die Teil des [Aspose.Total for C++](https://products.aspose.com/total/cpp/)-Pakets ist, vereinfacht diesen Änderungsprozess. Nachfolgend ist der Vorgang zum Aktualisieren des Excel-Dokuments beschrieben.
{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Aktualisieren Sie Excel-Dokumente mit C++" %}}

Laden Sie mithilfe der [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/)-API das Quelldokument mithilfe von [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8). Greifen Sie mit GetIWorksheets()->GetObjectByIndex(0) auf [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) und mit GetICells()->GetObjectByIndex auf die erforderliche Zelle zu. Ändern Sie mithilfe der PutValue-Methode den Inhalt in der Zelle, auf die zugegriffen wird. Rufen Sie zuletzt die Methode save() auf, um das Dokument zu speichern.

{{% blocks/products/pf/feature-page-code h3="C++-Code - Excel-Dokumente aktualisieren" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/feature-page-options formats="all" beforeslug="Aktualisieren">}}