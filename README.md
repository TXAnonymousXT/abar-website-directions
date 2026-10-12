# ABAR Real Estate — website directions

Six working homepage designs for [aba-r.com](https://aba-r.com), plus a cover page that presents them side by side.

**Live:** https://txanonymousxt.github.io/abar-website-directions/ — opens on any phone or laptop.

| File | Direction |
| --- | --- |
| `index.html` | Cover page — start here |
| `1-mashrabiya.html` | Sunlight through a carved lattice screen |
| `2-the-stack.html` | A 3D building that comes apart floor by floor |
| `3-peninsula.html` | Qatar's coastline drawn as ridgelines |
| `4-model-coast.html` | A white scale model of Doha — ABAR's buildings in green |
| `5-pop-up.html` | A pop-up book of Qatar |
| `6-simple.html` | A simple, bright site in ABAR's colours |

## Run it on another device

1. Clone the repository:

   ```bash
   git clone https://github.com/TXAnonymousXT/abar-website-directions.git
   ```

2. Open `index.html` in Chrome, Edge or Safari. That's all — there is nothing to install or build.

If a browser blocks anything when opened straight from the file, serve the folder instead and open <http://localhost:8000>:

```bash
python -m http.server 8000
```

An internet connection is needed: fonts, photographs and (for directions 2, 4 and 5) the 3D library load from public CDNs.

## Notes

- Company details, districts and the vision statement come from aba-r.com. Listings, prices, building counts and the phone number are placeholders.
- Photographs are free-licence images from Unsplash, standing in for ABAR's own.
