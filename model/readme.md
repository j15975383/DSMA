Here we exported a bert model using the Savedmodle function
access the model via
```
new_model = tf.keras.models.load_model('saved_model/my_model')
new_model.summary() 
```
