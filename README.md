Zomato MCP Server
An mcp server for your food ordering needs.

Disclaimer : This is only for testing purposes and Zomato disclaims any and all liabilities that may arise due to erroneous / non-functionality of the MCP integration.

Supported Features
🔎 Restaurant Discovery - Find nearby restaurants based on your location and preferences.
📒 Menu Browsing - Browse through detailed menus with prices, descriptions, and ratings.
🛒 Cart Creation - Add items to your cart and customize orders with ease.
🥗 Food Ordering - Place orders seamlessly with order tracking support.
💳 QR code payment - Complete secure payments using QR code integration.
Installation Guide
⚠️ OAuth Redirect URI Warning: Currently, we have only whitelisted the following redirect URIs for OAuth authentication. Please reach out to us to enable your client:

claude://claude.ai/settings/connectors
https://chatgpt.com/connector_platform_oauth_redirect
https://claude.ai/api/mcp/auth_callback
https://insiders.vscode.dev/redirect
https://oauth.pstmn.io/v1/callback
https://vscode.dev/redirect
Install in VsCode
One Click Installation

Click to install

Manual Installation

Add this to your mcp.json file.

{
	"servers": {
		"zomato-mcp-server": {
			"url": "https://mcp-server.zomato.com/mcp",
			"type": "http"
		}
	},
}
Disclaimer We are not allowing any third party apps to be built right now due to security and legal consideration, please watch out the space due to this
