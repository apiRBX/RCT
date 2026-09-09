# Roblox Client Tracker

| Metadata | Details |
| :--- | :--- |
| **Version** | `0.738.0.7381393` |
| **Version Hash** | `version-93202a13414c4131` |
| **Official Release Notes** | [Release Notes 738](https://create.roblox.com/docs/release-notes/release-notes-738) |

---

## Changelog

* Added Class [AnimatedImageTrack](https://create.roblox.com/docs/reference/engine/classes/AnimatedImageTrack) {🔒None} [⬆️Extends: Object] [🧠Memory: Gui] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Property [AnimatedImageTrack.Duration](https://create.roblox.com/docs/reference/engine/classes/AnimatedImageTrack#Duration) [🏷️ Hidden] [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [AnimatedImageTrack.FrameCount](https://create.roblox.com/docs/reference/engine/classes/AnimatedImageTrack#FrameCount) [🏷️ Hidden] [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [AnimatedImageTrack.TrackName](https://create.roblox.com/docs/reference/engine/classes/AnimatedImageTrack#TrackName) [🏷️ Hidden] [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Function [AnimatedImageTrack.GetContent](https://create.roblox.com/docs/reference/engine/classes/AnimatedImageTrack#GetContent)
  * Added Function [AnimatedImageTrack.GetFrameNames](https://create.roblox.com/docs/reference/engine/classes/AnimatedImageTrack#GetFrameNames)
* Added Class [AnimatedImageService](https://create.roblox.com/docs/reference/engine/classes/AnimatedImageService) {🔒None} [⬆️Extends: Instance] [🧠Memory: Gui] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [AnimatedImageService.GetFrameNames](https://create.roblox.com/docs/reference/engine/classes/AnimatedImageService#GetFrameNames)
  * Added Function [AnimatedImageService.GetTrack](https://create.roblox.com/docs/reference/engine/classes/AnimatedImageService#GetTrack)
  * Added Function [AnimatedImageService.GetTracksChanged](https://create.roblox.com/docs/reference/engine/classes/AnimatedImageService#GetTracksChanged)
  * Added Function [AnimatedImageService.Prewarm](https://create.roblox.com/docs/reference/engine/classes/AnimatedImageService#Prewarm)
  * Added Function [AnimatedImageService.UnloadTracks](https://create.roblox.com/docs/reference/engine/classes/AnimatedImageService#UnloadTracks)
* Added Class [AnimationValueNodeDefinition](https://create.roblox.com/docs/reference/engine/classes/AnimationValueNodeDefinition) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Property [AnimationValueNodeDefinition.NodeId](https://create.roblox.com/docs/reference/engine/classes/AnimationValueNodeDefinition#NodeId) {🚧Read: Animation} [⚡ThreadSafety: ReadSafe]
  * Added Property [AnimationValueNodeDefinition.NodeType](https://create.roblox.com/docs/reference/engine/classes/AnimationValueNodeDefinition#NodeType) {🚧Read: Animation | Write: Animation} [⚡ThreadSafety: ReadSafe]
* Added Class [AnimationValueOutputDefinition](https://create.roblox.com/docs/reference/engine/classes/AnimationValueOutputDefinition) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances]
* Update Class [AudioDeviceInput](https://create.roblox.com/docs/reference/engine/classes/AudioDeviceInput) [⬆️Extends: Instance] [🧠Memory: Internal]
  * Added Property [AudioDeviceInput.DictationEnabled](https://create.roblox.com/docs/reference/engine/classes/AudioDeviceInput#DictationEnabled): bool [🏷️ Hidden] {🚧Read: Audio, Input} [⚡ThreadSafety: ReadSafe]
* Update Class [AnimationImportData](https://create.roblox.com/docs/reference/engine/classes/AnimationImportData) [⬆️Extends: BaseImportData] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Property [AnimationImportData.ForceNewVersion](https://create.roblox.com/docs/reference/engine/classes/AnimationImportData#ForceNewVersion): bool [⚡ThreadSafety: ReadSafe]
  * Added Property [AnimationImportData.VersionedAssetId](https://create.roblox.com/docs/reference/engine/classes/AnimationImportData#VersionedAssetId): int64 [⚡ThreadSafety: ReadSafe]
* Update Class [Decal](https://create.roblox.com/docs/reference/engine/classes/Decal) [⬆️Extends: FaceInstance] [🧠Memory: GraphicsTexture]
  * Added Property [Decal.LocalizedTextureContent](https://create.roblox.com/docs/reference/engine/classes/Decal#LocalizedTextureContent): Content [🏷️ ReadOnly] [🏷️ NotReplicated] {🚧Read: Basic} [⚡ThreadSafety: ReadSafe]
* Update Class [Folder](https://create.roblox.com/docs/reference/engine/classes/Folder) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Property [Folder.IconTint](https://create.roblox.com/docs/reference/engine/classes/Folder#IconTint): Color3 {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
* Added Class [AnimatedImage](https://create.roblox.com/docs/reference/engine/classes/AnimatedImage) {🔒None} [⬆️Extends: GuiBase] [🧠Memory: Gui] [🏷️ NotCreatable]
  * Added Property [AnimatedImage.Content](https://create.roblox.com/docs/reference/engine/classes/AnimatedImage#Content) [🏷️ Hidden] [🏷️ NotReplicated] {🚧Read: UI} [⚡ThreadSafety: ReadSafe]
  * Added Property [AnimatedImage.PlaybackSpeed](https://create.roblox.com/docs/reference/engine/classes/AnimatedImage#PlaybackSpeed) [🏷️ Hidden] [🏷️ NotReplicated] {🚧Read: UI} [⚡ThreadSafety: ReadSafe]
  * Added Function [AnimatedImage.GetBoundTracks](https://create.roblox.com/docs/reference/engine/classes/AnimatedImage#GetBoundTracks) {🚧UI}
  * Added Function [AnimatedImage.Pause](https://create.roblox.com/docs/reference/engine/classes/AnimatedImage#Pause) {🚧UI}
  * Added Function [AnimatedImage.Resume](https://create.roblox.com/docs/reference/engine/classes/AnimatedImage#Resume) {🚧UI}
* Added Class [MomentsService](https://create.roblox.com/docs/reference/engine/classes/MomentsService) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [MomentsService.CheckMomentTextStatusAsync](https://create.roblox.com/docs/reference/engine/classes/MomentsService#CheckMomentTextStatusAsync) [🏷️ Yields] {🚧Capture}
  * Added Function [MomentsService.CreatePostAsync](https://create.roblox.com/docs/reference/engine/classes/MomentsService#CreatePostAsync) [🏷️ Yields] {🚧Capture}
  * Added Function [MomentsService.GenerateMomentTextAsync](https://create.roblox.com/docs/reference/engine/classes/MomentsService#GenerateMomentTextAsync) [🏷️ Yields] {🚧Capture}
* Update Class [Terrain](https://create.roblox.com/docs/reference/engine/classes/Terrain) [⬆️Extends: BasePart] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Added Property [Terrain.ExpandedTerrainResolved](https://create.roblox.com/docs/reference/engine/classes/Terrain#ExpandedTerrainResolved): bool [🏷️ Hidden] {🚧Read: Environment} [⚡ThreadSafety: ReadSafe]
* Update Class [Workspace](https://create.roblox.com/docs/reference/engine/classes/Workspace) [⬆️Extends: WorldRoot] [🧠Memory: BaseParts] [🏷️ NotCreatable] [🏷️ Service]
  * Added Property [Workspace.StreamingAdaptiveRadius](https://create.roblox.com/docs/reference/engine/classes/Workspace#StreamingAdaptiveRadius): bool {🚧Read: PluginOrOpenCloud | Write: PluginOrOpenCloud} [⚡ThreadSafety: ReadSafe]
* Update Class [PinShortcutService](https://create.roblox.com/docs/reference/engine/classes/PinShortcutService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [PinShortcutService.IsRevealPinnedExperienceAvailable](https://create.roblox.com/docs/reference/engine/classes/PinShortcutService#IsRevealPinnedExperienceAvailable) () -> bool
  * Added Function [PinShortcutService.RevealPinnedExperience](https://create.roblox.com/docs/reference/engine/classes/PinShortcutService#RevealPinnedExperience) (placeId: int64) -> null
  * Added Function [PinShortcutService.ShouldShowLuaNotificationOnPinExperienceCompleted](https://create.roblox.com/docs/reference/engine/classes/PinShortcutService#ShouldShowLuaNotificationOnPinExperienceCompleted) () -> bool
  * Added Event [PinShortcutService.OnPinExperienceCompleted](https://create.roblox.com/docs/reference/engine/classes/PinShortcutService#OnPinExperienceCompleted)
* Update Class [RunService](https://create.roblox.com/docs/reference/engine/classes/RunService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [RunService.BindToAnimation](https://create.roblox.com/docs/reference/engine/classes/RunService#BindToAnimation) (function: Function, frequency: StepFrequency = Hz30, priority: int = 2000) -> RBXScriptConnection {🚧Basic}
* Update Class [ScriptService](https://create.roblox.com/docs/reference/engine/classes/ScriptService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [ScriptService.ResolveModulePath](https://create.roblox.com/docs/reference/engine/classes/ScriptService#ResolveModulePath) (relativeTo: Instance, path: string) -> Instance [🏷️ CustomLuaState]
* Update Class [Studio](https://create.roblox.com/docs/reference/engine/classes/Studio) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Property [Studio.ReviewableChangeAddedTextColor](https://create.roblox.com/docs/reference/engine/classes/Studio#ReviewableChangeAddedTextColor): Color3 [🏷️ Hidden] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [Studio.ReviewableChangeRemovedTextColor](https://create.roblox.com/docs/reference/engine/classes/Studio#ReviewableChangeRemovedTextColor): Color3 [🏷️ Hidden] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
* Update Class [TextChannel](https://create.roblox.com/docs/reference/engine/classes/TextChannel) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Property [TextChannel.AddPlayersOnJoin](https://create.roblox.com/docs/reference/engine/classes/TextChannel#AddPlayersOnJoin): bool {🚧Read: Chat} [⚡ThreadSafety: ReadSafe]
* Removed Class DataModelPatchService
* Added Enum [AnimatedImagePlaybackState](https://create.roblox.com/docs/reference/engine/enums/AnimatedImagePlaybackState)
  * Added EnumItem `Begin` (0)
  * Added EnumItem `Playing` (1)
  * Added EnumItem `Paused` (2)
  * Added EnumItem `Completed` (3)
  * Added EnumItem `Canceled` (4)
* Added Enum [AnimatedImageScaleType](https://create.roblox.com/docs/reference/engine/enums/AnimatedImageScaleType)
  * Added EnumItem `Stretch` (0)
  * Added EnumItem `Tile` (1)
  * Added EnumItem `Fit` (2)
  * Added EnumItem `Crop` (3)
* Added Enum [AnimationValueNodeType](https://create.roblox.com/docs/reference/engine/enums/AnimationValueNodeType)
  * Added EnumItem `Invalid` (0)
  * Added EnumItem `Expression` (1)
* Update Enum [ConnectionError](https://create.roblox.com/docs/reference/engine/enums/ConnectionError)
  * Added EnumItem `TransportErrors` (1024)
  * Added EnumItem `DisconnectTransportIoError` (1025)
  * Added EnumItem `DisconnectTransportIoInternetError` (1026)
  * Added EnumItem `DisconnectTransportProtocolError` (1027)
  * Added EnumItem `DisconnectTransportNgtcp2Error` (1028)
  * Added EnumItem `DisconnectTransportQuicError` (1029)
  * Added EnumItem `DisconnectTransportRnaError` (1030)
* Added Enum [PinExperienceStatus](https://create.roblox.com/docs/reference/engine/enums/PinExperienceStatus)
  * Added EnumItem `Success` (0)
  * Added EnumItem `Failure` (1)
  * Added EnumItem `AlreadyExists` (2)
* Update Enum [StudioScriptEditorColorCategories](https://create.roblox.com/docs/reference/engine/enums/StudioScriptEditorColorCategories)
  * Added EnumItem `ReviewableChangeAddedText` (47)
  * Added EnumItem `ReviewableChangeRemovedText` (48)
