# great_tailnet_name
Automatically Re-roll Tailnet Names with Automa

## Project Overview

`great_tailnet_name` is a project designed to streamline the process of generating great names for Tailscale tailnets. Leveraging the Automa extension for Google Chrome, this project automates the task of re-rolling tailnet names until a desired short name or a keyword is found.

## Usage Instructions

Follow these steps to make the most of the `great_tailnet_name` project:

1. **Install Automa Extension:**
   - Make sure you have Google Chrome installed on your machine.
   - Install the Automa extension for Google Chrome.

2. **Import Workflow:**
   - Import the workflow from the file `Auto_Reroll_Tailnet_Names.automa.json`.

3. **Access Tailscale Dashboard:**
   - Visit [Tailscale Dashboard](https://login.tailscale.com/admin/dns).

4. **Initiate Name Change:**
   - Click on "Rename tailnet..." to initiate the tailnet renaming process.

5. **Leave the Page Open:**
   - Keep the page open with the "Re-roll options" button visible.

6. **Open Console:**
   - Open the Chrome Developer Tools console to monitor details (show as `screenshot.jpg`).

7. **Customize JavaScript Code:**
   - Open the workflow in the editor.
   - Customize the JavaScript code in the "Condidate found" path of the "Conditions" block to suit your preferences.

8. **Run Workflow:**
   - Run the workflow from the editor.
   - The workflow will automatically stop once a suitable candidate is found.

## Important Note

Ensure that you have a clear understanding of the JavaScript code in the "Conditions" block to customize the search criteria effectively.

Feel free to contribute or report issues if you encounter any while using the `great_tailnet_name` project. Happy tailnet naming!
