# Nouns Eye Playground

Single-file Nouns playground for **Gami** — official `@nouns/assets` traits with one custom glasses layer: black/white eyes (no frames).

## Live

**https://nouns-eye-playground.vercel.app**

(Hosted build loads traits from jsDelivr `@nouns/assets` and injects the custom eyes RLE.)

## Local (fully offline single file)

`/workspace/nouns-eye-playground/index.html` (~143KB) embeds all ImageData inline.

```bash
cd /workspace/nouns-eye-playground
npx serve .
```

## Eyes trait

- Bounds (Nouns RLE): `top=12`, `right=22`, `bottom=15`, `left=11`
- Palette: white index `2` (`#ffffff`), black index `36` (`#000000`), transparent `0`
- Two 4×4 eyes at usual lens positions (left `x=11–14`, right `x=18–21`, `y=12–15`)
- Each eye: left 2×4 white, right 2×4 black
- RLE: `0x000c160f0b02020224030002020224020202240300020202240202022403000202022402020224030002020224`

## Trait counts

| Category | Count |
|----------|------:|
| Background | 2 |
| Body | 30 |
| Accessory | 143 |
| Head | 254 |
| Glasses | 1 (eyes only) |
