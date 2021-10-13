# Training sets for LearningTCLs
This repo collects the uncertainty samples used in the paper "Chance-constrained regulation capacity offering for HVAC systems under non-Gaussian signals with mixture-model-based convexification"


## File descriptions
Three files contain historical samples for different uncertainties. All the samples are constructed based on the whole-year regD signal data in year 2020 in PJM. The original data can be found in https://www.pjm.com/-/media/markets-ops/ancillary/regulation-signal-posting.ashx


__constructUncertainty.csv:__  
This csv file contains the uncertainty samples of $m_t$, $\overline s_t$ and $\underline s_t$ 

__u_max.csv:__  
Uncertainty samples of $\overline u_{\tau}$

__u_min.csv:__  
Uncertainty samples of $\underline u_{\tau}$