---
title: Exportar OFT para PCL via Java
description: API Java para converter OFT para PCL sem usar o Microsoft Word ou Outlook
url_ignore: /pt/java/conversion/oft-to-pcl/
family: total
platformtag: net
feature: conversion
informat: OFT
outformat: PCL
otherformats: DOC MD EMF PCL ODT GIF PNG FLATOPC XPS DOT TEXT OTT TIFF SVG PS WORDML DOTM DOTX EPUB RTF DOCM PDF JPEG DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java para renderizar OFT para PCL" h2="Exporte OFT para PCL usando a API Java local sem usar dependências de terceiros" >}}
{{% blocks/products/pf/feature-page-summary %}}
A conversão de e-mail é um recurso poderoso que os desenvolvedores Java podem integrar em qualquer aplicativo Java J2SE, J2EE, J2ME via [Aspose.Total for Java](https://products.aspose.com/total/java/). Usando duas APIs dentro do pacote, você pode converter Oft OFT para PCL sem dependências de terceiros. Em primeiro lugar, você pode usar a API de manipulação de e-mail [Aspose.Oft for Java](https://products.aspose.com/email/java/) para converter o formato de arquivo OFT para HTML. Em segundo lugar, você pode renderizar HTML para PCL usando a API de processamento de documentos [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Como converter OFT para PCL" %}}
1. Abra o arquivo OFT usando a classe [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. Converta OFT para HTML usando [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.email.SaveOptions)) método
3. Carregue HTML usando a classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Salve o documento no formato PCL usando [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) e defina PCL como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você precisa usar o Aspose.Total para Java diretamente de um projeto baseado em [Maven](https://releases.aspose.com/total/java/) e inclua bibliotecas em seu pom.xml.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the OFT file to be converted
MailMessage message = MailMessage.load("sourceFile.oft"); 
// save OFT as a HTML 
message.save("HtmlOutput.html", SaveOptions.getDefaultHtml());
// load HTML with an instance of Document
Document document = new Document("HtmlOutput.html");
// call save method while passing SaveFormat.PCL
document.save("output.pcl", SaveFormat.PCL);   
```
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}