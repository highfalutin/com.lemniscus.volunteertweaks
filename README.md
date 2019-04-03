# com.lemniscus.volunteertweaks

At the moment, this extension simply designates the pages under `/civicrm/vol` as "private" so that the admin theme will be applied to them.

The extension is licensed under [AGPL-3.0](LICENSE.txt).

## Requirements

* PHP v5.4+
* CiviCRM 5.10 (may work with previous or later versions)
* CiviVolunteer 4.7.31-2.3.1 (may work with previous or later versions)

## Installation (Web UI)

This extension has not yet been published for installation via the web UI.

## Installation (CLI, Zip)

Sysadmins and developers may download the `.zip` file for this extension and
install it with the command-line tool [cv](https://github.com/civicrm/cv).

```bash
cd <extension-dir>
cv dl com.lemniscus.volunteertweaks@https://github.com/highfalutin/com.lemniscus.volunteertweaks/archive/master.zip
```

## Installation (CLI, Git)

Sysadmins and developers may clone the [Git](https://en.wikipedia.org/wiki/Git) repo for this extension and
install it with the command-line tool [cv](https://github.com/civicrm/cv).

```bash
git clone https://github.com/highfalutin/com.lemniscus.volunteertweaks.git
cv en volunteertweaks
```

## Usage

Enable the extension. Flush CiviCRM's caches (`cv flush` is a quick way if you're on the command line). In your web browser, navigate to `civicrm/vol/#/volunteer/manage` (under the CiviCRM base URL &mdash; so for example, the full URL might be https://www.widgets.org/civicrm/vol/#/volunteer/manage) and you should see the page displayed in the admin theme.

## Known Issues

none