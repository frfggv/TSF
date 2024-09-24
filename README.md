# TSF
Previous decomposition-based models have not focused on the interaction between trends and seasonal intervals in time series prediction. Considering the complex correlation between the patterns of sequences and different time scales, we propose a multi-branch framework based on Multi-scale Pattern Mixture Decomposition Block to mine complex patterns in time series. The contributions and innovations of this article are summarized as follows:

    1. To achieve mixed modeling of trends and seasons, we propose a multi-scale trend-season mixing layer using an Encoder-Decoder structure based on Gated Recurrent Units. This design effectively captures multi-scale correlations between trends and seasons, leading to accurate predictions.
    
    2. To enable adaptive fusion of multi-scale prediction results, we propose a time-aware adaptive fusion module that leverages forecasting horizon timestamps and convolutional blocks to capture temporal variation patterns across different scales.
    
    3. Our proposed new network, MTSMNet, has demonstrated excellent performance in the LTSF field. In addition, a series of experiments on public datasets have demonstrated that our model can capture long-term temporal dependencies and robustness.
    
The code will be made public after the paper is received.
