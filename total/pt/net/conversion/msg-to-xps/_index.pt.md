---
title: API C# para exportar MSG para XPS
description: Converta MSG para XPS sem usar o Microsoft Word ou Outlook em .NET
url_ignore: /pt/net/conversion/msg-to-xps/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: XPS
otherformats: DOC XPS DOCX WORDML GIF PCL SVG EMF JPEG EPUB DOTM DOTX OTT RTF ODT DOT TIFF DOCM TEXT PS PNG MD PDF FLATOPC
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportar MSG para XPS via .NET" h2="API .NET para renderizar MSG para XPS no Windows, macOS e Linux sem usar Word ou Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Se você é um desenvolvedor .NET que deseja adicionar recursos de conversão de MSG para XPS dentro de seus aplicativos, as APIs de manipulação de formato de arquivo [Aspose.Total for .NET](https://products.aspose.com/total/net/) são o caminho. frente. Usando [Aspose.Email for .NET](https://products.aspose.com/email/net/), você pode converter o formato de arquivo MSG para HTML. Depois disso, usando [Aspose.Words for .NET](https://products.aspose.com/words/net/), você pode renderizar HTML para XPS.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# para converter MSG em XPS" %}}
1. Abra o arquivo MSG usando a classe [MailMessage](https://reference.aspose.com/msg/net/aspose.msg/mailmessage)
2. Converta MSG para HTML usando o método [Save](https://reference.aspose.com/msg/net/aspose.msg.mailmessage/save/methods/3)
3. Carregue HTML usando a classe [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Salve o documento no formato XPS usando o método [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) e defina Xps como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-word.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analisar arquivo MSG via .NET" %}}
Antes de converter MSG para XPS, se você quiser ter certeza de que está convertendo o msg correto, você pode carregar o documento MSG, analisá-lo e dar uma olhada na propriedade desejada. Usando a classe [MapiMessage](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/msg /net/) API, você pode obter informações de remetente e destinatários. Por exemplo, você pode verificar um e-mail de remetente específico para a conversão usando a propriedade [SenderName](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restringir a edição de documentos XPS via .NET" %}}
Ao salvar o documento de MSG para XPS, talvez seja necessário proteger seu documento de saída. Às vezes, pode ser necessário limitar a capacidade de editar um documento e permitir apenas determinadas ações com ele. Isso pode ser útil para evitar que outras pessoas editem informações confidenciais em seu documento. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, permite controlar a maneira como você restringe o conteúdo usando o [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parâmetro de enumeração. Você pode definir seu documento como somente leitura usando as seguintes linhas de código. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.xps", SaveFormat.Xps);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos MSG a XPS mediante programación: casos de uso" %}}
A conversão de arquivos MSG para formatos XPS é necessário para desbloquear as capacidades completas de edição e gerenciamento de documentos. Essa conversão permite que você:

**Cenarios de Uso:**

*   **Edição de Documentos**: Converter arquivos MSG para editar documentos, adicionar novo conteúdo e modificar informações existentes.
*   **Preservação de Mensagens**: Usar formatos XPS para preservar mensagens, garantir a integridade dos dados e evitar a corrupção.
*   **Segurança de Arquivos**: Converter arquivos MSG para documentos seguros, criptografar informações sensíveis e proteger contra acesso não autorizado.
*   **Melhoria da Compatibilidade:** Usar formatos XPS para criar documentos compatíveis, garantindo compartilhamento suave e colaboração em diferentes plataformas.
*   **Armazenamento de Dados**: Converter arquivos MSG para documentos armazenados, armazenar dados históricos, manter um registro das comunicações passadas.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}