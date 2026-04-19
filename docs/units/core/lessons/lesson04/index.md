---
type: lesson
unit_id: core
lesson_id: 00_name
lesson_no: 00
lesson_title: name
year_level: [5, 6]
duration_min: 90
lesson_summary: One-sentence lesson summary.
classroom_setup_and_delivery_considerations: []
robot_use:          # building|interaction
internet_required:  # yes|no|optional
devices:          # per_student|pair|group
core_concepts: []
curriculum_links: []
learning_objectives: 
  - Add learning objectives in front matter under learning_objectives as a list.
success_criteria: 
  - Add success criteria in front matter under success_criteria as a list.
slides:
  - title: Lesson 1 slides - Meet Blossom (PPTX)
    url: ../../../../assets/slides/OutbackRobots_Lesson1_Slides_MeetBlossom.pptx
  - title: Lesson 1 slides - Meet Blossom (PDF)
    url: ../../../../assets/slides/OutbackRobots_Lesson1_Slides_MeetBlossom.pdf
build_videos: 
  - title: Building Blossom's Head - Video
    url: ../../../../../assets/videos/Lesson01_BlossomHead.mp4
worksheets: 
  - title: Encode a Mystery Word in Binary - Worksheet (PDF)
    url: ../../../../assets/worksheets/lesson02_worksheet_EncodeAMysteryWordInBinary.pdf
  - title: Encode a Mystery Word in Binary - Worksheet (DOCX)
    url: ../../../../assets/worksheets/lesson02_worksheet_EncodeAMysteryWordInBinary.docx
other_materials: []
activities: []
tags: []
status: draft
version: v0.1
---

# Lesson {{ page.meta.lesson_no }} - {{ page.meta.lesson_title }}

*{{ page.meta.lesson_summary }}*

!!! tip "At a glance"
    - :material-kangaroo: **Unit:** {{ page.meta.unit_id }}
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

![Lesson1 slides - Meet Blossom](../../../../assets/slides/OutbackRobots_Lesson1_Slides_MeetBlossom.pdf){ type=application/pdf style="min-height:50vh;width:80%"}

### Build videos
{% if page.meta.build_videos %}
{% for item in page.meta.build_videos %}
- [{{ item.title }}]({{ item.url }})
{% endfor %}
{% else %}
Add build video links in front matter under build_videos as title + url.
{% endif %}

<video controls>
  <source src="../../../../../assets/videos/Lesson01_BlossomHead.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>

### Worksheets
{% if page.meta.worksheets %}
{% for item in page.meta.worksheets %}
- [{{ item.title }}]({{ item.url }})
{% endfor %}
{% else %}
This lesson has no worksheets.
{% endif %}



--- 
## Lesson overview
After the previous lesson explained broadly what Artificial Intelligence is, lesson four focuses on a specific subclass of AI: generative Artificial Intelligence. GenAI includes all models that generate new content such as text, images, audio, or videos. A currently very popular Large Language Models such as ChatGPT, Google Gemini, or Microsoft Copilot are an example of genAI. They have fundamentally changed how humans interact with technology.  The use Large language Models, however, comes with many challenges and limitations. While they seem to understand our language, thoughts and feelings, they are purely based on probabilities and patterns that they "learned" from the massive amount of data they were trained on.
In this lesson, students will acquire an understanding of what the core limitations are and what they need to keep in mind when using generative AI models.

### Lesson Plan
(High-level structure with timings)

### Learning objectives
"I can..." statements to assess whether students have met the learning objectives
{% if page.meta.learning_objectives %}
{% for obj in page.meta.learning_objectives %}
- {{ obj }}
{% endfor %}
{% else %}
- Add learning objectives in front matter under learning_objectives as a list.
{% endif %}

### Evidence of learning (success criteria)
{% if page.meta.success_criteria %}
{% for criteria in page.meta.success_criteria %}
- {{ criteria }}
{% endfor %}
{% else %}
- Add success criteria in front matter under success_criteria as a list.
{% endif %}