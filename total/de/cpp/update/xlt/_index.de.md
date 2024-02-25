---
title: Aktualisieren Sie die XLT-Datei mit C++
description: Ändern Sie XLT-Dokumente in C++-Anwendungen, ohne Microsoft Excel zu verwenden.
family: total
platformtag: C++
feature: update
informat: XLT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Aktualisieren Sie die XLT-Datei über C++" h2="Ändern Sie XLT-Tabellen über Ihre C++-basierten Anwendungen, ohne Microsoft Office<sup>&reg;</sup> zu installieren." >}}

{{% blocks/products/pf/feature-page-summary %}}

Für einen Programmierer, der versucht, XLT-Dateien in einer C++-Anwendung zu aktualisieren, [Aspose.Total for C++](https://products.aspose.com/total/cpp/) API kann helfen, den Aktualisierungsprozess zu automatisieren. Es ist ein vollständiges Paket verschiedener C++-Bibliotheken, die mehrere Formate verarbeiten, einschließlich Microsoft Excel-Dokumente. Die [Aspose.Cells for C++](https://products.aspose.com/cells/cpp/)-API, die Teil des [Aspose.Total for C++](https://products.aspose.com/total/cpp/)-Pakets ist, vereinfacht diesen Änderungsprozess. Der Vorgang zum Aktualisieren des XLT-Dokuments ist einfach, indem Sie zuerst auf das Blatt zugreifen und dann den Zellenwert in Excel mit C++ aktualisieren.

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="So aktualisieren Sie die XLT-Datei in C++" %}}

- Laden Sie die XLT-Datei mit [CreateIWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory#a93f7282b976d2a001d44198dedaceee8)
- Zugriff auf relevantes [Worksheet](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_worksheet) unter Verwendung von GetIWorksheets()->GetObjectByIndex(0) und relevanter Zelle unter Verwendung von GetICells()->GetObjectByIndex
- Fügen Sie mithilfe der PutValue-Methode neue Daten in die Zelle ein, auf die zugegriffen wurde
- Speichern Sie die Datei als .xlt-Datei mit der Save-Methode, indem Sie die Datei mit dem Pfad als Parameter übergeben

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Änderungsanforderungen" %}}

- Für XLT-Modifikation nach [System Anforderungen](https://docs.aspose.com/cells/cpp/system-requirements/) für Windows- und Linux-Systeme 
- Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total.Cpp```
- Oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total.Cpp```
- Holen Sie sich alternativ das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [Downloads](https://releases.aspose.com/cells/cpp)

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Code - XLT-Datei in C++ aktualisieren" offSpacer="" %}}

{{< gist "aspose-com-gists" "42342f602044f852ec65704204e5d54a" "update-excel-documents.cpp" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}