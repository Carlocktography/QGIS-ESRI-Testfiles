## vectors

### simple_tables_compressed.gdb

Contains a number of simple tables, in a compressed geodatabase format (v10).

Layer | Description
--- | ---
no_geom_no_fields_no_features | Layer with no geometry, no extra fields (only ID field), and no features
no_geom_short_field_1_feature_1_16 | Layer with no geometry, an additional "short" field type, and one feature with ID 1 and field value 16
no_geom_short_field_2_feature_1_16_2_16 | Layer with no geometry, an additional "short" field type, and two features: ID 1, field value 16 and ID 2, field value 16
no_g_short_3_feature_1_16_2_16_3_17 | Layer with no geometry, an additional "short" field type, and three features: ID 1, field value 16, ID 2, field value 16, ID 3, field value 17
no_g_short_3_feature_1_16_2_17_3_16 | Layer with no geometry, an additional "short" field type, and three features: ID 1, field value 16, ID 2, field value 17, ID 3, field value 16
point_0_0 | Layer with point geometry, one feature at (0 0)
point_0_10 | Layer with point geometry, one feature at (0 10)
point_10_0 | Layer with point geometry, one feature at (10 0)
point_10_10 | Layer with point geometry, one feature at (10 10)
points_10_10_0_10 | Layer with point geometry, two features at (10 10), (0 10)
pointzm_10_10_5_7 | Layer with pointzm geometry, one feature at (10 10 5 7)
pointm_10_10_7 | Layer converted from shapefile with M -- GDB conversion has dropped the M value? Original point at (10 10 7)


### spatial_indices.gdb

Contains a number of simple tables containing various spatial index settings (v10).

Layer | Description
--- | ---
proj_0_0_0_actual_966630p74645906_0_0 | Projected CRS, spatial index created with resolutions 0, 0, 0 (resultant index resolution 966630.74645906, 0 0)
proj_no_spatial_index | Projected CRS, no spatial index
proj_1000000_0_0 | Projected CRS, spatial index created at resolutions 1000000, 0, 0
proj_10000_100000_1000000 | Projected CRS, spatial index created at resolutions 10000, 100000, 1000000
proj_10000_100000_0 | Projected CRS, spatial index created at resolutions 10000, 100000, 0
proj_10000_0_0 | Projected CRS, spatial index created at resolutions 10000, 0, 0
geographic_10000_0_0 | Geographic CRS, spatial index created at resolutions 10000, 0, 0
geographic_no_spatial_index | Geographic CRS, no spatial index
geographic_10_100_1000 | Projected CRS, spatial index created at resolutions 10, 100, 1000
geographic_10_0_0 | Projected CRS, spatial index created at resolutions 10, 0, 0
geographic_10_100_0 | Projected CRS, spatial index created at resolutions 10, 100, 0
geographic_0_0_0_actual_9p54313515422996_0_0 | Projected CRS, spatial index created at resolutions 0, 0, 0 (resultant index resolution 9.54313515422996, 0, 0)
unknowncrs_10000_100000_0 | Unknown CRS, spatial index created at resolutions 10000, 100000, 0
unknowncrs_0_0_0_actual_966630p74645906_0_0 | Unknown CRS, spatial index created at resolutions 0, 0, 0 (resultant index resolution 966630.74645906, 0, 0)
unknowncrs_10000_0_0 | Unknown CRS, spatial index created at resolutions 10000, 0, 0
unknowncrs_no_spatial_index | Unknown CRS, no spatial index
unknowncrs_10000_100000_1000000 | Unknown CRS, spatial index created at resolutions 10000, 100000, 1000000
unknowncrs_1000000_0_0 | Unknown CRS, spatial index created at resolutions 1000000, 0, 0


### domain.gdb

Contains a table with a domain field


### relations.gdb

Contains some tables with relationships.

Layer | Description
--- | ---
parent | Parent table, related to child1 and child2
child1 | Child table 1
child2 | Child table 2

### compressed_relations.gdb

Same as relations.gdb, but compressed (v10)

### compressed_lossy.gdb

Same as relations.gdb, but compressed using lossy compression (v10)

