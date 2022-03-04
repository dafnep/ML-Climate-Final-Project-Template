
Week2: investigating how climate simulators work. Try to finalize which models will be used in our project. Investigated CMIP available data and registered to get access. 
Week3: Collect observational time series data. Research on the construction
 Of causal graphs given time-series data. GC, CCM, PCMI, FCI. How to constrain the graph (choose t-1,t,t+1)?Use annually data for one specific month. Visualize data.
Week4: model co2 - temperature as a causal model. Exploration of tigramite.
Week 4: modify objective task. Create matrix with data of earth models. Model true_temp as = w*model_temp. Add related papers. If we is seen as a factor model can we have some proxies Z like in the Abodie paper? (Probably move without proxy predictors with a slight const in convergence time). 
Models that could be used: Linear regression (classic case y~N(wy,v)), GLMs, Neural Network (probably very few data plus not a favorite one).
Week 5: cluster djf temperatures instead of just picking one month. Fetch true temperature data. 