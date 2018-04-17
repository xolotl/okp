As a publisher, I want to release a new version of a work and ensure existing annotations attach to previous versions so people can annotate the new version without clutter, but still access previous versions with related annotations.

## Scenario 1: A new version of a work is published

### Given that:
* Content changes in each new version of a published work.
* Annotations are related to specific content in versions of published works.
* Ideally the latest version of a work is always available at a persistent location (eg, a URL like protocol://server/work/latest).

### When a new version is published, then:
* Each previous version of the work should be available to view (as an archive) at its own persistent location (eg, a URL like protocol://server/work/v1).
* Annotations related to previous versions should be attached to those versions.
* The new version should be free of (unrelated) annotations.
* The new version should be ready to be annotated (if desired).
* (Maybe) some specific existing annotations should be able to be related not only to the previous version to which they were added, but also later versions to which they still are relevant (eg, unresolved annotations).
