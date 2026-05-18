---
type: lesson
unit_id: core
lesson_id: 03_coding
lesson_no: 03
lesson_title: Coding Blossom
year_level: [5, 6]
duration_min: 90
lesson_summary: In the third lesson, students learn the basics of coding by creating a simple guessing game in Scratch.
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
  - title: Lesson 3 slides - Coding Blossom (PPTX)
    url: ../../../../assets/slides/OutbackRobots_Lesson3_Slides_CodingBlossom.pptx
  - title: Lesson 3 slides - Coding Blossom (PDF)
    url: ../../../../assets/slides/OutbackRobots_Lesson3_Slides_CodingBlossom.pdf
build_videos: 
  - title: Lesson 3 - Building Blossom's Spine
    watch_url: https://www.youtube.com/watch?v=Rs1Ef0Qb2fA
    embed_url: https://www.youtube.com/embed/Rs1Ef0Qb2fA?si=mSLJ4aLQNyX5s7mu
worksheets: 
other_materials: 
  - title: Lesson 3 - Coding Blossom (Scratch Project)
    url: ../../../../assets/other/Lesson03_ScratchCode_BlossomGame.sb3
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

![Lesson3 slides - Coding Blossom](../../../../assets/slides/OutbackRobots_Lesson3_Slides_CodingBlossom.pdf){ type=application/pdf style="min-height:50vh;width:80%"}

### Worksheets
{% if page.meta.worksheets %}
{% for item in page.meta.worksheets %}
- [{{ item.title }}]({{ item.url }})
{% endfor %}
{% else %}
This lesson has no worksheets.
{% endif %}

### Build videos

[Lesson 3 - Building Blossom's Spine - Watch on YouTube](https://www.youtube.com/watch?v=Rs1Ef0Qb2fA)

<iframe width="560" height="315" src="https://www.youtube.com/embed/Rs1Ef0Qb2fA?si=mSLJ4aLQNyX5s7mu" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

### Scratch project

1. Download the Scratch starter project:
  [Lesson 3 - Coding Blossom (Scratch Project)](../../../../assets/other/Lesson03_ScratchCode_BlossomGame.sb3)

2. Open Scratch at
  [www.scratch.mit.edu](https://scratch.mit.edu/projects/editor/)

3. Click:
   File → Load from your computer

4. Select the downloaded file.

#### Blossom sprites
You should not need the image files as they are already included in the Scratch project, but here they are if needed:
[Blossom sprites (ZIP)](../../../../assets/other/Lesson03_BlossomGame_Sprites.zip)

---

## Lesson overview

### Lesson Plan
  1. Lesson 2 Recap - 5 min​
  2. What is coding – 10 min​
    - 2.1 Introduction​
    - 2.2 Play the guessing game with friends​
  3. Code the game in Scratch – 40 min​
    - 3.1 If-else statements​
    - 3.2 Loops​
    - 3.3 Create your own blocks​
    - 3.4 Code the game​
  4. Building Blossom’s base - 25 min​
  5. Why coding discussion - optional​
  6. Survey - 5 min​
  7. Summary - 5 min​


### Learning objectives
After this lesson, students will be able to  

  - explain what coding is and why/where it is important to know,​
  - design algorithms involving multiple alternatives (branching) and iteration​, 
  - implement algorithms using visual programming, involving control structures (such as “if/then”)​.

### Evidence of learning (success criteria)
  - I can explain what coding is and why it is important.​
  - I can design an algorithm with different outcomes and repeated steps.​
  - I can use IF statements to control what happens in my program.​
  - I can use loops to repeat actions in my code.​
  - I can create and use my own custom blocks with meaningful names.​
  - I can use variables to store information (like a random number) in Scratch.​
  - I can explain how robots use sensors, code, and motors to respond to their environment.​
  - I can describe how computers use binary (0s and 1s) to communicate information.​

