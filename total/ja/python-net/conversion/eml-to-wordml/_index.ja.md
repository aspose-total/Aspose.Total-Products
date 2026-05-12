---
title: Python で EML を WORDML に変換する
description: Microsoft Outlook や Word を使用せずに、Python アプリケーションで EML を WORDML に保存します。 

family: total
platformtag: Python
feature: conversion
informat: EML
outformat: WORDML
otherformats: DOC DOCM DOCX DOT DOTM DOTX EMF EPUB FLATOPC MD ODT OTT PCL PDF PS RTF TEXT WORD WORDML BMP GIF IMAGE JPEG TIFF PNG SVG XPS
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python を使用して EML を WORDML に変換する" h2="Microsoft Word<sup>&reg;</sup> または Outlook をインストールせずに、Python アプリケーションで EML から WORDML への変換。" >}}

{{% blocks/products/pf/feature-page-summary %}}

アプリケーション内に EML から WORDML への変換機能を追加しようとしている Python 開発者は誰ですか? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API は、変換プロセスの自動化に役立ちます。 これは、電子メール、画像、Microsoft Word 形式など、さまざまな形式を扱うさまざまな API の完全なパッケージです。 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) パッケージの一部である [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) および [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API により、Python を使用してこの変換が容易になります。 これは 2 段階のプロセスです。まず、E メールをロードし、[Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) を介して HTML にレンダリングします。 次に、[Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) を使用して変換された HTML を読み込み、WORDML 形式に保存します。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python で EML を WORDML に変換する方法" %}}

- MailMessage.load クラスを使用してソース EML ファイルを開きます。
- 出力 HTML ファイル パスと関連する HTML 保存オプションをパラメーターとして指定して、`save` メソッドを呼び出します。 したがって、EML ファイルは指定されたパスで HTML に変換されます。
- [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) を使用して、保存した HTML ファイルをロードします。
- 関連するファイル パスを指定して save メソッドを呼び出します。最後にEMLが変換されます

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}

- EML から WORDML への変換には、Python 3.5 以降が必要です。
- プロジェクト内の API を PyPI から直接参照 ([Aspose.Words](https://pypi.org/project/aspose-words/) および [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- または、次の pip コマンド ```pip install aspose.words``` および ```pip install Aspose.Email-for-Python-via-NET``` を使用します。 
- さらに、Microsoft Windows または Linux ベースの OS ([Words](https://docs.aspose.com/words/python-net/system-requirements/) および [Email](https://docs.aspose.com/email/python-net/system-requirements/) の詳細を参照) および Linux の場合は、gcc および libpython の追加要件を確認し、ステップバイステップの手順に従ってください [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PythonでEMLをWORDMLに保存" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-email-to-word-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

EML から WordML への変換は、Python API を使用してメールメッセージを XML ベースのワードプロセッシングマークアップに変換し、構造化ドキュメントの相互運用性やシステムレベルの処理に適した形にします。これは、メール由来のコンテンツを XML 指向の文書ワークフローで扱う必要がある場合や、変換パイプラインに統合する場合に有用です。

自動化の観点からは、EML から WordML への変換により、通信内容をマークアップベースの文書形式で表現することで、トレーサビリティと処理の柔軟性が向上します。スケーラブルな文書交換、構造化パース、プログラム可能なワークフロー統合をサポートします。

{{% blocks/products/pf/agp/feature-section-col title="キー ユース ケース" %}}

* **XML ベースの文書出力**  
  メールコンテンツを WordML に変換し、構造化かつマークアップ駆動の文書ワークフローに対応します。

* **相互運用可能な文書交換**  
  XML 文書表現に依存するシステム間で、メール由来のコンテンツを移動させるのに役立ちます。

* **構造化コンテンツ処理**  
  文書内部をプログラムで解析または変換するシナリオをサポートします。

* **システムレベルの文書統合**  
  通信コンテンツを XML 中心のエンタープライズプロセスに組み込みやすくします。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自動化 シナリオ" %}}

* **マークアップワークフロー統合**  
  自動化により、WordML 出力を検証、変換、アーカイブシステムへルーティングできます。

* **構造化パースパイプライン**  
  プログラム的な変換により、メール由来コンテンツの制御された抽出と操作が可能です。

* **交換プロセスの自動化**  
  変換されたファイルは、XML ベースの文書構造を必要とするスケーラブルなシステムに供給できます。

* **エンタープライズ変換チェーン**  
  メールメッセージを WordML に標準化し、下流の繰り返し処理を容易にします。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}