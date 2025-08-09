# time-series-traffic-flow-prediction
In this study, we propose a new hybrid deep learning framework for short-term traffic flow forecasting that inte
grates physical traffic knowledge into data-driven models. Our approach begins by conducting a detailed empirical
 analysis of station-level traffic patterns and fitting candidate fundamental diagram models (e.g., Greenshields, Green
berg, Triangular) to identify the most representative flow–density relationship. We then incorporate this fundamental
 diagram as a regularization term into the loss function of several hybrid models using a traffic-informed penalty that
 aligns predicted flow values with established traffic dynamics. This integration enforces physically realistic predictions
 while preserving the forecasting power of deep neural networks. Extensive experiments on PeMS data from the I-5
 corridor demonstrate that our FD-informed hybrid models achieve improved robustness and generalization, especially
 under noisy and data-scarce conditions. Our contributions are threefold:
 1) We develop and compare multiple hybrid architectures that integrate convolutional, temporal, and sequential
 learning to capture complex temporal traffic dependencies.
 2) We incorporate traffic flow theory into the learning process by analyzing station-level traffic patterns and em
bedding the most appropriate fundamental diagram into the model’s loss function.
 3) We demonstrate the benefit of combining physics and learning by showing that FD-informed regularization
 improves model robustness in real-world scenarios. Data for this work is available in this link:  https://docs.google.com/spreadsheets/d/1hcZ7Kzjcs9jyRRvNLTPfSrjAai5_UGla/edit?usp=sharing&ouid=114464642486465531722&rtpof=true&sd=true
