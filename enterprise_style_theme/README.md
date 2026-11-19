# Enterprise Style Theme

**Author:** DIGITEN SARL  
**Odoo:** 20 Community  
**License:** LGPL-3  
**Price:** Free

Visual extension of MuK Backend Theme with a light grey cross-pattern launcher background, six-column desktop app grid, responsive layouts, white app-icon cards and refined forms, lists and buttons.

This is an independent Community theme. It is not the official Odoo Enterprise theme and includes neither Enterprise source code nor Enterprise applications. Installed application icons remain supplied by their respective applications. Odoo is a trademark of its respective owner; this module is not endorsed by Odoo S.A.

## Requirements

Install MuK Backend Theme (`muk_web_theme`) for the same Odoo version, and its dependencies. MuK IT retains authorship and licensing of all MuK components. This repository publishes only the DIGITEN visual extension, not the MuK modules under a different name.

## Installation

1. Put `enterprise_style_theme` into an Odoo addons directory.
2. Ensure compatible MuK dependencies are available in the addons path.
3. Restart Odoo, update the Apps list and install **Enterprise Style Theme**.
4. Refresh the browser with Ctrl+F5.

Technical name: enterprise_style_theme. For an earlier release with a different technical name, back up the database, uninstall only the earlier styling extension, keep MuK installed, then install this module. Do not enable both styling extensions together.

## Verification and limits

The styling in the preceding version was verified on the originating Odoo 20 instance. This release changes the technical name and asset paths; installation under the new technical name has not yet been tested. The web, print and dark CSS bundles compiled successfully; the CSS and SVG assets were served successfully. A clean installation on a separate Odoo 20 instance remains to be checked before Store submission. The light launcher background is intentional even when dark mode is selected. Applications shown depend on installed modules and access rights.

No external services, tracking, activation keys, user data collection or additional access permissions are introduced. Uninstall this module to remove its styles; MuK is managed separately.
