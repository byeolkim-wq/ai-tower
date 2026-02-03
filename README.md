# AI Tower

AI 코딩 어시스턴트 관제탑 - 터미널에서 실행 중인 AI 세션을 한눈에 모니터링

## 지원 도구

| AI | 상태 감지 | 대화 표시 | 브랜치 |
|----|----------|----------|--------|
| Claude Code | O | O | O |
| Codex | O | O | O |
| OpenCode | O | O (최근 세션) | O |

## 설치

```bash
curl -o ~/bin/ai-tower https://raw.githubusercontent.com/byeolkim-wq/ai-tower/main/ai-tower && chmod +x ~/bin/ai-tower
```

> `~/bin`이 PATH에 없다면:
> ```bash
> echo 'export PATH="$HOME/bin:$PATH"' >> ~/.zshrc && source ~/.zshrc
> ```

## 사용법

```bash
ai-tower        # 실시간 대시보드
ai-tower -1     # 한번만 출력
```

`q` 키로 종료

## 상태 표시

| 상태 | 의미 |
|------|------|
| 진행중 🔵 | AI가 작업 중 |
| 답변 대기 🟡 | 사용자 입력 대기 |
| 작업 완료 🟢 | AI 응답 완료 |

## 요구사항

- macOS
- Python 3

## 스크린샷

<img width="600" height="1720" alt="image" src="https://github.com/user-attachments/assets/a15967b5-87b5-49cf-869e-a0a01c6a549d" />
