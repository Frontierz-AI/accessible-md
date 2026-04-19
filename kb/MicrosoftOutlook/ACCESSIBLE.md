# Microsoft Outlook for Windows: Accessibility Reference

Reference covering keyboard shortcuts, screen reader behavior, interface layout, settings paths, and step-by-step procedures for using Classic Outlook and New Outlook for Windows with assistive technology.

Covers: JAWS, NVDA, Narrator, Windows Magnifier, high contrast themes, Immersive Reader, and tools for people with low vision.

---

## 1. Identifying Your Outlook Version

There are two distinct desktop applications for Windows:

- **New Outlook for Windows**: Web-technology-based app. The title bar says "Outlook (new)" or just "Outlook" on newer Windows 11 devices. It has a left rail with icon buttons (Mail, Calendar, People, To Do, Copilot) and a single-line ribbon. There is no File tab.
- **Classic Outlook for Windows**: Traditional Win32 desktop application included with Microsoft 365 / Office. The title bar says "Outlook" or "Microsoft Outlook." It has a multi-tab ribbon (File, Home, Send/Receive, Folder, View) and a Navigation Pane with a folder tree on the left.

### Keyboard-Based Identification

| Method | What to do | Classic result | New Outlook result |
|--------|-----------|----------------|--------------------|
| Title bar | Press Alt+Space, listen to window title | "Microsoft Outlook" or "Outlook" | "Outlook (new)" or includes "(new)" |
| File menu | Press Alt+F | Opens Backstage with Options, Account Settings, Open & Export | Opens a different File tab with Print, Account management |
| Ctrl+Y | Press Ctrl+Y | Opens "Go to Folder" dialog | Opens/focuses the Folder Pane |
| Settings | Press Alt+F, T | Opens Outlook Options dialog | May not work; New Outlook uses a gear icon / Settings pane |
| Toggle | Look for toggle in title bar area | "Try the new Outlook" toggle present | "Switch to classic Outlook" toggle present |

### Visual Identification

- **New Outlook**: Left rail with vertical icon buttons, single-line ribbon, no File tab, gear icon for settings (may be behind a three-dot menu), "New mail" button at top left.
- **Classic Outlook**: Multi-row ribbon with File/Home/Send-Receive/Folder/View tabs, folder tree with indentation, status bar at bottom with zoom slider, "New Email" button in ribbon.

---

## 2. Interface Layout

### New Outlook Regions

Navigable with F6 (forward) and Shift+F6 (backward):

1. **Left rail / App bar**: Vertical strip of icon buttons. Contains Mail, Calendar, People, To Do, Copilot, and other pinned apps.
2. **Folder pane**: Folder list for the current account (Inbox, Drafts, Sent Items, etc.). Access with Ctrl+Y, then type folder name letters to quick-jump.
3. **Message list**: Navigate with Up/Down arrow keys.
4. **Reading pane** (if enabled): Shows the content of the selected message. Can be positioned right, bottom, or hidden.
5. **Ribbon**: Single-line toolbar. Press Alt to show key tips.
6. **Search bar**: Ctrl+E.
7. **Settings**: Gear icon. Tab/Shift+Tab to find "Settings button," then Enter.

**F6 cycle order**: Left rail > Folder pane > Message list > Reading pane (if visible) > Ribbon.

### Classic Outlook Regions

Navigable with F6 (forward) and Shift+F6 (backward). Ctrl+F6 also cycles through regions.

1. **Navigation Pane (Folder Pane)**: Folder tree and navigation buttons (Mail, Calendar, People, Tasks). Toggle with Alt+F1.
2. **Message list**: Navigate with Up/Down arrow keys.
3. **Reading pane**: Configurable right/bottom/off. View > Reading Pane > Off to hide.
4. **Ribbon**: Tabs: File, Home, Send/Receive, Folder, View. Press Alt or F10 for key tips.
5. **To-Do Bar** (optional): Toggle via View > To-Do Bar.
6. **Status bar**: Connection status, item count, zoom slider.

**F6 cycle order**: Folder pane > Message list > Reading pane > To-Do Bar (if visible) > Ribbon.

### View Switching

| View | Classic | New Outlook |
|------|---------|-------------|
| Mail | Ctrl+1 | Ctrl+1 |
| Calendar | Ctrl+2 | Ctrl+2 |
| People/Contacts | Ctrl+3 | Ctrl+4 |
| Tasks | Ctrl+4 | — |
| Notes | Ctrl+5 | — |
| Copilot | — | Ctrl+3 |

---

## 3. Recommended Accessibility Settings

### New Outlook

**Turn off reading pane:**
1. Tab or Shift+Tab until "Settings button," press Enter.
2. Tab to "Accounts tab," Down arrow to "Mail tab," press Enter.
3. Tab to "Layout tab."
4. Tab until "Where do you want the reading pane to appear?"
5. Down arrow to "Hide reading pane." It auto-selects.
6. Tab to "Save button," press Enter.
7. Esc to close Settings.

**Turn off conversation view:**
1. Same path: Settings > Mail > Layout.
2. Tab until "How do you want your messages list organized?"
3. Navigate to "Show each message separately." It auto-selects.
4. Tab to "Save," press Enter. Esc to close.

With reading pane off, pressing Enter on a message opens it in its own view, and JAWS/NVDA will automatically start reading the message body. Conversation view groups messages and can be confusing for linear navigation.

### Classic Outlook

**Turn off reading pane:** Press Alt > V > R, P > choose "Off."

**Turn off conversation view:** Press Alt > V > C, V to uncheck "Show as Conversations."

**Disable message grouping:** In the View tab, go to the Arrangement group. Messages should be sorted by Date without grouping headers.

---

## 4. Keyboard Shortcuts

### Common to Both Versions

| Action | Shortcut | Notes |
|--------|----------|-------|
| New message | Ctrl+N | |
| Reply | Ctrl+R | |
| Reply All | Ctrl+Shift+R | |
| Forward | Ctrl+F | |
| Send message | Ctrl+Enter | Classic also uses Alt+S. Both work in Classic; only Ctrl+Enter in New. |
| Delete message | Delete | |
| Permanently delete | Shift+Delete | |
| Mark as read | Ctrl+Q | |
| Mark as unread | Ctrl+U | In message list: marks unread. In compose: underlines text. |
| Search | Ctrl+E | |
| Go to Mail | Ctrl+1 | |
| Go to Calendar | Ctrl+2 | |
| Copy / Cut / Paste | Ctrl+C / X / V | |
| Undo | Ctrl+Z | |
| Bold | Ctrl+B | |
| Italic | Ctrl+I | |
| Insert hyperlink | Ctrl+K | |
| Move between regions | F6 / Shift+F6 | |
| Close dialog/pane | Esc | |
| Open selected message | Enter or Shift+Enter | |
| Next/previous message | Down/Up arrow | |
| Left/Center/Right align | Ctrl+L / Ctrl+E / Ctrl+R | Compose only. |
| Spell check | F7 | Compose window. |
| Send/Receive All | F9 | |

### Version-Specific Shortcuts

| Action | Shortcut | Version |
|--------|----------|---------|
| Go to folder pane | Ctrl+Y | New |
| Go to folder (picker dialog) | Ctrl+Y | Classic |
| Quick-jump folder by name | Type letters after Ctrl+Y | New |
| Show keyboard shortcuts list | ? | New |
| Flag/unflag message | Insert key | New |
| Open message in new window | Shift+Enter | New |
| Next/previous message | Ctrl+> / Ctrl+< | New |
| Go to Copilot | Ctrl+3 | New |
| Go to People | Ctrl+4 | New |
| Switch to Contacts/People | Ctrl+3 | Classic |
| Switch to Tasks | Ctrl+4 | Classic |
| Switch to Notes | Ctrl+5 | Classic |
| Toggle Folder Pane | Alt+F1 | Classic |
| Go to Backstage (File) | Alt+F | Classic |
| Find in message | Ctrl+F (in open message; in list, forwards) | Classic |
| Advanced Find | Ctrl+Shift+F | Classic |
| New appointment | Ctrl+Shift+A | Classic |
| New meeting request | Ctrl+Shift+Q | Classic |
| New contact | Ctrl+Shift+C | Classic |
| New task | Ctrl+Shift+K | Classic |
| Go to a date (Calendar) | Ctrl+G | Classic |
| Open Address Book | Ctrl+Shift+B | Classic |
| Switch to Inbox | Ctrl+Shift+I | Classic |
| Switch to Outbox | Ctrl+Shift+O | Classic |
| Move message to folder | Ctrl+Shift+V | Classic |
| Check names in address field | Ctrl+K | Classic |
| Options dialog | Alt+F, T | Classic |
| "Tell me" search box | Alt+Q | Classic |
| Calendar: Day view | Ctrl+Alt+1 (New) / Alt+1 (Classic) | Both |
| Calendar: Week view | Ctrl+Alt+2 (New) / Alt+- (Classic) | Both |
| Calendar: Month view | Ctrl+Alt+4 (New) / Alt+= (Classic) | Both |
| Calendar: Go to today | Alt+Shift+Y or Home (New) / Ctrl+T (Classic) | Both |
| Calendar: Next/previous day | Ctrl+Alt+Right/Left arrows | New |

### Ribbon Navigation

**New Outlook:** Press Alt to show key tips. Use arrow keys to move between items. Tab cycles through commands. H activates Home tab, V activates View tab.

**Classic Outlook:** Press Alt or F10 to activate the ribbon and show key tips. Press the letter shown on a tab (H=Home, S=Send/Receive, O=Folder, V=View). Arrow keys navigate within ribbon groups. Ctrl+F1 toggles ribbon collapse/expand.

**Classic Outlook compose window** has its own separate ribbon with tabs: Message, Insert, Options, Format Text, Review. Key tips differ from the main window.

---

## 5. Screen Reader Behavior

### Narrator

- Narrator key: Caps Lock or Insert (configurable).
- Read current item: Narrator+Tab.
- Read from current position: Narrator+Ctrl+R or Narrator+Down arrow.
- Stop reading: Ctrl.
- Scan mode: Narrator+Space to toggle. In scan mode, Up/Down moves by line, H jumps to next heading.
- Narrator does NOT auto-read the message body when opening an email in New Outlook. The user must press Narrator+Ctrl+R.
- In New Outlook, pressing F6 to reach the left rail: Narrator announces "Left rail appbar navigation," followed by the current view.

### JAWS

- JAWS key: Insert.
- Read current line: Insert+Up arrow.
- Say all (continuous reading): Insert+Down arrow.
- Stop reading: Ctrl.
- Virtual cursor / forms mode: JAWS auto-switches. Press Insert+Z to toggle.
- JAWS auto-reads the message body when opening an email in New Outlook.
- JAWS has custom Outlook scripting that announces message flags, importance, and attachment presence.
- Re-read from beginning: Ctrl+Home, then Insert+Down arrow.
- Help: Insert+Space, then F1 opens FSCompanion.
- List links: Insert+F7. List headings: Insert+F6.
- In New Outlook filters, JAWS uses Ctrl+Down arrow (not just Down arrow) to browse filter options. JAWS may not announce filter submenu option names, but they work when selected.
- In Classic Outlook: Insert+Shift+W switches to browser mode for reading HTML email content.

### NVDA

- NVDA key: Insert or Caps Lock (configurable).
- Read current line: NVDA+Up arrow.
- Say all (continuous reading): NVDA+Down arrow.
- Stop reading: Ctrl.
- Browse mode vs Focus mode: NVDA+Space to toggle. In focus mode, keystrokes go to the app; in browse mode, NVDA intercepts for navigation.
- NVDA auto-reads the message body when opening an email in New Outlook.
- When in a text field, NVDA may need to be switched to focus mode manually. Press NVDA+Space if typing does not work.
- Re-read: Ctrl+Home, then NVDA+Down arrow.
- Elements list: NVDA+F7 (links, headings, landmarks).
- A community-maintained NVDA add-on for Outlook adds extra features (column reading, quick folder access).

### Screen Reader Differences Summary

| Behavior | Narrator | JAWS | NVDA |
|----------|----------|------|------|
| Auto-reads message on open (New Outlook) | No (manual: Narrator+Ctrl+R) | Yes | Yes |
| Virtual cursor in email body | Scan mode (Narrator+Space) | Auto-switch | Browse mode (NVDA+Space) |
| Filter navigation in New Outlook | Down arrow | Ctrl+Down arrow | Down arrow |
| Filter submenu announcement | Yes | No (still works) | Yes |
| Ribbon key tip activation | Alt | Alt | Alt |
| Quick help | Narrator+F1 | Insert+F1 | NVDA+F1 |
| List links | Scan mode, Tab | Insert+F7 | NVDA+F7 |
| List headings | Scan mode, H | Insert+F6 | NVDA+F7 (headings tab) |
| Focus mode for typing | Automatic | Automatic | May need manual toggle (NVDA+Space) |

---

## 6. Task-by-Task Procedures

### 6.1 Reading an Email

**New Outlook (reading pane off):**
1. Press F6 until "Message list" is announced.
2. Up/Down arrows to select the desired message. The screen reader announces sender, subject, date, and flags/status.
3. Press Enter to open the message.
4. JAWS and NVDA auto-read the body. With Narrator, press Narrator+Ctrl+R.
5. Press Esc to close and return to the message list.

**Classic Outlook (reading pane off):**
1. F6 to move focus to the message list.
2. Up/Down arrows to select a message.
3. Press Enter to open in a new window.
4. Screen Reader key+Down arrow for continuous reading.
5. Alt+F4 or Esc to close the message window.

**With reading pane on (both versions):**
Selecting a message in the list automatically loads it in the reading pane. Press F6 to move focus to the reading pane. Tab stops in the reading pane include interactive elements (reply buttons, links) that interrupt linear reading. Turning the reading pane off is recommended for people who use screen readers.

### 6.2 Composing and Sending an Email

**New Outlook:**
1. Ctrl+N. Focus lands on the To field.
2. Type recipient name or address. Suggestions appear; use Down arrow to browse, Enter to select.
3. Tab to Cc field. To show Bcc: Tab to the Bcc link near the To/Cc fields and press Enter.
4. Tab to "Add a subject" field, type subject.
5. Tab to "Message body," type message.
6. Ctrl+Enter to send.

**Classic Outlook:**
1. Ctrl+N (or Ctrl+Shift+M from any area). Focus lands on the To field.
2. Type recipient. Ctrl+K to check/resolve names from the address book.
3. Tab to Cc, Bcc (if not visible: press Alt+P or use the Options tab in the compose ribbon), Subject, and Body.
4. Alt+S or Ctrl+Enter to send.

### 6.3 Replying and Forwarding

- Reply: Ctrl+R
- Reply All: Ctrl+Shift+R
- Forward: Ctrl+F

Note: In Classic Outlook with a message open in its own window, Ctrl+F opens Find instead of Forward. Use the ribbon for Forward in that context.

Focus goes to the message body (reply) or To field (forward).

### 6.4 Adding Attachments

**New Outlook:**
1. While composing, press F6 to move to the ribbon.
2. Right arrow to "Insert tab."
3. Tab to "Attach file," press Enter.
4. Choose "OneDrive" or "Browse this computer."
5. Navigate with Tab and arrow keys to select the file, press Enter.

**Classic Outlook:**
1. While composing, press Alt, N, A, F (Insert tab > Attach File).
2. Browse with Tab and arrow keys, select file, press Enter.
3. Alternative: Alt+H, A, F from the Home tab.

### 6.5 Managing Received Attachments

**New Outlook:**
1. Open the email with Enter.
2. Tab to the attachment.
3. Tab to "More actions," press Space.
4. Choose "Download" (save locally) or "Save to OneDrive."
5. For all attachments: "Download all" or "Save all files to OneDrive."

**Classic Outlook:**
1. Open the email.
2. Tab to the attachment area.
3. Use the dropdown arrow next to the attachment name.
4. Choose to save, preview, or open.
5. To save all: ribbon or context menu "Save All Attachments."

**Removing an attachment from a draft:**
- New Outlook: Open the draft, move to the attachment, open its dropdown, choose "Remove attachment."
- Classic Outlook: Navigate to the attachment, press Shift+F10 (context menu), choose "Remove."

**Blocked attachments:** Outlook blocks certain risky file types (.exe, .bat, etc.). Workarounds: upload to OneDrive and share a link, compress into a .zip, or rename the extension.

**Large attachments:** If a file exceeds the size limit, upload to OneDrive or SharePoint and send a sharing link.

### 6.6 Managing Folders

**New Outlook:**
- Ctrl+Y moves focus to the folder pane. Type the first letters of the folder name to jump to it.
- Left/Right arrows collapse/expand folder sections.
- Enter opens the selected folder.

**Classic Outlook:**
- Ctrl+Y opens a "Go to Folder" dialog. Type the folder name and press Enter.
- Ctrl+Shift+V opens "Move to Folder" dialog for the selected message.
- In the Folder Pane (Alt+F1 to toggle), use Up/Down arrows to navigate, Right/Left to expand/collapse.

### 6.7 Searching

1. Ctrl+E to activate search.
2. Type search terms.
3. Down arrow to browse results. Enter to open a result.
4. To exit search — New Outlook: F6 to "Mail toggle," then Shift+Tab to "Exit search," Enter. Classic: Esc.

### 6.8 Calendar

**Opening Calendar:** Ctrl+2 (both versions).

**New Outlook Calendar:**
- New event: Ctrl+N.
- Switch views: Ctrl+Alt+1 (day), Ctrl+Alt+2 (week), Ctrl+Alt+4 (month).
- Navigate days/weeks: Ctrl+Alt+Left/Right arrows.
- Go to today: Alt+Shift+Y or Home.
- Browse events: Tab to move between events. Enter to open.
- Edit event details, then Tab to "Send" (meetings) or "Save" (appointments).

**Classic Outlook Calendar:**
- New appointment: Ctrl+Shift+A (opens full appointment window).
- New meeting: Ctrl+Shift+Q.
- Ctrl+N in Calendar view also creates a new appointment.
- Go to specific date: Ctrl+G.
- Go to today: Ctrl+T.
- Switch views: Alt+1 (day), Alt+2 (two days), Alt+- (week), Alt+= (month).

### Classic Outlook Calendar Grid Navigation

The calendar grid has multiple focus zones. Users can get stuck cycling through toolbar buttons instead of reaching time slots.

1. Press Ctrl+2 to enter Calendar view. Focus may land on the Date Navigator (mini calendar) or the ribbon.
2. Press F6 to cycle between regions: Date Navigator > Calendar grid > Ribbon > Navigation pane. The target is the Calendar grid.
3. Once inside the Calendar grid (JAWS announces a time slot like "10:00 AM" or an appointment title):
   - **Up/Down arrows**: Move between 30-minute time slots within the current day.
   - **Left/Right arrows**: Move to the same time slot on the previous/next day.
   - **Tab**: Jump to the next appointment (skips empty slots). Shift+Tab goes to the previous.
   - **Enter on an empty time slot**: Opens a quick inline appointment form (subject only). Tab moves to nearby existing appointments, which can be confusing. Using Ctrl+Shift+A instead opens the full appointment form.
   - **Enter on an existing appointment**: Opens the appointment detail window.
   - **Esc**: Closes the appointment window and returns to the calendar grid.
4. If stuck cycling through buttons (Back/Forward day view, Change view): press F6 until an actual time or appointment is announced.
5. Ctrl+T returns to today from anywhere in the calendar.

**Recommended approach for creating appointments with a screen reader:** Use Ctrl+Shift+A (or Ctrl+N in Calendar view) instead of the inline form. The full appointment window has fields: Subject > Start Date > Start Time > End Date > End Time > All Day checkbox > Location > Body. Tab moves linearly through them.

To convert an appointment to a meeting, press Ctrl+Shift+Q. This adds Required and Optional attendee fields.

**Joining a meeting (New Outlook):**
1. In Calendar, Tab to the meeting event, Enter to open.
2. Tab to "Join" button, Enter. Opens Teams.
3. Tab to adjust audio/video settings, then Shift+Tab to "Join now," Enter.

### 6.9 Meeting Creation with Optional Attendees

**New Outlook:**
1. Ctrl+N in Calendar view.
2. Fill in the title/subject.
3. Tab to the "Invite required attendees" field. Type names or addresses.
4. Below the required attendees field, there is an "Add optional attendees" link. It may not be visible by default. Tab past the required field to find it and activate it.
5. Type optional attendee names.
6. Fill in date, time, location, body.
7. Ctrl+Enter or Tab to Send.

**Classic Outlook:**
1. Ctrl+Shift+Q to create a new meeting request.
2. The window has: To (required attendees) > Subject > Location > Start/End times > Body.
3. To add optional attendees: Tab to the "To..." button and press Enter to open the Select Attendees dialog. Choose Required, Optional, or Resources for each attendee.
4. Alternative: press Alt+Q and type "optional" to search for the option.

### 6.10 Contacts / People

**New Outlook:** Ctrl+4 for People view. Ctrl+N to create. Ctrl+L for contact list. Shift+E to edit. Ctrl+E to search. Down/Up arrows to navigate.

**Classic Outlook:** Ctrl+3 for People. Ctrl+Shift+C for new contact. Ctrl+Shift+B for Address Book. Enter to open. Alt+F4 to close.

### 6.11 Signatures

**Classic Outlook:**
1. Alt+F, T, M (File > Options > Mail).
2. Alt+N, Enter to open Signatures and Stationery dialog.
3. Alt+N, Enter to create a new signature. Type name, Enter.
4. Alt+T then Tab to "Edit signature" area. Type the signature text.
5. Tab to "OK," Enter. Tab to "OK" again, Enter.

Insert manually in compose: Alt+N, A, S. Down arrow to pick, Enter.

Set default: In the Signatures dialog, Alt+M for "New messages" dropdown, Alt+F for "Replies/Forwards" dropdown.

**New Outlook:** Settings > Mail > Compose and reply > signature editing.

### 6.12 Rules

**New Outlook:**
1. Select a message. Press Enter to open it.
2. F6 until "Ribbon tabs." Press H for Home tab.
3. Press R, L to open Rules menu. Enter on "Create rule."
4. Select destination folder, Tab to "OK," Enter.

**Classic Outlook:** Alt, H, R, R (Create Rule). For advanced rules: Alt, H, R, M (Manage Rules & Alerts).

### 6.13 Sweep (New Outlook Only)

1. Select a message from the sender.
2. F6 to ribbon, H for Home tab, then S, P for Sweep.
3. Down arrow to select the sweep rule.
4. Tab to destination folder dropdown, pick folder.
5. Enter to confirm, Tab to "OK," Enter.

### 6.14 Flagging, Pinning, Snoozing (New Outlook)

- **Flag:** F6 > H > U. Down arrow to pick flag option, Enter.
- **Pin:** F6 > H > Y.
- **Snooze:** F6 > H > S, Z. Down arrow to pick time.
- **Archive:** Press Backspace on selected message.
- **Quick flag:** Press Insert key on the selected message.

### 6.15 Spell Check

Press F7 while composing to run the spell and grammar checker. This works in both Classic and New Outlook.

**Classic Outlook compose ribbon path:** The compose window has its own ribbon (tabs: Message, Insert, Options, Format Text, Review). Press Alt to see key tips. Alt, V, Q, G also opens spell check. The Review tab is NOT accessed with "R" in the compose window (that key tip is for Reply in the main window). F7 is the safest approach.

**New Outlook:** F7 works. The Editor can also be found in the Options area of the compose toolbar.

**Auto spell check before sending (Classic):** File > Options > Mail > "Always check spelling before sending."

### 6.16 Copilot

**Classic Outlook — Draft with Copilot:**
1. Ctrl+N to create new message.
2. Ctrl+F10 to show ribbon shortcuts.
3. C, P for Copilot menu, then D for "Draft with Copilot." Or Alt+I directly.
4. Type prompt, Tab to "Generate," Enter.
5. Tab to "Keep" to insert, or refine.

**Classic Outlook — Coaching:** Ctrl+F10 > C, P, C. Reviews tone, clarity, sentiment.

**Classic Outlook — Summarize:** Open an email. Shift+Tab to "Summarize" button, Enter.

**New Outlook:** Copilot is accessed via the Copilot view (Ctrl+3) or through ribbon commands in compose mode.

### 6.17 Dictation

- Win+H activates Windows dictation system-wide.
- Classic Outlook compose: Home tab > Dictate button.
- New Outlook compose: Dictate button in the ribbon.

### 6.18 Settings

**New Outlook — How to Access:**
- **Primary:** Gear/cog icon in the title bar area, to the right, near the profile picture.
- **Alternative:** If the gear icon is not visible (display configuration, magnification, or UI updates), look for a three-dot menu (...) near the profile icon. "Settings" is one of the menu options.
- **Keyboard:** Tab or Shift+Tab until the screen reader announces "Settings button" or "Settings gear." Press Enter.
- **Search within Settings:** There is a "Search settings" field at the top of the Settings dialog. Type keywords (e.g., "read," "signature," "notifications") to jump to the relevant setting.

**New Outlook Settings structure:**
1. Tab through top-level tabs: Accounts, General, Mail, Calendar, etc.
2. Down arrow within a tab to find subtabs. Enter to select.
3. Tab to navigate individual settings within a subtab.
4. Save, then Esc to close.

**Key settings locations (New Outlook):**

| Setting | Path |
|---------|------|
| Layout (reading pane, conversation view) | Settings > Mail > Layout |
| Mark as read behavior | Settings > Mail > **Message handling** (not Layout) |
| Notifications | Settings > General > Notifications |
| Signatures | Settings > Mail > Compose and reply |
| Calendar options | Settings > Calendar |
| Dark mode / themes | Settings > General > Appearance |

**Mark as read options (New Outlook):** "Mark displayed items as read when popped out or the selection changes" / "Mark items as read after being displayed for X seconds" / "Don't automatically mark items as read" / "Always keep items unread unless I explicitly mark them as read."

**Classic Outlook Settings:** Alt+F, T opens the Options dialog (File > Options). Categories: General, Mail, Calendar, Groups, People, Tasks, Search, Language, Accessibility, Advanced, Customize Ribbon, Quick Access Toolbar, Add-ins, Trust Center. Navigate with Down/Up arrows in the left panel, Tab to settings on the right.

**Mark as read (Classic):** File > Options > Mail > Reading Pane button > "Mark items as read when viewed in the Reading Pane" and delay setting.

---

## 7. Visual Appearance

### Dark Mode

- **New Outlook:** Settings > General > Appearance > "Dark" radio button > Save.
- **Classic Outlook:** File > Options > General > Office Theme > "Dark Gray" or "Black." Or File > Office Account > Office Theme dropdown.
- **Windows system-wide:** Settings > Personalization > Colors > Dark.

### High Contrast Themes

Windows Contrast Themes (Settings > Accessibility > Contrast themes, or Win+U) apply globally, including to Outlook. Options: Aquatic, Desert, Night Sky, Dusk.

Contrast themes are independent of screen readers or accessibility modes. They can be combined with Magnifier, Outlook Dark Mode, or display scaling without activating any screen reader.

### Zoom and Magnification

- **Windows Magnifier:** Win+Plus to zoom in, Win+Minus to zoom out, Win+Esc to exit. Views: Full screen (Win+Ctrl+F), Lens (Win+Ctrl+L), Docked (Win+Ctrl+D).
- **Display scaling:** Settings > System > Display > Scale (e.g., 125%, 150%).
- **Classic Outlook zoom:** Zoom slider in the status bar. Ctrl+Mouse wheel in the reading pane. In compose: View > Zoom.
- **New Outlook zoom:** Ctrl+Plus/Minus.
- **Font size in compose:** Ctrl+Shift+P or the font size dropdown in the ribbon.
- **Message list density (New Outlook):** Settings > Mail > Layout > Message list spacing (Spacious, Medium, Compact).

### Immersive Reader

Available in both versions for reading emails. Open a message, go to the View tab in the ribbon, select Immersive Reader.

Features:
- Text read aloud with word-by-word highlighting
- Adjustable font size, spacing, and font choice
- Line focus (1, 3, or 5 lines at a time)
- Syllable highlighting
- Parts of speech highlighting (nouns, verbs, adjectives)

---

## 8. Common Problems and Troubleshooting

### Screen Reader Not Reading Message Content
- Check that the reading pane is off and messages are opened with Enter.
- JAWS/NVDA not reading: Ctrl+Home, then Screen Reader key+Down arrow.
- Narrator: Narrator+Ctrl+R.
- HTML-heavy emails in Classic Outlook with JAWS: Insert+Shift+W to switch to browser view.

### Getting Lost in the Interface
- Press Esc repeatedly to close open panes/dialogs.
- Press F6 to cycle through regions.
- Ctrl+1 to return to Mail view.
- Ctrl+E to open search.

### Pop-up Dialogs Blocking Access
Common pop-ups that trap focus: "Get started with Copilot" prompt, license activation dialogs, feedback requests, migration prompts ("Try the new Outlook"), "What's new" announcements.

1. Press Esc first. This dismisses most pop-ups.
2. If Esc does not work, Tab to find a Close, Dismiss, or "Not now" button, then Enter.
3. Alt+F4 as a last resort.
4. After dismissing, press F6 to cycle back to the working region.

### NVDA Focus Mode Issues
If the user is typing but nothing appears, NVDA may be in browse mode. Press NVDA+Space to switch to focus mode. This is common in the compose window body.

### New Outlook Missing Features
Features that may be missing or work differently in New Outlook: custom keyboard shortcut assignment, some advanced rules, certain COM add-ins, offline access limitations. Classic Outlook remains available for these.

---

## 9. Text Formatting and Accessible Composition

### Accessibility Checker

**Classic Outlook:** In the compose window, press Alt+R, A, 1, A (or Review tab > Check Accessibility). The pane shows errors, warnings, and tips. Use Shift+Tab to results, Down arrow to browse issues, Space to expand.

**New Outlook:** Look for "Check Accessibility" in the Options or Review area of the compose ribbon.

**Auto-check (Classic):** File > Options > Accessibility > "Keep the Accessibility Checker running while I work."

### Inserting Hyperlinks

Ctrl+K opens the Insert Hyperlink dialog in both versions. Enter URL and display text.

Quick method: type a URL and press Space or Enter. Outlook auto-creates the link.

Use descriptive link text (e.g., "Microsoft Support page") rather than raw URLs.

### Inserting Images with Alt Text

**Classic Outlook:** Alt+N, P, 2, D to browse for an image file. To add alt text: move focus to the image, press Shift+F10 (context menu), choose alt text option, type description.

**New Outlook:** Use the Insert menu for picture options. Alt text can be added via the image context menu.

### Accessible Formatting Best Practices

- Use headings (Heading 1, 2, 3) for structure.
- Use bulleted or numbered lists for grouped information.
- Use descriptive hyperlink text.
- Choose sans-serif fonts (Arial, Calibri, Segoe UI) at 11pt or larger.
- Use strong contrast between text and background. Prefer "Automatic" font color.
- Avoid all-caps, excessive italics, and decorative backgrounds.
- Tables should be simple with a header row. Add alt text via Table Properties. Avoid nested tables.

---

## 10. Additional Features

### Switching Between Versions

**Classic to New:** Toggle at the top right of the window, labeled "Try the new Outlook." With a screen reader: Ctrl+F6 until "Command, Try the new Outlook," then Enter.

**New to Classic:** Toggle at the top right, or open "Outlook (classic)" from the Start menu.

New Windows 11 devices may only ship with New Outlook. Classic Outlook requires a Microsoft 365 subscription.

### Focused Inbox

Both versions support Focused Inbox, splitting mail into Focused and Other tabs. Tab to the Focused/Other control, Enter to switch. Move messages between tabs with Shift+F10 > "Move to Focused" or "Move to Other."

Turn off: New Outlook — Settings > Mail > Layout. Classic — View > Show Focused Inbox.

### Read Aloud

Classic Outlook has a built-in Read Aloud feature (separate from screen readers):

1. Enable: File > Options > Accessibility > "Show Read Aloud."
2. Open a message, then select Read Aloud from the Home or Message tab.
3. Controls: Ctrl+Alt+Space to start, Ctrl+Space to play/pause, Ctrl+Left/Right arrow to skip paragraphs.

### Syncing Mail

Press F9 to send/receive (both versions). New Outlook: View > Sync. Classic: Send/Receive tab.

If mail is not updating automatically in Classic: File > Options > Advanced > Send and Receive > check that "Include this group in send/receive (F9)" is selected.

### Account Type Limitations

**New Outlook supports:** Microsoft 365 work/school accounts, personal Microsoft accounts (Outlook.com, Hotmail, Live), Gmail, Yahoo, iCloud via IMAP (limited).

**New Outlook does NOT support:** On-premises Exchange, hybrid Exchange, sovereign cloud Exchange, POP protocols.

**Classic Outlook** supports all of the above, plus POP3, full IMAP, and on-premises Exchange.

---

*Frontierz in partnership with Microsoft*
*April 2026*
