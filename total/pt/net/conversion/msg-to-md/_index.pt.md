---
title: API C# para exportar MSG para MD
description: Converta MSG para MD sem usar o Microsoft Word ou Outlook em .NET
url_ignore: /pt/net/conversion/msg-to-md/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: MD
otherformats: SVG TIFF FLATOPC EMF WORDML DOTX ODT PS PCL PDF OTT GIF DOC PNG TEXT DOTM JPEG DOT DOCM RTF MD EPUB XPS DOCX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportar MSG para MD via .NET" h2="API .NET para renderizar MSG para MD no Windows, macOS e Linux sem usar Word ou Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Se você é um desenvolvedor .NET que deseja adicionar recursos de conversão de MSG para MD dentro de seus aplicativos, as APIs de manipulação de formato de arquivo [Aspose.Total for .NET](https://products.aspose.com/total/net/) são o caminho. frente. Usando [Aspose.Email for .NET](https://products.aspose.com/email/net/), você pode converter o formato de arquivo MSG para HTML. Depois disso, usando [Aspose.Words for .NET](https://products.aspose.com/words/net/), você pode renderizar HTML para MD.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# para converter MSG em MD" %}}
1. Abra o arquivo MSG usando a classe [MailMessage](https://reference.aspose.com/msg/net/aspose.msg/mailmessage)
2. Converta MSG para HTML usando o método [Save](https://reference.aspose.com/msg/net/aspose.msg.mailmessage/save/methods/3)
3. Carregue HTML usando a classe [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Salve o documento no formato MD usando o método [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) e defina Md como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}

```cs

MailMessage message = MailMessage.Load("sourceFile.msg");
 
message.Save("HtmlOutput.html", SaveOptions.DefaultHtml);

Document document = new Document("HtmlOutput.html");

document.Save("output.md", SaveFormat.Md); 
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analisar arquivo MSG via .NET" %}}
Antes de converter MSG para MD, se você quiser ter certeza de que está convertendo o msg correto, você pode carregar o documento MSG, analisá-lo e dar uma olhada na propriedade desejada. Usando a classe [MapiMessage](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/msg /net/) API, você pode obter informações de remetente e destinatários. Por exemplo, você pode verificar um e-mail de remetente específico para a conversão usando a propriedade [SenderName](https://reference.aspose.com/msg/net/aspose.msg.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}

```cs

var outlookMessageFile = MapiMessage.FromFile("message.msg");
 
if(outlookMessageFile.SenderName == "John"){
    
}
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restringir a edição de documentos MD via .NET" %}}
Ao salvar o documento de MSG para MD, talvez seja necessário proteger seu documento de saída. Às vezes, pode ser necessário limitar a capacidade de editar um documento e permitir apenas determinadas ações com ele. Isso pode ser útil para evitar que outras pessoas editem informações confidenciais em seu documento. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, permite controlar a maneira como você restringe o conteúdo usando o [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parâmetro de enumeração. Você pode definir seu documento como somente leitura usando as seguintes linhas de código. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.md", SaveFormat.Md);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos MSG a MD mediante programación: casos de uso" %}}
Arquivos MSG (mensagens) são usados para armazenar mensagens de texto planas, tornando-os ideais para enviar mensagens simples e notificações. No entanto, ao trabalhar com mais dados estruturados, os arquivos Markdown se tornam essenciais para formatar e apresentar informações.

A conversão de arquivos MSG para formats Markdown é necessária para desbloquear a potencial completa da formatação e apresentação dos seus mensagens. Essa conversão permite que você:

**Cenários de Uso:**

*   **Formatagem de Postagens do Blog**: Converter arquivos MSG para criar postagens do blog formatadas, incluindo títulos, parágrafos e listas.
*   **Modelos de E-mail**: Usar Markdown para formatação de modelos de e-mail, tornando fácil enviar mensagens profissionais com facilidade.
*   **Mensagens de Chatbot**: Converter arquivos MSG para criar conversas de chatbot atraentes, utilizando a formatação de Markdown para exibir logs de conversa e respostas.
*   **Escrita de Documentação Técnica**: Usar Markdown para escrever e formatar documentações técnicas, incluindo guias, tutoriais e manuais de uso.
*   **Postagens Sociais**: Converter arquivos MSG para criar postagens sociais formatadas, incluindo imagens, links e hashtags.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}