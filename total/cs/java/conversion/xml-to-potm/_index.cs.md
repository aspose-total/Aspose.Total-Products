---
title: Převeďte XML na POTM přes Java API
description: Java API pro převod XML na POTM bez použití aplikace Microsoft Word
url: /cs/java/conversion/xml-to-potm/
family: total
platformtag: net
feature: conversion
informat: XML
outformat: POTM
otherformats: POTM XAML POWERPOINT POTX OTP PPSX PPTM PPT PPSM PPS SWF POT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API pro export XML do POTM" h2="Export XML do POTM prostřednictvím on premise Java API bez použití Microsoft<sup>&reg;</sup> PowerPoint nebo Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Pomocí [Aspose.Total for Java](https://products.aspose.com/total/java/) můžete snadno převést XML na POTM v jakékoli aplikaci Java J2SE, J2EE, J2ME. Za prvé, pomocí [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), můžete exportovat XML do PPTX. Poté pomocí [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API můžete převést PPTX na POTM.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API pro převod XML na POTM" %}}
1. Otevřete soubor XML pomocí třídy [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Převeďte XML na PPTX pomocí metody [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Načtěte dokument PPTX pomocí třídy [Presentation](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Uložte dokument do formátu POTM pomocí metody [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) a nastavte ` Potm` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Javu můžete snadno používat přímo z projektu založeného na [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) a zahrnují [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) a [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/) ve vašem pom.xml.

Případně můžete získat soubor ZIP z [stažení](https://downloads.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load XML file with an instance of Document class
Document document = new Document("template.xml");
// save XML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Potm format
presentation.save("output.potm", SaveFormat.Potm);   
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Požadavky na převod" %}}
Při načítání formátu souboru XML může být váš dokument chráněn heslem. [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) umožňuje otevírat i zašifrované dokumenty. Chcete-li otevřít zašifrovaný soubor, můžete inicializovat novou instanci [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) a předejte název souboru a heslo jako argumenty.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open XML document
Document doc = new Document("input.xml", "Your@Password");
// save XML as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Otevřete šifrovaný soubor XML přes Java" %}}
Po převodu XML na POTM můžete také přidat předdefinovaný typ pohledu pro vaši prezentaci. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) poskytuje možnost nastavit typ zobrazení pro generovanou prezentaci, když je otevřena v PowerPointu prostřednictvím [ViewProperties](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties). Vlastnost [setLastView](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) se používá k nastavení typu zobrazení pomocí [ViewType](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewType) enumerátor. 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Potm format
presentation.save("output.potm", SaveFormat.Potm);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Další možnosti převodu" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xml-to-pps/" name="XML Na PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xml-to-swf/" name="XML Na SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xml-to-potx/" name="XML Na POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xml-to-ppsx/" name="XML Na PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xml-to-potm/" name="XML Na POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xml-to-ppt/" name="XML Na PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xml-to-ppsm/" name="XML Na PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xml-to-xaml/" name="XML Na XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xml-to-otp/" name="XML Na OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xml-to-pptm/" name="XML Na PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xml-to-pot/" name="XML Na POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/cs/net/conversion/xml-to-powerpoint/" name="XML Na POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}