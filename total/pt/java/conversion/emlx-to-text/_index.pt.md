---
title: Exportar EMLX para TEXT via Java
description: API Java para converter EMLX para TEXT sem usar o Microsoft Word ou Outlook
url_ignore: /pt/java/conversion/emlx-to-text/
family: total
platformtag: net
feature: conversion
informat: EMLX
outformat: TEXT
otherformats: PS DOTM GIF JPEG DOCM DOC PNG ODT TIFF SVG PDF DOT PCL EMF WORDML EPUB DOTX DOCX OTT RTF TEXT FLATOPC XPS MD
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="API Java para renderizar EMLX para TEXT" h2="Exporte EMLX para TEXT usando a API Java local sem usar dependências de terceiros" >}}
{{% blocks/products/pf/feature-page-summary %}}
A conversão de e-mail é um recurso poderoso que os desenvolvedores Java podem integrar em qualquer aplicativo Java J2SE, J2EE, J2ME via [Aspose.Total for Java](https://products.aspose.com/total/java/). Usando duas APIs dentro do pacote, você pode converter Emlx EMLX para TEXT sem dependências de terceiros. Em primeiro lugar, você pode usar a API de manipulação de e-mail [Aspose.Email for Java](https://products.aspose.com/email/java/) para converter o formato de arquivo EMLX para HTML. Em segundo lugar, você pode renderizar HTML para TEXT usando a API de processamento de documentos [Aspose.Words for Java](https://products.aspose.com/words/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Como converter EMLX para TEXT" %}}
1. Abra o arquivo EMLX usando a classe [MailMessage](https://reference.aspose.com/email/java/com.aspose.email/mailmessage)
2. Converta EMLX para HTML usando [save](https://reference.aspose.com/email/java/com.aspose.email/MailMessage#save(java.io.OutputStream,%20com.aspose.emlx.SaveOptions)) método
3. Carregue HTML usando a classe [Document](https://reference.aspose.com/words/java/com.aspose.words/Document)
4. Salve o documento no formato TEXT usando [save](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)) e defina TEXT como SaveFormat
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