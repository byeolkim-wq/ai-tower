# AI Tower

AI 코딩 어시스턴트 세션 모니터링 대시보드

Claude Code, Codex, OpenCode 세션을 실시간으로 모니터링합니다.

## 설치

```bash
# 다운로드
curl -o ~/bin/ai-tower https://raw.githubusercontent.com/byeolkim-wq/ai-tower/main/ai-tower

# 실행 권한 부여
chmod +x ~/bin/ai-tower

# PATH에 ~/bin 추가 (없다면)
echo 'export PATH="$HOME/bin:$PATH"' >> ~/.zshrc
source ~/.zshrc
```

## 사용법

```bash
ai-tower
```

- `q` 키로 종료
- 1초마다 자동 업데이트

## 기능

- Claude Code, Codex, OpenCode 세션 감지
- 프로젝트명, Git 브랜치 표시
- 상태 표시: 진행중 🔵, 답변 대기 🟡, 작업 완료 🟢
- 최근 대화 내용 표시 (Claude, Codex)

## 요구사항

- macOS
- Python 3
- terminal-notifier (알림용, 선택사항)

```bash
brew install terminal-notifier
```

## 스크린샷

<img width="600" height="1720" alt="image" src="https://github.com/user-attachments/assets/a15967b5-87b5-49cf-869e-a0a01c6a549d" />

