---
title: C#-API zum Exportieren von MD nach DOT
description: Konvertieren Sie MD in DOT, ohne Microsoft Word zu verwenden
url: /de/net/conversion/md-to-dot/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: DOT
otherformats: FLATOPC WORDML PCL DOT DOTM ODT RTF MHTML OTT MARKDOWN XAMLFLOW DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendern Sie MD über .NET in DOT" h2=".NET-API zum Exportieren von MD nach DOT unter Windows, macOS und Linux, ohne Microsoft Word zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) ist eine leistungsstarke API zum Hinzufügen von Funktionen zur Dokumentbearbeitung und -konvertierung in Ihrer .NET-Anwendung. Durch die Verwendung der erweiterten PDF-Verarbeitungs-API [Aspose.PDF für .NET] (https://products.aspose.com/pdf/net/) können Sie das MD-Dateiformat in DOC konvertieren. Danach können Sie mit der leistungsstarken Dokumentenverarbeitungs-API [Aspose.Words for .NET](https://products.aspose.com/words/net/) DOC in DOT rendern.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C#-API zum Konvertieren von MD in DOT" %}}
1. Öffnen Sie die MD-Datei mit der Klasse [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document).
2. Konvertieren Sie MD mit der Methode [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) in Doc
3. Laden Sie die Doc-Datei mithilfe der Klasse [Document] (https://apireference.aspose.com/words/net/aspose.words/document) von Aspose.Words
4. Speichern Sie das Dokument im DOT-Format mit der Methode [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) und legen Sie Dot als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads] (https://downloads.aspose.com/total/net) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.md");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.dot", SaveFormat.Dot);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Entschlüsseln Sie die MD-Datei mit dem Besitzerkennwort über .NET" %}}
Wenn Sie Ihr Dokument vor der Konvertierung von MD in DOT entschlüsseln möchten, können Sie dies mithilfe der API tun. Um die PDF-Datei zu entschlüsseln, müssen Sie zuerst ein [Dokument](https://apireference.aspose.com/pdf/net/aspose.pdf/document)-Objekt erstellen und das MD mit dem Passwort des Besitzers öffnen. Danach müssen Sie die Methode [Decrypt](https://apireference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) des Document-Objekts aufrufen. Speichern Sie schließlich die aktualisierte Datei mit der Save-Methode des Document-Objekts.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.md", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="ReadOnly DOT-Datei über .NET erstellen" %}}
Um Ihr DOT vor Bearbeitung zu schützen und zu verhindern, dass andere Personen sensible und vertrauliche Informationen in Ihrem Dokument bearbeiten, können Sie den Schutz des Dokuments auch über die API festlegen. Sie können die Bearbeitung eines Dokuments einschränken und nur bestimmte Aktionen damit zulassen. Dies kann mit der [Aspose.Words for .NET](https://products.aspose.com/words/net/)-API erfolgen. Sie können damit steuern, wie Sie den Inhalt mithilfe des Aufzählungsparameters [ProtectionType](https://apireference.aspose.com/words/net/aspose.words/protectiontype) einschränken. Sie können Ihr Dokument mit den folgenden Codezeilen schreibgeschützt machen. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.dot", SaveFormat.Dot);    
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere Konvertierungsoptionen" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/md-to-ott/" name="MD Zu OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/md-to-mhtml/" name="MD Zu MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/md-to-wordml/" name="MD Zu WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/md-to-dot/" name="MD Zu DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/md-to-odt/" name="MD Zu ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/md-to-rtf/" name="MD Zu RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/md-to-ps/" name="MD Zu PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/md-to-flatopc/" name="MD Zu FLAZuPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/md-to-pcl/" name="MD Zu PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/md-to-markdown/" name="MD Zu MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/md-to-xamlflow/" name="MD Zu XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/md-to-dotx/" name="MD Zu DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}