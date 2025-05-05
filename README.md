

# TrainAndSearch

- [Project summary](#project-summary)
  - [The issue we are hoping to solve](#the-issue-we-are-hoping-to-solve)
  - [How our technology solution can help](#how-our-technology-solution-can-help)
  - [Our idea](#our-idea)
- [Technology implementation](#technology-implementation)
  - [IBM watsonx product(s) used](#ibm-ai-services-used)
  - [Other IBM technology used](#other-ibm-technology-used)
  - [Solution architecture](#solution-architecture)
  - [Solution demo video](#solution-demo-video)
  - [Project development roadmap](#project-development-roadmap) 
  - [Live demo](#live-demo)- 
  - [Authors](#authors)


_INSTRUCTIONS: Below are the suggested sections to include in your README file to make sure your project is well documented. You can remove this instruction text._

## Project summary
The project is about how to acheive the 8th goal of the United Nations Sustainable Development goals by use of IBM software


### The issue we are hoping to solve
The problem being solved is people have challenges regarding finding the most appropriate job to apply for and most of all the training course to select so as to be considered for a particular job.
The requirements could be too detailed and complex which makes it difficult to decide if an applicant could be capable of being selected for the job opportunity.


### How our technology solution can help
Using generative AI to ease job search and offer recommendation of courses from IBM training website.


### Our idea
  The solution is about enabling people to determine if they meet the criteria through use of Watsonx.ai and IBM Cognos analytics. Additionally, we are using courses from IBM training to suggest courses which they could pursue so as to boost their chances of being hired. The IBM granite models granite-3-2-8b-instruct and Granite Guardian 3.1 2B. 
The solution starts with grounding the CV document of a person into the Watsonx.ai (chat mode) then the question that is placed is the job description the person is applying to.
The Watsonx.ai generates scores of the level at which the CV has met the qualifications.
Then the information (score levels as a percentage) is placed into an excel document. The excel document is uploaded into the IBM Cognos Analytics which generates insights from the excel sheet.
The insights generated together with any relevant information is placed into the Watsonx.ai (structured mode) where recommendations are generated on what steps are to be taken so as to have higher scores in applying for future job opportunities. Recommendations of which Information Technology courses to be taken for upskilling purposes are obtained from IBM training  (https://www.ibm.com/training) .  
Moreover, the solution aside from job seekers the solution could be used by companies to upskill their employees especially by use of AI so as to determine how a company could achieve economic growth.



## Technology implementation

### IBM watsonx product(s) used



**Featured watsonx products**

- [watsonx.ai](https://www.ibm.com/products/watsonx-ai) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
- The watsonx.ai ( chat mode ) was used to generate score levels which evaluates whether the person is best suited to apply for the job
- The watsonx.ai ( structured mode) was used to train AI maodels regarding job application




### Other IBM technology used



 [IBM Cognos Analytics ](https://www.ibm.com/products/cognos-analytics) - WHERE AND HOW THIS IS USED IN OUR SOLUTION
 - The IBM Cognos Analytics was used to analyze scores obtaind from the watsonx.ai
 


### Solution architecture

REPLACE THIS EXAMPLE WITH YOUR OWN, OR REMOVE THIS EXAMPLE

Diagram and step-by-step description of the flow of our solution:

![image](https://github.com/user-attachments/assets/bc5de5bf-1cb6-4334-ac5b-bd0ece1e2fa0)


### Solution demo video

https://dataplatform.cloud.ibm.com/analytics/notebooks/v2/ad0d1b2a-3354-4f39-ad68-c132ee24f878/view?access_token=d2f1d6abe5613507a8a34d8f4a4678923f71f4c96ddd5e66af3bad2962b3b69b&context=wx

---

https://dataplatform.cloud.ibm.com/analytics/notebooks/v2/55118f62-87c5-4682-877f-26f96b1507aa/view?access_token=ddb78b85dcb0296d1bb14f239e8888a6a7c7289b7504d9b9690e43dabd69e54b&context=wx


### Authors


- ** John Maina** - _Initial work_ - [PurpleBooth](https://)




