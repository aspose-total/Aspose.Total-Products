---
title: C#-API zum Exportieren von CGM nach DOCM
description: Konvertieren Sie CGM in DOCM, ohne Microsoft Word zu verwenden
url_ignore: /de/net/conversion/cgm-to-docm/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: DOCM
otherformats: OTT MHTML WORDML DOT ODT RTF PS FLATOPC PCL MARKDOWN XAMLFLOW DOTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Rendern Sie CGM über .NET in DOCM" h2=".NET-API zum Exportieren von CGM nach DOCM unter Windows, macOS und Linux, ohne Microsoft Word zu verwenden" >}}

{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for .NET](https://products.aspose.com/total/net/) ist eine leistungsstarke API zum Hinzufügen von Funktionen zur Dokumentbearbeitung und -konvertierung in Ihrer .NET-Anwendung. Durch die Verwendung der erweiterten PDF-Verarbeitungs-API [Aspose.PDF für .NET](https://products.aspose.com/pdf/net/) können Sie das CGM-Dateiformat in DOC konvertieren. Danach können Sie mit der leistungsstarken Dokumentenverarbeitungs-API [Aspose.Words for .NET](https://products.aspose.com/words/net/) DOC in DOCM rendern.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C#-API zum Konvertieren von CGM in DOCM" %}}
1. Öffnen Sie die CGM-Datei mit der Klasse [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document).
2. Konvertieren Sie CGM mit der Methode [Save](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) in Doc
3. Laden Sie die Doc-Datei mithilfe der Klasse [Document](https://reference.aspose.com/words/net/aspose.words/document) von Aspose.Words
4. Speichern Sie das Dokument im DOCM-Format mit der Methode [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) und legen Sie Docm als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total``` oder über die Package Manager Console von Visual Studio mit ```Install-Package Aspose.Total```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://releases.aspose.com/total/net) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "convert-cgm-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Entschlüsseln Sie die CGM-Datei mit dem Besitzerkennwort über .NET" %}}
Wenn Sie Ihr Dokument vor der Konvertierung von CGM in DOCM entschlüsseln möchten, können Sie dies mithilfe der API tun. Um die PDF-Datei zu entschlüsseln, müssen Sie zuerst ein [Dokument](https://reference.aspose.com/pdf/net/aspose.pdf/document)-Objekt erstellen und das CGM mit dem Passwort des Besitzers öffnen. Danach müssen Sie die Methode [Decrypt](https://reference.aspose.com/pdf/net/aspose.pdf/document/methods/decrypt) des Document-Objekts aufrufen. Speichern Sie schließlich die aktualisierte Datei mit der Save-Methode des Document-Objekts.  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "96edf7f9c1335b3ced21f24a1efa17cc" "decrypt-cgm-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="ReadOnly DOCM-Datei über .NET erstellen" %}}
Um Ihr DOCM vor Bearbeitung zu schützen und zu verhindern, dass andere Personen sensible und vertrauliche Informationen in Ihrem Dokument bearbeiten, können Sie den Schutz des Document auch über die API festlegen. Sie können die Bearbeitung eines Document einschränken und nur bestimmte Aktionen damit zulassen. Dies kann mit der [Aspose.Words for .NET](https://products.aspose.com/words/net/)-API erfolgen. Sie können damit steuern, wie Sie den Inhalt mithilfe des Aufzählungsparameters [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) einschränken. Sie können Ihr Dokument mit den folgenden Codezeilen schreibgeschützt machen. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("input.doc");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.docm", SaveFormat.Docm);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="CGM-Dateien programmgesteuert in DOCM umwandeln: Anwendungsfälle" %}}
Die Konversion von Dateien im CGM-Format in DOCM-Dateiformate ist notwendig, um die volle Potenz deiner Dokumentbearbeitung und Zusammenarbeitsfähigkeiten freizusetzen. Diese Konversion ermöglicht dir:

**Benutzerfallsbeispiele:**

*   **Zusammenarbeitsbare Dokumentbearbeitung**: Konvertiere CGM-Dateien, um bearbarke Dokumente zu erstellen, mit Teammitgliedern zusammenzuarbeiten und Änderungen in Echtzeit zu verfolgen.
*   **Intelligente Dokumentverwaltung**: Verwende DOCM, um Sicherheitssetzungen anzuwenden, die Bearbeitungsberechte eingeschränken und den Dokumentintegrität bewahren.
*   **Professionelle-Graden-Dokumentdesign**: Konvertiere CGM-Dateien, um visuell ansprechende Dokumente zu erstellen, multimediale Inhalte hinzufügen und die Leserengagement zu erhöhen.
*   **Gesetzeskonformes Berichterstellen**: Verwende DOCM, um Berichte zu erzeugen, die den gesetzlichen Anforderungen entsprechen, Änderungen verfolgen und eine Prüfung durchführen.
*   **Integration mit Microsoft Office-Tools**: Konvertiere CGM-Dateien, um sich optimal mit anderen Microsoft Office-Tools wie Word, Excel und PowerPoint zu integrieren.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}