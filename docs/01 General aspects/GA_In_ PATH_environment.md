---
title: Implement a folder for the PATH environment
layout: home
nav_order: 1
parent: Installations and Setup
has_children: false
---

Implement a folder for the PATH Environment

Reason: If you call an executable from the CMD window (or from a script) it is required to tell the operating system where the executable is safed. If no information is provided, the operating system check wether the executable is available through the PATH environment (i.e., the computer checks if the executable is placed there - in that case, it can be called withouth the definition of the specific place on your computer).

1) Define a folder on your computer where you want to safe executables that should be globally available (e.g., C:\PATHEXE; the folder name is defined by the user). If this folder is not existing yet, generate it.

2) Go the the System settings (Proprieta del sistema) and go to tab Advanced (Avanzate), there is in the lower section the button Environment settings (Variabli d'Ambiente)

3) Go to System Variables (Variabli di sistema) and look for the parameter Path; mark path and click Modify (Modifica); add the location of the folder that contains the executables to the parameter (e.g., C:\PATHEXE

4) Check if the folder is considered by the PATH environment by opening the command window (CMD) and calling an executable from that folder; if the exectable is recognized (i.e., something happens) you have esuccessfully added the folder to the PATH enironment.

5) Now you can safe all executables that should be globally available on your computer within this folder