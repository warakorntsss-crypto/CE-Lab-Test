# CE-Lab-Test

Static prototype website for the **materials testing service** of the
Department of Civil Engineering, Faculty of Engineering, Chiang Mai University.

A multi-layer, shopping-style catalog of laboratory tests. No build step —
plain HTML/CSS/JS, opens directly in a browser.

## Pages (layers)

| File | Role |
|------|------|
| `layer1.html` | Landing — category (หมวด) grid |
| `layer2-concrete.html` | หมวด 1 · Concrete & Masonry — test boxes |
| `layer2-steel.html` | หมวด 2 · Steel, Wire & Rope — test boxes |
| `layer3-concretecompression.html` | กำลังอัดคอนกรีต — product/shopping detail |
| `layer3-steeltension.html` | แรงดึงเหล็กเส้น — product/shopping detail |
| `layer4.html` | Cart — recap + order form |
| `layer5.html` | Checkout — summary + payment method |

Naming: `layer{depth}-{testkey}.html`.

## Features

- Responsive card/box grids, Sarabun Thai font.
- Variant dropdown → live unit price → quantity stepper → line total.
- Cart persisted in `localStorage` (`labCart`); badge counts list items.
- ISO 17025 accreditation emblem on accredited tests.

## Data source

`test-list.md` — test catalog and rates (อัตราปกติ ตามบัญชี ร1/2568).

## Status

Prototype. Only หมวด 1–2 partially wired; remaining categories and detail
pages are placeholders.
