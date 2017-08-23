# Clubs

## What are clubs?
Clubs are groups of people that enjoy collecting cards of any type, a certain type, to sell on the market to earn a profit or just a group of friends.

**How many can I join?**  
You can join up to 5 clubs at any one time.

**How do I view a club?**  
Run `[]club [club-name]` *but that's just the start*.

**How do I join a club?**  
Run `[]cjoin [club-name]` - clubs with invites disabled require an admin or owner to invite you.

**How do I leave a club?**  
Run `[]cleave [club-name]`

**How do I view my own clubs?**  
Run `[]pclubs`. *Simples*

**How do I view someone else's clubs?**  
Run `[]pclubs @user`

## Making your own club
*This part is straight forward.*  
Run `[]ccreate [name]` *replace `[name]` with your chosen club name* and that's it.

**I don't want my club anymore.**  
There are two ways of giving your club up.
 1. Run `[]cleave` *only do this if you are certain that you want it removed*.
 2. Run `[]cgiveowner @user [club-name]` to transfer ownership of the club to another club member.

**How do I invite a user?**  
Run `[]cinv @user [club-name]`.

**How do I see what invites are still pending?**  
Run `[]cinvlist [club-name] <| [page]>` - the page is optional.

**How do I remove an invite?**  
Run `[]crinv @user [club-name]`

## Customizing your club

**How do I change the name of my club?**  
Run `[]ceditname [club-name] | [new-name]`

**How do I edit the description of my club?**  
Run `[]ceditdesc [club-name] | [desc]`

**How do I edit the club banner?**  
Goto the [banner editor](https://discord.cards/banner-edit) and choose your banner type, color, design and design color.  
In the `Club Name` field enter the club name of which you want to edit.  
Lastly, copy the command below your brand new banner and paste it into a channel that Discord Cards has access to. *Press enter of course.*

## Managing your club

**How do I view the member list?**  
Run `[]cmembers [club-name] <| [page]>` - the page is optional.

**How do I view the ban list?**
Run `[]cbanlist [club-name] <| [page]>` - the page is optional.

**How do I kick/ban/unban a member?**  
To kick a member, run `[]ckick @user [club-name]`.
To ban a member, run `[]cban @user [club-name]`.
To unban a member, run `[]cunban @user [club-name]`.

**What ranks are there for clubs and how do I set someones rank?**  

The available ranks are:
 - Owner
 - Admin
 - Member

You can set someone's role by using the following command:  
`[]crank [name] | @user [Admin|Member]` *not Owner, that's for `[]cgiveowner`*

**How can I set my club's settings?**  
Use `[]csetting [name] | [setting] <value>`  

#### BUT THERE'S MORE!!

#### Club Settings
- `displayColor` = Change the color that is used on the side of the embed.
- `baseName`, `designName`, `baseColor`, `designColor` = All of these properties decend from the banner editor *simple and short*.
- `open` = Toggle if players can join your club or not.
 - `yes` - open
 - `no` - closed


#### Commands

• []csetting
