# The Flower Shop Ottawa

## Page inventory and sitemap

The site has six main pages and supporting shopping pages. “Projects” presents
the shop's floral design work; “Flower Care” is the additional student-chosen
page.

```text
Primary navigation
Home
├── About
├── Projects
├── Shop Bouquets
│   └── Bouquet Details
├── Flower Care
└── Contact

Account and shopping navigation
Home
├── Account
├── Search Results
│   └── Bouquet Details
├── Favorites
│   └── Bouquet Details
└── Cart
    └── Checkout
        └── Order Confirmation

Bouquet Details ── add to cart ──> Cart
```

### Three-click check

Every page is reachable from Home in one click through the primary or account
and shopping navigation. Bouquet Details is one click from Shop Bouquets,
Search Results, or Favorites; Cart is one click from the shopping navigation or
Bouquet Details; Checkout is one click from Cart; and Order Confirmation is one
click from Checkout. The longest planned path is Home → Cart → Checkout → Order
Confirmation (three clicks). No exception is planned.

## Homepage wireframes

The existing [mobile mockup](./HOME%20PAGE.jpg) is 390 × 1109 pixels, so it is
the mobile design reference. The desktop sketch below rearranges the same
regions for a wide screen. The product areas represent bouquet cards; the
footer represents the social links shown in the mockup.

### Mobile

```text
┌──────────────────────────────┐
│ Brand                        │
│ Account  Menu  Search        │
│          Favorites  Cart     │
├──────────────────────────────┤
│ Promotion banner             │
├──────────────────────────────┤
│ Bouquet Styles               │
│       [bouquet] [bouquet]    │
├──────────────────────────────┤
│ Other Bouquets               │
│ [bouquet] [bouquet] [bouquet]│
│ [bouquet] [bouquet] [bouquet]│
├──────────────────────────────┤
│ Featured Bouquets            │
│ [bouquet] [bouquet] [bouquet]│
├──────────────────────────────┤
│ Seasonal Bouquets            │
│ [bouquet] [bouquet] [bouquet]│
├──────────────────────────────┤
│ Social links                 │
└──────────────────────────────┘
```

### Desktop

```text
┌──────────────────────────────────────────────────────────────────────────┐
│ Brand                 Primary navigation                  Account/Search│
│                                                       Favorites / Cart   │
├──────────────────────────────────────────────────────────────────────────┤
│                           Promotion banner                               │
├──────────────────────────────────────────────────────────────────────────┤
│ Bouquet Styles                                                           │
│ [bouquet] [bouquet] [bouquet] [bouquet] [bouquet]                        │
├──────────────────────────────────────────────────────────────────────────┤
│ Other Bouquets                                                           │
│ [bouquet] [bouquet] [bouquet] [bouquet] [bouquet] [bouquet]              │
├──────────────────────────────────────────────────────────────────────────┤
│ Featured Bouquets                                                        │
│ [bouquet] [bouquet] [bouquet] [bouquet] [bouquet]                        │
├──────────────────────────────────────────────────────────────────────────┤
│ Seasonal Bouquets                                                        │
│ [bouquet] [bouquet] [bouquet] [bouquet] [bouquet]                        │
├──────────────────────────────────────────────────────────────────────────┤
│ Social links                                                             │
└──────────────────────────────────────────────────────────────────────────┘
```

## Existing colour palette

- Primary: `#B45F06`
- Primary tints: `#D6B68A`, `#F3C969`, `#7A8F6A`
- Primary shades: `#D9A066`, `#E6B8C4`
- Neutrals: `#E6E6E6`, `#FFFFFF`

The homepage HTML is structural only. It intentionally does not link the
stylesheet or add product copy, images, colours, fonts, or spacing.
