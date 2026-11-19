# STRUCTURE · salon-de-eye-sample (v0.1 · 사진 중심 크림 미니멀 · 모서리 2px · 배포 예정 salon-de-eye-sample.lgt3232.workers.dev)

```
salon-de-eye-sample/
├─ index.html                     단일 파일 (CSS · JS 인라인)
├─ wrangler.toml                  name = salon-de-eye-sample
├─ .assetsignore                  img/ · _old/ · 문서 · index_*.html · _deploy 배포 제외
├─ sd-jost.woff2                  영문 워드마크 · 제목 (Jost 300–500, 영문만)
├─ sd-pretendard.woff2            본문 · 한글 (Pretendard 300–700, 페이지 글자 전부)
├─ sd-mark.svg                    라인아트 로고 마크(헤더 · 히어로 · 푸터)
├─ sd-hero.webp                   히어로 눈매
├─ sd-g1 ~ sd-g9.webp             속눈썹 갤러리 9장(정사각, 모바일 첫 장 넓은 칸)
├─ favicon.png · og-sd.jpg
├─ img/                           다올 제공 원본 119장 + _원문.md (배포 제외 · 레포에 올리지 말 것)
└─ CHANGELOG.md / STRUCTURE.md
```

## 섹션 순서
헤더(+ 900px 미만 `.snav`) → 히어로(크림) → `#about`(흰) → `#lash` 갤러리 9(크림) → `#price` 3카드(흰) → `#booking`(크림) → `#visit`(흰 · 구글 지도) → 푸터(흰) + 모바일 `.quick`.

## 버튼 · 링크
- 네이버 예약 `https://m.place.naver.com/place/1115108261/ticket`(메인, 인스타 프로필 링크): 헤더 · 히어로 · 예약 안내 · 오시는 길 · 하단 바
- 전화 `tel:050713477860`: 히어로 · 오시는 길 · 푸터 · 하단 바
- 인스타 `https://www.instagram.com/salon_de_eye_official/`: 히어로 · 예약 안내 · 푸터 · 하단 바
- 네이버 길찾기 `map.naver.com/p/entry/place/1115108261` · 블로그 `blog.naver.com/minju7860` · 네이버 플레이스(푸터)

## 폰트 재생성
문구 바꾸면 빠진 글자 검사(LESSONS §26). 한글은 Pretendard만, Jost는 영문만.
