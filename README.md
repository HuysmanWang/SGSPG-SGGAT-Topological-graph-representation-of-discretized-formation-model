# TGLABX on discretized formation model of geo-parameters prediction

SGSPG-SGGAT-Topological-graph-representation-of-discretized-formation-model
The soil’s compression modulus (Es) is one of the most critical mechanical parameters for studying land subsidence
in urban strata. Meanwhile, the vertical heterogeneity and lateral discontinuity in the distribution of Es is
one of the leading causes of TBM (tunnel-boring-machine) entrapment in the field. In this study, we first obtain
the minimum redundancy input variables for Es prediction by comparing 20 purely data-driven models. Based on
this, we propose a static directed and weighted graph based on spatial correlation and sequence stratigraphy for
mechanism-driven learning, the spatial-geological stratigraphic graph (SG-SPG), where edges encode essential
spatial-geological information in direction and weights. Then we built a spatial-geological graph attention
network (SGGAT) for node-level estimation and edge-level correction of Es prediction, including two attention
layers to adequately capture the dependencies between spatial location and lithology. The results show that our
method outperforms state-of-the-art models (R2 = 0.99, RMSE = 0.0593 MPa). Furthermore, through network
analysis of SG-SPG, we find that increasing global transitivity significantly improves accuracy, while decreasing
local connectivity and degree centrality of nodes slightly increases the prediction residuals. Our approach provides
interpretability for graph neural network (GNN) and is advantageous for geophysical property prediction
problems with Spatio-temporal heterogeneity

DOI:https://doi.org/10.1016/j.compgeo.2022.105112

figshare 
DOI:10.6084/m9.figshare.c.6285465
DOI:10.6084/m9.figshare.21509670
