# Web-GIS Frontend Challenge

We would like you to demonstrate your Web-GIS Frontend development skills. Using WebGL-powered libraries, create a web map to be integrated into our web application, which is built with React + typescript + NextJS. The map component should be somewhat similar to this [POC](https://clausa.app.carto.com/map/12a2ca02-8184-4515-b6f7-09c7fec36007). 

You will be asked to demo it running in your local or you are also welcome to deploy it in a free server of your choice and share a link to it so we can see your work. We also want to see the code pushed to a new branch in this repo. 

Here is all the data you will need:
1. H3 Tilesets hosted in BigQuery. Use the service account (provided via e-mail) to access these Tilesets.
- `na-core-dev:test_layers.L4_1_species_rarity_weighted_richness_tileset_copy`
- `na-core-dev:test_layers.L4_2_biodiversity_intactness_tileset_copy`

2. Point locations (i.e., asset locations) should be created from the [locations_data.csv](https://github.com/rafael-na/web-gis-h3/blob/main/locations_data.csv), which in the case of our web app such data is in a postgres db.

![webmap_h3_poc](https://github.com/user-attachments/assets/5f5e658d-1530-48d0-ad59-a5ed9aeb77ce)
