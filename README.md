# Renova

## 日本語 / Japanese

ファイル名を一括で変更するデスクトップアプリです。

## 目的

Windowsの標準機能で複数のファイルを一括で名前変更すると、  
`(1)`, `(2)`, `(10)` のように **番号の桁数が揃わない** 形式になります。

見た目上は大きな問題がなくても、  
ファイルを読み込むソフトによっては **文字列順（辞書順）で処理**され、

file (1)<br>
file (10)<br>
file (2)<br>


のように、**意図しない順序になる場合があります。

Renovaは、この問題を防ぐために  
`01, 02, 03 ...` のように **桁数を揃えた連番リネーム** を
簡単に行えるようにすることを主な目的として開発されました。

## 特徴

- **「シンプルモード」** と **「シリーズモード」** の2種類を搭載
- 詳細設定は **右上の歯車アイコン** から変更可能
- 外観および動作の変更は、**アプリ再起動後に適用**されます
- バグ修正や改善が行われた場合、**新バージョンを公開**します  
  ※ 自動更新機能は搭載していません

## 主な機能（シンプルモード）

- 接頭辞を用いて、ファイル名に **連番を自動付与**
- 数字の **桁数を揃える** ことが可能  
  - 例：2桁指定の場合  
    `1 → 01`
- 開始番号を自由に設定可能
- 接頭辞と数字の間に  
  **スペース (` `)** または **アンダースコア (`_`)** を挿入可能

## 主な機能（シリーズモード）

- シンプルモードを拡張した、**より詳細な設定**が可能
- 一般ユーザー向けというより、**私的なファイル整理用途**を想定
- 利用は自己責任でお願いします

## 動作環境

- Windows 11 25H2
- ※ 上記環境でのみ動作確認を行っています  
  他のOSやバージョンでの動作は未検証です

---

## English / 英語

A desktop application for bulk file renaming.

## Purpose

When renaming multiple files using the standard Windows feature,
numbers are added in the format `(1)`, `(2)`, `(10)`,
resulting in **inconsistent digit lengths**.

While this may look fine visually,  
some applications sort file names **as plain text**, which can lead to
unexpected ordering such as:

file (1)<br>
file (10)<br>
file (2)<br>


Renova was developed primarily to prevent this issue by allowing
easy batch renaming with **zero-padded sequential numbers**
such as `01, 02, 03`, ensuring consistent and correct file order.

## Features

- Includes two modes: **Simple Mode** and **Series Mode**
- Advanced settings can be configured from the **gear icon in the top-right**
- Changes to appearance and behavior are applied **after restarting the app**
- Bug fixes and improvements are released as **new versions**  
  ※ This application does **not** include an auto-update feature

## Main Features (Simple Mode)

- Automatically assigns **sequential numbers** to file names using a prefix
- Allows you to **align the number of digits**  
  - Example: When set to 2 digits  
    `1 → 01`
- Customizable starting number
- You can insert either  
  **a space (` `)** or **an underscore (`_`)**  
  between the prefix and the number

## Main Features (Series Mode)

- Provides **more detailed and advanced settings** than Simple Mode
- Intended mainly for **personal file organization**
- Use at your own risk

## Environment

- Windows 11 25H2
- Tested only on the environment listed above  
  Other operating systems or versions have not been verified


