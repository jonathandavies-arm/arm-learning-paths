---
# ================================================================================
#       Edit
# ================================================================================

# Always 3 questions. Should try to test the reader's knowledge, and reinforce the key points you want them to remember.
    # question:         A one sentence question
    # answers:          The correct answers (from 2-4 answer options only). Should be surrounded by quotes.
    # correct_answer:   An integer indicating what answer is correct (index starts from 0)
    # explanation:      A short (1-3 sentence) explanation of why the correct answer is correct. Can add additional context if desired


review:
    - questions:
        question: >
            Linux kernel parameters can impact Envoy performance.
        answers:
            - "True"
            - "False"
        correct_answer: 1
        explanation: >
            Kernel network stack can have a direct impact on Envoy.

    - questions:
        question: >
            Which solutions can be used to potentially gain additional performance on Arm?
        answers:
            -  THP
            -  PGO
            - "all of the above"  
        correct_answer: 3                    
        explanation: >
            Both THP and PGO can be used to potentially gain additional performance.




# ================================================================================
#       FIXED, DO NOT MODIFY
# ================================================================================
title: "Review"                 # Always the same title
weight: 20                      # Set to always be larger than the content in this path
layout: "learningpathall"       # All files under learning paths have this same wrapper
---
