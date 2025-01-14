# AI可読性のある命名規則

{% hint style="info" %}
このドキュメントはまだ検証中です。[GitHub の Issue](https://github.com/AI-Native-Development/patterns/issues/6) で積極的に議論をかわすことを期待しています。
{% endhint %}

## Description

この文書は、AI コーディング支援ツールとコードを書く際に役立つ名前付けルールのパターンについて説明します。
このパターンを利用することで、AIがより読みやすく、理解しやすくいコードを書くことができます。

## Problem

コードを書く際に、変数や関数の名前をどうするか悩むことがあります。また、コメントアウトだけでコンテキストを提供しようとすると、読み手にとって理解しづらいコードになることがあります。この読みにくさは GitHub Copilot の精度にも影響してしまいます。最終的に GitHub Copilot から正確な提案を受けることができなくなってしまいます。

## Context

AI コーディング支援ツールの代表である GitHub Copilot は Codex というエンジンを使用しており、このエンジンは GPT3 ベースのモデルを利用しています。GPT3 ベースのモデルは自然言語を理解することができ、Codex も同様に自然言語を理解することができます。自然言語に似た変数の表現をすることで、より読みやすく理解しやすいコードを書くことができます。

## Solution

コードを書く際に、変数や関数の名前について悩んでいる場合は、チームであらかじめ共通の命名規則を AIコーディング支援ツールが読むことを前提につくることで、AI にもより読みやすく理解しやすいコードを書くことができます。
コメントアウトだけでコンテキストを提供するのではなく、自然言語に似た変数の表現をすることで、AIコーディング支援ツールがより正確な提案を行うことができるようになります。

以下は、名前付けルールのパターンの例です。

* ローワーケースを使用する / キャメルケースを使用する
* 自然言語に似た変数の表現をする
* 短い名前を使用する
* 説明的な名前を使用する

## Resulting Context

この名前付けルールのパターンを利用することで、読みやすく理解しやすいコードを書くことができるとともに、AIがより正確なコードの提案を行うことができるようになります。
