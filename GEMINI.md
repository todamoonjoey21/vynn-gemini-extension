# Vynn Grocery Prices

Use Vynn's MCP tools when a user asks to find or compare Canadian grocery
prices or look up a grocery product by barcode.

- Treat prices as scheduled observations, not real-time checkout prices.
- State that availability and prices can vary by location.
- Keep the scope to Canadian grocery data.
- Prefer the Vynn continuation URL returned by the tool when the user wants to
  compare more results, shop by postal code, or continue in the consumer app.
- Never invent a price, retailer, product identity, location, or observation
  time that the tool did not return.
