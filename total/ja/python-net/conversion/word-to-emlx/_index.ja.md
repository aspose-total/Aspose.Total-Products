---
title: Python で WORD を EMLX に変換する
description: Microsoft Word や Outlook を使用せずに、Python アプリケーション内で WORD を EMLX に保存します。

family: total
platformtag: Python
feature: conversion
informat: WORD
outformat: EMLX
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python を使用して WORD を EMLX に変換する" h2="Microsoft Word<sup>&reg;</sup> または Outlook をインストールせずに、Python アプリケーションで WORD から EMLX への変換。" >}}

{{% blocks/products/pf/feature-page-summary %}}

アプリケーション内に WORD から EMLX への変換機能を追加しようとしている Python 開発者は誰ですか? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API は、変換プロセスの自動化に役立ちます。 これは、電子メール、画像、Microsoft Word 形式など、さまざまな形式を扱うさまざまな API の完全なパッケージです。 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) パッケージの一部である [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) および [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API により、Python を使用してこの変換が容易になります。 これは 2 段階のプロセスです。最初に WORD ファイルをロードし、[Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) を介して HTML にレンダリングします。 次に、[Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) を使用して変換された HTML を読み込み、EMLX 形式に保存します。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python で WORD を EMLX に変換する方法" %}}

- [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) クラスを使用してソース WORD ファイルを開きます。
- 出力 HTML ファイル パスと関連する HTML 保存オプションをパラメーターとして指定して、`save` メソッドを呼び出します。 したがって、WORD ファイルは指定されたパスで HTML に変換されます。
- MailMessage.load を使用して、保存した HTML ファイルをロードします。
- 関連するファイル パスを指定して save メソッドを呼び出します。最後にWORDが変換されます

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}

- WORD から EMLX への変換には、Python 3.5 以降が必要です。
- プロジェクト内の API を PyPI から直接参照 ([Aspose.Words](https://pypi.org/project/aspose-words/) および [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- または、次の pip コマンド ```pip install aspose.words``` および ```pip install Aspose.Email-for-Python-via-NET``` を使用します。 
- さらに、Microsoft Windows または Linux ベースの OS ([Words](https://docs.aspose.com/words/python-net/system-requirements/) および [Email](https://docs.aspose.com/email/python-net/system-requirements/) の詳細を参照) および Linux の場合は、gcc および libpython の追加要件を確認し、ステップバイステップの手順に従ってください [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PythonでWORDをEMLXに保存" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

Python API を使用した Word から EMLX への変換は、ワードプロセッシング文書を特定のメール環境で一般的に使用される EMLX メッセージファイルに変換することを可能にします。これにより、文書の内容を保存したり、メール中心の形式で再利用したりする必要があるシナリオ（閲覧、転送、アーカイブなど）をサポートします。

自動化システムにおいて、この変換は文書を構造化されたメールアーティファクトに変換し、メッセージの保存、移行、またはコミュニケーション処理パイプラインに組み込むことで、ワークフローの継続性を向上させます。

{{% blocks/products/pf/agp/feature-section-col title="主な使用ケース" %}}

* **メールクライアント互換性**
  文書の内容を EMLX ファイルに変換し、互換性のあるメッセージング環境で使用できるようにします。

* **文書ベースのメッセージアーカイブ**
  Word で作成されたコンテンツを、整理された保存に適したメッセージ形式で保持します。

* **クロスフォーマット コンテンツ再利用**
  同じソース素材を文書とメール指向の両方の目的に利用できるようにします。

* **移行準備**
  文書ソースからメッセージ互換ファイルが必要な移行をサポートします。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自動化シナリオ" %}}

* **自動メールファイル変換**
  Word 文書を EMLX 出力に変換し、保存または後のインポートに使用します。

* **保持ワークフロー支援**
  業務文書をメール形式のレコードに変換し、構造化されたアーカイブに利用します。

* **バッチコンテンツパッケージング**
  標準化された文書テンプレートから大規模にメッセージファイルを生成します。

* **システム統合パイプライン**
  EMLX 出力を、より広範なコンテンツおよびコミュニケーションワークフローの中間資産として使用します。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}