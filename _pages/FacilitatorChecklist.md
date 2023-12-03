---
layout: collection
title: "Facilitator Checklist"
collection: facilitatorchecklist
permalink: /facilitatorchecklist/
author_profile: false
published: true
---

![Staging Discussion]({{ site.baseurl }}/assets/images/staging.png)

<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Interactive Checklist</title>

  <style>
    /* Style the checkbox container */
    .checkbox-container {
      list-style-type: none;
      padding: 0;
    }

    /* Style the list items */
    .checkbox-item {
      display: flex;
      align-items: center;
      margin-bottom: 10px;
    }

    /* Style the checkbox */
    .checkbox-input {
      margin-right: 10px;
    }
  </style>
</head>
<body>

  <ul class="checkbox-container" id="checkboxList"></ul>

  <script>
    // Array of tasks
    const tasks = [
      "Use the room",
      "Use Templates for gathering data",
      "Methods: Balance amount and complexity",
      "Have a visible agenda",
      "Make intro and outro",
      "Inform about previous outcomes",
      "Use Boundary Objects",
      "Stage the workshop",
      "Remember to add breaks",
      "Consider your audience",
      "Respect the timeframes",
      "Use Gamification",
      "Be prepared in advance",
      "Gather the needed equipment in advance",
      "Bring snacks!"
    ];

    // Get the checkboxList container
    const checkboxList = document.getElementById('checkboxList');

    // Populate the checklist using the tasks array
    tasks.forEach((task, index) => {
      const listItem = document.createElement('li');
      listItem.classList.add('checkbox-item');

      const checkbox = document.createElement('input');
      checkbox.type = 'checkbox';
      checkbox.classList.add('checkbox-input');
      checkbox.id = `task${index + 1}`;

      const label = document.createElement('label');
      label.htmlFor = `task${index + 1}`;
      label.textContent = task;

      listItem.appendChild(checkbox);
      listItem.appendChild(label);

      checkboxList.appendChild(listItem);
    });
  </script>

</body>
</html>


