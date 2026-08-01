# Hanzo-VideoHelper

ComfyUI nodes for video in and out — load a video as frames, combine frames back into a video, and the batch plumbing around that.

This is a Hanzo-maintained fork of [Kosinkadink/ComfyUI-VideoHelperSuite](https://github.com/Kosinkadink/ComfyUI-VideoHelperSuite), pinned so the ComfyUI node packs we
run together stay on versions we have tested together.

## Install

```bash
cd ComfyUI/custom_nodes
git clone https://github.com/hanzoai/Hanzo-VideoHelper
cd Hanzo-VideoHelper
[ -f requirements.txt ] && pip install -r requirements.txt
```

Restart ComfyUI. The nodes appear in the node menu under the categories upstream defines.

## Docs

Node reference and usage are upstream's — see [Kosinkadink/ComfyUI-VideoHelperSuite](https://github.com/Kosinkadink/ComfyUI-VideoHelperSuite). Nothing about the nodes
themselves is changed here.

## Contributing

Improvements to the nodes belong upstream: open them against
[Kosinkadink/ComfyUI-VideoHelperSuite](https://github.com/Kosinkadink/ComfyUI-VideoHelperSuite), and this fork picks them up on the next sync. Open an issue here only
for something specific to the fork.

## License

Upstream's; see the licence file in this repository.
