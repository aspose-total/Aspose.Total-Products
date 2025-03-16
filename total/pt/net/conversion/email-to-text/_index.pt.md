---
title: API C# para exportar EMAIL para TEXT
description: Converta EMAIL para TEXT sem usar o Microsoft Word ou Outlook em .NET
url_ignore: /pt/net/conversion/email-to-text/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: TEXT
otherformats: EPUB GIF MD RTF DOCM PCL FLATOPC JPEG PDF EMF WORDML DOTX ODT DOTM DOC DOT XPS SVG PNG DOCX OTT TIFF TEXT PS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportar EMAIL para TEXT via .NET" h2="API .NET para renderizar EMAIL para TEXT no Windows, macOS e Linux sem usar Word ou Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Se você é um desenvolvedor .NET que deseja adicionar recursos de conversão de EMAIL para TEXT dentro de seus aplicativos, as APIs de manipulação de formato de arquivo [Aspose.Total for .NET](https://products.aspose.com/total/net/) são o caminho. frente. Usando [Aspose.Email for .NET](https://products.aspose.com/email/net/), você pode converter o formato de arquivo EMAIL para HTML. Depois disso, usando [Aspose.Words for .NET](https://products.aspose.com/words/net/), você pode renderizar HTML para TEXT.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# para converter EMAIL em TEXT" %}}
1. Abra o arquivo EMAIL usando a classe [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Converta EMAIL para HTML usando o método [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Carregue HTML usando a classe [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Salve o documento no formato TEXT usando o método [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) e defina Text como SaveFormat
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
Antes de converter EMAIL para TEXT, se você quiser ter certeza de que está convertendo o email correto, você pode carregar o documento EMAIL, analisá-lo e dar uma olhada na propriedade desejada. Usando a classe [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, você pode obter informações de remetente e destinatários. Por exemplo, você pode verificar um e-mail de remetente específico para a conversão usando a propriedade [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restringir a edição de documentos TEXT via .NET" %}}
Ao salvar o documento de EMAIL para TEXT, talvez seja necessário proteger seu documento de saída. Às vezes, pode ser necessário limitar a capacidade de editar um documento e permitir apenas determinadas ações com ele. Isso pode ser útil para evitar que outras pessoas editem informações confidenciais em seu documento. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, permite controlar a maneira como você restringe o conteúdo usando o [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parâmetro de enumeração. Você pode definir seu documento como somente leitura usando as seguintes linhas de código. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.text", SaveFormat.Text);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos EMAIL a TEXT mediante programación: casos de uso" %}}
Conversão de Email para Texto é utilizado para extraír informações de e-mails, tornando-os ideais para criar registros escritos e resumos. No entanto, ao trabalhar com cadeias de e-mails longas, ferramentas como clientes de e-mail se tornam essenciais para organizar e rastrear conversas.

A conversão de e-mails em arquivos de texto é necessária para desbloquear a plena capacidade do seu potencial de armazenamento de registros e habilidades de resumo. Essa conversão permite que você:

**Cenários de Uso:**

*   **Arquivagem de E-mail**: Converter e-mails para criar registros escritos, arquivos e resumos para referência histórica.
*   **Análise de Comunicação com Clientes**: Usar arquivos de texto para analisar conversas de e-mail de clientes, rastrear problemas e identificar tendências nas comunicações.
*   **Notas de Reunião e Resumo**: Converter e-mails para criar notas concisas de reuniões, resumos e itens de ação para equipes e partes interessadas.
*   **Monitoramento de Campanhas de Marketing**: Usar arquivos de texto para monitorar conversações de campanhas de marketing, rastrear as respostas e medir o engajamento.
*   **Arquivagem Legal**: Converter e-mails para criar registros escritos oficiais, evidências e transcritos para fins legais.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}