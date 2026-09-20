<p align="center">
  <img src="assets/vynn-logo.png" alt="Vynn logo" width="112">
</p>

# Vynn Grocery Prices for Gemini CLI

Find and compare nightly-observed Canadian grocery prices from Vynn directly
in Gemini CLI. The extension connects Gemini to Vynn's public, read-only MCP
server and can:

- search for grocery products and observed prices;
- look up a grocery product by barcode; and
- send shoppers to [vynnapp.com](https://www.vynnapp.com/) to compare more
  results or continue shopping.

No Vynn account or API key is required to use the connector. Prices come from
scheduled observations and are not real-time checkout prices. Availability and
prices can vary by location.

## Install

```bash
gemini extensions install https://github.com/todamoonjoey21/vynn-gemini-extension
```

Restart Gemini CLI after installation. Then ask, for example:

> Use Vynn to find milk prices in Ontario.

## Tools

| Tool | Purpose |
| --- | --- |
| `search_products` | Search Canadian grocery products and observed prices. |
| `lookup_product` | Look up a grocery product by UPC, EAN, or GTIN barcode. |

The connector is read-only. It does not place orders or change a Vynn account.
When a shopper follows a returned Vynn link, their account and Vynn+ access are
handled by the consumer platform at vynnapp.com.

## Privacy and support

- [Privacy policy](https://www.vynnapp.com/privacy)
- [Terms of service](https://www.vynnapp.com/terms)
- Support: [hello@vynnapp.com](mailto:hello@vynnapp.com)

## License

Apache-2.0. See [LICENSE](LICENSE).
