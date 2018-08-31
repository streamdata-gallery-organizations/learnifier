---
swagger: "2.0"
x-collection-name: Learnifier
x-complete: 0
info:
  title: Learnifier List of all users in group.
  version: 1.1.0
  description: Returns a list of all members in User Groups that are based on the
    Global Group with this groupid.
host: learnifier.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /coursedesigns:
    get:
      summary: Lists all global course design templates
      description: Lists all global course design templates. Only api callers that
        have full access can call this method.
      operationId: coursedesigns.get
      x-api-path-slug: coursedesigns-get
      responses:
        200:
          description: OK
      tags:
      - Courses
  /extorgunit:
    get:
      summary: Get Organization Unit with External Id
      description: Returns information about the organization unit with the specified
        external id.
      operationId: extorgunit.get
      x-api-path-slug: extorgunit-get
      parameters:
      - in: query
        name: extid
        description: The external id of the organization unit
      responses:
        200:
          description: OK
      tags:
      - Organizations
  /extparticipation:
    get:
      summary: Gets a participation by external id
      description: Gets a participation by external id.
      operationId: extparticipation.get
      x-api-path-slug: extparticipation-get
      parameters:
      - in: query
        name: extid
        description: The external id of the participation
      responses:
        200:
          description: OK
      tags:
      - Courses
      - Participation
  /extproject:
    get:
      summary: Gets Organization Unit by external id
      description: Gets an Organization Unit by external id
      operationId: extproject.get
      x-api-path-slug: extproject-get
      parameters:
      - in: query
        name: extid
        description: The external id of the organization unit
      responses:
        200:
          description: OK
      tags:
      - Projects
  /extuser:
    get:
      summary: Gets a user by external id
      description: Gets a user by external id.
      operationId: extuser.get
      x-api-path-slug: extuser-get
      parameters:
      - in: query
        name: extid
        description: The external id of the user
      responses:
        200:
          description: OK
      tags:
      - Users
  /globalusergroups:
    get:
      summary: List Global User Groups.
      description: Returns a list of Global User Groups. Global User Groups are set
        up for the realm, and will generate groups that can be used on the client
        level.
      operationId: globalusergroups.get
      x-api-path-slug: globalusergroups-get
      responses:
        200:
          description: OK
      tags:
      - Users
      - Groups
  /globalusergroups/{groupid}/members:
    get:
      summary: List of all users in group.
      description: Returns a list of all members in User Groups that are based on
        the Global Group with this groupid.
      operationId: globalusergroups.groupid.members.get
      x-api-path-slug: globalusergroupsgroupidmembers-get
      parameters:
      - in: path
        name: groupid
        description: ID of group
      responses:
        200:
          description: OK
      tags:
      - Users
      - Groups
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---