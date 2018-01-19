Estimating prothonotary warbler (PROW) annual survival to determine whether hosts of conspecific brood parasitism (CBP) have lower annual survival than non-hosts. 

Tucker, A. M. and Bulluck, L. P. (2017), No evidence for a negative effect of conspecific brood parasitism on annual survival of female Prothonotary Warblers. Ibis. doi:10.1111/ibi.12538

PROW_data.rda contains the following:
- CH: multistate capture histories of individal female PROW for 5 years (1 = non-host, 2 = host, 3 = breeding with unknown CBP status)
- Age: corresponding ages of all females across 5 years
- Nestlings: the total number of nestlings fledged by each female each year

PROW_CBP_JAGS.R contains JAGS model code for the multievent model to estimate state-specific annual survival with uncertain states and R code to generate initial values, run data, and visualize results.