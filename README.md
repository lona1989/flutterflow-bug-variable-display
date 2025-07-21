# flutterflow-bug-variable-display
Problem with App State not updating in FlutterFlow

## Problem with App State not updating in FlutterFlow

Hi,

I'm building a mobile app with FlutterFlow (2025 version).  
I want to display a selected month in a Text widget using an App State variable.

### What I did:
- I created an App State variable named `selectedMonth` (String).
- I set an Action Flow onTap to update this App State with the value `"January"` or other months.
- I bind a Text widget to display `selectedMonth`.

### The issue:
Even though the variable is updated in the Action Flow, the Text widget still shows `[selectedMonth]` and not the selected value.

I also tried:
- Rebuilding the page after setting the App State.
- Using a default value.
- Trying a test variable (e.g., `JanvierTEST`), which works.

### Screenshot:
(Attach screenshots or explain the structure if needed)

---

### What I want:
I would like to know if this is a bug in FlutterFlow or if I’m missing a step.  
Is there a proper way to bind a Text widget to an App State variable in FlutterFlow 2025?

Thanks for your help 🙏
