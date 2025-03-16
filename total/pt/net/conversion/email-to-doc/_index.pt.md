---
title: API C# para exportar EMAIL para DOC
description: Converta EMAIL para DOC sem usar o Microsoft Word ou Outlook em .NET
url_ignore: /pt/net/conversion/email-to-doc/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: DOC
otherformats: TEXT RTF DOC JPEG EMF EPUB DOT GIF PCL WORDML ODT TIFF SVG DOCM MD DOTX PS DOTM DOCX OTT PDF XPS FLATOPC PNG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportar EMAIL para DOC via .NET" h2="API .NET para renderizar EMAIL para DOC no Windows, macOS e Linux sem usar Word ou Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Se você é um desenvolvedor .NET que deseja adicionar recursos de conversão de EMAIL para DOC dentro de seus aplicativos, as APIs de manipulação de formato de arquivo [Aspose.Total for .NET](https://products.aspose.com/total/net/) são o caminho. frente. Usando [Aspose.Email for .NET](https://products.aspose.com/email/net/), você pode converter o formato de arquivo EMAIL para HTML. Depois disso, usando [Aspose.Words for .NET](https://products.aspose.com/words/net/), você pode renderizar HTML para DOC.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# para converter EMAIL em DOC" %}}
1. Abra o arquivo EMAIL usando a classe [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Converta EMAIL para HTML usando o método [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Carregue HTML usando a classe [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Salve o documento no formato DOC usando o método [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) e defina Doc como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analisar arquivo EMAIL via .NET" %}}
Antes de converter EMAIL para DOC, se você quiser ter certeza de que está convertendo o email correto, você pode carregar o documento EMAIL, analisá-lo e dar uma olhada na propriedade desejada. Usando a classe [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, você pode obter informações de remetente e destinatários. Por exemplo, você pode verificar um e-mail de remetente específico para a conversão usando a propriedade [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restringir a edição de documentos DOC via .NET" %}}
Ao salvar o documento de EMAIL para DOC, talvez seja necessário proteger seu documento de saída. Às vezes, pode ser necessário limitar a capacidade de editar um documento e permitir apenas determinadas ações com ele. Isso pode ser útil para evitar que outras pessoas editem informações confidenciais em seu documento. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, permite controlar a maneira como você restringe o conteúdo usando o [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parâmetro de enumeração. Você pode definir seu documento como somente leitura usando as seguintes linhas de código. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.doc", SaveFormat.Doc);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos EMAIL a DOC mediante programación: casos de uso" %}}
Conversão de Arquivos de E-mail em Documentos do Microsoft Office (DOC)

Arquivos de e-mail são amplamente utilizados para comunicação, mas quando se trata de compartilhar e analisar dados, os documentos do Microsoft Office se tornam essenciais. A conversão de arquivos de e-mail para o formato DOC desbloqueia o potencial completo da sua capacidade de criação e análise de documentos.

A conversão de arquivos de e-mail para formatos DOC é necessária para desbloquear o potencial completo da sua capacidade de criação e análise de documentos. Esta conversão permite que você:

**Uso Caso:**

*   **Solicitação de Projeto Proposta**: Converte arquivos de e-mail para criar documentários de proposta de projeto concisos e profissionais, destacando detalhes-chave e prazos.
*   **Documentação de Minutas de Reunião**: Use DOC para organizar as minutas de reuniões, itens de ação e decisões tomadas durante a reunião.
*   **Avaliação e Análise de Contratos**: Converte arquivos de e-mail para avaliar e analisar contratos, garantindo que todos os termos e condições sejam compreendidos claramente por ambas as partes.
*   **Submissão de currículo e Carta de Currículo**: Crie currículos profissionais e cartas de currículo usando templates DOC, ajustando seus materiais de aplicação para abertas específicas de emprego.
*   **Geração de Relatórios de Conferência**: Use DOC para gerar relatórios de conferência, resumindo apresentações, discussões e resultados-chave.

Ao converter arquivos de e-mail para o formato DOC, você pode gerenciar e analisar suas necessidades de criação de documentos de forma eficiente.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}