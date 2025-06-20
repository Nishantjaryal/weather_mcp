# weather_mcp

weather_mcp server acts as a api for ai models to fetch weather data

## Run it

1. **Clone the Repository**

```bash
https://github.com/Nishantjaryal/weather_mcp.git
```

```bash
cd weather_mcp
```

```bash
npm install
```

### claude_desktop_config.json

```bash
{
  "mcpServers": {
    "weather": {
      "command": "node",
      "args": ["ABSOLUTE LOCATION OF .JS FILE IN BUILD DIRECTORY"]
    }
  }
}

```
