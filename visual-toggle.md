---
layout: privacy_toolkit_auxiliary
title: Visual Toggle

description: In research we ask our participants to give us their data. Moreover, many studies have no data deletion date, so participants must trust researchers to guard their data in perpetuity. This is a big ask from participants--but what are we giving them in return? Researchers should give participants access to their own data. This practice follows the basic research principles of beneficence and respect for autonomy. In addition, if participants derive value from participating, they are more likely to stay in the study. 

floating_image: header-visual-toggle.svg
responsive_blocks:
  - type: diagram
    image_color: FEF7F8
    title: Participants struggle to interpret data that is poorly presented.

    description_items:
      - Participants approach their data with many kinds of questions. Presenting data in the wrong format makes it more difficult for them to answer those questions. For instance, presenting stepcount data only over the last week, or as a daily number, makes it more difficult for participants to identify trends.
      
    image_block:
      title: "Worst Case Scenario: Participant Can't Make Use of Their Data"
      image: worst-visual-toggle.svg

  - type: diagram
    image_color: F7FDFA
    title: Give participants an easy way to explore their data, so that they benefit from participating in the study.

    description_items:
      - Give participants access to their own data within the app. In addition, build ways for participants to explore their data. Think about the kinds of questions participants might want to answer. Help participants explore correlations between different data types and view data over different time frames. And keep the interface simple, so it is easy to use.  
    image_block:
      title: "Best Practice: Toggles to Support Different Views of Data"
      image: best-visual-toggle.svg

  - type: steps
    title: What to prepare?

    steps:
      - label: Step 1
        title: List all the data types being collected about the participant.
        description: Make sure that all, or at least as many of them as possible, are accessible by participants. 

      - label: Step 2
        title: Identify what kinds of questions participants are likely to have.
        description: Are your participants likely to be concerned about trends over time? What about what symptoms happen at the same time? Think through the different kinds of questions you anticipate your participants will have. Do some user research to find out what kinds of things participants want to know.    

      - label: Step 3
        title: Determine what kinds of visualizations make most sense.
        description: Think about both what is feasible for you to build and what your participants will be able to understand. Remember that many adults struggle with reading graphs, so offer options that are not graphs (like timelines of numbers). In addition, since many people have low graph literacy, choose common graph formats that people are more likely to be familiar with. Think about what axes and scales will make most sense for your users. For example, users may be less familiar with things like logarithmic scales. However, remember that some data types should be represented as raw numbers, while other types may need to be normalized or transformed in some way in order to be more easily understood.    

      - label: Step 4
        title: Keep it simple and usable.
        description: Build only what you can maintain for at least the length of the study. Although you should offer more than one option for exploring data, you don’t need to reinvent R or Excel. Instead, keep your eye on simplicity and ease of use. Small and fine-grained controls can be hard to use on a phone. Strike a balance between making visualizations informative and stripping out unnecessary detail. If needed, consider a web interface for more complex data exploration. And don’t forget to do user testing to make sure your interface is usable!    

  - type: resources
    title: Resources
    resource_blocks:
      - title: Case Studies
        resources:
        - title: Better Visualizing of Fitness App Data Helps Discover Trends, Reach Goals
          subtitle: Michelle Ma
          button_text: Read Article
          resource_image: ic-document.svg
          link: https://www.washington.edu/news/2014/07/08/better-visualizing-of-fitness-app-data-helps-discover-trends-reach-goals/
          
        - title: See It, Believe It. The Web Visualization Library
          subtitle: David Haddad
          button_text: Read Article
          resource_image: ic-document.svg
          link: https://www.openmhealth.org/see-it-believe-it-the-web-visualization-library/  
          
        - title: A Systematic Review of Patient-Facing Visualizations of Personal Health Data
          subtitle: MR Turchioe, A Myers, S Isaac, D Baik, LV Grossman, JS Ancker, RM Creber
          button_text: Read Article
          resource_image: ic-document.svg
          link: https://www.ncbi.nlm.nih.gov/pubmed/31597182?dopt=Abstract   
          
        - title: Understanding Literacy and Numeracy
          subtitle: Centers for Disease Control and Prevention
          button_text: Read Article
          resource_image: ic-document.svg
          link: https://www.cdc.gov/healthliteracy/learn/UnderstandingLiteracy.html   
          
        - title: Health History Timeline
          subtitle: Katie McCurdy
          button_text: Read Article
          resource_image: ic-document.svg
          link: http://katiemccurdy.com/portfolio/health-history-timeline/
          
        - title: Mistakes, We've Drawn A Few
          subtitle: Sarah Leo
          button_text: Read Article
          resource_image: ic-document.svg
          link: https://medium.economist.com/mistakes-weve-drawn-a-few-8cdd8a42d368
 
        - title: You’ve Been Reading Charts Wrong. Here’s How a Pro Does It.
          subtitle: Christopher Ingraham
          button_text: Read Article
          resource_image: ic-document.svg
          link: https://www.washingtonpost.com/business/2019/10/14/youve-been-reading-charts-wrong-heres-how-pro-does-it/ 

        - title: Visualizing Health
          subtitle: University of Michigan
          button_text: See Examples
          resource_image: ic-example.svg
          link: http://www.vizhealth.org/
          
        - title: Data Visualizations
          subtitle: Institute for Health Metrics and Evaluation
          button_text: See Examples
          resource_image: ic-example.svg
          link: http://www.healthdata.org/results/data-visualizations

      - title: Resources
        resources:
        - title: Visual Toggle Patterns
          button_text: View in Figma
          resource_image: ic-figma.svg
          link: https://www.figma.com/file/QjlqDSjde4GK7fR9sP78Qv/Privacy-Toolkit-Public-to-Webpage?node-id=44%3A16

---
