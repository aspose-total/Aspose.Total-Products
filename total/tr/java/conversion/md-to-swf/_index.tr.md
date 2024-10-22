---
title: Java API aracılığıyla MD'yi SWF'ye dönüştürün
description: Microsoft Word kullanmadan MD'yi SWF'ye dönüştürmek için Java API
url_ignore: /tr/java/conversion/md-to-swf/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: SWF
otherformats: PPSX PPSM PPT POT POTM POWERPOINT OTP SWF XAML PPTM POTX PPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="MD'yi SWF'ye Aktarmak için Java API" h2="Microsoft<sup>&reg;</sup> PowerPoint veya Adobe<sup>&reg;</sup> Acrobat Reader kullanmadan şirket içi Java API aracılığıyla MD'yi SWF'ye aktarın" >}}
{{% blocks/products/pf/feature-page-summary %}}
[Aspose.Total for Java](https://products.aspose.com/total/java/) kullanarak herhangi bir Java J2SE, J2EE, J2ME uygulamasında MD'yi SWF'ye kolayca dönüştürebilirsiniz. İlk olarak, [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) kullanarak MD'yi PPTX'e aktarabilirsiniz. Bundan sonra, [Aspose.Slides for Java](https://products.aspose.com/slides/java/) PowerPoint Processing API'yi kullanarak PPTX'i SWF'ye dönüştürebilirsiniz.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="MD'yi SWF'ye Dönüştürmek için Java API" %}}
1. [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document) sınıfını kullanarak MD dosyasını açın
2. [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-int-) yöntemini kullanarak MD'yi PPTX'e dönüştürün
3. [Sunum](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) sınıfını kullanarak PPTX belgesini yükleyin
4. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.lang.String-int-) yöntemini kullanarak belgeyi SWF biçiminde kaydedin ve ` Swf` SaveFormat olarak
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Dönüşüm Gereksinimleri" %}}
Aspose.Total for Java'yı doğrudan [Maven](https://releases.aspose.com/total/java/) tabanlı bir projeden kolayca kullanabilirsiniz. ve [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) ve [Aspose.Slides for Java](https://docs.aspose.com/slides/java/installation/) pom.xml dosyanızda.

Alternatif olarak, [indirilenler](https://releases.aspose.com/total/java) adresinden bir ZIP dosyası alabilirsiniz.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "1117f48b6b86750ef08ff3ea2a04da2b" "convert-md-to-powerpoint.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Dönüşüm Gereksinimleri" %}}
MD dosya biçimini yüklerken belgeniz parola korumalı olabilir. [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) şifreli belgeleri de açmanıza olanak tanır. Şifrelenmiş dosyayı açmak için [Belgenin](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java) yeni örneğini başlatabilirsiniz. .lang.String-) sınıfını seçin ve dosya adını ve parolayı argüman olarak iletin.  
{{% blocks/products/pf/feature-page-code %}}

```java
// open MD document
Document doc = new Document("input.md", "Your@Password");
// save MD as PPTX format 
document.save("PptxOutput.pptx", SaveFormat.Pptx); 

```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Java ile Şifreli MD Dosyasını Açın" %}}
MD'yi SWF'ye dönüştürdükten sonra, sunumunuz için önceden tanımlanmış görünüm tipi de ekleyebilirsiniz. [Aspose.Slides for Java](https://products.aspose.com/slides/java/), PowerPoint'te [ViewProperties](https:/) aracılığıyla açıldığında oluşturulan sunu için görünüm türünü ayarlama olanağı sağlar. /apireference.aspose.com/slides/java/com.aspose.slides/ViewProperties) sınıfı. [setLastView](https://reference.aspose.com/slides/java/com.aspose.slides/ViewProperties#setLastView-int-) özelliği, [ViewType](https:/) kullanılarak görünüm türünü ayarlamak için kullanılır. /apireference.aspose.com/slides/java/com.aspose.slides/ViewType) numaralandırıcı. 
{{% blocks/products/pf/feature-page-code %}}

```java
// instantiate a Presentation object that represents a PPTX file
Presentation presentation = new Presentation("PptxOutput.pptx");
// set view type
presentation.getViewProperties().setLastView((byte) ViewType.SlideMasterView);
// save the presentation as Swf format
presentation.save("output.swf", SaveFormat.Swf);    
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
 
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}