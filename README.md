# Analysis of Acquisitions for Validation

We have an existing validation database for DSWx-HLS: https://podaac.jpl.nasa.gov/dataset/OPERA_DSWX-HLS_CALVAL_PROVISIONAL_V1

The planet scenes were selected to be within 1 day of the HLS scene used to generate the DSWx-HLS product.

In this repo, we find an S1 SLC ID that is within 6 days of the Planet acquisition. Then, we find all the S1 SLCs that cover the relevant MGRS tile and associate all the burst IDs.

The MGRS tiles were found here: https://github.com/NASA-IMPACT/hls-land_tiles

The JPL burst ids were found in the releases here: https://github.com/opera-adt/burst_db/releases/