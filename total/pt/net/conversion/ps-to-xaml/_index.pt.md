---
title: Exportar PS para XAML via API C#
description: API .NET para converter PS em XAML sem usar o Microsoft Word
url_ignore: /pt/net/conversion/ps-to-xaml/
family: total
platformtag: net
feature: conversion
informat: PS
outformat: XAML
otherformats: XAML OTP POT SWF POTM PPSM POTX PPT PPSX PPS PPTM POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Renderizar PS para XAML via .NET" h2="API .NET para exportar PS para XAML no Windows, macOS e Linux sem usar o Microsoft<sup>&reg;</sup> PowerPoint" >}}

{{% blocks/products/pf/feature-page-summary %}}
Usando um pacote de APIs poderosas de automação de formato de arquivo [Aspose.Total for .NET](https://products.aspose.com/total/net/) você pode facilmente renderizar PS para XAML em duas etapas simples. Usando a API de processamento de PDF [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/), você pode transformar o formato de arquivo PS em PPTX. Depois disso, usando a API de processamento de apresentação [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), você pode converter PPTX para XAML.
{{% /blocks/products/pf/feature-page-summary  %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="API .NET para converter PS em XAML" %}}
1. Abra o arquivo PS usando a classe [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document)
2. Converta PS para PPTX usando o método [Salvar](https://reference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5)
3. Carregue o arquivo PPTX usando a classe [Apresentação](https://reference.aspose.com/slides/net/aspose.slides/presentation)
4. Salve o documento no formato XAML usando o método [Save](https://reference.aspose.com/slides/net/aspose.slides.presentation/save/methods/5) e defina `Xaml` como SaveFormat
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Instale a partir da linha de comando como ```nuget install Aspose.Total``` ou via Package Manager Console do Visual Studio com ```Install-Package Aspose.Total```.

Como alternativa, obtenha o instalador MSI offline ou as DLLs em um arquivo ZIP em [downloads](https://releases.aspose.com/total/net).
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "convert-ps-to-docm.cs" >}}
{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

{{% blocks/products/pf/feature-page-section  h2="Obtenha metadados XMP do arquivo PS via .NET" %}}
Ao converter PS para XAML, você pode precisar de informações extras de metadados XMP para priorizar seu processo de conversão em lote. Por exemplo, você pode obter e classificar seus documentos de conversão com base na data de criação e processar os documentos de acordo. [Aspose.PDF for .NET](https://products.aspose.com/pdf/net/) permite que você acesse os metadados XMP de um arquivo PS. Para obter os metadados de um arquivo PS, você pode criar um objeto [Document](https://reference.aspose.com/pdf/net/aspose.pdf/document) e abrir o arquivo PS de entrada. Depois disso, você pode obter os metadados do arquivo usando a propriedade [Metadados](https://reference.aspose.com/pdf/net/aspose.pdf/document/properties/metadata).  
{{% blocks/products/pf/feature-page-code %}}
{{< gist "aspose-com-gists" "03ca9b446f7a7fc78d49a01c742a2540" "decrypt-ps-file.cs" >}}
{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Criar arquivo XAML somente leitura via .NET" %}}
Ao usar a API [Aspose.Slides for .NET](https://products.aspose.com/slides/net/), você pode aprimorar ainda mais os recursos do seu aplicativo de conversão. Um dos recursos pode ser criar seu arquivo de saída somente leitura para aumentar a segurança. A API permite que você defina seu arquivo XAML como somente leitura, o que significa que os usuários (depois de abrirem a apresentação) veem a recomendação somente leitura. 
{{% blocks/products/pf/feature-page-code %}}

```cs

Presentation presentation = new Presentation("PptxOutput.pptx");

presentation.ProtectionManager.ReadOnlyRecommended = true;

presentation.Save("output.xaml", SaveFormat.Xaml);     
```

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="Transformación de archivos PS a XAML mediante programación: casos de uso" %}}
Arquivos de formato PDF Portátil (PS) são usados para armazenar informações de gráficos vetoriais, tornando-os ideais para criar gráficos estáticos, logotipos e ilustrações. No entanto, ao trabalhar com dados dinâmicos, o XAML (Língua de Marcação de Aplicações Extensível) se torna essencial para construir interfaces de usuário e aplicações.

A conversão de arquivos PS para formatos XAML é necessária para desbloquear a potencial integral da sua capacidade de desenvolvimento de aplicativos. Essa conversão permite que você:

*   **Desenvolvimento de Aplicativos Móveis**: Converter arquivos PS para criar aplicações móveis nativas com interfaces de usuário intuitivas, aproveitando o poder do XAML para uma experiência de usuário sem alterações.
*   **Desenvolvimento de Aplicativos de Deskstop**: Usar XAML para construir aplicações de desktop robustas e escaláveis, aproveitando as forças da linguagem em bindings de dados, animações e template.
*   **Bibliotecas de Componentes de UI Reutilizáveis**: Converter arquivos PS para criar componentes de UI reutilizados, como botões, campos de texto e menus, usando XAML para design eficiente e manutenível.
*   **Gráficos 3D e Animações**: Usar XAML para trazer gráficos 3D e animações à vida em suas aplicações, combinando o poder dos gráficos vetoriais com a flexibilidade de uma linguagem de marcação.
*   **Acessibilidade e Personalização**: Converter arquivos PS para criar elementos UI acessíveis e personalizáveis, garantindo que suas aplicações atendam às necessidades e preferências de usuários diversificados.
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}


{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}