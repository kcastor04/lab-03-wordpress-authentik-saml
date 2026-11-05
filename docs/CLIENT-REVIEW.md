# Client Review: Lab 03 Sample

**Repository folder:** `lab-03-wordpress-authentik-saml`
**Status:** Client review (not published)
**Purpose:** First sample of the nine-lab portfolio. Approval of this sample sets the style, structure and evidence approach for the remaining eight labs and the portfolio landing page.

This file is for internal review only. It can be removed before publication.

**How to review:** open [`preview.html`](preview.html) in any web browser. No installation or internet connection is needed: all images and styling are embedded. It is a local approximation of the README, not an exact GitHub rendering, and `README.md` remains the deliverable. Use *Expand all screenshots* at the top of the preview to open every supporting-screenshot section at once. Like this file, `preview.html` is a review aid and should be removed before publication.

---

## 1. Decisions required before publication

| # | Decision | Options / notes | Client answer |
|---|---|---|---|
| 1 | **Approve style and content** | Approve as is, or list changes (tone, length, section depth, badge set, heading emojis, diagram style). | |
| 2 | **Hands-on completion** | Did the portfolio owner personally complete this lab? If yes, can you supply your own screenshots (e.g. the WordPress Users page showing the JIT-created account, and the provider configuration)? | |
| 3 | **Permission to republish source material** | The lab text and all 27 screenshots come from *Hands-On IAM Labs – Lab 3* by Andrew, All Things Identity. Please confirm you have permission to republish them publicly, or tell us to replace them with your own screenshots. | |
| 4 | **GitHub owner** | GitHub username or organization that will own the repository. | |
| 5 | **Repository name** | Proposed: `lab-03-wordpress-authentik-saml`. Confirm or provide an alternative. | |
| 6 | **Repository visibility** | Public or private. Nothing will be created or pushed until this is confirmed. | |

---

## 2. How the answers change the README

- **If hands-on completion is confirmed with your own evidence:** the evidence-scope note in the README and the "source-demonstrated" wording will be updated to first-person, execution-based wording. The status badge will change from *Client review* to a completion status, and your screenshots will replace or supplement the guide's.
- **If completion is confirmed without your own evidence:** the guide screenshots stay, the attribution stays, and the wording can say the lab was completed while still noting that the screenshots are the guide's examples.
- **If completion is not confirmed:** the current wording stays as is. It describes the lab and its expected results without claiming personal execution.
- **If republishing permission is not available:** guide screenshots will be removed. The README will rely on the custom diagrams and configuration tables until your own screenshots are supplied.

---

## 3. Optional confirmations

These items are not blockers, but answers would make the README more specific:

- Did you complete the guide's **optional** steps (group-based access control, custom attribute mapping preview)? They are currently documented as optional and not claimed.
- Should the README mention the dependency labs (Lab 0 environment, Lab 2 MFA) as links once those repositories exist?
- Is there a preferred author name or profile link for the footer?

---

## 4. Evidence and safety decisions already applied

- All screenshots are attributed to All Things Identity, and the README states they are example screenshots from the training guide.
- **Excluded:** Figure 3.45 (TOTP enrollment QR code, an MFA secret) and Figure 3.37 (password-set dialog).
- **No redaction was needed** in the selected screenshots. Environment addresses already appear as `SERVER_IP`, `WP_PORT` and `AUTHENTIK_PORT` placeholders in the source, and the example identities use the reserved `example.com` domain. The certificate shown in Figure 3.30 is a public signing certificate, not a secret.
- Version-dependent plugin endpoints are shown as examples from plugin v6.2.0, with the guide's instruction to read them from the installed plugin.
- At the client's request, the architecture and workflow diagrams are **editable Mermaid diagrams** written as text in `README.md`. GitHub draws them directly; editing the `mermaid` code block changes the diagram. Only the banner remains an image.
- The full screenshot-to-source mapping (file, PDF page, figure, caption, cropping, redaction) is in [`evidence-manifest.json`](evidence-manifest.json).

---

## 5. Source gaps noted

- The guide does not describe a specific organization or business scenario. The README frames the lab around the general pattern the guide teaches and invents no organizational details.
- The guide states that MFA applies during the SSO sign-in, but the only screenshot of it is the excluded QR enrollment screen. The README therefore states this in text only.
- The guide provides no metrics, timings or measured outcomes, so none are reported.
