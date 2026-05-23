# Evaluating Web Accessibility for Visual Disabilities: A Decision-Based Method for LLM-Generated Web Pages

This repository contains the associated files described in our submission to *Programming and Computer Software* (Submission ID: 17). This README provides an overview of the repository structure.

## Manuscript Information

**Title:** Evaluating Web Accessibility for Visual Disabilities: A Decision-Based Method for LLM-Generated Web Pages  
**Submission ID:** 17

### Authors

**Guillermo Vera-Amaro**  
*Universidad Veracruzana*  
Email: gvera@uv.mx  

**José Rafael Rojano-Cáceres**  
*Universidad Veracruzana*  
Email: rrojano@uv.mx  

### Abstract

The increasing use of Large Language Models (LLMs) for generating web pages poses new challenges for accessibility evaluation, as results from automated tools are often descriptive and insufficient for decision making. This paper proposes a threshold-based method for evaluating the accessibility of LLM-generated web pages. The method is derived from a progressive experimental design that incrementally combines automated testing (AT), analytical expert evaluation through Barrier Walkthrough (BW), and empirical evaluation using Cognitive Walkthrough (CW). Results show that automated metrics alone may overestimate accessibility and fail to reflect task-level usability, while progressively combined methods provide more reliable and interpretable evidence. Based on these findings, explicit threshold criteria are introduced to support accept–reject decisions for AI-generated pages. The proposed method enables consistent, reproducible, and decision-oriented accessibility evaluation in AI-driven web content generation pipelines.

## Repository Structure

The repository is organized as follows:

- `output/`: This folder stores generated HTML variants produced by each model across different configurations.

## Additional Notes

For full details on the methodology and results, refer to the associated article.

## Summary of the variants obtained from experiments

| ID   | Variant                     | Link          |
|------|-----------------------------|---------------|
| V01  | Original (Site 1)           | [View](https://www.washington.edu/accesscomputing/AU/before.html) |
| V02  | Manual compliance (Site 1)  | [View](https://www.washington.edu/accesscomputing/AU/after.html) |
| V03  | GPT-HTML (Site 1)           | [View](https://gverafei.github.io/decision-based-method/output/gpt-site1/1-from_html.html) |
| V04  | GPT-HTML+T (Site 1)         | [View](https://gverafei.github.io/decision-based-method/output/gpt-site1/2-from_html_template.html) |
| V05  | GPT-MD (Site 1)             | [View](https://gverafei.github.io/decision-based-method/output/gpt-site1/3-from_md.html) |
| V06  | GPT-MD+T (Site 1)           | [View](https://gverafei.github.io/decision-based-method/output/gpt-site1/4-from_md_template.html) |
| V07  | Gem-HTML (Site 1)           | [View](https://gverafei.github.io/decision-based-method/output/gemini-site1/1-from_html.html) |
| V08  | Gem-HTML+T (Site 1)         | [View](https://gverafei.github.io/decision-based-method/output/gemini-site1/2-from_html_template.html) |
| V09  | Gem-MD (Site 1)             | [View](https://gverafei.github.io/decision-based-method/output/gemini-site1/3-from_md.html) |
| V10  | Gem-MD+T (Site 1)           | [View](https://gverafei.github.io/decision-based-method/output/gemini-site1/4-from_md_template.html) |
|------|-----------------------------|---------------|
| V11  | Original (Site 2)           | [View](https://openassessittoolkit.github.io/accessible_u/before_u.html) |
| V12  | Manual compliance (Site 2)  | [View](https://openassessittoolkit.github.io/accessible_u/after_u.html) |
| V13  | GPT-HTML (Site 2)           | [View](https://gverafei.github.io/decision-based-method/output/gpt-site2/1-from_html.html) |
| V14  | GPT-HTML+T (Site 2)         | [View](https://gverafei.github.io/decision-based-method/output/gpt-site2/2-from_html_template.html) |
| V15  | GPT-MD (Site 2)             | [View](https://gverafei.github.io/decision-based-method/output/gpt-site2/3-from_md.html) |
| V16  | GPT-MD+T (Site 2)           | [View](https://gverafei.github.io/decision-based-method/output/gpt-site2/4-from_md_template.html) |
| V17  | Gem-HTML (Site 2)           | [View](https://gverafei.github.io/decision-based-method/output/gemini-site2/1-from_html.html) |
| V18  | Gem-HTML+T (Site 2)         | [View](https://gverafei.github.io/decision-based-method/output/gemini-site2/2-from_html_template.html) |
| V19  | Gem-MD (Site 2)             | [View](https://gverafei.github.io/decision-based-method/output/gemini-site2/3-from_md.html) |
| V20  | Gem-MD+T (Site 2)           | [View](https://gverafei.github.io/decision-based-method/output/gemini-site2/4-from_md_template.html) |
