---
name: Talk Proposal
about: Describe this issue template's purpose here.
title: 'Talk Proposal: {Talk Title}'
labels: 'talk'
assignees: ''
body:
    - type: markdown
      attributes:
        value: |
            Thanks so much for your interest in speaking at SFNode!
            
            We love to hear from the community and ar excited to see what you are working on
            or what you are excited about.
    - type: input
      attributes:
        label: Full name and Bio
        description: Who are you and what are you all about? We will post this in the Meetup description.
      validations:
        required: true
    - type: input
      attributes:
        label: Talk title
        description: What is the title of your presentation?
      validations:
        required: true
    - type: textarea
      attributes:
        label: Talk abstract
        description: Make sure talk is true to the title and abstract as we will post this in the Meetup description
      validations:
        required: true
    - type: input
      attributes:
        label: Talk Duration
        description: We accept all types of talks, from lightning talks with a length of 5min to whole 1hr sessions.
      validations:
        required: true
    - type: input
      attributes:
        label: Url to Slides or GitHub Repo
        description: Either now or can be posted in Meetup comments later. Our attendees love to reference the slides after the talks.
    - type: textarea
      attributes:
        label: Social Media Info
        description: How can folks communicate with you? Twitter handle, GitHub, Other social profiles, Personal blog, etc.
    - type: checkboxes
      attributes:
        label: Are you going to be live coding?
        options:
            - label: Yes, I will!
    - type: checkboxes
      attributes:
        label: Do you need audio from your computer?
        options:
            - label: Yes, I will!
