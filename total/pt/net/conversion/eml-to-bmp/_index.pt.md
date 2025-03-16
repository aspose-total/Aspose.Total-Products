---
title: API C# para exportar EML para BMP
description: Converta EML para BMP sem usar o Microsoft Word ou Outlook em .NET
url_ignore: /pt/net/conversion/eml-to-bmp/
family: total
platformtag: net
feature: conversion
informat: EML
outformat: BMP
otherformats: DOC EMF DOT PCL GIF RTF OTT FLATOPC DOTM TIFF PDF PNG DOCM PS XPS DOTX SVG ODT DOCX EPUB TEXT WORDML MD JPEG
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportar EML para BMP via .NET" h2="API .NET para renderizar EML para BMP no Windows, macOS e Linux sem usar Word ou Outlook" >}}

{{% blocks/products/pf/feature-page-summary %}}
Se você é um desenvolvedor .NET que deseja adicionar recursos de conversão de EML para BMP dentro de seus aplicativos, as APIs de manipulação de formato de arquivo [Aspose.Total for .NET](https://products.aspose.com/total/net/) são o caminho. frente. Usando [Aspose.Email for .NET](https://products.aspose.com/email/net/), você pode converter o formato de arquivo EML para HTML. Depois disso, usando [Aspose.Words for .NET](https://products.aspose.com/words/net/), você pode renderizar HTML para BMP.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API C# para converter EML em BMP" %}}
1. Abra o arquivo EML usando a classe [MailMessage](https://reference.aspose.com/eml/net/aspose.eml/mailmessage)
2. Converta EML para HTML usando o método [Save](https://reference.aspose.com/email/net/aspose.email.mailmessage/save/methods/3)
3. Carregue HTML usando a classe [Document](https://reference.aspose.com/words/net/aspose.words/document)
4. Salve o documento no formato BMP usando o método [Save](https://reference.aspose.com/words/net/aspose.words.document/save/methods/4) e defina Bmp como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "convert-email-formats-to-images.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Analisar arquivo EML via .NET" %}}
Antes de converter EML para BMP, se você quiser ter certeza de que está convertendo o eml correto, você pode carregar o documento EML, analisá-lo e dar uma olhada na propriedade desejada. Usando a classe [MapiMessage](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage) de [Aspose.Email for .NET](https://products.aspose.com/email/net/) API, você pode obter informações de remetente e destinatários. Por exemplo, você pode verificar um e-mail de remetente específico para a conversão usando a propriedade [SenderName](https://reference.aspose.com/email/net/aspose.email.mapi/mapimessage/properties/sendername).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "5a9fece649991cb4d3f82988b0979ef7" "parse-email-files.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Restringir a edição de documentos BMP via .NET" %}}
Ao salvar o documento de EML para BMP, talvez seja necessário proteger seu documento de saída. Às vezes, pode ser necessário limitar a capacidade de editar um documento e permitir apenas determinadas ações com ele. Isso pode ser útil para evitar que outras pessoas editem informações confidenciais em seu documento. [Aspose.Words for .NET](https://products.aspose.com/words/net/) API, permite controlar a maneira como você restringe o conteúdo usando o [ProtectionType](https://reference.aspose.com/words/net/aspose.words/protectiontype) parâmetro de enumeração. Você pode definir seu documento como somente leitura usando as seguintes linhas de código. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Document document = new Document("HtmlOutput.html");

document.Protect(ProtectionType.ReadOnly, "password");

document.Save("output.bmp", SaveFormat.Bmp);  
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos EML a BMP mediante programación: casos de uso" %}}
Arquivos de EML (Electronic Mail) são utilizados para armazenar emails com conteúdo textual, tornando-os ideais para armazenamento de conteúdo e anexos de emails.

No entanto, quando se trabalha com dados intensivos em imagem, os formatos BMP (Bitmap) se tornam essenciais para a preservação e melhoria das imagens.

A conversão dos arquivos EML para formatos BMP é necessária para desbloquear o potencial completo dos seus ativos digitais e visualizações. Essa conversão permite que você:

**Cenários de Uso:**

*   **Preservação de Imagem**: Converter arquivos EML para preservar anexos de emails como imagens de alta qualidade, garantindo a integridade dos dados e a precisão histórica.
*   **Análise e Análise Forense Digital**: Usar BMP para analisar e visualizar conteúdo de email, como mensagens de texto e anexos, para fins de investigação.
*   **Otimização de Imagem com E-Comércio**: Converter arquivos EML para otimizar imagens de produtos, reduzindo o tamanho do arquivo e melhorando os tempos de carga da página web.
*   **Digitização Artística**: Usar BMP para digitalizar obras de arte a partir de anexos de email, preservando obras criativas e artefatos históricos.
*   **Visualização e Presentação de Dados**: Converter arquivos EML para criar apresentações interativas, visualizações e relatórios que exibem conteúdo de email de uma forma mais atraente.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}