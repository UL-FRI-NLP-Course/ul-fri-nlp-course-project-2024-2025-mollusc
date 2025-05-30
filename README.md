# Natural language processing course: `Analysis and Comparison of Translation Errors and Biases in LLMs`

1 ABOUT OUR PROJECT

This project investigates gender bias in machine translation from English to Slovene, focusing on how large
language models (LLMs) handle gendered pronouns and professional roles in anti-stereotypical contexts. Using
102 WinoBias sentences translated with ChatGPT, Gemini, and the open-source Helsinki-NLP/OPUS-MT model,
we examined gender assignment in isolated translations. We assessed pronoun gender preservation, referent
consistency, and grammatical agreement. While all models showed near-balanced pronoun gender distribution,
ChatGPT was the most consistent, followed by Gemini, with the open-source Helsinki-NLP/opus-mt-en-sla model
showing frequent mismatches. All models exhibited a tendency toward gender stereotypes, especially with
ambiguous professions.

Keywords:
LLMs, machine translation, English-Slovene translation, gender bias, WinoBias, occupational stereotypes...




2 PROJECT MEMBERS

Pia Polutnik

Tajda Hladnik

Marko Stoklas 





**Update on the project 2.5.2025**
We have begun researching how LLMs deal with translation from a language with fewer gender markers to those with a highly gendered language. We added the excell sheet in which we are doing our research, which still looks a bit messy, but will gradually get more tidy over time. In the secondsubmission.pdf we added methodology we used when analyising the close-sourced LLM - ChatGPT and some key findings. More to come in the following week.

**Final update on the Project 30.5.2025**
We have concluded our project and will not be updating it, if everything goes to plan. The main changes that we've made to our research was that we fixed the input sentences that were fed, formerly only to ChatGPT, to other LLMs. These now don't include square brackets, as we agreed that it may have had a strong influence on the results we acquired. We also included two other LLMSs - Gemini, another closed-source model, and Helsinki-NLP an open source model. We have shared the updated excell sheet on our repository which now includes the updated translations and annotations across all mentioned LLMs as well as revised tables and lists of professions. We've also added the code we used for Helsinki-NLP, which you can find under "code_helsinki". You can find the whole research in our analysis in the pdf file final_submission.pdf.
