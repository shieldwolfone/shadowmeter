![ShadowMeter](shadowmeter-dark.png#gh-dark-mode-only)
![ShadowMeter](shadowmeter-light.png#gh-light-mode-only)

What happens when you implement a Network Anomaly Detection System (NADS) with [nDPI](https://www.ntop.org/products/deep-packet-inspection/ndpi/), [Tensorflow](https://www.tensorfloworg/), and [Rust](https://www.rust-lang.org/)?  Well, let's prototype an experiment and find out.
# Motivation
This project is a collaboration with the [nTop](https://ntop.org) team. It is motivated by the following:
* Anomaly detection using unsupervised learning algorithmns is an effective way to detect zero-day attacks, i.e. threat hunt.
* nDPI extracts advanced data features that make it suitable for building deep learning models.
* Rust is a great language and ecosystem for implementing network security software since it is designed for performance, reliability, and safety.

# Tentative schedule

* Phase 1 - implement flow tracking engine with Rust (July 2023)
* Phase 2 - implement and integrate nDPI Rust bindings (August 2023)
* Phase 3 - integrate [TensorFlow](https://github.com/tensorflow/rust) Rust bindings for prediction (September 2023)



###
Brand designed by [Glitschka Studios](https://www.glitschkastudios.com/)