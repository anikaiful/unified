@addtogroup experimental Experimental
@page experimental Readme
@ingroup experimental

Experimental functionality. Use this stuff at your own risk.

## Notes

The following environmental variable is required to load the plugin:

`NWNX_CORE_LOAD_EXPERIMENTAL_PLUGIN=y`

## Environment Variables

| Variable Name | Value | Notes |
| -------------   | :----: | ------------------------------------ |
| `NWNX_EXPERIMENTAL_SUPPRESS_PLAYER_LOGIN_INFO` | true/false | Suppresses the playerlist and player login/logout messages for all players except DMs. This functionality is not compatible with @ref rename "NWNX_Rename". |
| `NWNX_EXPERIMENTAL_REMOVE_ACAB_MODIFIERS_FROM_EXPERTISE` | true/false | Removes the AC and AB modifiers from Expertise. |