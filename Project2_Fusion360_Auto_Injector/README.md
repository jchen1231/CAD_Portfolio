# Project 2: Auto-injector

Team: Dr. Jenna Mueller, Ph.D., David Garvey, Taya Lee, and Jason Chen

Time Frame: Fall 2023 – Spring 2024

**NOTE:** All components were originally made in Fusion 360, but there are STEP file versions for your convenience.

## File Structure

- `renders_drawings_images/`: screenshots showing various assembly states of the auto-injector
- `source_files/`:
  - The **main** device assembly files are `auto_injector_rev_D_v15.f3z` and `STEP_auto_injector_rev_D_v15.step`
  - I included some select custom computer-aided design (CAD) parts for this device
- `BoM_Auto_injector_Assembly.xlsx`: a draft bill of materials
- `Project2_Triple_needle_Auto_injector_Overview.pptx`: labeled diagrams and other information

## Overview

Dr. Mueller and her lab are pioneering a low-cost, alternative cervical cancer ablation therapy for resource-limited settings. The therapeutic consists mainly of a hydrogel material, ethyl cellulose, and ethanol, with the former enabling sufficient localization of ethanol at the tumor site, causing cancer cell death and tissue necrosis. The combination of ethyl cellulose and ethanol is referred to as ECE. Through extensive in vivo testing in pigs, they found that a single injection of ECE is often insufficient for larger tumor masses. They proposed two potential solutions to this challenge: to combine ECE with another therapeutic, such as a photodynamic therapy agent, or to inject multiple deposits.

This project highlights efforts to implement the second solution through developing an easy-to-use, low-cost, triple-needle injector device that delivers three ECE deposits in close proximity to cause a larger area of tissue necrosis in one injection. The injector device, nicknamed the Auto-injector, is capable of delivering three simultaneous ECE deposits and then retracting its needles after injection, all driven by an air canister pressurized using a bike pump.

## Goals

- Easy to use and repair
- Retracts needles to prevent injury
- Injects viscous ECE solution in a timely manner
- Compatible with a speculum
- Reusable and low-cost

## Tools Used

- CAD Software: Fusion 360
- Prusa MK3S PLA 3D-printer
- Formlabs Form 3 SLA 3D-printer
- Heat staking machine
- Tap and die set
- Lathe
- Band saw
- Belt sander
- Drill press

## Project Highlights

- The needle retraction and ECE injection work independently of each other.
  - The needle retraction requires pushing the rear rod button to extend the needle and sliding the side slider to retract.
  - The ECE injection only requires pushing the trigger button to actuate.
- Device can be disassembled into a few main components held together using the threaded inserts, alignment pins, ribs, and interference fits. See the PowerPoint overview for more details.
- Incorporated feedback from Taya, a graduate student in the Mueller Lab. When the button is pressed fully, a spring-driven latch drops down and holds the trigger in place; the button must be held to keep the pneumatic valve open for the entire duration of the ECE injection.
- The narrow snout is compatible with a speculum.
- The only consumables are the needles. All remaining components only need to be replaced due to wear.

## What I learned

- Operated the lathe to mill the reusable syringe barrel and plunger components from aluminum rod stock.
- Utilized design configurations as a powerful tool for finding optimal working designs. Many different configurations—labeled using extrude cuts—can be printed and tested simultaneously, speeding up the design process.
- Used Fusion 360 to render, animate, and draw device mechanics for better visualization.
- Maintained and organized an assembly with 40+ components, incorporating both custom and off-the-shelf components; proper naming and version control were critical.
- Material choice matters: initially used Formlabs Tough resin for the housing without checking compatibility with heated inserts; the SLA prints chipped and cracked.
- Tolerance issues: brass rods ordered online were often too warped axially to allow for smooth retraction.
- I must better anticipate the challenges that inevitably arise when translating the CAD model to physical assembly. Some assembly challenges specific to this project include:
  - Using a die tool to cut axially-symmetric threads into the brass rod.
  - Heated inserts had to be properly aligned when inserted.
  - Ensuring the short brass rods at the device tip were sawed and filed to the same length.
  - Stiff tubes caused extra friction and deflection in the final assembly, resulting in inconsistent extension and retraction.
  - PLA and SLA prints often have imperfections caused by support structures and post-processing.
- Friction can result in significant wear and tear. This was especially true for the retraction mechanism, which incorporates a spring-loaded latch that can disengage only when significant force is applied against the latch.
