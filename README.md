# mautic.org-website
This repository relates to the mautic.org website. We accept PRs here to make changes, and issues to flag up problems that you might find or changes that are needed.

## Local Developer setup

Our preferred setup for local development is DDEV, and we have included all of the necessary files and configuration here to spin up a local developer environment using DDEV and get going for contributions back to this project.

If you prefer another environment for local development, we are happy to take merge requests that provide alternate configuration and instructions to use something other than DDEV.  However the core Mautic.org support team will only provide support and troubleshooting if you are using DDEV for local development, as this is our adopted standard.

### Local developer spinup -- no seed database available

Local developer spinup assumes you are using DDEV for local developer environments.

You can install the codebase for Mautic.org without a seed database (i.e., no content) following these instructions.

1.  Check out this code repository on the `main` branch
1.  Copy the files located in .ddev/scaffold to docroot/sites/default/
1.  Execute `ddev start` -- this will initialize a local environment with a settings.ddev.php file, which is excluded from any commits with .gitignore rules in the codebase.
1.  Execute `ddev init`

This will initialize the Mautic site locally, with the Mautic.org theme, but no content or configuration beyond what is installed with the `mauticorg` default profile.

### Local developer spinup -- seed database

Under construction!  Coming soon...
