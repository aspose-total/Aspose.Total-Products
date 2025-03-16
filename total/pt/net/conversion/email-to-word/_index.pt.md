---
title: API C# para exportar EMAIL para WORD
description: Converta EMAIL para WORD sem usar o Microsoft Word ou Outlook em .NET
url_ignore: /pt/net/conversion/email-to-word/
family: total
platformtag: net
feature: conversion
informat: MSG
outformat: DOCX
otherformats: DOCM ODT TEXT PCL OTT DOCX PS FLATOPC EPUB XPS GIF WORD DOTX DOC DOTM MD WORDML PDF DOT JPEG PNG RTF SVG TIFF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportar EMAIL para WORD via .NET" h2="API .NET para renderizar EMAIL para WORD no Windows, macOS e Linux sem usar Word ou Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Se você é um desenvolvedor .NET que deseja adicionar recursos de conversão de EMAIL para WORD dentro de seus aplicativos, as APIs de manipulação de formato de arquivo [Aspose.Total for .NET](https://products.aspose.com/total/net/) são o caminho. frente. Usando [Aspose.Email for .NET](https://products.aspose.com/email/net/), você pode converter o formato de arquivo EMAIL para HTML. Depois disso, usando [Aspose.Words for .NET](https://products.aspose.com/words/net/), você pode renderizar HTML para WORD.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# para converter EMAIL em WORD" %}}
1. Abra o arquivo EMAIL usando a classe [MailMessage](https://reference.aspose.com/email/net/aspose.email/mailmessage)
2. Converta EMAIL para HTML usando o método [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
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

{{% blocks/products/pf/feature-page-section  h2="Analisar arquivo EMAIL via .NET" %}}
Antes de converter EMAIL para WORD, se você quiser ter certeza de que está convertendo o email correto, você pode carregar o documento EMAIL, analisá-lo e dar uma olhada na propriedade desejada. Usando a classe [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/email /net/) API, você pode obter informações de remetente e destinatários. Por exemplo, você pode verificar um e-mail de remetente específico para a conversão usando a propriedade [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restringir a edição de documentos WORD via .NET" %}}
Ao salvar o documento de EMAIL para WORD, talvez seja necessário proteger seu documento de saída. Às vezes, pode ser necessário limitar a capacidade de editar um documento e permitir apenas determinadas ações com ele. Isso pode ser útil para evitar que outras pessoas editem informações confidenciais em seu documento. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, permite controlar a maneira como você restringe o conteúdo usando o [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parâmetro de enumeração. Você pode definir seu documento como somente leitura usando as seguintes linhas de código. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");
// call save method while passing SaveFormat.Docx
document.Save("output.docx", SaveFormat.Docx);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos EMAIL a WORD mediante programación: casos de uso" %}}
Conversão de Emails para Documentos do Microsoft Word: Desbloqueando o Poder Completo das Capacidades de Comunicação

Os e-mails são ideais para armazenar mensagens curtas, tornando-os adequados para correspondências casuais e comunicações informais. No entanto, quando se trata de criação de documentos formais e apresentações, os documentos do Microsoft Word se tornam essenciais para transmitir informações complexas e ideias.

A conversão de conteúdo de e-mail em formatos do Microsoft Word é necessária para desbloquear o potencial completo das suas capacidades de comunicação. Essa conversão permite que você:

*   **Relatórios de Negócios**: Converte e-mails para criar relatórios profissionais de negócios, mostrando atualizações da empresa, dados financeiros e tendências do mercado.
*   **Breves de Política e Propostas**: Use o Microsoft Word para desenvolver breves políticas, propostas e apresentações formais para tomadores de decisão, stakeholders e clientes.
*   **Papers Acadêmicos e Relatórios de Pesquisa**: Converte e-mails para produzir papéis acadêmicos de alta qualidade, relatórios de pesquisa e revisões de literatura, garantindo citações precisas e referências adequadas.
*   **Minutas de Reunião e Agendas**: Use o Microsoft Word para criar minutas de reunião, agendas e resumos formais, facilitando a comunicação eficaz e o registro.
*   **Ensaios Pessoais e Posts do Blog**: Converte e-mails para criar ensaios pessoais envolventes, posts do blog e artigos, mostrando habilidades de escrita e criatividade.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}