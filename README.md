# GDG Americana - Google I/O Extended - 19/07/2025

Apresentação feita no GDG de Americana em 19 de julho de 2025.

Local: Senai Americana

[Link do evento](https://gdg.community.dev/events/details/google-gdg-americana-presents-google-io-extended-americana-2025/)

# Passo a passo

## Pre-Requisitos

## Subir toolbox

Baixe o toolbox e dê permissão de execução
```
# see releases page for other versions
export VERSION=0.9.0
curl -O https://storage.googleapis.com/genai-toolbox/v$VERSION/linux/amd64/toolbox
chmod +x toolbox
```

Execute o toolbox (arquivo [tools.yaml](toolbox/tools.yaml) utilizado)
```
./toolbox --tools-file "tools.yaml"
```

## MCP Inspector

Execute e abra o MCP Inspector apontando para `http://127.0.0.1:5000/mcp`
```
npx @modelcontextprotocol/inspector
```

## ADK

Instalando o ADK usando pip
```
pip install google-adk
```

Execute o adk web na pasta investment-research e abra o navegador
```
adk web
```

# Slides
[PDF](slides/GDG-Americana-Neo4j.pdf)

# Links 

[Página Oficial do MCP](https://modelcontextprotocol.io/)

[Documentação Google Agent Development Kit](https://google.github.io/adk-docs/)

[ADK Python](https://github.com/google/adk-python)

[MCP Toolbox for Database](https://github.com/googleapis/genai-toolbox)

[Comunidade Neo4j no WhatsApp](https://chat.whatsapp.com/CQGa1sVzhAO3BMkLTf1116)

[GraphAcademy - Plataforma de cursos gratuitos da Neo4j](https://graphacademy.neo4j.com/pt)

[Ambiente Sandbox Neo4j](https://sandbox.neo4j.com/)

## MCP Servers
[https://mcpservers.org/](https://mcpservers.org/)

[https://hub.docker.com/mcp](https://hub.docker.com/mcp)

[https://mcp.so/](https://mcp.so/)

[https://cursor.directory/](https://cursor.directory/)

## Autor
[LinkedIn](https://www.linkedin.com/in/eliezerzarpelao/)

[YouTube](https://youtube.com/eliezerzarpelao)

