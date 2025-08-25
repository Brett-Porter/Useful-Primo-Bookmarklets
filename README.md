# Alma/Primo Debugging Bookmarklets

These bookmarklets are designed to help you with common debugging tasks in Alma and Primo. To use them, create a new bookmark in your browser and paste the JavaScript code for the desired tool into the URL field.

### CTO (Central Translation Override)

**Description:** This bookmarklet appends the `&displayCTO=true` parameter to the current URL. When activated, it reveals the translation codes on the page, helping you identify the specific **Central Translation Override (CTO)** key for any given text.

### PNX (Primo Normalized XML)

**Description:** Adds `&showPnx=true` to the URL, displaying the raw **PNX** record for the item you're viewing. This is crucial for troubleshooting and understanding how data is indexed in Primo.

### Show Record ID

**Description:** This tool is designed to display the record ID directly beneath each search result on a Primo page. It also adds links to view the **source record** (in the Alma MD Editor) and the **PNX** for that specific item.

### Label Codes

**Description:** This bookmarklet iterates through all the `translate` attributes on the page. It sets the `title` attribute for each element to its `translate` value, so when you hover your mouse over an item, a tooltip appears with the corresponding **label code**. This is very helpful when debugging interface translations.

### Show JS for PrimoVE

**Description:** Quickly navigates to the `custom.js` file for your current Primo VE view. The bookmarklet extracts the **vid** (view ID) from the URL and constructs the correct path to the JavaScript file, allowing you to view or inspect the **custom code** for that specific instance.
