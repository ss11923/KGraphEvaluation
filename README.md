# KGraphEvaluation
Knowledge Graph Evaluation: Neo4j GraphBuilder vs. Microsoft GraphRAG


Overview:
This repository contains code and resources for the comparative analysis of two tools used for automated knowledge graph generation from unstructured text: Neo4j’s GraphBuilder and Microsoft’s GraphRAG. Both tools leverage large language models (LLMs) to extract entities and relationships, transforming unstructured data into structured knowledge graphs. The analysis evaluates various metrics such as entity extraction, node degree distribution, clustering, and community detection to provide insights into the strengths and limitations of each tool.

Project Components:
The scripts used to process unstructured text through Neo4j’s GraphBuilder and Microsoft’s GraphRAG, and output knowledge graphs. Charles Dickens' novel "A Christmas Carol" was used as a sample unstructured file to standardize the generation of knowledge graphs for both tools.

Evaluation Metrics:
Entity Extraction and Labeling: Compares the frequency and types of entities extracted by both tools.
Node Degree Distribution: Measures graph connectivity by assessing how well nodes (entities) are linked.
Clustering and Community Detection: Visualizes and analyzes how entities are grouped into clusters and communities within the graphs.

Key Findings:
From this evaluation, we can conclude that GraphBuilder tends to generate larger, more detailed graphs with a broader range of entities, but many of the nodes remain isolated (orphan nodes), reducing overall graph connectivity.
GraphRAG produces more interconnected graphs with fewer nodes but stronger relationships between entities, making it more efficient for reasoning and querying tasks.
Node Degree Analysis reveals that GraphBuilder excels in entity extraction, while GraphRAG maintains denser and more meaningful relationships between entities.
