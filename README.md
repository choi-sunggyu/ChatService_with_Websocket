# ChatService_with_Websocket

## Project Structure
```text
/
├── app.py                 # FastAPI 메인 애플리케이션
├── run_server.py          # 서버 실행 및 ngrok 연결 스크립트
└── www/                   # 정적 파일 및 React 프론트엔드
    ├── index.html         # 메인 HTML 파일
    ├── static/            # 정적 파일 (CSS, JS 등)
    │   ├── css/
    │   │   └── style.css
    │   └── js/
    │       ├── main.js       # 메인 JavaScript 파일
    │       ├── ChatRoom.js   # 채팅방 컴포넌트
    │       └── RoomList.js   # 채팅방 목록 컴포넌트
    └── components/        # React 컴포넌트
```
