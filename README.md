# Perfume Dilution Calculator

A small web tool for the volume-ratio math behind perfume dilution.

No build step, no dependencies, no accounts. One `index.html` file - open it in any browser and it works, offline too.

## What it does

**Blend from oil** - enter a final volume and an oil concentration (% by volume), and it gives you:

- fragrance oil volume
- diluent (perfumer's alcohol) volume

**Dilute a concentrate** - enter an existing concentrate strength, a target strength, and the final volume you want. It applies the standard dilution relation (C1V1 = C2V2) and gives you concentrate and diluent volumes.

Both modes update live as you type.

## Scope

Volume ratios only (% v/v), assuming volumes add exactly; real mixtures can contract slightly. This is arithmetic, not safety, skin-use or IFRA guidance - always follow the safety documentation for your specific materials.

## Run it locally

```
open index.html        # macOS
xdg-open index.html    # Linux
start index.html       # Windows
```

Or serve the folder with any static file server.

## License

MIT - see [LICENSE](LICENSE). (Draft: the licence takes effect on publication.)
