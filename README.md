# Free MCP Credential Tester

Welcome to the **Free MCP Credential Tester**, the first entry point in the Universal Agent Economy OS open-core web-of-repos strategy.

## What is this?

This repository provides a lightweight, client-side HTML/JS tool that allows developers to test their agent credentials, tool calls, and x402 payment tokens in a simulation environment. It acts as a discovery funnel, increasing the adoption surface of all our previous artefacts:
- **x402 Middleware**
- **Identity Engine**
- **Vertical Packs**
- **Discovery Metadata**

By giving developers a free, public way to experience the platform, we lower the barrier to entry and drive traffic to the core hosted gateway.

## How to Use

1. **Open the Tester**: Simply open `tools/credential-tester/index.html` in any modern web browser.
2. **Fill out the Form**:
   - **Agent ID**: Enter your unique agent identifier.
   - **Credential Type**: Select the type of credential you are testing (e.g., API Key, OAuth2, x402 Payment Token).
   - **Payment Amount**: If testing x402 monetization, enter the simulation payment amount.
   - **Tool Call**: Provide the JSON payload for the tool your agent is attempting to call.
3. **Test in Simulation Mode**: Click the button to send a test request to our simulation gateway.
4. **View Results**: The response from the gateway will be displayed in the results area.

## Web-of-Repos Strategy

This repository is part of our broader "web of repos" strategy. Instead of a single monolithic repository, we are building a network of interconnected tools and services. 

This credential tester serves as the top of the funnel:
1. **Discover**: Developers find this free testing tool.
2. **Experience**: They simulate agent interactions and x402 payments easily.
3. **Adopt**: They are funneled to the core production gateway to deploy their agents for real.

## Go to Production

Ready to deploy your agents and start monetizing? Head over to the core hosted gateway:

👉 [Agent Economy OS Production Gateway](https://agent-economy-os-production.up.railway.app)

---
*Built for Day 81 of the Universal Agent Economy OS.*