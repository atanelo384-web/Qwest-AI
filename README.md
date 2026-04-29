<div align="center">
  
  <img src="https://img.icons8.com/fluency/96/api-settings.png" width="80">
  
  <h1>🔑 OpenRouter API Key</h1>
  
  <p>
    <strong>Qesty AI · API Configuration</strong>
  </p>
  
  <pre style="background: #0d1117; padding: 1rem; border-radius: 12px; color: #e6edf3;">
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
  </pre>
  
  <p>
    <img src="https://img.shields.io/badge/Model-Llama_3.3_70B-8A2BE2?style=flat-square">
    <img src="https://img.shields.io/badge/Status-Active-22c55e?style=flat-square">
    <img src="https://img.shields.io/badge/Type-Free-3b82f6?style=flat-square">
  </p>

</div>

---

## ✨ About this API Key

| Property | Value |
|----------|-------|
| **Service** | OpenRouter |
| **Model** | `meta-llama/llama-3.3-70b-instruct:free` |
| **Type** | 🆓 Free / Test |
| **Rate Limit** | ~20 requests/min |
| **Context** | 128K tokens |

---

## 📦 Quick Integration

### JavaScript / TypeScript

```javascript
const response = await fetch("https://openrouter.ai/api/v1/chat/completions", {
  method: "POST",
  headers: {
    "Content-Type": "application/json",
    "Authorization": "Bearer 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"
  },
  body: JSON.stringify({
    model: "meta-llama/llama-3.3-70b-instruct:free",
    messages: [
      { role: "user", content: "Hello, Qesty!" }
    ]
  })
});
