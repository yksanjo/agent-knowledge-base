# agent-knowledge-base-analyzer

> Service: analyzer for Intelligent Knowledge Base

## Installation

```bash
npm install @agent-knowledge-base/agent-knowledge-base-analyzer
```

## Usage

```javascript
import { AgentKnowledgeBaseAnalyzer } from '@agent-knowledge-base/agent-knowledge-base-analyzer';

const service = new AgentKnowledgeBaseAnalyzer();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT
