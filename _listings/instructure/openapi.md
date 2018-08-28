swagger: "2.0"
x-collection-name: Instructure
x-complete: 1
info:
  title: Instructure Canvas Utility APIs
  description: canvas-lms-includes-a-rest-api-for-accessing-and-modifying-data-externally-from-the-main-application-in-your-own-programs-and-scripts--
  termsOfService: https://www.canvaslms.com/policies/api-policy
  version: v1
host: canvas.instructure.com
basePath: /api/v1
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /courses/{course_id}/features/flags/feature:
    delete:
      summary: Remove feature flag
      description: Remove feature flag.
      operationId: remove-feature-flag
      x-api-path-slug: coursescourse-idfeaturesflagsfeature-delete
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Features
      - Flags
      - Feature
    get:
      summary: Get feature flag
      description: Get feature flag.
      operationId: get-feature-flag
      x-api-path-slug: coursescourse-idfeaturesflagsfeature-get
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Features
      - Flags
      - Feature
    put:
      summary: Set feature flag
      description: Set feature flag.
      operationId: set-feature-flag
      x-api-path-slug: coursescourse-idfeaturesflagsfeature-put
      parameters:
      - in: query
        name: locking_account_id
        description: If set, this FeatureFlag may only be modified by someone withnadministrative
          rights in the specified account
      - in: query
        name: state
        description: u201coffu201dnnThe feature is not available for the course, user,
          or account andnsub-accounts
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Course
      - Id
      - Features
      - Flags
      - Feature
  /quiz_submissions/{quiz_submission_id}/questions/id/flag:
    put:
      summary: Flagging a question.
      description: Flagging a question..
      operationId: flagging-a-question
      x-api-path-slug: quiz-submissionsquiz-submission-idquestionsidflag-put
      parameters:
      - in: query
        name: access_code
        description: Access code for the Quiz, if any
      - in: query
        name: attempt
        description: The attempt number of the quiz submission being taken
      - in: query
        name: validation_token
        description: The unique validation token you received when the Quiz Submission
          wasncreated
      responses:
        200:
          description: OK
      tags:
      - Quiz
      - Submissions
      - Quiz
      - Submission
      - Id
      - Questions
      - Id
      - Flag
  /users/{user_id}/features/flags/feature:
    delete:
      summary: Remove feature flag
      description: Remove feature flag.
      operationId: remove-feature-flag
      x-api-path-slug: usersuser-idfeaturesflagsfeature-delete
      responses:
        200:
          description: OK
      tags:
      - Users
      - User
      - Id
      - Features
      - Flags
      - Feature
    get:
      summary: Get feature flag
      description: Get feature flag.
      operationId: get-feature-flag
      x-api-path-slug: usersuser-idfeaturesflagsfeature-get
      responses:
        200:
          description: OK
      tags:
      - Users
      - User
      - Id
      - Features
      - Flags
      - Feature
    put:
      summary: Set feature flag
      description: Set feature flag.
      operationId: set-feature-flag
      x-api-path-slug: usersuser-idfeaturesflagsfeature-put
      parameters:
      - in: query
        name: locking_account_id
        description: If set, this FeatureFlag may only be modified by someone withnadministrative
          rights in the specified account
      - in: query
        name: state
        description: u201coffu201dnnThe feature is not available for the course, user,
          or account andnsub-accounts
      responses:
        200:
          description: OK
      tags:
      - Users
      - User
      - Id
      - Features
      - Flags
      - Feature