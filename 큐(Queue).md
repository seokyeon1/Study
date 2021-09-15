# 큐(Queue)

**구조**: 큐는 뒤에서는 삽입만 하고 앞에서는 삭제만 할 수 있는 구조. 가장 먼저 삽입한 원소는 맨 앞에 있다가 가장 먼저 삭제. 선입 선출 구조(First in First Out).

**변수**: front, rear

**삽입 연산**

|   연산자   | 삽입 위치 |
| :-----: | :---: |
| enQueue | rear  |

**삭제 연산**

|   연산자   | 삽입 위치 |
| :-----: | :---: |
| deQueue | front |

**알고리즘**

**공백 큐 생성**

- 크기가 n인 1차원 배열 생성
- front, rear을 -1로 초기화



**검사 알고리즘**

- 공백 : front = rear
- 포화 : rear = n-1 (n : 배열의 크기, n-1 : 배열의 마지막 인덱스)



**삽입(enQueue) 알고리즘**

```
void enQueue(int a) {
  if (isFull == 1) return;
  queue[rear] = a;
  rear = (rear + 1) % SZ;
  arr[rear] = data;
  return;
}
```

- 포화 상태인지 검사
- rear++
- Q[rear] = item



**삭제(deQueue) 알고리즘**

```
int deQueue() {
  if (isEmpty == 1) return INF;
  {
    int temp = Queue[front];
    front = (front + 1) % SZ;
    return temp;
  }
}
```

- 공백 체크
- front++
- Q[front] 반환



