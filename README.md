<img src="images/cover.png" alt="redhand">

[![release](https://img.shields.io/github/release/c4m3l-security/redhand?label=version&color=brightgreen)](https://github.com/c4m3l-security/redhand/releases)
[![license](https://img.shields.io/github/license/c4m3l-security/redhand)](https://github.com/c4m3l-security/redhand/blob/main/LICENSE)
[![issues](https://img.shields.io/github/issues/c4m3l-security/redhand?color=red)](https://github.com/c4m3l-security/redhand/issues)
[![stars](https://img.shields.io/github/stars/c4m3l-security/redhand?color=yellow)](https://github.com/c4m3l-security/redhand/stargazers)
[![forks](https://img.shields.io/github/forks/c4m3l-security/redhand?color=blue)](https://github.comc4m3l-security/redhand/network)


Redhand is a tool designed to assist security professionals in the evaluation and optimization of their redteam infrastructure by monitoring C2 setups and testing files, both static and in runtime to help with bypassing antivirus and firewalls, for more effective redteam operations.

## Requirements
Lots of RAM... You can quickly run out of memory if you run to many virtual machines at once, I'm fixing this problem in the next release where I will add a sample queue.

## Good to know
There is currently no integrated setup for a intrusion detection system but I recommend to pick OSSEC (open-source) and configure it to your needs so that you can test files against a IDS with rulesets that matches your adversary for more realistic results.

Recommended firewalls that you can use is Portmaster (https://safing.io) or Glasswire (https://www.glasswire.com).
