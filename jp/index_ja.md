[Global Home](/R-layer-Mode-Theory/index.html) · [English](/R-layer-Mode-Theory/en/index_en.html) · [日本語](/R-layer-Mode-Theory/jp/index_ja.html)

# R-layer Mode Theory (RLMT)
Tsuyoshi Tohi による、理論宇宙論の独立研究です。2026 年 7 月からは予言を宇宙論のデータで検証し、否定的な結果や訂正も含めてすべての結果を報告しています。

---

## 🔷 現在の状況（2026年11月）
2026 年 7 月からは、理論をデータで検証しています。2026 年の論文では、RLMT の予言を Planck・ACT・SPT・DESI・Pantheon+・DES の超新星の公開尤度に当てはめ、否定的な結果や訂正もすべて報告しています。以前の巻と食い違う場合は、2026 年の論文を優先します（下の「アーカイブ」を参照）。

**これまでにデータからわかったこと**
- **原始スペクトル（RLMT-lite）。** Planck 2018 単独では Δχ² = +0.9、ΔAIC = +10.9。ACT DR6 と Planck を合わせると（P-ACT-lite）Δχ² = −4.4、ΔAIC = +5.6。パラメータが少ない分 ΛCDM が有利で、データは三モードの混合を排除も要求もしていません。
- **Lindblad 力学からのスペクトル。** 最小の形（Ω 層がインフレーションの時計の外にある）の RLMT は、特徴のないべき乗則を予言します。理論からは決まらない係数 μ をもう一つ加えると、CMB の減衰尾部に小さな特徴を予言します。平均の音速で曲率ゆらぎを作ると、μ = 1 と弱結合の冪 ν = 0.3 の模型は P-ACT-lite と整合します（緩和の始まりの鋭さにより Δχ² = −1.7〜−4.0。見かけの有意性を補正した全体の有意性は約 1.3σ）。ただし特徴は小さく、Simons Observatory でも検出は難しい見込みです（約 1.6σ）。
- **非ガウス性。** 各モードが音速 c_s = 1 で作られるなら f_NL = 0。係数 μ がある場合は小さな負の等辺型の f_NL（μ = 1 で −0.2〜−0.3 程度）。現時点では検証できません。
- **テンソル。** RLMT は現時点で r を予言しません（地平線の出口として読む直接の写像は退けました）。
- **ハッブル緊張。** これまでに試したどの RLMT の模型も、H0 を局所の値に近づけません。後期の Ω 層の暗黒エネルギー模型は w0wa と同程度に当てはまりますが、H0 は 68〜69.5 km/s/Mpc 程度に留まります。改善は「今日 w = −1、過去は幻影型」という形によるもので、RLMT ではない対照模型でも再現され、層の構造によるものではありません。超新星のデータの中にも、必要な大きさの赤方偏移・方向・局所の空洞への H0 の依存は見られません。
- **H0 = 73 に必要なもの。** 小さな代償でそこに届くのは、再結合の前に音の地平線を約 6.5% 縮める成分だけです。物質と放射の等量時に始まる早期暗黒エネルギーに、スケール不変なスペクトル（n_s = 1）を合わせると、SH0ES なしで H0 = 73.3 ± 0.5 になります。ただし S8 は 0.84〜0.85 に上がり、その代償は弱い重力レンズの観測により 1.8σ〜4.5σ と変わります。n_s を自由にすると、同じ模型の H0 は 70.1 ± 1.1 です。これは RLMT の模型ではありません。電子の質量を変える模型ではこれは再現されず、n_s = 1 では Δχ² が約 +71 悪くなります。
- **早期の修正重力。** 共形結合した Layer-2 のスカラーは厳密に暗黒放射になります（否定的な結果）。
- **宇宙定数。** Ω 層の Lindblad の散逸からは、観測される Λ は出ません（ユニモジュラーの機構で、内部の熱浴ならゼロ、de Sitter の地平線を熱浴とすると桁違いに大きすぎる）。
- **暗黒セクターとしての Ω 層。** 電弱スケールの U(1)_T セクターとして実現すると、非弾性の暗黒物質の基準点、m_χ = 277 ± 8 GeV と 56.6 GeV の暗黒光子・暗黒ヒッグスを与えます。今の間接探索・宇宙論・加速器の制限を 2.5〜10.5 の余裕で通ります。層をより大きな SU(3) の表現に置いても、新しい数は決まりません（否定的な結果）。この模型の低いスケールのインフレーションで n_s ≈ 0.963 になるのは 2% の調整をした場合で、調整しなければ n_s ≈ 1 です。その場合は早期の成分が必要ですが、RLMT はそれを与えません。
- **R 方向の近道。** GW170817 の制限により、実用的な近道はありません。
- **数値の道具。** hi_class の監査で、コードのいくつかの問題を見つけて直し、CLASS と hi_class の開発者に報告しました。

## 🔷 論文（2026年）
各項目は最新の版にリンクしています。以前の版は Zenodo の記録からたどれます。

- **RLMT: Lindblad Cosmogenesis, SU(2) Geometry, and a Numerical Confrontation with Planck 2018 Data** （親論文、第 2 版）  
  [10.51094/jxiv.5386](https://doi.org/10.51094/jxiv.5386) · [10.5281/zenodo.23131099](https://doi.org/10.5281/zenodo.23131099)
- **RLMT：モード振幅係数の表現論的起源と，テンソルセクター結合に関する否定的結果** （第 3 版）  
  [10.51094/jxiv.6151](https://doi.org/10.51094/jxiv.6151)（第 2 版） · [10.5281/zenodo.23356202](https://doi.org/10.5281/zenodo.23356202)（第 3 版）
- **RLMT: RLMT and the Hubble Tension: Primordial and Late-Time Ω-Layer Tests against Planck, ACT DR6, SPT-3G D1, DESI DR2, Pantheon+ and DES Supernovae, with Control Models, an H0 = 73 Stress Test with Restricted Early Dark Energy, a Varying-Electron-Mass Comparison, and Methodological Corrections** （ハッブル緊張の論文、第 9 版）  
  [10.5281/zenodo.24095632](https://doi.org/10.5281/zenodo.24095632)
- **Early dark energy at matter–radiation equality with a scale-invariant spectrum selects H0 ≃ 73 without SH0ES** （早期暗黒エネルギーの短報、第 2 版。Physics of the Dark Universe に投稿中）  
  [10.5281/zenodo.24211812](https://doi.org/10.5281/zenodo.24211812) · データとコード [10.5281/zenodo.23975271](https://doi.org/10.5281/zenodo.23975271)
- **RLMT: From Lindblad Relaxation to the Primordial Spectrum: A de Sitter Cosmogenesis Map, Symmetric Base Spectra, and the Relaxation Exponent** （Lindblad 写像の論文、第 1.4 版）  
  [10.5281/zenodo.24095771](https://doi.org/10.5281/zenodo.24095771)
- **RLMT: From a CMB fit to a testable dark sector — the Ω layer of R-layer Mode Theory as an electroweak-scale U(1)_T sector** （U(1)_T の論文、第 5 版）  
  [10.5281/zenodo.24213478](https://doi.org/10.5281/zenodo.24213478)
- **RLMT: Reading the Primordial Fossils of RLMT-lite** （化石の論文、第 1.2 版）  
  [10.5281/zenodo.23354922](https://doi.org/10.5281/zenodo.23354922)
- **RLMT: The Conformally Coupled Layer-2 Scalar Is Exactly Dark Radiation** （短報）  
  [10.51094/jxiv.6786](https://doi.org/10.51094/jxiv.6786) · [10.5281/zenodo.23272537](https://doi.org/10.5281/zenodo.23272537)
- **RLMT: Does the R-Layer Define a Preferred Foliation? A Nonequilibrium Three-Mode Clock and Its Ghost-Condensate Limit**  
  [10.5281/zenodo.23274007](https://doi.org/10.5281/zenodo.23274007)
- **RLMT: Do Shortcuts Through the R-Direction Exist? Constraints from GW170817 and the Layered Expansion of Vol. XLI-L**  
  [10.5281/zenodo.23275612](https://doi.org/10.5281/zenodo.23275612)

**数値の方法**
- **RLMT: A numerical audit of hi_class for a table-driven MTFE/RLMT background: consistency identities, a regularization floor, and the resulting σ8** （hi_class の監査、第 3.1 版）  
  [10.5281/zenodo.23827616](https://doi.org/10.5281/zenodo.23827616)
- **RLMT: When does the kineticity regularization of hi_class bias σ8? An identity for the k² coefficient and two failures of the x formulation at a field turnaround**  
  [10.5281/zenodo.23934021](https://doi.org/10.5281/zenodo.23934021)

**技術的な基礎**
- **RLMT: R-layer Mode Theory Appendix X-II: Technical Foundation — Continuous Mode Tension, Topological Sectors, Particle Hypotheses, and Research Boundaries** （第 1.4 版）  
  [10.5281/zenodo.24218113](https://doi.org/10.5281/zenodo.24218113)

各論文のコードは、Zenodo の記録に添付してあります。上の ΔAIC は、識別できる追加パラメータ 5 個で数えた値です（誤りの記録 ERR-006）。Zenodo の最新版はすべて 5 個で数えています。親論文（Jxiv 5386・Zenodo 23131099）と、表現論の論文の Jxiv 版は 7 個で数えた値を載せており、次の版で訂正します。

---

## 🗄 アーカイブ（理論だけの Volumes、2026 年 3〜7 月）
RLMT は 2026 年 3 月 16 日に初めて文書化しました。その時期の Volumes は、理論の発展の記録として残しています。これらは理論だけの文書で、データには当てはめていません。2026 年 7 月以降の論文（RLMT: ...）が検証して置き換えた主張には、Vol. XLI の H0 の三つ組や、Vol. XLI-L の層ごとの膨張率があります。

- [Volume 一覧](volumes_ja.md)（タイトル・概要・DOI。本文は英語版）
- [RLMT の紹介](rlmt_intro_ja.md)（当初の概要を、書かれたまま保存）

---

## Language
- **日本語**（現在）
- [English](../en/index_en.html)
