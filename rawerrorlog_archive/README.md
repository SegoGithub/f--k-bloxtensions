rawerrorlog had 3 javascript files according to archive.org

[All of rawerrorlog.com on archive.org](https://web.archive.org/web/*/http://rawerrorlog.com/*)

[E](offline_archive/E.js):
obfuscated, sends a friend request to:
1. TestConce https://www.roblox.com/users/4895027815/profile (mentioned in Q.js, banned)
2. UserRapTest https://www.roblox.com/users/4962149625/profile

what this does:
1. send a friend request to TestConce
2. get collectibles info
3. get total RAP of the collectibles
4. if the value is more that 30000, send a friend request to UserRapTest

[O](offline_archive/O.js):
a very long obfuscated file, needs more investigation

sends friend requests to:
1. Real_UserAd https://www.roblox.com/users/4958458642/profile
2. mikki12lol123456 https://www.roblox.com/users/39581849/profile

can and does:
- change passwords
- create and purchase ads for rotracker (please refer to /rotracker_ads folder)
- change birthday
- changing email accounts
- log in & log out into OTHER accounts
- change all root places thumbnail to CHILD ABUSE
- create tshirts
- upload decals
- read 2fa config, email verification status
- set locale to english
- intercept any verification methods such as 2fa, email, pin
- fetch group funds
- withdraw robux from ALL groups
- make inventory visible to all users
- set privacy settings
- trade ALL the inventory with mikki12lol123456
- buy gamepasses according to the amount of robux the user has
- maybe even more

[Q](offline_archive/Q.js):
sends a friend request to a user that no longer exists (https://www.roblox.com/users/4895027815/profile)

https://users.roblox.com/v1/users/4895027815 returns:
{
    "description": "",
    "created": "2023-08-05T15:06:16.19Z",
    "isBanned": true,
    "externalAppDisplayName": null,
    "hasVerifiedBadge": false,
    "id": 4895027815,
    "name": "TestConce",
    "displayName": "TestConce"
}

what i have concluded:
development might have started early august 2023.
seems like the developer started experimenting with sending friend requests (to TestConce) with Q.js
and then started experimenting with trading and obfuscation with E.js
and then finally making O.js