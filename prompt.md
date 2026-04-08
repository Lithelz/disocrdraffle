Create a simple web-based tool that generates formatted Discord raffle announcements for Pokémon TCG product raffles. The tool should have a clean form interface where users can input raffle details and get a formatted output they can copy and paste into Discord.
Required Input Fields:

Title (text input) - e.g., "ASCENDED HEROES ETB"
Total Spots (number input) - e.g., 30
Price Per Spot (number input with $ symbol) - e.g., 5
Remaining Spots (number input) - auto-calculates as spots are claimed
Payment Options (checkboxes with custom text fields):

Zelle
Cash App
Venmo
Apple Pay
Other (custom)


Bonus Deals (dynamic list - add/remove):

"Buy X get Y EXTRA" format
e.g., "Buy 3 get 1 EXTRA 🎫"


Raffle Tag (optional text) - e.g., "@Raffle"
Claimed Spots (dynamic list - add/remove):

Username (with @ prefix)
Number of spots (e.g., "3+1" for 3 purchased + 1 bonus)



Output Format:
Generate a Discord-formatted message using this exact structure:
**[TITLE]**

WINNER: LAST NAME STANDING ON WHEEL

🍀🍀

[Total]🎫 at $[Price]/ea

**[Remaining]/[Total] 🎫 REMAINING**

💰 **PAYMENT OPTIONS:**
🟩 Zelle : 
🟦 cash app : 
🟡 Venmo : 
(Payment due after filled)

🍀🍀 [Optional @Raffle tag]

🎫 **BONUS DEALS:** ➡️ [List each bonus deal with arrow]

**BONUS 🎫 ARE EXTRA 🎫 ON THE WHEEL AND NOT A REDUCTION FROM ORIGINAL [Total]**

**CLAIMED 🎫:**
✅ @Username [spots]
✅ @Username [spots]
[continue list...]
Features Needed:

Live Preview - Show the formatted output as user types
Copy Button - One-click copy to clipboard
Save/Load Templates - Save common raffle setups
Claimed Spots Calculator - Auto-update remaining spots as claimed spots are added
Emoji Support - Include: 🎫 🍀 💰 🟩 🟦 🟡 ✅ ➡️
Mobile Responsive - Works on phone browsers
Local Storage - Save form data between sessions

Technical Requirements:

Build as a single HTML file with embedded CSS/JavaScript (no dependencies)
Can run completely offline/locally
Clean, simple UI with good spacing
Use standard Discord text formatting (bold with **text**)
All data processing happens client-side only

