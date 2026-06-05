# Sign-in & devices

The Ultimate Effects Pack **plugin** unlocks with your **Sellfy purchase email** — not a license key. This page covers sign-in, device limits, and fixes for common access issues.

**New subscriber?** Start with the [Subscriptions overview](index.md).

---

## Sign in (magic link)

1. Open Premiere Pro and launch the **Ultimate Effects Pack** plugin panel.
2. Enter the **email you used at Sellfy checkout**.
3. Click **Email me a sign-in link**.
4. On **the same computer**, check your inbox and click the link in the email.
5. The browser confirms you're signed in — switch back to Premiere. The panel unlocks within a few seconds.

!!!tip Open the email on this computer
The sign-in flow ties to your machine. Request the link from the plugin, then open that email on the same computer where Premiere is running.
!!!

### Sign-in link details

| Detail | Value |
|--------|-------|
| Link lifetime | **20 minutes** |
| Uses per link | **One time** |
| If it expires | Request a new link from the plugin |

You do **not** need to copy or paste a license key anywhere.

---

## Device activations

Your subscription (or lifetime purchase) includes **2 active devices**.

- Each computer gets a unique device ID the first time you sign in.
- Signing in on a **third** computer **replaces the oldest** device automatically.
- There is no manual "deactivate" button in the plugin — signing in on a new machine handles rotation.

**Footer note in the plugin:** *"Your license includes 2 device activations. New activations automatically replace the oldest device."*

### Switching computers

1. Install the plugin on the new machine.
2. Sign in with your Sellfy email.
3. If you already have two devices active, the least recently used slot is freed for the new computer.

### "This computer is not activated"

Sign in again with your purchase email on that computer. If you recently signed in elsewhere and exceeded two devices, signing in here will register this machine and drop the oldest one.

---

## Subscription status checks

The plugin re-validates your license with the server about every **12 hours**.

| Status | Plugin behavior |
|--------|-----------------|
| **Active subscription** | Unlocked |
| **Canceled, still in paid period** | Unlocked + **Subscription canceled** banner with days left |
| **Period ended** | Locked — renew on Sellfy and sign in again |

Canceled but still in your paid period? See [Cancel your subscription](cancel-your-subscription.md).

---

## Troubleshooting sign-in

### "No active purchase found for this email"

- Use the **exact email** from your Sellfy receipt (check work vs. personal, typos, `+` aliases).
- Confirm your subscription is **active** or still inside the **paid period** after canceling.
- New purchase? Allow a minute for webhooks to register, then try again.

### I never got the sign-in email

- Check **Spam**, **Promotions**, and **Updates**.
- Search for mail from the Ultimate Effects Pack sign-in sender.
- Request a new link from the plugin (previous links expire after 20 minutes).

### The link worked in the browser but Premiere is still locked

- Wait a few seconds — the plugin polls for completion automatically.
- Make sure Premiere stayed open while you clicked the link.
- Click **Cancel** on the waiting screen and request a fresh link.

### Plugin locked after I canceled

If you're **still inside your paid period**, wait for the next status check (up to ~12 hours) or restart Premiere and sign in again. You should see the **days left** banner, not a hard lock.

If your **period has ended**, renew on [Sellfy](https://kylerholland.sellfy.store/) and sign in again.

### Wrong email at checkout

Licenses are tied to the **checkout email**. If you purchased under the wrong address, [contact support](../support/contact.md) with your receipt — we can't move licenses to a new email without verification.

---

## Re-sign-in after updates

If we ship a plugin update that changes device tracking, you may need to **sign in one more time** so your current computer registers. Use the same email-and-link flow as your first sign-in.

---

## Related

- [Subscriptions overview](index.md)
- [Cancel your subscription](cancel-your-subscription.md)
- [Downloads & updates](../support/downloads-and-updates.md)
- [Contact support](../support/contact.md)
