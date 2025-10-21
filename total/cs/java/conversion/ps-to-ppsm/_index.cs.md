---
title: Převeďte PS na PPSM přes Java API
description: Java API pro převod PS na PPSM bez použití aplikace Microsoft Word
url_ignore: /cs/java/conversion/ps-to-ppsm/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: PPSM
otherformats: PPS PPSX XAML POWERPOINT POT PPSM POTX PPTM OTP POTM SWF PPT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java API pro export PS do PPSM" h2="Export PS do PPSM prostřednictvím on premise Java API bez použití Microsoft<sup>&reg;</sup> PowerPoint nebo Adobe<sup>&reg;</sup> Acrobat Reader" >}}
{{% blocks/products/pf/feature-page-summary %}}
Pomocí [Aspose.Total for Java](https://products.aspose.com/total/java/) můžete snadno převést PS na PPSM v jakékoli aplikaci Java J2SE, J2EE, J2ME. Za prvé, pomocí [Aspose.PDF for Java](https://products.aspose.com/pdf/java/), můžete exportovat PS do PPTX. Poté pomocí [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API můžete převést PPTX na PPSM.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java API pro převod PS na PPSM" %}}
1. Otevřete soubor PS pomocí třídy [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Převeďte PS na PPTX pomocí metody [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-)
3. Načtěte dokument PPTX pomocí třídy [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation)
4. Uložte dokument do formátu PPSM pomocí metody [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) a nastavte ` Ppsm` jako SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Požadavky na převod" %}}
Aspose.Total pro Javu můžete snadno používat přímo z projektu založeného na [Maven](https://releases.aspose.com/total/java/) a zahrnují [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) a [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/) ve vašem pom.xml.

Případně můžete získat soubor ZIP z [stažení](https://releases.aspose.comtotal/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "f5707d58ebee8d2889c8dbe5aa739d87" "convert-ps-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Požadavky na převod" %}}
Při načítání formátu souboru PS může být váš dokument chráněn heslem. [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) umožňuje otevírat i zašifrované dokumenty. Chcete-li otevřít zašifrovaný soubor, můžete inicializovat novou instanci [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) a předejte název souboru a heslo jako argumenty.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open PS document
Document doc = new Document("input.ps", "Your@Password");
// save PS as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Otevřete šifrovaný soubor PS přes Java" %}}
Po převodu PS na PPSM můžete také přidat předdefinovaný typ pohledu pro vaši prezentaci. [Aspose.Slides for Java](https://products.aspose.com/slides/java/) poskytuje možnost nastavit typ zobrazení pro generovanou prezentaci, když je otevřena v PowerPointu prostřednictvím [ViewProperties](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties). Vlastnost [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) se používá k nastavení typu zobrazení pomocí [ViewType](https://reference.aspose.com/slides/java/com.aspose.slides/ViewType) enumerátor. 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Ppsm format
presentation.save("output.ppsm", SaveFormat.Ppsm);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}

Převádění souborů PS (PostScript) na PPSM (PowerPoint Macro-Enabled Show) umožňuje interaktivní a automatizované prezentace. PPSM zachovává makra vložená do snímků pro dynamické chování, jako jsou aktualizace dat nebo interaktivní grafy.

{{% blocks/products/pf/agp/feature-section-col title="Klíčové použití" %}}

* Vytváření interaktivních, makro-povolených prezentací z diagramů PS.
* Automatizace aktualizací snímků řízených daty v klientech nebo školeních.
* Vkládání PostScriptových grafů a diagramů do dynamických prezentací.
* Standardizace interaktivních šablon prezentací pro firemní použití.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Automatizační scénáře" %}}

* Hromadná konverze PS na PPSM pro firemní automatizační pracovní postupy.
* Integrace s analytickými a reportingovými platformami pro dynamické aktualizace snímků.
* Plánovaná konverze PS zpráv do makro-povolených show.
* AI-asistované vkládání maker pro interaktivní chování snímků.

{{% /blocks/products/pf/agp/feature-section-col %}}
{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}