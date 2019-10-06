# Commit message format and conventions

## Commits

Commits MUST be "atomic". A single commit changes one thing and one thing only. Usually it is one of the following:

* adds a new onion service

* edits an onion service

* deletes an onion service

* tags existing onion service

* untags existing onion service

* changes meta information about the repository (i.e. README)

When adding multiple tags, it's fine to group this change in one commit as long as the tags point to same onion service.

When referring to a service, use the name specified in yaml file.

**All commits MUST be signed off with commiter's PGP key.**

## Commit prefixes

Each change uses different commit prefix. Prefixes help when reviewing changes, and also keep the git log concise.

### Meta

Use for repository related changes.

```
Meta: Initial commit
```

### Add

Use when adding a new onion service.

```
Add: The Service
```

### Edit

Use when editing existing onion service.

```
Edit: The Service
```

### Tag

Use when tagging an onion service.

```
Tag: The Service
```

### Untag

Use when untagging an onion service.

```
Untag: The Service
```

### Delete

Use when deleting an onion service.

```
Delete: The Service
```