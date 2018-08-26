---
name: LaunchDarkly
x-slug: launchdarkly
description: Our vision is to eliminate risk for developers and operations teams from
  the software development cycle. As companies transition to a world built on software,
  there is an increasing requirement to move quickly&mdash;but that often comes with
  the desire to maintain control. LaunchDarkly is the feature management platform
  that enables dev and ops teams to control the whole feature lifecycle, from concept
  to launch to value. Feature flagging is an industry best practice of wrapping a
  new or risky section of code or infrastructure change with a flag. Each flag can
  easily be turned on/off independent of code deployment (aka &rdquo;dark launching&rdquo;).
  Equipping businesses with the ability to move at the speed of every deploy allows
  an entire company to learn rapidly, deliver value to their customers faster, and
  produce more value. Developers can build, marketing can launch, product can iterate,
  and sales can sell.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
x-kinRank: "7"
x-alexaRank: "187776"
tags: Flags
created: "2018-08-25"
modified: "2018-08-25"
url: https://raw.githubusercontent.com/streamdata-gallery-topics/flags/master/_listings/launchdarkly/apis.md
specificationVersion: "0.14"
apis:
- name: Launch Darkly - Get a list of all features in the given project.
  x-api-slug: flagsprojectkey-get
  description: Get a list of all features in the given project..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2
  tags: SaaS, Technology, Enterprise, Orchestration, Containers, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/flags/master/_listings/launchdarkly/flagsprojectkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/flags/master/_listings/launchdarkly/flagsprojectkey-get-openapi.md
- name: Launch Darkly - Create a feature flag
  x-api-slug: flagsprojectkey-post
  description: Create a feature flag.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2
  tags: SaaS, Technology, Enterprise, Orchestration, Containers, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/flags/master/_listings/launchdarkly/flagsprojectkey-post-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/flags/master/_listings/launchdarkly/flagsprojectkey-post-openapi.md
- name: Launch Darkly - Delete a feature flag by ID
  x-api-slug: flagsprojectkeyfeatureflagkey-delete
  description: Delete a feature flag by id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2
  tags: SaaS, Technology, Enterprise, Orchestration, Containers, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/flags/master/_listings/launchdarkly/flagsprojectkeyfeatureflagkey-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/flags/master/_listings/launchdarkly/flagsprojectkeyfeatureflagkey-delete-openapi.md
- name: Launch Darkly - Get a single feature flag by key.
  x-api-slug: flagsprojectkeyfeatureflagkey-get
  description: Get a single feature flag by key..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2
  tags: SaaS, Technology, Enterprise, Orchestration, Containers, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/flags/master/_listings/launchdarkly/flagsprojectkeyfeatureflagkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/flags/master/_listings/launchdarkly/flagsprojectkeyfeatureflagkey-get-openapi.md
- name: Launch Darkly - Modify a feature flag by ID
  x-api-slug: flagsprojectkeyfeatureflagkey-patch
  description: Modify a feature flag by id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2
  tags: SaaS, Technology, Enterprise, Orchestration, Containers, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/flags/master/_listings/launchdarkly/flagsprojectkeyfeatureflagkey-patch-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/flags/master/_listings/launchdarkly/flagsprojectkeyfeatureflagkey-patch-openapi.md
- name: Launch Darkly - Lists the current flag settings for a given user.
  x-api-slug: usersprojectkeyenvironmentkeyuserkeyflags-get
  description: Lists the current flag settings for a given user..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2
  tags: SaaS, Technology, Enterprise, Orchestration, Containers, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/flags/master/_listings/launchdarkly/usersprojectkeyenvironmentkeyuserkeyflags-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/flags/master/_listings/launchdarkly/usersprojectkeyenvironmentkeyuserkeyflags-get-openapi.md
- name: Launch Darkly - Get a user by key.
  x-api-slug: usersprojectkeyenvironmentkeyuserkeyflagsfeatureflagkey-get
  description: Get a user by key..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2
  tags: SaaS, Technology, Enterprise, Orchestration, Containers, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/flags/master/_listings/launchdarkly/usersprojectkeyenvironmentkeyuserkeyflagsfeatureflagkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/flags/master/_listings/launchdarkly/usersprojectkeyenvironmentkeyuserkeyflagsfeatureflagkey-get-openapi.md
- name: Launch Darkly - Specifically enable or disable a feature flag for a user based
    on their key.
  x-api-slug: usersprojectkeyenvironmentkeyuserkeyflagsfeatureflagkey-put
  description: Specifically enable or disable a feature flag for a user based on their
    key..
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2
  tags: SaaS, Technology, Enterprise, Orchestration, Containers, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/flags/master/_listings/launchdarkly/usersprojectkeyenvironmentkeyuserkeyflagsfeatureflagkey-put-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/flags/master/_listings/launchdarkly/usersprojectkeyenvironmentkeyuserkeyflagsfeatureflagkey-put-openapi.md
- name: Launch Darkly - Get a list of statuses for all feature flags
  x-api-slug: flagstatusesprojectkeyenvironmentkey-get
  description: Get a list of statuses for all feature flags.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2
  tags: SaaS, Technology, Enterprise, Orchestration, Containers, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/flags/master/_listings/launchdarkly/flagstatusesprojectkeyenvironmentkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/flags/master/_listings/launchdarkly/flagstatusesprojectkeyenvironmentkey-get-openapi.md
- name: Launch Darkly - Get a list of statuses for all feature flags
  x-api-slug: flagstatusesprojectkeyenvironmentkeyfeatureflagkey-get
  description: Get a list of statuses for all feature flags.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2
  tags: SaaS, Technology, Enterprise, Orchestration, Containers, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/flags/master/_listings/launchdarkly/flagstatusesprojectkeyenvironmentkeyfeatureflagkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/flags/master/_listings/launchdarkly/flagstatusesprojectkeyenvironmentkeyfeatureflagkey-get-openapi.md
- name: Launch Darkly - Get a list of statuses for all feature flags
  x-api-slug: flagstatusesprojectkeyenvironmentkey-get
  description: Get a list of statuses for all feature flags.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2
  tags: SaaS, Technology, Enterprise, Orchestration, Containers, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/flags/master/_listings/launchdarkly/flagstatusesprojectkeyenvironmentkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/flags/master/_listings/launchdarkly/flagstatusesprojectkeyenvironmentkey-get-openapi.md
- name: Launch Darkly - Get a list of statuses for all feature flags
  x-api-slug: flagstatusesprojectkeyenvironmentkeyfeatureflagkey-get
  description: Get a list of statuses for all feature flags.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/21652-launchdarkly-com.jpg
  humanURL: http://www.launchdarkly.com
  baseURL: https://app.launchdarkly.com//api/v2
  tags: SaaS, Technology, Enterprise, Orchestration, Containers, API Service Provider,
    API Provider, Profiles, Relative Data, Service API
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/flags/master/_listings/launchdarkly/flagstatusesprojectkeyenvironmentkeyfeatureflagkey-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-topics/flags/master/_listings/launchdarkly/flagstatusesprojectkeyenvironmentkeyfeatureflagkey-get-openapi.md
x-common:
- type: x-website
  url: http://www.launchdarkly.com
- type: x-api-gallery
  url: http://kubernetes.api.gallery.streamdata.io
- type: x-api-stack
  url: http://launchdarkly.stack.network
- type: x-crunchbase
  url: https://crunchbase.com/organization/launchdarkly
- type: x-email
  url: sales@launchdarkly.com
- type: x-email
  url: privacy@launchdarkly.com
- type: x-email
  url: security@launchdarkly.com
- type: x-github
  url: https://github.com/launchdarkly
- type: x-curated-source
  url: http://launchdarkly.com/blog/stripe-webhook-event-processing-best-practices/
- type: x-website
  url: http://launchdarkly.com
- type: x-twitter
  url: https://twitter.com/LaunchDarkly
- type: x-webhook
  url: https://apidocs.launchdarkly.com/docs/webhooks-overview
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---