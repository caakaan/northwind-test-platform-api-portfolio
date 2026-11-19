# QA Automation Shop API

API documentation and Postman collection for the **Northwind Test Platform**, a QA automation training platform.

**Live API:** [northwind-test-platform.vercel.app](https://northwind-test-platform.vercel.app)  
**Swagger UI:** [API Docs](https://northwind-test-platform.vercel.app/api-docs)  
**Postman collection:** [Open in Postman](https://go.postman.co/workspace/cc66a8a1-e924-458b-9a21-90d1098c3491/collection/589c1b77-a9fc-4f31-8083-1bc53fbcbab9)

## What's included

- `openapi.json`: complete OpenAPI 3.0.3 specification, including paths, schemas, parameters, request bodies, responses, and examples.
- `postman_collection.json`: Postman Collection v2.1 export organized by API area, with 58 requests and 235 example responses.

The contract contains 40 paths covering authentication, products, suppliers, cart, orders, reviews, shipping, reports, health/debugging, and integrations.

## Quick start

1. Import `openapi.json` or `postman_collection.json` into Postman.
2. Set the `baseUrl` variable to `https://northwind-test-platform.vercel.app` or your local API URL.
3. For protected routes, authenticate and provide the returned bearer token where required.

Credentials and tokens in examples are illustrative documentation values, not production credentials.

## Tech stack

OpenAPI 3.0.3 · Postman Collection v2.1 · REST · JSON

---

# Em português

Documentação e collection Postman da **Northwind Test Platform**, plataforma de treinamento em automação de QA.

- `openapi.json`: especificação completa OpenAPI 3.0.3.
- `postman_collection.json`: exportação Postman v2.1 com 58 requisições e 235 exemplos de resposta.
- 40 caminhos cobrindo autenticação, produtos, fornecedores, carrinho, pedidos, avaliações, frete, relatórios, saúde/debug e integrações.

Para importar, carregue um dos arquivos no Postman. Configure `baseUrl` para `https://northwind-test-platform.vercel.app` ou para a URL local. Os usuários e tokens dos exemplos são valores ilustrativos da documentação.
