# Prospect-Response-Propensity-Model
This work has used XGBoost algorithm. 
I find that XGBoost is quite powerful to deal with all kinds of irregularities of data.
It is easy to build a model using XGBoost but difficult to imporve the model. I have tried heavy duty grid search and ensemble techninques
including bagging and stacking to imporve accuracy score in this analysis. But accuracy score of gradient boosting model could not be imporved inspite of those exercises.
Inspite of this limitation, tree boosting has been proven to give state-of-the-art results on many standard classification models.
Moreover, I find that, XGBoost is easy to scalable in all scenarios. The system runs quite faster than existing popular solutions on a single machine and scales to billions of examples in distributed or memory-limited settings.

Ref:
Chen, T., & Guestrin, C. (2016, August). Xgboost: A scalable tree boosting system. In Proceedings of the 22nd acm sigkdd international conference on knowledge discovery and data mining (pp. 785-794). ACM.
