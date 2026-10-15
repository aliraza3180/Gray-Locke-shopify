# Supplement store: Shopify theme

A Shopify storefront for a dietary supplement, built on Shopify's Horizon 4.3.0 theme with a set of custom sections.

## Custom work

All custom sections appear in the theme editor as "GL | ...".

| Section | File |
|---|---|
| Band | `sections/gl-band.liquid` |
| Columns | `sections/gl-columns.liquid` |
| Diagram | `sections/gl-diagram.liquid` |
| FDA Disclaimer | `sections/gl-disclaimer.liquid` |
| Full Formula | `sections/gl-facts.liquid` |
| FAQ | `sections/gl-faq.liquid` |
| Hero | `sections/gl-hero.liquid` |
| Ingredients | `sections/gl-ingredients.liquid` |
| Size Selector | `sections/gl-size-selector.liquid` |
| Image with Text | `sections/gl-split.liquid` |
| Sticky Add to Cart | `sections/gl-sticky-buy.liquid` |
| Trust Bar | `sections/gl-trust-bar.liquid` |

Shared snippets are in `snippets/gl-*.liquid` and the styles are in `assets/gl-sections.css`.
The size cards add to cart through Horizon's own product form component, so the cart drawer and cart count update as they do on the product page.

## Notes

- Company, brand names and contact details in the content are placeholders.
- Images are referenced from the store's Shopify Files and are not part of this repository.
- Horizon is a theme by Shopify.

## Local development

```
shopify theme dev --store your-store.myshopify.com
```
