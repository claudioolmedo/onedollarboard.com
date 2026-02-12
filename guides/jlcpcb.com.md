    
# Manufacturing Guide – JLCPCB

This guide shows how to manufacture the **One Dollar Board V1.004 R1** at JLCPCB in just a few minutes.

The process is simple:
1. Download the official manufacturing file
2. Upload it to JLCPCB
3. Confirm settings
4. Place your order

---

## Step 1 – Download the Official File

Download the latest manufacturing package (click to download):

👉 [**Download ZIP – Official JLCPCB Package**](https://github.com/claudioolmedo/onedollarboard.com/raw/main/download/OneDollarBoard.com.ODB.1.004_r1_jlcpcb.zip)

📁 [All files in `/download`](https://github.com/claudioolmedo/onedollarboard.com/tree/main/download)

After downloading:

• Extract the ZIP file  
• You will see:

- `OneDollarBoard_V1.004_R1_JLCPCB_BOM.xlsx`
- `OneDollarBoard_V1.004_R1_JLCPCB_CPL.xlsx`
- `OneDollarBoard.com.ODB.1.004_r1_jlcpcb.zip` (this is the file you should upload directly to the JLCPCB website – it already contains all the necessary Gerber files)

You only need the extracted files. Do not modify them.

---

## Step 2 – Go to JLCPCB

Open: [jlcpcb.com](https://jlcpcb.com)

Click:

**"Order Now"**

---

## Step 3 – Upload Gerber Files

1. Drag and drop the **Gerber folder** into JLCPCB
2. Wait for preview to load (takes a few seconds)
3. Confirm board looks correct

No changes required.

---

## Step 4 – Enable PCB Assembly

After Gerber upload:

1. Enable **"PCB Assembly"**
2. Select **Top Side Assembly Only**

(One Dollar Board V1 is single-side assembly – all SMD on top.)

---

## Step 5 – Upload BOM and CPL

Upload:

• `OneDollarBoard_V1.004_R1_JLCPCB_BOM.xlsx`  
• `OneDollarBoard_V1.004_R1_JLCPCB_CPL.xlsx`

JLCPCB will automatically match components.

Confirm:

• All parts are matched  
• No missing components  
• CH32V003 is correctly detected  
• LED polarity is correct  

---

## Step 6 – Confirm Order

Recommended basic settings:

• 2 Layers  
• 1.6mm thickness  
• Green solder mask (lowest cost)  
• HASL finish  
• 0603 components (default)  

Click **"Save to Cart"**

Place order.

---

## Manufacturing Time

The entire process takes:

🕒 ~5–10 minutes to upload and confirm  
📦 3–7 days production (depending on shipping)

---

## Important Notes

• Do not edit the BOM or CPL files  
• Do not rename files  
• Keep assembly on Top side only  
• Bottom side is copper/traces only  

---

## ⚠️ If You See This Error

Sometimes JLCPCB may show this message:

"J1, J2, JP1, JP2 designators don't exist in the BOM file."

✅ This is normal.  
Just click **"Continue"**.

JLCPCB only assembles **SMD components**.

- **J1, J2** — PCB connector footprints only. No components to buy. Ignore them.
- **JP1, JP2** — Headers soldered manually after you receive the board. Easy to solder and widely available.

---

## 🛠 If You Want to Assemble at Home

If you prefer to:
- Order only the PCB (no assembly)
- Use your own pick-and-place machine
- Or solder by hand

You can download the full LCSC component list here (click to download):

👉 [**Download LCSC BOM (XLSX)**](https://github.com/claudioolmedo/onedollarboard.com/raw/main/download/OneDollarBoard_V1.004_R1_LCSC_BOM.xlsx)

The PCB itself is very low cost.

You may also:
- Create a panel if you have experience
- Use manual pick-and-place
- Hand solder 0603 components

---

## 📐 Manufacturing in Other PCB Services

This guide is optimized for **JLCPCB**, but you can manufacture anywhere.

You can:

1. [Download the design files from GitHub](https://github.com/claudioolmedo/onedollarboard.com/tree/main/download)
2. Open them in **Autodesk Eagle (Fusion 360)**
3. Export Gerbers for any PCB manufacturer

Fusion 360 has a free version available.

---

## 🤝 Contribute

If you improve the board, adapt it, or manufacture it in your country:

Please consider leaving a comment or suggestion on GitHub.

Let’s awaken talent around the world.

---

## Version

Board: One Dollar Board V1.004 R1  
Designed in Austin, Texas  
Latest version always available at: [onedollarboard.com](https://onedollarboard.com)