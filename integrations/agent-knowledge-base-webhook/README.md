# agent-knowledge-base-webhook

> Integration: webhook for Intelligent Knowledge Base

## Installation

```bash
npm install @agent-knowledge-base/agent-knowledge-base-webhook
```

## Usage

```javascript
import { AgentKnowledgeBaseWebhook } from '@agent-knowledge-base/agent-knowledge-base-webhook';

const service = new AgentKnowledgeBaseWebhook();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
