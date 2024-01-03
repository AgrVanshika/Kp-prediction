KpNet_model.py changed in line 187 to be compatible with tensorflow 2.8:

self.model.compile(optimizer=tf.keras.optimizers.Adam(learning_rate=adam_lr),loss=loss, metrics=metrics)


Requirements:

tensorflow 2.8.0
tensorflow-probability 0.14.0
numpy 1.22.4
pandas 1.4.1
keras 2.8.0
scikit-learn 1.0.1
matplotlib 3.5.1
matplotlib_inline 0.1.3
seaborn 0.13.0
scipy 1.11.2
joblib 1.3.2
