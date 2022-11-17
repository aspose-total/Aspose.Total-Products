---
title: تحويل المستندات عبر C++ 

description: قم بتحويل تنسيقات المستندات المختلفة مثل Word و Excel و PowerPoint و PDF و JSON والصور والمزيد باستخدام C++ API. 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="تحويل المستند باستخدام C++" h2="تحويل ملفات Microsoft <sup> & reg؛ </sup> Office Word و Excel و PowerPoint و PDF والصور وتنسيقات أخرى متنوعة باستخدام مكتبة C++." >}}

{{% blocks/products/pf/feature-page-summary %}}
يحل [Total C++ Library](https://products.aspose.com/total/cpp/) مشكلة تحويل المستندات ويمكن للمطورين أتمتة حل إدارة المستندات ومعالجتها بسهولة عن طريق دمج واجهة برمجة التطبيقات في التطبيقات المطورة الجديدة أو في التطبيقات الحالية. يمكن لمبرمجي C++ إضافة وظائف مثل إنشاء مستندات تنسيقات مختلفة أو تحريرها أو تحويلها داخل حلهم دون الاعتماد على أي برنامج. بعض الحالات العامة مثل TXT إلى PDF ، SVG إلى PNG ، XLSX إلى CSV ، JSON إلى CSV ، Word إلى PDF ، HTML إلى PDF ، يمكن تحويلها بسهولة. علاوة على ذلك ، هناك عدد قليل من الحالات التي تتعامل معها واجهة برمجة التطبيقات المدرجة أدناه وعدد قليل من الروابط المقدمة لحالات التحويل ذات الصلة. 

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="تحويل Microsoft Word إلى Excel" %}}
يدعم Total C++ API تحويل Microsoft Word DOC / DOCX إلى Excel.  العملية هي تحميل ملف Word DOC / DOCX باستخدام [مستند](https://reference.aspose.com/words/cpp/class/aspose.words.document) مرجع فئة واستدعاء [حفظ](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_string_saveformat) وظيفة العضو للتحويل إلى HTML أولاً. ثم قم بتحميل مستند HTML باستخدام [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) مرجع فئة واستدعاء [حفظ](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a5dc7de23f7ceba76a05dc1d49f51502e) لحفظ المستند بتنسيق Excel. 

{{% blocks/products/pf/feature-page-code h3="C++ - تحويل Word إلى Excel" %}}

{{< gist "aspose-com-gists" "1219e046dd93cf1ab6a75783eb74c191" "convert-word-to-excel.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="pdf-to-powerpoint pdf-to-excel pdf-to-txt pot-to-doc potm-to-doc potx-to-doc pps-to-doc ppsm-to-doc ppsx-to-doc ppt-to-doc pptm-to-doc pptx-to-doc doc-to-pptx docm-to-pptx docx-to-pptx dot-to-pptx dotm-to-pptx dotx-to-pptx" >}}

{{% blocks/products/pf/feature-page-section  h2="PDF لتحويل Word" %}}
تدعم مكتبة تحويل C++ أيضًا تحويل PDF إلى Word DOC و DOCX وتحويل التنسيقات الأخرى. بالنظر إلى حالة تقديم PDF إلى RTF ، فهي عملية من خطوتين ، أولاً تحويل PDF إلى تنسيق Word DOC / DOCX ثم تحويله إلى RTF. الخطوات المضمنة لهذا ، تحميل ملف PDF باستخدام [مستند](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document) مرجع فئة واستدعاء [حفظ](https://reference.aspose.com/pdf/cpp/class/aspose.pdf.document#adb8061c585440fde49c1263e68837f01) لتحويل PDF إلى Word. الآن قم بتحميل ملف Word DOC / DOCX مرة أخرى باستخدام [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) مرجع فئة Aspose.Words API واحفظه في تنسيق RTF باستخدام [حفظ](https://reference.aspose.com/words/cpp/class/aspose.words.document#save_stream_saveformat) وظيفة العضو.

{{% blocks/products/pf/feature-page-code h3="C++ - PDF لتحويل Word" %}}

{{< gist "aspose-com-gists" "fe7c3ff0a8c783e4f0ed6bff199c6800" "convert-pdf-to-word.cpp" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="odt-to-pptx ott-to-pptx rtf-to-pptx txt-to-pptx word-to-pptx wordml-to-pptx email-to-bmp email-to-word eml-to-xps emlx-to-image msg-to-doc oft-to-pdf cgm-to-doc cgm-to-csv pot-to-csv pdf-to-tsv pdf-to-csv doc-to-csv" >}}

{{% blocks/products/pf/feature-page-section  h2="تحويل JSON إلى Word" %}}
بالنسبة لتحويل JSON ، تدعم C++ API مجموعات مختلفة مثل JSON إلى Word و Json إلى PowerPoint و Word إلى JSON وما إلى ذلك. بالنظر إلى حالة تحويل Word ، العملية هي قراءة بيانات JSON الصالحة من ملف باستخدام كائن جديد [IWorkbook](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook) ثم استدعاء [حفظ](https://reference.aspose.com/cells/cpp/class/aspose.cells.i_workbook#a9460f52a2dec8f4bf623a4905167d997) طريقة لحفظ JSON كملف PDF. لذا الآن قم بتحميل الملف المحفوظ باستخدام فئة [Document](https://reference.aspose.com/words/cpp/class/aspose.words.document) واحفظه في تنسيق مستند Word باستخدام [حفظ](https://reference.aspose.com/Words/cpp/class/aspose.words.document#save_string_saveformat).
{{% blocks/products/pf/feature-page-code h3="C++ - تحويل JSON إلى Word" %}}

{{< gist "aspose-com-gists" "62d90d1935ee72ea0be4071f38e82ece" "parse-json-to-doc.cpp" >}}


{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="flatopc-to-pptx pdf-to-mhtml mhtml-to-csv tex-to-docm xps-to-gif svg-to-mhtml pptx-to-mhtml ps-to-pcl md-to-rtf epub-to-pptm md-to-ppt pdf-to-ppsx svg-to-ods xps-to-excel docx-to-excel odt-to-fods rtf-to-xlsx json-to-ppsx json-to-word word-to-json powerpoint-to-json powerpoint-to-xlsx ppsm-to-json" >}}