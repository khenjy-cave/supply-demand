# Cost Structure

What’s the tradeoff when generalizing Omnitags across platforms?

## Costs:
- Increased cognitive load (especially for devs not familiar with dynamic programming)
- Slower performance on cold starts if everything is metadata-parsed live
- Testing complexity (mocking alias-mapped objects, SQL builders)
- Difficult documentation if conventions are loosely enforced

> Omnitags pays a small complexity tax up front to save big on scaling effort.
