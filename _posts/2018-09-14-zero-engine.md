---
layout: page
title: Zero Engine
category: projects
tags: [Games, projects, C++, CMake, Python]
---

![Zero Engine]({{site.baseurl}}/img/zero.png)


## Software Engineer 

##### Zero Engine Team - DigiPen R&D  

Zero Engine is an open source game engine created in DigiPen R&D by the Zero Engine Team. It is a component-based game engine that focuses on being as lightweight, easy to use, and customizable as possible to allow for rapid iteration. More information here: https://www.zeroengine.io

The source is now available under the M.I.T. License here on GitHub: https://github.com/zeroengineteam/ZeroCore
### What I Did

* Extended Buildbot by writing custom steps in Python to allow for automated tests on more development branches so bugs could be caught before ever being merged into a release build.
* Constructed doc tool in C++ to parse Doxygen output and combine it with Zero Engine output to increase accuracy of both the code ref online as well as the tooltips displayed in the engine’s editor.
* Introduced macro expansion support features to the C++ doc tool to document properties that were defined and/or commented in macros, greatly reducing the number of bound properties missing documentation.
* Ported the Zero Engine over from a Visual Studio project to a CMake project, allowing for cross-platform development.
* Co-Created a presentation/tutorial using the knowledge from porting the Zero Engine project to teach students and CMake beginners how to get started using best practices. (github.com/playmer/CMakePresentation)
* Wrote a CMake utility that allowed for adding new external libraries with minimal script changes to reduce the need to make unnecessary CMake changes.
* Developed a Phabricator markdown exporter in C++ for the doc tool, reducing the doc upload process to running a script.
* Extended the core engine’s documentation system to export template information from bound templated engine types to allow for proper type information for templates in the code ref and in tooltips to improve type discoverability for users.
* Learned how to create builds for WebAssembly and Linux while maintaining the Buildbot server and the CMake project.


### Tools and Languages Used

* C++
* Python
* CMake
* Zilch
* Buildbot
* Doxygen
