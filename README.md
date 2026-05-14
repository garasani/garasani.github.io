# homepage-01

Astro 기반 개인 홈페이지 프로젝트입니다.

최종 배포 목표는 GitHub Pages의 `github.io` 주소입니다. 첫 버전은 Home 페이지만 포함하고, 이후 About / Projects / Posts 페이지로 확장할 수 있게 시작합니다.

## Project Structure

```text
/
├── public/
├── src/
│   ├── layouts/
│   │   └── BaseLayout.astro
│   ├── pages/
│   │   └── index.astro
│   └── styles/
│       └── global.css
├── astro.config.mjs
├── package.json
└── tsconfig.json
```

## Commands

```sh
npm run dev
npm run build
npm run preview
```

## Notes

- 새 라이브러리는 승인 후 추가합니다.
- 배포 설정은 GitHub 저장소 이름과 `github.io` 주소가 정해진 뒤 확정합니다.
