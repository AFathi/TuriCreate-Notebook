# Turi Create Notebooks
This repository's main purpose is explaining what [Turi Create](https://github.com/apple/turicreate) is, how to install it, and how to use it. Additionally, I'm providing a few [Jupyter Notebook](http://jupyter.org) examples that demonstrate different uses of the Python package.

Also, in this **README** file, I will explain how to setup `Python`, `pip`, and install the `turicreate` package on your machine.


| Table of Contents  |  Description       |
| ------------------ | ------------------ |
| [What is Turi Create?](#) |  Describes what **Turi Create** is and what developers can use it for.|
| [Requirements](#) | Describes the machine and software requirements to use **Turi Create** and run the **Jupyter Notebook** examples.|
| [Install & Setup](#) | Explains the installation and setup process in details |

## What is Turi Create?
In the [Turi Create](https://github.com/apple/turicreate) official repository, they describe it as a library that:
>simplifies the development of custom machine learning models. You don't have to be a machine learning expert to add recommendations, object detection, image classification, image similarity or activity classification to your app.

From a point of view of an iOS developer with some background in machine learning, I'd describe it as a library that does the complex mathematical computation for you, while you only worry about finding the right dataset for your machine learning model.

Some machine learning models created using **Turi Create** can easily be exported as a [Core ML](https://developer.apple.com/documentation/coreml) model and be implemented into iOS, macOS, tvOS or watchOS applications.

Models that easily allow **Core ML** exporting include:
- Image Classification models
- Object Detection models

**Note**:- Turi Create is open source. Which means we can create an `export_coreml` method for any model we want by editing the source code. I'll demonstrate how to do that in this repository ☺️!

## Why use Turi Create?
In the past few years, the use of machine learning approaches to solve problems and perform complex tasks have been increasing. Machine learning enable us to use big data rather than writing millions of lines of code to perform complex tasks, such as image classification.

Before **Turi Create**, it would be very challenging and time consuming for software developers to create a machine learning model and run it on mobile devices. In order to run a machine learning model on an iPhone or iPad, you would have to optimize your model, which is a very complicated procedure. 

However, thanks to GraphLab and Apple, now we have both **Turi Create** and **CoreML** that enable us to easily create machine learning models for Apple devices. Turi Create provides us with essential machine learning algorithms, such as k-nearest neighbor, to integrate it with other advanced deep learning algorithms, such as Residual Networks (ResNet), in order to create a production-ready machine learning trained model.

In this repository, I will be demonstrating how to create useful machine learning models that may many uses in your existing and future applications!

## Requirements
