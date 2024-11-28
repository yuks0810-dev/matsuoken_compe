## サンプルコード
このフォルダで公開するコードはLLM講座2024の最終課題で利用可能なサンプルコードとなります。  
- LoRA_template_20241127.ipynb: SFTによるモデルの追加学習のためのコード  
- Model_Inference_Template_20241127.ipynb: 学習したモデルを用いた推論のためのコード  
となっております。 
これら2つのコードはOmnicampus上での動作を想定しています。  
他の環境で使用する場合は、適宜修正をお願いします。  

LoRA_template_20241127.ipynbを実行するだけでも課題提出に必要なjsonlファイルの生成とHugging Faceへのモデル提出は可能です。
ただし、Hugging Faceで作成が必要なREADME.mdには「Hugging Faceにアップロードしたモデルを用いて推論する方法」を書く必要があり、その際にModel_Inference_Template_20241127.ipynbが参考となります。  
  
また、Google Colabの無料版（T4）でも動作可能なunsloth版もございますが、こちらは若干、難易度が高いためコード内の説明をじっくり読んで慎重にお使いください。  
  
## 変更履歴
2024/11/28 LoRA_template_20241127.ipynbとModel_Inference_Template_20241127.ipynbのモデルのロードに関してコード内にコメント追加
2024/11/27 コードを刷新。Omnicampus上での実行することを想定したLoRA_template_20241127.ipynbとModel_Inference_Template_20241127.ipynbを追加  
2024/11/23 LoRA_template_unsloth2.ipynbに推論とjsonl出力のコードを追加  
2024/11/23 LoRA_template_unsloth2.ipynbのモデル保存の箇所を修正  
2024/11/23 Model_Inference_Template.ipynbのデータ読み込みの箇所を修正  
2024/11/22 LoRA_template_unsloth.ipynbで出力されるスコアが低いため、ハイパーパラメータのチューニングを行ったLoRA_template_unsloth2.ipynbを公開  
2024/11/20 コード公開  