![ShadowMeter](shadowmeter.png)

What happens when you implement a Network Anomaly Detection System (NADS) using [nDPI](https://www.ntop.org/products/deep-packet-inspection/ndpi/) and [Tensorflow](https://www.tensorflow.org/)?  Well, let's try an experiment and find out.
# Motivation
This project is a collaboration with the [nTop](https://ntop.org) team. It is motivated by the following:
* Anomaly detection using unsupervised learning algorithmns is an effective way to detect zero-day attacks.
* Implementing a network security software with Rust is good practice since it is designed for performance and safety.
* nDPI includes advanced data features that make it ideal for deep learning.

# Tentative schedule

* Phase 1 - implement flow tracking engine with Rust (July 2023)
* Phase 2 - implement and integrate nDPI Rust bindings (August 2023)
* Phase 3 - integrate [TensorFlow](https://github.com/tensorflow/rust) Rust bindings for prediction (September 2023)



###
Brand designed by [Glitschka Studios](https://www.glitschkastudios.com/)