# LLM-Wiki Labs

Joonan Lab의 AI Native 연구 시스템 인터랙티브 모음.

**Live**: https://joonan30.github.io/llm-wiki-labs/

## Labs

| # | Title | Date | Description |
|---|---|---|---|
| 01 | [Evolution](evolution/) | 2026-06-28 | 82일 동안 LLM-Wiki가 바뀐 기록 + 처음 한 시간 가이드 + 실제 워크플로우 5개 |

## What is this?

연구실의 AI 위키 시스템(LLM-Wiki)을 어떻게 만들고 운영하는지를 인터랙티브 페이지로 보여주는 모음. 학부생부터 PI까지 4역할 렌즈로 같은 콘텐츠를 다르게 읽을 수 있도록 설계했습니다.

각 lab은 단일 HTML 파일입니다. 외부 의존성은 Google Fonts 한 줄뿐이라 어떤 정적 호스팅에서도 그대로 작동합니다.

## Design

- **Color**: OKLCH 5색 팔레트 (테라코타 / 모스 / 사프란 / 멀버리 / 버디그리스)
- **Typography**: Newsreader (display), IBM Plex Sans (body), JetBrains Mono (code)
- **Inspired by**: [garden-skills/web-design-engineer](https://github.com/ConardLi/garden-skills) 디자인 철학 (AI 클리셰 회피, 의도된 타이포 대비, 미세 인터랙션)

## Running locally

```bash
git clone https://github.com/joonan30/llm-wiki-labs.git
cd llm-wiki-labs
python3 -m http.server 8000
# open http://localhost:8000/
```

## License

MIT. fork·remix 자유.

## Author

Joon-Yong An (안준용) · Korea University
