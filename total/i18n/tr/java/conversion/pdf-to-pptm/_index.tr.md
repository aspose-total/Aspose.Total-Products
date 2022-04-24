---
title: Java API aracılığıyla PDF'yi PPTM'ye dönüştürün
description: Microsoft Word kullanmadan PDF'yi PPTM'ye dönüştürmek için Java API
url: /tr/java/conversion/pdf-to-pptm/
family: total
platformtag: net
feature: conversion
informat: PDF
outformat: PPTM
otherformats: PPSX OTP PPS PPTM XAML POTX PPSM POTM PPT SWF POT POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="PDF'yi PPTM'ye Aktarmak için Java API" h2="Microsoft<sup>&reg;</sup> PowerPoint veya Adobe<sup>&reg;</sup> Acrobat Reader kullanmadan şirket içi Java API aracılığıyla PDF'yi PPTM'ye aktarın" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) kullanarak herhangi bir Java J2SE, J2EE, J2ME uygulamasında PDF'yi PPTM'ye kolayca dönüştürebilirsiniz. İlk olarak, [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) kullanarak PDF'yi PPTX'e aktarabilirsiniz. Bundan sonra, [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API'yi kullanarak PPTX'i PPTM'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="PDF'yi PPTM'ye Dönüştürmek için Java API" %}}
1. [Document](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document) sınıfını kullanarak PDF dosyasını açın
2. [save](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) yöntemini kullanarak PDF'yi PPTX'e dönüştürün
3. [Sunum](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation) sınıfını kullanarak PPTX belgesini yükleyin
4. [save](https://apireference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) yöntemini kullanarak belgeyi PPTM biçiminde kaydedin ve ` Pptm` SaveFormat olarak
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Java'yı doğrudan [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose/aspose-total) tabanlı bir projeden kolayca kullanabilirsiniz. ve [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) ve [Aspose.Slides for Java](https://docs.aspose.com/slides/java/) içerir kurulum/) pom.xml dosyanızda.

Alternatif olarak, [indirilenler](https://downloads.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

```java
// load PDF file with an instance of Document class
Document document = new Document("template.pdf");
// save PDF as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// save the presentation as Pptm format
presentation.save("output.pptm", SaveFormat.Pptm);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Dönüşüm Gereksinimleri" %}}
PDF dosya biçimini yüklerken belgeniz parola korumalı olabilir. [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) şifreli belgeleri de açmanıza olanak tanır. Şifrelenmiş dosyayı açmak için [Belgenin](https://apireference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java) yeni örneğini başlatabilirsiniz. .lang.String-) sınıfını seçin ve dosya adını ve parolayı argüman olarak iletin.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open PDF document
Document doc = new Document("input.pdf", "Your@Password");
// save PDF as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java ile Şifreli PDF Dosyasını Açın" %}}
PDF'yi PPTM'ye dönüştürdükten sonra, sunumunuz için önceden tanımlanmış görünüm tipi de ekleyebilirsiniz. [Aspose.Slides for Java](https://products.aspose.com/slides/java/), PowerPoint'te [ViewProperties](https:/) aracılığıyla açıldığında oluşturulan sunu için görünüm türünü ayarlama olanağı sağlar. /apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties) sınıfı. [setLastView](https://apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) özelliği, [ViewType](https:/) kullanılarak görünüm türünü ayarlamak için kullanılır. /apireference.aspose.com/slides/java/com.aspose.slides/ViewType) numaralandırıcı. 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Pptm format
presentation.save("output.pptm", SaveFormat.Pptm);    
```
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="Diğer Dönüşüm Seçenekleri" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pdf-to-pps/" name="PDF İle PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pdf-to-swf/" name="PDF İle SWF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pdf-to-potx/" name="PDF İle POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pdf-to-ppsx/" name="PDF İle PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pdf-to-potm/" name="PDF İle POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pdf-to-ppt/" name="PDF İle PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pdf-to-ppsm/" name="PDF İle PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pdf-to-xaml/" name="PDF İle XAML" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pdf-to-otp/" name="PDF İle OTP" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pdf-to-pptm/" name="PDF İle PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pdf-to-pot/" name="PDF İle POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/tr/net/conversion/pdf-to-powerpoint/" name="PDF İle POWERPOINT" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}