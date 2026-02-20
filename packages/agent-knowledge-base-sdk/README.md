# agent-knowledge-base-sdk

> Package 3: sdk for Intelligent Knowledge Base

## Installation

```bash
npm install @agent-knowledge-base/agent-knowledge-base-sdk
```

## Usage

```javascript
import { AgentKnowledgeBaseSdk } from '@agent-knowledge-base/agent-knowledge-base-sdk';

const service = new AgentKnowledgeBaseSdk();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
