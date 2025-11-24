---
title: API Java para renderizar MD para SXC
description: Exporte MD para SXC via API Java sem usar o Microsoft Excel ou Adobe Reader
url_ignore: /pt/java/conversion/md-to-sxc/
family: total
platformtag: net
feature: conversion
informat: MD
outformat: SXC
otherformats: DIF EXCEL TXT XLTM SXC XLT XLTX XLSM XLSB FODS XLAM TSV
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportar MD para SXC via Java" h2="Converta o arquivo MD para SXC usando a API Java local em qualquer aplicativo Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
Ao usar o [Aspose.Total for Java](https://products.aspose.com/total/java/), você pode integrar o recurso de conversão MD para SXC em seus aplicativos Java em um processo de duas etapas. Em primeiro lugar, usando [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) você pode renderizar MD para XLSX. Na segunda etapa, você pode converter XLSX para SXC usando a API de programação de planilha [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converter arquivo MD para SXC via Java" %}}
1. Abra o arquivo MD usando a classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converta MD para XLSX usando [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) método
3. Carregue o documento XLSX usando a classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Salve o documento no formato SXC usando [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) método
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total para Java diretamente de um projeto baseado em [Maven](https://releases.aspose.com/total/java/) e inclua [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) e [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) em seu pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversão" %}}
Se o seu documento MD estiver protegido por senha, você não poderá convertê-lo em SXC sem a senha. Usando a API, você pode primeiro abrir o documento protegido usando uma senha válida e convertê-lo depois. Para abrir o arquivo criptografado, você pode inicializar uma nova instância do [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) e passe o nome do arquivo e a senha como argumentos.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Converter MD Protegido para SXC via Java" %}}
Ao converter o arquivo MD para SXC, você também pode adicionar marca d'água ao formato de arquivo SXC de saída. Para adicionar uma marca d'água, crie uma nova pasta de trabalho para abrir o arquivo XLSX convertido. Selecione a Planilha por meio de seu índice, crie uma Forma e use sua função addTextEffect, defina cores, transparência e muito mais. Depois disso, você pode salvar seu documento XLSX como SXC com marca d'água. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
```
{{< blocks/products/pf/agp/feature-section >}}



A conversão de MD (Markdown) para SXC (StarOffice Calc) beneficia organizações que ainda utilizam ambientes de planilhas legados do StarOffice/OpenOffice. O SXC suporta fórmulas, estruturas de planilhas e formatação de células compatíveis com ecossistemas de escritório mais antigos.



{{% blocks/products/pf/agp/feature-section-col title="Principais Casos de Uso" %}}



* Migrar tabelas Markdown para planilhas SXC legadas.

* Atualizar sistemas empresariais mais antigos com dados baseados em MD.

* Gerar arquivos SXC para plataformas desatualizadas, mas ainda operacionais.

* Preparar registros de engenharia do Markdown em formatos de planilhas clássicas.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{% blocks/products/pf/agp/feature-section-col title="Cenários de Automação" %}}



* Conversão em lote de MD para SXC para ferramentas de negócios arquivadas.

* Conexões ETL para software governamental ou industrial legado.

* Produção noturna de SXC a partir de repositórios Markdown.

* Geração de SXC acionada para fluxos de trabalho compatíveis com versões anteriores.



{{% /blocks/products/pf/agp/feature-section-col %}}



{{< /blocks/products/pf/agp/feature-section >}}
```
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}