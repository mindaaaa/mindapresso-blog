# Mindapresso Blog ☕️

Markdown 기반으로 직접 구현한 감성 기술 블로그입니다.  
Next.js 13 App Router, TypeScript, Tailwind CSS를 활용하여 개발중입니다.

## 주요 기술 스택

- [Next.js 13](https://nextjs.org/) `App Router`
- TypeScript
- Tailwind CSS
- gray-matter`Markdown 메타데이터 파싱`
- remark + rehype `Markdown 렌더링`

## 📁 디렉토리 구조

```
src/
├── app/
│ ├── page.tsx # 글 목록
│ └── posts/[slug]/ # 글 상세
├── components/ # 재사용 UI 컴포넌트
├── lib/ # 마크다운 로딩 & 파싱 로직
├── posts/ # .md 글 원본 저장소
├── styles
```

## 현재 상태

- ✅ 프로젝트 초기 세팅 완료
- 마크다운 글 목록 기능 구현 중

## 🛠 향후 계획

- 글 상세 페이지 구현
- 카테고리 필터 / 검색 기능
- 다크모드 지원
- 댓글 / 좋아요 기능 `Utterances, Firebase`
- 커스텀 도메인 배포

---

> 개발자의 생각을 에스프레소처럼 진하게 담아내는 블로그, Mindapresso ☕
