# 🔥 페이지 작동

![done](README.assets/done.gif)


# 📋 프로젝트 진행
- 2인 1조 페어 프로젝트로 번갈아가며 `드라이버`, `네비게이터`역할을 수행
- `GitHub`를 활용하여 진행함

# 💡 주요 기능
## 네비게이션 바
- `Viewport`의 너비가 `992px 미만`일 경우 `네비게이션 바`의 아이템들이 `토글`되는 `햄버거` 안에 배치됨
- `Login`을 클릭하면 `Modal`이 작동함
  `Modal`에는 `fade` 애니메이션을 적용함

## `home.html`
- `Carousel`을 활용하여 이미지가 자동 전환되는 배너를 배치함
- `Viewport`의 너비에 따라 영화 목록 카드 배치가 변함

## `Community.html`
- `Viewport`의 너비가 `992px 이상`이면 왼쪽에 `aside`메뉴, 오른쪽에 게시판 테이블이 나타남
- `Viewport`의 너비가 `992px 미만`이면 게시판 테이블이 카드 형태로 변화함
  - 경계값인 992px을 기준으로 게시판과 카드의 `display`를 조작함 (`d-none` <-> `d-table`)

- 게시한 `hover`시 효과 추가