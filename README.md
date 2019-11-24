# Phase-1_Week2_MNIST
Week2 Assignment

For 17th epoch, the accuracy is 99.45%. This is the highest accuracy I'm getting.

1. Log file for 20 epochs:


Train on 60000 samples, validate on 10000 samples
Epoch 1/20

Epoch 00001: LearningRateScheduler setting learning rate to 0.003.
60000/60000 [==============================] - 20s 328us/step - loss: 0.4301 - acc: 0.8974 - val_loss: 0.2563 - val_acc: 0.9423
Epoch 2/20

Epoch 00002: LearningRateScheduler setting learning rate to 0.0022744503.
60000/60000 [==============================] - 13s 212us/step - loss: 0.1801 - acc: 0.9513 - val_loss: 0.0905 - val_acc: 0.9791
Epoch 3/20

Epoch 00003: LearningRateScheduler setting learning rate to 0.0018315018.
60000/60000 [==============================] - 12s 206us/step - loss: 0.1410 - acc: 0.9622 - val_loss: 0.0481 - val_acc: 0.9897
Epoch 4/20

Epoch 00004: LearningRateScheduler setting learning rate to 0.0015329586.
60000/60000 [==============================] - 12s 205us/step - loss: 0.1196 - acc: 0.9698 - val_loss: 0.0408 - val_acc: 0.9905
Epoch 5/20

Epoch 00005: LearningRateScheduler setting learning rate to 0.0013181019.
60000/60000 [==============================] - 12s 203us/step - loss: 0.1031 - acc: 0.9741 - val_loss: 0.0332 - val_acc: 0.9917
Epoch 6/20

Epoch 00006: LearningRateScheduler setting learning rate to 0.0011560694.
60000/60000 [==============================] - 12s 200us/step - loss: 0.0909 - acc: 0.9773 - val_loss: 0.0484 - val_acc: 0.9867
Epoch 7/20

Epoch 00007: LearningRateScheduler setting learning rate to 0.0010295127.
60000/60000 [==============================] - 12s 202us/step - loss: 0.0852 - acc: 0.9770 - val_loss: 0.0338 - val_acc: 0.9909
Epoch 8/20

Epoch 00008: LearningRateScheduler setting learning rate to 0.0009279307.
60000/60000 [==============================] - 12s 201us/step - loss: 0.0770 - acc: 0.9792 - val_loss: 0.0321 - val_acc: 0.9913
Epoch 9/20

Epoch 00009: LearningRateScheduler setting learning rate to 0.0008445946.
60000/60000 [==============================] - 12s 200us/step - loss: 0.0723 - acc: 0.9801 - val_loss: 0.0269 - val_acc: 0.9925
Epoch 10/20

Epoch 00010: LearningRateScheduler setting learning rate to 0.0007749935.
60000/60000 [==============================] - 12s 197us/step - loss: 0.0678 - acc: 0.9802 - val_loss: 0.0290 - val_acc: 0.9924
Epoch 11/20

Epoch 00011: LearningRateScheduler setting learning rate to 0.0007159905.
60000/60000 [==============================] - 12s 198us/step - loss: 0.0651 - acc: 0.9809 - val_loss: 0.0266 - val_acc: 0.9929
Epoch 12/20

Epoch 00012: LearningRateScheduler setting learning rate to 0.000665336.
60000/60000 [==============================] - 12s 198us/step - loss: 0.0599 - acc: 0.9823 - val_loss: 0.0236 - val_acc: 0.9940
Epoch 13/20

Epoch 00013: LearningRateScheduler setting learning rate to 0.0006213753.
60000/60000 [==============================] - 12s 198us/step - loss: 0.0591 - acc: 0.9822 - val_loss: 0.0226 - val_acc: 0.9942
Epoch 14/20

Epoch 00014: LearningRateScheduler setting learning rate to 0.0005828638.
60000/60000 [==============================] - 12s 198us/step - loss: 0.0541 - acc: 0.9831 - val_loss: 0.0208 - val_acc: 0.9944
Epoch 15/20

Epoch 00015: LearningRateScheduler setting learning rate to 0.0005488474.
60000/60000 [==============================] - 12s 197us/step - loss: 0.0536 - acc: 0.9825 - val_loss: 0.0238 - val_acc: 0.9934
Epoch 16/20

Epoch 00016: LearningRateScheduler setting learning rate to 0.0005185825.
60000/60000 [==============================] - 12s 198us/step - loss: 0.0541 - acc: 0.9831 - val_loss: 0.0227 - val_acc: 0.9935
Epoch 17/20

Epoch 00017: LearningRateScheduler setting learning rate to 0.000491481.
60000/60000 [==============================] - 12s 204us/step - loss: 0.0507 - acc: 0.9837 - val_loss: 0.0202 - val_acc: 0.9945
Epoch 18/20

Epoch 00018: LearningRateScheduler setting learning rate to 0.0004670715.
60000/60000 [==============================] - 12s 199us/step - loss: 0.0496 - acc: 0.9836 - val_loss: 0.0209 - val_acc: 0.9942
Epoch 19/20

Epoch 00019: LearningRateScheduler setting learning rate to 0.0004449718.
60000/60000 [==============================] - 12s 198us/step - loss: 0.0465 - acc: 0.9847 - val_loss: 0.0216 - val_acc: 0.9937
Epoch 20/20

Epoch 00020: LearningRateScheduler setting learning rate to 0.000424869.
60000/60000 [==============================] - 12s 197us/step - loss: 0.0481 - acc: 0.9834 - val_loss: 0.0199 - val_acc: 0.9935

<keras.callbacks.History at 0x7fd896824320>





2. score = model.evaluate(X_test, Y_test, verbose=0)
   print(score)
   
   [0.01985513117592782, 0.9935]


3. Strategy choosen to attain the above result:

   i)  changed dropout to 0.05
   ii) changed number of channels
