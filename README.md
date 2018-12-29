# early-stopping-pytorch
Early stopping is a form of regularization used to avoid overfitting on the training dataset. A simple implementation of early stopping keeps track of the validation loss, if the loss stops decreasing for several epochs in a row the training stops. The EarlyStopping class in ```pytorchtool.py``` is inspired by the [ignite EarlyStopping class](https://github.com/pytorch/ignite/blob/master/ignite/handlers/early_stopping.py).
