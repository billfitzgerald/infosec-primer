# A. Introduction: Who Should Read This

This primer is intended as an introduction to information security testing. The primary audience is district staff and education technology vendors, but the usefulness of this information goes far beyond these two primary audiences. We hope and anticipate that this primer will be used by parents, students, privacy advocates, teachers, and anyone else with an interest in learning more about how to evaluate the security of the software we build and use. 

In an ideal world, the basic principles described in this primer would be incorporated as part of basic software development. The tests in this primer can be run by any aspiring application developer and could be incorporated as part of an investor's due diligence around a product or business idea. High school students can learn the basics of security testing as part of a STEAM curriculum. As our world becomes increasingly saturated with connected devices, an understanding of information security is an increasingly useful skill. 

For a school or district with the necessary resources, the primer provides tools to perform a basic level of security testing as part of the district's application-approval process. While security testing is an important part of a district's process for evaluating  software, it is one part in a broader process that generally starts with a brief check to determine whether a tool meets the organization's minimum standards. Once it has been determined that an application meets a legitimate and relevant educational need, additional evaluations can follow.

Depending on the application, these evaluation steps can include:
*  understanding how the application collects, uses, shares, and protects data, which could involve reading the terms of service and privacy policies for the application; 
*  and asking the vendor to explain their data-handling practices. This list of questions prepared by the [Consortium for School Networks (CoSN)](http://www.cosn.org/sites/default/files/03_SecurityQuestions.pdf) (PDF download) provides a good list of questions for application vendors.

We highlight these other, less technical means of evaluating software because it is necessary to show that, with educational technology, an information security practice is one piece of a larger puzzle. Evaluating educational technology requires that we begin with the learning goals met by the application and then expand to ensure that the application meets all of the requirements for online safety, privacy, security, and legal compliance. A "good" decision around educational technology requires insight into all of these areas, with the needs of learners guiding the evaluation process.

A good portion of this text is technical documentation that describes how to set up a testing environment and how to run tests. A secondary goal of this primer is to provide an overview of information security, including what it is and why it matters. To support that goal, several sections of the text are directly relevant to people who won't be running tests but who want to learn more. 

* Section B. [Responsible Disclosure](responsible.md): This section gives an overview of the ethics of information security testing and how to respond when security issues get discovered. The ethos of responsible disclosure lets us test safely and is a necessary foundation for all security research.
* Section E. [Testing Scenarios and Procedures](testing_scenarios.md): All of the testing scenarios are divided into three sections: a **Summary**, an overview of **Exploitability and Impact**, and **Setup and Tests**. The first two sections -- the **Summary** and the overview of **Exploitability and Impact** -- describe how and when a specific security issue can pose a risk. These two sections help frame why the issues matter without the reader getting bogged down in the technical details of running the tests.

Finally, this text is intended as a primer, not as a comprehensive guide. We made the decision to leave out subjects such as [cross-site scripting](glossary.md#h.glossary-xss) -- not because it isn't a real risk but because testing for cross-site scripting vulnerabilities can do serious damage to the applications being tested. 

Over time, the content in this guide will evolve and expand to meet the shifting needs of technology. We anticipate updates throughout the year, with published "official" releases happening one to two times annually. As with all the work in the [Common Sense District Privacy Evaluation Initiative](https://www.graphite.org/privacy), we welcome input and involvement -- so if you want to get involved, please be in touch.

* Proceed to the next chapter: B. [Responsible Disclosure](responsible.md)
