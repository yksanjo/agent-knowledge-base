# agent-knowledge-base-monitor

> Service: monitor for Intelligent Knowledge Base

## Installation

```bash
npm install @agent-knowledge-base/agent-knowledge-base-monitor
```

## Usage

```javascript
import { AgentKnowledgeBaseMonitor } from '@agent-knowledge-base/agent-knowledge-base-monitor';

const service = new AgentKnowledgeBaseMonitor();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
