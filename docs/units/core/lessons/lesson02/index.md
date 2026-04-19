---
type: lesson
unit_id: core
lesson_id: 02_sensing
lesson_no: 02
lesson_title: Sensing the world
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
  - title: Lesson 2 slides - Sensing the world (PPTX)
    url: ../../../../assets/slides/OutbackRobots_Lesson2_Slides_SensingTheWorld.pptx
  - title: Lesson 2 slides - Sensing the world (PDF)
    url: ../../../../assets/slides/OutbackRobots_Lesson2_Slides_SensingTheWorld.pdf
build_videos: 
  - title: Building Blossom's Spine - Video
    url: ../../../../../assets/videos/Lesson02_BlossomSpine.mp4
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

![Lesson2 slides - Sensing the world](../../../../assets/slides/OutbackRobots_Lesson2_Slides_SensingTheWorld.pdf){ type=application/pdf style="min-height:50vh;width:80%"}

### Build videos
{% if page.meta.build_videos %}
{% for item in page.meta.build_videos %}
- [{{ item.title }}]({{ item.url }})
{% endfor %}
{% else %}
Add build video links in front matter under build_videos as title + url.
{% endif %}

<video controls>
  <source src="../../../../../assets/videos/Lesson02_BlossomSpine.mp4" type="video/mp4">
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
(Where does it fit in the unit and why is it here?)
(What teachers need to know to teach this lesson)

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