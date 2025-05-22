# Project 1: Portable Optical Table

Team: Dr. Jenna Mueller, Ph.D., Dr. Tri Quang, Ph.D., Michele Kaluzienski, and Jason Chen

Time Frame: Fall 2019 – Fall 2021

**NOTE:** If the files are incompatible with your SolidWorks version, please use the included STEP files. Only the main assemblies have both SolidWorks and STEP versions.

## File Structure

- `renders_drawings_images/`: screenshots of the Portable Testing Chamber (PTC) assembly in different states
- `source_files/`:
  - **Main** SolidWorks assembly file is `PTC_Optical_Table_v4.sldasm` (note that this file is slightly ahead of the images shown through this portfolio)
  - Custom computer-aided design (CAD) parts for this assembly
  - Commercial parts used in the assembly
  - Replica looks-like model of the laparoscope device our lab developed
- `assembly_procedure/`:
  - Assembly protocol for PTC
  - `BoM_PTC_Assembly.xlsx`: a bill of materials draft
- `Portable_Optical_Table_Updates.pdf`: slides presented to our lab every 2–3 weeks
- `Project1_Portable_Testing_Chamber_Overview`: labeled diagrams and other information

## Overview

There is a need for accessible laparoscope and camera characterization modalities, especially in low-resource or field-deployable settings. Specifically, we want a testing setup compatible with our low-cost, in-house laparoscope, called the Keyscope. The Portable Testing Chamber (PTC) is designed to facilitate essential laparoscope characterization imaging in a standardized manner, eliminating the need for expensive optical tables and associated components. The PTC ensures reliable testing conditions by effectively blocking out external light and providing uniform internal lighting. We optimized dimensions, materials, structure, and LED lighting through iterative prototyping. In contrast to alternatives like Thorlabs' XE25C9 model, which can exceed $300 in cost and lacks integrated lighting, our solution offers a cost-effective, fully illuminated, and seamlessly compatible option for a variety of laparoscopes. Lastly, this setup emphasizes the incorporation of readily-available components and ease of assembly and repair.

## Goals

- Compatible with a variety of laparoscopes and imaging test targets
- Accessible components that can be easily sourced worldwide
- Low-cost compared to commercial options
- Easy to assemble, disassemble, and replace
  - Requires minimal fabrication tools
  - Avoids permanent adhesives or fixtures (e.g., superglue)
- Restricted to a regular-sized 3D-printer with about a 220mm × 220mm footprint

## Tools Used

- CAD Software: SolidWorks
- Ender 3 pro PLA 3D-printer
- Allen keys
- Band saw

## Project Highlights

- The screw-down clamp and brush-lined opening make PTC compatible with our lab's 5mm and 10mm diameter laparoscopes and a Stryker SOC laparoscope.
- The adjustable posts allow for the characterization of 30-degree laparoscopes as well.
- We ensured that our desired camera working distances were accommodated and that the PTC remained compatible with our image analysis targets, enabling consistent evaluation and effective optimization after each design iteration.
- The enclosure itself mainly consists of PLA, foam, and paper, which costs less than 25% of alternatives such as Thorlabs’ XE25C7/M model.
- We either designed custom parts or sourced lower-cost alternatives. Since we were not using precision tools like lasers, we could tolerate larger manufacturing tolerances.
- The assembly protocol illustrates how easy it is to assemble, disassemble, and replace.
- The only adhesive used is on the brushed weatherstrips, limited to a small, modular section of the frame.
- We strategically split the frame into multiple components that could be easily printed on a hobbyist 3D-printer such as the Ender 3 Pro.
- We took advantage of the disposability of 3D-printed parts, designing features that could be tapped by bolts to create more permanent fixtures when needed.

## What I learned

- I developed skills in SolidWorks, including assemblies, mates, animations, and technical drawings.
- The most important lesson is that a design is only as effective as the metrics used to evaluate it.
  - If the metrics are unrealistic, a lot of time will be wasted trying to meet those requirements.
  - If the tools used to obtain the metrics are inconsistent, it becomes difficult to tell if the incremental changes led to improvements.
- Since not all design requirements can be fully met within a limited timeline, we must prioritize effectively to meet deadlines. For example, we chose to emphasize even, diffuse lighting within the testing chamber over further reducing the costs of the remaining optical components (all optical components are expensive).
- It is important to document every meeting somewhere, and ideally, have someone else review the notes, as they may catch details you missed.
- I learned a lot about collaboration as I worked closely with our post-doc and lab technician on this project. Although I led the CAD work, I had to improve my ability to communicate, justify my design decisions, and resolve disagreements constructively.
- Following protocols is essential because with multiple team members, data collection and image analysis must be consistent across users to establish a reliable baseline for improving the design and achieving our goal.
- The more eyes there are on a challenge, the more likely we are to find the optimal solution. Thus, I deeply value regular presentations.
- This was the first major project where CAD was invaluable not only for modeling our setup, but also for elegantly conveying design decisions to our primary stakeholder, Dr. Mueller.
