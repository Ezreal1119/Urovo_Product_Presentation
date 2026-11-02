# GAINSCHA GS-2208D

Two-page English product reference focused on coffee-counter labels. GS-3205D is excluded. Source checks: 2026-11-02.

## Controlling source and artwork

Customer PDF: `/Volumes/SSD1T/Downloads/debuglogger/2 Inch Desktop Label Printer GS-2208D.pdf`.

Both pages were rendered and read visually because most text is outlined. The GS-2208D column specifies 203 dpi, direct thermal, up to 203.2 mm/s (8 ips), 54 mm maximum print width, 127 mm maximum roll OD, 129 × 165.3 × 244.3 mm, 1.3 kg, USB + Ethernet, and optional Bluetooth/Wi-Fi. No USB Host is promised for this supplied edition. The reference is identified as GAINSCHA, while UROVO branding identifies the presentation collection.

The original product art is decoded from page 1, `Im2.jp2`, and losslessly saved as PNG without retouching or proportion changes: `../assets/407ff0fc4e7cc36342ed.png`.

The HTML notes retain edition differences, optional dual-colour stock requirements and the limits of command emulation and label/adhesive compatibility. They do not claim waterproof labels, clinical certification or a guaranteed app connection.

## Public manufacturer references

- GAINSCHA: https://gainscha.com.tw/Product-Center/Desktop-Barcode-Printer/Surpass-Series/2-Inch-Desktop-Label-Printer-GS-2208D
- TSC DH220: https://usca.tscprinters.com/en/products/dh-series-2-inch-high-precision-desktop-printers
- TSC family datasheet: https://fs.tscprinters.com/system/files/tsc-auto-id-th-dh-series-en-20250930.pdf
- Zebra ZD411: https://www.zebra.com/us/en/products/printers/desktop/zd400-series/zd411.html
- Zebra technical specification: https://www.zebra.com/content/dam/zebra_dam/en/tech-specs/zd411-tech-specs-en-us.pdf

TSC's 203 dpi / 8 ips / 54 mm / 127 mm figures match GS-2208D's principal headline specifications. Zebra's 203 dpi maximum print width is 56 mm; USB Host and optional Ethernet are reported as its own configuration. Differing Zebra speed wording across official documents is not used to make a speed superiority claim.

## Luckin coffee reference video

The customer identifies the supplied clip as a Luckin coffee reference. Sampled frames show a Gainscha printer printing labels and a coffee-store drink preparation workflow. Exact model and rollout scope are not independently established by a readable model plate. The deck attributes the clip to the customer and does not claim official endorsement, exclusive supply or all-store deployment.

Original, unchanged: `/Volumes/SSD1T/Downloads/debuglogger/1102-luckin.mov` (about 35.93 seconds; H.264/AAC; 2560×1440; 70,741,165 bytes).

Web copy: `../assets/gs2208d-luckin-demo.mp4` (about 35.94 seconds; H.264/AAC; 682×1080; 12,359,259 bytes).

Only fixed black sidebars are removed, using crop `908:1440:826:0`; the complete sequence is scaled to 1080 pixels tall, encoded as H.264 CRF 23 with the original AAC audio copied, and stored as MP4 with fast-start metadata. There are no scene cuts, speed changes or changes to the original file. Poster: `../assets/gs2208d-luckin-poster.jpg`, extracted at 2 seconds from the web copy.

The play button opens a native HTML dialog with standard video controls. Close, Escape, backdrop click and slide changes stop and reset the video. The embedded and standalone product pages use the same local media file. A catalog entry also exposes the clip in the collection's Video library on the two GS-2208D pages.

## Café illustration

Tool: built-in `image_gen`. This is a generated application illustration, not a frame from the customer video or proof of a customer deployment.

Generated original: `/Users/patrickxu/.codex/generated_images/01a1998d-d799-7483-ac53-0a066ae3305b/exec-91d2e0c5-ead6-4ff0-8727-c82fcaa1e1ee.png`.

Project asset: `../assets/gs2208d-cafe-scene.png`.

Final prompt:

```text
Use case: photorealistic-natural.
Asset type: 16:9 wide cafe workflow illustration for a two-inch desktop label printer presentation.
Reference image role: exact GS-2208D hardware identity. Preserve its dark gray angular body, black upper media window, two small circular front-top buttons and small indicator lights, turquoise side release latch, front horizontal label output, Gainscha wordmark, width-to-height proportions and compact desktop size. No invented UROVO branding.
Scene: a bright modern coffee shop counter. The exact printer is beside a point-of-sale screen, printing a small white drink order label. A barista's hands take a printed adhesive label and apply it to a blue takeaway coffee cup with a white lid; another prepared drink waits nearby. The label has a simple generic English drink order with 'Latte', 'Less ice', '30% sugar' and 'Order 028'. The printer and labelled cup are the focal points. Softly blurred espresso equipment and coffee shop background, warm natural daylight, realistic materials and anatomy. Render as a professional editorial photo.
Composition: wide horizontal crop, close enough to clearly recognize the printer, matching its original front-left three-quarter angle. Printer near left-center, hands and cup near center-right. Keep the lower-right corner calm for a play-video button that will be added later in HTML. Do not draw the button into the image.
Constraints: exact reference printer design, not a receipt tower or four-inch RFID printer. No touchscreen added to the printer, no cutter or extra hardware. No floating captions, UI overlays, QR art, watermarks, made-up certification marks or large brand logos on the cups. This is an application illustration, not documentary evidence of the supplied Luckin coffee video.
```
