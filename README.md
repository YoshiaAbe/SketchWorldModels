# 世界モデルセミナー最終プロジェクト

# ファイル
*   README.md - ファイルの概要と参考文献を記載  
*   origin_start_sketching.py - "CLIPasso応用_感情認識_データセット生成_Master.ipynb"で使用。  
*   CLIPasso応用_感情認識_スケッチ画像.ipynb - colab環境。CLIPassoスケッチ画像データセットで感情認識を行ったファイル。  
*   CLIPasso応用_感情認識_プレーン画像.ipynb - colab環境。スケッチ画像とプレーン画像での感情認識の結果を確認するため、"CLIPasso応用_感情認識_スケッチ画像.ipynb"で使用したスケッチ画像データセットの生成元画像と同様同数のプレーン画像（元画像）を使用し同じようにクラス分けして感情認識を行ったファイル。  
*   CLIPasso応用_感情認識_データセット生成_Master.ipynb - colab環境。CLIPassoを使ってスケッチ画像データセットを生成するマスターファイル。実際のデータセット作成時はgoogle共有ドライブを使用してグループで分担して行った。  
*   CLIPasso応用_感情認識_Master.ipynb - colab環境用。FER-2013データセットで感情認識モデルの性能を確かめた。CLIPasso応用としての感情認識タスクのマスターファイル。  
*   （メモ）saliency map実装についてはneural rendererスケッチ生成コードと同様のため省略いたします。  

# 参考にしたブログ、コード、文献など
### CLIPasso, saliency map
*   論文/コード [CLIPasso](https://clipasso.github.io/clipasso/) 
*   論文 [Learning Transferable Visual Models From Natural Language Supervision](https://cdn.openai.com/papers/Learning_Transferable_Visual_Models_From_Natural_Language_Supervision.pdf)
*   ブログ [論文解説】自然言語処理と画像処理の融合 – OpenAI 『CLIP』を理解する(1)](https://data-analytics.fun/2021/03/24/understanding-openai-clip/)
*   ブログ [Saliency Mapを使って画像を良い感じに切り抜くAIを作った](https://qiita.com/ttyszk/items/833d3753248bbc8a211f)
*   ブログ [Saliency Mapを使って有名な絵画を分析してみる](https://qiita.com/ryota765/items/7a5941f7a80ce083f6fb)

### 感情認識
*   データセット [FER-2013](https://www.kaggle.com/datasets/msambare/fer2013)
*   コード [「少ないデータで転移学習を用いて画像内の表情を分類する」](https://github.com/zarakima/face-classification)  
