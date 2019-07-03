# AnomlyTrigger
Anomly Trigger with AutoEncoder

### Code Structure

Currently I just dump everything into one notebook. To move forward, we likely
need to restructure the code into divisions:

* processing  : File reading interface for Delphes, Level-1 ntuples
* models      : different AE models
* train       : functions for training process, batch?
* notebook    : for notebook collection
* performance : Besides the general ROC and AUC, we likely need code for the trigger rate, efficiency etc.

