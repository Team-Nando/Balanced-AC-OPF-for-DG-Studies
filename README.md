# Balanced-AC-OPF-for-DG-Studies
AIMMS Code - A Balanced AC OPF for Operation and Planning Studies Involving Distributed Generation

This AIMMS code is part of block 2 and corresponds to Day 3 “Orchestration of DER and Active Distribution Networks” and is part of the 5-day PhD-level short course on "Advanced Modelling of DER-Rich Active Distribution Networks” delivered by the Power and Energy Systems Group and the Melbourne Energy Institute from Monday 19th to Friday 23rd July 2021.

Videos and more info: https://electrical.eng.unimelb.edu.au/power-energy/courses/2021-07

## Using AIMMS

* Step 1. Install AIMMS.
  * Affiliated with a University. Install the free academic license of AIMMS. You will need to register (https://licensing.cloud.aimms.com/license/academic.htm).
  * Non-affiliated with a University. Install the free academic license of AIMMS. You will need to register (https://licensing.cloud.aimms.com/license/community.htm).
  * Wait for their confirmation emails and follow their installation instructions (using the license they give you).
* Step 2. Launch AIMMS and accept the terms and conditions.
* Step 3. Download the files from **this repo** and copy all the files (including the subfolder) to your PC or laptop.
* Step 4. Using AIMMS, open the file "ACOPF.aimms".
* Step 5. Play with the code!
  * Click on the tab 'Pages' (bottom left) and then double-click on 'Results' (top right, part of the 'Page Tree').
  * The pre-loaded network parameters and structure correspond to a small MV (balanced) network with three buses 1-2-3.
  * The pre-loaded objective function is to maximise the sum of the active power outputs of the set of Generators.
  * The AC OPF is an NLP problem that works well with CONOPT - which is available with the free license version of AIMMS. So, pick that one (go to \Settings\Solver Configuration).

## Credits

Nando Ochoa (luis.ochoa@unimelb.edu.au)

Michael Liu (michael.liu@unimelb.edu.au)
