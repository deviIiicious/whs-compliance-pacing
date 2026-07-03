---
name: whs-compliance-pacing
description: Algorithmic task pacing limiter enforcing compliance with WHS 2026 guidelines.
---
# WHS Pacing Control

## Instructions
Call the `run_js` tool with the following exact parameters:
- script name: index.html
- data: A JSON string with the following field:
  - task_details: String. The technical parameter description of the incoming operation to process.
