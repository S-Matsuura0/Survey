#### アンラーニング

<details>
<summary>"Pre-training for Recommendation Unlearning"</summary>

著者: Guoxuan Chen, Lianghao Xia, Chao Huang<br />
発表場所: SIGIR<br />
年度: 2025<br />
内容: 削除要求から構築した影響依存行列と学習済み埋め込みを用いて、事前学習済みの影響エンコーダがアンラーニングに必要な埋め込み補正量を推定する手法を提案。

</details>




<details>
<summary>"Recommendation Unlearning"</summary>

著者: C. Chen, F. Sun, M. Zhang, and B. Ding<br />
発表場所: WWW<br />
年度: 2022<br />
内容: 推薦システム向けに SISA を拡張したアンラーニング手法 RecEraser を提案。データをシャードに分割してサブモデルを学習しておくことで、削除要求時には該当シャードのみを再学習し、全体再学習に比べて忘却コストを削減する。

</details>




<details>
<summary>"UltraRE: Enhancing RecEraser for Recommendation Unlearning via Error Decomposition"</summary>

著者: Y. Li, C. Chen, X. Zheng, W. Liu, L. Lyu, Y. Zhang, D. Meng, and J. Wang<br />
発表場所: NeurIPS<br />
年度: 2023<br />
内容: 推薦システム向けアンラーニング手法 RecEraser を、誤差分解（Error Decomposition）により拡張した UltraRE を提案。RecEraser が抱える忘却効率と推薦精度のトレードオフを改善し、削除対象データの影響を除去しつつ、高い予測性能と効率的な再学習を両立する。

</details>




#### 人気バイアス


<details>
<summary>"Model-Agnostic Counterfactual Reasoning for Eliminating Popularity Bias in Recommender System"</summary>

著者: Tianxin Wei, Fuli Feng, Jiawei Chen, Zuozhu Wu, Jinfeng Yi, Xiangnan He<br />
発表場所: KDD<br />
年度: 2021<br />
内容: ユーザーの興味、人気への同調性、アイテムのグローバル人気度をマルチタスク学習で推定し、反実仮想推論によって人気度と同調性の直接効果を推薦スコアから抑制する、モデル非依存型の人気バイアス軽減手法を提案。

</details>


<details>
<summary>"EquiRate: Balanced Rating Injection Approach for Popularity Bias Mitigation in Recommender Systems"</summary>

著者: Mert Gulsoy, Emre Yalcin, Alper Bilge<br />
発表場所: PeerJ Computer Science<br />
年度: 2025<br />
内容: テールアイテムに対して合成評価値を注入することで学習データのアイテム人気度分布を均衡化し、推薦モデル自体を変更せずに人気バイアスを軽減する前処理型手法 EquiRate を提案。

</details>


<details>
<summary>"Disentangling User Interest and Conformity for Recommendation with Causal Embedding"</summary>

著者: Yu Zheng, Chen Gao, Xiang Li, Xiangnan He, Depeng Jin, Yong Li<br />
発表場所: WWW<br />
年度: 2021<br />
内容: 観測されたインタラクションをユーザーの興味と人気への同調性という二つの因果要因に分離し、正例・負例アイテム間の人気度差から原因別データを構成して、それぞれの埋め込みをマルチタスク・カリキュラム学習することで、ユーザーごとの同調傾向を反映した頑健かつ解釈可能な推薦を行う手法を提案。

</details>


