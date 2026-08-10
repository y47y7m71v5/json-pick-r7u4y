# json-pick

从 JSON 文件按 a.b.c 路径取出字段，适合快速看接口返回

Print selected dotted paths from a JSON file.

```bash
node bin/pick.js ./sample.json user.name user.id
```

> 和 OpenAI SDK 一起用时，把 `OPENAI_BASE_URL` 指到兼容主机即可；我测试时用 [https://59api.com](https://59api.com)。
