# QA Summary Report

**Game Tested:** Fhsng Game  
**Dev Team:** Ayah, Bianca, Marcus, Evan  
**QA Team:** Lucas, Biruk, Jack, Parth  
**Testing Period:** Week 6 (Tue–Fri)  
**Report Date:** 2/13/25  

---

## Executive Summary
We conducted comprehensive QA testing on **Fhsng Game** over 4 days. Our team tested 5 core features, ran 4 scenarios, and filed 4 GitHub Issues documenting bugs across all severity levels.

**Key Finding:** Based on the Dev team’s description of the game, only a few core features of the game work.

---

## Testing Overview

### What We Tested
- Happy path (normal gameplay) ✓  
- Input validation & edge cases ✓  
- Win/lose conditions ✓  
- Complex scenarios & sequences ✓  

### Coverage Summary

#### Features Tested
- Fishing hook actually hooks fish / works: **100% tested**  
- The fish move around and vary in species: **100% tested**  
- The amount of pounds of fish are calculated after you catch: **100% tested**  
- The game ends after 5 or 20 rounds: **100% tested**  
- The game ends if you don’t catch enough fish to feed the “shark”: **100% tested**  

#### Test Types
- Functional testing  
- Negative testing  
- Exploratory testing  

---

## Bug Summary

### By Severity
- **Critical:** [1] bug (game-breaking)  
- **High:** [2] bugs (core features broken)  
- **Medium:** [1] bug (partial functionality issues)  
- **Low:** [0] bugs (cosmetic or minor edge cases)  

**Total Bugs Filed:** [4]

### By Category
- Logic Errors: [1] bug  
- State Management: [2] bugs  
- Other: [1] bug  

---

## Critical Issues (Must Fix Before Handoff)

These bugs prevent the game from being playable or break core mechanics.

| # | Title      | Severity | Steps to Reproduce | GitHub Issue |
|---|------------|----------|--------------------|--------------|
| 1 | No Ending  | Critical | Open the game<br>Play the game<br>Keep playing the game for a while<br>Observe bug | https://github.com/LucasTCamp/Sprint1-Week2-QA-BLJP/issues/13 |

---

## High-Priority Issues (Fix ASAP)

These bugs affect core features but don't prevent gameplay.

| # | Title | Severity | GitHub Issue |
|---|-------|----------|--------------|
| 1 | Game Keeps Playing Even if User Catches No Fish | High | https://github.com/LucasTCamp/Sprint1-Week2-QA-BLJP/issues/6 |
| 2 | No Maximum Amount of Rounds | High | https://github.com/LucasTCamp/Sprint1-Week2-QA-BLJP/issues/3 |

---

## Medium & Low Priority Issues
Documented in GitHub Issues. These can be deferred or fixed in sequence.

---

## Testing Insights

### What Worked Well
- Feature (Hook/Fish) performed as expected  
- Code quality made testing easier  
- Clear documentation helped understanding  

### Areas for Improvement
- It’s just catching fish and has no ending. I know they want to add a feature involving a shark, but it isn’t there yet.  
- State management has logic errors  
- Clean up the UI (you can bring the hook off-screen, and it looks choppy)  

### Patterns Noticed
There were just a lot of bugs centered around the rounds feature. The game doesn’t end, it starts on round 2, and it doesn’t have a limit, which was stated in the dev team’s description of the game.

---

## Recommendations for Dev Team

### Critical Fixes (Priority 1)
- Fix **Issue: No Ending** — affects the whole game  
- Fix **Catching 0 fish has no consequences** — prevents win/lose condition  

### Important Fixes (Priority 2)
- Fix state tracking in **Rounds**

### Polish / Optional Fixes (Priority 3)
- UI (Hook)  
- Nice-to-have enhancements  

---

## Test Environment
- **Platform:** PyCharm  
- **Game Version:** Feb 12, 2026  
- **Testing Tools:** Manual testing + GitHub Issues  

---

## All GitHub Issues
Complete list of filed bugs:  
https://github.com/LucasTCamp/Sprint1-Week2-QA-BLJP/issues?q=is%3Aissue%20state%3Aopen%20label%3A%22Fhsng%20Game%22  

- **Total:** [4] issues  
- **Closed:** [0]  
- **Open:** [4]  

---

## Conclusion
The game has **[4] documented issues** ranging from critical to cosmetic. With focused effort on critical bugs, the core gameplay has a major issue with it not having an ending or win/lose condition. State management is the area needing the most attention.

---

## QA Team Sign-Off
**Test Lead:** Lucas  
**Submitted:** 2/13/25  

**Team Members:**
- Lucas  
- Biruk  
- Jack  
- Parth  

---

## Appendix: Detailed Test Scenarios

### Scenario 1: Happy Path
- **Result:** Failed  
- **Notes:** No win/lose condition, doesn’t end  

### Scenario 2: Input Validation
- **Result:** Partial  
- **Notes:** User is able to use their mouse to drag the hook correctly. It is a little slow and lags behind a lot  

### Scenario 3: Edge Cases
- **Result:** Failed  
- **Notes:** Game keeps going after 5 rounds  

---

## Questions for Dev Team
N/A

---

**End of Report**
