[Data Tracker Guides](https://github.com/cityofaustin/data-tracker-guides]) > [Signs & Markings](https://github.com/cityofaustin/data-tracker-guides/tree/master/signsmarkings) > [Create Work Order (Technician)](https://github.com/cityofaustin/data-tracker-guides/blob/master/signsmarkings/create_work_order_tech.md)

#  Create a New Work Order (Markings, Technician)
##### User Role Required: Technician (Signs and Markings)

1. Login: http://transportation.austintexas.io/data-tracker/#home/work-tasks-markings/

2. Click "New Work Order" button.

3. Complete New Work Order form:
    
    - **Work Groups**: the Markings work group(s) that will complete the work. | Required.
    
    - **311 SR #**: The markings 311 service request number related to this work order. | Optional.
    
    - **Instructions and Comments**: Description of the work to be completed and any additional comments | Required.

    - **Location Type**: (Intersection / Section of Road / Specific Location ) | Required
    
    - **Primary Street**: The name of the primary street at which work will be completed. | Required
    
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

5. Verify Work Order Status. The work order should have a status of ISSUED, indicating that work tasks can be completed.

6. Verify Tasks have been created. Scroll down to the Tasks section. There will be one tasks for each workgroup you identified when creating the work order. Each task will have a status of ISSUED.
