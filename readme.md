{% comment %}

# This team hasn't started yet...

Check back later!

**Please read `tasks.md` to start your work.**

{% endcomment %}

### **Introduction**
Our team will do
- Task 1) Staring issues
- Task 2) Project board
- Task 3) Set up readme.md
- Task 4) Write C code
- Task 5) Get a status badge
- Task 6) Showcase your team
- Task 7) Register your repo
 
### **Code**

```c
{% include_relative code.c %}
```

![badge](https://github.com/div1121/project-team-a-try/blob/master/image_for_c.JPG?raw=true)

![example workflow](https://github.com/div1121/project-team-a-try/actions/workflows/c-cpp.yml/badge.svg)

### **Contribution**
{% for student in site.stu %}
    <img alt="student image" src="{{student.image}}">
    <h3>@{{ student.user }} ({{ student.name }}</h3>
    <p>{{ student.content | markdownify }}</p>
{% endfor %}