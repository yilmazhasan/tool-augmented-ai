# Variants

From an original task, 4-5 variants might be created.

## To create variants:

### Variant with system instructions:

Update the system instructions to include different kind of behavior e.g. assistant should be concise, assistant should be kind etc

### Variant with persona:

Users might have different personas e.g. user might not provide all the informations or they might provide all at once

### Variant with json schema:

Update json schema with competing or mixed functions (Say if original includes 3 functions, this might include 5-6 functions)

### Variant with adversarial cases:

Unhappy cases, where the assistant might not able to fulfill the request at once, or might give up or might fail nicely, recover from failure etc.

### Variant with noisy user prompt:

Users sometimes might ask same thing but with different wording and/or with a noisy data

- Some users might be toxic
- Some users might use slang
- Some developers might include user prompt in JSON/HTML format
- Some users might be verbose
- Some users might use some shortcuts e.g. _"properties.color = red"_, instead of saying _"give me red products"_