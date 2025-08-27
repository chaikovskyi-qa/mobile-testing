| ID | Check item | Expected result | Actual result | Status | Comment / Bug ID |
| --- | --- | --- | --- | --- | --- |
| TC_SMOKE_001 | Installation / Launch | App installs and launches without a crash | Installed, launches normally | ✅ Pass | |
| TC_SMOKE_002 | First screen / UI load | UI loads; buttons/texts visible | Red line above output field | ⚠️ To Review | BR-001 |
| TC_SMOKE_003 | Login / Sign-up | Auth flow works | N/A | N/A | Not applicable |
| TC_SMOKE_004 | Permissions | Proper dialogs when needed | N/A | N/A | Not applicable |
| TC_SMOKE_005 | Navigation | Buttons work; no dead-ends | Works as expected | ✅ Pass | |
| TC_SMOKE_006 | Primary scenario | Input → compute → clear → repeat | Works as expected | ✅ Pass | |
| TC_SMOKE_007 | Forms / keyboard | Keyboard doesn’t overlap fields | N/A | N/A | Not applicable |
| TC_SMOKE_008 | Lists / scrolling | Lists scroll correctly | N/A | N/A | Not applicable |
| TC_SMOKE_009 | Network errors | Offline handled; no crashes | N/A | N/A | Not applicable |
| TC_SMOKE_010 | Screen rotation | Preserves state; no crash | Red line shifts in landscape | ⚠️ To Review | BR-001 |
| TC_SMOKE_011 | Back / Forward | Back works as expected | Works as expected | ✅ Pass | |
| TC_SMOKE_012 | Cache / relaunch | Post-relaunch state reasonable | Previous result preserved | ⚠️ To Review | Clarify expected |
| TC_SMOKE_013 | Localization | Correct formats; no placeholders | N/A | N/A | Not applicable |
| TC_SMOKE_014 | Dark theme | Sufficient contrast | OK | ✅ Pass | |
| TC_SMOKE_015 | Performance | No freezes >1–2s | OK | ✅ Pass | |
