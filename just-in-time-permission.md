---
layout: privacy_toolset_auxiliary
test:
  - One
    - It
    - Works
  - Two
    - It
    - Works

title: Just-in-time permission
description: Apps usually bombard users with permissions screens requesting access to their camera, microphone and location data all at once. <br /> <br />There is a right time for everything! An easy solution to this problem is to surface the appropriate access permissions right before the user needs to complete a task requiring this type of data.

---


<div class="c-auxiliary__message-block">
  <div class="c-auxiliary__message-block-title">
    <div class="c-auxiliary__message-block-title-text">Worst Case Scenario</div>
    <div class="c-auxiliary__mesage-block-title-arrow b-tools__mobile">
      <img target="#first-pattern" class="c-auxiliary__expand-arrow" src="{{ "/images/ic_expand_arrow.svg" | prepend: site.baseurl }}">
    </div>
  </div>
  <div id="first-pattern" class="c-auxiliary__message-block-description hide">
    <div class="c-auxiliary__message-block-description-item">
      When a participant receives all of the permission requests all at once, it is natural for the participant to feel overwhelmed and suspicious of these such requests. Without the proper understanding of the reason why this data is being collected and its value to the biomedical researchers, a participant is more likely to deny the permissions during the onboarding process. If they decide to turn on the permissions at a later date, they will need to complete the cumbersome task of navigating to their phone’s system settings to update the app’s permissions. 
    </div>
    <div class="c-auxiliary__message-block-description-item">
      This extra mental burden could induce frustration, especially among less tech-savvy users, or even worse, abandonment among them to leave or delete the app, sadly even before their participation begins.
    </div>

  <div class="c-auxiliary__image-block">
    <div style="background-color: #FEF7F8" class="c-auxiliary__image-block-title">Worst Case Scenario: Participant Denies Permissions and Must Navigate System Settings</div>
    <img id="first-image" style="background-color: #FEF7F8" src="{{ "/images/worst-just-in-time-permission.png" | prepend: site.baseurl }}">
  </div>
    <div class="c-auxiliary__message-block-view-larger b-tools__mobile">
      <div class="c-auxiliary__message-block-view-larger-left">View larger</div>
      <div class="c-auxiliary__message-block-view-larger-right">
        <img target="#first-image" class="c-auxiliary__view-fullscreen-img" src="{{ "/images/ic-expand-image.png" | prepend: site.baseurl }}">
      </div>
    </div>
  </div>

</div>

<div class="c-auxiliary__message-block">
  <div class="c-auxiliary__message-block-title">
    <div class="c-auxiliary__message-block-title-text">Just-in-time permission lays the groundwork for engagement.</div>
    <div target="#second-pattern" class="c-auxiliary__mesage-block-title-arrow b-tools__mobile">
      <img target="#second-pattern" class="c-auxiliary__expand-arrow" src="{{ "/images/ic_expand_arrow.svg" | prepend: site.baseurl }}">
    </div>
  </div>
  <div id="second-pattern" class="c-auxiliary__message-block-description hide">
    <div class="c-auxiliary__message-block-description-item">
      With just-in-time permission, a participant is provided with sufficient context to make an informed and conscious decision to allow or deny permission when the permission becomes required for an study-related task. The just-in-time permission lays the groundwork for a long-term engagement by fostering mutual understanding and trust between researchers and participants. 
    </div>

  <div class="c-auxiliary__image-block">
    <div style="background-color: #F7FDFA" class="c-auxiliary__image-block-title">Best Practice: Just-In-Time Permission</div>
    <img id="second-image" style="background-color: #F7FDFA" src="{{ "/images/worst-just-in-time-permission.png" | prepend: site.baseurl }}">
  </div>
    <div class="c-auxiliary__message-block-view-larger b-tools__mobile">
      <div class="c-auxiliary__message-block-view-larger-left">View larger</div>
      <div class="c-auxiliary__message-block-view-larger-right">
        <img target="#second-image" class="c-auxiliary__view-fullscreen-img" src="{{ "/images/ic-expand-image.png" | prepend: site.baseurl }}">
      </div>
    </div>
  </div>
</div>

<div class="c-auxiliary__message-block">
  <div class="c-auxiliary__message-block-title">
    <div class="c-auxiliary__message-block-title-text">What to prepare?</div>
    <div target="#third-pattern" class="c-auxiliary__mesage-block-title-arrow b-tools__mobile">
      <img target="#third-pattern" class="c-auxiliary__expand-arrow" src="{{ "/images/ic_expand_arrow.svg" | prepend: site.baseurl }}">
    </div>
  </div>
  <div id="third-pattern" class="c-auxiliary__message-block-description hide">
    <div class="c-auxiliary__message-block-description-item">
      <div class="c-auxiliary__step">
        <div class="c-auxiliary__step-left">
          Step 1
        </div>
        <div class="c-auxiliary__step-right">
          <div class="c-auxiliary__step-title">Send just-in-time permission request only when a relevant tasks comes up.</div>
          <div class="c-auxiliary__step-description">Place the permission request only at the moment when a participant wants to complete a relevant task. [iOS] -> consider that this could take place during the (‘prepareForSegue’)</div>
        </div>
      </div>
      <div class="c-auxiliary__step">
        <div class="c-auxiliary__step-left">
          Step 2
        </div>
        <div class="c-auxiliary__step-right">
          <div class="c-auxiliary__step-title">Explain just-in-context how the permission is required for the task.</div>
          <div class="c-auxiliary__step-description">Provide a walkthrough of what task the participant is required to accomplish, how the task connects to the scientific research, and why the permission must be turned on in order to gather the data.</div>
        </div>
      </div>
      <div class="c-auxiliary__step">
        <div class="c-auxiliary__step-left">
          Step 3
        </div>
        <div class="c-auxiliary__step-right">
          <div class="c-auxiliary__step-title">Use texts and visuals to demonstrate a real example. </div>
          <div class="c-auxiliary__step-description">For example, show a visual of the finger-tapping exercise and explain the application must have the permission to use the motion sensor in order to track finger movements.</div>
        </div>
      </div>
    </div>
  </div>
  <div id="c-auxiliary__fullscreen-img-container">
    <img id="c-auxiliary__fullscreen-img"/>
    <img id="c-auxiliary__fulscreen-img-close" src="{{ "/images/ic-close.svg" | prepend: site.baseurl }}">
  </div>
</div>
<script>
  $('.c-auxiliary__expand-arrow').click(event => {
    console.log('click')
    let clickedArrow = $(event.target)
    if (clickedArrow.hasClass("flip")) {
      clickedArrow.removeClass("flip");
      $(clickedArrow.attr('target')).addClass("hide")
      $(clickedArrow.attr('target')).removeClass("show")
    } else {
      clickedArrow.addClass("flip");
      $(clickedArrow.attr('target')).addClass("show")
      $(clickedArrow.attr('target')).removeClass("hide")
    }
  })

  $('#c-auxiliary__fulscreen-img-close').click(event => {
    $("#c-auxiliary__fullscreen-img-container").removeClass('show');
  })

  $('.c-auxiliary__view-fullscreen-img').click(event => {
    let icon = $(event.target)
    let imageSrc = $(icon.attr('target')).attr('src');
    let fullscreenImage = $("#c-auxiliary__fullscreen-img");
    let fullscreenImageContainer = $("#c-auxiliary__fullscreen-img-container");
    fullscreenImage.attr('src', imageSrc);
    fullscreenImageContainer.addClass("show");
  })
</script>
