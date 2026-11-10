# Contributing to Awesome Unity 2D

Awesome Unity 2D에 관심을 가져 주셔서 감사합니다!
이 문서는 새로운 자료를 추가하거나 기존 내용을 고치는 방법을 안내합니다.

이 저장소는 코드가 없는 문서형 프로젝트라서 별도 설치나 빌드가 필요 없습니다.

## 🚀 시작하기

### 1. Fork & Clone

GitHub에서 이 저장소 오른쪽 위의 **Fork** 버튼을 눌러 내 계정으로 복사한 뒤, 내 컴퓨터로 가져옵니다.

```bash
git clone https://github.com/lee12sen/awesome-unity-2d.git
cd awesome-unity-2d
```

### 2. 브랜치 생성

작업 내용을 알 수 있는 이름으로 브랜치를 만듭니다.

```bash
git checkout -b add/piskel
```

| 작업 | 브랜치 이름 | 예시 |
| --- | --- | --- |
| 자료 추가 | `add/자료이름` | `add/piskel` |
| 내용 수정 | `fix/수정내용` | `fix/kenney-link` |
| 자료 삭제 | `remove/자료이름` | `remove/old-site` |

### 3. 변경사항 커밋 (Conventional Commits)

`README.md`를 수정한 뒤, 추가한 링크가 잘 열리는지와 Markdown 미리보기에서 형식이 깨지지 않는지 확인하고 커밋합니다.

```bash
git add README.md
git commit -m "docs: add Piskel to tools section"
```

커밋 메시지는 [Conventional Commits](https://www.conventionalcommits.org/) 형식을 따릅니다.

| 타입 | 사용하는 경우 | 예시 |
| --- | --- | --- |
| `docs` | 자료 추가, 설명 수정 등 문서 변경 | `docs: add Piskel to tools section` |
| `fix` | 깨진 링크, 잘못된 정보 수정 | `fix: update broken Kenney link` |
| `chore` | 목차 정리 등 기타 작업 | `chore: sort tools alphabetically` |

### 4. Push & Pull Request

내 Fork 저장소로 올린 뒤, GitHub에서 원래 저장소로 **Pull Request**를 보냅니다.

```bash
git push origin add/piskel
```

- PR 제목은 커밋 메시지와 같은 형식으로 써 주세요.
- PR 1개에는 **자료 1개**만 추가해 주세요. 리뷰와 관리가 쉬워집니다.

> 💡 명령어가 익숙하지 않다면 GitHub 웹에서 `README.md`의 연필 아이콘을 눌러 수정해도 됩니다. Fork와 브랜치 생성이 자동으로 처리됩니다.

## 📋 자료 추가 기준

1. **유니티 2D 게임 개발과 관련**이 있어야 합니다.
2. **무료로 사용 가능**해야 합니다. 유료라면 무료 버전이나 무료 사용 방법이 있어야 하며, 설명에 이를 밝혀 주세요.
3. **직접 써 보았거나 내용을 확인한** 자료여야 합니다.
4. 이미 목록에 있는 자료와 **중복되지 않아야** 합니다. 추가 전에 `Ctrl + F`로 검색해 주세요.
5. 광고나 홍보만을 위한 링크는 받지 않습니다.

## ✍️ 작성 형식 (Style Guide)

각 항목은 아래 형식을 지켜 주세요.

```markdown
- [자료 이름](링크) - 한 문장 설명. 마침표로 끝내기.
```

예시:

```markdown
- [Piskel](https://www.piskelapp.com/) - 브라우저에서 바로 쓰는 무료 픽셀아트·스프라이트 애니메이션 편집기.
```

- 알맞은 분류 안에 넣어 주세요.
- 설명은 "무엇인지"와 "어디에 쓰는지"가 드러나게 짧게 써 주세요.
- 링크는 가능한 한 공식 사이트 주소를 사용해 주세요.

## 🐛 문제 신고

깨진 링크나 잘못된 정보를 발견했지만 직접 고치기 어렵다면, **Issues** 탭에서 새 이슈를 열어 알려 주세요.

## 🤝 행동 강령

이 프로젝트에 참여하는 모든 분은 [행동 강령](CODE_OF_CONDUCT.md)을 지켜 주셔야 합니다.
