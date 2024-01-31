# Model-Based Testing Prototype for TiGL

This project was developed as part of the course "Software Quality" (Project 9) at the University of Cologne and supervised by Prof. Dr. Michael Felderer.

## Purpose

The goal is to create a model-based testing (MBT) approach for TiGL, a Titanium Graphical Library commonly used in the aerospace industry for aircraft wing design. This repository contains test cases and automation scripts for testing the TiGL Viewer's graphical user interface (GUI) using MBT and the MBT tool GraphWalker.

## Test Cases

### Open and Display Model:

Test the functionality of opening and displaying a model in the TiGL Viewer.

**Steps:**
1. Launch the TiGL Viewer.
2. Open a valid model file.
3. Verify successful loading and display of the model.
4. Close the TiGL Viewer.

**Expected Outcome:**
- The test steps are executed without errors.
- The model is successfully loaded and displayed.
- The TiGL Viewer closes properly.

### Select and Rotate Component:

Test the functionality of selecting and rotating a component in the TiGL Viewer.

**Steps:**
1. Launch the TiGL Viewer.
2. Open a model with selectable components.
3. Select a component and perform a rotation action.
4. Verify the component's rotation.
5. Close the TiGL Viewer.

**Expected Outcome:**
- The test steps are executed without errors.
- The selected component rotates as expected.
- The TiGL Viewer closes properly.

## Features

- **Model-Based Testing (MBT):**
  - Formulate test cases based on the expected behavior of the TiGL Viewer's GUI.
  - Ensure comprehensive coverage of GUI interactions through structured test cases.

- **GraphWalker Automation:**
  - Utilize the MBT tool GraphWalker for automating the execution of formulated test cases.
  - Benefit from the ability to visualize and analyze test coverage with GraphWalker.

- **AppleScript/Automator Automation:**
  - Utilize the Apple Automator tool for automating the execution of formulated test cases.

## Requirements

- Installed [TiGL](https://github.com/DLR-SC/tigl)
- macOS with Apple Automator and AppleScript
- Valid testfile saved on the desktop

    
## Installation

- Clone this repository to your local machine or download the script files.

## Usage

1. Open the AppleScript files corresponding to the desired test case using the Script Editor on MacOS.

2. Review and modify the script if necessary to match your system configuration.

3. Execute the modified AppleScript using the Script Editor or run it through the terminal.

## Feedback and Contributions

We welcome feedback, bug reports, and contributions! If you encounter any issues or have suggestions for improvement, please open an issue or submit a pull request.

## Contact

For any inquiries or assistance, feel free to contact Kaan Akbulut or Johannes Simon.
E-Mail: kakbulut@smail.uni-koeln.de / jsimon10@smail.uni-koeln.de

## License
This project is available under the [MIT License](LICENSE).
