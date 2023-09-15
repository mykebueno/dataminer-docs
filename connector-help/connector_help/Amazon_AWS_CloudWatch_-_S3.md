---
uid: Connector_help_Amazon_AWS_CloudWatch_-_S3
---

# Amazon AWS CloudWatch - S3

CloudWatch can be used to monitor S3. Amazon Simple Storage Service is storage for the internet. It is designed to make web-scale computing easier for developers. Amazon S3 has a simple web services interface that you can use to store and retrieve any amount of data, at any time, from anywhere on the web. It gives any developer access to the same highly scalable, reliable, fast, inexpensive data storage infrastructure that Amazon uses to run its own global network of websites. The service aims to maximize benefits of scale and to pass those benefits on to developers.

## About

### Product Info

| **Range** | **Supported Firmware** |
|-----------|------------------------|
| 1.0.0.x   | 20100801               |

### System Info

| **Range** | **DCF Integration** | **Cassandra Compliant** | **Linked Components** | **Exported Components** |
|-----------|---------------------|-------------------------|-----------------------|-------------------------|
| 1.0.0.x   | No                  | Yes                     | \-                    | \-                      |

## Configuration

### Connections

#### Virtual Connection

This connector uses a virtual connection and does not require any input during element creation.

## How to Use

This connector is automatically generated by the connector Amazon AWS CloudWatch, range 1.0.0.x.

### General

The General page contains the **Entry ID** that is a unique identifier for this service. The **Entry Type** provides more insight in the different parts that the **Entry ID** consists of. The **Polling Interval** can be modified on this page and the **Entry Status** indicates if the service entry is still present. With the **Force Polling** button, you can poll the metrics immediately without having to wait until the interval time has elapsed.

### Metrics

The Metrics pages contain all polled metric values. Polling of the appropriate metric can be enabled via the **Config Poll** page button. It is not possible to set the Poll parameter to *Enabled* for metric parameters that have the *N/A* value. These *N/A* metrics are not present in the provided metrics list for this instance and hence their Poll parameter will remain *Disabled*.