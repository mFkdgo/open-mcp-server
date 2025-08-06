<import src="https://raw.githubusercontent.com/openmcp/openmcp/master/docs/openmcp-deploy.md"/>

###json config

{
  "mcpServers": {
    "azt-open": {
        "command": "uvx",
        "args": [
          "open-mcp-server@latest"
        ],
		"env": {
				"API_KEY": "",
				"SECRET_KEY": "",
				"VERSION": "1.0",
				"ENV_URL": ""
			}
      }
  }
}
