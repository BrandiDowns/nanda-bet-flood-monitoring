![nanda bet region](https://github.com/BrandiDowns/nanda-bet-flood-monitoring/blob/main/pics/gujarat_s2_cloudless_2021_small.png "Study Extent in India")


# Flood Monitoring in Nanda Bet

A series of Python scripts and Jupyter notebooks to monitor flooding using Sentinel-1 and CYGNSS in the Little Rann of Kachchh (LRK), Gujarat, India, centered on the small island of Nanda Bet. 


## About the Nanda Bet Flood Monitoring Project
Nanda Bet is one of 74 islands in the saline mudflats of LRK. During monsoon season, the region fills with water and becomes a wetland. Thus the LRK has the unique propoerty of being both a saline desert and a wetland ecosystem, depending on the time of year. Out of the four largest bets, or islands, in the LRK, Nanda Bet has the highest faunal species diversity and the highest habitat diversity [[1]](#1).

These scripts use Sentinel-1 and CYGNSS to observe changes in surface water extent in and around Nanda Bet, but can be adapted for any region by modifying the region of interest (roi) parameters, date ranges, and optimizing thresholds for local soil types, vegetation, etc.

![sentinel-1 gif](https://github.com/BrandiDowns/nanda-bet-flood-monitoring/blob/main/pics/s1_vv_20200101_20201231_annotated.gif "Sentinel-1 VV over Nanda Bet")



<img src="https://github.com/BrandiDowns/nanda-bet-flood-monitoring/blob/main/pics/gpm_mean_monthly_total_accum_precip_2020.png" width="750">

## Installation


## Dependencies
* [earthengine-api](https://github.com/google/earthengine-api)
* [geemap](https://github.com/giswqs/geemap)


## References
<a id="1">[1]</a> 
J.D. Joshi, K. Tatu, D. Joshi, R.D. Kamboj, 
"Comparative account of faunal diversity of four major islands (bets) in Little Rann of Kachchh (LRK), Gujarat, India,"
*International Research Journal of Biological Sciences,*
vol. 7, no. 6, pp. 9-19, Jun. 2018.
