# Bug Reports

## BR-001: Vertical line visible on the right (portrait & landscape)
**Severity:** Low | **Priority:** Medium  
**Env:** Android 13, AVD Pixel 5; portrait & landscape  
**Steps:** Open Calculator → observe right edge (both orientations)  
**Expected:** No extra lines; layout flush with screen edge  
**Actual:** Thin red/white vertical line visible on the right  
**Attachments:** `screens/calculator-ui-issue.png` (portrait), `screens/calculator-ui-issue-land.png` (landscape)

---

## BR-002: Result persists after relaunch (needs clarification)
**Severity:** Low | **Priority:** Low  
**Env:** Android 13, AVD Pixel 5  
**Steps:** Compute `10 ÷ 3 =` → Close app → Reopen  
**Expected:** (TBD) Either last result cleared, or restored per requirements  
**Actual:** Previous result is preserved after relaunch  
**Note:** Requires PO decision; link with TC_SMOKE_012

---

## BR-003: Decimal formatting rules unclear
**Severity:** Medium | **Priority:** Medium  
**Env:** Android 13  
**Steps:** Compute `10 ÷ 3 =` and similar fractions  
**Expected:** Rounding/precision per spec (e.g., 2 decimals, bankers rounding, etc.)  
**Actual:** Formatting seems correct visually, but no documented rule; risk of inconsistency  
**Suggestion:** Define and document rounding/precision rules
