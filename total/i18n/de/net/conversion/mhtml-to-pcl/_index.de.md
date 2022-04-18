---
title: C#-API zum Exportieren von MHTML nach PCL
description: Konvertieren Sie MHTML in PCL, ohne Microsoft Word zu verwenden
url: /de/net/conversion/mhtml-to-pcl/
family: total
platformtag: net
feature: conversion
informat: MHTML
outformat: PCL
otherformats: XAMLFLOW ODT OTT WORDML FLATOPC DOT PS PCL MARKDOWN RTF DOTX DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendern Sie MHTML über .NET in PCL" h2=".NET-API zum Exportieren von MHTML nach PCL unter Windows, macOS und Linux, ohne Microsoft Word zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) ist eine leistungsstarke API zum Hinzufügen von Funktionen zur Dokumentbearbeitung und -konvertierung in Ihrer .NET-Anwendung. Durch die Verwendung der erweiterten PDF-Verarbeitungs-API [Aspose.PDF für .NET] (https://products.aspose.com/pdf/net/) können Sie das MHTML-Dateiformat in DOC konvertieren. Danach können Sie mit der leistungsstarken Dokumentenverarbeitungs-API [Aspose.Words for .NET](https://products.aspose.com/words/net/) DOC in PCL rendern.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C#-API zum Konvertieren von MHTML in PCL" %}}
1. Öffnen Sie die MHTML-Datei mit der Klasse [Document](https://apireference.aspose.com/pdf/net/aspose.pdf/document).
2. Konvertieren Sie MHTML mit der Methode [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) in Doc
3. Laden Sie die Doc-Datei mithilfe der Klasse [Document] (https://apireference.aspose.com/words/net/aspose.words/document) von Aspose.Words
4. Speichern Sie das Dokument im PCL-Format mit der Methode [Save](https://apireference.aspose.com/words/net/aspose.words.document/save/methods/4) und legen Sie Pcl als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads] (https://downloads.aspose.com/total/net) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("template.mhtml");
 
document.Save("DocOutput.doc", SaveFormat.Doc); 

var outputDocument = new Aspose.Words.Document("DocOutput.doc");

outputDocument.Save("output.pcl", SaveFormat.Pcl);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Entschlüsseln Sie die MHTML-Datei mit dem Besitzerkennwort über .NET" %}}
Wenn Sie Ihr Dokument vor der Konvertierung von MHTML in PCL entschlüsseln möchten, können Sie dies mithilfe der API tun. Um die PDF-Datei zu entschlüsseln, müssen Sie zuerst ein [Dokument](https://apireference.aspose.com/pdf/net/aspose.pdf/document)-Objekt erstellen und das MHTML mit dem Passwort des Besitzers öffnen. Danach müssen Sie die Methode [Decrypt](https://apireference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) des Document-Objekts aufrufen. Speichern Sie schließlich die aktualisierte Datei mit der Save-Methode des Document-Objekts.  
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("Decrypt.mhtml", "password");

document.Decrypt();
 
document.Save("Decrypt_out.doc");
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="ReadOnly PCL-Datei über .NET erstellen" %}}
Um Ihr PCL vor Bearbeitung zu schützen und zu verhindern, dass andere Personen sensible und vertrauliche Informationen in Ihrem Dokument bearbeiten, können Sie den Schutz des Dokuments auch über die API festlegen. Sie können die Bearbeitung eines Dokuments einschränken und nur bestimmte Aktionen damit zulassen. Dies kann mit der [Aspose.Words for .NET](https://products.aspose.com/words/net/)-API erfolgen. Sie können damit steuern, wie Sie den Inhalt mithilfe des Aufzählungsparameters [ProtectionType](https://apireference.aspose.com/words/net/aspose.words/protectiontype) einschränken. Sie können Ihr Dokument mit den folgenden Codezeilen schreibgeschützt machen. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.pcl", SaveFormat.Pcl);    
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Andere Konvertierungsoptionen" subTitle="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/mhtml-to-ott/" name="MHTML Zu OTT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/mhtml-to-mhtml/" name="MHTML Zu MHTML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/mhtml-to-wordml/" name="MHTML Zu WORDML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/mhtml-to-dot/" name="MHTML Zu DOT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/mhtml-to-odt/" name="MHTML Zu ODT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/mhtml-to-rtf/" name="MHTML Zu RTF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/mhtml-to-ps/" name="MHTML Zu PS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/mhtml-to-flatopc/" name="MHTML Zu FLAZuPC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/mhtml-to-pcl/" name="MHTML Zu PCL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/mhtml-to-markdown/" name="MHTML Zu MARKDOWN" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/mhtml-to-xamlflow/" name="MHTML Zu XAMLFLOW" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/de/net/conversion/mhtml-to-dotx/" name="MHTML Zu DOTX" description="" >}}



{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}