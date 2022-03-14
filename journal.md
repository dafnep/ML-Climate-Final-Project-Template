
Week2: investigating how climate simulators work. Try to finalize which models will be used in our project. Investigated CMIP available data and registered to get access. 
Week3: Collect observational time series data. Research on the construction
 Of causal graphs given time-series data. GC, CCM, PCMI, FCI. How to constrain the graph (choose t-1,t,t+1)?Use annually data for one specific month. Visualize data.
Week4: model co2 - temperature as a causal model. Exploration of tigramite.
Week 4: modify objective task. Create matrix with data of earth models. Model true_temp as = w*model_temp. Add related papers. If we is seen as a factor model can we have some proxies Z like in the Abodie paper? (Probably move without proxy predictors with a slight const in convergence time). 
Models that could be used: Linear regression (classic case y~N(wy,v)), GLMs, Neural Network (probably very few data plus not a favorite one).
Week 5: cluster djf temperatures instead of just picking one month. Fetch true temperature data.
Week 6: having some problems with real temperature datasets... they all represent temperature anomalies instead of absolute data.. First synthetic control objective function minimization code. 
Week 7: Created two synthetic control calculation processes. For the first one matrix V is set with equal values for all donors (the importance of each past approximation of Y is equal). For the second one matrix V is calculated through cross validation. Also tested for grouped 5-year time series data. 