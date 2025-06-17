# snello-ai-generator

We need to create some MCP Servers:
- maven + quaryable
  - mvn create ....
  - mvn queryable-maven-plugin:3.0.4:add
  - mvnw queryable:install
  - mvnw queryable:source   
- github
  - create repository for code
    - git init
    - git add actions  
  - create repository for remote server
    - using templates 
- server
  - generate docker-compose from scaffoling
  - start and stop of project
    - remote ssh commands using ssh-key
   
# exampe of use of mcp server and creation of mcp server
  - https://quarkus.io/blog/agentic-ai-with-quarkus-p2/
  - https://www.geeksforgeeks.org/java/java-runtime-exec-method/
  - https://github.com/sshaaf/keycloak-mcp-server
  - https://foojay.io/today/building-local-llm-ai-powered-applications-with-quarkus-ollama-and-testcontainers/
  - https://github.com/mariofusco/quarkus-agentic-ai/tree/main/src/main/java/org/agenticai/routing


## some mcp server linked to client
  - https://glaforge.dev/posts/2025/04/04/mcp-client-and-server-with-java-mcp-sdk-and-langchain4j/
  - https://github.com/langchain4j/langchain4j-examples/blob/main/mcp-github-example/src/main/java/dev/langchain4j/example/mcp/github/McpGithubToolsExample.java
  - https://www.linkedin.com/pulse/integrating-mcp-model-context-protocol-langchain4j-access-goncalves-pedze/
