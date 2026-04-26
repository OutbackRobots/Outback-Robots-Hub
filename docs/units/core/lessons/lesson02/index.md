---
type: lesson
unit_id: core
lesson_id: 02_sensing
lesson_no: 02
lesson_title: Sensing the World - From Signals to Data
year_level: [5, 6]
duration_min: 90
lesson_summary: This lesson teaches students the fundamentals of how robots sense their environment and convert those signals into useful data.
classroom_setup_and_delivery_considerations: []
robot_use: building         # building|interaction
internet_required: no # yes|no|optional
devices:          # per_student|pair|group
core_concepts: []
curriculum_links: []
learning_objectives: 
  - Add learning objectives in front matter under learning_objectives as a list.
success_criteria: 
  - Add success criteria in front matter under success_criteria as a list.
slides:
  - title: Lesson 2 slides - Sensing the World (PPTX)
    url: ../../../../assets/slides/OutbackRobots_Lesson2_Slides_SensingTheWorld.pptx
  - title: Lesson 2 slides - Sensing the World (PDF)
    url: ../../../../assets/slides/OutbackRobots_Lesson2_Slides_SensingTheWorld.pdf
build_videos: 
  - title: Lesson 2 - Building Blossom's Spine
    watch_url: https://www.youtube.com/watch?v=Rs1Ef0Qb2fA
    embed_url: https://www.youtube.com/embed/Rs1Ef0Qb2fA?si=mSLJ4aLQNyX5s7mu
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

![Lesson2 slides - Sensing the World](../../../../assets/slides/OutbackRobots_Lesson2_Slides_SensingTheWorld.pdf){ type=application/pdf style="min-height:50vh;width:80%"}

### Worksheets
{% if page.meta.worksheets %}
{% for item in page.meta.worksheets %}
- [{{ item.title }}]({{ item.url }})
{% endfor %}
{% else %}
This lesson has no worksheets.
{% endif %}

### Build videos

[Lesson 2 - Building Blossom's Spine - Watch on YouTube](https://www.youtube.com/watch?v=Rs1Ef0Qb2fA)

<iframe width="560" height="315" src="https://www.youtube.com/embed/Rs1Ef0Qb2fA?si=mSLJ4aLQNyX5s7mu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


---

## Lesson overview

### Lesson Plan
  1. Lesson 1 Recap - 5 min​
  2. Sensors – 15 min​
    - 2.1 From Human to Robot Senses​
    - 2.2 Types of Sensors​
  3. Language of Machines – 30 min​
    - 3.1 Control Process in Humans and Robots​
  	- 3.2 Electricity (off/on)  ​
    - 3.3 Bits and Bytes  ​
    - 3.4 (Spelling in) Binary ​
    - 3.5 Optional extension: Binary beads or Counting in binary – 15-30 min​
    - 3.6 Programming Languages  ​
  4. Building Blossom’s head - 30 min​
  5. Survey - 5 min​
  6. Summary - 5 min​


### Learning objectives
After this lesson, students will be able to  

  - explain the function of sensors in robots and other machines,​
  - identify different types of sensors and what each one senses,​
  - describe the control process sequence in robots and other machines ​(sensor input → computer with code → motor → movement)​
  - describe how computers use 0/1 (off/on) to represent information,​
  - encode and decode a short word using a binary code chart,​
  - understand what programming languages are.​

### Evidence of learning (success criteria)
  - I can explain what sensors are used for inside of robots and other machines.​
  - I can name three different types of sensors and what they measure.​
  - I can outline the order of processing inside the Blossom robot that is needed to turn environmental input into an action. (input → sensor → computer with code → motor position → movement)​
  - I can describe how computers use electricity to communicate information with off- and on-states (0/1).​
  - I can encode and decode a short word in binary using the class chart.​
  - I can explain that programming languages are a human-friendly way to write instructions that computers can understand.​


