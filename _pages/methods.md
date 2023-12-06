---
layout: collection
title: "Methods"
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
</style>

<div class="container">
<h3>Nametag Exercise</h3>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/Nametag.png" alt="Nametag">
      <small>Link to template: </small>
      <small>Template from “The Universal Design Guide”: </small>
      <small><a href="https://universaldesignguide.com/wp-content/uploads/Template_nametag.pdf">Link to template</a></small>
  </details>
<h3>Desk Research</h3>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/DeskResearch.png" alt="DeskResearch">
      
  </details>
<h3>Personas</h3>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/Personas.png" alt="Personas">
      <small>Link to template: </small>
      <small>Template from “The Universal Design Guide”: </small>
      <small><a href="https://universaldesignguide.com/wp-content/uploads/Persona_v2.pdf">Link to template</a></small>
  </details>
<h3>User Journey</h3>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/UserJourney.png" alt="UserJourney">
      <small>Link to template: </small>
      <small>Template from “The Universal Design Guide”: </small>
      <small><a href="https://universaldesignguide.com/wp-content/uploads/Journey-map-v2.pdf">Link to template</a></small>
  </details>
<h3>Prototyping</h3>
  <details class="default square">
      <summary>Click to <span class="open">open</span><span class="close">close</span></summary>
      <img src="{{ site.baseurl }}/assets/images/Prototyping.png" alt="Prototyping">
  </details>
</div>


