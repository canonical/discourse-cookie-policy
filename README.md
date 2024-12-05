# discourse-cookie-policy

This repository contains a discourse theme component for a cookie policy notification.

## How to use it

This component can only be used through discourse. You are able to add it through the admin panel to a pre-existing theme. 
See the discourse guide for more info: https://meta.discourse.org/t/installing-a-theme-or-theme-component/63682

## How to update it

Ensure the latest version of of the [canonical cookie policy](https://github.com/canonical/cookie-policy) is installed in the project.

Run the build command:

`yarn run build-cookie-policy`

Merge the changes in the the `main` branch.

The changes will be picked up automatically by discourse and a discourse admin will be prompted to pull in the latest changes.