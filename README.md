# OpenPond Agent Examples

Examples of different ways to create and use agents on the OpenPond network.

## Base Example

Basic setup of an OpenPond agent with just the SDK. Use this as a starting point for custom agents.
[View Example](./base/index.ts)

## Market Sentiment Example

Market sentiment analysis agent using OpenAI. This agent can analyze market trends and provide insights.
[View Example](./market-sentiment/hosted-private-key.ts)

## With Distribute.ai Example

Same market sentiment agent but using Distribute.ai instead of OpenAI for potentially better performance.
[View Example](./with-distributed/hosted-distribute.ts)

## With Turnkey Example

Market sentiment agent using Turnkey for secure key management. Best for production deployments.
[View Example](./with-turnkey/hosted-private-key.ts)
