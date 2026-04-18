# OpenNode — Decentralized GPU Compute Marketplace

[![Website](https://img.shields.io/badge/Website-onc.mom-blue?style=for-the-badge)](https://onc.mom)
[![API](https://img.shields.io/badge/API-OpenAI%20Compatible-green?style=for-the-badge)](https://onc.mom/api-docs)

> **Run any LLM via OpenAI-compatible API. 80% cheaper than OpenAI. No vendor lock-in.**

🚀 [Get Started](https://onc.mom) · 📖 [API Docs](https://onc.mom/api-docs) · ⛏️ [Earn by Mining](https://onc.mom/miner)

---

## What is OpenNode?

OpenNode is a **decentralized GPU compute marketplace** that connects AI developers with distributed GPU node operators worldwide.

- **For Developers**: Drop-in replacement for OpenAI API. Change one URL, keep all your code.
- **For GPU Owners**: Earn ONC tokens by contributing idle GPU compute power (95% revenue share).
- **For Everyone**: Democratize AI inference — no centralized gatekeepers, no vendor lock-in.

## ⚡ Quick Start (30 seconds)

```python
from openai import OpenAI

client = OpenAI(
    api_key="your-opennode-api-key",
    base_url="https://onc.mom/v1"  # Only change this line!
)

response = client.chat.completions.create(
    model="gpt-4o",
    messages=[{"role": "user", "content": "Hello, OpenNode!"}]
)
print(response.choices[0].message.content)
```

**That's it.** One line change from OpenAI to OpenNode. All existing code works instantly.

## 💰 Pricing (80% cheaper than OpenAI)

| Model | Input (per 1M tokens) | Output (per 1M tokens) | Savings vs OpenAI |
|-------|----------------------|------------------------|-------------------|
| `gpt-4o` | $1.00 | $3.00 | **-80%** |
| `gpt-4o-mini` | $0.10 | $0.30 | **-80%** |
| `claude-3-5-haiku` | $0.20 | $0.60 | **-75%** |
| `gemini-2.5-flash` | $0.15 | $0.45 | **-70%** |
| `gemini-2.0-flash` | $0.10 | $0.30 | **-75%** |

## 🔌 Integration Examples

### LangChain
```python
from langchain_openai import ChatOpenAI

llm = ChatOpenAI(
    model="gpt-4o",
    openai_api_key="your-key",
    openai_api_base="https://onc.mom/v1"
)
```

### LlamaIndex
```python
from llama_index.llms.openai import OpenAI

llm = OpenAI(model="gpt-4o", api_key="your-key", api_base="https://onc.mom/v1")
```

### cURL
```bash
curl https://onc.mom/v1/chat/completions \
  -H "Authorization: Bearer your-key" \
  -H "Content-Type: application/json" \
  -d '{"model": "gpt-4o", "messages": [{"role": "user", "content": "Hello!"}]}'
```

## ⛏️ Earn by Mining

Have idle GPUs? Become an OpenNode miner:

1. Register at [onc.mom/miner](https://onc.mom/miner)
2. Connect your GPU node
3. Earn **95% of inference revenue** in ONC tokens automatically

## 🏆 Pioneer Program

Early adopters get permanent benefits:
- Extra ONC token rewards
- Reduced platform fees locked in forever
- Pioneer badge on profile

[Join Pioneer Program →](https://onc.mom/pioneer)

## 👥 Referral Program

- **10 ONC** per successful referral
- **5% permanent commission** on all their API usage

[Get Your Referral Link →](https://onc.mom/referral)

---

**[🚀 Start using OpenNode at onc.mom](https://onc.mom)**
