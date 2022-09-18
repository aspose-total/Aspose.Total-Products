---
title: Python で DOT を PPTM に変換する
description: Microsoft Word や PowerPoint を使用せずに、Python アプリケーションで DOT から PPTM への変換 
url: /ja/python-net/conversion/dot-to-pptm/
family: total
platformtag: Python
feature: conversion
informat: DOT
outformat: PPTM
otherformats: PowerPoint PPSX PPTX PPT POT POTX POTM PPTM PPSM PPS ODP
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python を使用して DOT を PPTM に変換する" h2="Microsoft Word<sup>&reg;</sup> または PowerPoint をインストールせずに、Python アプリケーションで DOT から PPTM への変換" >}}

{{% blocks/products/pf/feature-page-summary %}}

アプリケーション内に DOT から PPTM への変換機能を追加しようとしている Python 開発者は誰ですか? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API は、変換プロセスの自動化に役立ちます。これは、さまざまな形式を扱うさまざまな API の完全なパッケージです。 そう **Python で DOT を PPTM に変換する方法**

主に2段階です。 まず [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) API を使用して DOT ファイルを PDF に変換します。 その後、PowerPoint Python API [Aspose.Slides for Python via .NET](https://products.aspose.com/slides/python-net/) を使用して、作成した PDF をプレゼンテーションに PPTM 形式で保存します。 

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python で DOT を PPTM に変換する" %}}
- **ステップ1** [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) クラスを使用してソース DOT ファイルを開きます。
- [Save](https://reference.aspose.com/words/python-net/aspose.words/document/save/) メソッドを使用して、ファイル名と目的のディレクトリ パスを指定し、DOT ファイルを PDF に保存します。
-  **ステップ2** [Presentation](https://reference.aspose.com/slides/python-net/aspose.slides/presentation/) クラスのインスタンスを含む PDF ファイルをロードします。
-  出力ファイルのパスと SaveFormat.PPTM をパラメーターとして指定して、`save` メソッドを呼び出します。 したがって、DOT ファイルは指定されたパスで PPTM に変換されます。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}

- DOT から PPTM への変換には、Python 3.5 以降が必要です。
- PyPI ([Aspose.Slides](https://pypi.org/project/Aspose.Slides/) および [Aspose.Words](https://pypi.org/project/aspose-words/)) から直接プロジェクト内の API を参照するか、
- 次の pip コマンド ```pip install aspose.slides``` および ```pip install aspose.words``` を使用します。さらに、
- Microsoft Windows または Linux ベースの OS ([Slides](https://docs.aspose.com/slides/python-net/system-requirements/) および [Words](https://docs.aspose.com/words/python-net/system-requirements/) の詳細を参照) および Linux の場合は、gcc および libpython の追加要件を確認し、[INSTALL](https://docs.aspose.com/words/python-net/installation/) の手順に従ってください。
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Python で DOT を PDF に保存 - ステップ 1" offSpacer="" %}}

{{< gist "aspose-com-gists" "64442bfb87f37cb8b1d3fe9cfa666c1b" "convert-microsoft-word-documents-to-pdf-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{% blocks/products/pf/agp/code-block title="Python で PDF を PPTM に保存 - ステップ 2" offSpacer="" %}}

{{< gist "aspose-com-gists" "64442bfb87f37cb8b1d3fe9cfa666c1b" "convert-pdf-files-to-powerpoint-in-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/other-supported-autogen >}}
{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}