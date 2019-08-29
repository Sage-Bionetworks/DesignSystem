---
layout: privacy_toolkit_auxiliary
title: Just-in-time permission

description: Apps usually bombard users with permissions screens requesting access to their camera, microphone and location data all at once. <br /> <br />There is a right time for everything! Request permissions right before the user needs to complete a task that requires this type of data. This approach is called a just-in-time permission.

responsive_blocks:
  - type: diagram
    image_color: FEF7F8
    title: Asking for all permissions upfront can cause distrust.

    description_items:
      - When a participant receives all permission requests at once, they might feel overwhelmed and suspicious of these requests. Without an understanding of why permissions are required to collect the data, and why this data is valuable to researchers, the participant could deny permissions during the onboarding process. If they decide to grant permissions later, they will  have to navigate their phone’s system settings and update the app’s permissions. 
      - This extra burden could create frustration, especially among less tech-savvy users. Even worse, it could cause them to leave or delete the app before their participation has even begun.
    image_block:
      title: "Worst Case Scenario: Participant Denies Permissions and Must Navigate System Settings"
      image: worst-just-in-time-permission.png

  - type: diagram
    image_color: F7FDFA
    title: Just-in-time permission lays the groundwork for engagement.

    description_items:
      - With just-in-time permission, the participant is provided the context to make an informed decision to allow or deny permissions that collect data for study-related tasks. Just-in-time permission also lays the groundwork for long-term engagement, by fostering mutual understanding and trust between researchers and participants.  
    image_block:
      title: "Best Practice: Just-In-Time Permission"
      image: best-just-in-time-permission.png

  - type: steps
    title: What to prepare?

    steps:
      - label: Step 1
        title: Send just-in-time permission request only when a relevant tasks comes up.
        description: Place the permission request only at the moment when a participant wants to complete a relevant task. For iOS, this could take place during the (’PrepareForSegue’).

      - label: Step 2
        title: Explain just-in-context how the permission is required for the task.
        description: Provide a walkthrough of what task the participant is required to accomplish, how the task connects to the scientific research, and why the permission must be turned on in order to gather the data.

      - label: Step 3
        title: Use texts and visuals to demonstrate a real example.
        description: For example, show a visual of the finger-tapping exercise and explain the application must have the permission to use the motion sensor in order to track finger movements.

  - type: resources
    title: Resources
    resource_blocks:
      - title: Case Studies
        resources:
        - title: How to Ask for App Permissions
          subtitle: Luke Wroblewski
          button_text: Watch Video
          link: https://www.lukew.com/ff/entry.asp?1928

        - title: What Can Bike Sharing Apps Teach Us About Mobile On-boarding Design?
          subtitle: Luke Wroblewski
          button_text: Read Article
          link: https://www.lukew.com/ff/entry.asp?1995

        - title: Permission and Best Practices
          subtitle: Sarah Gold
          button_text: Read Article
          link: https://www.projectsbyif.com/blog/making-digital-services-worth-trusting-permissions-and-best-practices/

      - title: Resources
        resources:
        - title: Just-In-Time Permissions Patterns
          button_text: View in Figma
          link: https://www.figma.com/file/BnryUMjHKeCADBiS0Rch7qBH/Privacy-Templates-Public?node-id=135%3A93

        - title: iOS GitHub Repo
          button_text: View on GitHub
          link: #

        - title: Android GitHub Repo
          button_text: View on GitHub
          link: https://github.com/Sage-Bionetworks/DesignSystem-Android
---
