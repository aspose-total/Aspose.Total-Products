---
title: .NET을 사용하여 CSV를 RTF로 변환 또는 무료 온라인 변환기 사용
description: .NET Framework, .NET Core, Mono 또는 Xamarin 플랫폼에서 CSV를 RTF로 변환 또는 온라인. 코드를 통합하기 전에 무료 CSV to RTF 온라인 변환기를 빠르게 테스트하십시오.

family: total
platformtag: net
feature: conversion
informat: CSV
outformat: RTF
otherformats: WORD DOC DOCX DOCM DOT DOTM DOTX MOBI ODT OTT RTF WORDML
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen-total h1="C#을 통해 CSV를 RTF로 변환 또는 온라인 앱" h2="엑셀 내보내기&reg; .NET Framework, .NET Core, Mono 또는 Xamarin 플랫폼에서 CSV를 RTF로">}}
{{< blocks/products/pf/main-container >}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title=".NET에서 CSV에서 RTF로 변환" %}}
1. [Workbook](https://apireference.aspose.com/cells/net/aspose.cells/workbook) 클래스를 사용하여 CSV 파일 열기
2. CSV를 PDF로 변환하고 SaveFormat을 자동으로 설정
3. 변환된 PDF 파일을 [문서](https://apireference.aspose.com/pdf/net/aspose.pdf/document) 클래스를 이용하여 불러옵니다.
4. [Save](https://apireference.aspose.com/pdf/net/aspose.pdf.document/save/methods/5) 방법을 사용하여 문서를 RTF 형식으로 저장하고 Docx을 SaveFormat으로 설정합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total```로 설치합니다.

또는 [downloads](https://releases.aspose.com/total/net)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-autogen title="CSV에서 RTF로의 변환을 위한 .NET C# 코드" gistPath="" %}}
```cs
// load the CSV file using Workbook class
var book = new Aspose.Cells.Workbook("input.csv");
// save CSV as PDF
book.Save("pdfOutput.pdf", Aspose.Cells.SaveFormat.Auto); 
// load the PDF file using Document class
var document = new Aspose.Pdf.Document("pdfOutput.pdf");
// save document in RTF format
document.Save("output.docx", SaveFormat.Docx); 
```
{{% /blocks/products/pf/agp/code-autogen %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0" align="center">

<h3>CSV를 RTF로 변환하는 무료 온라인 변환기</h3>

<iframe style="border: none; height: 426px;" scrolling="no" src="https://total-conversion-app-65z5r2lp.qa.k8s.dynabic.com/?to=docx&from=csv" id="child-iframe" width="80%"></iframe>

</div></div>
</div></div>
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
<style>.howtolist li{margin-right: 0!important;line-height: 26px;position: relative;margin-bottom: 10px;font-size: 13px;list-style-type: none;}</style>
<div class="col-md-12 tl bg-gray-dark howtolist section">
  <a class="anchor" name="faqpage"></a>
  <div class="container tl dflex" itemscope="" itemtype="https://schema.org/FAQPage">
      <div class="col-md-4 howtosectiongfx">
          <img class="social-panel-hide-on-mobile" src="https://www.groupdocs.cloud/templates/brand/images/groupdocs/conversion/groupdocs_conversion-brand.png" alt="FAQs" width="335" height="283">
      </div>
      <div class="howtosection col-md-8">
          <div>
              <h2>자주 묻는 질문</h2>
              <ul>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>어떻게 CSV를 RTF 온라인으로 변환할 수 있습니까?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">CSV 변환을 위한 온라인 앱은 위에 통합되어 있습니다. 변환 프로세스를 시작하려면 CSV 파일을 끌어다 놓거나 지정된 영역 내부를 클릭하여 문서를 가져올 수 있습니다. 그런 다음 "변환" 버튼을 클릭하여 CSV에서 RTF로 변환을 시작합니다. 프로세스가 완료되면 클릭 한 번으로 변환된 파일을 쉽게 다운로드하여 RTF 형식으로 원하는 출력을 얻을 수 있습니다.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>CSV를 변환하는 데 얼마나 걸립니까?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">이 온라인 변환기의 속도는 빠르지만 주로 CSV 파일의 크기에 따라 달라집니다. 작은 CSV 파일이 있는 경우 몇 초 만에 RTF로 변환할 수 있습니다. 또한 변환 코드를 .NET 애플리케이션에 통합한 경우 변환 프로세스 속도는 애플리케이션을 얼마나 잘 최적화했는지에 따라 달라집니다.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>무료 Aspose.Total 변환기를 사용하여 CSV를 RTF로 변환하는 것이 안전합니까?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">물론! CSV에서 RTF로 변환 프로세스가 완료되면 RTF 파일에 대한 다운로드 링크가 즉시 생성됩니다. 파일의 보안을 최우선으로 생각하므로 업로드된 모든 파일은 24시간 후에 삭제되며 해당 기간이 지나면 다운로드 링크 작동이 중지됩니다. CSV 파일을 포함하여 변환 프로세스 중에 파일이 안전하다는 것을 확신할 수 있습니다. 위의 무료 앱은 테스트용으로 코드를 통합하기 전에 결과를 확인할 수 있습니다.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>CSV를 변환하려면 어떤 브라우저를 사용해야 합니까?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Google Chrome, Firefox, Opera, Safari와 같은 온라인 CSV에서 RTF로의 변환을 위해 최신 웹 브라우저를 유연하게 사용할 수 있습니다. 그러나 데스크톱 애플리케이션을 구축하는 경우 Aspose.Total CSV Conversion API를 원활하게 통합할 수 있습니다.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}
{{< blocks/products/pf/agp/about-autogen-total >}}
{{< /blocks/products/pf/main-container >}}
{{< /blocks/products/pf/main-wrap-class >}}