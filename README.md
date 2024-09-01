# Task Scheduler for Daily Activities

This project is a Python-based task scheduler designed to optimize and manage daily activities, particularly focused on the daily routine of a student. The scheduler prioritizes tasks based on dependencies, duration, and the ability to multitask, aiming to improve productivity and time management.

## Introduction

This Task Scheduler is developed to address the complexities of managing multiple tasks throughout the day, especially in an academic setting. The scheduler uses a priority queue mechanism to ensure that important tasks are completed on time while allowing flexibility for multitasking where possible.

## Features

- **Priority-Based Scheduling**: Assigns tasks based on their priority, considering dependencies and time constraints.
- **Multitasking Capability**: Allows for simultaneous task execution, such as doing laundry while studying.
- **Dynamic Reprioritization**: Adjusts task priorities in real-time based on task completion and changing circumstances.
- **User-Friendly Interface**: Simple to add, remove, and view tasks, making it easy to manage your day.

## Algorithmic Strategy

The scheduler employs a priority queue, where tasks are assigned priority values based on their importance, duration, and dependencies. The algorithm allows for multitasking by grouping compatible tasks together, ensuring efficient use of time.

Key concepts:
- **Priority Queue**: Organizes tasks by priority, allowing the most critical tasks to be handled first.
- **Dependency Management**: Ensures that tasks with prerequisites are only scheduled once their dependencies are completed.
- **Multitasking Support**: Tasks that can be performed simultaneously are scheduled together to maximize productivity.

## Limitations

- **Multitasking Constraints**: The current version does not fully support complex multitasking scenarios where more than two tasks need to be managed simultaneously.
- **Fixed vs. Continuous Tasks**: The scheduler currently struggles with distinguishing between fixed and continuous tasks, which can lead to scheduling inefficiencies.
- **Scalability**: The algorithm's efficiency decreases with a high number of tasks, particularly when tasks have complex dependencies.
