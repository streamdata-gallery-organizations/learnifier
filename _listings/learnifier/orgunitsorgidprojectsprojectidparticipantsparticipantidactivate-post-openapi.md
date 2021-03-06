---
swagger: "2.0"
x-collection-name: Learnifier
x-complete: 0
info:
  title: Learnifier Activate participant
  version: 1.1.0
  description: Activates a participant so that it can be used
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
  /orgunits:
    get:
      summary: Organization Units
      description: |-
        The orgunits endpoint returns information about the available organization units (orgunits).
        The response includes the display name, internal and external id and client number.
      operationId: orgunits.get
      x-api-path-slug: orgunits-get
      responses:
        200:
          description: OK
      tags:
      - Organizations
    post:
      summary: Adds an Organization Unit
      description: Adds an Organization Unit
      operationId: orgunits.post
      x-api-path-slug: orgunits-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      responses:
        200:
          description: OK
      tags:
      - Organizations
  /orgunits/{orgid}:
    get:
      summary: Get Organization Unit
      description: |-
        Returns information about the specified organization unit.
        The response includes the display name, internal and external id and client number.
      operationId: orgunits.orgid.get
      x-api-path-slug: orgunitsorgid-get
      parameters:
      - in: path
        name: orgid
        description: Id of the organization unit
      responses:
        200:
          description: OK
      tags:
      - Organizations
    patch:
      summary: Updates an Organization Unit
      description: Adds an Organization Unit
      operationId: orgunits.orgid.patch
      x-api-path-slug: orgunitsorgid-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: orgid
      responses:
        200:
          description: OK
      tags:
      - Organizations
  /orgunits/{orgid}/projects:
    get:
      summary: Organization Unit Projects
      description: Returns the available projects for the organization unit
      operationId: orgunits.orgid.projects.get
      x-api-path-slug: orgunitsorgidprojects-get
      parameters:
      - in: path
        name: orgid
        description: Id of the organization unit
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Projects
    post:
      summary: Create project
      description: Creates a new project
      operationId: orgunits.orgid.projects.post
      x-api-path-slug: orgunitsorgidprojects-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: orgid
        description: Id of the organization unit
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Projects
  /orgunits/{orgid}/projects/{projectid}:
    delete:
      summary: Deletes the project
      description: Deletes the project. The project can only be deleted if the project
        do not contain any participants.
      operationId: orgunits.orgid.projects.projectid.delete
      x-api-path-slug: orgunitsorgidprojectsprojectid-delete
      parameters:
      - in: path
        name: orgid
        description: Id of the organization unit
      - in: path
        name: projectid
        description: Id of the project
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Projects
      - Projectid
    get:
      summary: Project information
      description: Returns project information
      operationId: orgunits.orgid.projects.projectid.get
      x-api-path-slug: orgunitsorgidprojectsprojectid-get
      parameters:
      - in: path
        name: orgid
        description: Id of the organization unit
      - in: path
        name: projectid
        description: Id of the project
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Projects
      - Projectid
    patch:
      summary: Update project information
      description: Updates information about a project. Values are only updated if
        the fields are specified in the input
      operationId: orgunits.orgid.projects.projectid.patch
      x-api-path-slug: orgunitsorgidprojectsprojectid-patch
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: orgid
        description: Id of the organization unit
      - in: path
        name: projectid
        description: Id of the project
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Projects
      - Projectid
  /orgunits/{orgid}/projects/{projectid}/participants:
    get:
      summary: Project participants
      description: Returns project participants
      operationId: orgunits.orgid.projects.projectid.participants.get
      x-api-path-slug: orgunitsorgidprojectsprojectidparticipants-get
      parameters:
      - in: path
        name: orgid
        description: Id of the organization unit
      - in: path
        name: projectid
        description: Id of the project
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Projects
      - Projectid
      - Participants
    post:
      summary: Add participant
      description: Add a user to the project. Participant information is created for
        the user. In the body object, only one of either email or userid must be specified.
        The participant needs to be activated before it the user can access it.
      operationId: orgunits.orgid.projects.projectid.participants.post
      x-api-path-slug: orgunitsorgidprojectsprojectidparticipants-post
      parameters:
      - in: body
        name: body
        schema:
          $ref: '#/definitions/holder'
      - in: path
        name: orgid
        description: Id of the organization unit
      - in: path
        name: projectid
        description: Id of the project
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Projects
      - Projectid
      - Participants
  /orgunits/{orgid}/projects/{projectid}/participants/${participantId}:
    delete:
      summary: Deletes a participant
      description: "Deletes a participant. The user itself will still remain but any
        state related to the project will be deleted. \nIt might not be possible due
        to constraints from the products in the project to delete the participant.
        However\nthis can only be determined at the time of the delete. If a delete
        fails the participant will have their inError\nflag set."
      operationId: orgunits.orgid.projects.projectid.participants._participantId.delete
      x-api-path-slug: orgunitsorgidprojectsprojectidparticipantsparticipantid-delete
      parameters:
      - in: path
        name: orgid
        description: Id of the organization unit
      - in: path
        name: participantId
        description: Participant id
      - in: path
        name: projectid
        description: Id of the project
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Projects
      - Projectid
      - Participants
      - $participantId
  /orgunits/{orgid}/projects/{projectid}/participants/${participantId}/activate:
    post:
      summary: Activate participant
      description: Activates a participant so that it can be used
      operationId: orgunits.orgid.projects.projectid.participants._participantId.activate.post
      x-api-path-slug: orgunitsorgidprojectsprojectidparticipantsparticipantidactivate-post
      parameters:
      - in: path
        name: orgid
        description: Id of the organization unit
      - in: path
        name: participantId
        description: Id of the participant
      - in: path
        name: projectid
        description: Id of the project
      responses:
        200:
          description: OK
      tags:
      - Organizations
      - Projects
      - Projectid
      - Participants
      - $participantId
      - Activate
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