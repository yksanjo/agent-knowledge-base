# agent-knowledge-base-cli

> Package 4: cli for Intelligent Knowledge Base

## Installation

```bash
npm install @agent-knowledge-base/agent-knowledge-base-cli
```

## Usage

```javascript
import { AgentKnowledgeBaseCli } from '@agent-knowledge-base/agent-knowledge-base-cli';

const service = new AgentKnowledgeBaseCli();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
