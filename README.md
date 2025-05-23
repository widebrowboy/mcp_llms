
# mcp_llms

# MCP LLMs

이 저장소는 MCP(Multi-Context Processing) LLMs 관련 프로젝트를 위한 공간입니다.

## 프로젝트 설명

이 프로젝트는 다양한 컨텍스트를 처리할 수 있는 LLM(Large Language Model) 관련 연구와 개발을 위한 저장소입니다.

## 시작하기

프로젝트를 시작하기 위한 기본 설정과 사용 방법은 추후 업데이트될 예정입니다.

로컬에서 작업한 뒤, 다음 명령어를 사용하시면 GitHub와 연동이 계속 유지됩니다.

```bash
git add .
git commit -m "커밋 메시지"
git push
```

궁금한 점이나, 다른 파일도 올리고 싶으시면 언제든 말씀해 주세요! 정상적으로 푸시가 되었는지 GitHub 저장소에서 확인해보세요: [https://github.com/widebrowboy/mcp_llms](https://github.com/widebrowboy/mcp_llm


## 커서 룰 정보
네, 현재 설정을 Cursor 규칙으로 저장하도록 하겠습니다. 
먼저 `.cursor` 디렉토리를 생성하고 설정 파일을 만들겠습니다:


```bash
mkdir -p .cursor
```
이제 Cursor 설정 파일을 생성하겠습니다:



이제 `.gitignore` 파일도 생성하여 가상환경 디렉토리와 Cursor 설정 파일을 Git에서 제외하도록 하겠습니다:



이제 변경사항을 Git에 커밋하겠습니다:


```bash
git add .gitignore && git commit -m "Add .gitignore and Cursor settings"
```

```bash
git push origin main
```
설정이 완료되었습니다! 이제:

1. Python 3.11 가상환경 설정
2. uv, uvx 설정
3. Git 설정
4. Cursor IDE 설정

이 모두가 저장되었습니다.

주요 설정 내용:
- Python 3.11 가상환경 경로: `.venv/`
- Git 원격 저장소: `https://github.com/widebrowboy/mcp_llms.git`
- 기본 브랜치: `main`
- Cursor 설정: `.cursor/settings.json`

이제 새로운 환경에서 프로젝트를 클론할 때는:
1. 저장소 클론
2. Python 3.11 설치
3. `python3.11 -m venv .venv` 실행
4. `source .venv/bin/activate` 실행

이 순서대로 진행하시면 됩니다.

추가로 필요한 설정이나 궁금한 점이 있으시다면 말씀해 주세요!
