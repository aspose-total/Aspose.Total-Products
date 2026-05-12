---
title: Python で XPS を EMAIL に変換する
description: Microsoft Word や Outlook を使用せずに、Python アプリケーション内で XPS を EMAIL に保存します。

family: total
platformtag: Python
feature: conversion
informat: XPS
outformat: EMAIL
otherformats: EMAIL MSG PST OST OFT EML EMLX MBOX ICS VCF
---
{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Python を使用して XPS を EMAIL に変換する" h2="Microsoft Word<sup>&reg;</sup> または Outlook をインストールせずに、Python アプリケーションで XPS から EMAIL への変換。" >}}

{{% blocks/products/pf/feature-page-summary %}}

アプリケーション内に XPS から EMAIL への変換機能を追加しようとしている Python 開発者は誰ですか? [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) API は、変換プロセスの自動化に役立ちます。 これは、電子メール、画像、Microsoft Word 形式など、さまざまな形式を扱うさまざまな API の完全なパッケージです。 [Aspose.Total for Python via .NET](https://products.aspose.com/total/python-net/) パッケージの一部である [Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) および [Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) API により、Python を使用してこの変換が容易になります。 これは 2 段階のプロセスです。最初に XPS ファイルをロードし、[Aspose.Words for Python via .NET](https://products.aspose.com/words/python-net/) を介して HTML にレンダリングします。 次に、[Aspose.Email for Python via .NET](https://products.aspose.com/email/python-net/) を使用して変換された HTML を読み込み、EMAIL 形式に保存します。

{{% /blocks/products/pf/feature-page-summary %}}

{{< blocks/products/pf/agp/feature-section >}}
{{% blocks/products/pf/agp/feature-section-col title="Python で XPS を EMAIL に変換する方法" %}}

- [Document](https://reference.aspose.com/words/python-net/aspose.words/document/) クラスを使用してソース XPS ファイルを開きます。
- 出力 HTML ファイル パスと関連する HTML 保存オプションをパラメーターとして指定して、`save` メソッドを呼び出します。 したがって、XPS ファイルは指定されたパスで HTML に変換されます。
- MailMessage.load を使用して、保存した HTML ファイルをロードします。
- 関連するファイル パスを指定して save メソッドを呼び出します。最後にXPSが変換されます

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="変換要件" %}}

- XPS から EMAIL への変換には、Python 3.5 以降が必要です。
- プロジェクト内の API を PyPI から直接参照 ([Aspose.Words](https://pypi.org/project/aspose-words/) および [Aspose.Email](https://pypi.org/project/Aspose.Email-for-Python-via-NET/))
- または、次の pip コマンド ```pip install aspose.words``` および ```pip install Aspose.Email-for-Python-via-NET``` を使用します。 
- さらに、Microsoft Windows または Linux ベースの OS ([Words](https://docs.aspose.com/words/python-net/system-requirements/) および [Email](https://docs.aspose.com/email/python-net/system-requirements/) の詳細を参照) および Linux の場合は、gcc および libpython の追加要件を確認し、ステップバイステップの手順に従ってください [INSTALL](https://docs.aspose.com/words/python-net/installation/)
 

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="PythonでXPSをEMAILに保存" offSpacer="" %}}

{{< gist "aspose-com-gists" "1dbc5b4bf28dba34207d9bb94cbc149e" "convert-word-to-email-via-python.py" >}}

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

{{< blocks/products/pf/agp/feature-section >}}

XPS から EMAIL への変換を Python API で実現すると、チームは固定レイアウトのドキュメントコンテンツを配布、アーカイブ、通信ワークフローでの処理が容易なメール対応フォーマットに変換できます。これは、レポート、請求書、通知、または生成されたドキュメントを手動でコピーや書式設定することなく、再利用可能なメッセージ資産に変換する必要がある組織にとって価値があります。

自動化重視の環境では、XPS をメール対応出力に変換することで配信効率が向上し、スケーラブルなドキュメント通信をサポートし、ドキュメントパイプラインを通知システム、アーカイブツール、ワークフローオーケストレーションプラットフォームと統合するのに役立ちます。

{{% blocks/products/pf/agp/feature-section-col title="主な使用例" %}}

* **ドキュメントベースのメール配信**  
  XPS ドキュメントをメール対応コンテンツに変換し、レポート、明細書、通知を構造化されたメッセージングワークフローで共有できるようにします。

* **自動化コミュニケーションパイプライン**  
  ドキュメントを生成し、手動介入なしで即座に外部メール処理のために準備するシステムをサポートします。

* **アーカイブとトレーサビリティ**  
  メール指向のフォーマットでドキュメント情報を保持し、通信アーカイブ内で保存、インデックス付け、レビューが可能です。

* **ワークフロー統合**  
  ドキュメント生成システムとメッセージング、レビュー、コンプライアンスプロセスを統合されたパイプラインで接続するのに役立ちます。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="自動化シナリオ" %}}

* **スケジュールされたレポート配信**  
  自動化により、定期的な XPS レポートをメール対応出力に変換し、日常的な社内外のコミュニケーションに利用できます。

* **イベントトリガー通知**  
  特定のビジネスイベントが発生した際に、新しく生成された XPS ドキュメントをメールコンテンツに変換できます。

* **大量通信処理**  
  大量のドキュメントバッチをプログラムで変換し、スケーラブルなメッセージ作成とルーティングが可能です。

* **コンプライアンス通信ワークフロー**  
  自動化パイプラインは、監査やガバナンスの要件に合わせて、ドキュメントベースのメール記録を生成、変換、保存できます。

{{% /blocks/products/pf/agp/feature-section-col %}}

{{< /blocks/products/pf/agp/feature-section >}}
{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}

{{< blocks/products/pf/agp/other-autogen-total >}}

{{< /blocks/products/pf/main-wrap-class >}}

{{< /blocks/products/pf/feature-page-wrap >}}