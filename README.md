# Roblox Client Tracker

| Metadata | Details |
| :--- | :--- |
| **Version** | `0.737.0.7371584` |
| **Version Hash** | `version-9fe94fb0e9d84c25` |
| **Official Release Notes** | [Release Notes 737](https://create.roblox.com/docs/release-notes/release-notes-737) |

---

## Changelog

* Update Class [AudioDeviceInput](https://create.roblox.com/docs/reference/engine/classes/AudioDeviceInput) [⬆️Extends: Instance] [🧠Memory: Internal]
  * Removed Property AudioDeviceInput.DictationEnabled
* Update Class [AnimationImportData](https://create.roblox.com/docs/reference/engine/classes/AnimationImportData) [⬆️Extends: BaseImportData] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Removed Property AnimationImportData.ForceNewVersion
  * Removed Property AnimationImportData.VersionedAssetId
* Added Class [DataModelPatchService](https://create.roblox.com/docs/reference/engine/classes/DataModelPatchService) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [DataModelPatchService.GetLuaVersion](https://create.roblox.com/docs/reference/engine/classes/DataModelPatchService#GetLuaVersion)
  * Added Function [DataModelPatchService.GetPatch](https://create.roblox.com/docs/reference/engine/classes/DataModelPatchService#GetPatch)
  * Added Function [DataModelPatchService.RegisterPatch](https://create.roblox.com/docs/reference/engine/classes/DataModelPatchService#RegisterPatch)
  * Added Function [DataModelPatchService.UpdatePatch](https://create.roblox.com/docs/reference/engine/classes/DataModelPatchService#UpdatePatch)
* Update Class [Decal](https://create.roblox.com/docs/reference/engine/classes/Decal) [⬆️Extends: FaceInstance] [🧠Memory: GraphicsTexture]
  * Removed Property Decal.LocalizedTextureContent
* Update Class [Folder](https://create.roblox.com/docs/reference/engine/classes/Folder) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Removed Property Folder.IconTint
* Update Class [Terrain](https://create.roblox.com/docs/reference/engine/classes/Terrain) [⬆️Extends: BasePart] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Removed Property Terrain.ExpandedTerrainResolved
* Update Class [Workspace](https://create.roblox.com/docs/reference/engine/classes/Workspace) [⬆️Extends: WorldRoot] [🧠Memory: BaseParts] [🏷️ NotCreatable] [🏷️ Service]
  * Removed Property Workspace.StreamingAdaptiveRadius
* Update Class [PinShortcutService](https://create.roblox.com/docs/reference/engine/classes/PinShortcutService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Removed Function PinShortcutService.IsRevealPinnedExperienceAvailable
  * Removed Function PinShortcutService.RevealPinnedExperience
  * Removed Function PinShortcutService.ShouldShowLuaNotificationOnPinExperienceCompleted
  * Removed Event PinShortcutService.OnPinExperienceCompleted
* Update Class [RunService](https://create.roblox.com/docs/reference/engine/classes/RunService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Removed Function RunService.BindToAnimation
* Update Class [ScriptService](https://create.roblox.com/docs/reference/engine/classes/ScriptService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Removed Function ScriptService.ResolveModulePath
* Update Class [Studio](https://create.roblox.com/docs/reference/engine/classes/Studio) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Removed Property Studio.ReviewableChangeAddedTextColor
  * Removed Property Studio.ReviewableChangeRemovedTextColor
* Update Class [TextChannel](https://create.roblox.com/docs/reference/engine/classes/TextChannel) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Removed Property TextChannel.AddPlayersOnJoin
* Removed Class AnimatedImageTrack
* Removed Class AnimatedImageService
* Removed Class AnimationValueNodeDefinition
* Removed Class AnimationValueOutputDefinition
* Removed Class AnimatedImage
* Removed Class MomentsService
* Update Enum [ConnectionError](https://create.roblox.com/docs/reference/engine/enums/ConnectionError)
  * Removed EnumItem `TransportErrors`
  * Removed EnumItem `DisconnectTransportIoError`
  * Removed EnumItem `DisconnectTransportIoInternetError`
  * Removed EnumItem `DisconnectTransportProtocolError`
  * Removed EnumItem `DisconnectTransportNgtcp2Error`
  * Removed EnumItem `DisconnectTransportQuicError`
  * Removed EnumItem `DisconnectTransportRnaError`
* Update Enum [StudioScriptEditorColorCategories](https://create.roblox.com/docs/reference/engine/enums/StudioScriptEditorColorCategories)
  * Removed EnumItem `ReviewableChangeAddedText`
  * Removed EnumItem `ReviewableChangeRemovedText`
* Removed Enum AnimatedImagePlaybackState
* Removed Enum AnimatedImageScaleType
* Removed Enum AnimationValueNodeType
* Removed Enum PinExperienceStatus
