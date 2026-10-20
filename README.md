# Ulysse Lebigre

Software engineer building AI agents: structured extraction, risk-based routing,
human-in-the-loop, and guardrails tested adversarially, not just happy-path demos.

## Agents

**[Alder AP Agent](https://github.com/UlysseLeb/alder-ap-agent)** — LangGraph agent
that validates supplier invoices, scores risk, and pauses for human approval on
risky cases, resuming execution from the exact point it stopped.

**[NovaSupply Ops Agent](https://github.com/UlysseLeb/novasupply-agent)** — Agent
that triages support emails, choosing its own tools (order lookup, policy search,
escalation) instead of following a fixed if/else route. Deployed on AWS Lambda,
with a Bedrock Guardrail tested through adversarial prompt injection and an
assertion-based eval suite (5/5).

**[NovaSupply Inbox AI](https://github.com/UlysseLeb/novasupply-inbox-ai)** —
Production email triage and reply-drafting workflow, human-in-the-loop, live at
nova-supply.luluplug.com.

## Stack

Python, LangGraph, Strands Agents, AWS Bedrock (Claude, Titan, Knowledge Base,
Guardrails), AWS Lambda, CDK, DynamoDB.
