1. 데이터는 MNIST를 사용합니다.
2. 입력 영상에 노이즈를 추가

3.세 개의 모델을 만들어 비교함.
  3-1. 오토인코더의 hidden layer에서 128개의 노드 수를 갖는 모델을 생성하세요.

  3-2. 오토인코더의 encoder와 decoder에 각각 1개의 layer를 추가하여 encoder layer, 중앙 hidden layer, decoder layer에서 각각 256개, 128개, 256개의 노드 수를 갖는 모델을 생성하세요.

 3-3. 합성곱 오토인코더는 수업 시간에 사용한 모델을 사용합니다.

4. 비용함수는 mean squared error를 적용하고, 최적화 방법은 AdamOptimizer, 총 epoch 수는 10번으로 고정
