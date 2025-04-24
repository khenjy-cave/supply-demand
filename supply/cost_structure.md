# Cost Structure

What’s the tradeoff when generalizing Omnitags across platforms?

## Costs:
- Increased cognitive load (especially for devs not familiar with dynamic programming)
- Slower performance on cold starts if everything is metadata-parsed live
- Testing complexity (mocking alias-mapped objects, SQL builders)
- Difficult documentation if conventions are loosely enforced

> Omnitags pays a small complexity tax up front to save big on scaling effort.



# Cost Structure

What are the tradeoffs or costs?

- Upfront time to define field aliases and metadata consistently.
- Cognitive load if many content types are handled differently.
- Higher dev responsibility to ensure metadata doesn't break logic.
- Performance impact if JSON is parsed dynamically on every request.

> The cost of flexibility is planning—pay it early, benefit forever.
