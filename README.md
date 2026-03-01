# レンアイシステム — キャラクターMOD サンプル
**Love System Character MOD Sample**

このリポジトリは、**レンアイシステム** 向けキャラクターMODの開発サンプルです。  
公式キャラクター「永山詩織」のMODデータを収録しており、MOD開発の参考としてご利用ください。

---

## 収録サンプル

| MOD ID | キャラクター | 説明 |
|--------|------------|------|
| `shiori_nagayama` | 永山詩織（Shiori Nagayama） | 街の病院に勤務する看護師。明るくサバサバした性格だが、怪我をしている人を見ると放っておけないタイプ。 |

---

## リポジトリ構成

```
shiori_nagayama/
├── mod.json           # MODメタデータ（必須）
├── character.json     # キャラクター定義（必須）
├── events.json        # イベントメタデータ（必須）
├── events/            # イベントスクリプト (41本)
├── portraits/         # 立ち絵 (PNG・背景透過)
│   └── spring/
│       └── casual/
├── cg/                # イベントCG (PNG/JPEG)
└── audio/             # BGM (MP3)
```

---

## インストール方法

MODフォルダをドキュメントフォルダ内の所定のディレクトリに配置してください。

### Windows
```
C:\Users\[ユーザー名]\Documents\lovesystem\mods\
```

### macOS / Linux
```
~/Documents/LoveSystem/mods/
```

### 手順

1. このリポジトリをクローン、またはZIPでダウンロードして解凍します
2. `shiori_nagayama/` フォルダを上記のディレクトリにコピーします
3. レンアイシステム を起動すると、MODが自動的に読み込まれます

配置後のフォルダ構成例（Windows）:

```
Documents\
└── lovesystem\
    └── mods\
        └── shiori_nagayama\   ← ここに配置
            ├── mod.json
            ├── character.json
            └── ...
```

---

## MOD開発について

このサンプルをベースに、独自のキャラクターMODを開発することができます。  
MODの仕様・作成ガイドは公式Webサイトをご参照ください。

**MOD開発ガイド**: https://lovesystem.info/mod/

---

## ライセンス

このサンプルデータはレンアイシステムの公式MODサンプルです。  
MOD開発の参考・学習目的でご利用ください。
