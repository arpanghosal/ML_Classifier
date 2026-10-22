16.05.2025
--------------


There's a lot in this section. But maybe, everything needs to be modified here and there a bit-> 
WP85 and WP70 reweighting BDT model
This is a bit messed up and I might have to run some stuff again with ph conv type binned. RN the loss curves with 19 vars and ph conv lead binned -> 4th fold didn't work so great. Not sure where the issue is.




















3-class classifier model:
Test with 19 variables as well as 20.

With 20 vars (using 85 data reweighted for 70) and with conversion types UNbinned (results in INT):
Sig vs Total Bkg sep: 11.87%  (binning 0,0.42,0.623,1)
AUC: Recheck

With 20 vars (using 85 data reweighted for 70) and with conversion types binned: 
Sig vs Bkg sep: 11.36% (binning 0,0.4,0.6,1)
AUC: 0.739240



With 19 vars (using 85 data reweighted for 70) and with conversion types binned:
Sig vs Bkg sep: 10.34% (binning 0,0.4,0.6,1)
Loss curve looks better though, more bunched together
AUC: 0.733650



