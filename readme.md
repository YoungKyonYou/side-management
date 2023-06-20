1. 채팅방에 총인원 표시(현재 기준, 나간 사람 포함하지 않고)
2. 채팅방 나간 사람이랑 새로 들어온 사람 구분, 카운팅 plus, minus 처리
3. 닉네임 중복 확인
4. 특정 채팅방의 내용을 찾을 수 있어야 함
5. 특정 채팅방의 특정 멤버의 내용을 볼 수 있어야 함
6. 특정 채팅방에서 채팅 검색 기능 제공
7. 채팅 내역은 최대 일주일까지만 보관 그 이후는 과거 테이블에 저장
8. 특정 채팅방에 참여하고 있는 멤버 아이디 리스트 반환할 수 있어야 함
9. 채팅방의 모든 메세지 내용(content, 발송자, 시간) 반환해야 함

ChatRoom
- teamId (PK)
- memberCnt
- isActive (방이 활성화 되어 있는지 여부)
Message
-messageId(PK)
-teamId (FK)
-content
-isJoin  (방에 있는지 여부)
-createdTime
-modifiedTime
-memberId (메시지 발송자)

https://velog.io/@joypeb/Springboot3-Websocket-%EC%B1%84%ED%8C%85-Stomp-SockJS-Spring-Security
