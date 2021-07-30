#### https://codeforces.com/contest/1552/problem/D

---

#### 문제 설명: 배열 a 가 주어지고,임의의 b[i]-b[j]로 모든 a의 원소를 만들 수 있는 b가 존재하는지 찾는 문제이다. 

---

문제 해설: b배열의 원소들을 vertex, a배열의 원소들을 edge로 하는 그래프가 있다고 생각해 보자. Vertex가 n개, edge가 n개가 있다면 필연적으로 사이클이 존재할 것이다. 이 사이클이 존재할수 있는지 체크하는 것이 이 문제의 핵심이다.  사이클만 존재한다면 그 사이클에 조건에 맞게끔 붙여 나가면 되기 때문이다.![graph](https://user-images.githubusercontent.com/41511949/127618756-6ee1fc6e-7a95-43e3-9c88-66f95e355554.png)

