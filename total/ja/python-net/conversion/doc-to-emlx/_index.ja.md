---
title: Python で DOC を EMLX に変換する
description: Microsoft Word や Outlook を使用せずに、Python アプリケーション内で DOC を EMLX に保存します。

family: total
platformtag: Python
feature: conversion
informat: DOC
outformat: EMLX
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python を使用して DOC を EMLX に変換する" h2="Microsoft Word<sup>&reg;</sup> または Outlook をインストールせずに、Python アプリケーションで DOC から EMLX への変換。" >}}

{{% blocks/products/pf/feature-page-summary %}}

アプリケーション内に DOC から EMLX への変換機能を追加しようとしている Python 開発者は誰ですか? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API は、変換プロセスの自動化に役立ちます。 これは、電子メール、画像、Microsoft Word 形式など、さまざまな形式を扱うさまざまな API の完全なパッケージです。 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) パッケージの一部である [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) および [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API により、Python を使用してこの変換が容易になります。 これは 2 段階のプロセスです。最初に DOC ファイルをロードし、[Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) を介して HTML にレンダリングします。 次に、[Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) を使用して変換された HTML を読み込み、EMLX 形式に保存します。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python で DOC を EMLX に変換する方法" %}}

- [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) クラスを使用してソース DOC ファイルを開きます。
- 出力 HTML ファイル パスと関連する HTML 保存オプションをパラメーターとして指定して、`save` メソッドを呼び出します。 したがって、DOC ファイルは指定されたパスで HTML に変換されます。
- MailMessage.load を使用して、保存した HTML ファイルをロードします。
- 関連するファイル パスを指定して save メソッドを呼び出します。最後にDOCが変換されます

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}

- DOC から EMLX への変換には、Python 3.5 以降が必要です。
- プロジェクト内の API を PyPI から直接参照 ([Aspose.Words](https://pypi.org/project/aspose-words/) および [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- または、次の pip コマンド ```pip install aspose.words``` および ```pip install Aspose.Email-for-Python-via-NET``` を使用します。 
- さらに、Microsoft Windows または Linux ベースの OS ([Words](https://docs.aspose.com/words/python-net/system-requirements/) および [Email](https://docs.aspose.com/email/python-net/system-requirements/) の詳細を参照) および Linux の場合は、gcc および libpython の追加要件を確認し、ステップバイステップの手順に従ってください [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PythonでDOCをEMLXに保存" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

DOC から EMLX への変換は、Word のコンテンツを特定のデスクトップメールエコシステムで使用されるメールメッセージ形式に変換し、メールフレンドリーな構造でコンテンツを保持できるようにします。プラットフォーム固有のメッセージ保存要件に合わせて文書情報を整合させる必要がある場合に便利です。

Python API を使用すると、DOC から EMLX への変換を繰り返し実行でき、効率的に自動エクスポート、アーカイブ作業、手動での再フォーマットなしでの特殊なメール処理ワークフローをサポートします。

{{% blocks/products/pf/agp/feature-section-col title="主要な使用例" %}}

* **プラットフォーム固有のメッセージエクスポート**
  文書コンテンツを EMLX に変換し、対応するメール環境との互換性を確保します。

* **メールアーカイブの準備**
  文書から派生した情報を、メールボックスの保存作業に適したメッセージ形式で保存します。

* **コンテンツの再利用**
  正式な文書コンテンツを、対象ワークフローでメール対応レコードとして再利用します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自動化シナリオ" %}}

* **メールボックスコンテンツの自動化**
  DOC 入力からプログラム的に EMLX ファイルを生成し、メール指向システム向けに活用します。

* **特殊アーカイブパイプライン**
  EMLX ベースの保存が必要な環境向けに、文書変換を自動化します。

* **大量エクスポートジョブ**
  文書バッチを EMLX に変換し、繰り返しの手作業処理を削減します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}