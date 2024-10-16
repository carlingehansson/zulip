# Manage user groups

{!user-groups-intro.md!}

## Create a user group

!!! tip ""

    You can modify the group's name, description, and other settings after it
    has been created.

{!how-to-create-a-user-group.md!}

## Change a user group's name or description

{start_tabs}

{tab|desktop-web}

{relative|group|all}

1. Select a user group.

1. Select the **General** tab on the right.

1. Click the **pencil** (<i class="fa fa-pencil"></i>) icon
   to the right of the user group, and enter a new name or description.

{!save-changes.md!}

{end_tabs}

## Configure who can mention a user group

{start_tabs}

{tab|desktop-web}

{relative|group|all}

1. Select a user group.

1. Select the **General** tab on the right.

1. Under **Group permissions**, configure **Who can mention this group**.

{!save-changes.md!}

{end_tabs}

## Add users to a user group

{start_tabs}

{tab|desktop-web}

{relative|group|all}

1. Select a user group.

1. Select the **Members** tab on the right.

1. Under **Add members**, enter a name or email address. The typeahead
   will only include users who aren't already members of the group.

1. Click **Add**. Zulip will notify everyone who is added to the group.

!!! tip ""

    To add users in bulk, you can copy members from an
    existing channel or user group.

{end_tabs}

## Remove users from a user group

{start_tabs}

{tab|desktop-web}

{relative|group|all}

1. Select a user group.

1. Select the **Members** tab on the right.

1. Under **Members**, find the user you would like to remove.

1. Click the **Remove** button in that row. Zulip will notify everyone who is
   removed from the group.

!!! warn ""

    **Note**: If you remove yourself from a user group, you
    may no longer have permission to modify the user group.

{end_tabs}

## Deactivate a user group

{start_tabs}

{tab|desktop-web}

{relative|group|all}

1. Select a user group.

1. Click the **Deactivate group** (<i class="fa fa-trash-o"></i>) button in the
   upper right corner of the user group settings panel.

1. Click **Confirm**.

{end_tabs}

## Configure who can create user groups

{!admin-only.md!}

By default, [all members](/help/roles-and-permissions) in a Zulip
organization can create user groups. However, you can restrict that
ability to specific [roles](/help/roles-and-permissions). Note that
guests cannot create user groups.

{start_tabs}

{tab|desktop-web}

{settings_tab|organization-permissions}

1. Under **Other permissions**, configure **Who can create user groups**.

{!save-changes.md!}

{end_tabs}

## Configure who can manage user groups

{!admin-only.md!}

By default, [owners](/help/roles-and-permissions) in a Zulip
organization can manage user groups. However, you can expand that
ability to specific [roles](/help/roles-and-permissions).

Guests cannot modify user groups.

{start_tabs}

{tab|desktop-web}

{settings_tab|organization-permissions}

1. Under **Other permissions**, configure **Who can manage user groups**.

{!save-changes.md!}

{end_tabs}

## Related articles

* [User groups](/help/user-groups)
* [Mention a user or group](/help/mention-a-user-or-group)
* [Create user groups](/help/create-user-groups)
* [Moving to Zulip](/help/moving-to-zulip)
* [Roles and permissions](/help/roles-and-permissions)
