---
title: قم بإنشاء ملف باستخدام Python 

description: أنشئ نصًا ومستندات Microsoft Word بدون تثبيت Microsoft Office 
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="أنشئ المستندات باستخدام Python" h2="أنشئ ملفات نصية وملفات Microsoft Word DOCX و DOC داخل تطبيقات Python دون تثبيت Microsoft Office <sup>&reg;</sup>." >}}

{{% blocks/products/pf/feature-page-summary %}}
يعد تخزين البيانات هو الأساس لأي تطبيق برمجي اعتمادًا على طبيعة التطبيق. قد يكون موقع التخزين هو قاعدة البيانات أو XML أو JSON أو الملفات النصية أو تقارير Excel أو مستندات Microsoft Word. إدخال / إخراج الملف هو جزء من أي لغة ومعظم اللغات بما في ذلك Python تدعم كتابة البيانات إلى ملفات نصية. لنفكر في لغة بايثون. كتابة الملفات النصية الموجودة باستخدام Python ، فهي توفر طريقة فتح وكتابة وإغلاق لهذه المهام. أولاً ، افتح الملف بمسار الملف ذي الصلة وألحق أو اكتب الميزة كوسائط. ثم اكتب النص المطلوب في ملف وأغلق الملف أخيرًا باستخدام طريقة close (). 

لإنشاء مستندات Microsoft Word باستخدام Python ، نستخدم حزمة [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) APIs التي تحتوي على [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API كجزء من الحزمة الخاصة بها. توفر واجهة برمجة التطبيقات هذه حل أتمتة المستندات الكاملة للفواتير والتقارير والمقالات الفنية. إجراءات إنشاء مستند Word المدرجة أدناه.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="كيفية إنشاء ملف نصي باستخدام بايثون" %}}

إنشاء ملفات نصية والكتابة إليها أمر بسيط. توفر Python طريقة open () بثلاث معاملات ويجب أن تستخدم أحد المعلمات جنبًا إلى جنب مع مسار الملف. هناك ثلاث معلمات هي "x" و "a" و "w". من خلال توفير "x" ، سيتم إنشاء ملف جديد ولكنه يلقي بخطأ في حالة وجود الملف بالفعل. من خلال توفير "a" ، سيتم إنشاء ملف نصي جديد إذا لم يكن موجودًا وفي حالة وجوده ، سيتم إلحاق المحتوى في النهاية. وأخيرًا توفير "w" ، سيتم إنشاء مستند نصي جديد واستبداله بالمحتوى الجديد في حالة وجوده بالفعل.

{{% blocks/products/pf/feature-page-code h3="Python - إنشاء ملف نصي" %}}

{{< gist "aspose-com-gists" "6961d2c30ccbbae86fc8cc4cdf8155cc" "create-text-file-using-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}

{{% blocks/products/pf/feature-page-section  h2="قم بإنشاء مستندات Microsoft Word" %}}

يحتوي Total Python Word API على العديد من الميزات بما في ذلك إنشاء ملفات Microsoft Word وإدراج الصور والنص داخل المستندات وإضافة الجداول والقوائم داخل الملفات وكذلك تعديل المستندات الموجودة بسهولة. لإنشاء عملية مستند Microsoft Word ، قم بإنشاء كائن من فئات [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) و [DocumentBuilder](https://reference.aspose.com/words/python-net/aspose.words/documentbuilder/). أضف النص والفقرة والقوائم والجداول المطلوبة داخل المستند ثم احفظها في النهاية.

{{% blocks/products/pf/feature-page-code h3="Python - إنشاء مستندات Microsoft Word" %}}

{{< gist "aspose-com-gists" "6961d2c30ccbbae86fc8cc4cdf8155cc" "create-word-files-via-python.py" >}}

{{% /blocks/products/pf/feature-page-code  %}}
{{% /blocks/products/pf/feature-page-section %}}