# Transition
Transition is a PHP Finite State Machine Package to manage and validate state transitions

## Transitions Goals
 
* Ability to change state
* Know the next available states return for drop down list boxes (DDLB) aka select boxes
* Checks during transition and roll back to previous state
* Use php Enums, including bitmasked definitions of state
* Do states also require permissions? States and gates
* Generate a full state diagram from state
    * Intermediary format of text state diagram -> PlantUML or similar
    * Text state should be able to generate code (stubs) and diagrams
    * Reverse engineering would be awsome  ie code <-> text <-> diagram
* Generate a state skeleton from a text map of states, yaml or similar
* Make state from artisan command `make:transition` create from stubs


## Status - Design Phase
We are currently in design phase and looking to take contributions for #hacktoberfest

## Thoughts 
* is there a way for `.gitignore` to selectively ignore based on branch?
    - ie not merge things to main but have them available on dev and feature branches

## Other state machine libraraies
