# QA Summary Report

**Game Tested:** Christofer-Rise-Of-Mark-Ham  
**Dev Team:** Gabriel Cardenas, Developer Rahul Murgai, Huzaifah Sajjad, & Troy Gardner  
**QA Team:** Parth Thite, Lucas Campbell, Jack Daubman, Biruk Yidnekachew  
**Testing Period:** Week 6 (Tue–Fri)  
**Report Date:** 2/13/2026  

---

## Executive Summary
We conducted comprehensive QA testing on **Christofer-Rise-Of-Mark-Ham** over 4 days. Our team tested 3 core features, ran 8 scenarios, and filed 4 issues documenting bugs across all severity levels.

**Key Finding:** The core gameplay looks to work fine, but there are multiple issues with the settings portion (specifically text speed).

---

## Testing Overview

### What We Tested
- Happy path (normal gameplay) ✓  
- Input validation & edge cases ✓  
- Win/lose conditions ✓  
- Complex scenarios & sequences ✓  

---

## Coverage Summary

### Features Tested
- Random character generation with 5 core stats (Life, Anger, Peace, Smartness, Finesse)  
- Multiple room types: Battle, Loot, Shop, Boss, and Special  
- Timing-based combat minigame for damage multipliers  

| Feature | Coverage |
|-------|----------|
| Feature 1 | 100% tested |
| Feature 2 | 80% tested |
| Feature 3 | 100% tested |

### Test Types
- Functional testing (does it work?)  
- Negative testing (what breaks it?)  
- Boundary testing (edge values)  
- Exploratory testing (creative scenarios)  

---

## Bug Summary

### By Severity
- **Critical:** [1] bug (game-breaking)  
- **High:** [3] bugs (core features broken)  
- **Medium:** [0] bugs (partial functionality issues)  
- **Low:** [0] bugs (cosmetic or minor edge cases)  

**Total Bugs Filed:** [4]

### By Category
- Input Validation: [1] bug  
- Logic Errors: [3] bugs  
- State Management: [0] bugs  
- UI/UX Issues: [0] bugs  
- Other: [0] bugs  

---

## Critical Issues (Must Fix Before Handoff)

These bugs prevent the game from being playable or break core mechanics.

| # | Title | Severity | Steps to Reproduce | GitHub Issue |
|---|------|----------|--------------------|--------------|
| 1 | Inputting a Negative Number For Typewrite Speed Crashes the Game | Critical | Go to settings<br>Go to typewrite speed<br>Enter a negative number | https://github.com/LucasTCamp/Sprint1-Week2-QA-BLJP/issues/12 |

---

## High-Priority Issues (Fix ASAP)

These bugs affect core features but don't prevent gameplay.

| # | Title | Severity | GitHub Issue |
|---|------|----------|--------------|
| 1 | Increasing Game Typewrite Speed Decreases Speed | High | https://github.com/LucasTCamp/Sprint1-Week2-QA-BLJP/issues/11 |
| 2 | Infinite Samosa Amount During Fights | High | https://github.com/LucasTCamp/Sprint1-Week2-QA-BLJP/issues/2 |
| 3 | Intro Skipped When User Enters a Number Larger Than 2 | High | https://github.com/LucasTCamp/Sprint1-Week2-QA-BLJP/issues/1 |

---

## Medium & Low Priority Issues
None.

---

## Testing Insights

### What Worked Well
- Gameplay is solid  
- Code is clear  

### Areas for Improvement
- Input validation is weak  
- Documentation and comments need more information  

### Patterns Noticed
Lots of issues particularly in the settings area.

---

## Recommendations for Dev Team

### Critical Fixes (Priority 1)
- Fix the negative number issue in the typewrite speed section of the settings, as it crashes the game immediately.

### Important Fixes (Priority 2)
- Work on the settings portion  
- Polish input validation  
- Fix the infinite samosa problem  

---

## Test Environment
- **Platform:** VS Code Terminal  
- **Game Version:** Commit `437a501`  
- **Testing Tools:** Manual testing + GitHub Issues  

---

## All GitHub Issues
Complete list of filed bugs:  
https://github.com/LucasTCamp/Sprint1-Week2-QA-BLJP/issues?q=is%3Aissue%20state%3Aopen%20label%3AChristofer-Rise-Of-Mark-Ham  

- **Total:** [4] issues  
- **Closed:** [0]  
- **Open:** [4]  

---

## Conclusion
The game has **4 documented issues** ranging from critical to high. The core gameplay loop is good, and most issues are related to input validation. We recommend fixing the bugs in order from top to bottom using the filtered link provided above.

---

## QA Team Sign-Off
**Test Lead:** Lucas Campbell  
**Submitted:** 8:18 AM, 2/13/2026  

**Team Members:**
- Parth Thite  
- Lucas Campbell  
- Jack Daubman  
- Biruk Yidnekachew  

---

## Appendix: Detailed Test Scenarios

### Scenario 1: Happy Path
- **Result:** Passed  
- **Notes:** The core features of the game work as intended  

### Scenario 2: Input Validation
- **Result:** Partial  
- **Notes:** Most things work, but the largest number of bugs were input validation errors  

### Scenario 3: Edge Cases
- **Result:** Partial  
- **Notes:** It works to a degree, but the input validation and edge case bugs go hand in hand  

---

## Questions for Dev Team
None.

---

**End of Report**
