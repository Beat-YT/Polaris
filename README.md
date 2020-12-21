# PolarisV2
They said to think back, but I think we went a bit too far.

This branch (**dev**) is the work-in-progress v1.1.0 codebase.

# Building
Add an __**SDK**__ (software development kit) to your Polaris instance. You can download the SDK for 1.8 [here](https://cdn.discordapp.com/attachments/764552370931630121/764552498526552084/SDK.zip)
You might need to fix your SDK the first time you set up the Polaris codebase by undefining PF_MAX in FN_CoreUObject_Classes.hpp.

# Libraries
| Library       | License       | Usage                                                     |
| ------------- | ------------- | --------------------------------------------------------- |
| MinHook       | BSD-2-Clause  | Used for hooking directly into Fortnite.                  |
| Dear ImGui    | MIT           | Used for the Polaris menu.                                |
| nlohmann/json | MIT           | Used for saving and loading Polaris Creation Files (pcf). |
