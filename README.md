# Roblox Client Tracker

| Metadata | Details |
| :--- | :--- |
| **Version** | `0.744.0.7441077` |
| **Version Hash** | `version-7aaa6838d36c4448` |
| **Official Release Notes** | [Release Notes 744](https://create.roblox.com/docs/release-notes/release-notes-744) |

---

## Changelog

* Added Class [AppHandle](https://create.roblox.com/docs/reference/engine/classes/AppHandle) {🔒None} [⬆️Extends: Object] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Function [AppHandle.Call](https://create.roblox.com/docs/reference/engine/classes/AppHandle#Call) {🚧InternalTest}
  * Added Function [AppHandle.Close](https://create.roblox.com/docs/reference/engine/classes/AppHandle#Close) {🚧InternalTest}
  * Added Function [AppHandle.ExecuteLuau](https://create.roblox.com/docs/reference/engine/classes/AppHandle#ExecuteLuau) {🚧InternalTest}
  * Added Function [AppHandle.RunTest](https://create.roblox.com/docs/reference/engine/classes/AppHandle#RunTest) {🚧InternalTest}
* Update Class [AnimatedImageService](https://create.roblox.com/docs/reference/engine/classes/AnimatedImageService) [⬆️Extends: Instance] [🧠Memory: Gui] [🏷️ NotCreatable] [🏷️ Service]
  * Removed Property AnimatedImageService.UserCreatedTracks
* Update Class [AnimationPlayer](https://create.roblox.com/docs/reference/engine/classes/AnimationPlayer) [⬆️Extends: Instance] [🧠Memory: Gui]
  * Changed the serialization of Property [AnimationPlayer.AnimationContent](https://create.roblox.com/docs/reference/engine/classes/AnimationPlayer#AnimationContent)
    from: [🚫None]
    to: [💾|📁Serialized]
  * Changed the serialization of Property [AnimationPlayer.AutoPlay](https://create.roblox.com/docs/reference/engine/classes/AnimationPlayer#AutoPlay)
    from: [🚫None]
    to: [💾|📁Serialized]
  * Changed the serialization of Property [AnimationPlayer.Enabled](https://create.roblox.com/docs/reference/engine/classes/AnimationPlayer#Enabled)
    from: [🚫None]
    to: [💾|📁Serialized]
  * Changed the serialization of Property [AnimationPlayer.IsPlaying](https://create.roblox.com/docs/reference/engine/classes/AnimationPlayer#IsPlaying)
    from: [🚫None]
    to: [💾SaveOnly]
  * Changed the serialization of Property [AnimationPlayer.Loop](https://create.roblox.com/docs/reference/engine/classes/AnimationPlayer#Loop)
    from: [🚫None]
    to: [💾|📁Serialized]
  * Changed the serialization of Property [AnimationPlayer.Speed](https://create.roblox.com/docs/reference/engine/classes/AnimationPlayer#Speed)
    from: [🚫None]
    to: [💾|📁Serialized]
  * Changed the serialization of Property [AnimationPlayer.Track](https://create.roblox.com/docs/reference/engine/classes/AnimationPlayer#Track)
    from: [📁LoadOnly]
    to: [💾|📁Serialized]
* Update Class [AudioSearchParams](https://create.roblox.com/docs/reference/engine/classes/AudioSearchParams) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotReplicated]
  * Added Property [AudioSearchParams.MaxPageSize](https://create.roblox.com/docs/reference/engine/classes/AudioSearchParams#MaxPageSize): int {🚧Read: AssetRead | Write: AssetRead} [⚡ThreadSafety: ReadSafe]
  * Added Property [AudioSearchParams.SortType](https://create.roblox.com/docs/reference/engine/classes/AudioSearchParams#SortType): AudioSortType {🚧Read: AssetRead | Write: AssetRead} [⚡ThreadSafety: ReadSafe]
* Update Class [AvatarAccessoryRules](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the security of Property [AvatarAccessoryRules.AccessoryMode](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#AccessoryMode)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarAccessoryRules.AccessoryMode](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#AccessoryMode)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarAccessoryRules.BackAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#BackAccessoryOverride)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarAccessoryRules.BackAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#BackAccessoryOverride)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAccessoryRules.CustomAccessoryMode](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#CustomAccessoryMode)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAccessoryRules.CustomBackAccessoryEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#CustomBackAccessoryEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAccessoryRules.CustomBackAccessoryId](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#CustomBackAccessoryId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAccessoryRules.CustomFaceAccessoryEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#CustomFaceAccessoryEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAccessoryRules.CustomFaceAccessoryId](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#CustomFaceAccessoryId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAccessoryRules.CustomFrontAccessoryEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#CustomFrontAccessoryEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAccessoryRules.CustomFrontAccessoryId](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#CustomFrontAccessoryId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAccessoryRules.CustomHairAccessoryEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#CustomHairAccessoryEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAccessoryRules.CustomHairAccessoryId](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#CustomHairAccessoryId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAccessoryRules.CustomHeadAccessoryEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#CustomHeadAccessoryEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAccessoryRules.CustomHeadAccessoryId](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#CustomHeadAccessoryId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAccessoryRules.CustomNeckAccessoryEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#CustomNeckAccessoryEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAccessoryRules.CustomNeckAccessoryId](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#CustomNeckAccessoryId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAccessoryRules.CustomShoulderAccessoryEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#CustomShoulderAccessoryEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAccessoryRules.CustomShoulderAccessoryId](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#CustomShoulderAccessoryId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAccessoryRules.CustomWaistAccessoryEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#CustomWaistAccessoryEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAccessoryRules.CustomWaistAccessoryId](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#CustomWaistAccessoryId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarAccessoryRules.EnableEmissives](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#EnableEmissives)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarAccessoryRules.EnableEmissives](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#EnableEmissives)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarAccessoryRules.EnableSound](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#EnableSound)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarAccessoryRules.EnableSound](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#EnableSound)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarAccessoryRules.EnableVFX](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#EnableVFX)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarAccessoryRules.EnableVFX](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#EnableVFX)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarAccessoryRules.FaceAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#FaceAccessoryOverride)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarAccessoryRules.FaceAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#FaceAccessoryOverride)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarAccessoryRules.FrontAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#FrontAccessoryOverride)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarAccessoryRules.FrontAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#FrontAccessoryOverride)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarAccessoryRules.HairAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#HairAccessoryOverride)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarAccessoryRules.HairAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#HairAccessoryOverride)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarAccessoryRules.HeadAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#HeadAccessoryOverride)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarAccessoryRules.HeadAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#HeadAccessoryOverride)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarAccessoryRules.LimitBounds](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#LimitBounds)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarAccessoryRules.LimitBounds](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#LimitBounds)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarAccessoryRules.LimitMethod](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#LimitMethod)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarAccessoryRules.LimitMethod](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#LimitMethod)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarAccessoryRules.NeckAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#NeckAccessoryOverride)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarAccessoryRules.NeckAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#NeckAccessoryOverride)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarAccessoryRules.ShoulderAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#ShoulderAccessoryOverride)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarAccessoryRules.ShoulderAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#ShoulderAccessoryOverride)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarAccessoryRules.WaistAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#WaistAccessoryOverride)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarAccessoryRules.WaistAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#WaistAccessoryOverride)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Function [AvatarAccessoryRules.willRemoveAccessory](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#willRemoveAccessory)
    from: {🚧None}
    to: {🚧AvatarAppearance}
* Update Class [AvatarAnimationRules](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the capabilities of Property [AvatarAnimationRules.AnimationClipsMode](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#AnimationClipsMode)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarAnimationRules.AnimationPacksMode](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#AnimationPacksMode)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarAnimationRules.AnimationPacksMode](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#AnimationPacksMode)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarAnimationRules.ClimbAnimationOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#ClimbAnimationOverride)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarAnimationRules.ClimbAnimationOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#ClimbAnimationOverride)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAnimationRules.CustomClimbAnimationEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#CustomClimbAnimationEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAnimationRules.CustomClimbAnimationId](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#CustomClimbAnimationId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAnimationRules.CustomFallAnimationEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#CustomFallAnimationEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAnimationRules.CustomFallAnimationId](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#CustomFallAnimationId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAnimationRules.CustomIdleAlt1AnimationEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#CustomIdleAlt1AnimationEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAnimationRules.CustomIdleAlt1AnimationId](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#CustomIdleAlt1AnimationId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAnimationRules.CustomIdleAlt2AnimationEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#CustomIdleAlt2AnimationEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAnimationRules.CustomIdleAlt2AnimationId](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#CustomIdleAlt2AnimationId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAnimationRules.CustomIdleAnimationEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#CustomIdleAnimationEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAnimationRules.CustomIdleAnimationId](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#CustomIdleAnimationId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAnimationRules.CustomJumpAnimationEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#CustomJumpAnimationEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAnimationRules.CustomJumpAnimationId](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#CustomJumpAnimationId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAnimationRules.CustomRunAnimationEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#CustomRunAnimationEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAnimationRules.CustomRunAnimationId](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#CustomRunAnimationId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAnimationRules.CustomSwimAnimationEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#CustomSwimAnimationEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAnimationRules.CustomSwimAnimationId](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#CustomSwimAnimationId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAnimationRules.CustomSwimIdleAnimationEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#CustomSwimIdleAnimationEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAnimationRules.CustomSwimIdleAnimationId](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#CustomSwimIdleAnimationId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAnimationRules.CustomWalkAnimationEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#CustomWalkAnimationEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarAnimationRules.CustomWalkAnimationId](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#CustomWalkAnimationId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarAnimationRules.FallAnimationOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#FallAnimationOverride)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarAnimationRules.FallAnimationOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#FallAnimationOverride)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarAnimationRules.IdleAltAnimationOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#IdleAltAnimationOverride)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarAnimationRules.IdleAltAnimationOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#IdleAltAnimationOverride)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarAnimationRules.IdleAnimationOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#IdleAnimationOverride)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarAnimationRules.IdleAnimationOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#IdleAnimationOverride)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarAnimationRules.JumpAnimationOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#JumpAnimationOverride)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarAnimationRules.JumpAnimationOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#JumpAnimationOverride)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarAnimationRules.MoodAnimationOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#MoodAnimationOverride)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarAnimationRules.MoodAnimationOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#MoodAnimationOverride)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarAnimationRules.RunAnimationOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#RunAnimationOverride)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarAnimationRules.RunAnimationOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#RunAnimationOverride)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarAnimationRules.SwimAnimationOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#SwimAnimationOverride)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarAnimationRules.SwimAnimationOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#SwimAnimationOverride)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarAnimationRules.SwimIdleAnimationOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#SwimIdleAnimationOverride)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarAnimationRules.SwimIdleAnimationOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#SwimIdleAnimationOverride)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarAnimationRules.WalkAnimationOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#WalkAnimationOverride)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarAnimationRules.WalkAnimationOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#WalkAnimationOverride)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
* Update Class [AvatarBodyRules](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the capabilities of Property [AvatarBodyRules.AppearanceMode](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#AppearanceMode)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarBodyRules.AvatarType](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#AvatarType)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarBodyRules.AvatarType](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#AvatarType)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarBodyRules.BuildMode](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#BuildMode)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarBodyRules.BuildMode](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#BuildMode)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarBodyRules.CustomBodyBundleId](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomBodyBundleId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarBodyRules.CustomBodyType](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomBodyType)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarBodyRules.CustomBodyTypeScale](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomBodyTypeScale)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarBodyRules.CustomBuildBodyType](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomBuildBodyType)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarBodyRules.CustomBuildBodyType](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomBuildBodyType)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarBodyRules.CustomBuildHead](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomBuildHead)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarBodyRules.CustomBuildHead](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomBuildHead)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarBodyRules.CustomBuildHeight](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomBuildHeight)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarBodyRules.CustomBuildHeight](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomBuildHeight)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarBodyRules.CustomBuildProportions](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomBuildProportions)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarBodyRules.CustomBuildProportions](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomBuildProportions)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarBodyRules.CustomBuildWidth](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomBuildWidth)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarBodyRules.CustomBuildWidth](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomBuildWidth)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarBodyRules.CustomEyebrowEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomEyebrowEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarBodyRules.CustomEyebrowId](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomEyebrowId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarBodyRules.CustomEyelashEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomEyelashEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarBodyRules.CustomEyelashId](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomEyelashId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarBodyRules.CustomFaceEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomFaceEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarBodyRules.CustomFaceId](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomFaceId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarBodyRules.CustomHeadEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomHeadEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarBodyRules.CustomHeadId](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomHeadId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarBodyRules.CustomHeadScale](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomHeadScale)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarBodyRules.CustomHeight](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomHeight)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarBodyRules.CustomHeightScale](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomHeightScale)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarBodyRules.CustomLeftArmEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomLeftArmEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarBodyRules.CustomLeftArmId](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomLeftArmId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarBodyRules.CustomLeftLegEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomLeftLegEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarBodyRules.CustomLeftLegId](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomLeftLegId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarBodyRules.CustomMoodEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomMoodEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarBodyRules.CustomMoodId](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomMoodId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarBodyRules.CustomProportionsScale](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomProportionsScale)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarBodyRules.CustomRightArmEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomRightArmEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarBodyRules.CustomRightArmId](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomRightArmId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarBodyRules.CustomRightLegEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomRightLegEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarBodyRules.CustomRightLegId](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomRightLegId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarBodyRules.CustomTorsoEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomTorsoEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarBodyRules.CustomTorsoId](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomTorsoId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarBodyRules.CustomWidthScale](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomWidthScale)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarBodyRules.CustomWorldHeight](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomWorldHeight)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarBodyRules.CustomWorldHeight](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomWorldHeight)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarBodyRules.HeadOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#HeadOverride)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarBodyRules.HeadOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#HeadOverride)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarBodyRules.KeepPlayerHead](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#KeepPlayerHead)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarBodyRules.LeftArmOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#LeftArmOverride)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarBodyRules.LeftArmOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#LeftArmOverride)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarBodyRules.LeftLegOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#LeftLegOverride)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarBodyRules.LeftLegOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#LeftLegOverride)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarBodyRules.RightArmOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#RightArmOverride)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarBodyRules.RightArmOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#RightArmOverride)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarBodyRules.RightLegOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#RightLegOverride)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarBodyRules.RightLegOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#RightLegOverride)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarBodyRules.ScaleMode](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#ScaleMode)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarBodyRules.ScaleMode](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#ScaleMode)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarBodyRules.TorsoOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#TorsoOverride)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarBodyRules.TorsoOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#TorsoOverride)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
* Update Class [AvatarClothingRules](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the security of Property [AvatarClothingRules.ClassicPantsAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#ClassicPantsAccessoryOverride)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarClothingRules.ClassicPantsAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#ClassicPantsAccessoryOverride)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarClothingRules.ClassicShirtsAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#ClassicShirtsAccessoryOverride)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarClothingRules.ClassicShirtsAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#ClassicShirtsAccessoryOverride)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarClothingRules.ClassicTShirtsAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#ClassicTShirtsAccessoryOverride)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarClothingRules.ClassicTShirtsAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#ClassicTShirtsAccessoryOverride)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarClothingRules.ClothingMode](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#ClothingMode)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarClothingRules.ClothingMode](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#ClothingMode)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarClothingRules.CustomClassicPantsAccessoryEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#CustomClassicPantsAccessoryEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarClothingRules.CustomClassicPantsAccessoryId](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#CustomClassicPantsAccessoryId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarClothingRules.CustomClassicShirtsAccessoryEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#CustomClassicShirtsAccessoryEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarClothingRules.CustomClassicShirtsAccessoryId](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#CustomClassicShirtsAccessoryId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarClothingRules.CustomClassicTShirtsAccessoryEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#CustomClassicTShirtsAccessoryEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarClothingRules.CustomClassicTShirtsAccessoryId](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#CustomClassicTShirtsAccessoryId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarClothingRules.CustomClothingMode](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#CustomClothingMode)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarClothingRules.CustomDressSkirtAccessoryEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#CustomDressSkirtAccessoryEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarClothingRules.CustomDressSkirtAccessoryId](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#CustomDressSkirtAccessoryId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarClothingRules.CustomJacketAccessoryEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#CustomJacketAccessoryEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarClothingRules.CustomJacketAccessoryId](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#CustomJacketAccessoryId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarClothingRules.CustomLeftShoesAccessoryEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#CustomLeftShoesAccessoryEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarClothingRules.CustomLeftShoesAccessoryId](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#CustomLeftShoesAccessoryId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarClothingRules.CustomPantsAccessoryEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#CustomPantsAccessoryEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarClothingRules.CustomPantsAccessoryId](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#CustomPantsAccessoryId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarClothingRules.CustomRightShoesAccessoryEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#CustomRightShoesAccessoryEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarClothingRules.CustomRightShoesAccessoryId](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#CustomRightShoesAccessoryId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarClothingRules.CustomShirtAccessoryEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#CustomShirtAccessoryEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarClothingRules.CustomShirtAccessoryId](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#CustomShirtAccessoryId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarClothingRules.CustomShortsAccessoryEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#CustomShortsAccessoryEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarClothingRules.CustomShortsAccessoryId](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#CustomShortsAccessoryId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarClothingRules.CustomSweaterAccessoryEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#CustomSweaterAccessoryEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarClothingRules.CustomSweaterAccessoryId](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#CustomSweaterAccessoryId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarClothingRules.CustomTShirtAccessoryEnabled](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#CustomTShirtAccessoryEnabled)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarClothingRules.CustomTShirtAccessoryId](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#CustomTShirtAccessoryId)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarClothingRules.DressSkirtAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#DressSkirtAccessoryOverride)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarClothingRules.DressSkirtAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#DressSkirtAccessoryOverride)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarClothingRules.JacketAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#JacketAccessoryOverride)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarClothingRules.JacketAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#JacketAccessoryOverride)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarClothingRules.LeftShoesAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#LeftShoesAccessoryOverride)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarClothingRules.LeftShoesAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#LeftShoesAccessoryOverride)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarClothingRules.LimitBounds](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#LimitBounds)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarClothingRules.LimitBounds](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#LimitBounds)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarClothingRules.PantsAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#PantsAccessoryOverride)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarClothingRules.PantsAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#PantsAccessoryOverride)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarClothingRules.RightShoesAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#RightShoesAccessoryOverride)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarClothingRules.RightShoesAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#RightShoesAccessoryOverride)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarClothingRules.ShirtAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#ShirtAccessoryOverride)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarClothingRules.ShirtAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#ShirtAccessoryOverride)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarClothingRules.ShortsAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#ShortsAccessoryOverride)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarClothingRules.ShortsAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#ShortsAccessoryOverride)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarClothingRules.SweaterAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#SweaterAccessoryOverride)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarClothingRules.SweaterAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#SweaterAccessoryOverride)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarClothingRules.TShirtAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#TShirtAccessoryOverride)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarClothingRules.TShirtAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#TShirtAccessoryOverride)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Function [AvatarClothingRules.WillLimitLayeredAccessoryAsync](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#WillLimitLayeredAccessoryAsync)
    from: {🚧None}
    to: {🚧AvatarAppearance}
* Update Class [AvatarCollisionRules](https://create.roblox.com/docs/reference/engine/classes/AvatarCollisionRules) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the security of Property [AvatarCollisionRules.CollisionMode](https://create.roblox.com/docs/reference/engine/classes/AvatarCollisionRules#CollisionMode)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarCollisionRules.CollisionMode](https://create.roblox.com/docs/reference/engine/classes/AvatarCollisionRules#CollisionMode)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarCollisionRules.HitAndTouchDetectionMode](https://create.roblox.com/docs/reference/engine/classes/AvatarCollisionRules#HitAndTouchDetectionMode)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarCollisionRules.HitAndTouchDetectionMode](https://create.roblox.com/docs/reference/engine/classes/AvatarCollisionRules#HitAndTouchDetectionMode)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the capabilities of Property [AvatarCollisionRules.LegacyCollisionMode](https://create.roblox.com/docs/reference/engine/classes/AvatarCollisionRules#LegacyCollisionMode)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
  * Changed the security of Property [AvatarCollisionRules.SingleColliderSize](https://create.roblox.com/docs/reference/engine/classes/AvatarCollisionRules#SingleColliderSize)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AvatarCollisionRules.SingleColliderSize](https://create.roblox.com/docs/reference/engine/classes/AvatarCollisionRules#SingleColliderSize)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
* Update Class [AvatarRules](https://create.roblox.com/docs/reference/engine/classes/AvatarRules) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the capabilities of Property [AvatarRules.AvatarType](https://create.roblox.com/docs/reference/engine/classes/AvatarRules#AvatarType)
    from: {🚧None}
    to: {🚧Read: AvatarAppearance}
* Update Class [WrapLayer](https://create.roblox.com/docs/reference/engine/classes/WrapLayer) [⬆️Extends: BaseWrap] [🧠Memory: Instances]
  * Added Property [WrapLayer.RotateScaleDeformationMap](https://create.roblox.com/docs/reference/engine/classes/WrapLayer#RotateScaleDeformationMap): Content {🚧Read: AvatarAppearance} [⚡ThreadSafety: ReadSafe]
  * Added Property [WrapLayer.ScaleOnlyDeformationMap](https://create.roblox.com/docs/reference/engine/classes/WrapLayer#ScaleOnlyDeformationMap): Content {🚧Read: AvatarAppearance} [⚡ThreadSafety: ReadSafe]
  * Added Property [WrapLayer.TargetShaping](https://create.roblox.com/docs/reference/engine/classes/WrapLayer#TargetShaping): float {🚧Read: AvatarAppearance} [⚡ThreadSafety: ReadSafe]
* Update Class [CallingService](https://create.roblox.com/docs/reference/engine/classes/CallingService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [CallingService.ReceiveIncomingCall](https://create.roblox.com/docs/reference/engine/classes/CallingService#ReceiveIncomingCall) (pushPayloadJson: string) -> null
* Added Class [CloudClientService](https://create.roblox.com/docs/reference/engine/classes/CloudClientService) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
* Update Class [CollectionService](https://create.roblox.com/docs/reference/engine/classes/CollectionService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [CollectionService.GetCollections](https://create.roblox.com/docs/reference/engine/classes/CollectionService#GetCollections) (instance: Instance) -> Array {🚧Basic}
* Update Class [ContextActionService](https://create.roblox.com/docs/reference/engine/classes/ContextActionService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Event [ContextActionService.OpenInputActionManagerSignal](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#OpenInputActionManagerSignal) {🚧Input}
* Update Class [ControlState](https://create.roblox.com/docs/reference/engine/classes/ControlState) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotBrowsable]
  * Added Function [ControlState.HasField](https://create.roblox.com/docs/reference/engine/classes/ControlState#HasField) (name: string) -> bool [🏷️ NotBrowsable]
* Update Class [ExperienceService](https://create.roblox.com/docs/reference/engine/classes/ExperienceService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [ExperienceService.IsInExperience](https://create.roblox.com/docs/reference/engine/classes/ExperienceService#IsInExperience) () -> bool
* Update Class [BoxHandleAdornment](https://create.roblox.com/docs/reference/engine/classes/BoxHandleAdornment) [⬆️Extends: HandleAdornment] [🧠Memory: Instances]
  * Added Property [BoxHandleAdornment.DoubleSided](https://create.roblox.com/docs/reference/engine/classes/BoxHandleAdornment#DoubleSided): bool [🏷️ Hidden] {🚧Read: Basic, UI} [⚡ThreadSafety: ReadSafe]
* Update Class [ConeHandleAdornment](https://create.roblox.com/docs/reference/engine/classes/ConeHandleAdornment) [⬆️Extends: HandleAdornment] [🧠Memory: Instances]
  * Added Property [ConeHandleAdornment.DoubleSided](https://create.roblox.com/docs/reference/engine/classes/ConeHandleAdornment#DoubleSided): bool [🏷️ Hidden] {🚧Read: Basic, UI} [⚡ThreadSafety: ReadSafe]
* Update Class [CylinderHandleAdornment](https://create.roblox.com/docs/reference/engine/classes/CylinderHandleAdornment) [⬆️Extends: HandleAdornment] [🧠Memory: Instances]
  * Added Property [CylinderHandleAdornment.DoubleSided](https://create.roblox.com/docs/reference/engine/classes/CylinderHandleAdornment#DoubleSided): bool [🏷️ Hidden] {🚧Read: Basic, UI} [⚡ThreadSafety: ReadSafe]
* Update Class [ImageHandleAdornment](https://create.roblox.com/docs/reference/engine/classes/ImageHandleAdornment) [⬆️Extends: HandleAdornment] [🧠Memory: Instances]
  * Added Property [ImageHandleAdornment.DoubleSided](https://create.roblox.com/docs/reference/engine/classes/ImageHandleAdornment#DoubleSided): bool [🏷️ Hidden] {🚧Read: Basic, UI} [⚡ThreadSafety: ReadSafe]
* Update Class [PyramidHandleAdornment](https://create.roblox.com/docs/reference/engine/classes/PyramidHandleAdornment) [⬆️Extends: HandleAdornment] [🧠Memory: Instances]
  * Added Property [PyramidHandleAdornment.DoubleSided](https://create.roblox.com/docs/reference/engine/classes/PyramidHandleAdornment#DoubleSided): bool [🏷️ Hidden] {🚧Read: Basic, UI} [⚡ThreadSafety: ReadSafe]
* Update Class [SphereHandleAdornment](https://create.roblox.com/docs/reference/engine/classes/SphereHandleAdornment) [⬆️Extends: HandleAdornment] [🧠Memory: Instances]
  * Added Property [SphereHandleAdornment.DoubleSided](https://create.roblox.com/docs/reference/engine/classes/SphereHandleAdornment#DoubleSided): bool [🏷️ Hidden] {🚧Read: Basic, UI} [⚡ThreadSafety: ReadSafe]
* Update Class [Humanoid](https://create.roblox.com/docs/reference/engine/classes/Humanoid) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the parameters of Function [Humanoid.ApplyAvatarRules](https://create.roblox.com/docs/reference/engine/classes/Humanoid#ApplyAvatarRules)
    from: (avatarRules: AvatarRules)
    to: (avatarRules: Variant)
  * Changed the parameters of Function [Humanoid.ApplyAvatarRulesAsync](https://create.roblox.com/docs/reference/engine/classes/Humanoid#ApplyAvatarRulesAsync)
    from: (avatarRules: AvatarRules)
    to: (avatarRules: Variant)
  * Changed the security of Function [Humanoid.ApplyAvatarRulesAsync](https://create.roblox.com/docs/reference/engine/classes/Humanoid#ApplyAvatarRulesAsync)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Function [Humanoid.ApplyAvatarRulesAsync](https://create.roblox.com/docs/reference/engine/classes/Humanoid#ApplyAvatarRulesAsync)
    from: {🚧None}
    to: {🚧AvatarAppearance}
* Update Class [InputAction](https://create.roblox.com/docs/reference/engine/classes/InputAction) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Property [InputAction.Editor](https://create.roblox.com/docs/reference/engine/classes/InputAction#Editor): bool [🏷️ NotReplicated] [🏷️ NotScriptable] {🚧Read: Input} [⚡ThreadSafety: ReadSafe]
* Update Class [InputBinding](https://create.roblox.com/docs/reference/engine/classes/InputBinding) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Property [InputBinding.Editor](https://create.roblox.com/docs/reference/engine/classes/InputBinding#Editor): bool [🏷️ NotReplicated] [🏷️ NotScriptable] {🚧Read: Input} [⚡ThreadSafety: ReadSafe]
* Update Class [InputContext](https://create.roblox.com/docs/reference/engine/classes/InputContext) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Property [InputContext.Editor](https://create.roblox.com/docs/reference/engine/classes/InputContext#Editor): bool [🏷️ NotReplicated] [🏷️ NotScriptable] {🚧Read: Input} [⚡ThreadSafety: ReadSafe]
* Update Class [LinkingService](https://create.roblox.com/docs/reference/engine/classes/LinkingService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [LinkingService.CreateInternalDlic](https://create.roblox.com/docs/reference/engine/classes/LinkingService#CreateInternalDlic) (url: string, source: string) -> string?
  * Added Function [LinkingService.DetectDlic](https://create.roblox.com/docs/reference/engine/classes/LinkingService#DetectDlic) (deeplinkId: string) -> null
* Update Class [NotificationService](https://create.roblox.com/docs/reference/engine/classes/NotificationService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Event [NotificationService.TopicSubscriptionError](https://create.roblox.com/docs/reference/engine/classes/NotificationService#TopicSubscriptionError) {🚧Players}
  * Added Event [NotificationService.TopicTokenExpiry](https://create.roblox.com/docs/reference/engine/classes/NotificationService#TopicTokenExpiry) {🚧Players}
* Update Class [Player](https://create.roblox.com/docs/reference/engine/classes/Player) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the parameters of Function [Player.LoadCharacterWithAvatarRulesAsync](https://create.roblox.com/docs/reference/engine/classes/Player#LoadCharacterWithAvatarRulesAsync)
    from: (avatarRules: AvatarRules)
    to: (avatarRules: Variant)
  * Changed the security of Function [Player.LoadCharacterWithAvatarRulesAsync](https://create.roblox.com/docs/reference/engine/classes/Player#LoadCharacterWithAvatarRulesAsync)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Function [Player.LoadCharacterWithAvatarRulesAsync](https://create.roblox.com/docs/reference/engine/classes/Player#LoadCharacterWithAvatarRulesAsync)
    from: {🚧Players}
    to: {🚧AvatarAppearance, Players}
* Update Class [ProjectService](https://create.roblox.com/docs/reference/engine/classes/ProjectService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Event [ProjectService.MutationFailed](https://create.roblox.com/docs/reference/engine/classes/ProjectService#MutationFailed)
* Update Class [RealtimeMedia](https://create.roblox.com/docs/reference/engine/classes/RealtimeMedia) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Property [RealtimeMedia.IsConnectionWeak](https://create.roblox.com/docs/reference/engine/classes/RealtimeMedia#IsConnectionWeak): bool [🏷️ ReadOnly] [🏷️ NotReplicated] {🚧Read: InternalTest | Write: InternalTest} [⚡ThreadSafety: ReadSafe]
  * Added Event [RealtimeMedia.Disconnected](https://create.roblox.com/docs/reference/engine/classes/RealtimeMedia#Disconnected) {🚧InternalTest}
* Update Class [RunService](https://create.roblox.com/docs/reference/engine/classes/RunService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the security of Property [RunService.RunState](https://create.roblox.com/docs/reference/engine/classes/RunService#RunState)
    from: {🔒PluginSecurity}
    to: {🔒Read:None, Write:PluginSecurity}
  * Changed the capabilities of Property [RunService.RunState](https://create.roblox.com/docs/reference/engine/classes/RunService#RunState)
    from: {🚧Read: Basic}
    to: {🚧Read: Basic, PluginOrOpenCloud}
  * Changed the security of Function [RunService.IsEdit](https://create.roblox.com/docs/reference/engine/classes/RunService#IsEdit)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Function [RunService.IsEdit](https://create.roblox.com/docs/reference/engine/classes/RunService#IsEdit)
    from: {🚧Basic}
    to: {🚧Basic, PluginOrOpenCloud}
* Update Class [ScriptDocument](https://create.roblox.com/docs/reference/engine/classes/ScriptDocument) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Function [ScriptDocument.GetReadOnlyReasons](https://create.roblox.com/docs/reference/engine/classes/ScriptDocument#GetReadOnlyReasons) () -> Array
  * Added Function [ScriptDocument.IsReadOnly](https://create.roblox.com/docs/reference/engine/classes/ScriptDocument#IsReadOnly) () -> bool
  * Added Function [ScriptDocument.AddReadOnlyReasonsAsync](https://create.roblox.com/docs/reference/engine/classes/ScriptDocument#AddReadOnlyReasonsAsync) (reasons: Array) -> null [🏷️ Yields]
  * Added Function [ScriptDocument.RemoveReadOnlyReasonsAsync](https://create.roblox.com/docs/reference/engine/classes/ScriptDocument#RemoveReadOnlyReasonsAsync) (reasons: Array) -> null [🏷️ Yields]
* Update Class [SoundService](https://create.roblox.com/docs/reference/engine/classes/SoundService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [SoundService.DebugClearDetachedPlaybacks](https://create.roblox.com/docs/reference/engine/classes/SoundService#DebugClearDetachedPlaybacks) () -> null {🚧Audio}
  * Added Function [SoundService.EnableDetachedPlaybackMetadata](https://create.roblox.com/docs/reference/engine/classes/SoundService#EnableDetachedPlaybackMetadata) () -> null {🚧Audio}
  * Added Function [SoundService.GetDetachedPlaybackData](https://create.roblox.com/docs/reference/engine/classes/SoundService#GetDetachedPlaybackData) () -> Dictionary {🚧Audio}
  * Added Event [SoundService.AudioDeviceInputAdded](https://create.roblox.com/docs/reference/engine/classes/SoundService#AudioDeviceInputAdded) {🚧Audio}
* Update Class [StarterPlayer](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the security of Property [StarterPlayer.PlaceAvatarRules](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#PlaceAvatarRules)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [StarterPlayer.PlaceAvatarRules](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#PlaceAvatarRules)
    from: {🚧Read: Players}
    to: {🚧Read: AvatarAppearance, Players | Write: AvatarAppearance}
* Update Class [Studio](https://create.roblox.com/docs/reference/engine/classes/Studio) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the security of Property [Studio.PluginDebuggingEnabled](https://create.roblox.com/docs/reference/engine/classes/Studio#PluginDebuggingEnabled)
    from: {🔒PluginSecurity}
    to: {🔒RobloxScriptSecurity}
* Added Class [TestCoordinatorService](https://create.roblox.com/docs/reference/engine/classes/TestCoordinatorService) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [TestCoordinatorService.Participant](https://create.roblox.com/docs/reference/engine/classes/TestCoordinatorService#Participant) {🚧InternalTest}
  * Added Function [TestCoordinatorService.Signal](https://create.roblox.com/docs/reference/engine/classes/TestCoordinatorService#Signal) {🚧InternalTest}
  * Added Function [TestCoordinatorService.AwaitAllAsync](https://create.roblox.com/docs/reference/engine/classes/TestCoordinatorService#AwaitAllAsync) [🏷️ Yields] {🚧InternalTest}
  * Added Function [TestCoordinatorService.AwaitAnyAsync](https://create.roblox.com/docs/reference/engine/classes/TestCoordinatorService#AwaitAnyAsync) [🏷️ Yields] {🚧InternalTest}
  * Added Function [TestCoordinatorService.AwaitSignalAsync](https://create.roblox.com/docs/reference/engine/classes/TestCoordinatorService#AwaitSignalAsync) [🏷️ Yields] {🚧InternalTest}
  * Added Function [TestCoordinatorService.BarrierAsync](https://create.roblox.com/docs/reference/engine/classes/TestCoordinatorService#BarrierAsync) [🏷️ Yields] {🚧InternalTest}
* Update Class [TextChatService](https://create.roblox.com/docs/reference/engine/classes/TextChatService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [TextChatService.ChatIsLoaded](https://create.roblox.com/docs/reference/engine/classes/TextChatService#ChatIsLoaded) () -> null {🚧Chat}
  * Changed the parameters of Function [TextChatService.SendExpChatMessageClientRendered](https://create.roblox.com/docs/reference/engine/classes/TextChatService#SendExpChatMessageClientRendered)
    from: (textChatMessage: TextChatMessage, messageRenderedSurface: string = unknown, selectedChannelTab: int64 = -1, textChannelWindowName: string = )
    to: (textChatMessage: TextChatMessage, messageRenderedSurface: string = unknown, selectedChannelTab: int64 = -1, textChannelWindowName: string = , specialEffects: Array = {})
  * Added Event [TextChatService.CoreMessageReceived](https://create.roblox.com/docs/reference/engine/classes/TextChatService#CoreMessageReceived) {🚧Chat}
* Update Class [UserGameSettings](https://create.roblox.com/docs/reference/engine/classes/UserGameSettings) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the serialization of Property [UserGameSettings.UIScaleMultiplierHundredths](https://create.roblox.com/docs/reference/engine/classes/UserGameSettings#UIScaleMultiplierHundredths)
    from: [🚫None]
    to: [💾|📁Serialized]
* Update Class [VideoCaptureService](https://create.roblox.com/docs/reference/engine/classes/VideoCaptureService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [VideoCaptureService.ClearMockInput](https://create.roblox.com/docs/reference/engine/classes/VideoCaptureService#ClearMockInput) () -> null {🚧InternalTest}
  * Added Function [VideoCaptureService.SetMockInputAsync](https://create.roblox.com/docs/reference/engine/classes/VideoCaptureService#SetMockInputAsync) (videoContent: Content) -> Tuple [🏷️ Yields] {🚧InternalTest}
* Update Class [VoiceChatService](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [VoiceChatService.lastVoiceChatSubscriptions](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#lastVoiceChatSubscriptions) () -> Dictionary {🚧Audio, Chat}
* Added Class [ParticipantHandle](https://create.roblox.com/docs/reference/engine/classes/ParticipantHandle) {🔒None} [⬆️Extends: Object] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Function [ParticipantHandle.Click](https://create.roblox.com/docs/reference/engine/classes/ParticipantHandle#Click) {🚧InternalTest}
  * Added Function [ParticipantHandle.InputText](https://create.roblox.com/docs/reference/engine/classes/ParticipantHandle#InputText) {🚧InternalTest}
  * Added Function [ParticipantHandle.Launch](https://create.roblox.com/docs/reference/engine/classes/ParticipantHandle#Launch) {🚧InternalTest}
  * Added Function [ParticipantHandle.Screenshot](https://create.roblox.com/docs/reference/engine/classes/ParticipantHandle#Screenshot) {🚧InternalTest}
  * Added Function [ParticipantHandle.Scroll](https://create.roblox.com/docs/reference/engine/classes/ParticipantHandle#Scroll) {🚧InternalTest}
  * Added Function [ParticipantHandle.Shutdown](https://create.roblox.com/docs/reference/engine/classes/ParticipantHandle#Shutdown) {🚧InternalTest}
* Added Enum [AudioSortType](https://create.roblox.com/docs/reference/engine/enums/AudioSortType)
  * Added EnumItem `Relevance` (1)
  * Added EnumItem `MostUsed` (2)
  * Added EnumItem `Trending` (3)
  * Added EnumItem `RecentlyCreated` (4)
  * Added EnumItem `ShortestToLongest` (5)
  * Added EnumItem `LongestToShortest` (6)
* Update Enum [EasingStyle](https://create.roblox.com/docs/reference/engine/enums/EasingStyle)
  * Added EnumItem `Bezier` (11)
  * Added EnumItem `Spring` (12)
* Update Enum [FriendsCallingEndReason](https://create.roblox.com/docs/reference/engine/enums/FriendsCallingEndReason)
  * Added EnumItem `NoReason` (7)
