# QA Summary Report

**Game Tested:** Black Jack  
**Dev Team:** Samuel Taiwo, Jessica Kamienski, Karan Modi, Maxwell Noffsinger  
**QA Team:** Lucas, Biruk, Jack, Parth  
**Testing Period:** Week 6 (Tue–Fri)  
**Report Date:** 2/13/25  

---

## Executive Summary

We conducted comprehensive QA testing on Black Jack over 4 days. Our team tested 4 core features, ran 3 scenarios, and filed 3 GitHub Issues documenting bugs across all severity levels.

> **Key Finding:** Based on the Dev team’s description of the game, only a few core features of the game work.

---

## Testing Overview

### What We Tested

- Happy path (normal gameplay) ✓  
- Input validation & edge cases ✓  
- Win/lose conditions ✓  

### Coverage Summary

**Features Tested:**

- Player can Stand or Hit each round to play BlackJack – **100% tested**  
- Full deck of cards is simulated to correctly deal random cards – **100% tested**  
- Pygame visuals (if we can get it to work) – **100% tested**

**Test Types:**

- Functional testing  
- Negative testing  
- Exploratory testing  

---

## Bug Summary

### By Severity

- **Critical:** 0 bugs (game-breaking)  
- **High:** 2 bugs (core features broken)  
- **Medium:** 1 bug (partial functionality issues)  
- **Low:** 0 bugs (cosmetic or minor edge cases)  

**Total Bugs Filed:** 3  

### By Category

- **Logic Errors:** 1 bug  
- **UI/UX:** 1 bug  
- **Other:** 1 bug  

---

## Critical Issues (Must Fix Before Handoff)

None  

---

## High-Priority Issues (Fix ASAP)

These bugs affect core features but don't prevent gameplay.

| # | Title | Severity | GitHub Issue |
|---|--------|----------|--------------|
| 1 | User Loses Without Context | High | https://github.com/LucasTCamp/Sprint1-Week2-QA-BLJP/issues/7 |
| 2 | Betting is Allowed Even if User Has No Money | High | https://github.com/LucasTCamp/Sprint1-Week2-QA-BLJP/issues/4 |

---

## Medium & Low Priority Issues

Documented in GitHub Issues. These can be deferred or fixed in sequence.

- User Can Win Infinitely Once Acquiring Extra Cards Upgrade  

---

## Testing Insights

### What Worked Well

- Main features of Black Jack worked well  
- Code quality made testing easier  
- Clear documentation helped understanding  

### Areas for Improvement

- Needs more context for why the user lost  
- The upgrades need to be polished  

### Patterns Noticed

Main issues were with the visuals of the game, but most functionality works as intended.

---

## Recommendations for Dev Team

### Critical Fixes (Priority 1)

- None  

### Important Fixes (Priority 2)

- Provide context for why the user lost  
- Prevent betting when the user has no money (or allow negative balance intentionally with clear rules)

### Polish / Optional Fixes (Priority 3)

- Fix and refine upgrades  

---

## Test Environment

- **Platform:** PyCharm  
- **Game Version:** Feb 12, 2026  
- **Testing Tools:** Manual testing + GitHub Issues  

---

## All GitHub Issues

Complete list of filed bugs: See dev team repo for all open GitHub Issues tagged `qa-week6`

- **Total:** 3 issues  
- **Closed:** 0  
- **Open:** 4 (for dev team to fix in Week 7)  

---

## Conclusion

The game has 3 documented issues ranging from critical to cosmetic. With focused effort on critical bugs, the core gameplay has a major issue—there is no proper ending or clear win/lose condition.  

**State management** is the area needing the most attention.

---

## QA Team Sign-Off

**Test Lead:** Lucas  
**Submitted:** 2/13/25 8:33 AM  

**Team Members:**

- Lucas  
- Biruk  
- Jack  
- Parth  

---

## Appendix: Detailed Test Scenarios

### Scenario 1: Happy Path  
**Result:** Passed  
**Notes:** Core game works as intended  

### Scenario 2: Input Validation  
**Result:** Passed  
**Notes:** Works as intended  

### Scenario 3: Edge Cases  
**Result:** Passed  
**Notes:** Works as intended  

---

## Questions for Dev Team

None  

---

**End of Report**
