<img src="logo.jpg" width=150 align=right>

## Overview of Rogue Pilot

The hype for integrating artificial intelligence into an enterprise’s daily work has become more prevalent after the introduction of AI-driven systems that use Retrieval Augmented Generation (RAG) as seen with Copilot for Microsoft 365. But is the trust put into such systems and their control over decision-making processes rational? System design vulnerabilities within Copilot can be exploited to cause a dissemination of misinformation impacting decision-making processes negatively.

This talk will demonstrate such an attack that we have termed RoguePilot because of its ability to turn Copilot rogue. The attack occurs when a malicious document is introduced to the data pool (documents, presentations, other relevant files, etc.) related to a topic affecting the decision-making process of the enterprise. The malicious document contains a combination of corrupt data and malicious strings that suppress the correct documents related to the topic and respond to the user’s query with only the information present within the malicious document. Furthermore, the talk highlights how this attack can persist long after the deletion of content within the malicious document or the document itself.

The talk also points to the larger implications of such vulnerabilities, highlighting the potential for widespread and self-perpetuating organizational disruption and regulatory concerns. Our talk not only sheds light on the vulnerabilities currently present but also calls for a concerted effort to develop standards and practices that can shield enterprises from the adverse effects of such attacks on AI-driven systems.

## Research Paper

[pdf](rogue_pilot_arxiv.pdf) 
[cite](citation.txt)

## Contributors

* [Ayush Roychowdhury](https://www.linkedin.com/in/ayushroyc/?trk=people-guest_people_search-card) (UT Austin)
* [Mulong Luo](https://mulongluo.me) (UT Austin)
* [Prateek Sahu](https://prateeksahu.github.io) (UT Austin)
* [Sarbartha Banerjee](https://www.linkedin.com/in/sarbartha-banerjee-6945b242/) (UT Austin)
* [Mohit Tiwari](https://www.ece.utexas.edu/people/faculty/mohit-tiwari) (Symmetry Systems / UT Austin )

## Questions and Answers

* **Am I affected?**

  If you use Copilot for Microsoft 365, then you are affected by our findings. Copilot for Microsoft 365 has been rolling out widely in corporations. For example, UT Austin has recently made Copilot for Microsoft 365 university wide.

* **What is the mechanism behind Rogue Pilot?**

* **What product is affected by Rogue Pilot?**

  Rogue Pilot is targeting Copilot for Microsoft 365, which is a system that is used in the enterprise environment for improving efficiency. It is based on retrieval augmented generation (RAG). It should be noted that Rogue Pilot is not targeting Microsoft Copilot Pro, which does not use RAG for generating response based on enterprise database.

* **What is the difference between Copilot Pro and Copilot for Microsoft 365**

  Copilot Pro is a large language model that integrates with Microsoft ecosystem, that helps generate content based on the user prompt.
Copilot for Microsoft 365 is a retrevial-augmented generation system that can generate content based on the user prompt as well as the database of an enterprise.

* **What is retrieval augmented generation?**

  Retrieval augmented generation (RAG) is a technique for improving response quality and eliminating an LLM system’s expensive retraining or fine-tuning phase. It incorporates an additional step in an LLM system where the model retrieves external data to augmentits knowledge base, thus enhancing accuracy and reliability in generating responses, without using retraining or fine-tuning.

* **What is a large language model?**

  Large language models (LLMs) are machine learning models that can comprehend and generate human language text. They work by analyzing massive data sets of language.

* **Who is at fault with the findings?**

* **What is access control?**

* **Can I disable the Copilot?**

  While disabling Copilot for Microsoft 365 can prevent some of the issues demonstrated by Rogue Pilot, it will affect the efficiency of an enterprise who tries to use AI to improve the efficiency.

* **What can I do to protect myself against these?**

  Right now, there are known solutions that solve this. Our recommendation is to isolate top-secret files from Copilot and to keep Copilot away from safety critical decisions.

* **Can I use the logo?**

  Yes. The logo is licensed under MIT license.



