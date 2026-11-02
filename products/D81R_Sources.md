# D81R Series D812R and D813R

Two-page English HTML presentation, following the existing UROVO product series. Source checks: 2026-11-02.

## Product sources

- Dedicated specification: `/Users/patrickxu/patrick-agent/skills/urovo-product-expert/D81R Series/specs/default_202610081413/D81R Series(EN)-SPEC-20250114.pdf` (modified 2026-09-24).
- Brochure: `/Users/patrickxu/patrick-agent/skills/urovo-product-expert/D81R Series/brochure/default_202610081413/D81R Series(EN)-PB-2025.pdf`.
- A3 manual: `/Users/patrickxu/Downloads/D81R-RFID系列-使用手册（英）261023.docx`, revision A3 dated 2026-09-24.
- Shared printer configuration: `/Users/patrickxu/patrick-agent/skills/urovo-product-expert/_shared/accessories/device-and-accessories-guide_202609182242/Device-and-Accessories-Guide-20260918.md`.

The dedicated spec controls D812R 203 dpi / 104 mm and D813R 300 dpi / 108.4 mm. Both list up to 4 in/s RFID print + encode. A3 print-only speeds of 200 / 150 mm/s are kept separate in notes. On-metal support is optional, for validated media, conservatively up to 1.3 mm. No price or throughput superiority is inferred.

The HTML source notes preserve differences in width, RAM subtype, maximum media width, core sizes, wireless options and anti-metal thickness (1.3 versus 1.5 mm). The stated 15 mm pitch and parenthetical 0.625 inches are inconsistent, so no comparative pitch advantage is claimed. The 300 m ribbon is not presented as exclusive or as included stock.

## Manufacturer competitor references

- Zebra ZD621R official support: https://www.zebra.com/us/en/support-downloads/printers/desktop/zd621.html
- Zebra official user guide: https://www.zebra.com/content/dam/support-dam/en/documentation/unrestricted/guide/product/zd421-zd621-ug-en.pdf
- Manufacturer-authored Zebra datasheet reference copy: https://www.jarltech.com/sites/default/files/documents/product/datasheet/en/Zebra_ZD621_RFID_DataSheet_EN.pdf
- TSC TH240/DH240 Series official manual: https://fs.tscprinters.com/es/dl/3/8368

TSC TH240T and TH340T comparisons are for RFID configurations, excluding RC ribbon-cartridge variants. Selected on-metal tags up to 1.35 mm are qualified to tear-off mode. SATO CL4NX Plus is omitted from the main table because it is an industrial-class reference.

## Original product artwork

The hero is extracted from page 1, image Im3.jp2, of the dedicated D81R specification. It is decoded and losslessly saved as PNG for browser compatibility, with no retouching or proportion change.

Project asset: `../assets/cc5558bfac2538ef2e16.png`.

## Application illustration

Tool: built-in `image_gen`. The apparel-tagging scene is an illustration, not a customer deployment, supplied RFID media or a validated barcode result.

Generated original: `/Users/patrickxu/.codex/generated_images/01a1998d-d799-7483-ac53-0a066ae3305b/exec-8958a5ef-2b25-4310-89aa-3f9e861d5f30.png`.

Project asset: `../assets/d81r-apparel-tagging-scene.png`.

Reference: original product rendering extracted from the dedicated D81R specification.

Final prompt:

```text
Use case: photorealistic-natural.
Asset type: 16:9 wide application photo illustration for the UROVO D81R desktop UHF RFID printer presentation.
Input image role: exact hardware identity reference extracted from the original D81R product specification. Preserve its compact black rounded desktop body, smooth dark gray sloped top, small status LEDs on top, circular feed button marking, UHF badge, turquoise oval side latch, front UROVO badge and wide horizontal front output slot. No screen, no keyboard, no added antennas.
Scene: a tidy clothing-store backroom tagging station. The exact reference printer stands on a light wood workbench beside neatly folded garments and a small roll of blank labels. One store employee is visible only as forearms and hands, collecting a just-printed garment label from near the output slot. A short straight strip of white adhesive labels with simple generic SKU text and one barcode emerges from the output slot. Do not show the label running through any other machine or a rewind loop.
Composition: printer is the clear focal point, on the center-right, large enough to recognize its exact original shape, viewed from the reference three-quarter front-left angle. Folded garments and hands provide context to the left. Softly blurred shelving in background. Natural bright indoor light, realistic material textures and shadows, restrained professional editorial photography.
Constraints: preserve device identity and proportions strictly. No invented touchscreen, thermal receipt tower, scanner gun, card-payment reader, antenna or visible cutter mechanism. No financial payment scene. No floating icons, callout labels, infographic text, watermarks or extra branding. This is a conceptual application illustration, not a real customer installation.
```
