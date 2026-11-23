# Original Source Export and Synchronization Plan
_Status: not configured._

## 1. Export the original ChatGPT Site
Open **Sites** in ChatGPT, select the **Knights of Dawn** site and use its editing/Codex workflow to **export the complete source code**. Save its original components, assets, any embedded or linked data, dependency manifests and deployment settings. Do not include private keys, runtime secrets or unrelated personal data.

**Do not use the 21 November offline recovery ZIP as a substitute for the original source**: its README identifies that HTML as a reconstruction.

## 2. Import into this GitHub repository
Import and review source as a commit or pull request. Check fidelity against the current live site: menus, sections, text, images, character gallery, search, maps, interactive views and mobile layout. Preserve originals. Then reconcile site canon with [CANON_AND_DECISIONS.md](CANON_AND_DECISIONS.md).

## 3. Choose a reliable update direction
**Recommended: GitHub as the primary source repository.** Edit the checked-out source in ChatGPT's Codex/Work coding flow, commit every approved change to GitHub, review it, and publish the corresponding Site version. This is an editorial workflow, not automatic bidirectional replication.

If the exact source is compatible with **GitHub Pages**, configure GitHub Actions/Pages so that **GitHub commits automatically deploy the GitHub-hosted copy**. This is GitHub → GitHub Pages only.

## 4. ChatGPT Site → GitHub automation
Not available by merely connecting GitHub to ChatGPT. To mirror updates without manual commits, an **authenticated trigger or export integration** from the Site's source environment to GitHub would be required. No such automatic linkage has been configured or verified for this site. A scheduled fetch of a public web page would copy rendered output, not the original Site's project code or stored assets.

Until a supported change-trigger integration is verified, **every approved Site edit must also be committed to GitHub in the same editing workflow**. Do not claim automatic synchronization.
