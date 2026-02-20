# agent-knowledge-base-core

> Package 1: core for Intelligent Knowledge Base

## Installation

```bash
npm install @agent-knowledge-base/agent-knowledge-base-core
```

## Usage

```javascript
import { AgentKnowledgeBaseCore } from '@agent-knowledge-base/agent-knowledge-base-core';

const service = new AgentKnowledgeBaseCore();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
