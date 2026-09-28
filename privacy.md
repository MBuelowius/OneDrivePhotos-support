---
title: OneDrive Photos privacy policy
---

# OneDrive Photos privacy policy

Last updated: 28 September 2026.

OneDrive Photos is an independent macOS app. It uses Microsoft Authentication Library to sign in to the personal Microsoft account you choose and Microsoft Graph to access that account's OneDrive content. Microsoft handles sign-in and consent under its own terms.

## Data the app uses

- Your account identity and authentication state, to sign in and keep your session active.
- OneDrive file names, dates, sizes, media metadata, album membership, thumbnails, and original photo or video data needed to browse, view, export, or keep items downloaded.
- Files you explicitly import or paste for upload to a OneDrive destination you choose.

Browsing requests User.Read and Files.Read. Uploads and album changes ask for Files.ReadWrite when you enable those actions. The app does not run an independent server, advertising, analytics, subscriptions, or a licensing service. It does not send your media to us; media transfers for app functions use Microsoft Graph.

## Storage and deletion

Microsoft Authentication Library stores authentication state using the system credential store. The app stores library metadata, thumbnails, downloaded originals, and temporary exports in its local app container, separated by Microsoft account. Temporary exports are removed after their retention period.

Sign Out removes the session and clears the visible library, but does not erase locally stored files. While signed in, Settings → Remove Local Data deletes that account's app-managed metadata, thumbnails, downloaded originals, and temporary exports. It does not delete OneDrive files. You can also revoke the app's access through your Microsoft account's consent settings.

Earlier builds used a shared local cache. Those older cache files may remain in the app container and are not removed by the current account-specific Remove Local Data action. Do not put file paths, media, credentials, or account details in a public support issue. The [support page](support.html) explains how to request general help.

## This website

These pages are hosted by GitHub Pages. GitHub may log visitor IP addresses for security; see [GitHub's privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). The app itself does not send browsing activity to this site.

For questions about this policy, use the [public support issue tracker](https://github.com/MBuelowius/OneDrivePhotos-support/issues) without including personal data.
