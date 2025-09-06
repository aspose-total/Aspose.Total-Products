---
title: C++를 사용하여 XLSX를 PPTX로 변환 또는 무료 온라인 변환기 사용
description: C++ 애플리케이션 내에서 XLSX를 PPTX로 변환 또는 온라인. 코드를 통합하기 전에 무료 CSV to DOC 온라인 변환기를 빠르게 테스트하십시오.

family: total
platformtag: cpp
feature: conversion
informat: XLSX
outformat: PPTX
otherformats: DOC DOCX WORD POWERPOINT
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="C++를 통해 XLSX를 PPTX로 변환 또는 온라인" h2="엑셀 내보내기&reg; 완전한 기능을 갖춘 C++ 애플리케이션 내에서 XLSX에서 PPTX로" >}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="C++에서 XLSX에서 PPTX로 변환" %}}
1. [Factory](https://reference.aspose.com/cells)의 [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) 멤버 함수를 사용하여 XLSX 파일 열기 /cpp/class/aspose.cells.factory) 클래스 참조
2. XLSX를 PDF로 변환하고 SaveFormat을 PDF로 설정
3. [Document](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.pptxument) 클래스 참조를 사용하여 변환된 PDF 파일을 로드합니다.
4. [Save](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.pptxument#a6383c010776212483f51cc41235924db) 멤버 함수를 사용하여 문서를 PPTX 형식으로 저장하고 Pptx을 SaveFormat으로 설정합니다.
{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="변환 요구 사항" %}}
명령줄에서 ```nuget install Aspose.Total.Cpp```로 설치하거나 Visual Studio의 패키지 관리자 콘솔을 통해 ```Install-Package Aspose.Total.Cpp```로 설치합니다.

또는 [downloads](https://releases.aspose.com/total/cpp)에서 ZIP 파일의 오프라인 MSI 설치 프로그램 또는 DLL을 가져옵니다.
{{% /blocks/products/pf/agp/feature-section-col %}}
{{% blocks/products/pf/feature-page-code %}}
```cs
// load the XLSX file using Factory::CreateIWorkbook
intrusive_ptr<Aspose::Cells::IWorkbook> wkb = Factory::CreateIWorkbook(u"sourceFile.xlsx");
// save XLSX as PDF
wkb->Save(u"pdfOutput.pdf", SaveFormat_Pdf);
// load the PDF file using Pptxument class reference
auto pptx = MakeObject<Pptxument>(u"pdfOutput.pdf");
// save pptxument in PPTX format
pptx->Save(u"convertedFile.pptx", SaveFormat::Pptx);
```

{{% /blocks/products/pf/feature-page-code %}}
{{< /blocks/products/pf/agp/feature-section >}}

<div class="container-fluid agp-content bg-white aboutfile box-1 vh100 section nopbtm">
<div class=container>
<div class=row>
<div class="demobox tc col-md-12 padding-0">

<h3>XLSX에서 PPTX로 온라인 변환기</h3>

<iframe title="pptx에서 xlsx로 변환 온라인 도구" style="border: none; height: 426px;" scrolling="no" src="https://widgets.aspose.cloud/total-conversion/?to=pptx&from=xlsx" id="child-iframe" width="80%"></iframe>
<p style="font-size:1.3rem;color:#3d8ec4;font-weight:400"><a href="https://products.aspose.app/total/xlsx-to-pptx/">XLSX를 PPTX로 변환하는 무료 앱을 사용해 보세요.</a></p>
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
                          <span itemprop="name"><b>어떻게 XLSX를 PPTX 온라인으로 변환할 수 있습니까?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">XLSX 변환을 위한 온라인 앱은 위에 통합되어 있습니다. XLSX에서 PPTX로 변환 프로세스를 시작하려면 XLSX 파일을 지정된 영역으로 끌어다 놓거나 흰색 상자 내부를 클릭하여 파일을 가져오기만 하면 됩니다. 파일을 가져오면 "변환" 버튼을 클릭하여 변환 프로세스를 시작합니다. XLSX에서 PPTX로 변환이 완료되면 클릭 한 번으로 새로 변환된 PPTX 파일을 즉시 다운로드할 수 있습니다.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>XLSX를 변환하는 데 얼마나 걸립니까?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">이 온라인 변환기의 속도는 XLSX 파일의 크기에 크게 좌우됩니다. 더 작은 XLSX 파일은 단 몇 초 만에 PPTX로 변환할 수 있습니다. 또한 C++ 응용 프로그램 내에 변환 코드를 통합한 경우 응용 프로그램을 최적화한 방법에 따라 변환 프로세스의 효율성이 달라집니다.</span>
                      </div>
                  </li>
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>무료 Aspose.Total 변환기를 사용하여 XLSX를 PPTX로 변환하는 것이 안전합니까?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">물론! XLSX to PPTX 변환이 완료되면 제공된 다운로드 링크를 통해 변환된 파일을 즉시 다운로드할 수 있습니다. 업로드된 파일은 24시간이 지나면 삭제되며, 이 시간이 지나면 다운로드 링크가 작동하지 않습니다. 아무도 파일에 액세스할 수 없으므로 XLSX를 포함한 파일 변환이 완전히 안전하고 안전하다는 것을 확신할 수 있습니다. 무료 앱은 테스트 목적으로 위에 통합되어 코드를 통합하기 전에 결과를 확인할 수 있습니다.</span>
                      </div>
                  </li>                 
                  <li itemscope="" itemprop="mainEntity" itemtype="https://schema.org/Question">
                      <div>
                          <span itemprop="name"><b>XLSX를 변환하려면 어떤 브라우저를 사용해야 합니까?</b></span>
                      </div>
                      <div itemscope="" itemprop="acceptedAnswer" itemtype="https://schema.org/Answer">
                          <span itemprop="text">Google Chrome, Firefox, Opera 또는 Safari와 같은 최신 웹 브라우저를 사용하여 이 온라인 변환기에 액세스할 수 있습니다. 그러나 데스크톱 애플리케이션에서 작업하는 경우 Aspose.Total XLSX 변환 API가 원활한 솔루션을 제공합니다.</span>
                      </div>
                  </li>
              </ul>
          </div>
      </div>
  </div>
{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}
{{< /blocks/products/pf/feature-page-wrap >}}