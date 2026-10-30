[![Made with Slint](https://raw.githubusercontent.com/slint-ui/slint/master/logo/MadeWithSlint-logo-whitebg.png)](https://slint.dev)

Third-party licences: [licenses/](https://github.com/Toemsel/Foldaria/tree/main/licenses)

# Version 1.4.2

A small update that brings back missing network drives and tidies the Grid view.

## Bugfixes and Performance
- Mapped network drives that are not connected yet show in the sidebar again, without using up drive letters
- In Grid view, thumbnails no longer cover the bottom edge of the address bar at large paddings

# Version 1.4.1

A small update that fixes how windows are drawn on PCs with several monitors.

## Bugfixes and Performance
- Parts of a window no longer show what lies behind it on several monitors

# Version 1.4.0

Folders can now be shown as a list, a tree, tiles or a grid of thumbnails, and each folder remembers its view.
This version also brings more icon sets, see-through windows, and many fixes.

## New feature(s)
- Four views: List, Tree, Tiles and Grid in eight sizes; switch with Ctrl+wheel or Ctrl+Shift+1…4
- Every folder remembers its view, also after a restart
- Tree view: unfold folders in place; filter and sub-folder search work there too
- Grid view: folders show their newest pictures, texts and PDFs peeking out
- Six more icon sets, chosen from a drop-down with a live preview
- Window opacity: make every Foldaria window see-through
- "Ask before deleting": confirm every delete, and see which items skip the Recycle Bin

## Bugfixes and Performance
- The search popup looks right at display scaling above 100 %
- The window always opens on a visible screen, also after unplugging a monitor
- Arrow keys work right after Win+E brings Foldaria to the front
- Umlauts and other accented letters in zip file names show correctly
- Reordering sidebar items by drag works reliably
- The sidebar finds the open folder even among thousands of subfolders; "more…" lists the next ones
- Sub-folder search shows its results sorted once done, without jumping
- Less processor use while Foldaria sits idle
- Fixed several crashes found while testing this version ([#2](https://github.com/Toemsel/Foldaria/issues/2), [#3](https://github.com/Toemsel/Foldaria/issues/3), [#4](https://github.com/Toemsel/Foldaria/issues/4), [#5](https://github.com/Toemsel/Foldaria/issues/5))

# Version 1.3.0

A more colourful and polished release: a new theme picker, friendlier empty folders and one-click archive extraction.

## New feature(s)
- Pick themes from a grouped list with live preview, now with ten new themes
- Extract archives with one click from the pill above the file list
- Open the extracted folder from the finished message, here or in a new tab
- Empty folders and searches without results now show a friendly picture
- Hidden tabs have a clearer button

## Bugfixes and Performance
- Esc closes Settings again after using sliders, drop-downs or shortcut fields
- An unreachable network share no longer freezes the window
- The last item picked in global search comes first in every tab
- Renaming a file no longer selects the whole name by mistake
- Removed a "…" button from global search results that did nothing

## Other
- Slate and Steel themes replace Lemon and Olive

# Version 1.2.0

This version lets you open archives like folders and makes working with tabs easier.
Messages now appear as small notices in the corner, and the Microsoft Store version can replace Windows Explorer.

## New feature(s)
- Open zip, 7z, rar, tar, cab, iso, jar and more like folders, and extract them
- Shortcuts now open their target in the same tab
- Tabs keep a fixed width; tabs that don't fit wait in a searchable list
- Ctrl+Shift+T reopens the tab you closed last, right where it was
- Messages appear as notices in the corner that close by themselves, up to three at once
- Foldaria tells you when Windows' ransomware protection blocks a change, and how to allow it
- The Microsoft Store version can now replace Windows Explorer while Foldaria is running

## Bugfixes and Performance
- Replacing several files at once no longer leaves one "still in use"
- Files without an "open" action, such as ISO images, now run their default action
- A failed delete now says "could not be deleted" and gives a reason
- "Path not found" in the address bar is now translated

# Version 1.1.0

This version adds Quick Look previews, address bar suggestions and live folder updates. It also fixes several crashes and global search problems.

## New feature(s)
- Quick Look: press F3 to preview images, PDFs, Office documents, HTML, Markdown, SVG and text
- The address bar suggests folders and places as you type, including ones you visited before
- Folders update on their own when other programs add, change or remove files
- The active tab now flows smoothly into the toolbar
- Selected files can be dragged from anywhere in their row
- Recycled files now appear last in every search

## Bugfixes and Performance
- Global search no longer beeps while you type
- Global search now opens on the first double Ctrl after a cold start
- Quitting from the tray icon no longer crashes ([#1](https://github.com/Toemsel/Foldaria/issues/1))
- Dragging a tab out of the window no longer leaves it floating
- Network servers and shares that refuse access now ask for credentials
- Opening a folder and going back keeps your place in the list
- Context menus no longer close by themselves while a sub-menu is open
- Quick Look no longer shows stale or blank areas and no longer freezes with Office documents
- Esc closes the Settings pop-up again after changing an option
- Long paths in address bar suggestions no longer push the place tag out of view
- Inline copy progress bar no longer flickers at its right edge
- "Use as default for all folders" now applies to every folder

## Other
- Windows' security hardening: Git status column removed, safer archives, bounded stored files
- Settings now lists the licences of third-party components

# Version 1.0.0

The first public release of Foldaria: a fast, modern file manager for Windows with tabs, split panes and a system-wide search popup.

## New features
- Browse folders in tabs, split panes side by side, and drag tabs between windows.
- Sidebar with favourites, recent places, drives, network locations and cloud folders.
- Type to filter any folder instantly, including sub-folders, with fuzzy matching.
- Press Ctrl twice anywhere to search apps, files, folders and Windows settings.
- Navigation bar with breadcrumbs, address editing, suggestions and bookmarks.
- Copy, move, rename and delete with in-app progress; deletions go to the Recycle Bin.
- One context menu everywhere, with pins, search and other programs' entries.
- Columns per folder, sorting, and multi-select with check boxes.
- Free space on drives, sync status for cloud files, and network drive mapping.
- Open zip, 7z, rar and tar archives like folders.
- 15 themes, the Windows accent colour, rebindable shortcuts and icon sets.
- Available in 14 languages, following your Windows language.
- Optionally start with Windows and replace Windows Explorer, with a crash safeguard.
- Send crash reports to GitHub with one click, with personal data removed.
