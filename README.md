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
