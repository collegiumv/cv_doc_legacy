---
title: Matlab
author: CV Admins
layout: default
---

#MATLAB
MATLAB is a high-level language and interactive environment for numerical computation, visualization, and programming, commonly used by Engineering and Math majors.

UTDallas provides a way for all students to use MATLAB from any computer.  This is particularly simple over CVOS.

##1. Open a Terminal
To access the MATLAB server, we will need to open a SSH session in a terminal.  You can open the *xterm* terminal via `Application Menu > System Tools > XTerm`.

![Application Menu > System Tools > XTerm](/img/work/terminalMenu.png)

##2. Connect to Giant

You will need to connect to UTD's Matlab server, *Giant*, via an SSH session with X-forwarding support.  To achieve this, at the prompt, type `ssh -X net123123@giant.utdallas.edu` replacing net123123 with your netid.

You will then be prompted for your password.  While entering your password, you will not see any dots or other visual feedback until you hit enter.

##3. Launch Matlab

At the `{giant:~}` prompt, simply type `matlab` and hit enter.  Within a few seconds, you should have a graphical instance of matlab on your screen.

![Launching Matlab](/img/work/matlab.png)
