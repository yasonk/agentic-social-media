# Agentic Social Media

## Introduction (5 minutes)
- Jack is frustrated with algorithmic feeds showing inappropriate content, intrusive product suggestions, reduced visibility of friends and relatives, and constant exposure to rage-baiting.
- I will present research showing these frustrations are widespread, using recent studies from pewresearch, psychiatry.org, theharrispoll, and Georgetown university.

## The Why (2 minutes)
- The internet revolves around the fact that the user is the product, resulting in one-size-fits-none experiences.

## The solution (2 minutes)
- Define AI agents and describe where they fit into existing web infrastructure.
- Show a diagram illustrating a web service augmented with an AI agent.
- Explain how agents transform traditional patterns of request handling, data gathering, and UI generation.

## Replacing the Traditional Backend with an Agentic Backend (6 minutes)
- Business logic can be written in natural language. The agent is the code.
- User interfaces can be dynamically generated instead of being preprogrammed.
- Show diagram of Agent + Tools (MCP).
- Show diagram of a ReAct agent generating GitHub dashboards with a fully agentic backend - zero code is written for business logic, all logic is written in natural language.
- Provide a GitHub repo link demonstrating a fully agentic, interactive application.
- Note that hybrid systems (agent + algorithms) are often necessary for security, performance, and consistency.

## Bringing It Back to Jack: Agentic Social Media (6 minutes)
- Show a ReAct agent diagram where BlueSky Jetstream is the inbound data source.
- Explain the hybrid model: Python handles data ingestion, interactivity, and security; the agent handles filtering, sorting, curation, and content presentation.
- Compare two approaches to agent-generated dynamic UIs:
  - Agent generates the code needed to process arbitrary data formats.
  - UI is predefined and the data is embedded directly into the generated interface.
- Discuss the trade-offs of each approach in terms of flexibility, safety, and maintainability.

## Conclusion (2 minute)
- Present other use cases for fully agentic applications. 
