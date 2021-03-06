# KDD 2019 Hands-on Tutorial: Declarative Text Understanding with [SystemT](https://researcher.watson.ibm.com/researcher/view_group.php?id=1264)


## Requirements:

Laptop with WiFi - please ensure that you can connect to the conference wifi prior to the tutorial

Web browser - preferably the latest version of Firefox or Chrome.

This tutorial leverages resources from IBM cloud (https://cloud.ibm.com/)

**All labs require that you obtain an IBM cloud account (free version is sufficient to complete the labs)**

The labs only requires an IBM cloud account to use the Watson Knowledge Studio and Natural Language Understanding services.

## Abstract

With the proliferation of information in unstructured and semi-structured form, text understanding (TU) is becoming a fundamental building block in enterprise applications. SystemT is an industrial-strength system for developing end-to-end TU applications in a declarative fashion. Commonly used text operations are abstracted as built-in operators with clean, well-specified semantics exposed through a formal declarative language called AQL (Annotation Query Language), which are transformed by a compiler into highly optimized internal implementations and executed by an efficient and lean runtime engine. Its architecture is designed to address the main requirements for enterprise TU: scalability, expressivity, transparency, and extensibility. SystemT today ships with multiple products across 4 IBM Software Brands and is used in multiple ongoing research projects and being taught in universities. Ongoing research and development efforts focus on making SystemT more usable for both technical and business users, and continuing enhancing its core functionalities based on natural language processing, machine learning, and database technology. 

In this tutorial, we will motivate declarative TU and showcase SystemT features for meeting the enterprise TU requirements. The hands-on labs will provide concrete examples on performing TU in progressively sophisticated use cases.  

## Related References:

- **Overview Papers**
  - *SystemT: Declarative Text Understanding for Enterprise*. NAACL 2018 [link](https://aclweb.org/anthology/papers/N/N18/N18-3010/)
  - *SystemT: An Algebraic Approach to Declarative Information Extraction*. ACL 2010 [link](https://www.aclweb.org/anthology/P10-1014)
  
- **Online Course** Overview of Information Extraction Techniques and Hands-on experience doing Information Extraction using SystemT. [link](https://cognitiveclass.ai/courses/systemt/)


## Tutorial Outline:
- Introduction to enterprise text understanding
- Overview of SystemT
- Visual introduction to building extractors
- Hands-on Lab 1: Building extractors with Watson Knowledge Studio
- Hands-on Lab 2: Creating and editing extractors visually with the Advanced Rule Editor
- Annotation Query Language (AQL)
- Hands-on Lab 3: Creating advanced extractors and writing AQL with the Advanced Rule Editor
- Advanced topics and research directions
   
## Tutors:

**Huaiyu Zhu**

*[Huaiyu Zhu](https://www.linkedin.com/in/huaiyu-zhu-075608134/) is a Research Staff Member in the [Scalable Knowledge Intelligence](https://researcher.watson.ibm.com/researcher/view_group.php?id=9820) group at [IBM Almaden Research Center](http://www.research.ibm.com/labs/almaden/index.shtml). His main research focus is on text analytics, natural language processing, machine learning and statistical information processing. He has a PhD in Computational Mathematics and Statistics from University of Liverpool, and a BS in Computational Mathematics from Xian Jiaotong University.*

**Yunyao Li**

*[Yunyao Li](https://researcher.watson.ibm.com/researcher/view.php?person=us-yunyaoli) is a Principle Research Staff Member and Senior Research Manager at  IBM Almaden Research Center where she manages the [Scalable Knowledge Intelligence Department](https://researcher.watson.ibm.com/researcher/view_group.php?id=9820). She is also a Master Inventor and a member of IBM Academy of Technology.  Her expertise is in the interdisciplinary areas of natural language processing, databases, human-computer interaction, and information retrieval.  She is a founding member of SystemT, a state-of-the-art NLP system currently powering multiple IBM products, and numerous projects. She received her PhD and master degrees from  the University of Michigan Ann Arbor and undergraduate degrees from Tsinghua University, Beijing, China.  Read about Yunyao's [story from small-town China to Silicon Valley](https://www.cbronline.com/internet-of-things/cognitive-computing/small-town-china-silicon-valley-giant-amazing-story-one-ibm-researcher/) and follow her on Twitter @yunyao_li.*

**Laura Chiticariu**

*[Laura Chiticariu](https://www.linkedin.com/in/laura-chiticariu/) is the Chief Architect of Watson Knowledge and Language Foundation, with technical leadership responsibilities over Watson Natural Language Understanding, Watson Knowledge Studio and Watson Knowledge Graph. Laura is a core member of the [SystemT](http://researcher.watson.ibm.com/researcher/view_group.php?id=1264) R&D team, and strongly believes in the notion of `Transparent NLP`: leveraging machine learning techniques, while ensuring that the NLP system remains transparent - easy to comprehend, debug and enhance. She holds a Ph.D. in Computer Science, and has been teaching NLP across universities within and outside the U.S.*

**Marina Danilevsky**

*[Marina Danilevsky](https://www.linkedin.com/in/marina-danilevsky-a083b63/) is a Research Staff Member in the [Scalable Knowledge Intelligence](https://researcher.watson.ibm.com/researcher/view_group.php?id=9820) group at [IBM Almaden Research Center](http://www.research.ibm.com/labs/almaden/index.shtml) and a core member of the [SystemT](http://researcher.watson.ibm.com/researcher/view_group.php?id=1264) R&D team. She works in the intersection of data analytics, text mining, natural language processing, information networks, and human-computer interaction. She holds a Ph.D. in Computer Science from the [University of Illinois at Urbana-Champaign](http://www.cs.illinois.edu/) and a B.S. in [Mathematics](http://math.uchicago.edu/) from the [University of Chicago](https://www.uchicago.edu/).*

**Sanjana Sahayaraj**

*[Sanjana Sahayaraj](https://www.linkedin.com/in/sanjana-sahayaraj/) is a Software Developer in the [Scalable Knowledge Intelligence](https://researcher.watson.ibm.com/researcher/view_group.php?id=9820) group at [IBM Almaden Research Center](http://www.research.ibm.com/labs/almaden/index.shtml). Her current research interest is in Natural Language Processing. She completed her Masters in Computer Science from University of California, Santa Barbara and her Bachelors in Computer Science and Engineering from Anna University, Chennai, India. Connect with her on twitter [@Sanjana_1](https://twitter.com/Sanjana_1)*

**Teruki Tauchi**

*Teruki Tauchi is a front-end software developer of [IBM Watson Knowledge Studio](https://www.ibm.com/cloud/watson-knowledge-studio) at Tokyo Software & Systems Development Lab (TSDL), IBM Japan. He joined IBM after obtaining a Master of Engineering degree in Computer Science from University College London in 2015.*




