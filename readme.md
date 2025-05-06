# Awesome Quality Assurance Roadmap [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

## Contents
- [Introduction](#introduction)
- [Test Plan Sample](#test-plan-sample)
- [The Road Map](#the-road-map)
- [Advices](#advices)

## Introduction

テストは、あらゆる製品ライフサイクルにおいて不可欠な工程である。それが食品であれ、自動車であれ、ソフトウェアであれ、製品の成果物は期待される結果と一致し、当初のニーズを満たす必要がある。

ソフトウェアの各コンポーネントがどのように動作し、相互に連携するかを理解すること、さらに「壊す」スキルを習得することは、QAエンジニアにとって基本的かつ重要な素養である。ソフトウェアテストとは、ソフトウェアを調査・解析し、意図しない挙動や想定外のシナリオを引き起こす可能性のある問題を発見する技術的営みである。

以下に、QAおよびソフトウェアテストを学ぶためのステップを示す。これを基に、学習の旅路を始めてほしい。

## Test Plan Sample

QAチームが作成すべき最も重要な文書の一つがテスト計画書である。これがなければ、チームは視界不良の状態で活動することとなり、基準が不明確なまま、開始タイミングや各種テストの実施タイミングを誤ることで、納品品質が損なわれ、結果として不良コードのリリースに繋がりかねない。

テスト計画書の構成や内容は、プロジェクトや納品物の性質によって異なるが、ここでは汎用的かつ標準的な構成を持つPDFを提示する。あらゆるソフトウェアテストの現場で参考になる文書である。

PDFファイルのダウンロードは以下のリンクから可能である：[test_plan_sample.pdf](https://github.com/anas-qa/Quality-Assurance-Road-Map/blob/master/Test_Plan_Sample.pdf)

## The Road Map

![QA Engineer Road Map 2022](https://i.imgur.com/cM9cM8T.png)
![QA Engineer Road Map 2022](https://i.imgur.com/meodAKp.png)

## Advices

- 自分が失敗する様子を見たことのないテストコードは信用してはならない。

- ソフトウェアテストの本質を理解しないまま、いきなり自動化に手を出すべきではない。個人的には、自動化とは反復作業を効率化するための手段に過ぎないと考える。まずは適切なテスト基準を設計し、その後に自動化を行うことで、その設計が再利用・再実行可能な形に昇華される。

- 自動化とは、手動で設計・記述されたテストを、可読性・理解性・再利用性を備えたコードとして再構成することである。

- 自分のテストコードが、本当に何かを検証しているかを常に確認すべきである。

- テストコードそのものが、テストされるような状態であってはならない。

- HTTP 200 OK のステータスが常に「正常」を意味するとは限らない。特に、認証されていないAPI呼び出しに対して200ステータスが返ってきた場合、それはソフトウェアのセキュリティリスクとなる。ステータスコードのみに依存したテストは危険である。

## Contributing

貢献方法については、[contributing.md](https://github.com/fityanos/awesome-quality-assurance-road-map/blob/master/contributing.md) を参照。
