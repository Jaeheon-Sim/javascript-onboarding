# 문제 6 기능 요구 사항

1. 이메일과 닉네임을 보관
   - 각 리스트로 구분한다.
     - 인덱스가 같은 리스트의 값들은 같은 사람의 닉네임과 이메일이다.
2. 중복을 탐지
   - 각 닉네임을 모두 순회하며 닉네임의 글자(2글자 이상)이 겹치는지 확인한다.
     - 겹치는 값이 있다면 반환할 리스트에 입력한다.
       - 반환할 리스트에 이미 넣은 이메일이라면 넣지 않는다.
3. 중복되는 닉네임을 가진 사람의 이메일을 오름차순으로 정렬 후 반환
