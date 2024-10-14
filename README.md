# BIKE-cycles

The .csv files contained here count the number of 4-cycles in the Tanner graphs of BIKE keys.

The three files failures-r557.csv, failures-r587.csv, and failures-r587-t4 used keys from the 2022 paper "A study of error-floor behavior in QC-MDPC codes" by Arpin, Billingsley, Hast, Lau, Perlner, and Robinson ([available here](https://github.com/HastD/BIKE-error-floor/tree/main)) that resulted in decoder failure. 

The three files r557-filtered-keys.csv, r587-filtered-keys.csv, and r587-filtered-keys-t4.csv used randomly generated BIKE keys where Type I, Type II, and Type III weak keys were filtered.

In the files the columns correspond to:
* Number: the index of the key.
* H0 cycles: the number of cycles in H0
* H1 cycles: the number of cycles in H1
* H cycles: the number of cycles between H0 and H1
* Cycles: the total number of cycles
* H0S0, H0S1, and H0S2 (and H0S3 in the t4 files): the number of distances with multiplicity 0, 1, 2, and 3, respectively, in h0
* H1S0, H1S1, and H1S2 (and H1S3 in the t4 files): the number of distances with multiplicity 0, 1, 2, and 3, respectively, in h1
* HS0, HS1, and HS2 (and HS3 in the t4 files): the number of column intersections with size 0, 1, 2, and 3, respectively, between H0 and H1
