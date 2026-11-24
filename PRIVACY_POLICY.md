# TechTasker Privacy Policy

Last updated: November 24, 2026

TechTasker is a Chrome extension for managing technical ideas stored in a user-configured Bitbucket repository, synchronizing related Jira data, and optionally generating Jira descriptions through a user-configured OpenAI-compatible API.

## Data handled by the extension

TechTasker may store and process the following data:

- Bitbucket repository URL and Bitbucket API token.
- Jira base URL, project settings, field mappings, selected authentication mode, and Jira API token when PAT authentication is used.
- OpenAI-compatible API URL, model name, and API token.
- Ideas, idea descriptions, Jira links, Jira statuses, estimates, history events, attachments metadata, and cached synchronization data.

## How data is used

The data is used only to provide the extension functionality:

- loading and saving ideas in the configured Bitbucket repository;
- reading Jira issue data and creating or updating Jira-related information;
- sending selected idea content to the configured OpenAI-compatible API when the user uses AI generation features;
- caching previously loaded data locally to improve performance.

## Data storage

Settings, tokens, and cached application data are stored locally in the user's browser profile using Chrome extension storage and IndexedDB.

When browser-session authentication is selected for Jira, the browser may attach the current Jira session cookies to requests sent directly to the configured Jira server. TechTasker does not read or store the values of those cookies.

The extension developer does not receive, store, or process this data on developer-controlled servers.

## Data sharing

TechTasker does not sell user data and does not use user data for advertising, analytics, profiling, creditworthiness, or data brokerage.

The extension only sends data to services configured by the user:

- the configured Bitbucket server;
- the configured Jira server;
- the configured OpenAI-compatible API provider.

## Security

Users are responsible for configuring trusted Bitbucket, Jira, and OpenAI-compatible API endpoints. HTTPS endpoints are recommended for all integrations.

API tokens should be treated as sensitive credentials. Users should only enter tokens that are intended for use with the configured services and should revoke tokens when they are no longer needed. Browser-session authentication is limited by the permissions and lifetime of the Jira session in the current browser profile.

## Data deletion

Users can remove stored settings and cached data by clearing the extension's browser storage or uninstalling the extension.

Users can also revoke Bitbucket, Jira, or OpenAI-compatible API tokens in the corresponding external service. For browser-session authentication, signing out of Jira or letting the Jira session expire stops authenticated access from the extension.

## Limited use

TechTasker uses user data only for the extension's single purpose: managing technical ideas with user-configured Bitbucket, Jira, and OpenAI-compatible API integrations.

TechTasker does not:

- sell user data;
- use or transfer user data for personalized advertising;
- use or transfer user data for purposes unrelated to the extension's stated functionality;
- use or transfer user data to determine creditworthiness or for lending purposes.

## Contact

For privacy questions, open an issue in the [TechTasker Privacy Policy repository](https://github.com/Vladislav4er/tech-tasker-privacy-policy/issues).
