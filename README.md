# Auto Ticket Classification using Flow Designer

## Project Overview

This project automates the classification of school IT helpdesk tickets using ServiceNow Flow Designer.

The system analyzes the Short Description of a newly created ticket and automatically assigns the appropriate Category and Subcategory.

## Technologies Used

- ServiceNow
- Flow Designer
- Update Sets

## Categories

| Category | Subcategory |
|---|---|
| Network | Wi-Fi |
| Hardware | Projector |
| Access | Forgot Password |
| Performance | Slow Computer |

## Project Workflow

1. Student creates an IT support ticket.
2. The ticket contains the caller and short description.
3. Flow Designer checks the Short Description.
4. The appropriate Category and Subcategory are assigned automatically.
5. An email notification is sent to the caller.

## Testing

### Test 1 – Wi-Fi

Input:

`WiFi not working in library`

Expected result:

- Category: Network
- Subcategory: Wi-Fi

### Test 2 – Projector

Input:

`Projector not turning on`

Expected result:

- Category: Hardware
- Subcategory: Projector

## Project Files

- Project Update Set XML
- Project Report
- Project Presentation
