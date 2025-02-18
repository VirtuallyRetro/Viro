# Viro Version 1.0.

Viro the virtual, retro inspired, fully programable computer system for all of us that love retro systems but lack the space, tools, or required skills to create something physical.

## Features.
    Terminal
    Code Editor
    Assembly Language Instruction Set
    Graphics and Sound SubSystems
    Font Editor
    Options Dialogs
    Indepth Systems Manual

## Changes in Version 1.0
    Initial Version 1.0 Final Release Build.
    Runtime: Fixed bug in final updating of debug pane after program completion.

## Changes in Version 1.0 RC4
    Code Editor: Added a colour picker to allow easy selection and insertion of colour indexes.
    Code Editor: Added a keyboard listener tool for easy insertion of key values.
    Code Editor: Added a font editor to allow quick and easy modification of the font set.
    Code Editor: Added a new dialog based string tool.
    Code Editor: Altered keyboard shortcut for Metrics Viewer.
    Code Editor: Removed keyboard shortcut for full font editor.
    Code Editor: Removed memory reset as not needed.
    Compiler: Compiler now checks for filename case when linking resources.
    Compiler: Assembly instructions are now case sensitive, though labels, ports, constant and directives are not.
    Compiler: Added additional messaging for hidden/protect ported addresses.
    Compiler: Added hidden port addresses to the protected list.
    Compiler: Added remove single instance memory blocks at end of compile.
    Compiler: Fixed bug in .ORG instruction logic.
    Font Editor: Improved .ignoreLocal detection accounting for it being commented out.
    General: Visual improvements
    Graphics: Added optional True / False parameter to ClearScreen, to clear all buffers if required.
    Language: Change pcd to pds (Push Data Stack)
    Main Terminal: Added check for correct path case when setting path or changing directories.
    Main Terminal: Added an about dialog.
    Main Terminal: Added a password confirmation dialog for locking and unlocking the project.
    Main Terminal: Corrected a logic issue with the password system.
    Main Terminal: Corrected a logic issue with LS command.
    Main Terminal: Removed flags system and added an options dialog.
    Main Terminal: Reorganised the command processor for ease of management.
    Metrics Viewer: Added total engine calls.
    Options Dialog: Added options to set the debug pane update frequency.
    Runtime: Adjusted the way and frequency in which the debug pane is updates in the Debug engine.
    Runtime: Added NULL and Zero byte checking to the FileIO system.
    Runtime: Added prior value checking to the trigger register system, to stop excessive signal processing
    Runtime: Added RTI trap when used when an IRQ is not active.
    Runtime: Adjusted IRQ logic to use a register for active status.
    Runtime: Adjusted scheduler for increased performance.
    Runtime: Adjusted memory bit-mask to default to code not variables.
    Runtime: Adjusted performance calculation and debug pane display.
    Runtime: Adjusted performance engine tweak setting to better match CPU usage of Debug engine.
    Runtime: Adjusted screen refresh logic to use a register.
    Runtime: Altered keyboard shortcuts for Trace Mode and the Debug Pane.
    Runtime: Corrected logic for soft IRQ so it can’t be fired if an IRQ is already active.
    Runtime: Debug engine now remembers the last debug pane displayed on subsequent executions.
    Runtime: Decoupled all sub systems from the runtime engines.
    Runtime: Disabled PC and Address checking since implementation of memory bit-mask.
    Runtime: Fixed a bug where the debug engine was being run twice almost instantly which could lead to a crash.
    Runtime: Removed memory import / export requirements.
    Runtime: Separated the debug and performance engines.
    System: Added a check that the home and sub paths exist on load.
    System: Added unsaved project prompt, on all systems that may result in code/settings loss.
    System: Changed Min / Max screen resolutions from hardcoded to system variables.
    System: Changed ‘Sounds’ singleton to ‘Audio’
    System: Fixed bug where program would remain paused when clicking exit on the main window.
    System: Remapped all keyboard shortcuts with generic names so that using them in other systems is more understandable.
    System: Removed screen resizing and additional improvements to the system script.

## Screen Shots.

![Screenshot 2025-02-19 at 3 43 16 am](https://github.com/user-attachments/assets/31311d96-6b2b-4907-9907-eb84ceedabc5)<br>
![Screenshot 2025-02-19 at 3 42 44 am](https://github.com/user-attachments/assets/47083fc3-89fd-4176-88c6-cf999bd0aa6d)<br>
![Screenshot 2025-02-19 at 3 42 30 am](https://github.com/user-attachments/assets/808b60ad-9ea7-4a61-a7d4-45030517b284)<br>
![Screenshot 2025-02-19 at 3 41 25 am](https://github.com/user-attachments/assets/7d9715e2-be41-4369-bd71-c40543099409)<br>
![Screenshot 2025-02-19 at 3 41 12 am](https://github.com/user-attachments/assets/018961b9-ad5a-49ac-afef-27e5170c82fc)



