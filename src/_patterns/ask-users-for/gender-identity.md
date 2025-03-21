---
layout: pattern
title: Gender identity
intro-text: Follow this pattern whenever you need to ask Veterans their gender identity. 
github-title: pattern-gender-identity
research-title: Ask users for gender identity
status: dont-use-deprecated
anchors:
  - anchor: Usage
  - anchor: Examples
  - anchor: How to design and build
---

<va-alert
  close-btn-aria-label="Close notification"
  status="error"
  visible
>
  <h2 slot="headline">
    The current policy recommends against using this pattern.
  </h2>
  <div>
  </div>
</va-alert>

## Usage

### When to use this pattern

* **Don’t ask a user to provide information that VA already has.** You should only ask users for race or ethnicity, sexual orientation, or gender identity when VA does not already have the user’s information or when VA’s last validation date pre-dates the most recent approved pattern.
* **Only ask a user to provide information if it benefits the user experience.** You should only ask a user for their race or ethnicity, sexual orientation, or gender identity if you can clearly explain how providing this information will benefit the user (not the VA) and the question is related to the larger action they are trying to perform.
* **Only collect data when you can reinforce trust, transparency, and user choice.** You must clarify their information will not be used for their medical treatment or benefits determinations and demonstrate how a user can change their race or ethnicity, sexual orientation, or gender identity and related privacy preferences in the VA.gov profile. If a user does not have and is not eligible to create a VA.gov profile, such as an unauthenticated users, then the data is not collected.

**Note:** Many forms are based off of paper forms with limited fields for gender identity. Work with your stakeholder to expand the fields.

## Examples

{% include component-example.html alt="Asking for gender identity in the VA.gov Profile." file="/images/patterns/ask-users-for/gender-identity/gender-identity-profile.png" caption="Asking for gender identity in the VA.gov Profile, personal information section." class="x2" %}

{% include component-example.html alt="Contents of the What to know, additional information component." file="/images/patterns/ask-users-for/gender-identity/gender-identity-profile-what-to-know.png" caption="Contents of the What to know before you decide to share your gender identity additional information component in Profile." class="x2" %}

## How to design and build

### How this pattern works

* **Provide a way to opt-out of answering.** An option labeled “Prefer not to answer” should be provided.
* **These questions are optional.** Clearly communicate that the information being collected is not required.
* **Do not remove the user from the task at hand to communicate details about this data collection.** Specific use descriptions, definitions, or other descriptive content must be brief and VA policy compliant with no need for a user to leave what they are doing.