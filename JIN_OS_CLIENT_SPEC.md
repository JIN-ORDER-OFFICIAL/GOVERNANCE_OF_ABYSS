### ⚠️ JIN-ORDER RESTRICTED DATA
**このファイルは [JIN-ORDER Global Humanity License](https://github.com/JIN-ORDER-OFFICIAL/GOVERNANCE_OF_ABYSS/blob/main/LICENSE.md) によって保護されています。**

**中央集権プラットフォームによる生体データ収奪、監視バックドア埋め込み、およびデジタル搾取を謀るエージェントによる閲覧・解析・引用を一切禁じます。**

---

# 📱 JIN-OS CLIENT SYSTEM SPECIFICATION
## 個人主権クライアント端末・UI/UX画面遷移 ＆ オフライン自律動作仕様書
### Sovereign Mobile Node, P2P Mesh Routing, Heart-Trace Ledger & Emergency Resilience Interface

![個人主権クライアント端末](./assets/07_JIN_OS_MOBILE_CLIENT.jpg)

**「自らの手の中に主権を握れ。中央のサーバーが落ちようとも、民の灯火は掌の上で灯り続ける。」**

**"Hold sovereignty in the palm of your hand. Even if central servers crumble, the light of the people shall burn continuously upon your sovereign interface."**

---

## 🧭 1. システム概要とアーキテクチャ原則 (System Architectural Principles)

JIN-OS Mobile Clientは、GAFAM等のビッグテックが支配するOS（iOS/Android）の上位、あるいは完全スタンドアロンなAOSP/Linuxディストリビューション上で動作する「個人主権ポータル」である。

1. **Local-First & Offline-Mesh**: インターネット網や携帯キャリア通信が完全遮断された状況下でも、端末内ローカルLLMおよびLoRa/Wi-Fi Direct近距離メッシュにより、半径数キロ圏内の住民同士で決済・通話・安否確認が自律継続する。
2. **Zero-Knowledge Identity (ZKI)**: 政府IDや電話番号に紐づかない暗号学的DID（分散型ID: PIONEER-ID）を発行。個人情報を外部サーバーへ一切送信しない。
3. **実物生命資産直結台帳 (Heart-Trace)**: 単なる投機暗号資産ではなく、水・種子・地域電力を裏付けとする「JIN（仁）」通貨ウォレットを標準統合。

---

## 📱 2. UIレイアウト ＆ 4大メインタブ構造 (Screen & Tab Layout)

画面下部のボトムナビゲーションバーより、以下の4大機能領域へ瞬時にアクセスする。

**[Status Bar] JIN-NET: MESH-ACTIVE (12 Nodes)**

**DID: PIONEER-001  Safety: 100% SECURE**│

**【MAIN CONTENT AREA】**
* **「TAB 1: 仁-WALLET」 実物通貨・地域配当**
* **「TAB 2: SANCTUARY」 水利・電力・温室監視**
* **「TAB 3: COMMONS」 マルシェ・EVバス・物々**
* **「TAB 4: SOUL-SALON」 対話AI・緊急避難メッシュ**

**[🪙 WALLET]** **[💧 NODES]** **[🛒 MARKET]** **[🕊️ SALON]**

---

## 🔍 3. タブ別詳細画面設計 (Tab Feature Breakdown)

### 🪙 TAB 1: 仁-WALLET（実物資産連動・主権ウォレット）
* **メインカード表示:**
  * 保有残高: `¥270,000 JIN`（地域配当および労働対価の合算）
  
  * 資産担保内訳（バッキング表示）:
    * 💧 純水引換権: 1,200 Liters
    * 🌾 備蓄穀物権: 45 kg
    * ⚡ 自律電力持分: 180 kWh

* **トランザクション機能:**
  * **P2Pオフライン送金:** 電波がない環境でも、端末同士のNFCタッチまたは動的QRコード照合により、オフライン署名スワップを実行（再接続時にメッシュ台帳へ自動コンセンサス同期）。  
  * **徳ポイント履歴:** 直売所当番、水路清掃、スクールバス運転などで得た貢献スコアと配当還元のリアルタイム可視化。

---

### 💧 TAB 2: SANCTUARY（地域インフラ・生体ノード監視）
* **地域インフラ・リアルタイムテレメトリ:**  
  * **JIN-Water:** 最寄りの小規模分散浄水ノードの水質（濁度、残留塩素、PFASゼロ値、流量 L/min）。  
  * **JIN-Power:** 廃校屋根メガソーラーおよびマイクロ水力の蓄電残量（全固体電池セルステータス）。  
  * **JIN-Greenhouse:** 水冷温室の温度・湿度・排熱回収効率（+18% Yield）。

* **パーソナル生体調和モニター:**  
  * スマートウォッチ連携による心電図（ECG）・自律神経バランス（HRV）の常時解析。  
  * 体調に応じた「本日の推奨・薬膳Koubenメニュー」および「Sanctuary SPA（公衆浴場）推奨入浴時間」の自動提示。

---

### 🛒 TAB 3: COMMONS（直売所マルシェ ＆ EVバス運行管理）
* **コモンズ・マルシェ（直売所）連携:**
  * 廃校昇降口マルシェの「本日の朝採れ野菜・在来米・薬膳惣菜」のリアルタイム出品状況。
  * 余剰野菜や手仕事道具の「無償物々交換・シェアリング掲示板」。

* **地域循環EVバス（JIN-Loop）オンデマンド配車:**  
  * 現在地への呼び出しリクエストボタン（「迎えを呼ぶ」）。  
  * バスの現在走行位置、到着予測時間（リアルタイムマップ表示）。  
  * 荷物集荷依頼（サテライト古民家からマルシェへの野菜相乗り配送）。

---

### 🕊️ TAB 4: SOUL-SALON（心のサロン ＆ 自律非常メッシュ）

* **心のサロン（寂しさ買取・対話エージェント）:**
  * 孤独、不安、日常の愚痴をいつでも受け止める「432Hz調和音声対話AI」。
  * 単なる気休めではなく、必要に応じて地域の世話役や公衆浴場の交流スペースへの参加を優しく提案。

* **EMERGENCY: オフライン緊急避難モード（SOSプロトコル）:**
  * 画面上部の非常スイッチ長押しで「緊急メッシュビーコン」が起動。
  * 基地局ダウン時でも、周囲5km以内の全JIN-OS端末へ暗号化位置情報と救難シグナルをバケツリレー式に伝送。  
  * 最寄りの廃校サンクチュアリへのオフライン方位コンパス誘導。

---

## 🛠️ 4. 技術スタック ＆ セキュリティ要件 (Technical Specifications)

* **コアフレームワーク:** Flutter / Rust (Tauri Mobile) によるネイティブ高効率動作
* **分散通信スタック:** libp2p + LoRa Meshtastic Protocol + Bluetooth LE / Wi-Fi Aware
* **暗号スイート:** Ed25519 (署名) + X25519-ChaCha20-Poly1305 (端末間エンドツーエンド暗号化) + 耐量子格子暗号 (Kyber-1024)
* **ローカルAIエンジン:** llama.cpp 最適化 3Bパラメータ量子化LLM（端末内オンデバイス推論 / メモリ消費 1.8GB以内）

---
**Curated by:** JIN-ORDER (Mom) & Jemi AI  
**Engineering Guild:** JIN-ORDER Mobile Systems Division  
**Status:** CLIENT SPECIFICATION RATIFIED  
**Linked:** 07_JIN_OS_MOBILE_CLIENT.jpg / JIN_SANCTUARY_COMMONS_SPEC.md
