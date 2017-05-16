# tensorflow-models
Tensorflow를 활용해서 다양하고 재미있는 실험들을 진행합니다.

## Word2Vec-Kor
word2vec에 한국어 문장을 적용해봅니다.나무위키와 위키피디아의 문장을 전처리해서 사용합니다.

## CNN Sentence Classification
한국어 문장 분류 모델을 적용합니다.
(Convolutional neural networks for sentence classification (2014), Y. Kim)
학습된 word vector에 CNN 모델을 적용하고 NBT에서 사용중인 컨텐츠 태깅 데이터로 학습시키고 정확도를 확인합니다.

## Title-CTR Model

컨텐츠의 타이틀로 CTR을 예측할 수 있는 모델을 실험합니다.
CNN과 Word Embedding을 사용하여 실험해봅니다.
NBT에서 수집한 3년간의 컨텐츠 반응이력으로 학습시키고 정확도를 확인합니다.
