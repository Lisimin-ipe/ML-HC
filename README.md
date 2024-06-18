# ML-HC
Currently, the two models with the best prediction performance for fluid constant pressure heat capacity are uploaded. One uses XGBoost as the prediction algorithm, and the other uses DBN as the feature extraction algorithm and DNN as the prediction algorithm, forming the DBN-NN model.

If you need to use these models for prediction, please prepare the following features as input to the models: 'Total S:', 'SMILES', 'Zero point energy (ZPE):', 'Thermal correction to G:', 'Thermal correction to U:', 'Thermal correction to H:', 'Molar Mass', 'Density', 'HOMO', 'LUMO', 'GAP ENERGY', 'LUMO-ENERGY'.

If you have any questions about using the models or about the models themselves, please contact: smli@ipe.ac.cn.
