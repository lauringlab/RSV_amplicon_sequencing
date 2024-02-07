RSV Tiled Amplicon Sequencing 
--

A protocol for RSV-A and RSV-B sequencing that consists of two pools of overlapping amplicons. The amplicons are ~400bp long and are compatible with Illumina and Nanopore sequencing. Its designed to work with current Artic SARS-CoV-2 protocols. 

### RSV-A
- Uses hRSV/A/England/397/2017 as the reference (EPI_ISL_412866 on GISAID and PP109421.1 on Genbank). 
- Consists of 51 primer pairs.
- Amplicon 51 has alternative forward primers, and is not ~400 bp long. The first forward primer creates an amplicon that is ~580 bp long and the second primer creates an amplicon that is ~300 bp in length. This is something to keep in mind if filtering on read length for ONT sequencing. 
![Primer Scheme](RSVA_scheme_plot.png) 
### RSV-B
- Uses hRSV/B/Australia/VIC-RCH056/2019  as the reference (EPI_ISL_1653999 on GISAID and OP975389 on Genbank). 
- consists of 51 primer pairs, with all odd numbered pairs in pool 1 and even numbered primers in pool 2
![Primer Scheme](RSVB_scheme_plot.png) 

Please cite the following paper:

Surie D, Yuengling K, DeCuir J, Zhu Y, Lauring AS, Gaglani M, Ghamande S, Peltan ID, Brown SM, Ginde AA, Martinez A, Mohr NM, Gibbs KW, Hager DN, Ali H, Prekker M, Gong MN, Mohamed A, Johnson NJ, Srinivasan V, Steingrub JS, Leis AM, Khan A, Hough CL, Bender WS, Duggal A, Bendall EE, Wilson JG, Qadir N, Chang SY, Mallow C, Kwon JH, Exline MC, Shapiro NI, Columbus C, Vaughn IA, Ramesh M, Mosier JM, Safdar B, Casey JD, Talbot HK, Rice TW, Halasa N, Chappell JD, Grijalva CG, Baughman A, Womack KN, Swan SA, Johnson C, Lwin CT, Lewis N, Ellington S, McMorrow M, Martin E, Self WH, for the Investigating Respiratory Viruses in the Acutely Ill (IVY) Network. Severity of RSV vs COVID-19 and Influenza among Hospitalized Adults in the United States. JAMA Network Open. 2024; in press.
