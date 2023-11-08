<div align="center">
<h1 align="center">
Risk Practitioner Handbook
</h1>

![Image](images/software.png)

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-fuchsia?logo=GitHub)](https://github.com/deburky) 
[![Netlify Status](https://api.netlify.com/api/v1/badges/9e1397bb-f8f0-4ac4-88bf-8e855103606a/deploy-status)](https://app.netlify.com/sites/neon-parfait-a7dde1/deploys)
</div>

<span style="font-family: Karma, sans-serif;">

The idea to write this handbook came to me after I started to research convenient personal knowledge management tools to keep track of my library of web links and research papers about predictive models in the financial services domain, specifically in financial risk management. I decided to focus on the most developed areas of credit risk modeling, credit scoring, but hope to extend the handbook to cover more applied use-cases.

While one may come across many books on the topic, the examples provided may often appear too high-level for practical applications. There are several reasons why financial risk as a domain of specialty is special and not easy to unlock:

* Credit scoring a high-risk application of machine learning, which is governed by specific requirements surrounding model development activities. This makes the field very different from research settings where the aim is usually to maximimize accuracy or another metric of choice.
* Financial data is one of the most valued assets according to <a href="https://edmcouncil.org/wp-content/uploads/2023/03/EDM_Council_Data_ROI_SIG_Value_of_Data_29_Mar_2023_.pdf">this study</a> and is one of the most expensive to obtain, which makes datasets used in modeling very specific to a lender.
* Internal tools developed for credit risk require a solid data foundation that puts a strong emphasis on the quality of data and its representativeness. These topics are almost never addressed in most books and guides.

This handbook is focused on Python and its scientific ecosystem. Some years ago, many players in the banking space doubted that open-source software is going to replace their provider of choice. With Python, open-source credit risk management software is a reality, especially so in light of growing interest in large language models (LLMs) in Finance.

This handbook is an attempt to systematically collect relevant applied-focused materials that may be useful to a practitioner attempting to frame credit risk as a predictive modeling problem. Examples in the notebooks supplementing each chapter provide some examples of credit risk modeling work that can be extended to various real-world datasets.

</span>

## About the Author

![Image](images/photo_02.png)

<p><span style="font-family: Karma, sans-serif;">Denis is a risk practitioner specializing in credit risk modeling and consumer lending, a technical writer and a loyal fan of the Python language. The author is committed to making open-source tools more accessible to the community. For updates and additional tips, feel free to get in touch with me on <a href="https://www.linkedin.com/in/denisburakov">LinkedIn</a>.</span></p>

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
    <h2>Why Python?</h2>
    <p><span style="font-family: Karma, sans-serif;">Python is known as the lingua franca of data and is one of the most commonly used languages in the analytics and machine learning space. Using Python efficiently in credit risk modeling is essential for producing readable, production-grade code and improving the scalability of credit-risk models.</span></p>
  </div>
  <div class="column">
    <h2>What to Expect From This Handbook</h2>
    <p><span style="font-family: Karma, sans-serif;">This handbook assumes you have a basic understanding of object-oriented programming languages (e.g., Python, R, Julia) and credit risk basics like scorecards. You will find resource links for each tool and technique for further exploration and online/offline reading.</span></p>
  </div>
</div>