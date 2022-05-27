# qgis-practice-with-ngii-data
QGIS practice with NGII(National Geographic Information Institute) data of South Korea

## Basic setup sequence

1. Install QGIS for OS platform

- https://www.qgis.org/ko/site/forusers/download.html

2. Install QGIS plugin for South Korea (TMS for Korea)

- https://plugins.qgis.org/plugins/tmsforkorea/

3. Download Gyeonggi map data in NGII openmarket (Required Sign Up) 

- http://data.nsdi.go.kr/dataset/12771

4. Launch QGIS

5. Import Kakao map to layers

- Menu > Web > TMS for Korea > Kakao Maps > Kakao Hybrid

6. Import Gyeonggi map data to layers 

- Drag shp file to QGIS (e.g. LSMD_CONT_LDREG_41_202205.shp)

## Result comparison with commercial gis service

- NGII address in original kakao map service

![NGII address of kakao map service](/assets/images/kakao_map_ngii_address.png)

- NGII address in QGIS + NGII Gyeonggi data + Kakao map (Hybrid)

![NGII address of QGIS + Gyeonggi data + Kakao map](/assets/images/qgis_ngii_address.png)

