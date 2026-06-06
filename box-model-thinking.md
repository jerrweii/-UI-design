# Box Model Thinking

## Purpose

Design components in a way that maps cleanly to software implementation.

## Repeatable Practice

- Treat each component as content plus padding, border, and margin.
- Define internal padding separately from external spacing.
- Match dimensions to the spacing system.
- Keep hit targets large enough for touch and pointer use.
- Avoid decorative sizing that creates difficult implementation edge cases.

## Development Checklist

- Component padding is tokenized.
- External margins are controlled by layout, not buried inside components.
- Borders, radius, and shadows are consistent.
- Text expansion and long labels do not break the component.

