# PLAID dataset

PLAID stands for the Plug Load Appliance Identification Dataset. The data are intended for load identification research. The first version of PLAID is named PLAID1, collected in summer 2013. A second version of PLAID was collected in winter 2014 and released under the name PLAID2.

This dataset comes from PLAID1. It includes current and voltage measurements sampled at 30 kHz from 11 different appliance types present in more than 56 households in Pittsburgh, Pennsylvania, USA. Data collection took place during the summer of 2013. Each appliance type is represented by dozens of different instances of varying makes/models. 

For each appliance, three to six measurements were collected for each state transition. These measurements were then post-processed to extract a few-second-long window containing both the steady-state operation and the startup transient )when available). 

The classes correspond to 11 different appliance types: air conditioner, compact flourescent lamp, fridge, hairdryer, laptop, microwave, washing machine, bulb, vacuum, fan, heater.

Train size: 537

Test size: 537

Missing value: No

Number of classses: 11

Time series length: Vary

We pad NaN to the end of each time series to the length of the longest time series.

Data created by Gao, Jingkun, et al. (see [1], [2], [3]). Data edited by Patrick Schafer and Ulf Leser (see [4]).

[1] Gao, Jingkun, et al. "PLAID: a public dataset of high-resoultion electrical appliance measurements for load identification research: demo abstract." proceedings of the 1st ACM Conference on Embedded Systems for Energy-Efficient Buildings. ACM, 2014.

[2] https://github.com/jingkungao/PLAID

[3] http://www.plaidplug.com/

[4] Schäfer, Patrick, and Ulf Leser. "Fast and accurate time series classification with weasel." Proceedings of the 2017 ACM on Conference on Information and Knowledge Management. ACM, 2017.