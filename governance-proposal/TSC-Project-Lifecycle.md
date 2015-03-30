## ***DRAFT for Public Comment***

# Node.js Foundation Project Lifecycle

## Project Definition

A *project* is an autonomous group collaborating to achieve a set of responsibilities.

A project could be a working group collaborating with multiple groups both inside and outside the foundation but with no specific code base of its own to be released. A project could also be a traditional module or set of modules released regularly. This document draws no distinction between what are traditionally referred to as "working groups" or "committees" and traditional software projects.

## Lifecycle

Node.js Foundation’s technical Projects shall follow a lifecycle described in this Project Lifecycle document.  

The TSC shall encourage new Projects and innovation in the technical community. New Projects enter the Node.js technical community through a Proposal to the TSC or through the Bootstrap process.

## Bootstrap and Proposal

Before a project is chartered it must first incubate in some manner.

If a project needs to start *in* the foundation members are free to create a repository and begin regular meetings using the free tools available to all project members. During this period the project is unchartered and in the "Bootstrap" cycle and is not entitled to any financial or legal resources of the foundation and can be closed at any time by the TSC. Once the project matures and is ready to write a proposal that is sent to the TSC for approval and the project moves to the "Mature" phase once approved.

It is also common for projects to incubate and mature outside the foundation. These projects do not need to incubate within the foundation itself and instead should write a proposal for the TSC to approve and move directly to the "Mature" pahse.

Projects shall change state following TSC reviews. Projects typically change states independently from each other, but can cooperate closely and leverage each other’s results. Projects graduate from Proposal-state, through Incubation-state and Mature-state to Core-state. Archived–state is a Project state reserved for those Projects no longer being actively developed or used by the community.

| Project state |	Description |
| ------------- | ----------- |
| Incubation | Project has not been approved and is unchartered. Project does not formally exist yet, may not have real resources (yet), but is being worked on by the community. |
| Proposal | Project proposal is posted and under review. |
| Mature | Project is fully functioning but is not a required component of the platform.|
| Core | Project is a required component of the Node.js platform.|
| Archived | Project has been recognized as no longer being actively used or developed. This could be for a variety of reasons, e.g. project successfully accomplished its goals but is no longer used, project failed, etc., and has been archived as it's no longer a going concern.|

### Project state transitions

| From State | To State | Review |
| ---------- | -------- | ------ |
| Proposal | Mature | Proposal Review |
| Mature | Core | Core Review |
| Proposal, Bootstrap, Mature, Core | Archived | Archive Review |

## Reviews

### Proposal Review
* Proposal posted for two weeks, evaluated on metrics of:
 * Name is okay (e.g. no use of a trademark)
 * Project contact name, email and/or repo.
 * Description is complete
 * Scope and project plan is well defined
 * Resources are well defined
 * Initial members named
 * Initial contributors named
 * Meets Foundation’s policies (e.g. IP Policy)
 * Proposal has been socialized with potentially interested or affected existing Projects
 * The Project demonstrates stable output (e.g. code base, documents, tests, meetings, releases)
 * Active community working on the Project
 * History of successful
* TSC review
 * Working and stable community and output.
 * Confirmed acceptance and successful integration of contributions/code to partner/upstream projects when applicable.
 * Testing/integration environment defined and mature, tests and integration run successfully when applicable.
 * Well defined project documentation: contribution, governance, membership, and conduct policies in place.

### Core Review
 * Core-state proposal posted for two weeks
   * Project is shown to be a viable and necessary subsystem or component of the Node.js Platform.
   * Project build and test scripts have been created to work with the rest of the Node.js Platform.
   * Project shown to not break continuous development and integration environment.
 * TSC review metrics
   * Core review assesses projects based on the metrics of the graduation review and the necessity of the project relative to the codebase and user requirements.
   * In addition the project is required to have confirmed longevity (e.g. the project has been active for at least one year, participates in release activities, and has release plans outlined to stay active for at least another year).

### Termination Review
* Termination proposal posted for two weeks
 * States reason for project termination being sought
   * Termination proposal to include acceptable triggers for termination
   * (e.g. protracted idleness, or request by the project)
 * Estimates impact on other projects and how to mitigate
 * Impact and possible breakage to APIs or builds
 * Location identified and links created for archived project
* If Archival is not approved, the Project remains in its pre-reviewed state
