# Flax로 구현하는 Transformer 모델 구조.

* jax로 구현된 뉴럴 네트워크 라이브러리인 Flax는 numpy를 쉽게 GPU와 TPU에서 사용할수 있다는 장점이 있는 라이브러리 이며, 구글의 많은 연구자들의 논문 구현 라이브러리로 최근 상당히 많이 사용되어지고 있는 라이브러리이다. ~~아직 왜 좋은지는 모른다.~~
 

* Transformer의 구조를 Flax로 구현해보고 train까지 해보면서 Flax의 구조를 알아가보도록 하자.

* reference
  * Flax official transformer implementation: https://github.com/google/flax/tree/main/examples/wmt
