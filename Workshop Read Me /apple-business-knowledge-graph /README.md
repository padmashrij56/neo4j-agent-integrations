# Business Knowledge Graph with Neo4j

Hands-on work from the AI Workshop with Neo4j and Microsoft,
held October 1, 2026, in Chicago.

## My Work
- Used Neo4j Aura Document Intelligence to model a business
  knowledge graph from an Apple Form 10-K excerpt.
- Explored products, services, markets, distribution channels,
  and their relationships.
- Participated in the workshop’s MCP integration exercise.

## Results
- Graph preview: 88 nodes and 89 relationships.
- Exported model: 10 named entity types and 11 relationship types,
  with property definitions and constraints.

The JSON export contains the model structure, not the populated
graph data. The preview does not demonstrate a deployed database.
The MCP exercise is documented separately; its connection to this
Apple graph has not been confirmed.

## Sources and Credits
Completed using guided workshop materials. Original framework
and reference code belong to Neo4j Labs and their contributors.

- Source document: Apple_10-K_2025_2_pages.pdf
- [Workshop](https://www.aicamp.ai/event/eventdetails/W2026100111)
- [Microsoft Foundry + Neo4j](https://github.com/neo4j-labs/neo4j-agent-integrations/tree/main/microsoft-foundry)
- [MCP setup guide](https://github.com/neo4j-labs/neo4j-agent-integrations/blob/main/microsoft-foundry/infra/README.md)
- [GenAI ecosystem](https://neo4j.com/labs/genai-ecosystem/)
