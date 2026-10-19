# Foldaria Privacy Policy

Effective date: 19 October 2026

This policy explains how Foldaria, a file manager for Windows by Thomas Christof, handles your data. It applies to every
edition of Foldaria: the Microsoft Store version and the standalone download.

## In short

- Foldaria does not collect, transmit, sell or share any personal data.
- Foldaria has no account, no telemetry, no analytics, no advertising and no tracking.
- Foldaria makes no network connection of its own. Everything it stores stays on your PC.

## Data stored on your PC

Foldaria saves the following in your Windows profile, in the folder `%APPDATA%\Foldaria`. Only you and programs running
under your Windows account can read it.

- **Settings and layout:** your preferences, theme, sidebar entries, open tabs and windows, column layouts and menu
  customisations.
- **Search index:** the names and locations of apps, files and folders on your drives, so the search popup can find
  them quickly. It is built on your PC and never leaves it.
- **Search picks:** which results you chose in the search popup, so they rank higher next time.
- **Crash reports:** if Foldaria closes unexpectedly, a technical report is saved in the `dump` folder and deleted
  after 30 days, or as soon as you report it.

When you turn on **Start with Windows** or **Replace Windows Explorer**, Foldaria writes the matching entries to your
user's part of the Windows registry. Turning the option off removes them.

## Your files and folders

Foldaria shows, opens, copies, moves, renames and deletes files only when you ask it to. All of this happens on your
PC. File icons, context menus, the Recycle Bin, network drives and cloud folder status come from Windows itself.

Other programs can add entries to Foldaria's context menu, as they do in Windows Explorer. Those entries run the other
program's code, and that program's own privacy policy applies to them.

## Network locations and cloud folders

Foldaria shows network shares and cloud folders (for example OneDrive) through Windows. When a network location needs a
password, Windows asks for it in its own dialog. Foldaria never sees or stores your passwords. Storage figures for cloud
folders come from the provider's app installed on your PC.

## Crash reports

Foldaria never sends a crash report on its own. After a crash it may ask whether you want to report it. Only if you
click **Report on GitHub** does Foldaria open your web browser on a new, pre-filled issue on GitHub
(`github.com/Toemsel/Foldaria`). Nothing is sent until you press **Create** on GitHub yourself.

Before the report is filled in, Foldaria removes personal information. File and folder paths, your user name, your PC
and domain names, and e-mail addresses are replaced with placeholders. The report then contains only technical details:
the Foldaria version, the Windows version and display language, your appearance settings (such as theme and font size),
and where in Foldaria's code the crash happened.

GitHub issues are public. If you create one, GitHub's privacy statement applies to it. You can turn the question off
under Settings → General → "Ask to report crashes".

## Links

The links in Settings → About open the project's GitHub pages in your web browser. The website you visit decides what
it collects, not Foldaria.

## Clipboard

Foldaria reads or changes the clipboard only when you copy, cut or paste, or when you use a command such as "Copy path".

## Deleting your data

Uninstalling Foldaria removes the program. To also remove its settings, search index and crash reports, delete the
folder `%APPDATA%\Foldaria`.

## Children

Foldaria collects no data from anyone, including children.

## Changes to this policy

If Foldaria's handling of data changes, this policy will be updated and its effective date changed. Earlier versions
remain visible in the history of the repository where this policy is published.

## Contact

For questions about this policy, open an issue at https://github.com/Toemsel/Foldaria/issues.
