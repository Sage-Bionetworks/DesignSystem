---
layout: privacy_toolkit_auxiliary
title: Just-in-time permission

description: Apps usually bombard users with permissions screens requesting access to their camera, microphone and location data all at once. <br /> <br />There is a right time for everything! An easy solution to this problem is to surface the appropriate access permissions right before the user needs to complete a task requiring this type of data.

responsive_blocks:
  - type: diagram
    image_color: FEF7F8
    title: Worst Case Scenario

    description_items:
      - When a participant receives all of the permission requests all at once, it is natural for the participant to feel overwhelmed and suspicious of these such requests. Without the proper understanding of the reason why this data is being collected and its value to the biomedical researchers, a participant is more likely to deny the permissions during the onboarding process. If they decide to turn on the permissions at a later date, they will need to complete the cumbersome task of navigating to their phone’s system settings to update the app’s permissions.
      - This extra mental burden could induce frustration, especially among less tech-savvy users, or even worse, abandonment among them to leave or delete the app, sadly even before their participation begins.
    image_block:
      title: "Worst Case Scenario: Participant Denies Permissions and Must Navigate System Settings"
      image: worst-just-in-time-permission.png

  - type: diagram
    image_color: F7FDFA
    title: Just-in-time permission lays the groundwork for engagement.

    description_items:
      - With just-in-time permission, a participant is provided with sufficient context to make an informed and conscious decision to allow or deny permission when the permission becomes required for an study-related task. The just-in-time permission lays the groundwork for a long-term engagement by fostering mutual understanding and trust between researchers and participants. 
    image_block:
      title: "Best Practice: Just-In-Time Permission"
      image: best-just-in-time-permission.png

  - type: steps
    title: What to prepare?

    steps:
      - label: Step 1
        title: Send just-in-time permission request only when a relevant tasks comes up.
        description: Place the permission request only at the moment when a participant wants to complete a relevant task. [iOS] -> consider that this could take place during the (‘prepareForSegue’)

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
          button_text: Watch Video
          link: https://www.figma.com/file/BnryUMjHKeCADBiS0Rch7qBH/Privacy-Templates-Public?node-id=135%3A93

        - title: iOS GitHub Repo
          button_text: View on GitHub
          link: #

        - title: Android GitHub Repo
          button_text: View on GitHub
          link: https://github.com/Sage-Bionetworks/DesignSystem-Android
---
