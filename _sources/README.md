<div align="center">
<h1 align="center">
Risk Practitioner's Handbook
</h1>

![Image](images/software.png)

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-fuchsia?logo=GitHub)](https://github.com/deburky/RP-2023) [![View Book](https://img.shields.io/badge/Book-View%20Book-cyan?style=plastic&logo=book)](https://deburky.github.io/RP-2023/README.html)
</div>

## Introduction

<span style="font-family: Karma, sans-serif;">

The idea to write this handbook came to me after I started to research convenient personal knowledge management tools to keep track of my library of web links and research papers about predictive models in the financial services domain, specifically in financial risk management.

There are several reasons why financial risk as a domain of specialty is special and not easy to unlock:

* Credit scoring a high-risk application of machine learning, which is guided specific requirements for the end-to-end model development cycle. This is very different from a typical process of unconstrained model prototyping aimed at achieving top accuracy
* Financial data has the highest value according to <a href="https://edmcouncil.org/wp-content/uploads/2023/03/EDM_Council_Data_ROI_SIG_Value_of_Data_29_Mar_2023_.pdf">this study</a> and is one of the most expensive to obtain and is very specific to an institution running lending operations
* Internal tools developed for credit risk require a solid data foundation that puts a strong emphasis on the quality of data and its representativeness. These topics are almost never addressed given the availability of a static dataset

This handbook is focused on Python and its scientific ecosystem. Some years ago, many players in the banking splace thought that open-source software is never going to replace their provider of modeling and analytics software. With Python, open-source credit risk management software is a reality, especially with the growing interest in large language models (LLMs) in Finance.


This handbook is an attempt to systematically collect relevant applied-focused materials that may be useful to a practitioner attempting to frame credit risk as a machine learning problem. Examples in the notebooks supplementing each chapter exemplify some examples of credit risk modeling work that can be extended to various real-world datasets.

The structure of the Handbook is as follows:

* Chapter 1. Datasets
* Chapter 2. Models
* Chapter 3. Metrics
* Chapter 4. Explainability
* Chapter 5. Fairness

</span>


## Why This Handbook?

<span style="font-family: Karma, sans-serif;">

Credit scoring has been around for quite a while, so why write another handbook about it? Despite extensive research published over the years, this specific predictive modeling domain is no easy topic to dive into. However, learning by practicing on real-world credit datasets can help develop a practical understanding of the problem, its specifics, and how it can be modelled.

</span>

<style>
  .two-columns {
    display: flex;
  }

  .column {
    flex: 1;
    padding: 10px;
  }

</style>

<div class="two-columns">
  <div class="column">
    <h2>Why Python for Credit Risk Modeling?</h2>
    <p><span style="font-family: Karma, sans-serif;">Python is known as the lingua franca of data and is one of the most commonly used languages in the analytics and machine learning space. Using Python efficiently in credit risk modeling is essential for producing readable, production-grade code and improving the scalability of credit-risk models.</span></p>
  </div>
  <div class="column">
    <h2>What to Expect From This Handbook</h2>
    <p><span style="font-family: Karma, sans-serif;">This handbook assumes you have a basic understanding of object-oriented programming languages (e.g., Python, R, Julia) and credit risk basics like scorecards. You will find resource links for each tool and technique for further exploration and online/offline reading. This handbook will serve to provide starting points for credit-risk model development.</span></p>
  </div>
</div>

<div class="two-columns">
  <div class="column">
    <h2>About This Handbook</h2>
    <p><span style="font-family: Karma, sans-serif;">This handbook is a compilation of helpful resources, tips and other artifacts collected across years of working in the banking space. It draws from real-world experience and best practices in credit risk modeling.</span></p>
  </div>
  <div class="column">
    <h2>About the Author</h2>
    <p><span style="font-family: Karma, sans-serif;">The author works as a risk practitioner in the financial services domain, specializing in the area of credit risk modeling. The author is committed to making open-source tools more accessible to the community. For updates and additional tips, you can follow me on 
<a href="https://www.linkedin.com/in/denisburakov">LinkedIn</a>.</span></p>
  </div>
</div>