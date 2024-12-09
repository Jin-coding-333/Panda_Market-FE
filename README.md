## 📋 스프린트 미션 요구사항

---

## **기본 요구사항**

### **공통**
- [x] Github에 스프린트 미션 PR을 생성합니다.
- [x] Next.js를 사용해 프로젝트를 진행합니다.

---

### **자유 게시판 페이지**
- [ ] 게시글 목록에서 드롭다운을 사용하여 **"최신 순"**으로 정렬할 수 있도록 구현합니다.
- [x] 게시글 목록 데이터를 **본인이 만든 GET 메서드 API**를 활용하여 가져옵니다.
- [ ] 게시글 제목에 검색어가 포함되면 해당 게시글을 검색할 수 있도록 구현합니다.
- [x] 이미지는 디폴트 이미지를 사용하여 프론트엔드에서 처리합니다.
- [x] 게시글 닉네임 및 좋아요 개수는 임의값으로 프론트엔드에서 처리합니다.
- [x] **베스트 게시글**은 최신순 3개 게시글을 요청하여 데이터를 가져오고 구현합니다.
- [x] 특정 게시글을 클릭하면 해당 게시물의 **상세 페이지**로 이동합니다.

---

### **게시글 등록 & 수정 페이지**
- [x] 각 input 필드에 적절한 placeholder 값을 추가합니다.
- [x] 모든 input 필드에 값이 입력되면 **'등록' 버튼**이 활성화됩니다.
- [x] 게시글 등록 시, **POST 메서드 API**를 활용하여 데이터를 저장합니다.
- [x] **'등록' 버튼** 클릭 시, 해당 게시물 상세 페이지로 이동합니다.
- [ ] 게시글 수정 페이지는 등록 페이지와 동일한 UI로 구성합니다.
- [ ] 게시글 수정 시, **PATCH 메서드 API**를 활용하여 데이터를 업데이트합니다.

---

### **게시글 상세 페이지**
- [x] 게시글 상세 데이터를 **GET 메서드 API**로 가져옵니다.
- [x] 게시글 삭제 시, **DELETE 메서드 API**를 사용합니다.
- [x] 댓글 입력 시, 값이 입력되면 **'등록' 버튼**이 활성화됩니다.
- [x] 댓글 등록 시, **POST 메서드 API**를 사용하여 저장합니다.
- [ ] 댓글 수정 시, **PATCH 메서드 API**를 활용하여 데이터를 업데이트합니다.
- [x] 댓글 삭제 시, **DELETE 메서드 API**를 사용합니다.

---

## **심화 요구사항**

### **공통**
- [ ] 디자인 시안에 따라 **반응형 디자인**을 구현합니다.
- [ ] (선택 사항) 기존 React 코드를 **Next.js로 마이그레이션**합니다.
  - 주의: 마이그레이션에는 시간이 소요될 수 있으므로 선택적으로 진행합니다.

---

### 멘토에게
- 셀프 코드리뷰 이어나가겠습니다.
---
## 스크린샷

404페이지
![screencapture-localhost-3000-Items-2024-12-08-03_50_33](https://github.com/user-attachments/assets/6fa38db5-4ed9-428f-939c-d8974bedc661)

게시글 목록 페이지
![screencapture-localhost-3000-CommunityFeed-2024-12-09-03_23_11](https://github.com/user-attachments/assets/f8f9bd8c-c769-47f5-971e-d0bee78fc08a)

게시글 상세 페이지(댓글0)
![screencapture-localhost-3000-ArticleDetail-0cfe5986-2435-42fa-8eeb-622173523b86-2024-12-09-03_23_33](https://github.com/user-attachments/assets/cecba9c1-cf4b-41cf-ab9f-2ef3dd7851bf)

게시글 상세 페이지(댓글X)
![screencapture-localhost-3000-ArticleDetail-de93d517-0be3-4d82-9991-2976d0d3389a-2024-12-09-03_56_53](https://github.com/user-attachments/assets/a64a3ccb-c17c-4c48-95b2-28a9b7d86ea0)

홈 페이지
![screencapture-localhost-3000-2024-12-08-03_51_21](https://github.com/user-attachments/assets/61c98970-0876-4e23-be91-51da36dd47d7)
![486px_이하](https://github.com/user-attachments/assets/d3c9fa96-fc1e-4a12-895b-a59edc18c54b)
![750px_이하](https://github.com/user-attachments/assets/6a893d8c-81ca-44fe-a940-dbf8387a0b9d)


