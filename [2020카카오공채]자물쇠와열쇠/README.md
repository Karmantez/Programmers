# [2020카카오공채] 자물쇠와 열쇠 (Level 3)

- URL :  https://programmers.co.kr/learn/courses/30/lessons/60059
- 출처 :  Programmers (2020 KAKAO BLIND RECRUITMENT) 



## 개요

> 목표

열쇠를 나타내는 2차원 배열 key와 자물쇠를 나타내는 2차원 배열 lock이 매개변수로 주어질 때, 열쇠로 자물쇠를 열수 있으면 true를, 열 수 없으면 false를 return 하도록 solution 함수를 완성.



> 제약조건

- key는 M x M(3 ≤ M ≤ 20, M은 자연수)크기 2차원 배열입니다.
- lock은 N x N(3 ≤ N ≤ 20, N은 자연수)크기 2차원 배열입니다.
- M은 항상 N 이하입니다.
- key와 lock의 원소는 0 또는 1로 이루어져 있습니다.
  - 0은 홈 부분, 1은 돌기 부분을 나타냅니다.






## 계획

1. 우선 N, M이 크지 않고 key를 회전하고 움직여서 대조해봐야 하기 때문에 완전탐색을 해야한다고 생각했습니다.
2. 회전하는  method를 만들기 전 회전하는 면을 정수형 배열에 담아 연결리스트에 넣어 회전을 용이하게 하도록 구현했습니다.



## 결과

**푸는데 걸린시간 : ** ***약 2시간***



## 회고

1. 문제를 이해하는 것은 어렵지 않았지만 회전을 체계적이고 효율적으로 만들기 위해 많은 노력을 쏟은 탓에 시간이 좀 걸린 것 같습니다.


