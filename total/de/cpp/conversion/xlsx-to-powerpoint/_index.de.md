---
title: Konvertieren Sie XLSX in POWERPOINT mit C++ oder mit dem kostenlosen Online Converter
description: Konvertieren Sie XLSX in POWERPOINT innerhalb von C++-Anwendungen oder online. Testen Sie schnell den kostenlosen CSV-zu-DOC-Online-Konverter, bevor Sie den Code integrieren.

family: total
platformtag: cpp
feature: conversion
informat: XLSX
outformat: POWERPOINT
otherformats: PPTX DOCX DOC WORD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Konvertieren Sie XLSX über C++ in POWERPOINT oder online" h2="Excel exportieren&reg; XLSX zu POWERPOINT innerhalb voll funktionsfähiger C++-Anwendungen" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="XLSX-zu-POWERPOINT-Konvertierung in C++" %}}
1. Öffnen Sie die XLSX-Datei mit der Member-Funktion [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) von [Factory](https://reference.aspose.com/cells/cpp/class/aspose.cells.factory) Klassenreferenz
2. Konvertieren Sie XLSX in PDF und setzen Sie SaveFormat auf Pdf
3. Laden Sie die konvertierte PDF-Datei mithilfe der Klassenreferenz [Powerpointument](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.powerpointument).
4. Speichern Sie das Dokument im POWERPOINT-Format mit der Member-Funktion [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.powerpointument#a6383c010776212483f51cc41235924db) und legen Sie Powerpoint als SaveFormat fest
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Konvertierungsanforderungen" %}}
Installieren Sie von der Befehlszeile als ```nuget install Aspose.Total.Cpp``` oder über die Paket-Manager-Konsole von Visual Studio mit ```Install-Package Aspose.Total.Cpp```.

Alternativ können Sie das Offline-MSI-Installationsprogramm oder DLLs in einer ZIP-Datei von [downloads](https://releases.aspose.com/total/cpp) herunterladen.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLSX file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xlsx");
// save XLSX as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Powerpointument class reference
auto powerpoint = MakeObject<Powerpointument>(u"pdfOutput.pdf");
// save powerpointument in PPTX format
powerpoint->Save(u"convertedFile.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>Online-Konverter für XLSX zu POWERPOINT</h3>

<iframe title="pptx bis xlsx Online-Tool" style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=pptx&from=xlsx" id="child-iframe" width="80%"></iframe>
<p style="font-size:1.3rem;color:#3d8ec4;font-weight:400"><a href="https://products.aspose.app/total/xlsx-to-pptx/">Testen Sie unsere kostenlose App für die Konvertierung von XLSX in POWERPOINT</a></p>
</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="FAQs" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>Häufig gestellte Fragen</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Wie kann ich XLSX in POWERPOINT Online konvertieren?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Die Online-App für die XLSX-Konvertierung ist oben integriert. Um den XLSX-zu-POWERPOINT-Konvertierungsprozess zu starten, fügen Sie einfach Ihre XLSX-Datei hinzu, indem Sie sie per Drag & Drop in den dafür vorgesehenen Bereich ziehen oder in das weiße Feld klicken, um die Datei zu importieren. Sobald die Datei importiert ist, klicken Sie auf die Schaltfläche „Konvertieren“, um den Konvertierungsprozess zu starten. Nachdem die XLSX-zu-POWERPOINT-Konvertierung abgeschlossen ist, können Sie Ihre neu konvertierte POWERPOINT-Datei sofort mit nur einem Klick herunterladen.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Wie lange dauert die Konvertierung von XLSX?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Die Geschwindigkeit dieses Online-Konverters hängt stark von der Größe der XLSX-Datei ab. Kleinere XLSX-Dateien können in wenigen Sekunden in POWERPOINT konvertiert werden. Darüber hinaus hängt die Effizienz des Konvertierungsprozesses davon ab, wie Sie Ihre Anwendung optimiert haben, wenn Sie den Konvertierungscode in eine C++-Anwendung integriert haben.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Ist es sicher, XLSX mit dem kostenlosen Aspose.Total-Konverter in POWERPOINT umzuwandeln?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Natürlich! Nachdem die XLSX-zu-POWERPOINT-Konvertierung abgeschlossen ist, können Sie Ihre konvertierte Datei sofort über einen bereitgestellten Download-Link herunterladen. Wir löschen hochgeladene Dateien nach 24 Stunden und die Download-Links funktionieren nach diesem Zeitraum nicht mehr. Sie können sicher sein, dass die Dateikonvertierung, einschließlich XLSX, absolut sicher ist, da niemand Zugriff auf Ihre Dateien hat. Die kostenlose App wurde oben zu Testzwecken integriert, sodass Sie die Ergebnisse überprüfen können, bevor Sie den Code integrieren.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>Welchen Browser sollte ich verwenden, um XLSX zu konvertieren?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Sie können auf diesen Online-Konverter mit jedem modernen Webbrowser wie Google Chrome, Firefox, Opera oder Safari zugreifen. Wenn Sie jedoch an einer Desktop-Anwendung arbeiten, bietet die Aspose.Total XLSX Conversion API eine reibungslose Lösung.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}