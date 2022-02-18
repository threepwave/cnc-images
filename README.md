# cnc-images
Cached Metadata and Images for every Crypts and Caverns dungeon

**Directory Structure**
**Images** - All images are saved in `/img` and named `#.png` where # is the tokenId of that dungeon.

If an image doesn't exist, it is because there is no metadata for that tokenId (e.g. a bugged mint or an unminted id).

**Metadata** - ALl metadata is saved in `/metadata` in the file `dungeons.json`. This is a snapshot as of Friday Feb 18th at 9am PT.

**URL Structure**
Images are accessible via the following URL:
`https://img.cryptsandcaverns.com/img/1.png`

Replace `1` with your tokenId.

Metadata is accessible via the following URL:
`https://img.cryptsandcaverns.com/metadata/dungeons.json`