# TestRail Case: Mobile - Validate clicks & impressions against API

**Preconditions:**
- User is logged in
- App version: 1.2.3 (Android/iOS)

**Steps:**
1. Open the app and navigate to Analytics screen.
2. Note the Clicks and Impressions values shown in the UI.
3. Call the API endpoint /analytics?date=today for the same account.
4. Compare UI values with API response.

**Expected Result:**
- UI shows the same Clicks and Impressions as the API.
