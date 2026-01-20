# my-litellm
```curl
curl http://localhost:4000/v1/chat/completions \
  -H "Content-Type: application/json" \
  -H "Authorization: Bearer ABCD" \
  -d '{
    "model": "gemini-3-flash",
    "messages": [
      {"role": "user", "content": "Giải thích ngắn gọn về cơ chế Memory Safety trong Rust."}
    ],
    "temperature": 0.2
  }'
```