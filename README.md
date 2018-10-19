# keras-focal-loss
Implementation of binary and categorical/multiclass focal loss using Keras with TensorFlow backend. Two parameters are needed when calling the focal loss in model.compile(): alpha and gamma. The focal loss can be used by writing model.compile() as below:

model.compile(optimizer='adam', loss=categorical_focal_loss(gamma=2.0, alpha=0.25), metrics=['accuracy'])
