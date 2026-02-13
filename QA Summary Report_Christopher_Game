QA Summary Report: Christofer-Rise-Of-Mark-Ham
Report Date: 2/13/2026
Testing Period: Week 6 (Tue–Fri)
Game Version: commit 437a501

## Executive Summary
We conducted comprehensive QA testing on Christofer-Rise-Of-Mark-Ham over four days. Our team tested 3 core features, ran 8 scenarios, and filed 4 issues documenting bugs across all severity levels.
Key Finding: The core gameplay appears to function well; however, there are multiple critical and high-priority issues within the Settings portion (specifically regarding text speed and input validation).

## Project Contacts
Role
Names
Dev Team
Gabriel Cardenas, Rahul Murgai, Huzaifah Sajjad, Troy Gardner
QA Team
Parth Thite, Lucas Campbell, Jack Daubman, Biruk Yidnekachew


## Testing Overview
### Scope & Coverage
Happy path (normal gameplay) :white_check_mark:
Input validation & edge cases :white_check_mark:
Win/lose conditions :white_check_mark:
Complex scenarios & sequences :white_check_mark:
### Feature Breakdown
Random Character Generation: 100% Tested (Stats: Life, Anger, Peace, Smartness, Finesse)
Room Types: 80% Tested (Battle, Loot, Shop, Boss, Special)
Combat Minigame: 100% Tested (Timing-based damage multipliers)
### Test Methodologies
Functional testing: Does the game work as intended?
Negative testing: Intentional attempts to break the system.
Boundary testing: Testing the limits of input values.
Exploratory testing: Creative, non-linear gameplay scenarios.

## Bug Summary
### By Severity
Critical: 1 (Game-breaking)
High: 3 (Core features broken)
Medium: 0
Low: 0
Total Filed: 4
### By Category
Input Validation: 1
Logic Errors: 3
State Management/UI: 0

## Issue Tracking
### Critical Issues (Must Fix Before Handoff)
ID
Title
Steps to Reproduce
GitHub Link
1
Negative Number for Typewrite Speed Crashes Game
1. Settings -> 2. Typewrite Speed -> 3. Enter negative number
#12

### High-Priority Issues (Fix ASAP)
ID
Title
Description
GitHub Link
1
Speed Logic Inversion
Increasing Typewrite speed actually decreases it.
#11
2
Infinite Samosas
Players have an infinite amount of Samosas during fights.
#2
3
Intro Skip Bug
Intro is skipped if a user enters a number larger than 2.
#1


## Testing Insights
### What Worked Well
Core Gameplay: The loop is solid and engaging.
Code Quality: The codebase is clear and easy to navigate.
### Areas for Improvement
Input Validation: This is the weakest point; the game handles unexpected user input poorly.
Documentation: Comments and internal documentation need more detail for future maintenance.
### Patterns Noticed
A significant concentration of bugs is located within the Settings menu and user-input prompts.

## Recommendations
Priority 1: Resolve the negative number crash in Typewrite speed immediately.
Priority 2: Audit all input prompts for boundary checks (e.g., the Samosa exploit and Intro skip).
Priority 3: Polish the Settings UI and internal documentation.

## Test Environment & Links
Platform: VS Code Terminal
All GitHub Issues: View Full List
Status: 4 Open / 0 Closed

## Conclusion
While the core gameplay loop is entertaining and functional, the lack of input validation poses a risk to stability. We recommend addressing the documented bugs in order of severity (Top to Bottom) before the Week 7 handoff.
Test Lead: Lucas Campbell
Submitted: 8:18 AM | 2/13/2026

## Appendix: Detailed Scenarios
Scenario 1 [Happy Path]: Passed. Core features work as intended.
Scenario 2 [Input Validation]: Partial. High frequency of bugs when entering non-standard values.
Scenario 3 [Edge Cases]: Partial. Issues correlate directly with weak input validation.


