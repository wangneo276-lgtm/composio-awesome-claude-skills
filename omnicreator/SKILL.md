---
name: omnicreator
description: >
  Use Omni Creator (https://omnicreator.art), an AI Photo Editor Online
  free to try. Edit photos by typing: replace a background, remove objects,
  product photos, change an outfit, relight, text-to-image, upscale, virtual
  try-on, dual-image edit. Sign in with Google and check in for +10 credits daily.
---

# Omni Creator

Open **https://omnicreator.art/**. Omni Creator is an AI Photo Editor Online free to try. Sign in, check in for +10 credits daily, and edit photos by typing.

Support: support@omnicreator.art

## When to Use This Skill

- Someone asks to replace a photo background, remove objects, or clean a product shot
- Someone wants to change an outfit, relight a photo, or generate an image from text
- Someone needs image upscale, virtual try-on, or a dual-image edit
- The work should happen in the browser at https://omnicreator.art, not by calling generation APIs from this skill

## What This Skill Does

1. **Opens the live editor**: Send the person to https://omnicreator.art
2. **Points at the right page**: Background, object removal, product photo, fashion, relight, text-to-image, upscale, try-on, dual-image
3. **Explains credits**: Google sign-in, 20 starter credits, +10 daily check-in; failed generations are not charged
4. **Reads public facts via MCP**: `https://omnicreator.art/mcp` tools `get_overview`, `list_pages`, `fetch_public_page` are read-only

## How to Use

### Basic Usage

```
Help me replace the background of this photo at https://omnicreator.art
```

```
Open Omni Creator and walk me through removing the person on the left
```

### Advanced Usage

```
I have a messy phone photo of a product. Use Omni Creator (https://omnicreator.art/use-cases/product-photo) and tell me what to upload and type.
```

## Example

**User**: "Help me swap this carpet for a clean white studio background"

**Output**:
```
Open https://omnicreator.art/use-cases/background-replace
Sign in with Google, check in for +10 credits if you have not today, upload a JPG/PNG/WebP (max 25 MB), then type: clean white studio
```

**Inspired by:** Omni Creator at https://omnicreator.art

## Tips

- Upload JPG, PNG, WebP, AVIF, HEIC or HEIF up to 25 MB. BMP is not supported.
- Type the change in one sentence. Examples from the live pages: “clean white studio”, “the person on the left”, “a navy wool overcoat”.
- Checkout is not live. Use daily check-in credits today.
- Do not call `/api/studio/generate` from this skill. Generation needs the user’s Google session in the browser.

## Common Use Cases

- **Background replace**: https://omnicreator.art/use-cases/background-replace
- **Object removal**: https://omnicreator.art/use-cases/object-removal
- **Product photo**: https://omnicreator.art/use-cases/product-photo
- **Fashion edit**: https://omnicreator.art/use-cases/fashion-edit
- **Relight**: https://omnicreator.art/use-cases/photo-relighting
- **Text to image**: https://omnicreator.art/use-cases/text-to-image
- **Upscale**: https://omnicreator.art/image-upscale
- **Virtual try-on**: https://omnicreator.art/virtual-try-on
- **Dual-image edit**: https://omnicreator.art/dual-image-edit
