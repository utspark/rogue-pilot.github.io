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

