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
      padding: 10;
    }

    /* Style the list items */
    .checkbox-item {
      display: flex;
      align-items: baseline;
      margin-bottom: 40px;
    }

    /* Style the vertical stack */
    .v-stack {
      display: flex;
      flex-direction: column;
      margin-left: 10px;
    }

    /* Style the small (description) element */
    .v-stack small {
        flex: 1; /* Allow the small element to grow and take up remaining space */
    }

    /* Style the checkbox */
    .checkbox-input {
      margin-right: 100px;
    }

    /* Style the label list item */
    .checkbox-label-item {
      display: flex;
      flex-direction: column;
    }

    /* Preserve line breaks within labels */
    .checkbox-label-item label {
      white-space: pre-line;
    }
    
  </style>
</head>
<body>

  <h2>BEFORE THE WORKSHOP</h2>

  <ul class="checkbox-container" id="beforeWorkshopList"></ul>

  <h2>DURING THE WORKSHOP</h2>

  <ul class="checkbox-container" id="duringWorkshopList"></ul>

  <script>
    // Array of checklist items for BEFORE THE WORKSHOP
    const beforeWorkshopItems = [
      {
        label: ' Use templates for gathering data.',
        description: 'There are many templates available that complement specific methods and help you and your workshop’s participants to visualize the task and its outcome.'
      },
      {
        label: ' Consider the complexity of Methods.',
        description: 'Your workshop results will thank you if you balance the amount and complexity of your methods, as doing this right can enhance participants’ creativity, energy levels, and willingness to engage.'
      },
      {
        label: ' Consider your audience.',
        description: 'Know your participants. The number of participants dictates the types of methods you can use, but you should also consider their age, mental and physical abilities. Pretending that this is the first workshop your participants have ever been in enhances ease of understanding and clarity.'
      },
      {
        label: ' Be prepared in advance.',
        description: 'Know your agenda and schedule, be familiar with the workshop’s goal and any previous outcomes that need to be explained and be prepared to explain your methods. If the participants feel like you put lots of effort into making the workshop, they are more likely to put their effort into it too!'
      },
      {
        label: ' Gather the needed equipment in advance.',
        description: 'Imagine the printer you wanted to print with on the day of the workshop is out of ink, so you are unable to get your necessary equipment – wouldn’t that be stressful? Don’t leave it to luck, prepare all materials (physical, and digital) at least a day before the workshop. Have everything ready, so your time before the workshop can be spent on mental preparation.'
      },
      {
        label: ' Bring snacks.',
        description: 'If participants have all the necessary amenities in the room, like snacks, water, coffee, tea – they are less likely to keep thinking about the next upcoming break or exit the room during the workshop. Bring them!'
      }
    ];

    // Array of checklist items for DURING THE WORKSHOP
    const duringWorkshopItems = [
      {
        label: ' Make intro and outro.',
        description: 'Allocate designated time for introducing yourself to the participants, and adding an icebreaker or two for participants to get to know each other and establish trust. At the end of the workshop, make sure you wrap up, explain and reframe outcomes of the workshop and ask for participants’ feedback.'
      },
      {
        label: ' Have a visible agenda.',
        description: 'It isn’t enough to simply explain the agenda in the beginning, as most would immediately forget it. Make sure to add an agenda or plan of the workshop, either physical or digital, but visible at all times!'
      },
      {
        label: ' Inform about previous outcomes.',
        description: 'If your workshop builds on a previous project or co-creation process, make sure to allocate time for informing your participants about this and explain the relevant information to them.'
      },
      {
        label: ' Use the room.',
        description: 'This is important for both you, as a facilitator, but also for your participants. The facilitator should use the room to walk around so everyone can hear them and feel their presence – if the facilitator stands in one place for the whole workshop, participants might forget that they are there during an activity, which decreases the preset atmosphere of the workshop. It is also beneficial if the participants are encouraged to use the whole room – if it is a big space, there can be standing/physical methods, but even if the room is small, use the walls or blackboard (put sticky notes on them, draw, put template posters on).'
      },
      {
        label: ' Use boundary objects.',
        description: 'Different people will have different competencies. To bridge the gap between them, you can use objects such as shared tools (play doh, sketches, images), prototypes, shared processes (activities that need contribution from all participants) which are called boundary objects. These help individuals jointly transform their competences and knowledge (Valgeirsdottir, 2023).'
      },
      {
        label: ' Stage the workshop.',
        description: 'It is important that you, as a facilitator, “set the stage” for creative collaboration. Prepare, arrange, and explain activities according to your participants’ needs and abilities, facilitate discussions during the workshop’s activities and reframe the outcome of each activity (Pedersen, 2020).'
      },
      {
        label: ' Remember to add breaks.',
        description: 'Breaks are important to get one out of stagnation or fixation on one task, and they enhance creativity. Make sure you add some breaks, but not too many – this depends on the timeframe of your workshop.'
      },
      {
        label: ' Respect the timeframes.',
        description: 'Make sure to respect the timeslots you allocated to each activity within reason. Starting and finishing the workshop on time shows that you respect your participants’ time, and keeping the timeframes of each activity makes sure that you can go through them all.'
      },
      {
        label: ' Use gamification.',
        description: 'Getting significant insight from all participants is oftentimes easiest if you transform the co-creation processes into playful activities, called design games, that build on some sort of a purpose. They should be simple, they should allow you to include any participant regardless of their abilities, they should have a set of rules that participants adhere to, and they should focus on imagining possibilities instead of demonstrating solutions, hence the playfulness (Valgeirsdottir, 2023).'
      }
    ];

    // Function to create checklist items
    function createChecklistItems(containerId, items) {
      const checkboxList = document.getElementById(containerId);

      items.forEach((item, index) => {
        // Create a container list item
        const listItem = document.createElement('li');
        listItem.classList.add('checkbox-item');

        // Create a checkbox
        const checkbox = document.createElement('input');
        checkbox.type = 'checkbox';
        checkbox.classList.add('checkbox-input');
        checkbox.id = `${containerId}Item${index + 1}`;

        // Create a div for the VStack
        const vStack = document.createElement('div');
        vStack.classList.add('v-stack');

        // Create a label
        const label = document.createElement('label');
        label.htmlFor = `${containerId}Item${index + 1}`;
        label.textContent = item.label;

        // Create a small element for the description
        const small = document.createElement('small');
        small.textContent = item.description;

        // Append elements to the VStack
        vStack.appendChild(label);
        vStack.appendChild(small);

        // Append elements to the list item
        listItem.appendChild(checkbox);
        listItem.appendChild(vStack);

        // Append the list item to the checkboxList
        checkboxList.appendChild(listItem);
      });
    }

    // Create checklist items for BEFORE THE WORKSHOP
    createChecklistItems('beforeWorkshopList', beforeWorkshopItems);

    // Create checklist items for DURING THE WORKSHOP
    createChecklistItems('duringWorkshopList', duringWorkshopItems);
  </script>

</body>
</html>




<small> **References**<small>  
- <small> Pedersen, S., (2020) Staging negotiation spaces: A co-design framework, Design Studies, [https://doi.org/10.1016/j.destud.2020.02.002](https://doi.org/10.1016/j.destud.2020.02.002)<small>  
- <small>Valgeirsdottir, D. (2023) Staging Co-Creation and Creativity, Technical University of Denmark<small>




