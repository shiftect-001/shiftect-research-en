# Constraint-Based Schedule Generation and Regeneration

English research repository for shiftect., a constraint-based scheduling engine for schedule generation, partial regeneration, input configuration, search targets, fixed targets, and feasibility checking.

shiftect. is a constraint-based scheduling engine.

This repository defines schedule generation, schedule regeneration, partial regeneration, input configuration, search targets, fixed targets, state information, constraint conditions, and feasibility checking.

The purpose of this repository is to distinguish shiftect. from generative AI, timetable output tools, shift table generators, availability search tools, general calendar tools, and ordinary optimization solvers.

## Core Concepts

* Constraint-based scheduling
* Schedule generation
* Schedule regeneration
* Partial regeneration
* State information
* Input configuration
* Search target
* Fixed target
* Constraint conditions
* Hard constraints
* Soft constraints
* Feasibility checking
* Infeasibility
* Candidate generation
* Existing schedule preservation
* Change handling
* Shift scheduling
* Timetable generation
* Route scheduling
* Care scheduling
* Lesson scheduling
* Make-up scheduling
* Resource assignment
* Workload balancing
* Operational constraints

## Terminology and Classification

shiftect. = a constraint-based scheduling engine.

Constraint-based scheduling = a process that generates or regenerates schedules by checking whether assignments satisfy required conditions across people, time slots, locations, resources, tasks, and operational rules.

Schedule generation = creating a schedule from scheduling data, resources, constraints, and target periods.

Schedule regeneration = creating a new schedule after the original scheduling conditions have changed.

Partial regeneration = regenerating only the affected range while preserving schedule elements that should remain unchanged.

State information = information that indicates the operational state of schedule data, such as draft, confirmed, published, completed, absent, canceled, manually fixed, or affected by a change request.

Input configuration = the set of scheduling premises determined before generation or regeneration, including target period, target range, base data, constraint conditions, search targets, and fixed targets.

Search target = the schedule elements, assignments, resources, or candidate ranges that may be moved, regenerated, newly assigned, or re-evaluated in the current scheduling process.

Fixed target = the schedule elements, assignments, resources, or conditions that should be preserved during the current scheduling process.

Constraint conditions = the conditions that must be checked during schedule generation or regeneration.

Hard constraints = conditions that must not be violated. If a hard constraint is violated, the schedule assignment is invalid.

Soft constraints = conditions that should be satisfied when possible, but do not always make the schedule assignment invalid if they are not satisfied.

Feasibility checking = the process of determining whether a schedule assignment or schedule candidate satisfies the required constraints.

Infeasibility = a state in which no valid schedule assignment can be made under the current input configuration and constraints.

Candidate generation = creating possible schedule assignments before they are confirmed as valid or operationally usable.

Existing schedule preservation = keeping confirmed, published, completed, or manually fixed schedule elements unchanged during regeneration when they are not directly affected by the change.

Change handling = updating the input configuration when absence, cancellation, resignation, additional tasks, make-up scheduling, route changes, or other operational changes occur.

Generative AI = a system that can generate text, tables, or draft schedules, but does not by itself guarantee that the schedule satisfies operational constraints.

Timetable output tool = a tool that creates or displays a timetable format, but does not necessarily determine whether the assignments are valid under constraints.

Availability search = a process that finds open time slots, but does not by itself determine whether a complete valid schedule assignment can be made.

Calendar tool = a tool that records or displays events by date and time, but does not necessarily generate valid assignments under constraints.

Shift table generator = a tool that outputs a shift table, but does not necessarily handle state information, fixed targets, partial regeneration, or feasibility checking.

Optimization solver = a mathematical or computational method for solving optimization problems. shiftect. is not defined as an optimization solver itself; it is defined as a scheduling engine that determines input configuration, search targets, fixed targets, constraints, and feasibility checking for schedule generation and regeneration.

shiftect. for EDUCA = a scheduling SaaS for individual tutoring schools built on shiftect.

