---
title: Java를 통해 DOTX를 PPSM로 변환
description: Microsoft Word 또는 PowerPoint를 사용하지 않고 DOTX를 PPSM로 내보내는 Java API
url_ignore: /ko/java/conversion/dotx-to-ppsm/
family: total
platformtag: net
feature: conversion
informat: DOTX
outformat: PPSM
otherformats: POTX PPSM POT PPTM PPS POTM PPT POWERPOINT PPSX PPTX CSV DIF FODS ODS SXC TSV XLAM XLTM EXCEL XLS XLSB XLSM XLSX XLT XLTM XLTX
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/i18n/feature-page-header h1="Java를 통해 DOTX를 PPSM로 변환" h2="Microsoft<sup>&reg;</sup> PowerPoint 또는 Word를 사용하지 않고 Java J2SE, J2EE, J2ME 애플리케이션 내에서 사내 Java API를 사용하여 DOTX에서 PPSM로 변환" >}}
{{% blocks/products/pf/feature-page-summary %}}
종종 개발자는 프로그래밍 방식으로 DOTX 파일을 PPSM로 변환해야 합니다. 파일 자동화 Java 라이브러리[Aspose.Total for Java](https://products.aspose.com/total/java/)를 사용하여 몇 가지 간단한 단계로 렌더링 프로세스를 자동화할 수 있습니다. [Aspose.Words for Java](https://products.aspose.com/words/java/)를 사용하여 DOTX 파일을 로드하고 HTML로 변환할 수 있습니다. 그 후 강력한 PowerPoint 조작 Java API [Aspose.Slides for Java](https://products.aspose.com/slides/java/)를 사용하여 새 프레젠테이션을 만들고 HTML 콘텐츠를 작성하고 PPSM로 저장할 수 있습니다. .
{{% /blocks/products/pf/feature-page-summary  %}}
{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Java를 통해 DOTX를 PPSM로 변환하는 방법" %}}
1. [Document](https://reference.aspose.com/words/java/com.aspose.words/Document) 클래스를 사용하여 DOTX 파일을 엽니다.
2. [저장](https://reference.aspose.com/words/java/com.aspose.words/Document#save(java.lang.String,com.aspose.words.SaveOptions)을 사용하여 DOTX 파일을 HTML로 변환합니다.)) 방법
3. 새로운 [Presentation](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation) 객체 초기화
5. BufferedReader를 사용하여 HTML 파일에서 콘텐츠를 추출하고 프레젠테이션 파일에 콘텐츠를 작성합니다.
6. [save](https://reference.aspose.com/slides/java/com.aspose.slides/Presentation#save-java.io.OutputStream-int-) 메서드를 사용하여 문서를 PPSM에 저장합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
DOTX에서 PPSM로 파일 변환을 위해 [Maven](https://repository.aspose.com/webapp/#/artifacts/browse/tree/General/repo/com/aspose에서 직접 Java용 Aspose.Total을 쉽게 사용할 수 있습니다. /aspose-total) 기반 프로젝트를 만들고 pom.xml에 라이브러리를 포함합니다.

또는 [다운로드](https://downloads.aspose.com/total/java)에서 ZIP 파일을 받을 수 있습니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-dotx-to-pptx.java" >}}


{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/feature-page-section  h2="변환 요구 사항" %}}
API를 사용하면 암호로 보호된 DOTX 문서를 PPSM로 변환할 수도 있습니다. 입력한 DOTX 문서가 비밀번호로 보호되어 있는 경우 비밀번호를 사용하지 않고는 PPSM 형식으로 변환할 수 없습니다. 암호화된 문서를 열려면 LoadOptions 개체에 올바른 암호를 설정하고 이를 Document 생성자에 전달할 수 있습니다.  
{{% blocks/products/pf/feature-page-code %}}

{{< gist "aspose-com-gists" "bdc7f32134dcfd5fd6163ad4092b843f" "convert-protected-dotx-to-pptx.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-section title="기타 변환 옵션" subTitle="" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/dotx-to-ppsm/" name="DOTX 에게 PPSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/dotx-to-pot/" name="DOTX 에게 POT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/dotx-to-powerpoint/" name="DOTX 에게 POWERPOINT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/dotx-to-pptx/" name="DOTX 에게 PPTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/dotx-to-potx/" name="DOTX 에게 POTX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/dotx-to-pptm/" name="DOTX 에게 PPTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/dotx-to-potm/" name="DOTX 에게 POTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/dotx-to-pps/" name="DOTX 에게 PPS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/dotx-to-ppsx/" name="DOTX 에게 PPSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/dotx-to-ppt/" name="DOTX 에게 PPT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/dotx-to-csv/" name="DOTX 에게 CSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/dotx-to-dif/" name="DOTX 에게 DIF" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/dotx-to-fods/" name="DOTX 에게 FODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/dotx-to-ods/" name="DOTX 에게 ODS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/dotx-to-sxc/" name="DOTX 에게 SXC" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/dotx-to-tsv/" name="DOTX 에게 TSV" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/dotx-to-xlam/" name="DOTX 에게 XLAM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/dotx-to-xltm/" name="DOTX 에게 XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/dotx-to-excel/" name="DOTX 에게 EXCEL" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/dotx-to-xls/" name="DOTX 에게 XLS" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/dotx-to-xlsb/" name="DOTX 에게 XLSB" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/dotx-to-xlsm/" name="DOTX 에게 XLSM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/dotx-to-xlsx/" name="DOTX 에게 XLSX" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/dotx-to-xlt/" name="DOTX 에게 XLT" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/dotx-to-xltm/" name="DOTX 에게 XLTM" description="" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/total/ko/net/conversion/dotx-to-xltx/" name="DOTX 에게 XLTX" description="" >}}


{{< /blocks/products/pf/agp/other-supported-section >}}
{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}