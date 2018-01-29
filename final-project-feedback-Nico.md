### ***Final Project Feedback***

***Nico Van de Bovenkamp***

***

**Overall**  
Great work on your data exploration! You wrote a super effective pipeline for processing and cleaning your data. You are ready, and prepped to start fitting some models!

**Recommendations**  

***Transforming Data and Extracting Features***  
After you have cleaned, processed, and plotted your data, you should have some idea of it's shape. Once you can see some of the underlying shape of the data, you may want to start extracting features. Pulling out features can be done in a variety of ways: binning/one-hot-encoding categoricals (site_id), setting flags for data that exceeds certain values (effectively creating some bins for continuous data), log transforms (a few of your features could be good candidates for this, and you caught one of them!), etc.

***Building models***   
Next step: building your set of models. Remember to perform your train/test split, use cross-validation, pick a diverse set of models (potentially using some ensembling technique), perform some grid-searches of hyper-paramters, plot model performance, and then plot your model results (roc curve, auc scores, accuracy, percision/recall, predicted probabilities, feature importance).
