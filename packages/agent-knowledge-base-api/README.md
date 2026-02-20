# agent-knowledge-base-api

> Package 2: api for Intelligent Knowledge Base

## Installation

```bash
npm install @agent-knowledge-base/agent-knowledge-base-api
```

## Usage

```javascript
import { AgentKnowledgeBaseApi } from '@agent-knowledge-base/agent-knowledge-base-api';

const service = new AgentKnowledgeBaseApi();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
