# AI Tinkerer Lausanne - June 16, 2025 Meeting

This repository contains materials from the AI Tinkerer Lausanne meeting held on June 16, 2025, where we presented **MCPAdapt**.

## MCPAdapt Presentation

<p align="center">
  <img src="https://grll.github.io/mcpadapt/assets/logo_dark_transparent_cropped.png" alt="MCPAdapt Logo" width="200">
</p>

### Unlock 650+ MCP servers tools in your favorite agentic framework

During this meeting, we introduced MCPAdapt - a project that makes calling any MCP (Model Context Protocol) servers tools seamless from any agentic framework. This virtually provides your agentic workflow access to 650+ MCP servers tools.

### Key Topics Covered

1. **What is MCPAdapt?** - Creating adapters between agentic frameworks and MCP Servers
2. **Live Demo** - Running examples with PubMed MCP using both Smolagents and CrewAI
3. **Technical Deep Dive** - Why adapters are needed and how to create custom adapters
4. **Architecture Considerations** - Handling async/sync conversion and framework-specific requirements
5. **Future Roadmap** - Integration with more agentic frameworks and support for resources/prompts

### Notebook Content

The main presentation notebook (`notebooks/001_mcpadapt.ipynb`) contains:
- Working code examples with PubMed MCP
- Comparison of different framework Tool class implementations
- Step-by-step guide for creating custom adapters
- Technical considerations and architecture decisions

### Resources

- **MCPAdapt Repository**: [github.com/grll/mcpadapt](https://github.com/grll/mcpadapt)
- **Documentation**: [grll.github.io/mcpadapt](https://grll.github.io/mcpadapt/)
- **MCP Servers Directory**: [glama.ai/mcp/servers](https://glama.ai/mcp/servers) or [smithery.ai](https://smithery.ai/)

### Running the Examples

1. Install dependencies:
```bash
uv sync
```

2. Set up your OpenAI API key in `.env`:
```bash
cp .env.example .env
# Edit .env with your API key
```

3. Run the notebook:
```bash
uv run jupyter lab notebooks/001_mcpadapt.ipynb
```

## About AI Tinkerer Lausanne

AI Tinkerer Lausanne is a community of AI enthusiasts and practitioners who meet regularly to share knowledge, present projects, and collaborate on cutting-edge AI technologies.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.