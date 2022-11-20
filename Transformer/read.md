# Transformer
* 기존에 존재하던 Seq2Seq 모델의 구조인 Encoder-Decoder 구조를 사용하면서 RNN이 아닌 Attention 기법으로 성능을 끌어올린 모델
* 예측에 주로 사용되며 감성 분석이나 챗봇 등을 제작 가능
<br></br>
![Transformer](https://user-images.githubusercontent.com/89456014/202886403-6d9136f6-eaea-4365-8cde-8780bee6560c.png)
* 크게 Encoder, Decoder 두 구조로 나뉘어져 있으며, input 데이터에 Positional Encoding 이라고 위치 정보를 더해 주는 것이 특징
