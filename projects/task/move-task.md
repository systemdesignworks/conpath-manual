---
layout: default
title: タスクを移動する
parent: タスクの作成・編集
grand_parent: プロジェクト
nav_order: 2
has_children: false
---

# タスクを移動する
{: .no_toc }

## 目次
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## タスクを移動する

1. ツールバーの[選択]アイコンをクリックしてアクティブにします。
   
   <table><tr><td>
   <img src="/assets/images/activetool-selection.png" width="52px">
   </td></tr></table>

2. タスクをクリックして選択します。

   <table><tr><td>
   <img src="/assets/images/projects/task/move-task/1.png" width="40%">
   </td></tr></table>

3. 上下左右方向にドラッグし、目的のポイントでドロップします。
またはキーボードの矢印キーを押します。

   <table><tr><td>
   <img src="/assets/images/projects/task/move-task/2.png" width="40%">
   </td></tr></table>

   依存関係にあるタスクの始点、終点を越えるタスクの移動を行うとダイアログが表示され、[移動を実行]をクリックすると以降のタスクも連動して移動します。ダイアログの表示は、右クリックのコンテキストメニューから[依存関係のタスクを移動する際に確認ダイアログを表示]を選択してOFFにすることができます。

   <table><tr><td>
   <img src="/assets/images/projects/task/move-task/5.png" width="60%">
   </td></tr></table>

{: .note }
この操作では稼働日数が保持されたまま移動します。    

{: .warning }
タスクの移動には次の制約があります。  
・カレンダーの日付範囲外への移動はできません  
・依存関係にあるロックされたタスク、マイルストーンを越える移動はできません

## 複数のタスクをまとめて移動する

1. ツールバーの[選択]アイコンをクリックしてアクティブにします。

   <table><tr><td>
   <img src="/assets/images/activetool-selection.png" width="52px">
   </td></tr></table>

2. 対象全体を囲うように範囲選択、またはshiftを押しながら複数のタスクを選択します。

   <table><tr><td>
   <img src="/assets/images/projects/task/move-task/3.png" width="40%">
   </td></tr></table>
    
3. いずれかの要素、点線のボックスを上下左右方向にドラッグし、目的のポイントでドロップします。またはキーボードの矢印キーを押します。

   <table><tr><td>
   <img src="/assets/images/projects/task/move-task/4.png" width="40%">
   </td></tr></table>

   依存関係にあるタスクの始点、終点を越えるタスクの移動を行うと以降のタスクも連動して移動します。

{: .warning }
この操作では稼働日数は保持されません。    

{: .warning }
タスクの移動には次の制約があります。  
・カレンダーの日付範囲外への移動はできません  
・依存関係にあるロックされたタスク、マイルストーンを越える移動はできません