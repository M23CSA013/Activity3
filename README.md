**Activity 3:**

Model: Trained CNN on USPS Dataset
Specifications: Batch_size = 64, CNN layers = 2, Optimizer = Adam

Branches:

i) version 1.0: 
Changed configurations to  Batch_size = 32, CNN layers = 3, Optimizer = Adagrad

ii) version 2.0: 
Changed configurations to  Batch_size = 16, CNN layers = 4, Optimizer = RMSProp

**Activity 4:**

Rollback (branch = activity_rollback): Checked git log and rolled back to the stable version of Batch_size = 64, CNN layers = 2, Optimizer = Adam

Rollforward (branch = activity_rf): Checked git log, rolled back to version 2.0. Made necessary changes to the model code and configurations to fix the regression.


