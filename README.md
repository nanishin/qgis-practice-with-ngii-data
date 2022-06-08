# qgis-practice-with-ngii-data
QGIS practice with NGII(National Geographic Information Institute) data of South Korea

## Basic setup sequence

1. Install QGIS for OS platform

- https://www.qgis.org/ko/site/forusers/download.html

2. Install QGIS plugin for South Korea (TMS for Korea)

- https://plugins.qgis.org/plugins/tmsforkorea/

3. Download Gyeonggi GIS data in NGII openmarket (Required Sign Up)

- address : http://data.nsdi.go.kr/dataset/12771

- road : http://data.nsdi.go.kr/dataset/12665

- building : http://data.nsdi.go.kr/dataset/12623

- contour line : http://data.nsdi.go.kr/dataset/20180927ds0069

4. Launch QGIS

5. Import Kakao map to layers

- Menu > Web > TMS for Korea > Kakao Maps > Kakao Hybrid

6. Import Gyeonggi address data to layers

- Drag shp file to QGIS (e.g. LSMD_CONT_LDREG_41_202205.shp)

7. Import Gyeonggi road data to layers

- Drag shp file to QGIS (e.g. LSMD_CONT_UQ161_41_202205.shp)

8. Import Gyeonggi building data to layers

- Drag shp file to QGIS (e.g. F_FAC_BUILDING_41_202205.shp)

9. Import Gyeonggi contour line data to layers

- Drag shp file to QGIS (e.g. Z_NGII_N3L_F0010000_A.shp,Z_NGII_N3L_F0010000_B.shp,Z_NGII_N3L_F0010000_D.shp,Z_NGII_N3L_F0010000_E.shp,Z_NGII_N3L_F0010000_F.shp,Z_NGII_N3L_F0010000_G.shp,Z_NGII_N3L_F0010000_I.shp,Z_NGII_N3L_F0010000_J.shp,Z_NGII_N3L_F0010000_K.shp)

## Result comparison with commercial gis service

- NGII place in original kakao map service

![NGII place of kakao map service](/assets/images/kakao_map_ngii_address.png)

- NGII place in QGIS + Gyeonggi data(address) + Kakao map (Hybrid)

![NGII place of QGIS + Gyeonggi data(address) + Kakao map](/assets/images/qgis_ngii_address.png)

- NGII place in QGIS + Gyeonggi data(address,road) + Kakao map (Hybrid)

![NGII place of QGIS + Gyeonggi data(address,road) + Kakao map](/assets/images/qgis_ngii_address_road.png)

- NGII place in QGIS + Gyeonggi data(address,road,building) + Kakao map (Hybrid)

![NGII place of QGIS + Gyeonggi data(address,road,building) + Kakao map](/assets/images/qgis_ngii_address_road_building.png)

- NGII place in QGIS + Gyeonggi data(address,road,building,contour line) + Kakao map (Hybrid)

![NGII place of QGIS + Gyeonggi data(address,road,building,contour line) + Kakao map](/assets/images/qgis_ngii_address_road_building_contour_line.png)
