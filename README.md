#### アンラーニング
<details>
<summary>"Pre-training for Recommendation Unlearning", Guoxuan Chen, Lianghao Xia, Chao Huang, SIGIR, 2025</summary>
削除要求から構築した影響依存行列と学習済み埋め込みを用いて、事前学習済みの影響エンコーダがアンラーニングに必要な埋め込み補正量を推定する手法 **UnlearnRec** を提案。
</details>

<details>
<summary>"Recommendation Unlearning", C. Chen, F. Sun, M. Zhang, and B. Ding, WWW, 2022.</summary>
推薦システム向けに SISA を拡張したアンラーニング手法 RecEraser を提案。データをシャードに分割してサブモデルを学習しておくことで、削除要求時には該当シャードのみを再学習し、全体再学習に比べて忘却コストを削減する。
</details>

<details>
<summary>"UltraRE: Enhancing RecEraser for Recommendation Unlearning via Error Decomposition", Y. Li, C. Chen, X. Zheng, W. Liu, L. Lyu, Y. Zhang, D. Meng, and J. Wang, NeurIPS, 2023.</summary>
推薦システム向けアンラーニング手法 RecEraser を、誤差分解（Error Decomposition）により拡張した UltraRE を提案。RecEraser が抱える忘却効率と推薦精度のトレードオフを改善し、削除対象データの影響を除去しつつ、高い予測性能と効率的な再学習を両立する。
</details>


#### 人気バイアス
