this is vibecoded app builder built with base4. there will onnly be one release and it will be updated with each new version, you cannot use old versions as i cant figure that out yet ): 
it is a visual app builder and prototyping platform for designing, animating, and publishing interactive user interface screens with a layout engine loosely based on the Windows Fluent UI design system, thouigh it looks like shit, local-first file saving, and cloud collaboration features.
## Highlights

Cloud Sync & Cross-Platform Access: Open projects hosted in the cloud for editing from any device. Local drafts auto-backup and sync to your account when online.
Layout & Element Editing: Select multiple elements at once to modify common properties. Align elements with auto-spacing or snap-to guides. Create custom grids or snap elements to coordinates.
Fluent Design Engine: Acrylic blur effects, hover glows, and slide-out animations are baked into the engine. The default dark mode uses a `#1C1C1D` color scheme.
Interactive Prototyping: Preview your prototype with instant transitions between screens, back-button navigation, tooltip-style popovers, keyboard shortcuts, and screen name indicators.
Community & Template Sharing: Publish projects to the web or keep them private with unique ContainUL IDs for easy sharing. Search the community page for apps, view creator profiles, and fork public projects directly into your editor.
Template Store: Combine two or more elements into a single template to publish and save for later use.

 File Formats & Storage

Project files are saved as local `.tsp` files (or legacy `.abpj` files).
Embedded images are converted and stored as Base64-encoded data URLs to maintain fidelity when reloading the page or exporting the project.
## Changelog

 v2.5.0

A manual sync button was added to sync projects from the cloud or update the local editor.
Local drafts now upload to the cloud during sync.
Published apps can now be set to public or private directly from the editor without entering the preview mode.
The old Ctrl+Alt radial menu has been removed to make more space on the canvas.

 v2.4.5-v2.4.9

Options to configure the editor were added, including Snap to Grid, Grid Size, Show Coordinates, and default screen size.
Saving a draft to your homepage without publishing it as a standalone app became possible.
The ability to switch between accounts or add multiple profiles was implemented.
A duplicate screen button was added to the Screens panel.
The unresponsive UI bug when closing Project Settings was fixed.
Preview rendering performance was improved.

 v2.4.0-v2.4.4

Google account sign-ins and profile pages were added.
ContainUL ID search was implemented for faster project discovery.
The homepage redesign separated between user projects and community apps.
Project settings now have a fullscreen toggle and are organized into separate tabs, such as Home, Canvas, Properties, and Personalization.
A "Duplicate to Editor" option was added to community apps to fork them as new projects.
Guest Mode was introduced, allowing users to build apps without signing in and saving progress on their local machines only.

 v2.0.0-v2.3.0

The `.tsp` file format was introduced, which stores images as Base64-encoded data URLs.
The Windows 10/11 Fluent UI visual design language was implemented.
The ability to select multiple elements was added with a click-drag marquee or Ctrl+click.
Side panels (Properties and Screens) can now be collapsed to show more screen real estate.
Custom element glows, corner rounding, and shape-specific elements were added.

To design apps without an account, use Guest Mode. This will let you save your project as a local file on your machine. The export menu will also remember the last selected folder.

By signing in with a Google account, you'll be able to:

- backup your local drafts to the cloud
- publish your apps to the internet with a unique containul ID
- manage your public profile, including download analytics and community templates
