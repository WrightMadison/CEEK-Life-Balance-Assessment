# [CEEK Life Balance Assessment](https://www.ceekllc.com/balance-assessment)
## Current Version: 1.3
#### Released: February 11, 2022
##### Written by: Madison Wright
##### Contact: wrightmadison@gmail.com

## Introduction
This is a "Life Balance Assessment" written for CEEK LLC during my time as an intern there. The purpose of the assessment is to help people determine how balanced their priorities are in life with an initial evaluation, and then provide advice for finding better life balance. The assessment was written to be paired with a book written by the President of CEEK LLC, titled *[Navigate Chaos: A 5-Step Guide to Balance Work, Family, and Other Life Priorities](https://www.amazon.com/gp/product/1732517606)*.

I was told that I could develop the assessment in any way that I see fit and would be paid for my time learning new programming languages if need be. I ultimately decided to code the assessment in **JavaScript**, **HTML**, and **CSS** and taught myself these three programming languages in the early stages of development.

For the backend of the assessment, I decided to use a Google Sheet because the assessment does not collect sensitive information and I wanted it to be user-friendly for when I part from CEEK LLC. Having Google Sheets as the backend would not require a programmer to maintain it and anyone with access to the Google Sheet would be able to easily understand the data. All it required was for me to have a basic understanding of **Google Apps Script** to be able to push data to the spreadsheet.

## Take the Assessment
* [CEEK Life Balance Assessment](https://www.ceekllc.com/balance-assessment/)
* **Free access code:** b5x9-4z8d-hv2y

## Parameters
* Access code for the assessment that allows users to take it twice, once for an initial evaluation and again after several months to measure personal growth
* Demographic survey at the beginning to receive basic, non-identifying information about the user taking the assessment
* Users type their own priority areas and must provide 4-10 of them
* The assessment must have two sections, one for "Do you..." and one for "Are you willing to..." questions to determine the ranking of priority areas by measuring when the user sacrifices a particular priority area for another
* A PDF report is generated at the end to provide results
* Store the user's percentage score along with their basic demographic information

## Milestones
* **August 26, 2018:** The first complete version of the assessment was released for free trial mode.
* **October 10, 2018:** *Navigate Chaos: A 5-Step Guide to Balance Work, Family, and Other Life Priorities*, written by the President of CEEK LLC, was released and the access code was turned on for the assessment.
* **January 30, 2019:** Updated all of the report text after it was sent to two editors. Test cases were also written and thoroughly documented in a spreadsheet that has been pushed to this repository, along with test case results.
* **February 11, 2022:** In September 2020 Google shut down the infrastucture that Tabletop relies on, but this went unnoticed until November 2021 when I was contacted by CEEK for help. After the holidays I was hired to diagnose and fix the error. After looking into the error, I switched to Papa Parse per the recommendation of Tabletop developers. The only catch is that the assessment cannot be tested locally anymore; it can, however, be tested in Wix's editor preview mode.

## Programming Languages
* JavaScript
* HTML
* CSS
* Google Apps Script

## Libraries Used
* [Bootstrap](http://getbootstrap.com)
* [jQuery](https://jquery.com/)
* [jsPDF](https://github.com/MrRio/jsPDF)
* [Push Data to Google Sheet](https://github.com/dwyl/learn-to-send-email-via-google-script-html-no-server)
* ~~[Tabletop.js](https://github.com/jsoma/tabletop)~~ (no longer works due to a dependency that was shut down in September 2020)
* [Papa Parse](https://github.com/mholt/PapaParse)

## Other Resources Used
* [ImgBB](https://imgbb.com)
* [Markdown Live Preview](https://markdownlivepreview.com/)
