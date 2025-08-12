---
title: API Java para renderizar CGM para TXT
description: Exporte CGM para TXT via API Java sem usar o Microsoft Excel ou Adobe Reader
url_ignore: /pt/java/conversion/cgm-to-txt/
family: total
platformtag: net
feature: conversion
informat: CGM
outformat: TXT
otherformats: XLAM FODS XLTM ODS MD DIF EXCEL TXT XLTX XLT SXC XLSB
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Exportar CGM para TXT via Java" h2="Converta o arquivo CGM para TXT usando a API Java local em qualquer aplicativo Java J2SE, J2EE, J2ME" >}}
{{% blocks/products/pf/feature-page-summary %}}
Ao usar o [Aspose.Total for Java](https://products.aspose.com/total/java/), você pode integrar o recurso de conversão CGM para TXT em seus aplicativos Java em um processo de duas etapas. Em primeiro lugar, usando [Aspose.PDF for Java](https://products.aspose.com/pdf/java/) você pode renderizar CGM para XLSX. Na segunda etapa, você pode converter XLSX para TXT usando a API de programação de planilha [Aspose.Cells for Java](https://products.aspose.com/cells/java/).
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Converter arquivo CGM para TXT via Java" %}}
1. Abra o arquivo CGM usando a classe [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document)
2. Converta CGM para XLSX usando [save](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#save-java.lang.String-com.aspose.pdf.SaveOptions- ) método
3. Carregue o documento XLSX usando a classe [Workbook](https://reference.aspose.com/cells/java/com.aspose.cells/Workbook)
4. Salve o documento no formato TXT usando [save](https://reference.aspose.com/cells/java/com.aspose.cells/workbook#save(java.lang.String,%20com.aspose.cells.SaveOptions)) método
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="Requisitos de conversão" %}}
Você pode facilmente usar o Aspose.Total para Java diretamente de um projeto baseado em [Maven](https://releases.aspose.com/total/java/) e inclua [Aspose.PDF for Java](https://docs.aspose.com/pdf/java/installation/) e [Aspose.Cells for Java](https://docs.aspose.com/cells/java/installation/) em seu pom.xml.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="Requisitos de conversão" %}}
Se o seu documento CGM estiver protegido por senha, você não poderá convertê-lo em TXT sem a senha. Usando a API, você pode primeiro abrir o documento protegido usando uma senha válida e convertê-lo depois. Para abrir o arquivo criptografado, você pode inicializar uma nova instância do [Document](https://reference.aspose.com/pdf/java/com.aspose.pdf/Document#Document-java.lang.String-java.lang.String-) e passe o nome do arquivo e a senha como argumentos.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-protected-pdf-to-excel.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-section  h2="Converter CGM Protegido para TXT via Java" %}}
Ao converter o arquivo CGM para TXT, você também pode adicionar marca d'água ao formato de arquivo TXT de saída. Para adicionar uma marca d'água, crie uma nova pasta de trabalho para abrir o arquivo XLSX convertido. Selecione a Planilha por meio de seu índice, crie uma Forma e use sua função addTextEffect, defina cores, transparência e muito mais. Depois disso, você pode salvar seu documento XLSX como TXT com marca d'água. 
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "d25bc6acc71106757fdc028e2cdd660b" "convert-pdf-to-excel-with-watermark.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{% blocks/products/pf/feature-page-summary %}}
```
Converter arquivos **Computer Graphics Metafile (CGM)** para o formato **TXT (Texto Simples)** é valioso para extrair, documentar e processar informações gráficas vetoriais de forma leve e legível por humanos. Em **pipelines de processamento de dados Java-powered**, essa conversão permite a transformação de diagramas CGM em representações baseadas em texto para registro, armazenamento de metadados ou análise posterior. Ao capturar os elementos descritivos dos arquivos CGM em TXT, as organizações podem simplificar a integração com outros sistemas, possibilitar busca e indexação rápidas e manter a compatibilidade de longo prazo.



## ✅ Principais Casos de Uso

- **Registro Baseado em Texto de Diagramas**  
  Armazene informações de diagramas CGM como texto simples para fins de auditoria, depuração ou arquivamento.

- **Extração de Descrições Gráficas Vetoriais**  
  Converta estruturas CGM em TXT para análise, indexação de busca ou integração com ferramentas de análise.

- **Documentação de Metadados de Engenharia**  
  Documente dados de engenharia relacionados a CGM em arquivos TXT para referência rápida e armazenamento leve.


## ⚙️ Cenários de Automação

- **Bibliotecas de E/S Java para Conversão**  
  Utilize APIs padrão de manipulação de arquivos Java juntamente com analisadores CGM para extrair e escrever conteúdo em arquivos TXT.

- **Serviços de Observador de Arquivos**  
  Automatize a conversão de CGM para TXT monitorando diretórios com `WatchService` Java para novos eventos de arquivo.

- **Trabalhos de Conversão em Lote**  
  Processe grandes volumes de arquivos CGM em trabalhos Java agendados, exportando representações textuais para arquivamento ou análise.

- **Exportadores de Texto Simples em Pipelines ETL**  
  Integre a análise de CGM e a exportação de TXT em fluxos de trabalho Java baseados em Extrair-Transformar-Carregar para processamento de dados estruturados.
```
{{% /blocks/products/pf/feature-page-summary %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}