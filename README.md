# Plumber (for Linux)
Written by Amit Serper of Cybereason.

Plumber is a python wrapped ftrace utility to trace various process events (currently supoports fork/execve/process termination).
My goal was to provide a comfortable pythonic way of tracking short-lived process execution on Linux. Plumber is inspired by Brandan Gregg's amazing work and tools.

Current features (v 0.1): 
  - execve() calling
  - fork() calling
  - Process termination
  - Dazzling colour support

# Prerequisits
  * The [colored](https://pypi.python.org/pypi/colored) python module
  * You need to have ftrace support in your kernel - cat /proc/sys/kernel/ftrace_enabled.
# Usage
  - Run as root (in order to access the trace pipe) - python plumber.py
  - Kick back and enjoy :)
# Licesnsing:
 Plumber is licensed under the AGPL license. Please see LICENSE.MD file for more details.
