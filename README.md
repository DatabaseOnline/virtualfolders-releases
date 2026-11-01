# SQLTreeo Virtual Folders downloads

This repository only hosts the release files of **SQLTreeo Virtual Folders**, the add-in by
[SQLTreeo](https://www.sqltreeo.com/virtual-folders) that organizes the Object Explorer of SQL Server Management
Studio (SSMS) into your own folders: for databases, tables, views, procedures, functions, logins and SQL Server Agent
jobs, with a quick filter, special folders and extra information on the right-click menu.

- **Download:** every release is for one version of SSMS, which is the first number of the version: `v22.x.y.z` is for
  SSMS 22, `v21.x.y.z` for SSMS 21 and `v20.x.y.z` for SSMS 20. Pick the newest release of your SSMS version.
  - `VirtualFolders_v22_..._.msi` (SSMS 22): the installer. It finds SSMS 22, copies the add-in into its Extensions
    folder and asks SSMS to register it. It needs administrator rights and SSMS 22 installed first.
  - `VirtualFolders_v..._.zip`: the same files as a zip to extract into the Extensions folder of SSMS (unblock the zip
    first). See the installation guide on the website.
- **Product page, pricing and license keys:** https://www.sqltreeo.com/virtual-folders
- **Installation guides and documentation:** https://www.sqltreeo.com/docs/virtual-folders
- **Support:** https://www.sqltreeo.com

SQLTreeo Virtual Folders is commercial software. It is licensed, not sold: see [LICENSE.txt](LICENSE.txt) (end-user
license agreement). The first start begins a free 30-day trial with every feature enabled; after that a license key is
needed, sold on the website. The add-in changes nothing on your SQL Servers. The binaries in every release are signed by
Databaseonline.

The add-in does not update itself. From version 22.0.0.125 it asks sqltreeo.com once per start of SSMS whether a newer
version exists and says so on its menu item and on its Options page (switchable). Updating means installing the newer
release from here.
