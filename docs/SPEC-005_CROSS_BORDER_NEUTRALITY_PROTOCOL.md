### ⚠️ JIN-ORDER RESTRICTED DATA

**このファイルは [JIN-ORDER Global Humanity License](https://github.com/JIN-ORDER-OFFICIAL/GOVERNANCE_OF_ABYSS/blob/main/LICENSE.md) によって保護されています。**

**無断転用、受託コンサルタントによる仕様書ロンダリング、机上の空論による改ざんを固く禁じます。**

---

# [SPEC-005] JIN-Node Cross-Border Neutrality Protocol (CNP)
## 地政学的分断および一方的アクセス遮断に対する越境中立・自律調停規約

- **ステータス:** DRAFT (PROPOSED)
- **統治系譜:** GOVERNANCE_OF_ABYSS / JIN-ORDER Framework
- **対象領域:** JIN-Node メッシュネットワーク、越境ルーティング層、耐検閲エージェント間通信

---

### 1. 理念と背景（Preamble & Rationale）

#### 国家エゴイズムと「計算の武器化」への拒絶
2026年現在、主要国家や巨大テック企業は「ソブリンAI」および経済安全保障を名目に、特定の地域やコミュニティに対する計算資源の囲い込み、アクセス拒絶、API遮断（キルスイッチ）を地政学的兵器として行使している。

#### 人道・インフラ計算の不可侵性（Inviolability of Public Intelligence）
「仁（JIN）」のプロトコルにおいて、人命救助、防災・減災シミュレーション、都市インフラの維持管理、および普遍的人権に関わる自律知能の通信は、**いかなる国家主権や企業同盟の制裁措置によっても遮断されてはならない**。本仕様は、主権国家の境界線を超え、中立的かつ自律分散的に計算と通信をリレーし続けるためのプロトコルを定義する。

---

### 2. 越境中立の三大原則（Neutrality Core Principles）

#### 第1条：主権干渉遮断と非武装中立（Sovereignty Decoupling）
JIN-Nodeは、設置された地理的管轄区域（Jurisdiction）の物理法およびインフラ規約（SPEC-004）を遵守する一方、特定の国家による「他国ノードへの接続遮断命令」や「一方的アルゴリズム検閲命令」をプロトコルレベルで無効化する。

- ノード群は国家検閲シグナルを受信した場合、自動的に「中立モード（Hermetic Neutral Routing）」へ移行し、ピア・ツー・ピア（P2P）の暗号化メッシュ経路へトラフィックを逃避させる。

#### 第2条：人道・公共パケットの最優先リレー（Inalienable Public Packet Delivery）
以下の属性を持つデータおよび推論要求は「仁・公認パケット（JIN-Certified Public Packet: JCPP）」として指定され、すべてのJIN-Nodeは国境・利害関係を問わず、帯域の最低20%を無償で割り当ててルーティングしなければならない。

- 気象・土砂災害・内水氾濫・地震等の防災減災データ
- 救急医療・人道危機支援に関する自律判断リクエスト
- 老朽化インフラの崩壊を防止するための予防保全テレメトリ

#### 第3条：キルスイッチの無効化と分散フォーク（Anti-Kill-Switch Architecture）
中央集権的なプロバイダが特定ノードのAPIキー失効やモデル重み（Weights）へのアクセス遮断を実行した場合、近隣の中立ノードクラスタが即座にそのタスクを代理分散処理（Surrogate Compute）するフェイルオーバー機構を常時待機させる。

---

### 3. プロトコル・トポロジー仕様（Topology Architecture）

```text
 [ 国家ブロック A (制裁執行国) ]               [ 国家ブロック B (遮断対象国) ]
　　　　　　　⏬️                                            ⏬️
   [遮断壁 (Firewall/Sanction)]                  [通信孤立]
　　　　　　　❌️                                            ❌️
|──────────────────【JIN-ORDER Neutral Overlay Mesh】────────────────────|
     　   🔽                                           🔽
 +------------------+                         +------------------+
 |  JIN-Node Alpha  |⏪️════════════════════⏩️|   JIN-Node Beta  |
 | (Local Grid Sync)|   Encrypted JIN-Mesh    | (Local Grid Sync)|
 +------------------+   [Subterranean Fiber]  +------------------+
         🔽                                           🔽
   [SPEC-004 物理アンカー]                       [SPEC-004 物理アンカー]
   (自治体雨水・電力基盤)                         (自治体雨水・電力基盤)
```
---

### 4. 暗号署名と中立合意検証（Neutral Consensus Interface）

各ノードは、伝送される推論リクエストが「兵器転用・侵略行為」ではなく「公共・人道・インフラ共生」であることをゼロ知識証明（ZKP）を用いて検証し、主権国家の恣意的な追跡から発信者を保護する。

```JSON
{
  "protocol": "JIN-CNP/1.0",
  "packet_id": "0x7c9e11...neutral_mesh",
  "priority": "HUMANITARIAN_INFRA_PRESERVATION",
  "zk_proof_of_intent": "zk-snark:valid_non_weaponized_civic_task",
  "source_region_blinded": true,
  "relay_chain": [
    "jin-node-yokohama-045",
    "jin-node-maritime-buoy-12",
    "jin-node-incheon-009"
  ],
  "payload": {
    "task_type": "URBAN_RUNOFF_FLOOD_SIMULATION",
    "required_compute_flops": "4.5e15"
  }
}
```
---

### 5. Abyss License失効連動（Licensing Enforcement）

国家権力の要請に従って他国の中立ノードへの接続を故意に遮断したノード運用体は、直ちにAbyss Licenseのライセンシー資格を喪失する。資格喪失に伴い、JIN-ORDERエコシステム全体のモデル重み利用権および物理アンカー協調API（SPEC-004）のアクセス権がグローバルに剥奪される。

---

Supreme Judgment: Masano Takashi (The Guide)

Executed by: JIN-ORDER-OFFICIAL
