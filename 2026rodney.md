Distributed Sparse Linear Regression under Communication Constraints



Rodney Fonseca (UFBA)



Abstract: In multiple domains, statistical tasks are performed in distributed settings, with data split among several end machines that are connected to a fusion center. In various applications, the end machines have limited bandwidth and power, and thus a tight communication budget. In this work we focus on distributed learning of a sparse linear regression model, under severe communication constraints. We propose several two round distributed schemes, whose communication per machine is sublinear in the data dimension. In our schemes, individual machines compute debiased lasso estimators, but send to the fusion center only very few values. On the theoretical front, we analyze one of these schemes and prove that with high probability it achieves exact support recovery at low signal to noise ratios, where individual machines fail to recover the support. We show in simulations that our scheme works as well as, and in some cases better, than more communication intensive approaches.

