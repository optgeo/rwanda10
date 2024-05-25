# rwanda10
Terrain tiles from `Dem_Rwanda_10m_allt_20230921150153_band1.tif`

# Demo
- Observable https://observablehq.com/d/a693048dbb42976a

# Repositories
- Source Cooperative: https://beta.source.coop/repositories/smartmaps/rwanda10/
- GitHub: https://github.com/optgeo/rwanda10/

# Attribution
Water and Sanitation Corporation (WASAC), National Land Authority (NLA)

# How the tiles are created
```
rasterio rgbify --max-z 14 --min-z 2 --format webp -i 0.1 -b -10000 --verbose /data/Dem_Rwanda_10m_allt_20230921150153_band1.tif /data/rwanda10.mbtiles
```

# See also
## Source data
- https://geohub.data.undp.org/data/00d5add9be37e465398b081683c3ec03#Info

## Tools
- https://github.com/unvt/rgbify

