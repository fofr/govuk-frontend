GOV.UK Frontend ·
[![Build Status](https://travis-ci.com/alphagov/govuk-frontend.svg?branch=master)](https://travis-ci.com/alphagov/govuk-frontend)
[![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)
=====================

GOV.UK Frontend contains the code you need to start building a user interface
for government platforms and services.

See live examples of GOV.UK Frontend components, and guidance on when to use
them in your service, in the [GOV.UK Design
System](https://test_moving_docs--govuk-design-system-preview.netlify.com/).

## Contact the team

GOV.UK Frontend is maintained by a team at Government Digital Service. If you want to know more about GOV.UK Frontend, please email the [Design System
team](mailto:govuk-design-system-support@digital.cabinet-office.gov.uk) or get in touch with them on [Slack](https://ukgovernmentdigital.slack.com/messages/govuk-design-system).

## Quick start

There are 2 ways to start using GOV.UK Frontend in your app.

Once installed, you will be able to use the code from the examples in the
[GOV.UK Design System](https://test_moving_docs--govuk-design-system-preview.netlify.com/)
in your service.

### 1. Install with npm (recommended)

We recommend [installing GOV.UK Frontend using node package manager
(npm)](https://govuk-frontend-docs-prototype.netlify.com/installing_with_npm/#install-using-node-js-package-manager-npm).

### 2. Install by using compiled files

You can also [download the compiled and minified assets (CSS, JavaScript) from
GitHub](https://govuk-frontend-docs-prototype.netlify.com/installing_from_dist/#install-from-dist).

## Browser and assistive technology support

GOV.UK Frontend supports:

- [recommended browsers](https://www.gov.uk/service-manual/technology/designing-for-different-browsers-and-devices#browsers-to-test-in)
- [recommended assistive technologies](https://www.gov.uk/service-manual/technology/testing-with-assistive-technologies#what-to-test)
- Internet Explorer 8, 9 and 10, although components may not look perfect
- your users overriding colours in Windows, Firefox and Chrome

## Accessibility

The GOV.UK Design System team works hard to ensure that GOV.UK Frontend is accessible.

Using Frontend will help your service meet [level AA of WCAG 2.1](https://www.gov.uk/service-manual/helping-people-to-use-your-service/understanding-wcag). But you must still [check that your service meets accessibility requirements](https://www.gov.uk/service-manual/helping-people-to-use-your-service/making-your-service-accessible-an-introduction), especially if you extend or modify components.

You should also use:

- [the JavaScript from GOV.UK Frontend](https://govuk-frontend-docs-prototype.netlify.com/installing_with_npm/#4-add-javascript-and-initialise-components)
- [a separate stylesheet](https://govuk-frontend-docs-prototype.netlify.com/supporting_ie8/#support-internet-explorer-8) if you support Internet Explorer 8

Your service will not meet level AA of WCAG 2.1 if you use [compatibility mode](https://govuk-frontend-docs-prototype.netlify.com/compatibility_mode/#use-our-old-frameworks-or-colours) to use GOV.UK Frontend with old frameworks or the old colour palette.

You can also read the [accessibility statement for the GOV.UK Design System](https://test_moving_docs--govuk-design-system-preview.netlify.com/accessibility/).

### Accessibility warnings

If you get a warning from a linter or accessibility checker, check our list of [issues you should not need to fix](https://github.com/alphagov/govuk-frontend/issues/1280#issuecomment-509588851).

## Getting updates

To be notified when there’s a new release, you can either:

- [watch the govuk-frontend Github repository](https://help.github.com/en/articles/watching-and-unwatching-repositories)
- join the [#govuk-design-system channel on cross-government Slack](https://ukgovernmentdigital.slack.com/app_redirect?channel=govuk-design-system)

Find out how to [update with npm](https://govuk-frontend-docs-prototype.netlify.com/updating_with_npm/#update-using-node-js-package-manager-npm).

## Licence

Unless stated otherwise, the codebase is released under the MIT License. This
covers both the codebase and any sample code in the documentation. The
documentation is &copy; Crown copyright and available under the terms of the
Open Government 3.0 licence.

## Contribution guidelines

If you want to help us build GOV.UK Frontend, view our [contribution
guidelines](CONTRIBUTING.md).
