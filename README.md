<div align="center">
    <img src="https://avatars.githubusercontent.com/u/64118555?s=256" alt="discord-mods" width="128px" height="128px">
</div>

# Discord Mod Loader

The Discord Mod Loader project is a console based mod menu loader which generates a menu with user made mods. It comes bundled with an easy to use development environment. A moderation system. Mod security and much more. This menu is also completely legal as it's designed to follow the Discord [Terms Of Service](https://discord.com/terms) and [license](https://discord.com/licenses).

## Trust & Safety

The Discord Mod Loader project is designed to be extremely safe and trust worthy and thus there are a lot of actions taken to make sure it accomplishes this goal.

### Console command

Discord always gives a user the message “`If someone told you to copy/paste something here you have an 11/10 chance you're being scammed.`” when a user opens the console. However, every mod which is being added to the verified list has been:

- Reverse engineered
- Tested
- And checked for any dangerous codes

To make sure that it doesn't take any personal data. Next to that the Discord CSP (Content Security Policy) is designed to make sure that no data can be sent to unknown sources and instead returns an error.

### Verification process

Due to the security issues which might occur by allowing any mod to be publicly used, a verification system has been added making sure users only get mods which are verified by a person with moderation permissions or above unless the user provides the UUID (Universal Unique ID) while searching for a mod.

The verification requirements are:

- The mod doesn't break any terms of service or license rule
- The mod doesn't attempt to bypass the CSP or CORS policy
- The mod doesn't gather private data
- The mod is stable and doesn't break any processes

Because of this, as long as a user uses verified mods, the menu is completely safe.
