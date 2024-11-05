---
title: Exportar EML para PS via Java
description: API Java para converter EML para PS sem usar o Microsoft Word ou Outlook
url_ignore: /pt/java/conversion/eml-to-ps/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: PS
otherformats: EMF SVG RTF PCL DOTM XPS TIFF DOTX PS JPEG PNG DOCM PDF EPUB DOC GIF MD ODT WORDML OTT DOCX FLATOPC DOT TEXT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java para renderizar EML para PS" h2="Exporte EML para PS usando a API Java local sem usar dependências de terceiros" >}}
{{% blocks/products/pf/feature-page-summary %}}
A conversão de e-mail é um recurso poderoso que os desenvolvedores Java podem integrar em qualquer aplicativo Java J2SE, J2EE, J2ME via [Aspose.Total for Java](https://products.aspose.com/total/java/). Usando duas APIs dentro do pacote, você pode converter Eml EML para PS sem dependências de terceiros. Em primeiro lugar, você pode usar a API de manipulação de e-mail [Aspose.Email for Java](https://products.aspose.com/email/java/) para converter o formato de arquivo EML para HTML. Em segundo lugar, você pode renderizar HTML para PS usando a API de processamento de documentos [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Como converter EML para PS" %}}
1. Abra o arquivo EML usando a classe [MailMessage](https://reference.aspose.com/eml/java/com.aspose.eml/mailmessage)
2. Converta EML para HTML usando [save](https://reference.aspose.com/eml/java/com.aspose.eml/MailMessage#save(java.io.OutputStream,%20com.aspose.eml.SaveOptions)) método
3. Carregue HTML usando a classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Salve o documento no formato PS usando [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) e defina PS como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você precisa usar o Aspose.Total para Java diretamente de um projeto baseado em [Maven](https://releases.aspose.com/total/java/) e inclua bibliotecas em seu pom.xml.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "3b2d8cb19d998899886b4be72e1571ea" "convert-email-format-to-word.java" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}