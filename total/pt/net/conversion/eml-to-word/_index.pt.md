---
title: API C# para exportar EML para WORD
description: Converta EML para WORD sem usar o Microsoft Word ou Outlook em .NET
url_ignore: /pt/net/conversion/eml-to-word/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: DOCX
otherformats: DOC ODT PNG TIFF PDF WORD EMF JPEG TEXT DOT WORDML RTF OTT EPUB MD DOCM DOCX GIF SVG DOTX PCL XPS FLATOPC DOTM
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportar EML para WORD via .NET" h2="API .NET para renderizar EML para WORD no Windows, macOS e Linux sem usar Word ou Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Se você é um desenvolvedor .NET que deseja adicionar recursos de conversão de EML para WORD dentro de seus aplicativos, as APIs de manipulação de formato de arquivo [Aspose.Total for .NET](https://products.aspose.com/total/net/) são o caminho. frente. Usando [Aspose.Email for .NET](https://products.aspose.com/email/net/), você pode converter o formato de arquivo EML para HTML. Depois disso, usando [Aspose.Words for .NET](https://products.aspose.com/words/net/), você pode renderizar HTML para WORD.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# para converter EML em WORD" %}}
1. Abra o arquivo EML usando a classe [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Converta EML para HTML usando o método [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Carregue HTML usando a classe [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Salve o documento no formato WORD usando o método [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) e defina Word como SaveFormat
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
Antes de converter EML para WORD, se você quiser ter certeza de que está convertendo o eml correto, você pode carregar o documento EML, analisá-lo e dar uma olhada na propriedade desejada. Usando a classe [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, você pode obter informações de remetente e destinatários. Por exemplo, você pode verificar um e-mail de remetente específico para a conversão usando a propriedade [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restringir a edição de documentos WORD via .NET" %}}
Ao salvar o documento de EML para WORD, talvez seja necessário proteger seu documento de saída. Às vezes, pode ser necessário limitar a capacidade de editar um documento e permitir apenas determinadas ações com ele. Isso pode ser útil para evitar que outras pessoas editem informações confidenciais em seu documento. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, permite controlar a maneira como você restringe o conteúdo usando o [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parâmetro de enumeração. Você pode definir seu documento como somente leitura usando as seguintes linhas de código. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Docx
document.Save("output.docx", SaveFormat.Docx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos EML a WORD mediante programación: casos de uso" %}}
Arquivos de EML (Electronic Mail) são usados para armazenar mensagens baseadas em texto, tornando-os ideais para enviar e-mails pessoais e correspondências comerciais. No entanto, quando se trabalha com documentos que requerem formatação e controle de layout, documentos do Word se tornam essenciais para comunicação e colaboração profissionais.

A conversão de arquivos de EML em formatos do Word é necessária para desbloquear a potencialidade completa da sua comunicação escrita e das suas capacidades de colaboração. Essa conversão permite que você:

**Cenários de Uso:**

*   **Correspondência Comercial**: Converta arquivos de EML para criar letras de negócios formais, propostas e relatórios que refletem um tom profissional.
*   **Gestão de E-mails Pessoais**: Use o Word para gerenciar e-mails pessoais, criando pastas, etiquetas e categorias para uma organização fácil e rápida.
*   **Minutas de Reuniões e Atas**: Converta arquivos de EML para tirar notas precisas de reuniões, registrando as principais discussões e decisões de forma clara e concisa.
*   **Documentação Técnica**: Use o Word para criar manual de usuário, instruções e especificações técnicas que são fáceis de ler e entender.
*   **Edição de Documentos em Colaboração**: Converta arquivos de EML para colaborar com membros do seu time sobre documentos, rastreando alterações e revisões ao vivo.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}