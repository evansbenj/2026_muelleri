# Muelleri RNAseq

I did this in two batches because the first batch was highly sex-skewed based on PCRs that Sam did.

I have data in these directories:
```
/home/ben/projects/rrg-ben/ben/2024_allo_muel_RNAseq/fq/muel_fq
/home/ben/projects/rrg-ben/ben/2024_allo_muel_RNAseq/fq_muel_RNAseq_round2_2026
```

I intersected kmers from each tad with the fem-specific kmers based on WGS. 

Based on kmers, these are the females for round1:
```
-rw-r----- 1 ben rrg-ben 5804 Sep 23 08:42 in_allfemz_intersect_sum.meryl_but_not_allmalez_unionsum.meryl.meryl_X_muelleri_tad32_trim.R12_meryldb.out_intersect.meryl_counts.txt
-rw-r----- 1 ben rrg-ben 3264 Sep 23 08:42 in_allfemz_intersect_sum.meryl_but_not_allmalez_unionsum.meryl.meryl_X_muelleri_tad34_trim.R12_meryldb.out_intersect.meryl_counts.txt
-rw-r----- 1 ben rrg-ben 3162 Sep 23 08:42 in_allfemz_intersect_sum.meryl_but_not_allmalez_unionsum.meryl.meryl_X_muelleri_tad35_trim.R12_meryldb.out_intersect.meryl_counts.txt
-rw-r----- 1 ben rrg-ben 8677 Sep 23 08:42 in_allfemz_intersect_sum.meryl_but_not_allmalez_unionsum.meryl.meryl_X_muelleri_tad36_trim.R12_meryldb.out_intersect.meryl_counts.txt
-rw-r----- 1 ben rrg-ben 1258 Sep 23 08:42 in_allfemz_intersect_sum.meryl_but_not_allmalez_unionsum.meryl.meryl_X_muelleri_tad37_trim.R12_meryldb.out_intersect.meryl_counts.txt
-rw-r----- 1 ben rrg-ben 5124 Sep 23 08:42 in_allfemz_intersect_sum.meryl_but_not_allmalez_unionsum.meryl.meryl_X_muelleri_tad42_trim.R12_meryldb.out_intersect.meryl_counts.txt
```
and these are the males:
```
-rw-r----- 1 ben rrg-ben    0 Sep 23 08:42 in_allfemz_intersect_sum.meryl_but_not_allmalez_unionsum.meryl.meryl_X_muelleri_tad31_trim.R12_meryldb.out_intersect.meryl_counts.txt
-rw-r----- 1 ben rrg-ben  204 Sep 23 08:42 in_allfemz_intersect_sum.meryl_but_not_allmalez_unionsum.meryl.meryl_X_muelleri_tad33_trim.R12_meryldb.out_intersect.meryl_counts.txt
-rw-r----- 1 ben rrg-ben    0 Sep 23 08:42 in_allfemz_intersect_sum.meryl_but_not_allmalez_unionsum.meryl.meryl_X_muelleri_tad38_trim.R12_meryldb.out_intersect.meryl_counts.txt
-rw-r----- 1 ben rrg-ben    0 Sep 23 08:42 in_allfemz_intersect_sum.meryl_but_not_allmalez_unionsum.meryl.meryl_X_muelleri_tad39_trim.R12_meryldb.out_intersect.meryl_counts.txt
```


For round two the sex is more obvious:
females:
```
-rw-r----- 1 ben rrg-ben  9584 Sep 23 08:43 in_allfemz_intersect_sum.meryl_but_not_allmalez_unionsum.meryl.meryl_X_muelleri_tad36_2_trim.R12_meryldb.out_intersect.meryl_counts.txt
-rw-r----- 1 ben rrg-ben 13416 Sep 23 08:43 in_allfemz_intersect_sum.meryl_but_not_allmalez_unionsum.meryl.meryl_X_muelleri_tad41_2_trim.R12_meryldb.out_intersect.meryl_counts.txt
-rw-r----- 1 ben rrg-ben  5780 Sep 23 08:43 in_allfemz_intersect_sum.meryl_but_not_allmalez_unionsum.meryl.meryl_X_muelleri_tad42_2_trim.R12_meryldb.out_intersect.meryl_counts.txt
```
males:
```
-rw-r----- 1 ben rrg-ben     0 Sep 23 08:43 in_allfemz_intersect_sum.meryl_but_not_allmalez_unionsum.meryl.meryl_X_muelleri_tad32_2_trim.R12_meryldb.out_intersect.meryl_counts.txt
-rw-r----- 1 ben rrg-ben     0 Sep 23 08:43 in_allfemz_intersect_sum.meryl_but_not_allmalez_unionsum.meryl.meryl_X_muelleri_tad33_2_trim.R12_meryldb.out_intersect.meryl_counts.txt
-rw-r----- 1 ben rrg-ben     0 Sep 23 08:43 in_allfemz_intersect_sum.meryl_but_not_allmalez_unionsum.meryl.meryl_X_muelleri_tad35_2_trim.R12_meryldb.out_intersect.meryl_counts.txt
-rw-r----- 1 ben rrg-ben     0 Sep 23 08:43 in_allfemz_intersect_sum.meryl_but_not_allmalez_unionsum.meryl.meryl_X_muelleri_tad37_2_trim.R12_meryldb.out_intersect.meryl_counts.txt
-rw-r----- 1 ben rrg-ben     0 Sep 23 08:43 in_allfemz_intersect_sum.meryl_but_not_allmalez_unionsum.meryl.meryl_X_muelleri_tad39_2_trim.R12_meryldb.out_intersect.meryl_counts.txt
-rw-r----- 1 ben rrg-ben     0 Sep 23 08:43 in_allfemz_intersect_sum.meryl_but_not_allmalez_unionsum.meryl.meryl_X_muelleri_tad40_2_trim.R12_meryldb.out_intersect.meryl_counts.txt
-rw-r----- 1 ben rrg-ben    34 Sep 23 08:44 in_allfemz_intersect_sum.meryl_but_not_allmalez_unionsum.meryl.meryl_X_muelleri_tad43_2_trim.R12_meryldb.out_intersect.meryl_counts.txt
```

Checking with the sexes that Sam got from PCR:

batch1:
```
tad31,F
tad32,F
tad33,M
tad34,F
tad35,F
tad36,F
tad37,F
tad38,M
tad39,M
tad42,F
```
There is a discrepancy: kmers say tad31 is a male but PCR says it is a female

batch2 is completely consistent with Sam's PCR results:
```
30.2	F
31.2	F
34.2	F
32.2	M
33.2	M
35.2	M
37.2	M
39.2	M
40.2	M
43.2	M
```

# fischbergi:
```
/home/ben/projects/rrg-ben/ben/2026_fischbergi_RNAseq/fq/trimmed
```
Based on the file size, these are possible females:
```
-rw-r----- 1 ben rrg-ben 2.4K Sep 23 08:41 in_allfemz_intersect_sum.meryl_but_not_allmalez_unionsum.meryl.meryl_X_fischbergi_tad10_S171_L008_R_trim.R12_meryldb.out_intersect.meryl_counts.txt
-rw-r----- 1 ben rrg-ben 2.2K Sep 23 08:41 in_allfemz_intersect_sum.meryl_but_not_allmalez_unionsum.meryl.meryl_X_fischbergi_tad11_S172_L008_R_trim.R12_meryldb.out_intersect.meryl_counts.txt
-rw-r----- 1 ben rrg-ben 3.0K Sep 23 08:41 in_allfemz_intersect_sum.meryl_but_not_allmalez_unionsum.meryl.meryl_X_fischbergi_tad18_S179_L008_R_trim.R12_meryldb.out_intersect.meryl_counts.txt
-rw-r----- 1 ben rrg-ben 4.3K Sep 23 08:41 in_allfemz_intersect_sum.meryl_but_not_allmalez_unionsum.meryl.meryl_X_fischbergi_tad19_S180_L008_R_trim.R12_meryldb.out_intersect.meryl_counts.txt
-rw-r----- 1 ben rrg-ben  11K Sep 23 08:41 in_allfemz_intersect_sum.meryl_but_not_allmalez_unionsum.meryl.meryl_X_fischbergi_tad1_S164_L008_R_trim.R12_meryldb.out_intersect.meryl_counts.txt
-rw-r----- 1 ben rrg-ben 3.6K Sep 23 08:41 in_allfemz_intersect_sum.meryl_but_not_allmalez_unionsum.meryl.meryl_X_fischbergi_tad2_S165_L008_R_trim.R12_meryldb.out_intersect.meryl_counts.txt
-rw-r----- 1 ben rrg-ben 4.0K Sep 23 08:41 in_allfemz_intersect_sum.meryl_but_not_allmalez_unionsum.meryl.meryl_X_fischbergi_tad6_S169_L008_R_trim.R12_meryldb.out_intersect.meryl_counts.txt
-rw-r----- 1 ben rrg-ben 2.8K Sep 23 08:41 in_allfemz_intersect_sum.meryl_but_not_allmalez_unionsum.meryl.meryl_X_fischbergi_tad9_S170_L008_R_trim.R12_meryldb.out_intersect.meryl_counts.txt

```
and these are possible males:
```
-rw-r----- 1 ben rrg-ben  509 Sep 23 08:41 in_allfemz_intersect_sum.meryl_but_not_allmalez_unionsum.meryl.meryl_X_fischbergi_tad12_S173_L008_R_trim.R12_meryldb.out_intersect.meryl_counts.txt
-rw-r----- 1 ben rrg-ben  407 Sep 23 08:41 in_allfemz_intersect_sum.meryl_but_not_allmalez_unionsum.meryl.meryl_X_fischbergi_tad20_S181_L008_R_trim.R12_meryldb.out_intersect.meryl_counts.txt
```

These are intermediate:
```
-rw-r----- 1 ben rrg-ben 1.5K Sep 23 08:41 in_allfemz_intersect_sum.meryl_but_not_allmalez_unionsum.meryl.meryl_X_fischbergi_tad3_S166_L008_R_trim.R12_meryldb.out_intersect.meryl_counts.txt
-rw-r----- 1 ben rrg-ben 1.5K Sep 23 08:41 in_allfemz_intersect_sum.meryl_but_not_allmalez_unionsum.meryl.meryl_X_fischbergi_tad4_S167_L008_R_trim.R12_meryldb.out_intersect.meryl_counts.txt
-rw-r----- 1 ben rrg-ben 1.8K Sep 23 08:41 in_allfemz_intersect_sum.meryl_but_not_allmalez_unionsum.meryl.meryl_X_fischbergi_tad5_S168_L008_R_trim.R12_meryldb.out_intersect.meryl_counts.txt
-rw-r----- 1 ben rrg-ben 1.1K Sep 23 08:41 in_allfemz_intersect_sum.meryl_but_not_allmalez_unionsum.meryl.meryl_X_fischbergi_tad17_S178_L008_R_trim.R12_meryldb.out_intersect.meryl_counts.txt
```

