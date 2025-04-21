---
description: 'NOTE: OpenCode is not supported in version 2025.15'
---

# OpenCode

**OpenCode**: Requires the activation and return of license via the input of codes in the APEX user site. The ALM does not need an active internet connection. However, the codes will need to be transported to a computer that can access the internet to perform the activation or return processes on the APEX user site. The following sections will describe the fields and buttons for OpenCode licensing.

1. Activation Status: Describes the status of the OpenCode activation. This field is dependent on the selected product in section 3.3.
2. Pending Code: Contains the activation or return code that is required input for the APEX user site. The pending code can be copied to the clipboard via the tool button to the right. This field is dependent on the selected product in section 3.3.
3. Choose Product: Choices include APEX ANALYSIS OPENCODE and APEX ACQUISITON OPENCODE. This field determines whether activation or return will be performed on analysis or acquisition licenses and must be chosen prior to activation or return. This choice will also update the status and pending code fields.
4. Request OpenCode Activation: Generates an activation request code that is required by the APEX user site. After the request code is generated, the GUI will update with a field to enter the activation response code generated on the user site. It is important that the response code is entered into the ALM. Otherwise, the licensing state of the chose product will remain in limbo.
5. Update OpenCode Activation: If there is a current activation for the chosen product, the Request button will change to an Update button. This is button will generate a new activation request code that can be entered into the APEX user site to update the maintenance date only of your current activation. It is important that the response code is entered into the ALM. Otherwise, the licensing state of the chose product will remain in limbo.
6. Return OpenCode: Generates a return request code that is required by the APEX user site. After this request code is generated, the licenses for the chosen product are released from this computer. The request code must be entered into the APEX user site to release the licenses there, but the response code does not need to be entered into the ALM as the licenses have already been deleted.
7. Process Response Code: Enabled when the response code field is filled out with the correct pattern. This will activate the licenses for the chosen products on the system.
8. Cancel Request: Cancels the current pending request for the chosen product.
9. Delete OpenCode: Will delete all licenses associated with the chose product from the computer. Use with caution. Note that this will not release the licenses from the APEX user site. If the licenses are deleted, you will have to communicate with the license provider to have them released from the APEX user site.
10. Manage Trusted Storage: Show or hide the following buttons:

    Install Trusted Storage: Install Trusted Storage on the system. Use with caution, as this will most likely erase all of your OpenCode licenses. Trusted Storage is installed on installation of the ALM, so this button should not be needed.

    Reset Trusted Storage: Erase all OpenCode licenses for all products. Use with caution. If the licenses are deleted, you will have to communicate with the license provider to have them released from the APEX user site.
