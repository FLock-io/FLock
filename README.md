# FLock: World's 1st On-Chain Private Neural Processor

<p align="center">
  <a href="https://flock.io/">
    <img src="https://user-images.githubusercontent.com/5778228/202293780-0daf6544-8112-49bd-bc4d-3f95690c3707.png" width="140px" alt="FLock Website" />
  </a>
</p>

<p align="center">
FLock = Federated Learning + Blockchain
</p>

[![GitHub license](https://img.shields.io/github/license/FLock-io/FLock)](https://github.com/FLock-io/FLock/blob/main/LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/FLock-io/FLock/blob/main/CONTRIBUTING.md)
[![Telegram](https://img.shields.io/badge/Chat-Telegram-blue)](https://t.me/flock_io_community)
[![Discord](https://img.shields.io/badge/Channel-Discord-green)](https://discord.gg/ay8MnJCg2W)
[![Linkedin](https://img.shields.io/badge/Profile-Linkedin-blue)](https://www.linkedin.com/company/flock-io/)
[![BLog](https://img.shields.io/badge/News-Blog-yellowgreen)](https://flock-io.notion.site/Blog-96d7e2251c5b4655980993e5df902513)
[![Email](https://img.shields.io/badge/Say%20Hi-Email-orange)](mailto:hello@flock.io)
[![Twitter](https://img.shields.io/twitter/follow/flock_io?style=social)](https://twitter.com/flock_io)

### Introduction

FLock is an open-source framework for building Fedrated Learning systems natively on Blockchain. The combination of Fedrated Learning and Blockchain solves real-life blockers for each other:

+ **For Federated Learning** : lack of participation incentives and risk of malicious clients can be solved by Blockchain technologies
 
+ **For Blockchain** : Highly consumed and wasted Proof of Work computation powers can be replaced by computations of Fedrated Learning models, aka, Proof of Machine Learning (PoML).

### Principles
 
This project is built by a group of Oxford Alumni with strong industry and academic backgrounds in both Artificial Intelligence and Blockchain, which ensures the guidance of this project covers all different roles of participants in FLock:

+ **For Developers** : 
  + Build to earn
  + "Own your data" vision

+ **For Service Providers** :
  + Save bandwidth
  + Maintain model performance
  + Provably secure

+ **For End Users** :
  + Passive income (run FLock to earn)
  + Preserves privacy

### Robustness

Our proposed v1 design is robust against attacks

| Attack Method  | Description | Countermeasures |
| ------------- | ------------- | ------ |
| Re-identification attack  | Deriving encrypted identity information based on non-identity information in the data | No inter-node dataset transmission in FLock |
| Tracing attack  | Deriving a person's presence without knowing their actual identification | No inter-node dataset transmission in FLock |
| Dataset reconstruction attack | Deriving a person’s attributes from a dataset without accessing the data | FLock processed gradients lacks enough information to support such attacks |
| Model-inversion attack | Observe model output under varied input circumstances to learn about unauthorized training data | FLock's gradient post-process make this attack computationally in tensive |

### Publications

Dong, N., Sun, J., Wang, Z., Zhang, S., & Zheng, S. (2022). *FLock: Defending Malicious Behaviors in Federated Learning with Blockchain.* doi:10.48550/ARXIV.2211.04344 

**More papers to come**

### Developments

We are currently undertaking most of developments in private mode, will add them here once they are released and made public:

+ FLock System Design paper: Check out [this repo](https://github.com/FLock-io/FLock_system_design_paper) for details

+ FLock Healthcare App: Check out [this repo]() for details

+ FLock Finance App: Check out [this repo]() for details

+ FLock Model Distribution Serice: Check out [this repo]() for details

### Communications

Please star this project if you are interested, future communications and code/paper publications will be posted here.

We also welcome the community to join us in all possible ways!
