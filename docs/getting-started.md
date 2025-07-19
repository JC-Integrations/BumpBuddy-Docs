## Navigating

!> Do not literally type out `<` `>`

?> The user permissions required to run certain commands will be shown like <span class="user-permissions">this</span>.

Each category of commands has their own page which can be found on the sidebar.

| Syntax | Definition |
|-|-|
| <span class="parameter required">\<foo></span> | This argument is mandatory |
| <span class="parameter">\<foo></span> | This argument is optional |

## Bot Permissions

Bump Buddy requires some permissions to function correctly. Some are optional, depending on what you need.

| Permission | Required | Description |
|-|-|-|
| Manage Webhooks | <span class="green-background-text">Yes</span> | Used to set, update or remove the reminder channel. This allows Bump Buddy to create and delete webhooks in a channel. |
| View Channels | <span class="green-background-text">Yes</span> | Bump Buddy needs to access to the text channels in order to look for bumps. |
| Send Messages | <span class="green-background-text">Yes</span> | Bump Buddy needs to be able to send message. |
| Manage Messages | <span class="red-background-text">No</span> | This is used to delete reminder messages if autodelete is enabled. If you want to use autodelete, this permission will be needed. |
| Embed Links | <span class="green-background-text">Yes</span> | This allows Bump Buddy to send messages in an embed. |
| Read Message History | <span class="red-background-text">No</span> | This is used for fetchbump, if you want to use this command, you will need to give Bump Buddy this permission. |
| Mention @everyone, @here and All Roles | <span class="red-background-text">No</span> | If you want to have a reminder mention, then this is required, if the bump role isn't already allowed to be mentioned by everyone. |
| Add Reactions | <span class="red-background-text">No</span> | This allows Bump Buddy to add a stopwatch :stopwatch: reaction to detected bumps. |
