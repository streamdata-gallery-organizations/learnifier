---
name: Learnifier
x-slug: learnifier
description: Create your online courses in minutes. Learnifier is the fast and easy
  tool for creating and sharing great courses that work on your mobile, tablet and
  desktop. Book a DEMO or test it out with our FREE TRIAL.
image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
x-kinRank: "7"
x-alexaRank: "5836977"
tags: Learnifier
created: "2018-06-26"
modified: "2018-06-26"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/apis.md
specificationVersion: "0.14"
apis:
- name: Learnifier Lists all global course design templates
  x-api-slug: learnifier
  description: Lists all global course design templates. Only api callers that have
    full access can call this method.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////coursedesigns
  tags: Courses
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/coursedesigns-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/coursedesigns-get-openapi.md
- name: Learnifier Get Organization Unit with External Id
  x-api-slug: learnifier
  description: Returns information about the organization unit with the specified
    external id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////extorgunit
  tags: Organizations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/extorgunit-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/extorgunit-get-openapi.md
- name: Learnifier Gets a participation by external id
  x-api-slug: learnifier
  description: Gets a participation by external id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////extparticipation
  tags: Courses, Participation
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/extparticipation-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/extparticipation-get-openapi.md
- name: Learnifier Gets Organization Unit by external id
  x-api-slug: learnifier
  description: Gets an Organization Unit by external id
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////extproject
  tags: Projects
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/extproject-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/extproject-get-openapi.md
- name: Learnifier Gets a user by external id
  x-api-slug: learnifier
  description: Gets a user by external id.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////extuser
  tags: Users
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/extuser-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/extuser-get-openapi.md
- name: Learnifier List Global User Groups.
  x-api-slug: learnifier
  description: Returns a list of Global User Groups. Global User Groups are set up
    for the realm, and will generate groups that can be used on the client level.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////globalusergroups
  tags: Users,Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/globalusergroups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/globalusergroups-get-openapi.md
- name: Learnifier List of all users in group.
  x-api-slug: learnifier
  description: Returns a list of all members in User Groups that are based on the
    Global Group with this groupid.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////globalusergroups/{groupid}/members
  tags: Users,Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/globalusergroupsgroupidmembers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/globalusergroupsgroupidmembers-get-openapi.md
- name: Learnifier Organization Units
  x-api-slug: learnifier
  description: |-
    The orgunits endpoint returns information about the available organization units (orgunits).
    The response includes the display name, internal and external id and client number.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////orgunits
  tags: Organizations
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/orgunits-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/orgunits-get-openapi.md
- name: Learnifier Adds an Organization Unit
  x-api-slug: learnifier
  description: Adds an Organization Unit
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////orgunits
  tags: Organizations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/orgunits-post-openapi.md
- name: Learnifier Get Organization Unit
  x-api-slug: learnifier
  description: |-
    Returns information about the specified organization unit.
    The response includes the display name, internal and external id and client number.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////orgunits/{orgid}
  tags: Organizations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/orgunitsorgid-get-openapi.md
- name: Learnifier Updates an Organization Unit
  x-api-slug: learnifier
  description: Adds an Organization Unit
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////orgunits/{orgid}
  tags: Organizations
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/orgunitsorgid-patch-openapi.md
- name: Learnifier Organization Unit Projects
  x-api-slug: learnifier
  description: Returns the available projects for the organization unit
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////orgunits/{orgid}/projects
  tags: Organizations,Projects
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/orgunitsorgidprojects-get-openapi.md
- name: Learnifier Create project
  x-api-slug: learnifier
  description: Creates a new project
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////orgunits/{orgid}/projects
  tags: Organizations,Projects
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/orgunitsorgidprojects-post-openapi.md
- name: Learnifier Deletes the project
  x-api-slug: learnifier
  description: Deletes the project. The project can only be deleted if the project
    do not contain any participants.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////orgunits/{orgid}/projects/{projectid}
  tags: Organizations,Projects,Projectid
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/orgunitsorgidprojectsprojectid-delete-openapi.md
- name: Learnifier Project information
  x-api-slug: learnifier
  description: Returns project information
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////orgunits/{orgid}/projects/{projectid}
  tags: Organizations,Projects,Projectid
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/orgunitsorgidprojectsprojectid-get-openapi.md
- name: Learnifier Update project information
  x-api-slug: learnifier
  description: Updates information about a project. Values are only updated if the
    fields are specified in the input
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////orgunits/{orgid}/projects/{projectid}
  tags: Organizations,Projects,Projectid
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/orgunitsorgidprojectsprojectid-patch-openapi.md
- name: Learnifier Project participants
  x-api-slug: learnifier
  description: Returns project participants
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////orgunits/{orgid}/projects/{projectid}/participants
  tags: Organizations,Projects,Projectid,Participants
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/orgunitsorgidprojectsprojectidparticipants-get-openapi.md
- name: Learnifier Add participant
  x-api-slug: learnifier
  description: Add a user to the project. Participant information is created for the
    user. In the body object, only one of either email or userid must be specified.
    The participant needs to be activated before it the user can access it.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////orgunits/{orgid}/projects/{projectid}/participants
  tags: Organizations,Projects,Projectid,Participants
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/orgunitsorgidprojectsprojectidparticipants-post-openapi.md
- name: Learnifier Deletes a participant
  x-api-slug: learnifier
  description: "Deletes a participant. The user itself will still remain but any state
    related to the project will be deleted. \nIt might not be possible due to constraints
    from the products in the project to delete the participant. However\nthis can
    only be determined at the time of the delete. If a delete fails the participant
    will have their inError\nflag set."
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////orgunits/{orgid}/projects/{projectid}/participants/${participantId}
  tags: Organizations,Projects,Projectid,Participants,$participantId
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/orgunitsorgidprojectsprojectidparticipantsparticipantid-delete-openapi.md
- name: Learnifier Activate participant
  x-api-slug: learnifier
  description: Activates a participant so that it can be used
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////orgunits/{orgid}/projects/{projectid}/participants/${participantId}/activate
  tags: Organizations,Projects,Projectid,Participants,$participantId,Activate
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/orgunitsorgidprojectsprojectidparticipantsparticipantidactivate-post-openapi.md
- name: Learnifier Participant login link
  x-api-slug: learnifier
  description: |-
    Returns a single sign on link for the participant. The link is only usable once and should be used directly. The link expires after a few minutes.

    This operation requires the *login link* permission.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////orgunits/{orgid}/projects/{projectid}/participants/${participantId}/loginlink
  tags: Organizations,Projects,Projectid,Participants,$participantId,Loginlink
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/orgunitsorgidprojectsprojectidparticipantsparticipantidloginlink-post-openapi.md
- name: Learnifier Project team members
  x-api-slug: learnifier
  description: Returns the project team members. A team member is a ....
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////orgunits/{orgid}/projects/{projectid}/teammembers
  tags: Organizations,Projects,Projectid,Team,Members
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/orgunitsorgidprojectsprojectidteammembers-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/orgunitsorgidprojectsprojectidteammembers-get-openapi.md
- name: Learnifier List User Groups.
  x-api-slug: learnifier
  description: Returns a list of User Groups for the org unit.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////orgunits/{orgid}/usergroups
  tags: Organizations,Users,Groups
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/orgunitsorgidusergroups-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/orgunitsorgidusergroups-get-openapi.md
- name: Learnifier Create a User Group.
  x-api-slug: learnifier
  description: Create a User Group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////orgunits/{orgid}/usergroups
  tags: Organizations,Users,Groups
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/orgunitsorgidusergroups-post-openapi.md
- name: Learnifier Get user group
  x-api-slug: learnifier
  description: Returns single User Group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////orgunits/{orgid}/usergroups/{groupid}
  tags: Organizations,Users,Groups,Groupid
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/orgunitsorgidusergroupsgroupid-get-openapi.md
- name: Learnifier List of all users in group.
  x-api-slug: learnifier
  description: Returns a list of all members in User Groups that are based on the
    Global Group with this groupid.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////orgunits/{orgid}/usergroups/{groupid}/members
  tags: Organizations,Uses,Groups,Members
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/orgunitsorgidusergroupsgroupidmembers-get-openapi.md
- name: Learnifier Add user group member.
  x-api-slug: learnifier
  description: Adds a user to user group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////orgunits/{orgid}/usergroups/{groupid}/members
  tags: Organizations,Uses,Groups,Members
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/orgunitsorgidusergroupsgroupidmembers-post-openapi.md
- name: Learnifier Remove user group member.
  x-api-slug: learnifier
  description: Removes a user from a user group.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////orgunits/{orgid}/usergroups/{groupid}/members/{uuid}
  tags: Organizations,Uses,Groups,Members
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/orgunitsorgidusergroupsgroupidmembersuuid-delete-openapi.md
- name: Learnifier Lists all users
  x-api-slug: learnifier
  description: Lists all users. Only api callers that have full access can call this
    method.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////users
  tags: Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/users-get-openapi.md
- name: Learnifier Adds a user
  x-api-slug: learnifier
  description: Adds a user. No two users can have the same email address. Email is
    saved WITH case but compared regardless of case. Email can be changed for a user
    assuming it doesn't cause a conflict.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////users
  tags: Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/users-post-openapi.md
- name: Learnifier User information
  x-api-slug: learnifier
  description: Returns information about a user
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////users/{userid}
  tags: Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/usersuserid-get-openapi.md
- name: Learnifier Updates user information
  x-api-slug: learnifier
  description: Updates a user. All values that have a key defined in the input will
    be set. So if a value should not be updated omit it totally from the input, otherwise
    it will be unset.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////users/{userid}
  tags: Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/usersuserid-patch-openapi.md
- name: Learnifier User profile picture
  x-api-slug: learnifier
  description: |-
    Returns a thumbnail picture of the user. This can either be a selected picture or an auto generated image. This method doesn't require a full sign in. The api key is sufficient.
    The image is square and is likely, but not necessary, to be in 128x128 PNG format. However the format will always be either PNG, JPEG or GIF.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////users/{userid}/pic?key={APIKEY}
  tags: Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/usersuseridpickeyapikey-get-openapi.md
- name: Learnifier Returns information about the projects the user is a participant
    in.
  x-api-slug: learnifier
  description: Returns information about the projects the user is a participant in.
    Only the projects that the current token have access to will be listed.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com////users/{userid}/projectParticipations
  tags: Users
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/usersuseridprojectparticipations-get-openapi.md
- name: Learnifier
  x-api-slug: learnifier
  description: Create your online courses in minutes. Learnifier is the fast and easy
    tool for creating and sharing great courses that work on your mobile, tablet and
    desktop. Book a DEMO or test it out with our FREE TRIAL.
  image: http://kinlane-productions.s3.amazonaws.com/screen-capture-api/28448-learnifier.jpg
  humanURL: http://learnifier.com
  baseURL: https://learnifier.com//
  tags: Learnifier
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/learnifier/master/_listings/learnifier/openapi.md
x-common:
- type: x-crunchbase
  url: https://crunchbase.com/organization/learnifier
- type: x-developer
  url: https://learnifier.com/api/
- type: x-email
  url: sales@learnifier.com
- type: x-email
  url: Abdalla.Mohamed@learnifier.com
- type: x-email
  url: support@learnifier.com
- type: x-email
  url: jerker.klang@learnifier.com
- type: x-email
  url: mattias.borg@learnifier.com
- type: x-email
  url: lars.peterstrand@learnifier.com
- type: x-email
  url: hello@learnifier.com
- type: x-email
  url: unsubscribe@learnifier.com
- type: x-email
  url: privacy@learnifier.com
- type: x-twitter
  url: https://twitter.com/Learnifier
- type: x-website
  url: http://learnifier.com
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---