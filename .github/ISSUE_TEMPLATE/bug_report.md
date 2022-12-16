name: bug_report
description: Create a bug report to help improve Marlin Firmware
title: "[BUG] (bug summary)"
body:
  - type: markdown
    attributes:
      value: |
        ## Before Reporting a Bug

        - Read and understand 5985's [Code of Conduct](url). You are expected to comply with it, including treating everyone with respect.

        ## Instructions

        Please follow the instructions below. Failure to do so may result in your issue being closed. 
        
        1. Provide a good title starting with [BUG].
        2. Fill out all sections of this bug report form.
        3. Always attach all appropriate media

  - type: markdown
    attributes:
      value: |
        # Bug Details

  - type: textarea
    attributes:
      label: Bug Description
      description: >-
        Describe the bug in this section. Tell us what you were trying to do and what
        happened that you did not expect. Provide a clear and concise description of the
        problem and include as many details as possible.
      placeholder: |
        The robot spontaniously combusts.
    validations:
      required: true

  - type: input
    attributes:
      label: Bug Timeline
      description: Is this a new bug or an old issue? When did it first start?
    validations:
      required: true

  - type: textarea
    attributes:
      label: Expected behavior
      description: >-
        What did you expect to happen?
      placeholder: I expected it to move left.
      validations:
        required: true

  - type: textarea
    attributes:
      label: Actual behavior
      description: What actually happened instead?
      placeholder: It moved right instead of left.
    validations:
      required: true

  - type: textarea
    attributes:
      label: Steps to Reproduce
      description: >-
        Please describe the steps needed to reproduce the issue.
      placeholder: |
        1. [First Step] ...
        2. [Second Step] ...
        3. [and so on] ...
      validations:
        required: true

  - type: input
    attributes:
      label: Robot
      description: Which robot is this?
      placeholder: showbot
      validations:
        required: true

  - type: input
    attributes:
      label: Software version
      description: What version of software is this?

  - type: input
    attributes:
      label: How important is this
      description: How critical is this. Justify your answer
      placeholder: this must get done before comp
      validations:
        required: true

  - type: textarea
    attributes:
      label: Additional information & file uploads
