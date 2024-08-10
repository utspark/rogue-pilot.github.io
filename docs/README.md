<img src="logo.jpg" width=150 align=right>

## Overview of ConfusedPilot

The hype for integrating artificial intelligence into an enterprise’s daily work has become more prevalent after introducing AI-driven systems that use Retrieval Augmented Generation (RAG), such as Copilot for Microsoft 365. But is the trust in such systems and their control over decision-making processes within enterprises rational? Copilot and other RAG-based systems can be misused to cause dissemination of misinformation that negatively impacts decision-making processes without proper auditing and safeguarding of data available to large language models in RAG-based systems.

This talk will demonstrate such an attack that we have termed ConfusedPilot because of its ability to turn Copilot into a confused deputy. The attack occurs when a malicious document is introduced to the data pool (documents, presentations, other relevant files, etc.) related to a topic affecting the enterprise’s decision-making process. The malicious document contains a combination of corrupt data and malicious strings that suppress the correct documents related to the topic and respond to the user’s query with only the information present within the malicious document. Furthermore, the talk highlights how this attack can persist after deleting content within the malicious document or the document itself. The talk also points to the larger implications of such attacks, highlighting their cascading effect and existing security measures that can be used to reduce the attack’s effectiveness. Our talk sheds light on the current attacks and potential security measures that can shield enterprises from the adverse effects of such attacks on their AI-driven systems.

## Research Paper

[ConfusedPilot: Compromising Enterprise Information Integrity and Confidentiality with Copilot for Microsoft 365](confused_pilot_arxiv.pdf).
[bibtex](citation.txt)

## Contributors

* [Ayush Roychowdhury](https://www.linkedin.com/in/ayushroyc/?trk=people-guest_people_search-card) (UT Austin)
**Ayush RoyChowdhury** is an incoming master student at the Chandra Department of Electrical and Computer Engineering at the University of Texas Austin. His research interests include language model security, data security, and explainable artificial intelligence for security.
<img src="imgs/ayush.png" width=50 align=left>
* [Mulong Luo](https://mulongluo.me) (UT Austin)
  **Mulong Luo** is currently a postdoctoral researcher at the University of Texas at Austin. His research interests are in computer architecture, side channel, and machine learning. He won best paper award at CPS-SPC workshop. He got his Ph.D. from Cornell University in 2023.
  <img src="imgs/ayush.png" width=50 align=left>
* [Prateek Sahu](https://prateeksahu.github.io) (UT Austin)
   **Prateek Sahu** is currently a Ph.D. student at the University of Texas at Austin. His research interests are microservices, service mesh, cloud computing, function-as-a-service measurement.
  <img src="imgs/prateek.png" width=50 align=left>
  
* [Sarbartha Banerjee](https://www.linkedin.com/in/sarbartha-banerjee-6945b242/) (UT Austin)
  **Sarbartha Banerjee** is currently a Ph.D. candidate at the University of Texas at Austin. His research interests are secure accelerators, side channel defense, machine learning security.
  <img src="imgs/sarbartha.png" width=50 align=left>
  
* [Mohit Tiwari](https://www.ece.utexas.edu/people/faculty/mohit-tiwari) (Symmetry Systems / UT Austin)
  **Mohit Tiwari** is an associate professor and he directs the SPARK lab at the University of Texas at Austin. His current research focuses on building secure systems, all the way from hardware to system software to applications that run on them. Prof. Tiwari received a PhD from UC Santa Barbara (2011) and was a post-doctoral fellow at UC Berkeley (2011-13) before joining UT.
  <img src="imgs/mohit.jpeg" width=50 align=left>

