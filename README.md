# Adding IR Codes in Bruce

## Overview
This guide provides step-by-step instructions for adding IR codes to Bruce, ensuring seamless integration and functionality. Follow these steps to configure your device effectively.

---

## Prerequisites
### Required Items:
- [ ] Bruce installed on your device
- [ ] Connection to the WebUI

---

## Instructions

### Step 1: Gather IR Codes
- **Description:** Follow these steps to acquire the necessary IR codes:
  1. Clone the repository or download it as a ZIP file.
  2. Extract the files and prepare them for upload.
  3. Upload the files to an SD card or connect your device using the WebUI.
  
### Step 2: Access Bruce’s Configuration Directory
- **Details:**
  1. Connect to Bruce’s file system using your preferred method (e.g., SSH, WebUI, or direct SD card access).
  2. Navigate to the IR configuration directory located at `/bruce/config/ir-codes/`.

### Step 3: Add IR Code Files
- **Instructions:**
  1. Place your collected IR code files into the `/bruce/config/ir-codes/` directory.
  2. Ensure the files are named appropriately to reflect their functionality (e.g., `tv-power.ir`, `projector-input.ir`).
  
### Step 4: Test IR Codes
- **Verification:**
  1. Use Bruce’s WebUI to test the newly added IR codes.
  2. Verify the device responds correctly to the configured codes.

---

## Tips and Troubleshooting
- **File Naming:** Avoid using generic names like `unknown.ir`. Descriptive filenames improve maintainability.
- **File Permissions:** Ensure the uploaded files have the correct read/write permissions.
- **Debugging:** If codes don’t work, check the logs in the WebUI for detailed error messages.

---

For additional help, refer to the official Discord server or feel free to reach out to me!
