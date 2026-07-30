# SnapFlow Privacy Policy for Google Chrome

- **Effective date:** July 30, 2026
- **Contact:** [cchhll0210@gmail.com](mailto:cchhll0210@gmail.com)

## English

### 1. Overview

SnapFlow is a screenshot and web-capture extension for Google Chrome. It lets users capture a full webpage, the currently visible browser area, or a user-selected area, and manage the resulting screenshots locally on their device.

SnapFlow does not require an account and does not upload screenshots or page information to a SnapFlow server. SnapFlow offers optional, consent-based anonymous product analytics through Mixpanel. Analytics is disabled by default.

### 2. Single purpose

SnapFlow's single purpose is to let users capture webpages and manage the resulting screenshots locally on their device.

### 3. Data SnapFlow accesses and processes

SnapFlow processes the following data only when needed to provide its user-facing screenshot and localization features:

| Data | Why it is processed | Where it is stored |
| --- | --- | --- |
| Screenshot image and thumbnail | To create, preview, copy, download, and delete a screenshot requested by the user | Locally in the extension's IndexedDB |
| Current page URL and title | To identify the source of a screenshot in local history | Locally in the extension's IndexedDB |
| Capture time and capture type | To sort and identify screenshots in local history | Locally in the extension's IndexedDB |
| Image width, height, file type, and file size | To create and manage the local screenshot record | Locally in the extension's IndexedDB |
| Selected interface language | To keep the user's language choice | Locally in `chrome.storage.local` |
| Temporary capture-task information, including a job ID, capture type, tab/window identifiers, page URL/title, task status, and timestamps | To coordinate an active screenshot operation | Temporarily in `chrome.storage.session` and removed after the task is completed or cleared |
| Analytics consent and a random pseudonymous installation ID | To remember whether the user opted in and associate anonymous analytics data from the same installation | Locally in `chrome.storage.local`; the identifier is sent to Mixpanel only after opt-in |
| Limited product analytics data | To understand aggregate feature usage and improve reliability | Sent to Mixpanel only after opt-in |

SnapFlow also reads the browser's interface language locally to choose an initial interface language when the user has not made a manual selection.

Webpage content may appear inside a screenshot. Depending on the page selected by the user, that image may contain personal or sensitive information. SnapFlow processes that content only to perform the screenshot action explicitly requested by the user.

### 4. How data is obtained

Screenshot content, the active page URL, and the page title are accessed only after the user clicks SnapFlow and requests a screenshot. SnapFlow does not continuously monitor browsing activity and does not collect browsing history in the background.

The selected language is saved only when the user changes the language setting. Temporary task data is created only while coordinating a requested capture.

If the user explicitly enables “Help improve SnapFlow” in Settings and grants the optional Mixpanel host permission, SnapFlow sends only limited product-usage and reliability analytics. The transmitted data is restricted to coarse feature-usage categories, performance ranges, standardized diagnostic codes, interface configuration, extension and browser information, and random identifiers.

Analytics never includes screenshots, thumbnails, URLs, domains, page titles, webpage content, clipboard content, downloaded files, user input, or raw error messages.

### 5. How data is used

SnapFlow uses locally processed data only to:

- capture a full page, visible area, or selected area;
- create a thumbnail and local screenshot record;
- show the screenshot history and preview;
- let the user copy, download, or delete screenshots;
- display the interface in the selected language;
- provide task status and completion feedback; and
- if the user opts in, measure aggregate feature usage and capture reliability.

SnapFlow does not use screenshot content, URLs, page titles, or other local screenshot records for advertising, profiling, analytics, credit decisions, or any purpose unrelated to improving the extension's screenshot features.

### 6. Storage, retention, and transmission

- Screenshot images, thumbnails, and their metadata remain in the extension's local IndexedDB until the user deletes them, clears the extension's data, or uninstalls the extension.
- The language preference remains in local extension storage until the user changes it, clears extension data, or uninstalls the extension.
- Temporary capture-task information is cleared after the task is completed, cancelled, fails, or is identified as stale. Session storage is also managed by the browser.
- SnapFlow V1.0 does not transmit these records to the developer or to a SnapFlow server.
- SnapFlow does not use Chrome Storage Sync for screenshot data.
- When the user explicitly chooses Copy or Download, the requested image is written to the device clipboard or download location through browser-provided features. This is initiated and controlled by the user and is not a transfer to SnapFlow or the developer.
- Analytics consent and the random installation ID remain in local storage until the user disables analytics, clears extension data, or uninstalls SnapFlow.
- When analytics is enabled, limited product analytics data is sent over HTTPS to Mixpanel's US ingestion endpoint. SnapFlow sends the Mixpanel request with IP enrichment disabled (`ip=0`). Mixpanel may still process network information such as an IP address for delivery, security, or abuse prevention under its own policies.
- Disabling analytics stops future analytics transmission, removes the local installation ID, and removes SnapFlow's optional access to the Mixpanel endpoint. Data already received by Mixpanel may remain according to the Mixpanel project settings and retention policy.

### 7. Sharing and sale of data

SnapFlow does not sell or rent user data. It never sends screenshot content, thumbnails, page URLs, domains, page titles, webpage content, clipboard content, or downloaded images to Mixpanel or any other third party.

After the user opts in, Mixpanel acts as a product-analytics service provider and receives only the limited anonymous analytics data described above. SnapFlow integrates with Mixpanel through its HTTPS Track API and does not include Mixpanel Autocapture, Session Replay, advertising, social tracking, user profiles, or third-party cloud-storage integration. See the [Mixpanel Privacy Policy](https://mixpanel.com/legal/privacy-policy/).

The developer and other people cannot remotely view the user's locally stored screenshots through SnapFlow.

### 8. Permissions

SnapFlow requests only the permissions required for its current features:

- **`activeTab`** — temporarily accesses the active tab after a user action to capture the requested page and read its URL and title.
- **`scripting`** — injects packaged SnapFlow capture code into the active page when the user requests full-page or selected-area capture.
- **`offscreen`** — performs local Canvas, Blob, cropping, stitching, thumbnail, PNG encoding, and IndexedDB operations in an invisible extension document.
- **`sidePanel`** — displays the user's local screenshot history, previews, and screenshot actions.
- **`storage`** — stores the language preference and temporary capture-task state.
- **Optional `https://api.mixpanel.com/*` host access** — requested only when the user enables anonymous analytics and used only to send the limited analytics data described in this policy. It is not required for screenshots.

SnapFlow does not request persistent access to all websites and does not declare broad required host permissions.

### 9. Remote code and external services

SnapFlow does not download or execute remote code. Its executable code is packaged with the extension.

SnapFlow does not call AI services, OCR services, advertising networks, developer-operated APIs, or cloud storage. If the user opts in, SnapFlow calls only Mixpanel's Track API for the analytics described in this policy. No executable code is loaded from Mixpanel.

### 10. User controls and deletion

Users control when a capture occurs and which page or selected area is captured.

Users can:

- preview locally stored screenshots;
- copy or download a screenshot;
- delete individual screenshots and their associated local metadata from Screenshot History;
- change the interface language in Settings;
- enable or disable anonymous analytics at any time in Settings; and
- remove all SnapFlow extension data by clearing the extension's local data through browser settings or uninstalling SnapFlow.

Analytics is off until the user actively enables it. If optional host access is denied, no analytics data is sent. Because SnapFlow does not receive the local screenshot data, the developer cannot remotely retrieve, modify, or delete it on the user's behalf.

### 11. Security

SnapFlow minimizes permissions and keeps screenshot processing within the browser extension environment. It does not transmit screenshot data to a developer-controlled server. Optional analytics data is transmitted to Mixpanel over HTTPS only after consent.

Users should protect access to their device and browser profile. No method of local storage can be guaranteed to be completely secure against someone who already has access to the user's device or browser profile.

### 12. Chrome Web Store Limited Use

SnapFlow's use of information received from Chrome APIs complies with the Chrome Web Store User Data Policy, including the Limited Use requirements. Data accessed through Chrome APIs is used only to provide or improve SnapFlow's single-purpose, user-facing screenshot features.

### 13. Changes to this policy

This policy may be updated when SnapFlow's features or data practices change. The effective date at the top of this page will be revised when an update is published.

If a future version introduces materially different data handling, SnapFlow will provide the disclosures and consent required by applicable store policies and law before that processing begins.

### 14. Contact

For questions about this privacy policy or SnapFlow's data practices, contact:

[cchhll0210@gmail.com](mailto:cchhll0210@gmail.com)