# rhis-builder-satellite-templates
A sample git repository for Satellite template import.

***

This repository contains sample report templates to be imported into Satellite and support template synchronization in a gitops fashion. Any erb template pattern supported by Satellite using the [foreman_template](https://github.com/theforeman/foreman_templates) plugin can be stored in a repo like this. The metadata in the template will be parsed by Satellite and show up in the proper location. In a separate component in the repo we will work on a template validator to that we can validate templates prior to commit.

More details to come...


