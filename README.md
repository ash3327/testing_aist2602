# Introduction
Here is a brief introduction of the task we have to be done in this project.
Based on the material in the issues folder, the following tasks are assigned to us:
1. Create the issues of the tasks
2. Create the project board for tracking the progress of the project.
3. Modify the README.md file. Insert 3 section: Introduction, Code, Contributors. List the tasks that are required to be done. (Current task)
4. Edit the Contributors section in README.md. The required infromation can be found in `_students`. If the required documents have not been created in that folder, you may reminded the teammates to do so. 
5. Check the items mentioned in `task5.md` to make sure that the required infromation are presented.
6. Create a simple code with the programming language C and remove some unwanted lines as told by the instruction.
7. Update teh readme.md file with the specified markdown style. In this task, you may get more infromation from the link probivded in `task7.md`
8. Inset the last updated time for the repo and publicize this repo by posting the link on the public repo of this course.

For more details of these tasks, please refer to the `tasks.md` file.


# Code 


# Contributors
{% for student in site.students %}
  <ul>
    <li><img src="{{ student.image }}" width=50 height=50><a href="https://github.com/{{ student.user }}">@{{ student.user }}</a> ({{ student.name }})</li>
    <ul>
      <li>{{ staff_member.content | markdownify }}</li>
    </ul>
  </ul>
{% endfor %}

**Please read `tasks.md` to start your work.**
