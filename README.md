# DecAug Synthetic Load Dataset

This repository provides the synthetic load dataset generated using the **DecAug** framework, as described in our paper:

> **"Enhancing Observability for Cold-Start Buildings: A Decomposition-Based Demand Synthesis Approach"**
> \[Under review at IEEE Transactions on Smart Grid]

## 📘 Overview

The **DecAug Dataset** aims to support research in energy consumption forecasting and synthetic data generation. It simulates realistic electricity load profiles based on the learned consumption patterns.

We also plan to release the full source code upon the acceptance of the associated paper.

## 🧩 Dataset Description

to be continued


## 📂 Data Source

The original real-world load data used to train the DecAug model is the **the Building Data Genome Project 2**, which contains electricity consumption data for 19 different locations from around the world. The Genome dataset is publicly available and can be accessed at the following link:

🔗 [https://github.com/buds-lab/building-data-genome-project-2](https://github.com/buds-lab/building-data-genome-project-2)


## 🧪 Generation Method

The data is produced using **decomposition-based** augmentation framework, which first decomposes load time series data into three dominant components: the daily pattern, the seasonal context, and the irregular fluctuation and then separately augments each component through (i) time-series decomposition, (ii) component-specific generation (including pattern mixing, domain translation, and kernel density modeling), and (iii) contrastive-learning-based recombination guided by an evolutionary graph of pattern transitions.

Detailed methodology is available in Section III of our paper.


## 📁 Files

to be continued

## 📊 Format Example

to be continued

## 🛠️ How to Use the Dataset

to be continued


## 📜 License

to be continued


## 📝 Citation

to be continued


## 📬 Contact

to be continued
