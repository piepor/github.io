---
layout: posts
title:  "Value and Key Factors of a Process Mining Project"
date:   2022-08-18 11:08:33 +0200
categories: process-mining process-mining-in-action
---
*Process Mining* has experienced impressive growth in the last years, both in the academic and business world. Indeed, it fits perfectly in the digital transformation providing a data-driven holistic insight into actual processes. Thus, it enables various possible applications, from identifying and optimising inefficiencies to process simulation or activity automation. As outlined in "Process Mining in Action"[^1], the principal value of Process Mining lies in the concept of transparency, a prerequisite for digital transformation. Process Mining is similar to Magnetic Resonance Tomography, which helps the doctor look inside the patient's body, understand the problem and act accordingly.

![Homer Simpson's MRT](/assets/homer-radiography.jpg){: .align-center}

In the same way, Process Mining tools allow for identifying issues in the system with insights derived from data. Consequent action must be the primary outcome of a Process Mining project, aiming to improve the actual process.

*Transparency* is allowed through data stored in an *Event Log* related to events happening during the execution of a process. The minimal information requested is the event timestamp, the executed activity and the case ID. A case ID identifies a particular sequence of events in the same process execution, called process instance or trace. 



Based on traces contained in the Event Log, various algorithms called "miners" can extract the process model, a fundamental component of the Process Mining workflow. The model, in fact, allows visualising the *"As-Is"* process flow as opposed to its *"To-Be"* version. Indeed, while people tend to think in terms of simple flows ("To-Be"), reality tends to be complicated due to various factors influencing the execution process ("As-Is"). 

Thanks to the solid base of Event Log, Process Mining allows for unanimous objectivity,  avoiding subjective interpretation of reality and moving from a perception-based towards a fact-based discussion. Being a new technology, process experts will search for failure cases as a first reaction. Once the method's credibility has been assessed, the focus shifts toward understanding the results and comparing them to other available reports and *Key Performance Indicators* (KPIs).

![subjective vs objective](/assets/the-big-lebowsky.jpg){: .align-center}

Providing insights on all organisation levels, Process Mining enables the decentralisation of process improvement and a collaborative approach involving most employees. The process renovation should focus on variants and activities which are effort drivers and of no value. Indeed, insights let the process experts decide what should be avoided to improve the performance as indicated by the chosen KPIs.

Despite the powerful tools developed by the Process Mining community, experience shows that many projects fail. Exaggerated promises, unrealistic expectations, unspecific targets, reluctant teams and insufficient process traces can be some reasons for failure. The author of "Process Mining in Action"[^1] presents three factors that, from experience in the field, are crucial for a successful Process Mining project. They are the *"3Ps"* of Process Mining:

- *Purpose*
- *People*
- *Process traces*

![three-ps](/assets/three-ps.png){: .align-center}

**Purpose**

The first and perhaps the most critical factor is the project's purpose. It implies a clear understanding of the outcome, which, in turn, allows to make the best tool choice and be more effective during the project development. In fact, there is no point in using a hammer to tighten a screw. A clearly defined purpose is also easier to communicate, helping to create the collaborative approach mentioned above with higher employee engagement and satisfaction.

Examples of purpose in the manufacturing environment might be identifying bottlenecks in the value stream, optimising inventories, and reducing working capital and material waste.

**People**

A good purpose could be useless without the involvement of the right people in the project. Insights and transparency can not be exploited if the process experts don't appreciate the approach or are not determined to strive for improvements. A successful project requires the people involved to be open to change instead of conserving the status quo. 

For example, transparency could be considered a threat by managers responsible for parts of the process because it can highlight previously neglected or ignored issues. If employees perceive Process Mining as a threat, they won't cooperate, bringing the overall project toward failure. This attitude should be proactively addressed with, for example, open communication of targets, early involvement and continuous training.

**Process traces**

Lastly, as with most data science projects, Process Mining needs data that are provided as an Event Log, as mentioned before. Process traces are the foundations of every technique used to build insights into the system; therefore, they play a crucial role in the project's success. In the academic world, they are often given for granted, and most papers rely on having events already organised in traces inside the convenient structure of an Event Log. 

On the contrary, constructing a suitable Event Log takes significant effort in an actual Process Mining project. It can be described in a multi-step approach: the first is creating one storage environment. In this phase, process traces possibly coming from different IT sources, including ERP and non-ERP systems (Enterprise Resource Planning), must be discovered, extracted and aggregated into a Global Data Lake. Since raw data comes from various sources, it is required to standardise and harmonise them to visualise the complete process flow. 

The refined data are organised in a semantic layer with two positive consequences. First, it helps the end user access them using standard business terms. Second, it makes them available to multiple projects to avoid duplications. The last step consists of creating a powerful front end that makes data analytics and visualisations readily available to the business user. It must be able to show single activities, process flows and all process variants intuitively to the final user. It also must be fast, as the requested response time is less than a few seconds.

*Conclusions*

Although a silver bullet for a successful project does not exist, multiple experiences in the business world suggest that the presence of the "3Ps" is a necessary but not sufficient prerequisite. As in the "triangle of fire", lacking just one element makes the project's success almost impossible. In conclusion, before starting a Process Mining project, you should first focus on clarifying its purpose and desired results. Then, you must identify motivated people for the team and the necessary processtraces.

[^1]: Lars Reinkemeyer - ["Process Mining in Action"] [book] - Springer Nature Switzerland AG 2020

[book]: http://processmining.org/publications.html#books
