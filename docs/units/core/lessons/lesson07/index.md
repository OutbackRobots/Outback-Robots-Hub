---
type: lesson
unit_id: core
lesson_id: 07_AIandLLMs
lesson_no: 07
lesson_title: Design for Good - Chat Smart, Stay Safe
year_level: [5, 6]
duration_min: 90
lesson_summary: This lesson introduces students to Large Language Models (LLMs) like ChatGPT, exploring how they work, their benefits and limitations, and how to use them effectively and safely through good prompt engineering.
classroom_setup_and_delivery_considerations: []
robot_use: interacting         # building|interaction
internet_required: no # yes|no|optional
devices:          # per_student|pair|group
core_concepts: []
curriculum_links: []
learning_objectives: 
  - Add learning objectives in front matter under learning_objectives as a list.
success_criteria: 
  - Add success criteria in front matter under success_criteria as a list.
slides:
  - title: Lesson 7 slides - AI and LLMs (PPTX)
    url: ../../../../assets/slides/OutbackRobots_Lesson7_Slides_AIandLLMs.pptx
  - title: Lesson 7 slides - AI and LLMs (PDF)
    url: ../../../../assets/slides/OutbackRobots_Lesson7_Slides_AIandLLMs.pdf
build_videos: 
worksheets: 
  - title: LLM Prompt List - Worksheet (DOCX)
    url: ../../../../assets/worksheets/lesson07_workseet_LLMPromptList.docx
  - title: LLM Prompt List - Worksheet (PDF)
    url: ../../../../assets/worksheets/lesson07_workseet_LLMPromptList.pdf
other_materials: []
activities: []
tags: []
status: draft
version: v0.1
---

# Lesson {{ page.meta.lesson_no }} - {{ page.meta.lesson_title }}

!!! tip "At a glance"
    - :material-kangaroo: **Summary:** {{ page.meta.lesson_summary }}
    - :material-clock-outline: **Duration:** {{ page.meta.duration_min }} min
    - :material-robot: **Robot use:** {{ page.meta.robot_use }}


## Download resources

### Slides
{% if page.meta.slides %}
{% for item in page.meta.slides %}
- [{{ item.title }}]({{ item.url }})
{% endfor %}
{% else %}
Add slide links in front matter under slides as title + url.
{% endif %}

![Lesson7 slides - AI and LLMs](../../../../assets/slides/OutbackRobots_Lesson7_Slides_AIandLLMs.pdf){ type=application/pdf style="min-height:50vh;width:80%"}

### Worksheets
{% if page.meta.worksheets %}
{% for item in page.meta.worksheets %}
- [{{ item.title }}]({{ item.url }})
{% endfor %}
{% else %}
This lesson has no worksheets.
{% endif %}

![LLM Prompt List Worksheet](../../../../assets/worksheets/lesson07_workseet_LLMPromptList.pdf){ type=application/pdf style="min-height:50vh;width:80%"}

### Build videos

This lesson has no build videos.


---

## Lesson overview

### Lesson Plan
  1. Lesson 6 Recap - 5 min​
  2. Introduction to LLMs – 5 min​
  3. LLM sentence finisher – 15 min​
  4. Prompt engineering activity - 15 min​
  5. Interacting with Blossom and Ultrasonic sensor - 40 min​
  6. Survey - 5 min​
  7. Summary - 5 min


### Learning objectives
After this lesson, students will be able to  

  - Explain that LLMs work by predicting the next word based on patterns in data ​
  - Define AI and LLM in their own words ​
  - Identify at least two examples of LLMs they encounter in everyday life ​
  - Make and compare predictions the way an LLM does ​
  - Evaluate an AI's output critically rather than accepting it at face value ​
  - explain how the wording of a prompt affects the quality of an LLM's
  - identify the elements of an effective prompt: role, audience, task, constraints ​
  - compare outputs from different prompts and evaluate which is more useful


### Evidence of learning (success criteria)
  - I can explain why using recycled materials is a more sustainable design choice ​
  - I can explain what AI is and give two examples from my everyday life​
  - I can describe what 'LLM' stands for and what it does​
  - I can explain that LLMs learn by finding patterns in huge amounts of text​
  - I can explain why AI can sometimes get things wrong or make things up​
  - I can explain the difference between an AI predicting something and actually understanding it​
  - I can think of a situation where relying on AI might cause a problem​
  - I can write a prompt that gives an LLM enough information to give a useful answer
  - I can explain why a vague prompt produces a worse result than a specific one​
  - I can compare two AI responses and identify which prompt produced the better one
