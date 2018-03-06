[Data Tracker Guides](https://github.com/cityofaustin/data-tracker-guides) > [Signs & Markings](https://github.com/cityofaustin/data-tracker-guides/tree/master/signsmarkings) > [Create Work Order (Non-Technician)](https://github.com/cityofaustin/data-tracker-guides/blob/master/signsmarkings/create_work_order_non_tech.md)

#  Create New Work Order (Non-Technician)
##### User Role Required: Viewer

1. Login: http://transportation.austintexas.io/data-tracker/#home/work-orders-markings/
2. Click "New Work Order" button.
3. Complete New Work Order form:
    - **Work Type**: Signs or Markings | Required
    
    - **Requestor**: The business unit requesting the work.  | Required
    
    - **Work Groups**: the Markings work groups required. | Required if Work Type is Markings
    
    - **311 SR #**: The Signs or Markings 311 service request number related to this work order. | Optional. Only displayed when requestor is MAINTENANCE
    
    - **Maximo ID**: | Optional. Only displayed when Work Type is Signs
    
    - **Engineering Work Order ID**: the ID of the requestor's work order | Optional
    
    - **Regulation #**: | Optional. Work order will be placed on hold until reg is attached.
    
    - **Coordination Neeed**: If the work requires coordination across multiple ATD divisions | Required if requestor is not MAINTENCE or SBO / WHEREABOUTS
    
    - **Instructions and Comments**: Description of the work to be completed and any additional comments | Required if requestor is not MAINTENANCE

    - **Location Type**: (Intersection / Section of Road / Specific Location ) | Required
    
    - **Primary Street:** The name of the primary street at which work will be completed. | Required
    
    - **Cross Street**: The name of the cross street at which work will be completed | Required if Location Type is Intersection
    
    - **From Street**: The name of the first cross street that intersects with the primary street at which work will be completed | Required if Location Type is Section of Road
    
    - **To Street**: The name of the second cross street that intersects with the primary street at which work will be completed | Required if Location Type is Section of Road

    - **Address or Block #**: The street address or block number on the primary street at which work will be comleted | Required if Location Type is Specific Location
    
    - **Area**: The region of the city in which the work will be completed (North / Central / South) | Required
    
    - **School Nearby**: Flag to indicate if there is a school nearby this work location | Required
    
    - **Location Details**: Addtional description of the location at which work will be completed | Optional

4. Click the Create Work Order button to submit the form:
    - An email is automatically sent to the logged-in user confirming that a work order has been created
    
    - You will be redirected to the Work Order Details page
    
    - If Requestor is not MAINTENANCE, Work Order Status will be set to ON HOLD with On Hold Reason of WAITING FOR PLANS

5. Attach Plans. From the Work Order Details page, click the Add Attachment button. Complete the form:
    - **Type**: The type of attachment. Select Plans to attach plans. | Required

    - **Desription**: A description of the attachment contents. | Optional

    - **File**: The file to be uploaded. (Click 'Browse' to locate the file). | Required

    - **Submit button**: click to submit the attachment and return the work order details page.

6. Attach regulation document. If a regulation # was provided when the work order was created, the work order will have  a status of ON HOLD and a hold reason of WAITIN FOR REG until the regulation document is attached. To attach a reg, click on the Add Attachment button:
    - **Type**: The type of attachment. Select Regulation to attach a regulation document. | Required
    
    - See step 5 for adiditional attachment instructions.

7. Verify Work Order Status. The work order should now have a status of NEED TO BE ISSUED. If not, check the WAITING FOR HOLD REASON to add attachments if necessary.

8. Verify Tasks have been created. Scroll down to the Tasks section. There will be one tasks for each workgroup you identified when creating the work order. Each task will have a status of NEW.

9. Add additional tasks. If you need to add additional tasks to the work order, scroll down to the Tasks section, and select the required workgroup from the Workgroup drop-down menu. Click "Create Work Task" to create the work task.

    ##### NOTE: It is not possible to create work tasks if the work order status is ON HOLD.

