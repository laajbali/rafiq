# Rafiq | Prototype

An AI agent that catches member frustration early, hands staff a ready-to-act case, and protects member data throughout the journey.

🔗 **Live demo:** https://laajbali.github.io/rafiq-prototype/

## What it does

1. **Detects:** Reads the WhatsApp conversation and scores member frustration in real time.
2. **Acts:** Resolves the issue itself, or apologizes and compensates, depending on the frustration level.
3. **Hands off:** Escalates to a staff member with a full summary, so the member never has to repeat themselves.

## Frustration meter

| Score | Action |
|-------|--------|
| 0–40 | The agent resolves it |
| 40–70 | Apologizes and compensates |
| 70+ | Immediate handoff to staff |

## Prototype screens

- **Member experience:** A simulated WhatsApp conversation with the live frustration meter.
- **Staff screen:** The ready-made case, with an average handoff time of 42 seconds.
- **Admin dashboard:** Recurring frustration causes and the access log.

## Data protection

- Staff see only the minimum data needed for the case.
- Sensitive fields (national ID, date of birth) are hidden.
- Every access to a member file is logged.

## Note

This is a demo prototype only. All numbers and data are sample data.

## Run locally

Open `index.html` in any browser. No installation needed.
