# Power Transformers Repository

Welcome to the **Power Transformers Repository**! This repository is dedicated to exploring and understanding two powerful data transformation techniques: **Box-Cox** and **Yeo-Johnson** transformers. These methods are essential for preparing data for machine learning models by making data more Gaussian-like, which can improve the performance of many algorithms.

## Table of Contents

1. [Introduction](#introduction)
2. [Box-Cox Transformation](#box-cox-transformation)
3. [Yeo-Johnson Transformation](#yeo-johnson-transformation)
4. [Hands-On Code Examples](#hands-on-code-examples)
5. [Usage](#usage)
6. [Installation](#installation)
7. [Contributing](#contributing)
8. [License](#license)

## Introduction

Data transformations are crucial in the preprocessing steps of machine learning pipelines. The **Box-Cox** and **Yeo-Johnson** transformations are two widely-used techniques to stabilize variance, make the data more Gaussian-like, and, in some cases, improve the performance of machine learning models. This repository provides a detailed exploration of these methods, along with hands-on code examples.

## Box-Cox Transformation

The **Box-Cox** transformation is used to transform non-normal dependent variables into a normal shape. This can be beneficial for making the data meet the assumptions of parametric statistical tests or improving the performance of machine learning models.

**Key Points:**
- The transformation is defined only for positive data.
- It requires selecting an optimal lambda parameter.

For more detailed information, see the [Box-Cox Transformation section](#box-cox-transformation).

## Yeo-Johnson Transformation

The **Yeo-Johnson** transformation is a modification of the Box-Cox transformation that can handle both positive and negative values, making it more flexible in certain scenarios.

**Key Points:**
- It works with both positive and negative values.
- It also requires an optimal lambda parameter.

For more detailed information, see the [Yeo-Johnson Transformation section](#yeo-johnson-transformation).

## Hands-On Code Examples

This repository includes Jupyter notebooks and Python scripts demonstrating how to apply both Box-Cox and Yeo-Johnson transformations to datasets. The code is designed to be easy to follow and provides practical insights into when and how to use these transformations effectively.


