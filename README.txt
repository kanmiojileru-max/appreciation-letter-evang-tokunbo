CCC IJESHATEDO PARISH IV — INTERACTIVE LETTER OF APPRECIATION

PACKAGE CONTENTS
- index.html: interactive letter with animated envelope reveal
- assets/ccc-ijeshatedo-stamp.png: transparent blue conventional rubber stamp

FIRST RECIPIENT
Name: Evang. Tokunbo
Role: Chairman, CCC Ijeshatedo Parish IV in Diaspora

LETTER CONTENT
The letter thanks recipients for financial contributions, support, prayers, encouragement and other efforts toward the church's growth. Its wording stays the same for each recipient; only the recipient's name and role are personalized.

PUBLISHING
1. Extract this ZIP on your computer.
2. Create a GitHub repository and upload index.html and the entire assets folder to the repository root.
3. Sign in to Vercel, choose Add New → Project, import the repository, and deploy it as a static site.
4. Open the provided .vercel.app link to test the animation and stamp.
5. Share the link with the recipient.

PERSONALIZING FOR ANOTHER RECIPIENT
In index.html, find the JavaScript object:
const recipient = {
 name: "Evang. Tokunbo",
 role: "Chairman, CCC Ijeshatedo Parish IV in Diaspora"
};
Change only the name and role values for each recipient. Keep the letter body unchanged. For separate personalized links, deploy a separate copy for each recipient or use a web developer to add a recipient-specific URL parameter.

PRINTING
The “Print / Save as PDF” button opens the browser print dialog. Choose “Save as PDF” to create a printable letter with the stamp affixed.

Before publishing, verify the church details and stamp spelling/legibility.

STAMP DISPLAY FIX
The stamp image is now embedded directly in index.html, so it does not rely on a separate asset path and should render after deployment even if the assets folder was not uploaded. For deployment, upload index.html and the assets folder as included in this ZIP. Replace the previous deployed files with these updated files and redeploy.
