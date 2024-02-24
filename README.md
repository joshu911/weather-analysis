<!-- Table of Contents -->
# Table of Contents
- [Velma](#velma)
  - [Overview](#overview)
  - [Scope](#scope)
    - [Functionality](#functionality)
      - [Battery](#battery)
      - [GPS](#gps)
      - [Gyro](#gyro)
  - [Goal](#goal)
- [Architecture and Design](#architecture-and-design)
  - [System Requirement](#system-requirement)
  - [Module](#module)
  - [Design](#design)
  - [Logic](#logic)
- [Setup](#setup)

<!-- Content -->
# Velma

## Overview
<a id="overview"></a>

Velma contains all the requirements for an unmanned aerial vehicle (UAV) that is capable of operating without direct human control, relying instead on various sensors, software systems, and algorithms to perform tasks such as navigation, obstacle avoidance, and mission execution.

## Scope
<a id="scope"></a>

### Functionality
<a id="functionality"></a>

#### Battery
<a id="battery"></a>

Measure the voltage to determine the drone's battery percentage using battery capacity. A voltage divider connected at AO. This voltage is used to compensate the electronic speed controller for voltage drop. Thrust drops with a decrease in battery voltage we use measured voltage to increase throttle slightly when voltage drops to maintain uniform flight.

#### GPS
<a id="gps"></a>

Uses longitude and latitude to determine sense direction, altitude, velocity, time, and date.

#### Gyro
<a id="gyro"></a>

Measure angular motion per time to determine the drone's rotation.

## Goal
<a id="goal"></a>

Insert your content for the goal here.

# Architecture and Design

## System Requirement
<a id="system-requirement"></a>

Insert your content for system requirement here.

## Module
<a id="module"></a>

Insert your content for module here.

## Design
<a id="design"></a>

Insert your content for design here.

## Logic
<a id="logic"></a>

Insert your content for logic here.

# Setup
<a id="setup"></a>

Insert your content for Setup here.
