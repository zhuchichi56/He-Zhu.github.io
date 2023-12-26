---
title: "NLP Final Project"
excerpt: "Some Tips for LLMs in specific domains like clinic/law/finance."
collection: portfolio
---


1.扩充词表，每个领域都有专业名词，如果不扩充词表的话必然会造成输出的泛化与不准确;

2.为了减少幻觉，可以尝试使用retrieval-base的方法, 把领域的专业知识逐渐融入

3.微调超参数，找出最好的lora方法; 同时使用更好的微调方法，比如使用O-Lora

4.使用数据集进行增广 比如使用 Evol-instruct --> 让数据变得更加困难+更加多样性 或使用 humpback 方法根据教科书级别的数据创造微调pair

5.使用MoDS等算法精选出高质量的微调数据进行指令微调

6.根据教科书级别的数据进行继续预训练；
