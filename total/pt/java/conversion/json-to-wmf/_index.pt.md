---
title: Converter o formato JSON para WMF via Java
description: Analise JSON para WMF em Java sem usar o Microsoft PowerPoint
url_ignore: /pt/java/conversion/json-to-wmf/
family: total
platformtag: net
feature: conversion
informat: JSON
outformat: WMF
otherformats: TGA DICOM JPEG2000 WMZ EMZ PSD WMF DXF SVGZ IMAGE
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Converter o formato JSON para WMF via Java" h2="API Java para analisar o formato JSON para WMF em qualquer aplicativo Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
Usando [Aspose.Total for Java](https://products.aspose.com/total/java/), você pode converter o formato JSON para WMF em qualquer aplicativo Java em duas etapas simples. Em primeiro lugar, usando [Aspose.Cells for Java](https://products.aspose.com/cells/java/), você pode analisar JSON para JPEG. Depois disso, usando [Aspose.Imaging for Java](https://products.aspose.com/imaging/java/), você pode converter JPEG em WMF.
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converter o formato JSON para WMF via Java" %}}
1. Crie um novo objeto [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook) e abra o arquivo JSON
2. Salve JSON como JPEG usando [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions) ) método
3. Carregue o documento JPEG usando a classe [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image)
4. Salve o documento no formato WMF usando [save](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image#save-java.lang.String-com.aspose.imaging.ImageOptionsBase-) método
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total para Java diretamente de um projeto baseado em [Maven](https://releases.aspose.com/total/java/) e inclua bibliotecas em seu pom.xml.

Como alternativa, você pode obter um arquivo ZIP em [downloads](https://releases.aspose.com/total/java).
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversão" %}}
Além disso, a API permite analisar JSON para WMF com opções de layout especificadas. Para especificar as opções de layout, você pode usar a classe [JsonLayoutOptions](https://reference.aspose.com/cells/java/com.aspose.cells/jsonlayouttoptions). Ele permite que você processe uma matriz como uma tabela, ignore nulos, ignore o título da matriz, ignore o título do objeto, converta string em número ou data, defina data e formato de número e defina estilo de título. Todas essas opções permitem que você apresente seus dados conforme suas necessidades. O trecho de código a seguir mostra como definir as opções de layout.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "set-layout-and-parse-json-to-image.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Defina o layout e converta o formato JSON para WMF via Java" %}}
Usando a API, você também pode converter JSON em WMF com marca d'água em seu documento WMF. Para adicionar uma marca d'água, você pode primeiro converter JSON para JPEG e adicionar uma marca d'água nele. Para adicionar marca d'água, carregue um arquivo de imagem usando a classe [Image](https://reference.aspose.com/imaging/java/com.aspose.imaging/Image), crie um objeto da classe [Graphics](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics) e inicialize-a com o objeto Image, crie uma nova [Matrix](https://reference.aspose.com/imaging/java/com.aspose.imaging/Matrix) e defina a tradução e a transformação para o ângulo desejado e adicione marca d'água usando [Graphics.drawString](https://reference.aspose.com/imaging/java/com.aspose.imaging/Graphics#drawString-java.lang.String-com.aspose.imaging.Font-com.aspose.imaging.Brush-float-float-). Depois de adicionar a marca d'água em sua imagem, você pode salvar o JPEG como formato WMF. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "05eb9605b16ab5de85e0ecb2d7e80b3f" "convert-json-to-image-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}
Converter **JSON para WMF** é essencial para produzir **gráficos do Windows Metafile a partir de dados estruturados**. Arquivos WMF fornecem gráficos vetoriais escaláveis compatíveis com aplicativos legados do Windows e documentos do Office. Ao transformar JSON em WMF, organizações podem automatizar a criação de diagramas, gráficos e ilustrações técnicas, garantindo consistência e compatibilidade em fluxos de trabalho corporativos.

{{% blocks/products/pf/agp/feature-section-col title="Principais Casos de Uso" %}}

- **Aplicativos legados do Windows** – Manter compatibilidade com software mais antigo que requer gráficos WMF.
- **Diagramas escaláveis** – Gerar diagramas baseados em vetores que escalonam sem perda de qualidade.
- **Integração de documentos do Office** – Incorporar gráficos WMF diretamente em arquivos do Word, PowerPoint e Excel.
- **Gráficos empresariais** – Automatizar a geração de gráficos a partir de conjuntos de dados estruturados para relatórios corporativos.
- **Ilustrações técnicas** – Criar ilustrações precisas e orientadas por dados para manuais e documentos de engenharia.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="Cenários de Automação" %}}

- **Pipelines JSON para WMF** – Automatizar a conversão de dados estruturados em gráficos vetoriais WMF.
- **Geração automatizada de gráficos vetoriais** – Reduzir a criação manual de diagramas e ilustrações.
- **Renderização de gráficos orientada por JSON** – Preencher gráficos e visuais diretamente a partir de conjuntos de dados.
- **Fluxos de trabalho de ilustração em nível empresarial** – Integrar a geração de WMF em pipelines de documentação corporativa.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}