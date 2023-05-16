# leaflet.chinatmsproviders-correct-offset


## Usage

```bash
npm i leaflet.chinatmsproviders-correct-offset
```

[Leaflet-ChineseTmsProviders](https://github.com/htoooth/Leaflet.ChineseTmsProviders) + [Leaflet.InternetMapCorrection](https://github.com/gisarmory/Leaflet.InternetMapCorrection)
Leaflet.InternetMapCorrection需要加关注才能免费用，请注意！

```Javascript
//add TianDiTu Normal Map Layer to map.
L.tileLayer.chinaProvider('TianDiTu.Normal.Map').addTo(map);
```

## Example

```Javascript
var map = L.map('map', {
    center: [31.59, 120.29],
    zoom: 12
});

L.tileLayer.chinaProvider('TianDiTu.Normal.Map',{maxZoom:18,minZoom:5}).addTo(map);
L.tileLayer.chinaProvider('TianDiTu.Normal.Annotion',{maxZoom:18,minZoom:5}).addTo(map);
## Providers


Current options suitable for tile layers are:
* TianDiTu
    * TianDiTu.Normal.Map
    * TianDiTu.Normal.Annotion
    * TianDiTu.Satellite.Map
    * TianDiTu.Satellite.Annotion
    * TianDiTu.Terrain.Map
    * TianDiTu.Terrain.Annotion
* GaoDe
    * GaoDe.Normal.Map (include Annotion)
    * GaoDe.Satellite.Map
    * GaoDe.Satellite.Annotion
* Google
    * Google.Normal.Map (include Annotion)
    * Google.Satellite.Map (exclude Annotion)
    * Google.Satellite.Map (include Annotion)
    * Google.Roadnet.Map
* Geoq
    * Geoq.Normal.Map
    * Geoq.Normal.PurplishBlue
    * Geoq.Normal.Gray
    * Geoq.Normal.Warm
    * Geoq.Normal.Hydro
* OSM
    * OSM.Normal.Map
* Baidu
    * Baidu.Normal.Map
    * Baidu.Satellite.Map (exclude Annotion)
    * Baidu.Satellite.Annotion
* Tencent
    * Tencent.Normal.Map
    * Tencent.Satellite.Map
    * Tencent.Terrain.Map