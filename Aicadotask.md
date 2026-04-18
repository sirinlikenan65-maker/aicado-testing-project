# 📋 AICADO Task Main — Test Cases & Bug Report

---

## 📑 Sheet 1: Test Cases

| TC ID | Title | Precondition | Steps to Reproduce | Expected Result | Status | Priority |
|-------|-------|--------------|-------------------|-----------------|--------|----------|
| TC-1 | Verify login with valid credentials | https://run.aicado.ai/dashboard? | 1. Open the AICADO login page 2. Enter valid username 3. Enter valid password 4. Click on "Login" button | User is redirected to the dashboard. | ✅ Pass | High |
| TC-2 | Verify login with invalid password | https://run.aicado.ai/dashboard? | 1. Open login page 2. Enter valid username 3. Enter invalid password 4. Click "Login" | Error message "Invalid credentials" is displayed; login is not allowed. | ✅ Pass | High |
| TC-3 | Verify login with empty username and password fields | https://run.aicado.ai/dashboard? | 1. Open login page 2. Leave username field empty 3. Leave password field empty 4. Click "Login" | Validation messages appear under both fields, prompting user to enter required information. | ✅ Pass | High |
| TC-4 | Verify dashboard loads correctly after login | https://run.aicado.ai/dashboard? | 1. Log in to AICADO 2. Observe dashboard loading | All widgets, menus, and header elements appear without errors | ✅ Pass | High |
| TC-5 | Verify menu links navigation | https://run.aicado.ai/dashboard? | 1. On dashboard, click each menu link (e.g., Profile, Payments, Settings) | User is redirected to the corresponding page correctly | ✅ Pass | High |
| TC-6 | Verify Menu Links Navigation | https://run.aicado.ai/dashboard? | 1. Click each menu link 2. Observe page redirection | Each menu link navigates to the correct page | ✅ Pass | Medium |
| TC-7 | Verify Logout Functionality | https://run.aicado.ai/dashboard? | 1. Click "Logout" button 2. Observe redirection | User is redirected to login page and session ends | ✅ Pass | High |
| TC-8 | Verify Profile Update | https://run.aicado.ai/dashboard? | 1. Navigate to Profile page 2. Update user information 3. Click "Save" | Updated information is saved and displayed correctly | ✅ Pass | Medium |
| TC-9 | Verify Change Password Functionality | https://run.aicado.ai/dashboard? | 1. Navigate to Change Password 2. Enter old password, new password, confirm new password 3. Click "Save" | Password is updated successfully | ✅ Pass | Medium |
| TC-10 | Verify Dashboard Widgets Update | https://run.aicado.ai/dashboard? | 1. Trigger an action that updates data 2. Observe dashboard widgets | Widgets reflect updated data accurately | ✅ Pass | Medium |
| TC-11 | Verify Pagination Functionality | https://run.aicado.ai/dashboard? | 1. Navigate to list page 2. Click next/previous page buttons | Items of respective page are displayed correctly | ✅ Pass | High |
| TC-12 | Verify "Plan and Billing" Button Navigation | https://run.aicado.ai/dashboard? | 1. Locate the "Plan and Billing" button 2. Click the button | User is redirected to the Plan and Billing page; subscription plans and billing information displayed correctly | ✅ Pass | High |
| TC-13 | Create New AI Agent | https://run.aicado.ai/dashboard? | 1. Open the AI Agent section 2. Click "Create New Agent" 3. Fill in name, description, settings 4. Click "Save" or "Create" | New AI Agent is created successfully | ✅ Pass | High |
| TC-14 | Create New AI Agent and Change Background Color | https://run.aicado.ai/dashboard? | 1. Select Home section 2. Navigate to AI Agent section 3. Create new agent 4. Go to Styling section 5. Open background color panel 6. Choose a new color and click Save/Apply | New AI Agent is created; background color updates immediately | ✅ Pass | Medium |
| TC-15 | Change Title Color | https://run.aicado.ai/dashboard? | 1. Select Home section 2. Navigate to AI Agent section 3. Create new agent 4. Go to Styling section 5. Open title color panel 6. Choose a new color and click Save/Apply | New AI Agent is created; title color updates immediately | ✅ Pass | Medium |
| TC-16 | Upload Image to Avatar Section | https://run.aicado.ai/dashboard? | 1. Select Home section 2. Navigate to AI Agent section 3. Create new agent 4. Go to Avatar/Styling section 5. Click Upload Image 6. Select a valid image file 7. Click Save/Apply | New AI Agent is created; uploaded image appears correctly in Avatar section | ✅ Pass | Medium |
| TC-17 | Verify Text Input Display on Other Side | https://run.aicado.ai/dashboard? | 1. Select Home section 2. Navigate to AI Agent section 3. Create new agent 4. Open Styling Input Header section 5. Type a message 6. Press Send/Submit | The typed message appears correctly on the chat output area | ✅ Pass | High |
| TC-18 | Change AI Agent Name | https://run.aicado.ai/dashboard? | 1. Select Home section 2. Navigate to AI Agent section 3. Create or select an existing agent 4. Edit the agent's name 5. Click Save/Apply | AI Agent's name is updated successfully | ✅ Pass | Medium |
| TC-19 | Verify AI Agent Name Change Functionality | https://run.aicado.ai/dashboard? | 1. Go to Home section 2. Navigate to AI Agent section 3. Select an existing agent 4. Edit the agent's Name 5. Click Save/Apply 6. Go to another section where the agent name is displayed | The updated agent name should appear correctly in all sections/pages | ❌ Fail | Medium |
| TC-20 | Verify that user can enter text into the input field | https://run.aicado.ai/dashboard? | 1. Select the Home section 2. Navigate to AI Agent section 3. Select/create an agent 4. Locate the Input/Text field 5. Click on the input field 6. Try to type text using the keyboard | The user should be able to type text and the typed text should be visible | ❌ Fail | High |
| TC-21 | Verify that user can select and change the font size | https://run.aicado.ai/dashboard? | 1. Navigate to AI Agent > Styling > Text 2. Locate Font Size setting 3. Choose a different font size 4. Click Save/Apply | The selected font size should be applied accordingly | ✅ Pass | Medium |
| TC-22 | Verify that user can change the text color | https://run.aicado.ai/dashboard? | 1. Navigate to AI Agent > Styling > Text 2. Locate Text Color setting 3. Choose a different color 4. Click Save/Apply | The selected text color should be applied accordingly | ✅ Pass | Medium |
| TC-23 | Verify that user can change the font family | https://run.aicado.ai/dashboard? | 1. Navigate to AI Agent > Styling > Text 2. Locate Font Family setting 3. Choose a different font family 4. Click Save/Apply | The selected font family should be applied accordingly | ✅ Pass | Medium |
| TC-24 | Verify that user can change the input field background color | https://run.aicado.ai/dashboard? | 1. Navigate to AI Agent > Styling > Input 2. Locate Background Color setting 3. Choose a different color 4. Click Save/Apply | The selected background color should be applied to the input field | ✅ Pass | Medium |
| TC-25 | Verify that user can change the input field border color | https://run.aicado.ai/dashboard? | 1. Navigate to AI Agent > Styling > Input 2. Locate Border Color setting 3. Choose a different color 4. Click Save/Apply | The selected border color should be applied to the input field | ✅ Pass | Low |
| TC-26 | Verify file upload functionality | https://run.aicado.ai/dashboard? | 1. Select Home section 2. Navigate to AI Agent > Features 3. Click the File Upload button 4. Select a valid file 5. Click Upload/Submit | The file should upload successfully and appear in the list | ❌ Fail | High |
| TC-27 | Verify Features Section Functionality | https://run.aicado.ai/dashboard? | 1. Select Home section 2. Navigate to AI Agent > Features | All features should be visible and accessible | ✅ Pass | High |
| TC-28 | Verify that user can activate Voice Agent | https://run.aicado.ai/dashboard? | 1. Select Home section 2. Navigate to AI Agent > Features 3. Locate Voice Agent option 4. Toggle/activate the Voice Agent feature 5. Click Save/Apply if necessary | Voice Agent should be successfully activated | ❌ Fail | High |
| TC-29 | Verify that a Preset Message is saved successfully | https://run.aicado.ai/dashboard? | 1. Navigate to AI Agent > Features > Preset Messages 2. Enter a new message 3. Click Save 4. Verify the message appears in the list | The new preset message is saved successfully | ✅ Pass | High |
| TC-30 | Verify navigation to Tool section from AI Agent | https://run.aicado.ai/dashboard? | 1. Navigate to Home page 2. Click on AI Agent section 3. Locate and click on Tool section 4. Verify Tool section loads successfully | User can successfully navigate from Home → AI Agent → Tool | ✅ Pass | High |
| TC-31 | Verify Knowledge Base button functionality in Tool section | https://run.aicado.ai/dashboard? | 1. Navigate to Home > AI Agent > Tool 2. Locate the Knowledge Base button 3. Click on it 4. Verify the Knowledge Base page/modal opens | All content in the Knowledge Base is displayed and functional | ✅ Pass | High |
| TC-32 | Verify Analytics button functionality | https://run.aicado.ai/dashboard? | 1. Navigate to Home > AI Agent 2. Locate the Analytics button 3. Click on the Analytics button | All key elements in Analytics (charts, data, filters) are displayed and functional | ✅ Pass | High |
| TC-33 | Verify Reset Styling functionality in AI Agent page | https://run.aicado.ai/dashboard? | 1. Navigate to Home > AI Agent > Styling 2. Click on Reset Styling button | Reset Styling button is visible and clickable | ✅ Pass | High |
| TC-34 | Verify searching for a created AI Agent | https://run.aicado.ai/dashboard? | 1. Navigate to Home > AI Agent 2. Locate the Search field 3. Enter the name of the previously created AI Agent 4. Click Search or press Enter | User can select/view the AI Agent from the results | ✅ Pass | Medium |
| TC-35 | Verify Display Input Shadow functionality in AI Agent Styling | https://run.aicado.ai/dashboard? | 1. Navigate to Home > AI Agent > Styling 2. Locate Display Input Shadow option 3. Enable/disable the option 4. Observe the input fields for shadow effect | Display Input Shadow option is visible and clickable | ✅ Pass | Medium |
| TC-36 | Verify creating a new team | https://run.aicado.ai/dashboard? | 1. Navigate to Home page 2. Click on Select Your Team dropdown 3. Click on Create Team 4. Enter team details 5. Click Save/Create | New team is successfully created and appears in the list | ✅ Pass | High |
| TC-37 | Verify user can successfully submit a bug | https://run.aicado.ai/dashboard? | 1. Select the Domain button 2. Navigate to "Submit a Bug" section 3. Enter valid bug details 4. Click on "Submit" button | Bug is successfully submitted | ✅ Pass | High |
| TC-38 | Verify user can submit a bug after selecting Home and changing Team | https://run.aicado.ai/dashboard? | 1. Select Home from navigation 2. Change Team to the relevant team | Team is updated successfully | ✅ Pass | Medium |
| TC-38 | Verify user can delete a Team after selecting Home | https://run.aicado.ai/dashboard? | 1. Select Home from navigation 2. Select the Team to be deleted 3. Click Delete 4. Confirm the deletion | Team is successfully deleted | ✅ Pass | Medium |
| TC-39 | Verify Correct Display of Available Credits | https://run.aicado.ai/dashboard? | 1. Navigate to Dashboard or Billing/Account section 2. Locate the Available Credits field 3. Observe the displayed number | The system shows 250 credits accurately | ✅ Pass | High |
| TC-40 | Verify clicking "Add Credits" increases user credits | https://run.aicado.ai/dashboard? | 1. Navigate to Dashboard or Billing/Account 2. Click "Add Credits" button 3. Follow prompts to add credits 4. Observe the updated credit balance | Credit balance increases according to the added amount | ✅ Pass | High |
| TC-41 | Verify auto top-up automatically adds credits when balance falls below limit | https://run.aicado.ai/dashboard? | 1. Navigate to Plan and Billing 2. Update or verify Billing information 3. Enable/select Auto Top-Up option 4. Confirm changes | Billing update and Auto Top-Up selection are applied successfully | ✅ Pass | High |
| TC-42 | Verify user can add a new card and save it successfully via Stripe | https://run.aicado.ai/dashboard?tab=team | 1. Navigate to Payment/Billing section 2. Click Add New Card 3. Enter valid card details 4. Click Save/Add Card 5. Wait for confirmation from Stripe | New card is successfully saved via Stripe | ✅ Pass | High |
| TC-43 | Verify that card details are stored securely and encrypted | https://run.aicado.ai/dashboard?tab=team | 1. Navigate to Payment/Billing section 2. Identify a saved card 3. Inspect the backend storage 4. Verify how card details are stored | Full card numbers or CVV are not stored in plain text | ✅ Pass | High |
| TC-44 | Verify that Quota Reminder value is saved when "Save" is clicked | https://run.aicado.ai/dashboard? | 1. Navigate to Quota Reminder section 2. Enter a valid value (e.g., 50 credits) 3. Click Save 4. Refresh the page and return | The saved value persists after page refresh or navigation | ✅ Pass | High |
| TC-45 | Verify clicking "Publish" opens a new page | https://run.aicado.ai/dashboard? | 1. Navigate to the content section ready for publishing 2. Click the Publish button 3. Observe the application behavior | A new page is opened after clicking Publish | ✅ Pass | High |
| TC-46 | Verify "Choose an Option" button is visible and clickable | https://run.aicado.ai/dashboard? | 1. Navigate to Home page 2. Select the Agent section 3. Click on Choose an Option dropdown 4. Select Published from available options | Choose an Option dropdown is visible and clickable | ❌ Fail | High |
| TC-47 | Verify user can access and select a Display Options | https://run.aicado.ai/dashboard? | 1. Navigate to Home page 2. Select the Agent section 3. Click on Choose an Option dropdown 4. Select Published 5. Click Display Options | Display Options can be selected successfully | ✅ Pass | High |
| TC-48 | Verify user can access and click "Start with a Template" | https://run.aicado.ai/dashboard? | 1. Navigate to Home page 2. Click Start with a Template button | Start with a Template button is visible and clickable | ✅ Pass | Medium |

---

## 🐛 Sheet 2: Bug Report

### BUG-1 — AI Agent name is not updated across all sections

| Field | Details |
|-------|---------|
| **Title** | AI Agent name is not updated across all sections |
| **Priority** | Medium |
| **URL** | https://run.aicado.ai/dashboard?tab=Home |
| **Description** | Changing the AI Agent name in one section does not update it across other sections, causing inconsistency for users. |
| **Steps to Reproduce** | 1. Go to Home page 2. Open AI Agent section 3. Edit the AI Agent name 4. Save changes 5. Navigate to another section (e.g., Analytics or Dashboard) |
| **Actual Result** | AI Agent name updates in one section but does not reflect in other sections |
| **Expected Result** | AI Agent name should be updated consistently across all sections |
| **Attachment** | [View Attachment](https://drive.google.com/file/d/1okFFRGp9K9mKJVWMq95yBw-yfsLvgBYW/view?usp=drive_link) |

---

### BUG-2 — User cannot enter text into the input field

| Field | Details |
|-------|---------|
| **Title** | User cannot enter text into the input field |
| **Priority** | High |
| **URL** | https://run.aicado.ai/dashboard?tab=Home |
| **Description** | The input field does not allow the user to type any text. |
| **Steps to Reproduce** | 1. Go to Home page 2. Open AI Agent section 3. Locate the input field 4. Try to type any text into the input field |
| **Actual Result** | User cannot enter any text into the AI Agent input field |
| **Expected Result** | User should be able to type text into the AI Agent input field |
| **Attachment** | [View Attachment](https://drive.google.com/file/d/1-vTqSavXG6U0QNHZMM2C3gCYIx1SPhSW/view?usp=drive_link) |

---

### BUG-3 — File cannot be uploaded in the file upload field

| Field | Details |
|-------|---------|
| **Title** | File cannot be uploaded in the file upload field |
| **Priority** | High |
| **URL** | https://run.aicado.ai/dashboard?tab=Home |
| **Description** | The file upload field does not allow the user to upload any file, preventing successful submission. |
| **Steps to Reproduce** | 1. Go to Home page 2. Open AI Agent section 3. Navigate to Features section 4. Scroll to Image Upload section 5. Click "Choose File" / "Browse" 6. Select an image file from the system 7. Click "Upload" button |
| **Actual Result** | Upload fails |
| **Expected Result** | Image should be uploaded and displayed in the section without errors |
| **Attachment** | [View Attachment](https://drive.google.com/file/d/1UjHhCSnmjZ2ZTx4b-ItC1_PDw58Iryr6/view?usp=drive_link) |

---

### BUG-4 — Voice Agent cannot be activated

| Field | Details |
|-------|---------|
| **Title** | Voice Agent cannot be activated |
| **Priority** | High |
| **URL** | https://run.aicado.ai/dashboard?tab=Home |
| **Description** | The Voice Agent cannot be activated when the user clicks the "Activate" button in the Features section. |
| **Steps to Reproduce** | 1. Go to Home page 2. Open AI Agent section 3. Navigate to Features section 4. Scroll to Voice Agent feature 5. Click the "Activate" button |
| **Actual Result** | Voice Agent remains inactive; activation fails |
| **Expected Result** | Voice Agent should activate successfully, allowing the user to use voice features |
| **Attachment** | [View Attachment](https://drive.google.com/file/d/1bNhUIKYLeYx60Vm5FHA6VWzEW97Nc1S1/view?usp=drive_link) |

---

### BUG-5 — "Choose an Option" button is visible but dropdown does not open

| Field | Details |
|-------|---------|
| **Title** | "Choose an Option" button is visible but dropdown does not open |
| **Priority** | High |
| **URL** | https://run.aicado.ai/dashboard?tab=Home |
| **Description** | The user can see and click the button, but the dropdown menu does not open, preventing any selection. |
| **Steps to Reproduce** | 1. Go to Home page 2. Click on "Selection" 3. Select the desired AI Agent 4. Navigate to the "Published" section 5. Click on "Connect Your Domain" link/button |
| **Actual Result** | Page fails to open |
| **Expected Result** | "Connect Your Domain" page should open and be accessible for the user |
| **Attachment** | [View Attachment](https://drive.google.com/file/d/1QXULN0SjEni40ejTDdYLKmYHNs5JmhyZ/view?usp=drive_link) |
