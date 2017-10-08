# DRAFT

# The WhatEvery1Says (WE1S) Project

## A Prospectus

### _――Alan Liu, Jeremy Douglass, Scott Kleinman, and Lindsay Thomas (October 1, 2017)_

## Table of Contents

* [I. Fact Sheet](#_Toc494665687)
  * [Participating Institutions](#_Toc494665688)
  * [Team](#_Toc494665689)
  * [Funding Support](#_Toc494665690)
  * [Timeline](#_Toc494665691)
  * [Main Humanities Research Goals](#_Toc494665692)
  * [Main Digital Humanities Goals](#_Toc494665693)
  * [Main Public Goals (addressed to the public or to humanities advocates addressing the public)](#_Toc494665694)
* [II. Description of Project](#_Toc494665695)
  * [a. Overview](#_Toc494665696)
  * [b. Humanities Context](#_Toc494665697)
  * [c. Digital Humanities Context](#_Toc494665698)
  * [d. Expected Audiences and Outcomes](#_Toc494665699)
  * [e. Research Methods](#_Toc494665700)
  * [f. Technical Methods](#_Toc494665701)
* [III. Plans for Expansion from Pilot Project](#_Toc494665702)
  * [a. Mellon-Funded Next Stage of Project](#_Toc494665703)
  * [b. Diversity and Inclusion](#_Toc494665705)
  * [c. Expected Outcomes and Benefits](#_Toc494665706)
* [IV. Works & Tools Cited](#_Toc494665707)

## <a id="_Toc494665687" name="_Toc494665687">I. Fact Sheet</a>

### <a id="_Toc494665688" name="_Toc494665688">Participating Institutions</a>

* University of California, Santa Barbara (UCSB)
* California State University, Northridge (CSUN) (subgrantee)
* University of Miami (UM) (subgrantee)

### <a id="_Toc494665689" name="_Toc494665689">Team</a>

* _Principal Investigator:_ Alan Liu (Professor of English, UCSB)
* _Co-PIs:_ Jeremy Douglass (Assistant Professor of English, UCSB), Scott Kleinman (Professor of English, CSUN), Lindsay Thomas (Assistant Professor of English, UM)
* _Other participating faculty:_ Mauro Carassai (CSUN)
* _Sustainability and Usability Adviser_ : Greg Janée (Director, Data Curation Program, UCSB Library; and Developer, UC Curation Center at California Digital Library)
* _[To be recruited:]_ Two Postdoctoral Scholars/Lecturers (postdoctoral researchers who also teach some courses each year) for project years 2018-2019 and 2019-2020
* _[To be recruited:]_ Graduate student project managers
* _[To be recruited:]_ Graduate student and undergraduate research assistants, including those participating in WE1S’s “summer research camps”

### <a id="_Toc494665690" name="_Toc494665690">Funding Support</a>

* The Andrew W. Mellon Foundation, $1.1 million
* Additional support from UCSB in the form of additional salaries and benefits for the hybrid postdoc/lecturer positions and for the graduate-student project manager at UCSB.

### <a id="_Toc494665691" name="_Toc494665691">Timeline</a>

* Three years, October 1, 2017 to September 30, 2020.

### <a id="_Toc494665692" name="_Toc494665692">Main Humanities Research Goals</a>

* Use digital-humanities computational methods to study public discourse on the humanities in journalistic media and other sources at large data scales. Model the main themes, frames of discussion, and narratives (even “memes”) of such discourse; the relations between them; and also unexpected themes or relations. For example, how do journalists, politicians, business people, scientists, parents, students, university administrators, professors, writers, artists, and others typically talk about the humanities? How do the national and local, or policy and personal facets of “what everyone says” about the humanities intersect with each other (for example, when a legislator discusses education policy, or a parent or teacher discusses the future with a student)?
* Study how public discourse on the humanities compares across states, nations, and regions of the world. To begin with, how much talk about the humanities is there in the media in California as opposed to in New York, in the U.S. by contrast with the U.K., and in the North and West of the world by comparison with the southern hemisphere or mid and far east?
* Study the way racial, ethnic, gender, and other groups are positioned by the media, or position themselves in the media, in relation to the humanities versus more “practical” career choices, especially during first-generation immigrant or first-generation-to-college phases of a group’s social trajectory. Just one line of inquiry going beyond the stereotypes: if a first-generation immigrant student is told by parents and society to major in science, engineering, pre-medicine, pre-law, or pre-business; yet the cultural and personal identity of that student is vested in a deep humanities and arts heritage; then where does that excess “humanity” go and how is it expressed and cultivated?

### <a id="_Toc494665693" name="_Toc494665693">Main Digital Humanities Goals</a>

* Design and assemble a representative corpus (in this case, of public discourse on the humanities) with attention to principles of corpus “representativeness.”
* Advance methods for open, reproducible data workflow in the digital humanities, including methods for
  * tracking the provenance and workflow of sources, tools, and processes;
  * implementing workflows of data collection, preparation, analysis, and output workflows in chained series of executable (but customizable) data “notebooks” (Jupyter notebooks).
* Advance the sustainability of digital humanities workflows and outputs by using “containerized” (virtualized) data analysis platforms that can be distributed and be deposited in institutional or other repositories.

### <a id="_Toc494665694" name="_Toc494665694">Main Public Goals (addressed to the public or to humanities advocates addressing the public)</a>

* Provide a richer stock of themes, narratives, examples, and evidence types that can be drawn upon in discussing the humanities, whether at the policy level (e.g., how society should apportion investment in STEM versus humanities education) or at the individual or social level (e.g., how parents and students talk to each other about what life or career is about).
* Provide recommendations for humanities advocacy in the form of executive summaries addressed to different sectors of the public (journalists, politicians, business leaders, parents, students) and best-practices advice (e.g., avoiding untrue or overused themes in public discussion of the humanities, and drawing connections between the humanities and themes of interest to the public).
* Provide resource “kits” of themes, examples, and evidence for journalists, scholars, and administrators to draw on in discussing the humanities; or for students to draw on as they consider choosing a major and discussing it with parents.

## <a id="_Toc494665695" name="_Toc494665695">II. Description of Project</a>

### <a id="_Toc494665696" name="_Toc494665696">a. Overview</a>

Based at University of California, Santa Barbara (UCSB), with core collaborators at California State University, Northridge (CSUN) and University of Miami (UM), the “WhatEvery1Says” project (WE1S) uses digital humanities (DH) methods to study public discourse about the humanities at large data scales. The project concentrates on, but is not limited to, journalistic articles available in digital textual form beginning circa 1981. Previously engaged in a small-scale pilot project for this purpose, WE1S was in 2017 awarded Mellon Foundation funding of $1.1 million on a timeline of three years (beginning October 1, 2017) to expand significantly the scope and diversity of its sampled materials; to increase the range, nuance, and trustworthiness of its analytical methods; and to make its technical research environment agile enough to support rapid, flexible exploration of new materials and research questions. WE1S’s parent initiative is [4Humanities.org](http://4humanities.org/), which Principal Investigator Alan Liu (UCSB) started in 2010 with international collaborators to use digital technologies for humanities advocacy.

### <a id="_Toc494665697" name="_Toc494665697">b. Humanities Context</a>

WE1S contributes to recent research responding to the perceived long-term decline of the humanities, including after the most recent “crisis” period touched off by the Great Recession of the late 2000s and early 2010s. Such research has been broad and vigorous. For example, many scholars have written books on the value and history of the humanities [<sup>1</sup>](#ftn1); the [Society for the History of the Humanities](http://www.historyofhumanities.org/) has started the History of Humanities journal to publish new historical and comparative research on the humanities; the innovative Humanities & Liberal Arts Assessment (HULA)](http://www.pz.harvard.edu/projects/humanities-liberal-arts-assessment-hula) project has studied and assessed the “implicit internal logics of humanistic craft” in order to surface the methods and values of the humanities; major scholarly associations and foundations have issued reports, white papers, and policy recommendations [<sup>2</sup>]("ftn2"); the American Academy of Arts & Science has created [Humanities Indicators](http://www.humanitiesindicators.org/) and [Academy Data Forum](https://www.amacad.org/content/research/dataForumList.aspx) to gather significant statistics; and “public humanities” initiatives and humanities advocacy initiatives have been active in communicating the value of the humanities to the public and its representatives in government and the media (_for examples of all of the above see section III, Works Cited_).

WE1S adds uniquely to this broader field of research and advocacy by using digital humanities methods―mainly topic modeling―to analyze representations of the humanities in large numbers of public materials, especially journalistic media. If the Humanities Indicators project provides statistical research on the state of the humanities, WE1S provides the other half of the picture: discourse research on how the humanities are articulated in public and at crossover points between the public and the academy.

### <a id="_Toc494665698" name="_Toc494665698">c. Digital Humanities Context</a>

As a digital humanities project, WE1S also contributes to the evolving context and methods of the digital humanities field in three ways:

* WE1S takes its place in the evolving branch of the digital humanities called “cultural analytics,” which brings into convergence “distant reading,” text analysis, topic modeling, and other data-analytic methods to study sociocultural, historical, and aesthetic phenomena at collectively significant scales.
* Technologically, WE1S contributes to the development of integrated frameworks for data-analysis workflow by creating an adaptable data workflow system that draws on the principles of more complex digital humanities and scientific workflow systems but streamlines them (and translates the idea of “data provenance” in scientific workflow into that of “document” provenance). This creates a data-analysis workflow system that is more usable and intellectually graspable for a larger number of digital humanities scholars.
* Additionally, WE1S contributes to the development of open, shareable, and reproducible methods in the digital humanities. <a name="_ftn2"></a>Because WE1S’s Workflow Management System and Virtual Workspace System not only implement workflows but do so in open, annotated ways (creating provenance “manifests” using JSON and operating on them using open-science Jupyter notebooks),[<sup>3</sup>](#ftn3) they introduce to the digital humanities the kind of workflow systems based on metadata standards that the _in silico_ or data-intensive sciences have advanced under the rubrics of “open science” and “open lab.”

### <a id="_Toc494665699" name="_Toc494665699">d. Expected Audiences and Outcomes</a>

WE1S aims for its research and methods to serve three overlapping audiences in the following ways:

<a name="_ftn3"></a>
_i. For the public_, WE1S will provide research-based examples and analyses of themes, narratives, metaphors, evidence, and value statements about the humanities, together with links to readings in the original journalistic material. In addition, WE1S will create resources and recommendations to help guide discussion about the humanities by journalists, politicians, business people, university administrators, parents, and students.

_ii. For humanities scholars and administrators_, WE1S will provide articles, white papers, open metadata, interpreted results, and research workflows and tools representing its project. These can be used for study in such research areas as: university studies; the idea and value of the humanities; the history of the humanities; and “global” or comparative humanities. More broadly, the project will provide methods and tools for humanities researchers investigating the role of complex ideas in society.

_iii. For digital humanities scholars_, WE1S will contribute methods and tools (to be used either “as is” or in adapted form) for integrated, open, shareable, and reproducible data analysis and interpretation.

### <a id="_Toc494665700" name="_Toc494665700">e. Research Methods</a>

WE1S’s research starts with identifying and harvesting for analysis documents from journalistic sources (and in the future other sources in the public sphere) that include the phrases “humanities,” “liberal arts,” and (in the United Kingdom and Commonwealth nations, “the arts”). Text is “scraped” in plain-text form, “cleaned” and subjected to other pre-processing methods, and then converted into analytical data for machine learning processes such as topic modeling. To allow for null hypothesis testing, WE1S also gathers from its sources analytical data for a smaller “random” corpus of articles.

The main computational method that WE1S applies to analyze its gathered materials is topic modeling (specifically, Latent Dirichlet Allocation [LDA] topic modeling as implemented in the standard MALLET toolkit [Machine Learning for Language Toolkit]). A leading method of machine-learning analysis, topic modeling discovers through statistical means the existence, relative weight, and distribution of “topics” across documents (where topics are represented as a probability model of correlated words often indicative of what a human might conceive as “themes”). Topic modeling can be particularly important for discovering areas of public discourse related to the humanities that are not colored by preconceived theses or expectations (e.g., about the “crisis” of the humanities).[<sup>4</sup>](#ftn4) Facilitating the interpretive exploration of topic models is WE1S’s use of the [dfr-browser](https://agoldst.github.io/dfr-browser/) topic-model visualization interface developed by Andrew Goldstone, which was chosen as optimal after WE1S conducted a comparative study of 14 topic-model interfaces.[<sup>5</sup>](#ftn5)

In addition, WE1S will explore “word embedding” (word2vec) and text-classification analytical methods that have the potential to use the project’s collected data in ways that augment topic modeling.

### <a id="_Toc494665701" name="_Toc494665701">f. Technical Methods</a>

WE1S has developed a technical environment that implements its research through methods for (1) corpus assembly and preparation; (2) data provenance and workflow management; and (3) the integrated, containerized operation of workflows (including topic modeling and visualization of results). It is also developing (4) a protocol for interpreting topic models that lays out in declared form the iterative steps of interaction between human interpreters and machine-learning results. While particular features of this technical environment are specifically customized for WE1S, the overall paradigm is generalizable to many other digital humanities projects and can be implemented either “as is” through WE1S’s open-source methods and tools or by adapting these.

In detail, the elements of the WE1S technical environment in its beta form are as follows:

#### 1. Corpus Assembly and Preparation System

WE1S collects as plain text the materials from its journalistic sources via databases or directly through the APIs of source publications. In the case of databases, it does so by first using manual means for searching and downloading (as dictated by licensing conditions), and secondly using automated means for scraping (as plain text), cleaning, and other pre-processing of downloaded documents into “bags-of-words” analytical data. The cleaning, pre-processing, and conversion of plain texts into bags of words occurs in the project’s Virtual Workspace System and in a secure annex of that system, which then also mounts all or various parts of the WE1S dataset for topic modeling (and also de-duplicates material such as data from articles collected twice because they contain both “humanities” and “liberal arts,” which WE1S searches on separately).

#### 2. Manifest Framework

Digital humanities researchers working with large data sets or iterative processes have in the past adopted localized, ad hoc means for keeping track of their data, processing steps, and results―an approach that impedes collaborative work, makes repeating or adjusting research processes difficult, and does not support emerging publication standards for transparent data provenance and reproducible research.

WE1S addresses these issues through a “manifest framework” that documents the components and relations between different parts of a digital humanities research workflow―including data collection, pre-processing (e.g., cleaning), analysis, and presentation (e.g., visualizations). The WE1S manifest framework consists of a generalizable method for annotating data provenance and workflow declared through schema-based documents known as “manifests”:

* A manifest is a plain-text file formatted in the JSON serialization format (organizing information into keyword-value pairs) for describing a resource or process. Manifests can be created in a simple text editor, and they can also be written in other formats such as XML or YAML, and can be converted to JSON (or vice versa) as appropriate to particular projects.
* Manifests conform to the WE1S manifest “schema” (a definition of the terms and logic needed for tracking WE1S resources and processes that is currently in a version 1.0 state).[<sup>6</sup>](#ftn6) The WE1S schema is encoded using the [JSON Schema](http://json-schema.org/documentation.html) and can be expanded and customized based on the needs of other types of projects.
* The WE1S manifest framework shares much in common with other metadata standards and workflow management tools deployed in the sciences and other fields (such as the W3C’s[PROV](https://www.w3.org/TR/prov-overview/) Ontology and the [Open Science Framework](https://osf.io/)). But for use in the humanities it is designed specifically around a schema suited to the kinds of materials and processes typical of humanities research and also requires relatively little technical overhead.

#### 3. Workflow Management System

The Workflow Management System is a Web-based platform for creating and managing manifest documents. It allows researchers at various levels of technical proficiency to create valid manifests by filling in forms in their browser. Users enter manifest information required by the WE1S schema in Web-based forms. Alternatively, the platform can import manifests to the database from pre-existing manifest documents. The Workflow Management System is particularly important for newcomers to the WE1S project (e.g., new research assistants) who may not be familiar enough with the WE1S schema to create valid manifests from scratch. It also provides the ability to search the project’s stored manifests, which will become the basis for part of the public-facing Web site at the end of the project.

#### 4. Virtual Workspace System

To address a range of computing demands from a geographically distributed team with varying technical skills and different workstations, WE1S has created a Virtual Workspace System that facilitates open, reproducible digital humanities research through a defined computing platform, a shareable online environment, integrated customizable workflows, and on-demand online presentation of results. The WE1S Virtual Workspace System runs through the Web as well as locally on a laptop; its design and implementation can be used by other digital humanities projects; and it is consonant with the philosophy of such other online or containerized integrated systems as [Lexos](http://lexos.wheatoncollege.edu/) or [DH Box](http://dhbox.org/) that make advanced digital humanities research environments accessible.

The WE1S Virtual Workspace System is a virtual environment (runnable online from a server or as a “containerized” virtual computer on a local workstation) that implements a computing platform and a directed series of workflows. Data workflows include those for cleaning and pre-processing texts; converting texts into non-consumptive use “bags of words”; selecting parts of the WE1S dataset to analyze; generating topic models; and outputting results. These workflows are implemented using [Jupyter notebooks](http://jupyter.org/) (previously known as “iPython notebooks”), which both document processing steps and run actual code in step-by-step modules. Each new project begins by generating a new project folder containing a copy of a chained set of default notebooks. The project can then be customized. The final Jupyter notebook in the WE1S Virtual Workspace System generates an on-the-fly Web site showing a dynamic, interactive view of a topic model in Andrew Goldstone’s [dfr-browser](https://agoldst.github.io/dfr-browser/) interface. This Web site can be automatically and iteratively recreated whenever the underlying data workflow is changed (e.g., when a workflow is repeated using different parts of the corpus or different topic-modeling parameters).

#### 5. Interpretation Protocol for Topic Models

Because complex data-analysis sequences can have a “black box” effect, one of the needs of current _in silico_ science is not just to document technical workflows for reproducibility but also to make humanly understandable the steps in a workflow. The goal is to facilitate the interpretation of results.[<sup>7</sup>](#ftn7) Digital humanities research, of course, is rooted not just in data science but also long-standing traditions of humanistic hermeneutics, including the critical scrutiny of how humans “read” and “interpret” materials. Digital humanists thus carry the extra burden of needing to make visible the machine-to-human and human-to-human interpretive steps hidden in the interpretive process, steps involving how researchers read a topic model and how researchers communicate, discuss, and provide evidence for observations about topic models to reach credible conclusions. Yet there are currently no best practices in the digital humanities for explaining data workflow, let alone with attention to the act of human interpretation.

As part of its technical methods, WE1S is developing a topic-model interpretation protocol that declares in understandable form (as part of a manifest workflow) step-by-step interactions between machine learning and researcher interpretation/collaboration (e.g., when in the process researchers convene to interpret a topic model; what outputs, visualizations, and secondary algorithmic products such as Principal Component Analysis or hierarchical clusterings are used to deduce groups of topics; how researchers discuss a topic model; and how topic models and interpretive acts are iterated). The goal is not to assert _the_ definitive topic-model interpretation process (because this will be different depending on the nature of a project, its materials, and its personnel), but to declare _a_ topic model interpretation process that can then serve as a model and be adapted, improved, and varied by the larger DH community. It may be that over time one or several kinds of digital-humanities data interpretation protocols will evolve as shared conventions.

While still in progress, the WE1S topic-model interpretation protocol is currently drafted to specify a sequence of interpretive steps. These steps will eventually be documented in JSON-formatted manifests according to the WE1S manifest framework. This will allow for provenance tracking of interpretation workflows, the sharing of such workflows with other projects, and the automation of steps that facilitate interpretation―e.g., allowing the WE1S Virtual Workspace System to generate visualization aids at appropriate moments as the interpretation process unfolds).

## <a id="_Toc494665702" name="_Toc494665702"></a><a id="_1op6umco4s0o" name="_1op6umco4s0o"></a>III. Plans for Expansion from Pilot Project

### <a id="_Toc494665703" name="_Toc494665703"></a><a id="_go2s2tyl0rfl" name="_go2s2tyl0rfl"></a>a. Mellon-Funded Next Stage of Project

WE1S has operated since 2013 as a pilot project. With funding from the Mellon Foundation, WE1S will greatly extend the scope and diversity of its sampled materials from public discourse; improve its research methods and technical implementation to enable more rapid and more flexible exploration of these materials; and produce analyses and other outcomes for its intended public, humanities, and digital humanities audiences.

### <a id="_Toc494665705" name="_Toc494665705"></a>b. Diversity and Inclusion

i. In light of its theme, WE1S primarily understands diversity and inclusion to refer to facilitating the ability of underrepresented racial/ethnic groups―and also first-generation-to-college, immigrants, and others―to embrace the humanities in common with others so as to contribute to the full life of individuals, groups, educational and cultural institutions, and, ultimately, society. A core mission of WE1S’s plan for expanded research, therefore, is to acquire materials that facilitate understanding the complex relationship of underrepresented and other groups to the humanities. The aim is to position WE1S to ask such questions as: how do mainstream media position students and others from particular groups relative to the humanities? How do media articles addressed specifically to such groups compare with mainstream media? In what ways does public opinion about the very ideal of “diversity and inclusion” correlate with public opinion about the humanities?

ii. Secondarily, WE1S understands diversity and inclusion to refer to facilitating the participation of underrepresented students (and also students such as Asian-Americans underrepresented in the humanities, as well as women underrepresented in technology) in its own project. Because WE1S engages in interdisciplinary humanities/technology research with a strong focus on social issues, an appropriate diversity aim is to include underrepresented students from many fields (humanities, STEM, and social science) in its research as part of their educational training. At UCSB, these summer research camps will be advertised to graduate-student research assistants from diverse student bases, including not just programs with strengths in the digital humanities but also in areas such as ethnic and gender studies bearing on the diversity aspect of WE1S’s research aims. At CSUN, a particularly important WE1S initiative is to create Summer Research Camps that parallel those held at UCSB but also work to increase campus expertise in the digital humanities, including among its diverse student population. To this end, the CSUN camps will also directly involve undergraduates.

### <a id="_Toc494665706" name="_Toc494665706">c. Expected Outcomes and Benefits</a>

#### Expected Outcomes

Outcomes at the close of the WE1S project timeline will include a public-facing Web site presenting:

1. An overview description and rationale statement for the project.
1. A scoping statement of the materials collected and studied.
1. Topic models presented in a dynamic, interactive interface (based on dfr-browser) designed to encourage users to explore topics and read exemplary source articles.
1. Analyses and reports on what the project’s research brings to view about public discourse on the humanities.
1. Recommendations for humanities advocacy in the form, for example, of executive summaries addressed to different sectors of the public (journalists, politicians, business leaders, parents, students) and best-practices advice (e.g., avoiding untrue or overused themes in public discussion of the humanities, and drawing connections between the humanities and themes of interest to the public).
1. Resource “kits” of themes, examples, and evidence for journalists or scholars and administrators to draw on in discussing the humanities; or students to draw on as they consider choosing a major and discussing it with parents.
1. GitHub and institutional repositories containing WE1S technical systems (its manifest framework, Workflow Management System, Virtual Workspace System, and topic modeling interpretation protocol).

#### Expected Benefits

For its overlapping audiences of the public, humanities scholars and administrators, and digital humanists, the benefit that frames all subsidiary ones will be to use research-based knowledge to advance a more expansive notion of humanities advocacy―one geared toward not just humanities disciplines, scholars, and students, but the larger public.

Specific, concrete benefits for WE1S’s audiences include:

* _For various sectors and professions among the public_, WE1S will provide a richer stock of themes, narratives, examples, and evidence types that can be drawn upon in discussing humanities-related issues, whether at the policy level or at the individual or social level. WE1S will also help widen the social and cultural diversity of public discourse on the humanities, bringing into consideration not just the generic “student” or “major” referred to in many media stories but also students whose specific racial, ethnic, gender, immigrant, and generational backgrounds positions them differently in the field of such discussions. Equally beneficial will be the context in which WE1S frames this richer, more diverse mix of views on the humanities through its description and rationale statement, scoping statement, and analyses and recommendations.
* _For humanities scholars and administrators_, WE1S’s outcomes will not only facilitate their own participation in humanities advocacy (by widening and enriching the discourse of such advocacy in the ways described above) but also augment specific research, program-building and administrative, and public outreach missions. The project’s methods and tools will serve as a paradigm (and can be used “as is” or in adapted form) for researching the way other complex ideas that are like “the humanities” in having both narrow/sharply defined and broad/fuzzy senses behave in public discourse. WE1S will be able to assist in such activities as designing general education curricula, shaping agendas for humanities centers, or presenting a matriculation or commencement speech―all of which can benefit from WE1S’s research-backed identification of themes and the relations between themes. WE1S will provide an extended, enriched range of themes, arguments, examples, and other material to draw on in framing advocacy efforts on behalf of funding for the humanities, bringing new students into humanities majors, and showing the connection of the humanities to other educational fields and to other areas of social concern.
* _For the digital humanities research community_, WE1S will provide a paradigm of open, shareable, and reproducible research adapted for the kinds of provenance tracking, analysis workflows, and self-reflective attention to interpretive method characteristic of humanities-oriented “cultural analytics.” The WE1S manifest framework, Workflow Management System, Virtual Workspace System, and topic model interpretation protocol will be disseminated so that they can be used or adapted by other projects.

## <a id="_Toc494665707" name="_Toc494665707">IV. Works & Tools Cited</a>

4Humanities.org. Home page. Accessed April 18, 2017. [http://4humanities.org](http://4humanities.org/).

__________, “The Heart of the Matter Topic-Modeled (A Preliminary Experiment).” November 2, 2013. Accessed April 20, 2017. [http://4humanities.org/2013/11/the-heart-of-the-matter-topic-modeled-a-preliminary-experiment/](http://4humanities.org/2013/11/the-heart-of-the-matter-topic-modeled-a-preliminary-experiment/).

__________. “What U.S. Politicians Say About the Humanities―A Data Set and Analysis.” March 1, 2016. Accessed April 20, 2017. [http://4humanities.org/4humanities-research-projects/what-u-s-politicians-say-about-the-humanities/](http://4humanities.org/4humanities-research-projects/what-u-s-politicians-say-about-the-humanities/).

4Humanities.org. WhatEvery1Says (WE1S) Project. (See under WE1S.)

Academy Data Forum. Home page, 2017. American Academy of Arts and Sciences. Accessed April 19, 2017. [https://www.amacad.org/content/research/dataForumList.aspx](https://www.amacad.org/content/research/dataForumList.aspx).

Allen, Danielle, Chris Pupik Dean, Sheena Kang, and Maggie Schein. “Humanities Craftsmanship: A Study of 30 Years of Illinois Humanities Council Grant-making―A Report by the HULA Team. The Humanities and Liberal Arts Assessment Research Project, February 9, 2015. Accessed April 19, 2017. [http://www.pz.harvard.edu/resources/humanities-craftsmanship-a-study-of-30-years-of-illinois-humanities-council-grant-making](http://www.pz.harvard.edu/resources/humanities-craftsmanship-a-study-of-30-years-of-illinois-humanities-council-grant-making).

Allison, Sarah. “Other People’s Data: Humanities Edition.” _Cultural Analytics_, December 8, 2016. Accessed April 20, 2017. [http://culturalanalytics.org/2016/12/other-peoples-data-humanities-edition/](http://culturalanalytics.org/2016/12/other-peoples-data-humanities-edition/).

American Academy of Arts and Sciences Commission on the Humanities and Social Sciences. _The Heart of the Matter: The Humanities and Social Sciences for a Vibrant, Competitive, and Secure Nation_. Cambridge, MA: American Academy of Arts and Sciences, 2013. Accessed April 19, 2017. [http://www.humanitiescommission.org/_pdf/hss_report.pdf](http://www.humanitiescommission.org/_pdf/hss_report.pdf).

Apache Taverna (Taverna Workflow System). Home page. Apache Software Foundation, 2014-2016. Accessed February 2, 2017. [https://taverna.incubator.apache.org/](https://taverna.incubator.apache.org/).

Association of American Universities (AAU). Home page. Accessed April 21, 2017. [https://www.aau.edu/](https://www.aau.edu/).

Bate, Jonathan. _The Public Value of the Humanities_. London: Bloomsbury, 2011.

Belfiore, Eleonora, and Anna Upchurch, ed. _Humanities in the Twenty-First Century: Beyond Utility and Markets_. Basingstoke: Palgrave McMillan, 2013.

Blei, David M. “Probabilistic Topic Models.” _Communications of the ACM_ 55.4 (April 2012): 77-84. [doi: 10.1145/2133806.2133826](http://dl.acm.org/citation.cfm?id=2133826).

Bod, Rens. _A New History of the Humanities: The Search for Principles and Patterns from Antiquity to the Present_. Oxford University Press, 2013.

de Bolla, Peter. _The Architecture of Concepts: The Historical Formation of Human Rights_. New York: Fordham University Press, 2013.

California State University, Northridge (CSUN). “Diversity Initiatives at California State University Northridge.” N. d. Accessed April 21, 2017. [http://www.csun.edu/sites/default/files/CSUN%20Diversity%20Initiatives.pdf](http://www.csun.edu/sites/default/files/CSUN%20Diversity%20Initiatives.pdf).

__________. HSI Pathways to the Professoriate. Home page, n. d. Accessed April 21, 2017. [http://www.csun.edu/humanities/pathways-professoriate](http://www.csun.edu/humanities/pathways-professoriate).

Chronicling America: Historic American Newspapers. Home page, n. d. Library of Congress. Accessed April 20, 2017. [http://chroniclingamerica.loc.gov/](http://chroniclingamerica.loc.gov/).

Clawson, James. “Who’s Afraid of Topic Modeling? Proposing a Collaborative Workflow (with Virginia Woolf).” jmclawson.com. Accessed April 20, 2017. [http://jmclawson.com/topickit/Chicago-pdf.pdf](http://jmclawson.com/topickit/Chicago-pdf.pdf).

Congress.gov. Home page, n. d. Library of Congress. Accessed April 20, 2017. [https://www.congress.gov/](https://www.congress.gov/).

_Cultural Analytics_ (journal). “About CA.” Accessed March 20, 2017. [http://culturalanalytics.org/about/about-ca/](http://culturalanalytics.org/about/about-ca/).

dfr-browser. (See Goldstone, Andrew.)

Docker. Home page, 2017. Docker, Inc. Accessed April 30, 2017. [https://www.docker.com/](https://www.docker.com/).

Fedora. Home page, n. d. DuraSpace. Accessed April 30, 2017. [http://fedorarepository.org/](http://fedorarepository.org/).

Goldstone, Andrew. dfr-browser, v. 0.8a. Home page, June 8, 2016. Accessed March 22, 2017. [http://agoldst.github.io/dfr-browser/](http://agoldst.github.io/dfr-browser/).

Harpham, Geoffrey Galt. _The Humanities and the Dream of America_. Chicago: University of Chicago Press, 2011.

HathiTrust Digital Library. “Non-Consumptive Use Research Policy.” February 20, 2017. Accessed May 27, 2017. [https://www.hathitrust.org/htrc_ncup](https://www.hathitrust.org/htrc_ncup).

Hispanic Association of Colleges and Universities (HACU). “HACU Member Hispanic-Serving Institutions (HSIs).” N. d. Accessed April 21, 2017. [https://www.hacu.net/assnfe/CompanyDirectory.asp?STYLE=2&COMPANY_TYPE=1%2C5](https://www.hacu.net/assnfe/CompanyDirectory.asp?STYLE=2&COMPANY_TYPE=1%2C5).

__________. “Hispanic-Serving Institution Definitions.” N. d. Accessed April 21, 2017. [http://www.hacu.net/hacu/HSI_Definition.asp](http://www.hacu.net/hacu/HSI_Definition.asp).

Hispanic Serving Institutions (HSI). See above under Hispanic Association of Colleges and Universities (HACU), “HACU Member Hispanic-Serving Institutions (HSIs)” and “Hispanic-Serving Institution Definitions.”

_History of Humanities_ (journal). Edited by Rens Bod, Julia Kursell, Jaap Maat, Thijs Weststeijn. University of Chicago Press. Available online at: [http://www.journals.uchicago.edu/toc/hoh/current](http://www.journals.uchicago.edu/toc/hoh/current).

HathiTrust Research Center. Home page, n. d. Accessed April 18, 2017. [https://analytics.hathitrust.org/](https://analytics.hathitrust.org/).

Humanities and Liberal Arts Assessment Project (HULA). Home page, 2016. Harvard Graduate School of Education. Accessed April 19, 2017. [http://www.pz.harvard.edu/projects/humanities-liberal-arts-assessment-hula](http://www.pz.harvard.edu/projects/humanities-liberal-arts-assessment-hula).

Humanities Commons. Home page, 2016. Accessed April 30, 2017. [https://hcommons.org/](https://hcommons.org/).

Humanities Indicators. Home page, 2016. American Academy of Arts and Sciences. Accessed April 18, 2017. [http://www.humanitiesindicators.org/](http://www.humanitiesindicators.org/).

Hutner, Gordon, and Feisal G. Mohamed, ed. _A New Deal for the Humanities: Liberal Arts and the Future of Public Higher Education_. New Brunswick, NJ: Rutgers University Press, 2016.

Hypothes.is. Home page, n. d. Accessed April 20, 2017. [https://hypothes.is/](https://hypothes.is/).

Gil, Yolanda, and Daniel Garijo. “Towards Automating Data Narratives.” _Proceedings of the Twenty-Second ACM International Conference on Intelligent User Interfaces, Limassol, Cyprus, February 2017_. ACM, 2017. [doi: 10.1145/3025171.3025193](http://dx.doi.org/10.1145/3025171.3025193).

GitHub. Home page. Github, Inc., 2017. Accessed January 30, 2017. [https://github.com/](https://github.com/).

International Image Interoperability Framework (IIIF). Home page, n. d. Accessed April 19, 2017. [http://iiif.io/#plug-%E2%80%99n%E2%80%99-play-software](http://iiif.io/#plug-%E2%80%99n%E2%80%99-play-software).

JSTOR. Home page, n. d. ITHAKA. Accessed April 20, 2017. [https://www.jstor.org/](https://www.jstor.org/).

JSTOR Text Analyzer, beta version. Home page, n. d. JSTOR / ITHAKA. Accessed April 20, 2017. [https://www.jstor.org/analyze/](https://www.jstor.org/analyze/).

Jupyter Notebooks. (See Project Jupyter.)

Kabaservice, Geoffrey. “The Birth of a New Institution: How Two Yale presidents and Their Admissions Directors Tore Up the “Old Blueprint” to Create a Modern Yale.” Yale Alumni Magazine, December 1999. [http://archives.yalealumnimagazine.com/issues/99_12/admissions.html](http://archives.yalealumnimagazine.com/issues/99_12/admissions.html).

Kepler [computer software], v. 2.5. Home page. N. d. Accessed February 2, 2017. [https://kepler-project.org/](https://kepler-project.org/).

Lexomics Project. Home page, n. d. Wheaton College. Accessed April 20, 2017. [http://wheatoncollege.edu/lexomics/](http://wheatoncollege.edu/lexomics/).

Lexos, v. 3.0. Home page. Lexomics Research Group, Wheaton College. Accessed January 14, 2017. [http://lexos.wheatoncollege.edu/](http://lexos.wheatoncollege.edu/).

MALLET (Machine learning for Language Toolkit). (See McCallum, Andrew Kachites.)

McCallum, Andrew Kachites. MALLET (Machine Learning for Language Toolkit). Home page, 2002. Accessed May 28, 2017. [http://mallet.cs.umass.edu](http://mallet.cs.umass.edu/).

Mathae, Katherine Bailey, and Catherine Langrehr Birzer, ed. _Reinvigorating the Humanities: Enhancing Research and Education on Campus and Beyond_. New York/Washington, D. C.: American Association of Universities, 2004. Accessed April 19, 2017. [https://eric.ed.gov/?id=ED505820](https://eric.ed.gov/?id=ED505820).

Meandre. Home page, n. d. Accessed April 18, 2017. [http://www.seasr.org/meandre/](http://www.seasr.org/meandre/).

Mohr, John, and Petko Bogdanov. “Introduction–Topic Models: What They Are and Why They Matter.” _Poetics_ 41.6 (2013): 545-769. Accessed April 18, 2017. [http://www.sciencedirect.com/science/article/pii/S0304422X13000685](http://www.sciencedirect.com/science/article/pii/S0304422X13000685).

National Humanities Alliance. Home page, 2015. Accessed April 19, 2017. [http://www.nhalliance.org/](http://www.nhalliance.org/).

_New York Times_. “Top Colleges Doing the Most for the American Dream.” May 25, 2017. Accessed June 4, 2017. [https://www.nytimes.com/interactive/2017/05/25/sunday-review/opinion-pell-table.html](https://www.nytimes.com/interactive/2017/05/25/sunday-review/opinion-pell-table.html).

Nussbaum, Martha C. _Not for Profit: Why Democracy Needs the Humanities_. Princeton, NJ: Princeton University Press, 2016.

Open Science Framework. Home page, n. d. Center for Open Science. Accessed April 19, 2017. [https://osf.io/](https://osf.io/).

Project Jupyter (Jupyter Notebooks). Home page, April 13, 2017. Accessed April 19, 2017. [http://jupyter.org/](http://jupyter.org/).

ProQuest. Content databases including (in various overlapping packagings) News & Newspapers, Historical Newspapers, Ethnic NewsWatch, Black Newspapers, U.S. Hispanic Newsstand, and GenderWatch accessible through institutional subscriptionSee Proquest, “News & Newspapers,” n. d. Accessed April 20, 2017. [http://www.proquest.com/libraries/academic/news-newspapers/](http://www.proquest.com/libraries/academic/news-newspapers/).

PROV. (See W3C [World Wide Web Consortium]. “PROV-Overview.” April 30, 2013. Accessed February 2, 2017. [https://www.w3.org/TR/prov-overview/](https://www.w3.org/TR/prov-overview/).)

R-Shief. Home page, 2016. Accessed September 11, 2016. [http://r-shief.org/](http://r-shief.org/).

Rockwell, Geoffrey. “2016 Chicago Colloquium on Digital Humanities and Computer Science” (notes on the conference). _philosophi.ca_ (blog). Accessed April 20, 2017. [http://philosophi.ca/pmwiki.php/Main/2016ChicagoColloquiumOnDigitalHumanitiesAndComputerScience](http://philosophi.ca/pmwiki.php/Main/2016ChicagoColloquiumOnDigitalHumanitiesAndComputerScience).

Schiffrin, Anya, and Ethan Zuckerman. “Can We Measure Media Impact? Surveying the Field.” _Stanford Social Innovation Review_, Fall 2015. Accessed June 1, 2017. [https://ssir.org/articles/entry/can_we_measure_media_impact_surveying_the_field](https://ssir.org/articles/entry/can_we_measure_media_impact_surveying_the_field).

SEASR (Software Environment for the Advancement of Scholarly Research). Home page, n. d. Accessed April 18, 2017. [http://www.seasr.org/](http://www.seasr.org/).

Small, Helen. _The Value of the Humanities_. Oxford: Oxford University Press, 2013.

Smith, Sidonie Ann. _Manifesto for the Humanities: Transforming Doctoral Education in Good Enough Times_. Ann Arbor: University of Michigan Press, 2016.

Society for the History of the Humanities. Home page, 2017.Accessed April 19, 2017. [http://www.historyofhumanities.org/](http://www.historyofhumanities.org/).

Sunlight Foundation. Home page, n. d. Accessed April 20, 2017. [https://sunlightfoundation.com/](https://sunlightfoundation.com/).

Text Encoding Initiative (TEI). Home page, July 19, 2016. Accessed April 19, 2017. [http://www.tei-c.org/index.xml](http://www.tei-c.org/index.xml).

Ubois, Smiljana Antonijievic, and Ellysa Stern Cahoy. “Supporting Humanists’ Digital Workflow.” (See notes on talk by Rockwell.)

Underwood, Ted. “Topic Modeling Made Just Simple Enough.” _The Stone and the Shell_ (blog), April 7, 2012. Accessed February 15, 2017. [http://tedunderwood.com/2012/04/07/topic-modeling-made-just-simple-enough/](http://tedunderwood.com/2012/04/07/topic-modeling-made-just-simple-enough/).

University of Miami. _Fact Book 2016-17 (Fall 2016 Fact Book)_. 2017. University of Miami. Accessed April 21, 2017. [http://www.miami.edu/index.php/Fact_Book_2016-2017](http://www.miami.edu/index.php/Fact_Book_2016-2017).

U.S. Department of Education. “Developing Hispanic-Serving Institutions Program - Title V.” N. d. Accessed April 21, 2017. [https://ed.gov/programs/idueshsi/index.html?src=rt](https://ed.gov/programs/idueshsi/index.html?src=rt).

U.S. Government Publishing Office. Home page, n. d. Accessed April 20, 2017. [https://www.gpo.gov/](https://www.gpo.gov/).

WE1S (WhatEvery1Says). Home page, 2017. [http://we1s.ucsb.edu](http://we1s.ucsb.edu/).

__________. Project Developers’ Web site. [http://4humwhatevery1says.pbworks.com](http://4humwhatevery1says.pbworks.com/). (Current synopsis of project presented on a public-facing Web site: [http://4humanities.org/category/whatevery1says/](http://4humanities.org/category/whatevery1says/)).

__________. “How Public Media in the US and UK Compare in Their Terminology for the Humanities.” August 3, 2015. Accessed May 27, 2017. [http://4humwhatevery1says.pbworks.com/w/page/98623971/How%20Public%20Media%20in%20the%20US%20and%20UK%20Compare%20in%20Their%20Terminology%20For%20the%20Humanities](http://4humwhatevery1says.pbworks.com/w/page/98623971/How%20Public%20Media%20in%20the%20US%20and%20UK%20Compare%20in%20Their%20Terminology%20For%20the%20Humanities).

__________. Making the Humanities Public (undergraduate collaborative research group project). Home page, December 18, 2016. Accessed April 21, 2017. [http://liucrgs.pbworks.com](http://liucrgs.pbworks.com/).

__________. “Topic Modeling Systems and Interfaces.” November 12, 2016. Accessed April 20, 2017. [http://4humwhatevery1says.pbworks.com/w/page/104256241/Topic%20Modeling%20Systems%20and%20Interfaces](http://4humwhatevery1says.pbworks.com/w/page/104256241/Topic%20Modeling%20Systems%20and%20Interfaces).

Whitehouse.gov (The White House). Home page, n. d. Accessed April 20, 2017. [https://www.whitehouse.gov/](https://www.whitehouse.gov/).

Wings. Home page. May 8,2016. Accessed February 2, 2017. [http://www.wings-workflows.org/](http://www.wings-workflows.org/).

Yang, Henry. “A Message on Diversity from Chancellor Henry T. Yang.” University of California, n. d. Accessed April 10, 2017. [http://diversity.evc.ucsb.edu/message.from.the.chancellor/](http://diversity.evc.ucsb.edu/message.from.the.chancellor/).

* * *

<a name="ftn1"></a>
[<sup>1</sup>](#_ftn1) These include books by Bate, Belfiore and Upchurch, Bod, Brooks, Harpham, Hutner and Mohamed, Nussbaum, Small, and Smith.

<a name="ftn2"></a>
[<sup>2</sup>](#_ftn2) These include the American Association of University’s [_Reinvigorating the Humanities_](https://eric.ed.gov/?id=ED505820) (Mathae and Birzer, 2004) and the American Academy of Arts and Science Commission on the Humanities and Social Science’s [_Reinvigorating the Humanities_](https://eric.ed.gov/?id=ED505820) (2013). Other major reports on the humanities are listed under [“Resources”](http://www.humanitiescommission.org/AboutHumanitiesSocialSciences/resources.aspx) on the site of the Commission on the Humanities and Social Science.

<a name="ftn3"></a>
[<sup>3</sup>](#_ftn3) [Jupyter notebooks](http://jupyter.org/) (previously known as “iPython notebooks”) are documents stored in the JSON format that can not only narrate data processing steps but run actual code in step-by-step modules.

<a name="ftn4"></a>
[<sup>4</sup>](#_ftn4) For effective introductions to topic modeling written for scholars in the humanities and social sciences, respectively, see Underwood, and Mohr & Bogdanov. For an introduction intended for a general scientific audience by one of its inventors see Blei.

<a name="ftn5"></a>
[<sup>5</sup>](#_ftn5) See WE1S’s comparative study of [“Topic Modeling Systems and Interfaces.”](http://4humwhatevery1says.pbworks.com/w/page/104256241/Research%20on%20Topic%20Modeling) WE1S adapted Goldstone’s dfr-browser, which is open source under the MIT license, with his assistance.

<a name="ftn6"></a>
[<sup>6</sup>](#_ftn6) Documentation of the WE1S manifest schema version 1.0 is available at [https://github.com/whatevery1says/manifest/blob/master/we1s-manifest-schema-1.1.md](https://github.com/whatevery1says/manifest/blob/master/we1s-manifest-schema-1.1.md).

<a name="ftn7"></a>
[<sup>7</sup>](#_ftn7) For example, a recent paper by Yolanda Gil and Daniel Garijo titled “Towards Automating Data Narratives” provides proof-of-concept for the automatic creation of prose “narratives” of data workflows from the steps recorded in the Wings workflow system.
