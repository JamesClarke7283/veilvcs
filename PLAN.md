# Plan

All version control changes are stored in `.veil`.

- branches
- commits

## Commit Patch Format:
Commit ID [hash_id]
Parent Commit ID [hash_of_previous_commit]
Authors: [author1, author2] (optional field)
Message: [commit_message] (optional field)
```diff
Content here
```

Notes:
- Use Protobuf

## Branches

Protobuf File that points to a commit id.
