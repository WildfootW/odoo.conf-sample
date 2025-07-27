# Odoo 17 Configuration Samples
**Archived — further maintenance has moved to [LiquenOpS](https://github.com/LiquenOpS/odoo.conf-sample).**


This repository contains a sample `odoo.conf` file tailored for Odoo 17. The motivation behind this is that many of the available online configuration samples are for older versions like Odoo 8. To provide a more up-to-date reference, I created this sample specifically for Odoo 17.

## Important Notes
- **Untested**: This configuration file has not been fully tested. Use it with caution and modify it according to your specific setup.
- **Official References**: Any configuration options that do **not** have a `[TODO]` comment (e.g., `[TODO] Verify if 'xxxxx' option is still valid in Odoo 17.`) were directly verified from official sources, such as:
  - [odoo/debian/odoo.conf](https://github.com/odoo/odoo/blob/17.0/debian/odoo.conf)
  - [docker/17.0/odoo.conf](https://github.com/odoo/docker/blob/master/17.0/odoo.conf)
  - [Odoo Docs: System Configuration](https://www.odoo.com/documentation/17.0/administration/on_premise/deploy.html)

## Additional References
For configuration options marked with `[TODO]` or other parameter descriptions, these resources were consulted:
- [CYBROSYS Odoo 17 Development Book](https://www.cybrosys.com/odoo/odoo-books/odoo-17-development/setup-development-environment/conf-file/)
- [Odoo 8 Sample Configuration](https://gist.github.com/Guidoom/d5db0a76ce669b139271a528a8a2a27f)

## Contributing
Feel free to open an issue or submit a pull request to correct explanations or add more options. Contributions are welcome to help improve and expand this configuration file for Odoo 17.
