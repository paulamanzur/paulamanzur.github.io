<a id="readme-top"></a>
<p align="center"><img align="center" src="https://repository-images.githubusercontent.com/864117981/ae9169ec-c337-4250-98da-0e90138ba39b" alt="PREDICT"></p>
<div align="center">
  <h3 align="center">PREDICT Methodology</h3>

  <p align="center">
    A strategic MT risk methodology for effective localization solutions.
    <br />
  </p>
</div>

<details>
  <summary>Table of Contents</summary>
  
  <ol>
    <li><a href="#about-the-methodology">About The Methodology</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#contents">Contents</a></li>
    <li><a href="#dynamic-usage">Dynamic Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#faq">FAQ</a></li>
  </ol>
</details>

## About The Methodology

Enterprises in the localization sector handle diverse content types, requiring precise localization solutions. Options range from raw machine translation to transcreation. But how can they ensure the best match between content and localization method? Traditionally, the decision relied mostly on human judgment.

The PREDICT Methodology offers a systematic approach for assessing MT suitability, aligning content type with the optimal localization solution. By integrating risk tolerance weights into binary queries about a source content and use case, PREDICT provides a score and recommended solution, from raw MT to human-only translation.

This approach enables our business to provide the right quality for that specific content type, boost translation efficiency and reduce costs. Looking ahead, the methodology envisions integrating LLMs for automation and guidance, utilizing prompts to identify risk-mitigating strategies.

This case study, a contribution from _Booking.com's_ localization team, has been adapted and shared as open-source material in the **_[AMTA 2024](https://amtaweb.org/amta-2024/)_** proceedings. With a slightly modified version available, it aims to provide value for both suppliers and buyers within the localization industry.
<p align="right">(<a href="#readme-top">Back to top</a>)</p>

## Getting Started

### Prerequisites

Any Spreadsheet application capable of load a .xlsx file (MS Excel, LibreOffice, Google Sheets, etc)

### Installation

To get started you can either:
- Directly download the file [PREDICT Methodology Case Study.xlsx](https://github.com/paulamanzur/PREDICT-Methodology/blob/main/PREDICT%20Methodology%20Case%20Study.xlsx)

or
  
- By cloning the repo. To do so:

   1. Clone the repository:
       ```sh
       git clone https://github.com/paulamanzur/PREDICT-Methodology.git
       ```
   2. Open the `PREDICT Methodology Case Study.xlsx` file.
<p align="right">(<a href="#readme-top">Back to top</a>)</p>

## Contents

The Sheet includes the following tabs:
- `Intro`: Brief introduction to the project.
- `CriteriaDefinitions`: Questions in the form of statements and their definitions were divided into six main categories:
  - Source Text Characteristics (Structure, Style, Main Intent)
  - Terminology
  - Legal & Regulatory Requirements
  - Target Audience
  - Project-Specific
  - Field of Expertise

General examples have been provided to guide evaluators to the most objective answer and specific client examples can be added.

Field of Expertise refers to any Domains and Subdomains used by customers (not to Content Types), since different content types can belong to the same domain. For example, Marketing is the Domain and Marketing Editorial is the Content type). 

- `WeightsDictionary`: The methodology incorporates a set of 30 binary questions (evaluators provide responses that fall into one of two categories: "Yes" or "No"). Risk weights from 1 to 4 are added next to each question to provide granularity. The allocation of these weights is based on whether a “Yes” or “No” response to a question poses a risk to the eligibility of MT or leans towards the optimal outcome for the use of MT. For example:

  - Question in the form of statement: “The source text style shows signs of wordiness and verbosity”
  - Answer: This statement is TRUE (Answer is YES)
  - MT Eligibility Risk Allocation: This puts the Machine Translation Eligibility “At Risk”
  - MT Eligibility Risk Explanation: wordy and verbose writing styles can make it difficult for machine translation systems to understand the intended meaning of a text, identify the key information, parse the sentence structure, and follow grammatical rules. This can lead to inaccurate and even nonsensical translations.
  - Risk Weight Allocation (from 1 to 4): This puts the Machine Translation Eligibility At Risk of 4 points.

  If, on the other hand:
  
  - The following statement is TRUE (or the Answer is YES): “the source text style is clear, concise and direct”
  - This puts the Machine Translation Eligibility At Optimal (for its use)
  - MT Eligibility Risk Explanation: clear, concise, straightforward, and unambiguous text facilitates accurate translation by machine translation systems by eliminating the need for complex interpretation.
  - Risk Weight Allocation: This puts the Machine Translation Eligibility At Optimal for its use and therefore it has no risk points.

- `ResultsSummary`: Consolidates the results of each use case and gives a result based on their scores:
    > Final Score = Weighted Impact on MT Eligibility / Maximum Possible Risk to MT

It also contains several use cases:
- `Marketing PR Articles`
- `Marketing Editorial Articles`
- `Attractions Descriptions`
- `Scaled Property Descriptions`
- `Guest Reviews (UGC)`
- `Legal Documents (Internal)`
- `Inf. Comm. (Legal Emails)`
- `Inf. Comm. (Non-Legal Emails)`
- `User Research (Surveys)`
- `Help Centre (Partners)`
<p align="right">(<a href="#readme-top">Back to top</a>)</p>

## Dynamic Usage

Parameters, such as the questions, examples, domains and associated risk weights can be adjusted dynamically according to different Customer needs. Evaluators need to be familiarized with the source content text (examples) and the Criteria Definitions before starting answering the questions.

To use the Excel file:
- Navigate to the Case Study example sheets (e.g. Marketing PR Articles) and replace the information with your data (use the sheets as templates).
- Go to the `ResultsSummary` sheet to view the results based on your data. It will automatically update based on the data entered.
<p align="right">(<a href="#readme-top">Back to top</a>)</p>

## Contributing

For major changes, please open an issue first to discuss what you would like to change or contact me via the Contact information below.
<p align="right">(<a href="#readme-top">Back to top</a>)</p>

## License

This Excel file is licensed under the [Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/).

![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)
<p align="right">(<a href="#readme-top">Back to top</a>)</p>

## Contact

Paula Manzur: [LinkedIn](https://www.linkedin.com/in/paulamanzur)

Project Link: [https://github.com/paulamanzur/PREDICT-Methodology](https://github.com/paulamanzur/PREDICT-Methodology)
<p align="right">(<a href="#readme-top">Back to top</a>)</p>

## FAQ

#### Why was this methodology developed?

The creation of this methodology was part of a strategic localization initiative at Booking.com. It introduced a more robust, detailed, and systematic approach for the objective evaluation of diverse content types using multiple evaluators.

#### Can I adopt it as part of my Localization Program?

Yes, with non-commercial purposes, the Methodology aims to facilitate informed decision-making, aiding stakeholders in the localization industry in determining the optimal localization solution based on MT risk assessment.  

For more context, the localization & MT industry are assessing MT suitability in different ways, with no unified system in place. With the PREDICT Methodology, we've made a simple yet important attempt at a more robust, detailed, and systematic approach to MT eligibility criteria. This is not the final answer but a starting point to reopen the conversation within the MT community about the need for common best practices that empower people to make informed, data-driven decisions.

#### What is the recommended frequency for evaluation and how many Evaluators are recommended?

Evaluators actively provide their insight by answering the questionnaire. The advised number is 3 or 5 (preferably an odd number). The more evaluators are involved in the methodology, the more objective the evaluation process is. Stakeholders and language professionals who are familiar with the content can participate in the questionnaire. 
Exploratory evaluations for new content types and Periodic ones for validation (recommendation is once a year) depending on the business context.

#### Can I use LLMs as Evaluators? 

The Methodology was created with a human-centered approach. However, some experiments have been done with ChatGPT as an evaluator. Preliminary conclusions show that it requires several fine-tuning iterations for the prompts. For now, human evaluators are more reliable. If LLMs are used as evaluators, prompts need to be created from scratch and tested. There are no suggested prompts in the Methodology yet.

#### How can I validate PREDICT's recommendations?

If the methodology recommends Full MTPE for one content type and A/B testing is used to compare this solution versus RAW MT, for example, this can help validate or reject the prediction from a customer/business perspective. 
<p align="right">(<a href="#readme-top">Back to top</a>)</p>
