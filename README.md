[![License](https://img.shields.io/badge/License-Apache2-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0) [![Community](https://img.shields.io/badge/Join-Community-blue)](https://developer.ibm.com/callforcode/solutions/projects/get-started/)

_INSTRUCTIONS: This GitHub repository serves as a template and example you can use to create a well documented README for your project for the [2024 Call for Code Global Challenge](https://developer.ibm.com/callforcode/global-challenge/)._

Your required deliverables and project descriptions should be officially submitted to your My Team > Submissions section of the [Call for Code Global Challenge web site](https://compete.callforcode.skillsnetwork.site/competitions/2024-call-for-code-global-challenge), but you can also optionally include them here for completeness, as it is good practice to clearly document your project in your README file. Replace the examples seen here with your own deliverable links.

Use the **Use this template** button to create a new version of this repository and start entering content for your own Call for Code submission project. Make sure you have [registered for the 2024 Call for Code Global Challenge](https://www.ibm.com/account/reg/signup?formid=urx-52643) to access resources and full project submission instructions. Remove any "INSTRUCTIONS" sections when you are ready to submit your project.

_New to Git and GitHub? This free online course will get you up to speed quickly: [Getting Started with Git and GitHub](https://www.coursera.org/learn/getting-started-with-git-and-github)_.

# Replace this heading with your team/submission name

- [Project summary](#project-summary)
  - [The issue we are hoping to solve](#the-issue-we-are-hoping-to-solve)
  - [How our technology solution can help](#how-our-technology-solution-can-help)
  - [Our idea](#our-idea)
- [Technology implementation](#technology-implementation)
  - [IBM watsonx product(s) used](#ibm-ai-services-used)
  - [Other IBM technology used](#other-ibm-technology-used)
  - [Solution architecture](#solution-architecture)
- [Presentation materials](#presentation-materials)
  - [Solution demo video](#solution-demo-video)
  - [Project development roadmap](#project-development-roadmap)
- [Additional details](#additional-details)
  - [How to run the project](#how-to-run-the-project)
  - [Live demo](#live-demo)
- [About this template](#about-this-template)
  - [Contributing](#contributing)
  - [Versioning](#versioning)
  - [Authors](#authors)
  - [License](#license)
  - [Acknowledgments](#acknowledgments)

_INSTRUCTIONS: Below are the suggested sections to include in your README file to make sure your project is well documented. You can remove this instruction text._

## Project summary
The summary is that we are addressing lack of quality education by creating learning materials which could be accessed without the internet to marginalised communities and tackling clean water access by aiding water engineers with combining ESG reports from IBM software such as Maximo with  software such as IBM Cognos Analytics for easening analysis of drilling operations in harsh environments such as  arid areas.

### The issue we are hoping to solve
The first issue we are hoping to solve is that people who are affected by climate change  such as drought or floods lack finances to buy phones or even access the internet so as learn various information such as certification courses. Moreover, visually impaired people are significantly affected as they are unable to effectively learn. The second issue we seek to solve is that water engineers who either drill  water boreholes or engage in activities such as water purification have their operations affected by climate change. This could be due to carbon emissions from industries or high temperature which could affect drilling equipment for water boreholes.

### How our technology solution can help
Using generative AI to create updated and accessible  offline content.


### Our idea
The idea for quality education starts with gathering information from certification courses of IBM SkillsBuild, IBM website  and webinars from the IBM events website. The first  step would be to use watsonx.ai to generate new text then use watsonx.governance to examine possibility of bias and copyright infringement. The second  step would be placing the generated content in  PowerPoint documents then sending them to people who could use them. Alternatively, the documents could be uploaded to the chat mode of the Watsonx. ai so as to ground responses based on the contents of the documents.
 The idea for clean water access also relies on the generated content from a course of titled Fundamentals of sustainability and Technology which outlines use of IBM ESG software such as Envizi. The first step would be to acquire  information obtained from using ESG software such as Maximo and the Environmental Intelligence Suite , the information obtained could be details such as health score or numbers of failures. The information is then placed into excel documents by utilizing watsonx.ai and watsonx.orchestrate. The Watsonx. ai is used to add relevant content in the Add knowledge section of the Watsonx. Orchestrate so as to ground the  AI model with detailed information to use for its responses. The watsonx. Orchestrate is used automate the data entry process from information obtained from the  software such as Maximo and Environmental Intelligence Suite. This is accomplished by use of the AI assistant builder. Finally, the excel document is then uploaded to the IBM Cognos analytics so as to derive insights. These insights could be utilized by a water engineer especially on factors that affect water purification such as carbon emissions. Moreover,  information derived from the Environmental Intelligence Suite concerning geospatial data outlines occurrences of  earthquakes  which significantly  aids in planning of drilling  operations of  water boreholes. Information obtained from Maximo application suite such as probability of   failure once summarized by the IBM Cognos analytics could  be essential  in conducting efficient maintenance schedules as high temperature due to climate change often leads increased tendencies of thermal stress of drilling equipment.


More detail is available in our [description document](./docs/DESCRIPTION.md).

## Technology implementation

### IBM watsonx product(s) used

_INSTRUCTIONS: Included here is a list of IBM watsonx products. Remove any products you did not use. Leave only those included in your solution code. In your official submission on the Call for Code Global Challenge web site, you are required to provide details on where and how you used each IBM watsonx product so judges can review your implementation. Remove these instructions._

**Featured watsonx products**

- [watsonx.ai](https://www.ibm.com/products/watsonx-ai) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- The watsonx.ai was used in the idea of quality education by generation of new text from information obtained from the IBM SkillsBuild.
- The watsonx.ai was also used in the idea for clean water by prediction of weather patterns such as daily precipitation and providing recommendations on what action should be taken.

- [watsonx.governance](https://www.ibm.com/products/watsonx-governance) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- The watsonx.governance was used to detect levels or presence of copyright infringement from the generated content extracted from IBM SkillsBuild as well as information obtained from webinars and the IBM website.

- [watsonx Assistant](https://cloud.ibm.com/catalog/services/watsonx-assistant) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- Watsonx assistant was integrated with watsonx.ai so as to provide a  simple way to perform an integration between a dialog flow and generative AI inferencing services in watsonx.ai.

### Other IBM technology used

INSTRUCTIONS: List any other IBM technology or IBM AI services used in your solution and describe how each component was used. If you can provide details on where these were used in your code, that would help the judges review your submission.

 IBM Maximo Application Suite was used to create and train an AI vision model and perform an automated quality inspection
 IBM Environmental Intelligence Suite was used to examine geospatial, weather  and climate data which are main factors that water engineers take into account when drilling boreholes.
 Cognos Analytics was used so as to formulate  AI-powered responses and insights from factors that could affect water access such as examining scope emission report from IBM Envizi so as determine possible level of carbon contamination of water.This insights could be used for making  data-driven decisions.
 
**Additional IBM AI services (Remove any that you did not use)**

- [Watson Machine Learning](https://cloud.ibm.com/catalog/services/watson-machine-learning) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
Watson Machine learning  was an associated service when using the watsonx. ai
- [Watson Studio](https://cloud.ibm.com/catalog/services/watson-studio) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- Watson studio was accessible by use of the cloud pak for data, i used it in my solution by using templates provided in the cloud pak for data


- The 
-  
- 

### Solution architecture

REPLACE THIS EXAMPLE WITH YOUR OWN, OR REMOVE THIS EXAMPLE

Diagram and step-by-step description of the flow of our solution:

![Video transcription/translaftion app]( )



## Presentation materials

_INSTRUCTIONS: The following deliverables should be officially posted to your My Team > Submissions section of the [Call for Code Global Challenge resources site](https://cfc-prod.skillsnetwork.site/), but you can also include them here for completeness. Replace the examples seen here with your own deliverable links._

### Solution demo video

[![Watch the video](https://youtu.be/5fjDoKyZgPg)

### Project development roadmap

The project currently does the following things.

- Feature 1
- Feature 2
- Feature 3

In the future we plan to...

See below for our proposed schedule on next steps after Call for Code 2024 submission.

![Roadmap]()

## Additional details

_INSTRUCTIONS: The following deliverables are suggested, but **optional**. Additional details like this can help the judges better review your solution. Remove any sections you are not using._

### How to run the project

INSTRUCTIONS: In this section you add the instructions to run your project on your local machine for development and testing purposes. You can also add instructions on how to deploy the project in production.
The project is run by use of Watsonx.ai and Watsonx. governance, other areas where the solution could be deployed is in the Cognos analytics

### Live demo

You can find a running system to test at...

See our [description document](./docs/DESCRIPTION.md) for log in credentials.

---

_INSTRUCTIONS: You can remove the below section from your specific project README._

## About this template

### Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

### Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags).

### Authors


- ** John Maina** - _Initial work_ - [PurpleBooth](https://)

### License

This project is licensed under the Apache 2 License - see the [LICENSE](LICENSE) file for details.

### Acknowledgments

- Based on [Billie Thompson's README template](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2).
