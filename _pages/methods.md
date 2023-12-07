---
layout: collection
title: "Methods📜"
collection: methods
permalink: /methods/
author_profile: false
published: true
sidebar:
  nav: "methods"
---
<style>
  .container {
    overflow: hidden; /* Allow container to scroll if needed */
    height: 100%; /* Adjust height to 100% */
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    align-items: flex-start;
    width: 100%;
  }

  details {
    width: 100%;
    background: #E5D5BA;
    border-color: black; /* This line sets the border color to black */
    color: rgba(255, 255, 255, 0.9);
    border: 2px solid;
    cursor: pointer;
    transition: background 0.3s, color 0.3s, border-color 0.3s, all 0.6s;
    border-radius: 4px;
    min-height: 48px;
    /*max-height: 60px;*/
  }

  details:hover {
    border-color: #878d99;
    color: rgba(255, 255, 255, 0.6);
  }

  details:active {
    color: rgba(255, 255, 255, 0.9);
    border-color: #6d7380;
  }

  details + details {
    margin-top: 10px;
  }

  details p {
    color: black;
    line-height: 1.7;
    margin: 10px 0 0;
    padding: 0 20px 15px;
  }


  details.square {
    color: black;
    background: #E5D5BA;
  }

  details[open] {
    transition: background 0.3s, color 0.3s, border-color 0.3s, all 0.6s;
    /*min-height: 100px;*/
    /*max-height: 200px;*/
  }

  summary {
    list-style: none;
    outline: none;
    font-size: 16px;
    font-style: bold;
    padding: 13px;
    width: 100%;
    color: black;
  }

  summary:selection {
    background: transparent;
  }

  summary .close {
    display: none;
  }

  [open] summary .close {
    display: inline;
  }

  summary .open {
    display: inline;
  }

  [open] summary .open {
    display: none;
  }

  [open] summary {
    display: inline;
  }

  summary:after {
    margin-top: 2px;
    content: "➕";
    float: left;
    margin-right: 11px;
    text-align: center;
    font-size: 11px;
  }

  [open] summary:after {
    padding: 0 0 12px 0;
    content: "➖";
  }

  marker {
    display: none;
  }
  .separator {
      border: 0.5px solid gray;
      margin: 20px 0;
    }
</style>

![Methods Double Diamond]({{ site.baseurl }}/assets/images/methodsdd.png)

<p><small>For structuring the method tab, we choose to categorize the methods according to double diamond phases, to ensure alignment between the design frameworks and methods. Introduction, ice breakers and energizers are in a seperate category, since these does not fit into the double diamond framework, but should always be considered for workshops. </small></p>

<p><small>When designing a workshop the idea is to pick and choose from the methods by deciding which methods that are relevant and beneficial for the specific workshop. Remember that several of the methods fit into different phases of the workshop and they are not locked to be used in only one part of the workshop.</small>🤹🏻‍♀️ 🧾</p>

<div class="container">

<span id="Introduction"></span><span style="display: none;">[Reference to Introduction](#Introduction)</span>
<h2>INTRODUCTION AND ICEBREAKERS 🏁</h2>

<span id="Nametag"></span><span style="display: none;">[Reference to Nametag](#Nametag)</span> 
<h5>Nametag Exercise</h5>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/Nametag.png" alt="Nametag">
      <small>Link to template from Universal design guide: </small><br>
      <small><a href="https://universaldesignguide.com/wp-content/uploads/Template_nametag.pdf">Link to template</a></small>
  </details>

<span id="Song"></span><span style="display: none;">[Reference to Song](#Song)</span> 
<h5>Who Owns this Song?</h5>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/Song.png" alt="Song">
  </details>

<span id="TallTales"></span><span style="display: none;">[Reference to TallTales](#TallTales)</span> 
<h5>Tall Tales</h5>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/TallTales.png" alt="TallTales">
  </details>

<span id="PresentYourPartner"></span><span style="display: none;">[Reference to PresentYourPartner](#PresentYourPartner)</span> 
<h5>Present Your Partner</h5>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/PresentYourPartner.png" alt="PresentYourPartner">
  </details>


<span id="Energizers"></span><span style="display: none;">[Reference to Energizers](#Energizers)</span>
<h2>ENERGIZERS 🏃‍♀️</h2>

  <span id="Basketball"></span><span style="display: none;">[Reference to Basketball](#Basketball)</span>
<h5>Basketball</h5>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/Basketball.png" alt="Basketball">

  </details>

  <span id="HumanKnot"></span><span style="display: none;">[Reference to HumanKnot](#HumanKnot)</span>
<h5>The Human Knot</h5>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/HumanKnot.png" alt="HumanKnot">

  </details>

  <span id="CircleOfStretch"></span><span style="display: none;">[Reference to CircleOfStretch](#CircleOfStretch)</span>
<h5>Circle of Stretch</h5>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/CircleOfStretch.png" alt="CircleOfStretch">

  </details>

  <span id="BodyTapping"></span><span style="display: none;">[Reference to BodyTapping](#BodyTapping)</span>
<h5>Body Tapping</h5>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/BodyTapping.png" alt="BodyTapping">

  </details>

<span id="Discover"></span><span style="display: none;">[Reference to Discover](#Discover)</span>
<h2>DISCOVER🔰</h2>

<span id="DeskResearch"></span><span style="display: none;">[Reference to DeskResearch](#DeskResearch)</span>
<h5>Desk Research</h5>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/DeskResearch.png" alt="DeskResearch">

  </details>

<span id="CreateEmpathy"></span><span style="display: none;">[Reference to CreateEmpathy](#CreateEmpathy)</span>
<h5>Create Empathy: Video of User</h5>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/CreateEmpathy.png" alt="CreateEmpathy">

  </details>

  <span id="GameDesign"></span><span style="display: none;">[Reference to GameDesign](#GameDesign)</span>
<h5>Design Games</h5>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/GameDesign.png" alt="GameDesign">

  </details>

  <span id="GamePiece"></span><span style="display: none;">[Reference to GamePiece](#GamePiece)</span>
<h5>Game Piece for Design Game</h5>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/GamePiece.png" alt="GamePiece">

  </details>

  <span id="ActorWorlds"></span><span style="display: none;">[Reference to ActorWorlds](#ActorWorlds)</span>
<h5>Actor Worlds</h5>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/ActorWorlds.png" alt="ActorWorlds">

  </details>

  <span id="MessyMap"></span><span style="display: none;">[Reference to MessyMap](#MessyMap)</span>
<h5>Situational Mapping - Messy Map</h5>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/MessyMap.png" alt="MessyMap">

  </details>

  <span id="OrderedMap"></span><span style="display: none;">[Reference to OrderedMap](#OrderedMap)</span>
<h5>Situational Mapping - Ordered Map</h5>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/OrderedMap.png" alt="OrderedMap">

  </details>

  <span id="RelationalMap"></span><span style="display: none;">[Reference to RelationalMap](#RelationalMap)</span>
<h5>Situational Mapping - Relational Map</h5>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/RelationalMap.png" alt="RelationalMap">

  </details>

  <span id="AbilityPromptCards"></span><span style="display: none;">[Reference to AbilityPromptCards](#AbilityPromptCards)</span>
<h5>Ability Prompt Cards</h5>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/AbilityPromptCards.png" alt="AbilityPromptCards">

  </details>

  <span id="DevelopmentArea"></span><span style="display: none;">[Reference to DevelopmentArea](#DevelopmentArea)</span>
<h5>Development Arena</h5>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/DevelopmentArea.png" alt="DevelopmentArea">
  </details>


<span id="Define"></span><span style="display: none;">[Reference to Define](#Define)</span>
<h2>DEFINE 🗃️</h2>

  <span id="Personas"></span><span style="display: none;">[Reference to Personas](#Personas)</span>
<h5>Personas</h5>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/Personas.png" alt="Personas">
      <small>Link to template: </small>
      <small>Template from “The Universal Design Guide”: </small>
      <small><a href="https://universaldesignguide.com/wp-content/uploads/Persona_v2.pdf">Link to template</a></small>
  </details>

<span id="UserJourney"></span><span style="display: none;">[Reference to UserJourney](#UserJourney)</span>
<h5>User Journey</h5>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/UserJourney.png" alt="UserJourney">
      <small>Link to template: </small>
      <small>Template from “The Universal Design Guide”: </small>
      <small><a href="https://universaldesignguide.com/wp-content/uploads/Journey-map-v2.pdf">Link to template</a></small>
  </details>

  <span id="ActorNetwork"></span><span style="display: none;">[Reference to ActorNetwork](#ActorNetwork)</span>
<h5>Actor Network</h5>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/ActorNetwork.png" alt="ActorNetwork">

  </details>

  <span id="BullsEyes"></span><span style="display: none;">[Reference to BullsEyes](#BullsEyes)</span>
<h5>Bulls Eyes Categorization</h5>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/BullsEyes.png" alt="BullsEyes">

  </details>

<span id="Develop"></span><span style="display: none;">[Reference to Develop](#Develop)</span>
<h2>DEVELOP 🦾</h2>

  <span id="NegativeBrainstorming"></span><span style="display: none;">[Reference to NegativeBrainstorming](#NegativeBrainstorming)</span>
<h5>Negative Brainstorming</h5>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/NegativeBrainstorming.png" alt="NegativeBrainstorming">

  </details>

  <span id="BrainstormBox"></span><span style="display: none;">[Reference to BrainstormBox](#BrainstormBox)</span>
<h5>Brainstorm Box</h5>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/BrainstormBox.png" alt="BrainstormBox">

  </details>

  <span id="SilentBrainstorm"></span><span style="display: none;">[Reference to SilentBrainstorm](#SilentBrainstorm)</span>
<h5>Silent Brainstorm</h5>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/SilentBrainstorm.png" alt="SilentBrainstorm">

  </details>

  <span id="EvaluationMatrix"></span><span style="display: none;">[Reference to EvaluationMatrix](#EvaluationMatrix)</span>
<h5>Evaluation Matrix</h5>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/EvaluationMatrix.png" alt="EvaluationMatrix">
  </details>

  <span id="IdeaParkingLot"></span><span style="display: none;">[Reference to IdeaParkingLot](#IdeaParkingLot)</span>
<h5>Idea Parking Lot</h5>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/IdeaParkingLot.png" alt="IdeaParkingLot">
  </details>

  <span id="Neighbors"></span><span style="display: none;">[Reference to Neighbors](#Neighbors)</span>
<h5>Present your Neighbors</h5>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/Neighbors.png" alt="Neighbors">
  </details>


  <span id="Deliver"></span><span style="display: none;">[Reference to Deliver](#Deliver)</span>
<h2>DELIVER 📦</h2>

  <span id="IdeaWithIn"></span><span style="display: none;">[Reference to IdeaWithIn](#IdeaWithIn)</span>
<h5>Concept development - Idea with/ Idea in</h5>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/IdeaWithIn.png" alt="IdeaWithIn">
  </details>

  <span id="Prototyping"></span><span style="display: none;">[Reference to Prototyping](#Prototyping)</span>
<h5>Prototyping</h5>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/Prototyping.png" alt="Prototyping">
  </details>

  <span id="PosterTemplate"></span><span style="display: none;">[Reference to PosterTemplate](#PosterTemplate)</span>
<h5>PosterTemplate</h5>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/PosterTemplate.png" alt="PosterTemplate">
  </details>

  <span id="BuildMeasureLearn"></span><span style="display: none;">[Reference to BuildMeasureLearn](#BuildMeasureLearn)</span>
<h5>Build - Measure - Learn</h5>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/BuildMeasureLearn.png" alt="BuildMeasureLearn">
  </details>

  <span id="Difference"></span><span style="display: none;">[Reference to Difference](#Difference)</span>
<h5>The Difference that Matters</h5>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/Difference.png" alt="Difference">
  </details>


  <span id="ProsCons"></span><span style="display: none;">[Reference to ProsCons](#ProsCons)</span>
<h5>Pros and Cons</h5>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/ProsCons.png" alt="ProsCons">
  </details>

  <span id="StrengthsNWeaknesses"></span><span style="display: none;">[Reference to StrengthsNWeaknesses](#StrengthsNWeaknesses)</span>
<h5>Strengths and Weaknesses</h5>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/StrengthsNWeaknesses.png" alt="StrengthsNWeaknesses">
  </details>

</div>

<br>
<hr class="separator">
<span id="references"></span>
<h5>References:</h5> <span style="display: none;">[Reference to References](#references)</span>
[Playbook Method References PDF]({{ site.baseurl }}/assets/pdf/method_references.pdf)

