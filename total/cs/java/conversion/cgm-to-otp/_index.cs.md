---
title: Převeďte CGM na OTP přes Java API
description: Java API pro převod CGM na OTP bez použití aplikace Microsoft Word
url_ignore: /cs/java/conversion/cgm-to-otp/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: OTP
otherformats: XAML PPSX PPT POWERPOINT PPS SWF POTM OTP PPTM POTX POT PPSM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API pro export CGM do OTP" h2="Export CGM do OTP prostřednictvím on premise Java API bez použití Microsoft<sup>&reg;</sup> PowerPoint nebo Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Pomocí [Aspose.Total for Java](https://products.aspose.com/total/java/) můžete snadno převést CGM na OTP v jakékoli aplikaci Java J2SE, J2EE, J2ME. Za prvé, pomocí [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), můžete exportovat CGM do PPTX. Poté pomocí [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API můžete převést PPTX na OTP.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API pro převod CGM na OTP" %}}
1. Otevřete soubor CGM pomocí třídy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Převeďte CGM na PPTX pomocí metody [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Načtěte dokument PPTX pomocí třídy [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Uložte dokument do formátu OTP pomocí metody [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) a nastavte `OTP` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Javu můžete snadno používat přímo z projektu založeného na [Maven](https://releases.aspose.com/total/java/) a zahrnují [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) a [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/) ve vašem pom.xml.

Případně můžete získat soubor ZIP z [stažení](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "0efeafdb89a8f12c79a55721c524bbf8" "convert-cgm-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Požadavky na převod" %}}
Při načítání formátu souboru CGM může být váš dokument chráněn heslem. [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) umožňuje otevírat i zašifrované dokumenty. Chcete-li otevřít zašifrovaný soubor, můžete inicializovat novou instanci [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) a předejte název souboru a heslo jako argumenty.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open CGM document
Document doc = new Document("input.cgm", "Your@Password");
// save CGM as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Otevřete šifrovaný soubor CGM přes Java" %}}
Po převodu CGM na OTP můžete také přidat předdefinovaný typ pohledu pro vaši prezentaci. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) poskytuje možnost nastavit typ zobrazení pro generovanou prezentaci, když je otevřena v PowerPointu prostřednictvím [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties). Vlastnost [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) se používá k nastavení typu zobrazení pomocí [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) enumerátor. 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Otp format
presentation.save("output.otp", SaveFormat.Otp);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}