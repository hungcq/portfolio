---
weight: 6
title: "Medical Contract Template"
hlink: "https://medi-template.hungcq.xyz"
github: https://github.com/hungcq/medical-template
#cover:
#  image: /images/medical-template.png
summary: >
  This simple browser-based app automates the process of filling out hospital procurement documents,
  saving my cousin’s team hours of repetitive work and greatly reducing errors.
  It shows how even a small, well-designed software solution can have a significant real-world impact.
---

In 2021, my cousin approached me with a problem:
he and his team spent countless hours manually filling out hospital procurement documents required to purchase medical equipment.
For each bidding process, the same information—such as bidding package details, departments involved,
and contractor information—needed to be painstakingly entered into more than 20 different documents.
This repetitive work was not only time-consuming but also prone to errors,
resulting in the need for multiple rounds of error checking and correction.

To address this, I envisioned a simple solution: a static website that runs entirely in the browser,
allowing users to input the required information once, fill all the necessary documents automatically,
and download them as a zip file. I quickly brought this idea to life in about 30 minutes,
leveraging **React** for the frontend and **docxtemplater** for document processing,
then deploying the app using **AWS S3** and distributing it via **AWS CloudFront**.

Although simple, the app has saved the team thousands of hours of manual, error-prone work.
Now, they only need to fill out a single form to generate all required documents with consistent and accurate information.
This experience reaffirmed my belief that well-targeted software—even small,
focused projects—can deliver immense value and solve real problems, especially for those underserved by existing solutions.

![Screenshot](/images/medical-template.png)