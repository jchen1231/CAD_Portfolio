# Project 3: Bobblestat Biosensor

Team: Dr. William E. Bentley, Ph.D., Dr. John Rzasa, Ph.D., Quinn Burke, and Jason Chen

Time Frame: Spring 2024 – Current

**NOTE:** All components were originally made in Fusion 360, but there are STEP file versions for your convenience.

## File Structure

- `renders_drawings_images/`:
  - Device renders
  - Exploded assembly drawing
  - Device screenshots
- `source_files/`:
  - Fusion and STEP files of the most recent Bobblestat device
  - `nondevice_source_files/`:
    - Fusion and STEP files of electrode test rigs
    - Fusion and STEP files of electrode holders
    - Fusion and STEP files of electrode container plate
- `Project3_Bobblestat_Biosensor_Overview.pptx`: labeled diagrams and other information

## Project Overview

One major application of electrochemistry is the monitoring of specific compounds in contained environments, such as bioreactors, reservoirs, or lakes. This has led to growing interest in small, user-friendly, autonomous devices that can interrogate molecular information across diverse environments and trigger electronic or algorithmic responses based on prevailing inputs.

Our research groups—the Bentley and Payne Labs—have been at the forefront of developing “electro-genetics,” a technology that enables programmable activation of genetic circuits engineered into bacterial cells via redox agents. These genetically modified cells are then encapsulated onto an electrode to potentially enable an unprecedented range of detectable chemical compounds and highly dynamic, controlled feedback as a response. The principal means of this bidirectional information transfer—biological-electronic-biological—is redox electrochemistry.

Concurrently, the increasing accessibility of computer-aided design (CAD), printed circuit boards (PCBs), and electronic design automation (EDA) software has spurred interest in their use as alternatives to commercial electrodes. PCBs show promise in this context due to the common application of electroless nickel immersion gold coatings, which enhance durability and soldering. Gold is ideal for electrochemistry not only due to its high conductivity and corrosion resistance but also its exceptional biocompatibility. This project aims to integrate swappable PCB-based electrodes with a potentiostat device to make electrochemistry more accessible.

## Device Goals

- Modular
- Water-resistant
- Adjustable buoyancy
- Prevent trapping major internal air bubbles
- Optimize antenna orientation

## Tools Used

- CAD Software: Fusion 360
- EDA Software: Fusion 360 Electronics Workspace
- Formlabs Form 3 SLA 3D-printer
- Prusa MK3S PLA 3D-printer
- Soldering station
- Scanning electron microscope
- Multimeter
- Electroplating supplies (e.g., DC power supply)
- Wet lab supplies (e.g., pipettes)
- KUKA robotic arm

## Project Highlights

- Modular and repairable:
  - PCB-based electrodes are joined with the "electrode substrate" component, making them the only components that need replacing.
  - Adhesives are only used at the electrode-substrate interface. The rest of the assembly relies on friction and pressure.
- Water resistance was achieved using an o-ring retained by the dovetail groove.
- Adjustable buoyancy through customized air pockets and added weights.
- Ensures that no air bubbles are trapped at the electrode surface.
- Ensures the antenna always faces upward when floating for best signal quality.

## What I learned

- Conducting bench-testing to improve a fabrication process.
- Assembly must begin at some point, because the CAD model is only as good as its worst-constructed component. Some problems only emerge during assembly or manufacturing.
- Always reference your design inputs to avoid wasting time or straying from the desired product.
- Move as fast as you can without sacrificing quality or rushing. There will always be unforeseen challenges, and discovering them early gives you more time to address them.
- Ask questions and raise concerns regularly, either with experts or by consulting literature and online resources.
- Consulting the right people is crucial to building on recent progress and avoiding past mistakes.
- Quality control is crucial to establish robust statistical results. Changing vendors—or even order quantities—can significantly affect quality.
- Careful documentation is necessary to maintain consistent progress (e.g., identifying which specific variable led to improvement).
- There are many ways to implement o-rings, depending on the desired characteristics.
- My current best-practice workflow, shaped by trial and error:
  1. Clearly define your user needs and design inputs. Determine a baseline for what qualifies as success.
  2. Design and model as many parts as you can. If you cannot find part files online, measure and model them yourself.
  3. Source and assemble prototype as soon as possible.
  4. Print in PLA for initial fit and a looks-like prototype. Only advance to SLA when PLA no longer suffices, though it usually does.
  5. Carry out bench-testing.
  6. Analyze results, consult experts, and do some research.
  7. Iterate on the design and protocols.
