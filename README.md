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

1. Put `aya_backend_theme` into an Odoo addons directory.
2. Ensure compatible MuK dependencies are available in the addons path.
3. Restart Odoo, update the Apps list and install **Enterprise Style Theme**.
4. Refresh the browser with Ctrl+F5.

Technical module name `aya_backend_theme` is retained for compatibility with existing installations. Upgrading does not require uninstalling or migrating the existing module.

## Verification and limits

Version 20.0.1.2.0 was installed on the originating Odoo 20 instance. The web, print and dark CSS bundles compiled successfully; the CSS and SVG assets were served successfully. A clean installation on a separate Odoo 20 instance remains to be checked before Store submission. The light launcher background is intentional even when dark mode is selected. Applications shown depend on installed modules and access rights.

No external services, tracking, activation keys, user data collection or additional access permissions are introduced. Uninstall this module to remove its styles; MuK is managed separately.
