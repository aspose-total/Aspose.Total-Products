---
title: API C# para exportar EML para DOC
description: Converta EML para DOC sem usar o Microsoft Word ou Outlook em .NET
url_ignore: /pt/net/conversion/eml-to-doc/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: DOC
otherformats: EPUB PCL PDF JPEG DOCM DOC TEXT DOT MD RTF EMF DOTM SVG WORDML PS GIF TIFF XPS OTT ODT DOTX FLATOPC DOCX PNG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportar EML para DOC via .NET" h2="API .NET para renderizar EML para DOC no Windows, macOS e Linux sem usar Word ou Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Se você é um desenvolvedor .NET que deseja adicionar recursos de conversão de EML para DOC dentro de seus aplicativos, as APIs de manipulação de formato de arquivo [Aspose.Total for .NET](https://products.aspose.com/total/net/) são o caminho. frente. Usando [Aspose.Email for .NET](https://products.aspose.com/email/net/), você pode converter o formato de arquivo EML para HTML. Depois disso, usando [Aspose.Words for .NET](https://products.aspose.com/words/net/), você pode renderizar HTML para DOC.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# para converter EML em DOC" %}}
1. Abra o arquivo EML usando a classe [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Converta EML para HTML usando o método [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
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

{{% blocks/products/pf/feature-page-section  h2="Analisar arquivo EML via .NET" %}}
Antes de converter EML para DOC, se você quiser ter certeza de que está convertendo o eml correto, você pode carregar o documento EML, analisá-lo e dar uma olhada na propriedade desejada. Usando a classe [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, você pode obter informações de remetente e destinatários. Por exemplo, você pode verificar um e-mail de remetente específico para a conversão usando a propriedade [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restringir a edição de documentos DOC via .NET" %}}
Ao salvar o documento de EML para DOC, talvez seja necessário proteger seu documento de saída. Às vezes, pode ser necessário limitar a capacidade de editar um documento e permitir apenas determinadas ações com ele. Isso pode ser útil para evitar que outras pessoas editem informações confidenciais em seu documento. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, permite controlar a maneira como você restringe o conteúdo usando o [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parâmetro de enumeração. Você pode definir seu documento como somente leitura usando as seguintes linhas de código. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.doc", SaveFormat.Doc);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos EML a DOC mediante programación: casos de uso" %}}
Arquivos de e-mail são usados para armazenar informações de comunicação baseadas em texto, tornando-os ideais para criar documentos leves de ler. No entanto, quando se trabalha com dados apresentação, os documentos do Microsoft Office como o Word se tornam essenciais para a formatação e layout dos documentos.

A conversão de Arquivos de E-mail para formatos do Word é necessária para desbloquear as capacidades completas de sua formatação e layout de documento. Essa conversão permite que você:

**Cenários de Uso:**

*   **Comunicação de Negócios**: Converter arquivos de e-mail para criar documentos leves de negócios, relatórios e propostas.
*   **Minutos de Reunião e Notas**: Usar o Word para formatar minutos de reunião, notas e itens de ação, garantindo uma compreensão clara entre os membros da equipe.
*   **Correspondência Pessoal**: Converter arquivos de e-mail para criar documentos pessoais, como cartas, certificados e convites.
*   **Collateral de Marketing**: Usar o Word para criar materiais de marketing envolventes, como folhetos, folhas de anúncio e declarações de imprensa.
*   **Escrivão Profissional**: Converter arquivos de e-mail para produzir conteúdo profissional polido, incluindo artigos, posts de blog e estudos de caso.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}