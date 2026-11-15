# DESIGN.md — Folkway "Highland Operator & Financial Ledger" (pinned by brief)

**Visual authority:** AFFiNE doc 15 Option A (approved) + `LANDING-PROMPT-v3.md` reskin. Pinned — do not redirect.

## World
Golden-hour savanna, handcrafted operator. Warm vellum paper canvas, Highland field green, one sharp terracotta accent, harvest-gold ambient light. The look of Anthropic Claude × Mercury: literary warmth + calm financial stewardship. Explicitly NOT: dark-mode neon indigo SaaS, corporate blue, purple, black, icon grids.

## Tokens (--fw-*, doc 15 Option A final)
paper `#FAF6EE` · paper-warm `#F4EFE3` · surface `#FFFFFF` · mist-light `#F7F4ED` · mist `#EDE7DA` · mist-dark `#D6CCB9`
ink `#1C1A16` · ink-soft `#24211C` · text-2 `#575147` · text-muted `#787064`
field `#2F4A38` · field-light `#E5EBE6` · field-dark `#1E3024`
clay `#C85232` · clay-light `#F6E6DF` · clay-dark `#943820`
harvest `#B98A2E` · harvest-light `#F5EBD5` · harvest-dark `#785616`
verified `#0F6E4B`/`#E3F3EC`/`#A7DEC6` · merchant `#1E4E68`/`#E6F0F5`/`#B5D3E3` · estimated `#85550D`/`#F9EFD8`/`#E5C888` (dashed) · alert `#9E2A2B`/`#FAE8E8`/`#E6B5B5` (dashed)

## Type
- **Fraunces** display serif — headings; ONE italic emotional word max per heading.
- **Inter** — body/UI.
- **JetBrains Mono** — eyebrows, step numbers, ALL figures, `tabular-nums` everywhere a number is a promise.

## Signature elements
1. **Savanna hero**: layered inline SVG — peach sky `#F6D3BB` → mountain haze `#96A0BC` → grass bands `#D9A64A`/`#C88E3E`/`#8A8A38` → acacias with hanging woven nests → **Twill** the weaver bird (green `#3E7A4A`, cream apron, scarf `#D9622B`, wooden spool of rust thread).
2. **Vellum-glass hero card**: asymmetric 60/40 left-leaning, `backdrop-filter: blur(20px) saturate(140%)`, 1px specular rim, shadow `0 20px 44px -20px rgba(36,33,28,.12)`.
3. **Rust thread motif**: one continuous thread from Twill's spool through section markers to the FAQ underline. Quiet, meaningful.
4. **Paper ledger cards** (white, 1px `#EDE7DA`), clay "The Leak →" markers, harvest-gold benchmark pills.
5. **Vertical ledger steps** (mono 01–04, thread connecting), NOT equal columns.
6. **Pricing = ledger table** on `#F4EFE3`. MOST POPULAR in clay; founding badges harvest gold.
7. **Guarantee = stamped document card** (1px double border, sign-off feel).
8. Night-savanna dark mode (`prefers-color-scheme`): moon over nests, lantern-lit card.

## Motion
Hero planes fade in ≤1.6s (card last); sections rise 12–16px fast ease-out (once, reduced-motion safe); links underline left-to-right like pulled thread; hovers deepen `#2F4A38`→`#1E3024`. No scroll-jacking, no autoplay, no confetti.

## A11y
AA contrast (small clay text uses `#943820`/`#963F29`), clay focus rings, semantic HTML, 1440/1024/768/390, zero layout shift.
