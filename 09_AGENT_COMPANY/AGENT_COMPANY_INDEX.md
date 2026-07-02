# Jay Agent Company Index

Jay Agent Company는 Jay의 개인 AI 회사 운영체계다.

핵심 구조:

- Telegram Command Center
- Orchestrator
- Context Optimizer
- Workflow Harness
- Agent Teams
- Peer Review
- Red Team
- Judge
- Final Memo
- Jay Approval
- Memory Update

기본 팀:

- Finance
- Research
- Compliance 1
- Compliance 2 Red Team
- Product
- Engineering
- Marketing
- Security / Debug
- Judge

핵심 원칙:

- 스킬을 많이 만들지 않는다.
- 작은 핵심 워크플로를 반복 개선한다.
- 모든 작업은 run 단위로 저장한다.
- 모든 에이전트는 자기비판과 Do & Don't 후보를 남긴다.
- Red Team과 Judge를 통해 산출물을 검증한다.
- Jay 승인 없이 외부 발송, 법률 결론화, 코드 merge, 배포, 금융성 액션, MCP 쓰기 도구 실행을 하지 않는다.
- 원문 전체를 무조건 LLM에 던지지 않고 Context Pack을 만든다.

중요 파일:

- ~/workspace/jay-agent-os/docs/00_AGENT_COMPANY_STRATEGY.md
- ~/workspace/jay-agent-os/policies/01_OPERATING_POLICY.md
- ~/workspace/jay-agent-os/policies/02_FEEDBACK_EVOLUTION_POLICY.md
- ~/workspace/jay-agent-os/policies/03_TOKEN_CONTEXT_POLICY.md
- ~/workspace/jay-agent-os/memory/DO_AND_DONTS.md
- ~/workspace/jay-agent-os/agents/teams.yaml
- ~/workspace/jay-agent-os/workflows/agent_company_default.yaml
