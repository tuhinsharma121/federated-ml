# federated-ml

## Description

A modern smart building has a number of internet-enabled devices. IoT sensors to measure temperature, internet-enabled lighting, IP camera, IP phone, etc., and data is generated at scale across all the devices. There are two critical aspects of the network of devices to function well: data quality (the generated data has to be correct within an accepted error range) and security (with a number of internet-connected devices, securing the network from cyber threats is very important). But there are two broad challenges to achieve this: the data collected is very sensitive to business operations and hence the solution has to be privacy preserving, and the amount of data generated is huge and is not feasible to upload all of them to the cloud.

Tuhin Sharma and Bargava Subramanian explain how they used federated learning to build anomaly-detection models that monitor data quality and cybersecurity while preserving data privacy. Federated learning enables edge devices to collaboratively learn a machine learning model but keep all of the data on the device itself. Instead of moving data to the cloud, the models are trained on the device and only the updates of the model are shared across the network. Using federated learning gives you the following advantages: more accurate and low latency models where the data is not moved and only the model updates are shared, resulting in models having low latency (since the models are on the device) and being more accurate; privacy preserving because the data remains on the device; and energy efficient, because the workload on the device is drastically reduced—leading to lower power consumption and longer device life.

Tuhin and Bargava built deep learning models using Pytorch and Pysyft. They outline their architecture and show you how federated learning can help improve the models. Federated learning provides a framework to port models across organizations for the same domain of the device, something not possible in traditional cloud-based anomaly detection models, which makes it easy to deploy with very limited data.

Join in to hear some of Tuhin and Bargava’s success stories.

## Prerequisite knowledge

- A basic understanding of machine learning

## What you'll learn

- Learn what federated learning is and how to build and deploy such models.
