# 휴딧심리연구소 심리아카데미 팜플렛

## 📋 파일 목록

이 저장소는 다음 4개의 파일로 구성되어 있습니다:

1. **index.html** - 메인 웹페이지 (이 파일명 필수!)
2. **schedule-data.json** - 교육 일정 데이터
3. **contact-info.json** - 연락처 정보
4. **README.md** - 이 문서

---

## 🌐 GitHub Pages 배포 방법

### 1단계: 저장소 생성
1. GitHub.com에 로그인
2. 우측 상단 `+` 버튼 → `New repository` 클릭
3. Repository 이름: `psychology-academy`
4. **Public** 선택
5. `Create repository` 클릭

### 2단계: 파일 업로드
1. `Add file` → `Upload files` 클릭
2. 위 4개 파일을 **정확한 파일명**으로 드래그 앤 드롭
   - ✅ `index.html` (psychology_academy_pamphlet.html ❌)
   - ✅ `schedule-data.json` (schedule_data_json.json ❌)
   - ✅ `contact-info.json` (contact_info_json.json ❌)
   - ✅ `README.md`
3. `Commit changes` 클릭

### 3단계: GitHub Pages 활성화
1. `Settings` 탭 클릭
2. 왼쪽 메뉴 `Pages` 클릭
3. **Source** 섹션:
   - Branch: `main` 선택
   - Folder: `/ (root)` 선택
4. `Save` 클릭

### 4단계: 웹사이트 접속
5-10분 후:
```
https://[사용자명].github.io/psychology-academy/
```

---

## ⚠️ 중요: 파일명 규칙

GitHub Pages가 정상 작동하려면 **정확한 파일명**이 필요합니다:

### ✅ 올바른 파일명
- `index.html` → GitHub Pages 메인 페이지
- `schedule-data.json` → 하이픈(-) 사용
- `contact-info.json` → 하이픈(-) 사용

### ❌ 잘못된 파일명 (작동 안 함)
- `psychology_academy_pamphlet.html`
- `schedule_data_json.json` → 언더스코어(_) 사용
- `contact_info_json.json` → 언더스코어(_) 사용
- `schedule-data-json.json` → -json 중복

---

## ✏️ 연락처 정보 수정 방법

### GitHub에서 직접 수정

1. `contact-info.json` 파일 클릭
2. 연필 아이콘(✏️) 클릭
3. 정보 수정:
```json
{
  "organization": "휴딧심리연구소",
  "programTitle": "심리아카데미 1기 모집",
  "phone": "070-8838-3877",
  "businessPhone": "369-86-03038",
  "address": "서울시 동작구 흑석동 341 아크로리버힐 101동 3거 34호",
  "email": "hudit@hudit.co.kr",
  "website": "www.hudit.co.kr"
}
```
4. `Commit changes` 클릭
5. **1-2분 후 자동 반영**

---

## ✏️ 강사명 수정 방법

### GitHub에서 직접 수정

1. `schedule-data.json` 파일 클릭
2. 연필 아이콘(✏️) 클릭
3. 강사명 수정:
```json
{
  "title": "[상담실제1] 상담의 기본 기법",
  "instructor": "새로운 강사명"
}
```
4. `Commit changes` 클릭
5. **1-2분 후 자동 반영**

---

## 📱 모바일에서 수정

**GitHub 모바일 앱** 설치 후:
1. 저장소 접속
2. 파일 선택
3. ⋯ → `Edit file`
4. 수정 후 `Commit`

---

## 🔧 문제 해결

### Q: 사이트가 비어있어요
**A:** 파일명을 확인하세요!
- `index.html`이 있나요? (다른 이름은 안 됩니다)
- JSON 파일이 하이픈(`-`)을 사용하나요?

### Q: 데이터가 안 보여요
**A:** JSON 파일명을 확인하세요!
- ✅ `schedule-data.json`
- ✅ `contact-info.json`
- ❌ `schedule_data_json.json`
- ❌ `contact-info-json.json`

### Q: 수정이 반영되지 않아요
**A:** 브라우저 캐시 삭제:
- Windows: `Ctrl + Shift + R`
- Mac: `Cmd + Shift + R`
- 또는 시크릿 모드로 접속

### Q: JSON 형식 오류
**A:** [JSONLint](https://jsonlint.com/)에서 검증하세요.

---

## 📄 파일 구조

```
psychology-academy/
├── index.html              # 메인 페이지 (필수!)
├── schedule-data.json      # 일정 데이터
├── contact-info.json       # 연락처 정보
└── README.md               # 이 문서
```

---

## 📞 현재 연락처

- **기관**: 휴딧심리연구소
- **전화**: 070-8838-3877
- **사업자**: 369-86-03038
- **주소**: 서울시 동작구 흑석동 341 아크로리버힐 101동 3거 34호
- **이메일**: hudit@hudit.co.kr
- **웹**: www.hudit.co.kr

---

## 💡 핵심 요약

1. **파일명이 가장 중요합니다!**
   - `index.html` (다른 이름 불가)
   - 하이픈(`-`) 사용, 언더스코어(`_`) 사용 금지

2. **JSON 파일만 수정하면 됩니다**
   - 강사명 변경: `schedule-data.json`
   - 연락처 변경: `contact-info.json`

3. **수정 후 1-2분이면 반영됩니다**

---

**Made with ❤️ for 휴딧심리연구소**