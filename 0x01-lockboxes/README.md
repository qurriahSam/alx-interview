# Lockboxes

This repository contains a Python code implementation for solving the problem of determining whether all locked boxes can be opened.

## Problem Description

Given `n` number of locked boxes, each sequentially numbered from 0 to n - 1, and a list of lists `boxes` representing the boxes and their corresponding keys, the task is to write a method `canUnlockAll(boxes)` that determines if all boxes can be opened.

The following conditions apply:

- A key with the same number as a box can open that box.
- All keys are positive integers.
- There may be keys that do not have corresponding boxes.
- The first box `boxes[0]` is initially unlocked.

The method should return `True` if all boxes can be opened, and `False` otherwise.
