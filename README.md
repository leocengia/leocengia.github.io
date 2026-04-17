Stable KB for ACP cases:

---
title: "KB – Account Provisioning & SF Contacts"
description: "Knowledge base (HPO) – Access request, case documentation, verification, contacts, user management, MFA, VIP Access."
---

# KB – Account Provisioning & SF Contacts

## Indice
- [Articolo 1: HPO – Access request](#articolo-1-hpo--access-request)
  - [Policy](#policy)
  - [Process](#process)
  - [Chain properties (Lodging Strategic Partners)](#chain-properties-lodging-strategic-partners)
  - [Property has a property administrator](#property-has-a-property-administrator)
  - [Property doesn't have a property administrator and a pre-existing PC user doesn't exist](#property-doesnt-have-a-property-administrator-and-a-pre-existing-pc-user-doesnt-exist)
  - [Associate an existing PC User Admin to an account(s) that doesn’t have a Hotel Admin](#associate-an-existing-pc-user-admin-to-an-accounts-that-doesnt-have-a-hotel-admin)
  - [Property is in the process of onboarding](#property-is-in-the-process-of-onboarding)
  - [Disassociate or Deactivate user request](#disassociate-or-deactivate-user-request)
  - [Urgent Requests](#urgent-requests)
- [Articolo 2: HPO – Case documentation templates and minimum requirements](#articolo-2-hpo--case-documentation-templates-and-minimum-requirements)
  - [Case documentation guidelines](#case-documentation-guidelines)
  - [Case documentation templates](#case-documentation-templates)
  - [Case documentation templates for TST transfers](#case-documentation-templates-for-technical-solutions--tools-tst-transfers)
- [Articolo 3: HPO – Email address changes](#articolo-3-hpo--email-address-changes)
- [Articolo 4: HPO – Verify a contact](#articolo-4-hpo--verify-a-contact)
- [Articolo 5: HPO – Ownership change or convert a branded property to an independent](#articolo-5-hpo--ownership-change-or-convert-a-branded-property-to-an-independent)
- [Articolo 6: HPO – Modify a Salesforce contact](#articolo-6-hpo--modify-a-salesforce-contact)
- [Articolo 7: HPO – Manage user accounts](#articolo-7-hpo--manage-user-accounts)
- [Articolo 8: HPO – Set up or remove a sign-in verification method](#articolo-8-hpo--set-up-or-remove-a-sign-in-verification-method)
- [Articolo 9: HPO – Text message and phone call authentication](#articolo-9-hpo--text-message-and-phone-call-authentication)
- [Articolo 9 (secondo): HPO – Account and sign-in verification issues](#articolo-9-secondo-hpo--account-and-sign-in-verification-issues)
- [Articolo 10: HPO – Add, modify, or deactivate a VIP Access contact](#articolo-10-hpo--add-modify-or-deactivate-a-vip-access-contact)
- [Articolo 11: HPO – Create a Salesforce contact](#articolo-11-hpo--create-a-salesforce-contact)
- [Bonus 1: Account Provisioning – Approver Checklist](#bonus-1-account-provisioning--approver-checklist)
- [Bonus 2: About the Property Administrator (Admin)](#bonus-2-about-the-property-administrator-admin)

---

## Articolo 1: HPO – Access request

### Introduction
**Always advise property administrators to grant access or deactivate accounts. Assist partners only with any of the exceptional requests.**

### Jump to
- [Policy](https://expedia.lightning.force.com/lightning/r/Knowledge__kav/ka6PE000000QDxhYAG/view#policy)
- [Process](https://expedia.lightning.force.com/lightning/r/Knowledge__kav/ka6PE000000QDxhYAG/view#process)
- [Chain properties (Lodging Strategic Partners)](https://expedia.lightning.force.com/lightning/r/Knowledge__kav/ka6PE000000QDxhYAG/view#LSP)
- [Property has a property administrator](https://expedia.lightning.force.com/lightning/r/Knowledge__kav/ka6PE000000QDxhYAG/view#administrator)
- [Property doesn't have a property administrate and a pre-existing PC user doesn't exist](https://expedia.lightning.force.com/lightning/r/Knowledge__kav/ka6PE000000QDxhYAG/view#no_admin)
- [Associate an existing PC User Admin to an account(s) that doesn't have a Hotel Admin](https://expedia.lightning.force.com/lightning/r/Knowledge__kav/ka6PE000000QDxhYAG/view#no_hotel_admin)
- [Property is in the process of onboarding](https://expedia.lightning.force.com/lightning/r/Knowledge__kav/ka6PE000000QDxhYAG/view#Onboarding)
- [Disassociate or deactivate a user request](https://expedia.lightning.force.com/lightning/r/Knowledge__kav/ka6PE000000QDxhYAG/view#disassociate)
- [Urgent Requests](https://expedia.lightning.force.com/lightning/r/Knowledge__kav/ka6PE000000QDxhYAG/view#additional_info)

---

### Policy

**The property administrator should always create and deactivate user accounts. You should only create or deactivate user accounts under these exceptions:**
- **The property doesn’t already have a property administrator account. Always verify with the requester before assisting with this kind of request.**
- **The property is being onboarded; see _Property is in the process of onboarding_ below.**
- **The property administrator user is no longer working for them or has been unreachable for more than a week.**
- **The property only has a [Corporate level administrator account](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-User-access-levels). This requires you to create a user account that allows the creation of hotel level contacts.**
- **Under specific circumstances when an exception is identified, such as a partner threatening to end their contract with Expedia Group. This should only be done under the discretion of your Supervisor/Manager.**

**Don’t create users for phone multi-factor authentication removal requests. Instead, help them set up or remove a sign-in verification method. Refer to**  
[HPO – Text message and phone call authentication](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Text-message-and-phone-call-authentication)

**Notes:**
- **Before sending a case to TST review if the partner is part of the Managed accounts pilot.**
- **Always check if the hotel you are working with belongs to a strategic account. If it is, then follow the steps indicated in the section _Chain properties (Lodging Strategic Partners)_.**
- **If you identify that an outbound call is eventually required, collect the needed information per [HPO – Case documentation templates and minimum requirements](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Case-documentation-templates-and-minimum-requirements) during the outbound call.**
- **During the inbound call, inform the partner an outbound call will be made to verify their identity to ensure the security of their property's account and you will then gather the necessary details to best assist their request.**
- **If the Partner Central (EPC or PC) access request relates to VIP Access, misroute these cases to the VIP Access team.**
- **If the request is coming directly from a property set up under Consolidator, refer to [HPO – Finance advance – Consolidator hub](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Finance-advance-Consolidator-hub) to verify if there are any restrictions to Partner Central access.**
- **If the request is regarding Partner Central Account email address updates, see [HPO – Email address changes](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Email-address-changes) for the appropriate steps.**
- **User accounts related to Federated Vrbo PX User and Connectivity are internal information only. If the partner is aware of these accounts and requests to modify them, push back to the partner without sending any request to the AP Approvers. Those accounts cannot be modified per system design.**
- **EPC email cannot be changed by approvers once the account is created. The email only can be changed by the property with self-service option (see [HPO – Email address changes](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Email-address-changes)).**
- **EPC Username can never be modified. If found necessary, deactivation of the user should occur and a new one created altogether.**

---

### Process

**At the start of every case, [verify the request](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Verify-a-contact) and check if the property has a [property administrator](https://apps.expediapartnercentral.com/lodging/help/help-article/property/property-administration/about-the-property-administrator-user-role). Based on your findings, follow the appropriate process.**

- [Chain properties (Lodging Strategic Partners)](https://expedia.lightning.force.com/lightning/r/Knowledge__kav/ka6PE000000QDxhYAG/view#LSP)
- [Property has a property administrator](https://expedia.lightning.force.com/lightning/r/Knowledge__kav/ka6PE000000QDxhYAG/view#administrator)
- [Property doesn't have a property administrate and a pre-existing PC user doesn't exist](https://expedia.lightning.force.com/lightning/r/Knowledge__kav/ka6PE000000QDxhYAG/view#no_admin)
- [Associate an existing PC User Admin to an account(s) that doesn't have a Hotel Admin](https://expedia.lightning.force.com/lightning/r/Knowledge__kav/ka6PE000000QDxhYAG/view#no_hotel_admin)
- [Property is in the process of onboarding](https://expedia.lightning.force.com/lightning/r/Knowledge__kav/ka6PE000000QDxhYAG/view#Onboarding)
- [Disassociate or deactivate a user request](https://expedia.lightning.force.com/lightning/r/Knowledge__kav/ka6PE000000QDxhYAG/view#disassociate)

---

### Chain properties (Lodging Strategic Partners)

**Notes:**
- **When receiving a user access request from a Marriott account, reply using the email template _HA - Marriott PC Access Request_ within the _*Hotel Admin_ folder and close your case with no further action needed.**
- **When receiving a user access request from a Four Seasons account, reply using the email template _HA - Four Seasons PC Access Request_ within the _*Hotel Admin_ folder and close your case with no further action needed.**
- **When receiving a user access request from an OYO account, advise them to contact their corporate office.**

#### All users
- **If the contact doesn’t know the admin or the admin no longer works at the property, create a hotel level admin user.**
- **Use the appropriate confluence page to check if the pre-existing admin for that property is a corporate admin under “[chain/brand name] EPC users”.**
  - [Global accounts](https://expediagroup.atlassian.net/wiki/x/HaoYFQ)
  - [Key accounts NA](https://expediagroup.atlassian.net/wiki/spaces/CenOps/pages/353935293)
  - [Key accounts LATAM/EMEA](https://expediagroup.atlassian.net/wiki/x/uKoYFQ)
  - [Key account APAC](https://expediagroup.atlassian.net/wiki/x/ILoYFQ)
- **If the Partner Central user is not within the brand/chain confluence page, disassociate the property(ies).**
- **If the Partner Central is within the brand/chain confluence page, leave it untouched.**
- **If the request is for all brand or chain properties, this is a Corporate admin request. Transfer your case to the Onboarding and Maintenance (O&M) team using CMUI:**
  - **Topic:** Onboarding and Maintenance
  - **Subtopic:** Account Administration

---

### Property has a property administrator

**If the requester is the property administrator:**
- Ask the partner if there is a change of ownership (COO) happening at the property:
  - If no, proceed to step 2.
  - If yes, look for an open COO.
    - If it exists, leave a comment on the case about what the partner is requesting on your case. Then, before closing your case, link the COO as your case's parent. Advise the partner that their request will be handled via the COO case.
    - If no case exists OR a case was closed without resolution, reroute or misroute the case so it can be worked as an ownership case ([HPO – Ownership change or convert a branded property to an independent](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Ownership-change-or-convert-a-branded-property-to-an-independent)) and include the Partner Central (PC) access request details.
    - If a case exists but it's closed as processed, check if it's a PRIME account.
      - If it is, check with the property's Market Manager if it's okay to proceed with the case.
      - If it's not, proceed to step 2.
- Advise them that they can self-service and walk them through if needed.
- Close your case after sending an email:
  - **Type:** Information/Training Provided
  - **Category:** Directed to Self-Service

**If the request is _not_ the property administrator:**
- Advise them to speak to the property administrator to [create](https://apps.expediapartnercentral.com/lodging/help/help-article/property/property-administration/create-user-accounts-for-your-property?langId=1033), [edit, or remove](https://apps.expediapartnercentral.com/lodging/help/help-article/property/property-administration/change-security-access-levels-for-existing-user-accounts?domain=HOTEL) the requested user.
- Send the requester the _Partner Central Access – Requester_ template from the _*Training and Self- Service_ folder.
- Send the admin the _Partner Central Access – Hotelier admin_ template from the _*Training and Self-Service_ folder.
- Close your case.
- **Note:** You can share the first and last name of the administrator with the caller, once they’ve been verified. Don't share contact details.

**Important (HA unreachable):**  
If the requester claims the existing property's Hotelier Admin (HA) no longer works at the company or HA has been unreachable for more than a week, and there is no other HA associated with the property, **do not disassociate the HA from the property.** Instead, include the information in the Account Provisioning (AP) checklist's **User Details** section. The AP approver will review if HA disassociation or deactivation needs to happen.

Also, identify which instructions to follow depending on if the requestor has a pre-existing user or not:
- [Associate an existing PC User Admin to an account(s) that doesn’t have a Hotel Admin](https://expedia.lightning.force.com/lightning/r/Knowledge__kav/ka6PE000000QDxhYAG/view#no_hotel_admin)
- [Property doesn't have a property administrator and a Pre-existing PC user doesn’t exist](https://expedia.lightning.force.com/lightning/r/Knowledge__kav/ka6PE000000QDxhYAG/view#no_admin)

**If there is an existing HA and the request to approvers does not mention why self-service was not possible, approvers will reject the request as the partner is expected to self-serve.**

---

### Property doesn't have a property administrator and a pre-existing PC user doesn't exist

**Note:** If a property has no Hotelier Admin user account and the partner requests to create a non–Hotelier Admin user account, inform them that a Hotelier Admin user account needs to be created first.

- Ask the partner if there is a change of ownership (COO) happening at the property:
  - If no, proceed to step 2.
  - If yes, look for an open COO.
    - If it exists, leave a comment on the case about what the partner is requesting on your case. Then, before closing your case, link the COO as your case's parent. Advise the partner that their request will be handled via the COO case.
    - If no case exists OR a case was closed without resolution, reroute or misroute the case so it can be worked as an ownership case ([HPO – Ownership change or convert a branded property to an independent](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Ownership-change-or-convert-a-branded-property-to-an-independent)) and include the Partner Central (PC) access request details.
    - If a case exists but it's closed as processed, check if it's a PRIME account.
      - If it is, check with the property's Market Manager if it's okay to proceed with the case.
      - If it's not, proceed to step 2.
- Ask the requester who the property administrator should be and retrieve the administrator’s position title, full name, and email as per [HPO – Case documentation templates and minimum requirements](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Case-documentation-templates-and-minimum-requirements).
  - If the requestor doesn’t know who the administrator is:
    - For property with an account owner: contact the property’s Market Manager for assistance
    - For property without an account owner (PGA): HPO will take full ownership of obtaining this information
- Once an administrator has been identified, add the administrator’s verified contact to the property’s Salesforce (SF) contact list and update this contact on the case.
- Confirm if the contact should be associated with other properties:
  - If yes, check if the other properties have a Hotelier Admin user account.
    - If yes, redirect the requestor to contact each individual property’s Hotelier Admin for self-serve on associating the user account.
    - If no, check if the properties are linked by similar chain/brand/property.
      - If yes, proceed and include the user association request with the request for user creation.
      - If no, create a child case per property and work the case from the beginning.

**Bulk note:** For requests of 10+ properties or users, send a sequential case to the bulk team with required details from **Account Provisioning Approvals** in [HPO – Case documentation templates and minimum requirements](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Case-documentation-templates-and-minimum-requirements).

- If request received via Contact Us, chat, or intake form proceed.
- If request received via inbound call:
  - Complete an outbound call to the property's primary phone number to speak to the requestor OR get a written confirmation from an active previously verified contact.
- Send a request for account provisioning:
  - Document evidence per [HPO – Case documentation templates and minimum requirements](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Case-documentation-templates-and-minimum-requirements) and [HPO – Verify a chat contact](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Verify-a-chat-contact).
  - Select **Save** after filling required info from the **Account Provisioning** tab.
  - Update **Primary** and **Secondary Categories** in **Case Update** tab → **Save**.
  - Select **Submit For Approval**.
  - Case auto-updates to **Pending** and **Review** task created.
  - If approved: case updates to **Closed** and partner receives automatic confirmation email.
  - If rejected: case status becomes **Opened** and reason appears in case comments.

---

### Associate an existing PC User Admin to an account(s) that doesn’t have a Hotel Admin

- Ask the partner if there is a change of ownership (COO) happening at the property:
  - If no, proceed to step 2.
  - If yes, look for an open COO (follow same COO guidance as above).
- Find the existing PC User Admin’s contact in SF. Contact should indicate **“Expedia - SFDC; EPC”** in **Connected Systems** under contact’s **Details** tab.
- Add a relationship between this contact and the account(s) which the contact should be associated with.
- Follow steps 5, 6 and 7 from section **Property doesn't have a property administrator and a Pre-existing PC user doesn’t exist**.

**Notes:**
- If the PC User Admin needs to be associated with several properties not associated with a brand/chain, create a child case per property and work each case from the beginning.
- For requests of 10+ properties or users, send sequential case to bulk team (see documentation template guidance).

---

### Property is in the process of onboarding

Properties in onboarding will already have an active Hotelier Admin user. However, this user will not be able to create other users until onboarding is completed.

You may assist with user creation/association only if:
- Request is received directly from the Partner doing Onboarding
- Request is received from the New Partner Team associate or Market Manager in charge

Once processed, tell the partner that Hotelier Admin users can self-serve user creation after go-live.

**Important:** Push back on requests to create a user account with a generic username (e.g., “Reservations Team”). Always ask for first and last name.

In exceptional cases, you can associate an existing user account with a generic name to the onboarding property only if critical to speed up onboarding; reiterate that a new account must be created later.

---

### Disassociate or Deactivate user request

#### Non-bulk Requests

**If the request is only to disassociate the user from the account(s), determine if the account(s) has a Hotel Admin:**
- If yes, advise self-serve (Hotelier Admin can detach users; push to Self-Service).
- If no, proceed with disassociation and assist partner with creating a Hotel Admin:
  - If pre-existing user: follow guidance under **Associate an existing PC User Admin...**
  - If no pre-existing user: follow guidance under **Property doesn't have a property administrator...**

**If the request is to deactivate a user that isn't the last remaining hotel admin:**
- Check if the user is linked to any accounts.
- If yes, inform requestor that property administrator(s) must detach the user prior to deactivation (security). Place case in Pending-Partner.
- Once admin detaches in Partner Central:
  - Remove property association from any SF contact sharing same email as detached user. See [HPO – Modify a Salesforce contact](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Modify-a-Salesforce-contact)
- If admin cannot do it, send request to AP Approvers following steps 6 and 7 from **Property doesn't have a property administrator...**

#### Bulk requests

Proceed to submit directly for approval following bulk submission guidance from the Note section of either:
- **Associate an existing PC User Admin...** or
- **Property doesn't have a property administrator...**

**Note:** If requester claims existing HA no longer works or unreachable > 1 week and no other HA exists, don’t disassociate HA; include info in AP checklist **User Details** section. AP approver will decide disassociation/deactivation.

---

### Urgent Requests

**Note:** This information doesn’t apply to user creation.

If partner needs urgent action or waiting for TST technical resolution, use judgment:
- If urgent or not self-service item, you can complete it.
- If can be pushed to self-service without creating additional risk, push to SS as well.

Refer to:  
[HPO – Account and sign-in verification issues](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Account-and-sign-in-verification-issues)

---

## Articolo 2: HPO – Case documentation templates and minimum requirements

### Introduction
**When documenting a case, use the templates listed below as the minimum standards for case documentation. Submit the information as a case comment.**

### Case documentation guidelines
- Use these templates for internal documentation only.
- Write your case comments in English.
- Don't use these templates for partner-facing documentation. Keep partner interaction notes professional.
- Don't add personal information (e.g., credit card info, phone numbers, addresses).

### Case documentation templates

Use the following templates as minimum requirements; additional info may be needed depending on scenario.

| Type of Case | Information to Include |
|---|---|
| Standard Cases | - Duplicate (Y/N)<br>- Use Salesforce (SF) to document duplicate cases following case management guidelines.<br>- Request Details<br>- Record booking ID / Remittance Advice # / Invoice # / Etc.<br>- Issue Description – Brief overview<br>- Action<br>&nbsp;&nbsp;- Who requested it<br>&nbsp;&nbsp;- What action is requested and why<br>- Action Still Needed (if not complete/transferred)<br>&nbsp;&nbsp;- What action needs to be completed and why<br>&nbsp;&nbsp;- Who needs to complete it<br>&nbsp;&nbsp;- Whether follow-up is required and when |
| Chat Cases | If immediate resolution and chat ended: use **Case Summary** → **Feed** → **Generate Summary** → review → update if needed → **Post Summary** → see under **All Case Comments**.<br><br>If no immediate resolution (investigation/other team): set expectations and reroute to frontline associates. Include:<br>- Partner Name<br>- Email Address<br>- Verified (Y/N)<br>- Expedia ID<br>- Booking ID<br>- Issue<br>- Findings<br>- Actions Taken<br>- Actions Required<br><br>When partners become unresponsive see [HPO – Abandoned chat process](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Abandoned-chat-process). |
| Tax Cases | - Record if amount is RM or Indirect tax in PQC<br>- List current taxes from Partner Central<br>- Add updates you made and what partner requested |
| Consolidator Cases | - Consolidators' Name<br>- List consolidation<br>- Remit Vendor ID (VID)<br>- Property Vendor ID (VID)<br>- List IDs you are working on<br>- Record Action Taken<br>- List issue<br>- List resolution |
| Disney-related Cases | See [HPO – Consolidator information - Disney](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Consolidator-information-Disney). Include:<br>- Disney Invoice Number<br>- Transmission Queue ID<br>- Date Uploaded if different from partner file date (see [HPO – Upload Disney invoices](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Upload-Disney-invoices)) |
| Account Provisioning Approvals | Include in **User Details** section of AP checklist:<br>- First Name<br>- Last Name<br>- Username (not applicable for user creation)<br>- Email<br>- Level of [Access Requested](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-User-access-levels) (optional for MFA reset)<br>- Evidence of communication (even for already verified contacts). Acceptable evidence includes:<br>  - Screenshot/video of outbound call (must show real-time date/time, outbound status, phone number called, duration ≥ 15 sec)<br>  - Written request from Contact Us origin (same EID, contains required info) **or** written verification from a verified contact not matching requestor email (must contain username if applicable, full name, email, access level, action, reason SS not possible)<br>  - Chat request (transcript attached; must be same EID and include username if applicable, full name/email, access level, action, reason SS not possible)<br>  - Written request from MM or PSA (verification done; include required fields + reason SS not possible)<br>- Additional Comments<br>- What action needs to be done (one or more): Create new user; Associate user to [EID(s)]; Modify user; Deactivate user; MFA reset<br>- Reason why self-serve cannot be done and AP is needed<br>- If MFA reset: last 3 digits of MFA<br>- Preferred language<br><br>**For Bulk requests** add:<br>- EIDs<br>- Contact Verification Type<br>- User Updated in SF? (Y/N)<br>- Email Fraudulent/Quarantined? (Y/N)<br>- Duplicate User Accounts Exist? (Y/N)<br>- Multi Properties? (Y/N)<br>- Multi-User Accounts? (Y/N)<br>- Is Disassociation needed? (Y/N)<br><br>**For Ownership Change derived PC access** ONLY valid verification method is ALL of:<br>- Sales/Ownership agreement or bill of sale<br>- New owner name matches requested user name (or notated exception)<br>- Email used to send contract link matches creation email or old owner email<br>- Ensure new owner signed before AP review<br><br>**Important Notes** include outbound call recording requirements, generic-name restrictions, APAC name exceptions, Contact Us required content, fraud prevention instructions. |
| Hotel Closure Outreach | - Property Response<br>- Centrally Managed: Y/N (chain name)<br>- Last SF Case Activity<br>- Availability in EPC: Y/N<br>- Temp/Seasonal Closure in EPC: Y/N<br>- Availability on Hotel Site: Y/N<br>- Shopped: Y/N - results<br>- OB Call to Verify Status: Y/N<br>- Spoke to<br>- Outcome<br>- Reservations Search (earliest arrival date + total active impacted bookings; add total to Number of Requests field)<br>- Attached Reservation List: Y/N<br>- Outstanding Invoices: Y/N<br>- Nearby Properties Contacted/Outcome |
| Conversation Platform & Customer Engagement (Hotel Traveler) Relocation Transfers | - Reason for Relocation (Confirmed Hotel closed by TPG)<br>- Number of reservations affected<br>- List of bookings (Guest Name, Booking ID, Date of Arrival)<br>- Alternative options offered |
| Bulk Request | **Important:** Frontline agent reviews request and clarifies with partner before sending to Bulk. Always create sequential case with **Topic:** Bulk, **Subtopic:** Bulk Update Request.<br>- Requests accepted in English only<br>- Add all details needed to create same product in Partner Central<br>- Attachments accepted in editable formats only (Excel, Word) – no screenshots/PDF<br>- Include room type/rate plan codes or names<br>- Refer to [APM templates](https://expediacorp.sharepoint.com/:x:/s/AST/Ee84WfYHMV9Fn7lJRu669l8BpZfldTWTtq3hOtuM5yh4ZA?e=c5rh4P) if needed<br>- For ARI property update, review [HPO – ARI property and product setting updates](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-ARI-property-and-product-setting-updates) before sending to Bulk |
| Bulk Request (Price Model OBP → PDP) | - Confirm people included in base rate for new rate plans<br>- Extra Person Fee sets for PDP model<br>- Confirm promotions/linkages to be copied<br>- After bulk closure: ask partner update room rates and remove Stop sell |
| Relocation (Trained Associates Only) | In Case Description include:<br>- Name and title of caller<br>- Reason check-in dates impacted<br>- Fault<br>- Dates relocation needed<br>- Impacted Booking IDs<br>- Updated room or Walk option?<br>- Additional comments |
| Executive Escalations | - Proof escalation from Ariane Gorin / senior executive / Legal / Prevent team<br>- Issue reported<br>- Partner request/expectation<br>- Root cause (if known)<br>- Financial impact<br>- Actions taken<br>- Next steps (if any)<br>- Prevention recommendation (if applicable) |

### Case documentation templates for Technical Solutions & Tools (TST) transfers
- State the problem
- Include screenshots and/or video (co-browse) if possible
- Property Info: Property Name (EID)
- Issue Description: detailed what happens vs expected
- Steps taken to resolve: detailed research/troubleshooting
- Include specifics per issue:

| Issue | Specifics to Include |
|---|---|
| Booking Issues | - Use Salesforce Flows (records most TST info)<br>- Calculation: settings and rate calculator screenshot<br>- Virtual card: findings from EVC Admin Tools and Merchant Point |
| Live Site Issues | - URL where error occurs<br>- Content: screenshots from live site & Partner Central comparing behavior/settings<br>- Rates incorrect: shopping path (POS, stay dates, rate plan IDs, guests)<br>- Confirm reproducible in incognito |
| Partner Central Issues | - URL where error occurs<br>- Exact steps to reproduce<br>- Screenshot/video of error (video preferred)<br>- Confirm reproducible in incognito<br>- Username<br>- Browser used |

---

## Articolo 3: HPO – Email address changes

### Introduction
**Partner Central Account email address updates must be carefully managed to keep partner information safe and secure. Partners must edit their email addresses themselves on the Profile page of Partner Central.**

Advise partners to change email on the **Edit Profile** page. See:  
[HPO – Edit profiles](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Edit-profiles)

**Important:**
- Always verify requester employment prior to making contact changes. See [HPO – Verify a contact](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Verify-a-contact).
- Some SF contact info can only be modified by partner through Partner Central (First Name, Last Name, Phone, Mobile, Email) under **Profile** → **My Account**.

Best-case: change from free domain to company domain (e.g., Jdoe@gmail.com → JohnD@hilton.com).

Additional guidance:
- If account name and email indicate different person, check if shared account (other accounts use same email).
- If multiple users use same email: inform users cannot share accounts or email messages.
- If no one else uses that email: document circumstances before fulfilling request.
- If anonymous account (generic names): deactivate and create new after calling to confirm employment.

Notes:
- Connectivity providers are exception to proactive deletion.
- Avoid free domain emails when possible; accept if company email not provided and verification successful.
- Hotelier Admin receives automatic email when a user changes their email; helps ensure ex-employees aren’t maintaining access.

---

## Articolo 4: HPO – Verify a contact

### Introduction
**When a contact is displayed as NOT verified in a Salesforce case’s Contact Details section, verify a partner before actioning their request to prevent fraudulent activities.**

### How to verify a contact
For phone call: check property primary phone number matches Salesforce account page and Partner Central.

To verify, confirm partner works at property. Verify:
- First name
- Last name (not required for India/Indonesia)
- Phone number
- Cell number
- Role
- Email address

If existing contacts calling from verified number: select from contact dropdown and confirm phone matches property phone.

If contact unverified or missing: ask partner to log into Partner Central → Home → Internal tools → **User Tasks** history tool → confirm accessed user details. If partner logged in via active property user, property provided access; agent can verify employment and assist; can add SF contact if needed.

**High-risk scenarios must NOT be verified via User Tasks; ONLY outbound call:**
- Change property payment method to virtual card or remove virtual card
- Change property bank account details (if SS not possible due technical limitation)
- Create new account for a different property than the one used to connect to Partner Central

If User Tasks unavailable: always call property primary phone number listed in Salesforce; don’t verify using non-primary number used to call.

If cannot verify via User Tasks/outbound call and no other verified contact: if property has verified email accessible, send email and ask immediate response:
> “Please reply to this email to verify your affiliation with this property.  
> Fill in the following information:  
> - First and last name  
> - Email  
> - Phone number  
> - Role  
> Thank you”

**High-risk scenarios must NOT be verified via email; ONLY outbound call** (same as above).

### Unsuccessful outbound call
If verification requires outbound call and unsuccessful:
- Email a verified contact (not requestor) to approve request
- Set Unverified Contact Reason = Pending Verification
- Place case in Pending Callback (not pending-partner to avoid auto-closure)
- Attempt 3 outbound calls within a week; if still unsuccessful set reason = Unable to Verify; do not proceed; comment + close case
- If verified contact replies with approval, verify contact and proceed
- If requester not validated by existing verified contact, escalate to ERS Risk via Fraud Review button

### Multiple user/property request
- Independent properties: verify contact and add them to each property

**Single user access to multiple properties**
- Confirm properties linked by chain/brand/provider or same Managed By
- Properties linked if Owned By same person (verify on SF property account page)
- If not linked: must call/validate against each property/brand requested
- Verify requester is already authorized user for at least one property; no need to validate each property requested

**Multiple user requests**
- Verify only requester; create sequential case for Bulk PRI request
- New user accounts created in Partner Central auto-create verified SF Contact via sync (~15 minutes)

### Transferring to different teams
- Multi Request: original associate must verify before creating multiple cases
- Sequential Process Request: original associate must verify before creating sequential case
- Misrouted Case: associate working misrouted case must verify  
  *Efficiency note: first associate should verify if actions taken before misrouting.*
- Reroute from Chat: if partner is same but contact unverified, manually check verified box before routing; otherwise routed-case associate verifies new contact
- Transfer from Phone: phone team must verify before transfer

### Contact Us cases
If case via Contact Us and partner attached to property, but SF contact marked unverified: agent should update contact to verified because partner already verified through Partner Central.

---

## Articolo 5: HPO – Ownership change or convert a branded property to an independent

### Introduction
Process for recontracting when ownership changes. If staying with same owner and requesting contract changes see:  
[HPO – Business models and contract changes](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Business-models-and-contract-changes)

### Policy
Ownership change requires recontracting when ownership passes. Converting branded to independent can occur with or without new owner. Ownership change may be necessary for payment/billing updates; see:  
[HPO – Update payment and billing information](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Update-payment-and-billing-information)

Some OC requests derive from new owners incorrectly registering duplicate onboarding account; merge as duplicate and onboard under existing account through OC. Guide partner to self-serve updates:  
[HPO – Partner self-service](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Partner-self-service)

Notes:
- Individual properties cannot opt in/out of chain agreements
- Chains: central contact must reach out to O&M team
- APAC exception: regional chain/aggregator not strategic partner handled by APAC Specialist Team (see Regional chains link)

VIP access properties:
- If VIP property create case for VIP team via CMUI Topic: VIP Access / Subtopic: General VIP Access Inquiries (see VIP recognition article)

Partner Central access:
- PC access requests raised while OC open should be handled via OC case; contact old owner to verify; provide SS guidance and/or actions according to Access request article; proceed in separate PC access child case to OC.
- If request has separate case, original PC access case owner links as child and closes theirs.
- Important: PC won’t show invoices for previous owner after OC; advise partner to retrieve invoices before processing OC.

Unassigned territory:
- If EID inactive/consolidator/3PI: direct to onboard via Join Expedia Lead sign-up process
- If EID active: ask leadership to help update territory (see identify segment/service tier/territory)
- Place case in Pending-MM while awaiting territory update
- After territory assigned proceed with OC process
- For VR see VR ownership changes

Step by Step (high level):
- For Phone/Chat origin: check assigned territory; if none see Unassigned Territory; if assigned gather new owner contact info; if partner wants to close inventory direct to self-service inventory close-out; reroute via CMUI: Contract Loading / New Contract with reasons/talking points
- For Non-Phone/Chat origin: check territory; if none see Unassigned Territory; if assigned misroute: Contract Loading / New Contract

---

## Articolo 6: HPO – Modify a Salesforce contact

### Introduction
**Find the steps to update a contact from the contact record.**

**Important:** If request requires 10+ actions per category follow [HPO – Bulk requests](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Bulk-requests).

### Update a contact via the contact record
- Search by first/last name and/or email in Salesforce
- Select contact → **Details**
- Edit fields (pencil icon)
- **Save**

### Update relationship at a specific property
- Search contact
- Under **Related Accounts** select **View All**
- Down arrow on hotel → **Edit Relationship**
- Update info → **Save**
- Repeat for additional accounts as needed

### Salesforce-only Contacts
Validate contact via property account on Salesforce if contact is Salesforce-only (not synced from Partner Central or Vrbo UMS):
- Account page → Related Contacts
- Select Contact Name → Details
- In **Validate Contact Email And Phone Numbers** see validated status
- Update Email and Phone with valid values
- Select **Update And Validate Fields**
- Note: Email validated via Kickbox API; phone/mobile via Twilio via GPNV API

### Remove a contact via the contact record
If no Property Admin and verified contact calls to remove account from Partner Central:
- Disassociate user account from property if requester verified
- Account remains live and documented in Salesforce for possible re-association
- Hotel Admin responsible to inform EG when someone leaves; no process other than property informing us
- Important: ensure any Partner Central users are disassociated before removing contact
- If request from O&M: don’t misroute; follow below:
  - Open property SF account
  - Contacts → Related Contacts
  - Identify chain contacts by email domain (e.g., @accor.com, @hilton.com)
  - Down arrow → **Remove Relationship**
- If contact only associated with that property: deactivate entirely

---

## Articolo 7: HPO – Manage user accounts

### Introduction
**Create a new user account, change permissions, or give a user access to another property.**

Notes:
- Searching by Property ID in Partner Central User Accounts: only internal users can view all roles. Don’t share internal role details/screenshots with external partners (Multisource Users, Market Managers, etc.). Connectivity Vendor info may be shared if necessary.
- If property has at least one administrator: direct to self-serve via People section in Partner Central. If no admin available (left/unreachable >1 week), follow exceptions in [HPO – Access request](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Access-request).

Partners use a single login for all portals (One Identity). When admin invites a new user, account is created through One Identity and user emailed invite.

Before creating invite:
- Review Confluence [Account Provisioning—Approver Checklist](https://expediagroup.atlassian.net/wiki/x/mFhpIQ)
- Verify partner already under One Identity:
  - Open Partner Central → User Account
  - Search user within property
  - Edit user profile
  - Look for **EG Identity** label (means migrated to Unified Partner Login)

#### To create an invite
- Partner Central → **User Accounts**
- **Create a new account**
- Role: **External User Profile**
- Enter first name, last name, email
- **Next** → select property and role
- **Invite**

#### To change user permissions
- Search user in EPC → User accounts
- Pencil under View/Edit next to user
- 3 dots under Actions in associated properties section
- **Edit role**

#### To give a user access to another property
- **Add Property** on User account page
- Input Hotel ID + role
- **Add Property**

#### To remove a user account from being associated with a property
Only exception where non-AP trained associate can take action without AP review if user is **not** an administrator:
- Actions menu → **Remove User** → confirm

Notes:
- User accounts can still exist without property attachment, but new user invite must attach to at least one property.
- Connectivity provider accounts removed automatically when connectivity changes; if still listed escalate to TST.
- Hotelier Admin users can remove users with their same access level (Hotelier Admin).

---

## Articolo 8: HPO – Set up or remove a sign-in verification method

### Introduction
Accessing Partner Central requires sign-in verification (MFA) in certain cases (code via text/phone).

**Note:** MFA process will transition to Unified Partner Login later this year; for now use legacy MFA.

#### Add a verification method
- Profile icon → **User settings**
- **Secure Account**
- Note: No verification required when MM marks contact verified or provides written statement
- Choose set up text verification / phone call verification / mobile app push and follow prompts
- Enter code → **Continue**

#### Remove a verification method
- Profile icon → **User settings**
- **Secure Account**
- Scroll Security Settings
- Select number → **Remove** → follow prompts

#### Help partner without access to their only verified number
- MFA reset requests only from user who owns MFA
- If requester attempting reset for another user: redirect (security)
- If user no longer works: requester needs own account; MFA reset user must be disassociated/deactivated → follow [HPO – Access request](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Access-request)

Assist with resetting MFA:
- Confirm phone number to remove
- Document evidence per [HPO – Case documentation templates and minimum requirements](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Case-documentation-templates-and-minimum-requirements) and [HPO – Verify a chat contact](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Verify-a-chat-contact)
- Save required info in Account Provisioning tab
- Update case categories in Case Update tab → Save
- Submit for Approval
- Case updates to Pending and Review created
- If approved: case updates to Opened and you can send written confirmation then close
- If rejected: case remains Opened with reason to address

Requests received via live chat:
- Requestor must provide first name, last name, and email matching verified contact in Contact Details to be considered verified for MFA reset.
- If mismatch: advise call us OR advise transfer to local team and set expectations on processing time.

---

## Articolo 9: HPO – Text message and phone call authentication

### Introduction
MFA is extra security measure. Used when partners are prompted for numeric code via text/phone.

Partners can use email-based MFA on previously verified devices/browsers, but text/phone preferred.

MFA email must match One Identity email; changing one updates the other.

**Note:** MFA process will be updated in late Q3 or Q4 this year.

### About MFA
Any user account signing in requires MFA. Only EQC connectivity API logins don’t need MFA.

Used when:
- Viewing reservation credit card details / PII
- Viewing Expedia Quick Connect property settings
- Editing profile email address
- Adding/removing other MFA numbers
- Updating notification settings
- Changing device/browser
- Signing in after long time
- Clearing cookies
- Using Chrome incognito

### MFA settings
Partners set up SMS/phone via Partner Central profile. First time includes email link confirmation. Up to 5 numbers per week. Multiple countries allowed. System defaults to previously used method.

Partners can remove a phone number via **Unverify devices**. Help partners if no longer have access to only registered number.

Notes:
- If active user account name is generic: advise Hotelier Admin to deactivate and create new account with unique email.
- Generic names examples: “hotel manager”, “reservations department”, property name (unless matches user name).
- If only one contact in SF for property and it’s Hotel Admin with generic name: exception may be approved by AP reviewers for MFA reset.
- For NON-hotel admin only account: deactivate and create new with Hotel Admin access per [HPO – Access request](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Access-request).

### Fallback settings
Partners can use fallback method if code not received. Encourage text notifications. Email works only on already verified browser/device; clearing cookies removes email option.

### Partner support
- [HPO – Set up or remove a sign-in verification method](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Set-up-or-remove-a-sign-in-verification-method)
- [HPO – Account and sign-in verification issues](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Account-and-sign-in-verification-issues)

---

## Articolo 9 (secondo): HPO – Account and sign-in verification issues

### Description
**Troubleshoot common Partner Central account access issues. Always verify the contact requesting account help.**

**Important:** It’s against policy to sign in to Partner Central/PCO using partner credentials.

Additional note: in user search by Property ID, internal users can now see all roles; do not share internal role info/screenshots with external partners. Connectivity Vendor info acceptable if needed.

See also:
- [HPO – Escalate requests for fraud contact review](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Escalate-requests-for-fraud-contact-review)
- [Partner Central multiple login request form](https://expedia--c.documentforce.com/servlet/servlet.FileDownload?file=015C0000001y7MP)
- [HPO – File a case for issues with Partner Central and login verification](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-File-a-case-for-issues-with-Partner-Central-and-login-verification)

### Case scenarios

**Access to another user’s account (e.g., user sick or no longer employed)**
- Explain each user needs own access for security.
- If Hotelier Admin unavailable: create new account per [HPO – Access request](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Access-request).

**Forgotten password**
- Ask partner to use “Forgot your password?” link.
- Password rules:
  - ≥ 7 characters, letters+numbers
  - Not match/resemble previous 4
  - Difficult to guess, no common words
  - Case sensitive
  - Should not be known breached
- After 5 failed attempts account locks for 30 minutes; cannot remove lock.
- Password error messages examples included (leaked list / too similar).

**Invalid email/password message**
- Confirm correct email associated with property and password.
- Unicode must match exactly; no wide-form characters.
- Check for fraud; escalate if needed. If not fraud: ask partner to reset password.
- If escalation message displays: send to Fraud team.
- Important: don’t mention potential fraud to partner.

**Inaccessible account email address**
- Ask partner to contact email provider.

**Multiple users sharing email/account**
- Explain unique email per account required.
- Follow access-to-another-user flow.

**Property user list**
- See [HPO – Manage user accounts](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Manage-user-accounts)
- Provide list to manager/primary contact/Hotelier Admin if needed via verified email.

**Suspicious-looking email or compromised account**
- See [HPO – Partner inquiries about Suspicious/Phishing Communication with talking points](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Partner-inquiries-about-Suspicious-Phishing-Communication-with-talking-points)

### Verifications
**Important:** Don’t provide login verification code via phone or email.

Verification messages: ask about device/browser and what they’re accessing; appears when changing device/browser, not signed in recently, clearing cookies, incognito, accessing secure info (PII, settings, profile email, MFA numbers, notifications).

### Verification code not received
Internal-only: email MFA may work on previously verified device/browser.

- Ask partner to try fallback method (see set up/remove verification method article).
- For email only:
  - Check spam/junk; add admin@expediapartnercentral.com to trusted list
  - Confirm email correct (especially new accounts)
  - If not received, [verify we sent the email](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Lodging-notification-status-tool?r=1115&ui-knowledge-components-aura-actions.KnowledgeArticleVersionCreateDraftFromOnlineAction.createDraftFromOnlineArticle=1)
- EVC-SCR: send IP allow list if blocked (see partners need help receiving emails)
- TST: remove strategic/corporate accounts from verification
- Ask partner reset password; if still no email escalate via file-a-case article.
- In Partner Central: User accounts → View/Edit → View verification history → review errors.

### Common issues
**VOIP number for SMS**
- Verify user and check fraud; if cannot verify flag ERS.
- If fraudulent: deflect with no additional info.
- Suggest phone call MFA or mobile number for SMS.
- If delayed SMS > 5 min, check Verification History; use Resend; follow TST transfer guidelines.
- If code not sent: request TST open Identity JIRA with username, hotel ID, last attempted call time, tag “Twilio call attempt not found.”
- If code sent but error: if user verified and not fraudulent, copy error text and open Twilio help center case with provided template (includes UUID, SIDs, etc.).

**Verification code not received via Partner Central app**
- Ensure latest app version and login at least once.
- Mobile app verification not available for iOS 12 or earlier / Android < 6.
- If cannot verify, flag ERS; if fraudulent deflect.
- Ask TST open Mobile App JIRA with username, hotel ID, last attempted call time, tag “Verification attempt not found.”

---

## Articolo 10: HPO – Add, modify, or deactivate a VIP Access contact

### Introduction
VIP Access trained associates process VIP Access contact update requests and request Partner Central account provisioning.

### Request account provisioning for VIP Access
Follow account provisioning steps in:  
[HPO – Access request](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Access-request)

### Create a new VIP Contact
Property Administrator should create contacts in Partner Central. If none, we can create:
- Follow [HPO – Create a Salesforce contact](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Create-a-Salesforce-contact)
- In Email Preferences edit VIP Access notifications:
  - VIP Access: Arrival Notifications
  - VIP Access: Customer Care
  - VIP Access: Program Management (VIP Reporting Frequency monthly)
- If modifying VIP Access Primary contact:
  - choose VIP Primary Contact and add today’s date in VIP Primary Contact Changed field
  - property page → Update Contact Lookups → select primary contact → save
- If Primary VIP Access contact changed:
  - use template VIP Access Primary Contact Change and CC market manager
- Follow [HPO – Access request](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Access-request)
- Send VIP Access Primary Contact Change email to contact and requester, copying VIP Access and LPS Market Managers
- Update case details:
  - Resolution Type: Request Processed
  - Primary Category: Contact updates
  - Secondary Category: Add contact
  - Close case

### Modify a VIP Contact
Partners with VIP Access should modify themselves; walk them through steps and update SF contact as needed.
If requesting general contact updates and EPC Hotel Verified, they must update in Profile in Partner Central. Send template VIP Access Existing Partner Central Contact Update copying VIP Access and LPS Market Managers.

Steps:
- Search contact in SF
- Confirm requester verified (see Verify a contact)
- Select contact → Related → find property → Edit Relationship
- Enable/disable requested VIP Settings
- In Partner Central: Guest Relations → VIP Access → Update in VIP Access Contacts → choose contacts → Save
- Send confirmation email (VIP Access Primary Contact Change), copying VIP Access and LPS Market Managers if any
- Update case fields (Request Processed / Contact updates / Modify contact) and close

### Deactivate a VIP Contact
- Search contact in SF
- Confirm requester verified
- Contact → Related → property → Edit Relationship
- Deselect all VIP Access notification checkboxes
- If user needs removal from property and Partner Central: follow Deactivate a Salesforce contact
- In Partner Central: VIP Access → Update → trash icon remove contact
- Important: must have at least one VIP Contact listed; obtain replacement first if only contact
- Update case fields (Request Processed / Contact updates / Remove contact) and close

---

## Articolo 11: HPO – Create a Salesforce contact

### Introduction
**Steps to add a brand-new contact to Salesforce or add a relationship to an existing contact.**

**Important:** If request has 10+ actions per category follow [HPO – Bulk requests](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Bulk-requests).

### Add a new contact
- Search SF by first/last name and/or email to confirm if existing
- If no contact exists, go to property Account page
- Account → Contacts tab → **New Contact**
- Choose correct type:
  - Core OTA properties: Contact (Standard external contact)
- Enter required details:
  - First and last name (not all caps)
  - Email
  - Phone or mobile (capture both if available)
  - Written language
  - Spoken language
- Follow [Verify a contact](https://expedia.lightning.force.com/articles/en_US/Knowledge/HPO-Verify-a-contact)
- Select Contact Verified checkbox if appropriate
- Save
- If contact applies to multiple properties, add relationships (see Add relationship section); ensure verified at all properties

### Add a new relationship to an existing contact
- Search SF for existing contact
- Call property phone number and verbally verify requester employed (cannot add/update until complete)
- Select contact → Related Accounts → Add Relationship
- Enter Hotel name or Expedia ID
- Select Primary contact or EVC contact if needed
- Select Contact Verified checkbox if appropriate
- Save

Note: phone field auto-populates from account phone number; can overwrite with partner’s number.

Verification outcomes table:
- Verification Successful → Create/modify contact as needed
- Requester Unavailable → Create contact but don’t check Contact Verified
- Verification Fails (Fraud Not Suspected) → Create contact but don’t check Contact Verified; advise cannot verify employment
- Verification Fails (Fraud Suspected) → Create contact without Contact Verified; set Unverified Contact Reason = Suspected Fraudulent Contact; advise cannot verify; escalate per Fraud escalation process

---

## Bonus 1: Account Provisioning – Approver Checklist

> Documento usato dagli agenti che approvano/respingono richieste AP.

### For Account Provisioning (AP) reviewers only
- Approvers should not review and approve their own reviews. If Omni assigns you your own case review, put task in pending and ask peer/leadership to reassign.
- Managed Accounts / Federated login = SSO; partners should contact internal technical team; if frontline created review task, push back. EPC tool will block creation with UI error indicating federated partner must use EPC SSO.

Managed account pilot:
- Belmond – Start date July 15, 2024
- Radisson – ROW – Start date TBA
- H World International – Start date TBA

Additional notes include:
- Multiple actions can be requested in one review if same property.
- Bulk associates perform AP check manually outside typical approval flow.
- Marriott/Four Seasons requests should be rejected and pushed back (templates noted in chain properties section; reference “Work a Partner Central access request (000036036)”).

Property in onboarding:
- Officially able to request new user creation if request from onboarding partner or NPT associate/MM.

**Checklist tables included for:**
- New user creation / access level update (HA availability, fraud/quarantine checks, SF verified, valid contact info, verification proof, multi-user/property logic, access level, duplicate search, EID, language)
- Deactivate user (verification proof, disable scenarios for non-bulk vs bulk)
- MFA reset (rules, exception for single generic HA, required proof, last 3 digits MFA)

(Nota: Il testo completo delle checklist è incluso nel DOCX; se vuoi che lo separi in una pagina dedicata “approver-checklist.md” per GitHub Pages, dimmelo.)

---

## Bonus 2: About the Property Administrator (Admin)

Articolo “Help and Support” di Partner Central.

### About the Property Administrator (Admin)
The Property Administrator user role (Admin) is the main point of contact for a property. To see who the Admin is, select your property name.

### What Admins can do
Admins manage key settings and user accounts. They can:
- [Add new users](https://apps.expediapartnercentral.com/lodging/help/help-article/property/property-administration/create-user-accounts-for-your-property?langId=1033), including other Admins
- [Edit or remove user roles and accounts](https://apps.expediapartnercentral.com/lodging/help/help-article/property/property-administration/change-security-access-levels-for-existing-user-accounts?langId=1033)
- [Manage email notification settings](https://apps.expediapartnercentral.com/lodging/help/help-article/property/property-administration/manage-email-notifications-for-your-partner-central-account?domain=HOTEL&langId=1033)
- [Update the legal entity name and property name](https://apps.expediapartnercentral.com/lodging/help/help-article/property/property-administration/update-your-legal-entity-and-property-name?langId=1033)
- [Change banking or payment details](https://apps.expediapartnercentral.com/lodging/help/help-article/property/property-administration/update-banking-information?langId=1033) for Expedia Collect (EC) invoices

### Admin responsibilities
Admins should regularly review and update user accounts to protect privacy and security. They also get an email whenever a user changes the email address linked to their account.
``
