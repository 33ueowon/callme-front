
## 📁 폴더 구조
````
📦 src  
├── 📂 components                 # 재사용 가능한 UI 컴포넌트 모음
│   ├── 📂 main                   # 🏠 MainPage 구성 섹션들 
│   │   ├── SectionHello.jsx         # 닉네임 인사 + 검색 바 (가현)
│   │   ├── SectionPickYourIdol.jsx  # (가현)
│   │   ├── SectionTop5.jsx          # (가현)
│   │   └── SectionLetter.jsx        # (가현)
│   └── 📂 common                # 버튼, 카드 등 공용 UI 컴포넌트 (예: IdolCard, SearchBar 등)

├── 📂 pages                      # 화면 단위 페이지 컴포넌트
│   ├── 📂 Call
│   │   └── Incall.jsx               # 영상 통화 중 화면 (현주)
│   ├── HomePage.jsx                # 메인 홈 페이지
│   ├── IdolDetail.jsx              # 아이돌 상세 페이지
│   ├── Landing.jsx                 # 랜딩(인트로) 페이지 (여원)
│   ├── Nickname.jsx                # 닉네임 입력 페이지 (여원)
│   ├── Letter.jsx                  # 편지 페이지 (지은)
│   └── Search.jsx                  # 아이돌 검색 결과 페이지

├── 📂 router                     # 라우팅 설정
│   └── AppRoutes.jsx               # URL ↔ 페이지 매핑 정의

├── 📂 context                    # 전역 상태 관리 
│   ├── NicknameContext.jsx         # 닉네임 전역 관리 (가현)
│   └── StatsContext.jsx            # 통계/조회수 등 상태 관리 (가현)

├── 📂 utils                      # API 호출, 날짜 포맷 등 유틸 함수 모음
│   ├── email.js                   
│   ├── format.js         
│   ├── idoleApi.js         
│   ├── letterApi.js         
│   └── nicknameStorage.js         

└── App.jsx                       # 앱 루트 컴포넌트, 전체 구조/라우터 포함
``
