# indigo-core

Local-first companion engine.

- PWA chat over WebSocket
- Ollama text + vision
- Image paste + screen-share frames
- Three.js VRM stage (`@pixiv/three-vrm`)
- `[action:...]` tags for clothes / camera / extras

Bring your own character file (`character.md`), face image, and `.vrm`.

## Run

```bash
ollama pull llama3.1
npm install
npm start
# http://localhost:8081
```

```bash
TEXT_MODEL=qwen2.5:32b VISION_MODEL=llava npm start
```

## Character

Copy `character.example.md` to `character.md`. The server reads that file as the system prompt.

Do not commit private portraits, VRM bodies, or session logs.

MIT for the engine. Your character files stay yours.
