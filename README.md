# [Baekjoon](https://www.acmicpc.net) Algorithm

[![Solved.ac Profile](http://mazassumnida.wtf/api/v2/generate_badge?boj=dlsdudg15)](https://solved.ac/dlsdudg15)

## Python3

```python3
import sys

# 공백으로 구분된 2개 숫자 입력 받기
N, M = map(int, sys.stdin.readline().split())
  
# 여러 줄 입력 받기
n = int(sys.stdin.readline())
data = [sys.stdin.readline().strip() for i in range(n)]
  
# 문자열 입력 받기
data = sys.stdin.readline().rstrip()
```

## NodeJS

```javascript
const fs = require('fs');
const input = fs.readFileSync('/dev/stdin').toString();

// 한 줄 입력 받기
input.split(' ');

// 여러 줄 입력 받기
input.split('\n');
```
