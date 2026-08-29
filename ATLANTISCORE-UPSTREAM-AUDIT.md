# AtlantisCore upstream Playerbots audit branch

This branch preserves a reviewed set of independently authored fixes from open
upstream development work. It is an audit and integration candidate, not an
AtlantisCore release baseline and not evidence that the changes were accepted
upstream or validated together in production.

The original authorship retained by Git is intentional. Before selecting any
change for an AtlantisCore release, compare it with the current upstream pull
request, verify that it still applies to the chosen Playerbot core and module
revisions, build the complete server, and run focused runtime acceptance tests.

| Commit | Preserved topic |
| --- | --- |
| `9e98efe4` | Execute quest objectives while in the RPG quest state |
| `079773d3` | Initialize shared NPC-flag lists deterministically |
| `d0f33818` | Allow wandering bots to accept a nearby quest |
| `8144acc3` | Stop before casting an opening spell |
| `bb87a337` | Recover before starting another fight |
| `7379a138` | Guard chat dispatch during bot lifecycle transitions |
| `361c6b75` | Avoid repeated TravelNode teleport-node allocation |
| `ea8660a0` | Preserve PlayerbotAI lifetime for cached values |

No environment names, credentials, operational logs, or deployment topology
belong on this branch.
