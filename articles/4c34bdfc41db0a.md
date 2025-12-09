---
title: "IS-IS触ってみた"
emoji: "🦁"
type: "tech" # tech: 技術記事 / idea: アイデア
topics: [network, is-is, tech]
published: false
---

本記事は[いちぴろ・エクスプローラ Advent Calendar 2025](https://qiita.com/advent-calendar/2025/ichipiro-explorer) Day 15の記事です.

本記事は, 有名なルーティングプロトコルであるIS-IS(Intermediate System to Intermediate System)に触れて, その挙動を見るものになります.

## はじめに
aa

## IS-ISとは？
IS-ISとはIGPの一つで, 各ルータの接続状況をもとにして経路を決定するリンクステートアルゴリズムを用いるプロトコルです.
元々, OSI向けのルーティングプロトコルとして開発されましたが, TCP/IPにも対応したという経緯があります.
IS-ISに関連するRFCは以下
- RFC1195
- RFC5120
- RFC8202

海外のISPでよく使用されていることが知られていますが, 国内でもSRv6の注目を受けて話題に上がることも多くなってきた印象です.

## 検証で使用するネットワーク構成

## 投入したコンフィグ

## 動作検証


## まとめ