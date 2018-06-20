---
name: Microsoft Graph
x-slug: microsoft-graph
description: 'Microsoft Graph exposes multiple APIs from Office 365 and other Microsoft
  cloud services through a single endpoint: https://graph.microsoft.com. Microsoft
  Graph simplifies queries that would otherwise be more complex. You can use Microsoft
  Graph to: Access data from multiple Microsoft cloud services, including Azure Active
  Directory, Exchange Online as part of Office 365, SharePoint, OneDrive, OneNote,
  and Planner. Navigate between entities and relationships. Access intelligence and
  insights from the Microsoft cloud (for commercial users).'
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Snooze
created: "2018-06-20"
modified: "2018-06-20"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/snooze/master/_listings/microsoft-graph/apis.md
specificationVersion: "0.14"
apis:
- name: Microsoft Graph Event Snooze Reminder
  x-api-slug: microsoft-graph
  description: 'event: snoozeReminder Postpone a reminder until a new time.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/events/{id}/snoozeReminder
  tags: Event, Snooze, Reminder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/snooze/master/_listings/microsoft-graph/meeventsidsnoozereminder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/snooze/master/_listings/microsoft-graph/meeventsidsnoozereminder-post-openapi.md
- name: Microsoft Graph Event Snooze Reminder
  x-api-slug: microsoft-graph
  description: 'event: snoozeReminder Postpone a reminder until a new time.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/events/{id}/snoozeReminder
  tags: Event, Snooze, Reminder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/snooze/master/_listings/microsoft-graph/usersid--userprincipalnameeventsidsnoozereminder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/snooze/master/_listings/microsoft-graph/usersid--userprincipalnameeventsidsnoozereminder-post-openapi.md
- name: Microsoft Graph Event Snooze Reminder
  x-api-slug: microsoft-graph
  description: 'event: snoozeReminder Postpone a reminder until a new time.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/events/{id}/snoozeReminder
  tags: Event, Snooze, Reminder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/snooze/master/_listings/microsoft-graph/groupsideventsidsnoozereminder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/snooze/master/_listings/microsoft-graph/groupsideventsidsnoozereminder-post-openapi.md
- name: Microsoft Graph Event Snooze Reminder
  x-api-slug: microsoft-graph
  description: 'event: snoozeReminder Postpone a reminder until a new time.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendar/events/{id}/snoozeReminder
  tags: Event, Snooze, Reminder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/snooze/master/_listings/microsoft-graph/mecalendareventsidsnoozereminder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/snooze/master/_listings/microsoft-graph/mecalendareventsidsnoozereminder-post-openapi.md
- name: Microsoft Graph Event Snooze Reminder
  x-api-slug: microsoft-graph
  description: 'event: snoozeReminder Postpone a reminder until a new time.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendar/events/{id}/snoozeReminder
  tags: Event, Snooze, Reminder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/snooze/master/_listings/microsoft-graph/usersid--userprincipalnamecalendareventsidsnoozereminder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/snooze/master/_listings/microsoft-graph/usersid--userprincipalnamecalendareventsidsnoozereminder-post-openapi.md
- name: Microsoft Graph Event Snooze Reminder
  x-api-slug: microsoft-graph
  description: 'event: snoozeReminder Postpone a reminder until a new time.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////groups/{id}/calendar/events/{id}/snoozeReminder
  tags: Event, Snooze, Reminder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/snooze/master/_listings/microsoft-graph/groupsidcalendareventsidsnoozereminder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/snooze/master/_listings/microsoft-graph/groupsidcalendareventsidsnoozereminder-post-openapi.md
- name: Microsoft Graph Event Snooze Reminder
  x-api-slug: microsoft-graph
  description: 'event: snoozeReminder Postpone a reminder until a new time.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendars/{id}/events/{id}/snoozeReminder
  tags: Event, Snooze, Reminder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/snooze/master/_listings/microsoft-graph/mecalendarsideventsidsnoozereminder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/snooze/master/_listings/microsoft-graph/mecalendarsideventsidsnoozereminder-post-openapi.md
- name: Microsoft Graph Event Snooze Reminder
  x-api-slug: microsoft-graph
  description: 'event: snoozeReminder Postpone a reminder until a new time.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendars/{id}/events/{id}/snoozeReminder
  tags: Event, Snooze, Reminder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/snooze/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsideventsidsnoozereminder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/snooze/master/_listings/microsoft-graph/usersid--userprincipalnamecalendarsideventsidsnoozereminder-post-openapi.md
- name: Microsoft Graph Event Snooze Reminder
  x-api-slug: microsoft-graph
  description: 'event: snoozeReminder Postpone a reminder until a new time.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroup/calendars/{id}/events/{id}/snoozeReminder
  tags: Event, Snooze, Reminder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/snooze/master/_listings/microsoft-graph/mecalendargroupcalendarsideventsidsnoozereminder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/snooze/master/_listings/microsoft-graph/mecalendargroupcalendarsideventsidsnoozereminder-post-openapi.md
- name: Microsoft Graph Event Snooze Reminder
  x-api-slug: microsoft-graph
  description: 'event: snoozeReminder Postpone a reminder until a new time.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendargroup/calendars/{id}/events/{id}/snoozeReminder
  tags: Event, Snooze, Reminder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/snooze/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsideventsidsnoozereminder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/snooze/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupcalendarsideventsidsnoozereminder-post-openapi.md
- name: Microsoft Graph Event Snooze Reminder
  x-api-slug: microsoft-graph
  description: 'event: snoozeReminder Postpone a reminder until a new time.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////me/calendargroups/{id}/calendars/{id}/events/{id}/snoozeReminder
  tags: Event, Snooze, Reminder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/snooze/master/_listings/microsoft-graph/mecalendargroupsidcalendarsideventsidsnoozereminder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/snooze/master/_listings/microsoft-graph/mecalendargroupsidcalendarsideventsidsnoozereminder-post-openapi.md
- name: Microsoft Graph Event Snooze Reminder
  x-api-slug: microsoft-graph
  description: 'event: snoozeReminder Postpone a reminder until a new time.'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com////users/{id | userPrincipalName}/calendargroups/{id}/calendars/{id}/events/{id}/snoozeReminder
  tags: Event, Snooze, Reminder
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/snooze/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsideventsidsnoozereminder-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/snooze/master/_listings/microsoft-graph/usersid--userprincipalnamecalendargroupsidcalendarsideventsidsnoozereminder-post-openapi.md
- name: Microsoft Graph
  x-api-slug: microsoft-graph
  description: 'Microsoft Graph exposes multiple APIs from Office 365 and other Microsoft
    cloud services through a single endpoint: https://graph.microsoft.com. Microsoft
    Graph simplifies queries that would otherwise be more complex. You can use Microsoft
    Graph to: Access data from multiple Microsoft cloud services, including Azure
    Active Directory, Exchange Online as part of Office 365, SharePoint, OneDrive,
    OneNote, and Planner. Navigate between entities and relationships. Access intelligence
    and insights from the Microsoft cloud (for commercial users).'
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/microsoft-graph.png
  humanURL: https://developer.microsoft.com/en-us/graph/
  baseURL: https://graph.microsoft.com//
  tags: Snooze
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/snooze/master/_listings/microsoft-graph/openapi.md
x-common:
- type: x-change-loge
  url: https://developer.microsoft.com/en-us/graph/docs/overview/changelog
- type: x-documentation
  url: https://developer.microsoft.com/en-us/graph/docs
- type: x-explorer
  url: https://developer.microsoft.com/en-us/graph/graph-explorer
- type: x-getting-started
  url: https://developer.microsoft.com/en-us/graph/docs/get-started/rest
- type: x-github
  url: https://github.com/microsoftgraph
- type: x-sdk
  url: https://developer.microsoft.com/en-us/graph/code-samples-and-sdks
- type: x-website
  url: https://developer.microsoft.com/en-us/graph/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---