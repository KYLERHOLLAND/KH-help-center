# Troubleshooting & FAQ

Common questions and fixes for Kyler Holland digital products. Start here if something isn't working — most issues are download, install, or Premiere setup related.

!!!tip Not sure how to install your pack?
See [How KH products install](../getting-started/how-products-install.md) for step-by-step guides by file type (`.prfpset`, `.prproj`, MOGRT, LUT, and more).
!!!

---

## Downloads & account

==- I didn't get my confirmation email
Search your inbox for **Thanks for your purchase! Download your assets now** from `store+kylerholland@mail.sellfy.store`. Check **Spam**, **Promotions**, and **Updates** tabs.

You can also [sign in to your account](https://assets.kylerholland.com/u/signin/) with your purchase email → **Orders** → **View order** → **Download**.

Full walkthrough: [Downloads & updates](downloads-and-updates.md).
===

==- I lost my download link
Your order stays available in your account. [Sign in](https://assets.kylerholland.com/u/signin/) with the **same email used at checkout**, open **Orders**, click **View order**, then **Download**. See [Downloads & updates](downloads-and-updates.md).
===

==- I don't see my order when I sign in
- Confirm you're using the **exact email** from your purchase receipt (work vs. personal, typos, etc.).
- Free products still go through checkout — you need the email you entered there.
- If you used Apple Pay or a wallet, check which email that payment method is tied to.

Still missing? [Contact support](contact.md) with your receipt or payment confirmation.
===

==- The `.zip` won't download or says the link expired
Try a different browser or disable download managers/extensions. Sign in to [your account](https://assets.kylerholland.com/u/signin/) and download from **Orders** instead of the email link.

If the file is very large (for example the sound effects library), use a stable connection and enough free disk space before starting.
===

==- macOS blocked or quarantined my download
After extracting, if Premiere or Finder warns about the file:

1. Right-click the `.zip` or extracted folder → **Open** (macOS may ask you to confirm once).
2. For `.prfpset` / `.mogrt` files, import through Premiere as described in [How KH products install](../getting-started/how-products-install.md) — don't run unknown scripts from the archive.

Only use files from your official order email or account.
===

---

## Installation & import

==- I imported the `.zip` instead of extracting it first
Always **extract** the archive first. Import the actual file inside — `.prfpset`, `.prproj`, `.mogrt`, or `.cube` — not the `.zip` itself.
===

==- Where is the `.prfpset` file? My pack uses a Premiere project instead
Some packs (for example [Ultimate Effects Pack](../products/the-ultimate-effects-pack/index.md) and [Seamless Flow](../products/seamless-flow-transition-pack/index.md)) install by **dragging a `.prproj` file** into the Project panel — not via **Effects → Import Presets**.

Check your product's help page or [How KH products install](../getting-started/how-products-install.md) for the correct workflow.
===

==- My preset bin isn't showing after import
1. In the **Effects** panel, expand **Presets** and scroll — the pack may appear as a new folder.
2. Confirm you imported the **`.prfpset`** file, not the `.zip`.
3. **Restart Premiere Pro** after importing.
4. On some packs, right-click the `.prfpset` in Finder/Explorer and choose **Open With → Adobe Premiere Pro**.

Product-specific tips: [200+ Text Effects troubleshooting](../products/200-text-effects/index.md#troubleshooting).
===

==- MOGRT / Essential Graphics template won't install
1. Open **Window → Essential Graphics**.
2. Drag the `.mogrt` into the panel, or use **Install Motion Graphics Template** (plus icon).
3. Find it under **Local Templates**, then drag to the timeline.

If the **Edit** tab is empty, select the MOGRT clip on the timeline first. See [How KH products install — MOGRT](../getting-started/how-products-install.md#mogrt--motion-graphics-templates).
===

==- LUT isn't showing in Lumetri Color
1. Select the clip → open **Lumetri Color** → **Creative** tab → **Look** → **Browse**.
2. Navigate to the extracted folder and choose a **`.cube`** file.
3. Or import the included **`.prfpset`** and drag a LUT preset from **Effects → Presets**.

LUTs also work in DaVinci Resolve, Final Cut Pro, and other apps — import `.cube` files through that app's LUT browser.
===

==- "Media offline" on a transition or effect
Usually means linked files were moved or deleted.

- For project-based packs, keep the **Do not delete** folder next to the `.prproj` file — do not rename or relocate it alone.
- Re-import the project from the original extracted location if files were moved.
- Use **Link Media** in Premiere only if you moved the **entire** pack folder together.

Details: [Ultimate Effects Pack FAQ](../products/the-ultimate-effects-pack/index.md#frequently-asked-questions).
===

---

## Using products in Premiere Pro

==- Preset applied but nothing visible on the timeline
Many transition presets need a **cut between two clips** or trim handles on a single clip. Drag the preset to the **edit point** or the head/tail of a clip as shown in that product's tutorial.

Text presets need a **text or caption layer** selected — they won't work on empty video tracks.
===

==- Transition feels too fast, slow, or wrong at my frame rate
- Trim the preset on the timeline to lengthen or shorten it.
- Some presets behave differently on **24fps vs 30fps** timelines — preview with loop playback enabled.
- Remove and re-apply one preset at a time if effects look stacked or broken (**Remove Attributes** on the clip first).
===

==- Playback is stuttering or preview looks low quality
Press **Enter** to render the work area, or set the Program Monitor quality to **Full** after rendering. Transform and glitch presets often need a render pass for smooth preview.
===

==- Wrong Premiere version / project won't open
Many packs include folders for different versions (for example **CC 2020 Update 2** vs **CC 2018–2019**). Open the project folder that matches your Premiere build.

We recommend the latest Premiere Pro when possible. See [Downloads & updates — Product updates](downloads-and-updates.md#product-updates) and your product page for version notes.
===

==- Brevidy panel won't open or install
Brevidy installs through its own extension workflow — not as a `.prfpset` or `.zip` drag-in. Follow the install steps on the [Brevidy help page](../products/brevidy/index.md) and confirm you're on a supported Premiere version.

Contact [Brevidy/KH support](contact.md) with your order email and Premiere version if the panel still won't load.
===

---

## Purchases, refunds & licensing

==- Can I get a refund?
All digital sales are **final** once a product has been downloaded or accessed. See [Refunds & purchase policy](refunds-and-policy.md) for full terms.

If something isn't working, we're happy to help with install and troubleshooting — [contact support](https://assets.kylerholland.com/contact/) before assuming the product is incompatible.
===

==- Can I share a pack with a friend or client?
Products are licensed for **individual use**. Redistribution, resale, or sharing download files without permission is not allowed. See [Refunds & purchase policy](refunds-and-policy.md).
===

==- Standard vs commercial license (Ultimate Effects Pack)
**Standard** — personal and YouTube use. **Commercial** — paid client work or company projects. Choose the correct license at checkout. Details on the [Ultimate Effects Pack](../products/the-ultimate-effects-pack/index.md) page.
===

---

## Still stuck?

1. Open your product's help page from the [product list](../products/index.md) — each has install steps and an FAQ.
2. Watch the matching tutorial on the [Tutorial index](tutorial-index.md).
3. [Report a bug](report-a-bug.md) if the product is installed but misbehaving, or [contact support](https://assets.kylerholland.com/contact/) for account and download help. Include:
   - The email used at checkout
   - Product name
   - Premiere Pro version (or other app)
   - Screenshots of any error messages

We typically respond within 1–2 business days.
