📌 Overview

This project is a simple chat application built with ROS (Robot Operating System).
It demonstrates the publisher–subscriber communication model using two nodes:

Speaker Node → Publishes messages.

Microphone Node → Subscribes to messages and sends responses back.

It uses AsyncSpinner for multithreading, enabling both publishing and subscribing to run concurrently without blocking execution.

⚙️ Tools & Skills Demonstrated

Operating System: Ubuntu 18.04 / 20.04

ROS Versions: Melodic / Noetic

Programming Language: C++ with roscpp

Build System: Catkin & CMake

Concepts:

Publisher & Subscriber nodes

Multithreading with AsyncSpinner

ROS Topics & Message Passing
