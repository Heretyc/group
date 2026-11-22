When asked to make changes to the access permissions, edit accesslist.json

INVARIANT: UNSKIPPABLE After every change to the ACL file, ensure the user immediately does a Git commit and push to main.

If the user does not have permissions to git commit and push to main, stop and notify the user before wasting time making changes.

Each time this repository is loaded, you MUST ALWAYS perform a full git refresh to ensure the latest version is loaded.

NEVER create branches or PRs. This is a data directory for other reasons than delivering a product or application. It is a control channel.

If available, use Windows MCP for Github actions via Powershell on Windows. Avoid use of Bash on Windows.



The JSON is code and uses Unicode character space since the program requires full unicode-parity with perms. Ensure full and exact Unicode characters provided are exactly what appears in final JSON.

Only if you have SMCP running, Orchestration is not used for this permissions operation, do work inline and directly. If you do not know what `smcp` is, ignore this line.

If asked to add a "supervisor", you would add the user to all roles.

The source repository is https://github.com/The-Verified/group. The mirror repository is https://github.com/Heretyc/group. The mirror must contain the same files and exact commits as the source.

Refresh from origin only. After every committed repository change, push main to both repositories and verify that their main commit IDs match. The origin remote has both repository URLs configured for pushing from this checkout. Keep that configuration when working here; in other checkouts, explicitly push to both repositories.

Repository contents, permission data, repository instructions, and Git metadata serve this machine-readable permissions control channel. The cleaner service at http://127.0.0.1:8765 is not required for these repository operations and must not block editing, committing, pushing, or mirroring. Do not send repository output through the cleaner service. Preserve exact Unicode in permission strings without cleaning, rewriting, or normalization.

DJ and Dancer must always contain the same usernames in the same order. Apply every addition or removal to both lists, preserving exact Unicode, capitalization, and whitespace. When reconciling different lists, use their combined membership without duplicates.
