# Roblox Client Tracker

| Metadata | Details |
| :--- | :--- |
| **Version** | `0.734.0.7340915` |
| **Version Hash** | `version-d679641ad17741aa` |
| **Official Release Notes** | [Release Notes 734](https://create.roblox.com/docs/release-notes/release-notes-734) |

---

## Changelog

* Update Class [EditableImage](https://create.roblox.com/docs/reference/engine/classes/EditableImage) [⬆️Extends: Object] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Added Function [EditableImage.SampleImageProjected](https://create.roblox.com/docs/reference/engine/classes/EditableImage#SampleImageProjected) (sourceMesh: EditableMesh, sourceTexture: EditableImage, projectionConfig: Dictionary, brushConfig: Dictionary) -> null {🚧DynamicGeneration}
* Update Class [AnimationRigData](https://create.roblox.com/docs/reference/engine/classes/AnimationRigData) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Function [AnimationRigData.Dump](https://create.roblox.com/docs/reference/engine/classes/AnimationRigData#Dump) () -> string {🚧Animation}
* Update Class [AssetImportService](https://create.roblox.com/docs/reference/engine/classes/AssetImportService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the parameters of Event [AssetImportService.StartSingleMeshImport](https://create.roblox.com/docs/reference/engine/classes/AssetImportService#StartSingleMeshImport)
    from: (fileName: string)
    to: (fileName: string, assetId: int64)
* Update Class [AudioSpeechToText](https://create.roblox.com/docs/reference/engine/classes/AudioSpeechToText) [⬆️Extends: Instance] [🧠Memory: Internal]
  * Added Property [AudioSpeechToText.DisableVoiceDetection](https://create.roblox.com/docs/reference/engine/classes/AudioSpeechToText#DisableVoiceDetection): bool [🏷️ Hidden] {🚧Read: Audio} [⚡ThreadSafety: ReadSafe]
  * Added Property [AudioSpeechToText.EnableVolumeCheck](https://create.roblox.com/docs/reference/engine/classes/AudioSpeechToText#EnableVolumeCheck): bool [🏷️ Hidden] {🚧Read: Audio} [⚡ThreadSafety: ReadSafe]
  * Added Property [AudioSpeechToText.VoiceDetectedOverride](https://create.roblox.com/docs/reference/engine/classes/AudioSpeechToText#VoiceDetectedOverride): bool [🏷️ Hidden] {🚧Read: Audio} [⚡ThreadSafety: ReadSafe]
* Update Class [AudioTextToSpeech](https://create.roblox.com/docs/reference/engine/classes/AudioTextToSpeech) [⬆️Extends: Instance] [🧠Memory: Internal]
  * Added Function [AudioTextToSpeech.LoadPlatformAsync](https://create.roblox.com/docs/reference/engine/classes/AudioTextToSpeech#LoadPlatformAsync) () -> AssetFetchStatus [🏷️ Yields] {🚧Audio}
* Added Class [AudioWindSynthesizer](https://create.roblox.com/docs/reference/engine/classes/AudioWindSynthesizer) {🔒None} [⬆️Extends: Instance] [🧠Memory: Internal] [🏷️ NotBrowsable]
  * Added Property [AudioWindSynthesizer.Enabled](https://create.roblox.com/docs/reference/engine/classes/AudioWindSynthesizer#Enabled) {🚧Read: Audio | Write: Audio} [⚡ThreadSafety: ReadSafe]
  * Added Property [AudioWindSynthesizer.PositionInstance](https://create.roblox.com/docs/reference/engine/classes/AudioWindSynthesizer#PositionInstance) {🚧Read: Audio | Write: Audio} [⚡ThreadSafety: ReadSafe]
  * Added Property [AudioWindSynthesizer.PositionType](https://create.roblox.com/docs/reference/engine/classes/AudioWindSynthesizer#PositionType) {🚧Read: Audio | Write: Audio} [⚡ThreadSafety: ReadSafe]
  * Added Property [AudioWindSynthesizer.Profile](https://create.roblox.com/docs/reference/engine/classes/AudioWindSynthesizer#Profile) {🚧Read: Audio | Write: Audio} [⚡ThreadSafety: ReadSafe]
  * Added Property [AudioWindSynthesizer.Volume](https://create.roblox.com/docs/reference/engine/classes/AudioWindSynthesizer#Volume) {🚧Read: Audio | Write: Audio} [⚡ThreadSafety: ReadSafe]
  * Added Function [AudioWindSynthesizer.GetConnectedWires](https://create.roblox.com/docs/reference/engine/classes/AudioWindSynthesizer#GetConnectedWires) {🚧Audio}
  * Added Function [AudioWindSynthesizer.GetInputPins](https://create.roblox.com/docs/reference/engine/classes/AudioWindSynthesizer#GetInputPins) {🚧Audio}
  * Added Function [AudioWindSynthesizer.GetOutputPins](https://create.roblox.com/docs/reference/engine/classes/AudioWindSynthesizer#GetOutputPins) {🚧Audio}
  * Added Event [AudioWindSynthesizer.WiringChanged](https://create.roblox.com/docs/reference/engine/classes/AudioWindSynthesizer#WiringChanged) {🚧Audio}
* Update Class [CaptureService](https://create.roblox.com/docs/reference/engine/classes/CaptureService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [CaptureService.StartUploadCaptureForSupportTicketAsync](https://create.roblox.com/docs/reference/engine/classes/CaptureService#StartUploadCaptureForSupportTicketAsync) (capture: Capture) -> Tuple [🏷️ Yields] {🚧Capture}
* Update Class [CollectionService](https://create.roblox.com/docs/reference/engine/classes/CollectionService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [CollectionService.CreateCollection](https://create.roblox.com/docs/reference/engine/classes/CollectionService#CreateCollection) (query: string, root: Instance = nil) -> CollectionHandle {🚧Basic}
* Update Class [DeferredAssetManagerService](https://create.roblox.com/docs/reference/engine/classes/DeferredAssetManagerService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Property [DeferredAssetManagerService.JoiningPlaceId](https://create.roblox.com/docs/reference/engine/classes/DeferredAssetManagerService#JoiningPlaceId): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [DeferredAssetManagerService.JoiningUniverseId](https://create.roblox.com/docs/reference/engine/classes/DeferredAssetManagerService#JoiningUniverseId): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [DeferredAssetManagerService.PregameLoadingScreenOnly](https://create.roblox.com/docs/reference/engine/classes/DeferredAssetManagerService#PregameLoadingScreenOnly): bool [⚡ThreadSafety: ReadSafe]
  * Added Function [DeferredAssetManagerService.CancelPrefetch](https://create.roblox.com/docs/reference/engine/classes/DeferredAssetManagerService#CancelPrefetch) () -> null
* Update Class [ScreenGui](https://create.roblox.com/docs/reference/engine/classes/ScreenGui) [⬆️Extends: LayerCollector] [🧠Memory: Instances]
  * Added Property [ScreenGui.IgnoresTitleBarReservation](https://create.roblox.com/docs/reference/engine/classes/ScreenGui#IgnoresTitleBarReservation): bool [🏷️ Hidden] {🚧Read: UI} [⚡ThreadSafety: ReadSafe]
* Update Class [GuiService](https://create.roblox.com/docs/reference/engine/classes/GuiService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [GuiService.GetUIScaleMultiplier](https://create.roblox.com/docs/reference/engine/classes/GuiService#GetUIScaleMultiplier) () -> int {🚧UI}
  * Added Function [GuiService.SetUIScaleMultiplier](https://create.roblox.com/docs/reference/engine/classes/GuiService#SetUIScaleMultiplier) (multiplierHundredths: int) -> null {🚧UI}
* Update Class [LogService](https://create.roblox.com/docs/reference/engine/classes/LogService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [LogService.GetLogger](https://create.roblox.com/docs/reference/engine/classes/LogService#GetLogger) (name: string) -> Logger [🏷️ CustomLuaState] {🚧Logging}
* Added Class [ViewportCamera](https://create.roblox.com/docs/reference/engine/classes/ViewportCamera) {🔒None} [⬆️Extends: Camera] [🧠Memory: Instances]
* Update Class [WorldRoot](https://create.roblox.com/docs/reference/engine/classes/WorldRoot) [⬆️Extends: Model] [🧠Memory: BaseParts] [🏷️ NotCreatable]
  * Added Function [WorldRoot.CollisionGroupSetCollidable](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#CollisionGroupSetCollidable) (name1: string, name2: string, collidable: bool) -> null {🚧Physics}
  * Added Function [WorldRoot.CollisionGroupsAreCollidable](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#CollisionGroupsAreCollidable) (name1: string, name2: string) -> bool {🚧Physics}
  * Added Function [WorldRoot.GetMaxCollisionGroups](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#GetMaxCollisionGroups) () -> int {🚧Physics}
  * Added Function [WorldRoot.GetRegisteredCollisionGroups](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#GetRegisteredCollisionGroups) () -> Array {🚧Physics}
  * Added Function [WorldRoot.IsCollisionGroupRegistered](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#IsCollisionGroupRegistered) (name: string) -> bool {🚧Physics}
  * Added Function [WorldRoot.RegisterCollisionGroup](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#RegisterCollisionGroup) (name: string) -> null {🚧Physics}
  * Added Function [WorldRoot.RenameCollisionGroup](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#RenameCollisionGroup) (from: string, to: string) -> null {🚧Physics}
  * Added Function [WorldRoot.UnregisterCollisionGroup](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#UnregisterCollisionGroup) (name: string) -> null {🚧Physics}
* Update Class [WorldModel](https://create.roblox.com/docs/reference/engine/classes/WorldModel) [⬆️Extends: WorldRoot] [🧠Memory: BaseParts]
  * Changed the security of Property [WorldModel.UseWorkspaceCollisionGroups](https://create.roblox.com/docs/reference/engine/classes/WorldModel#UseWorkspaceCollisionGroups)
    from: {🔒RobloxSecurity}
    to: {🔒None}
* Update Class [PackageService](https://create.roblox.com/docs/reference/engine/classes/PackageService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [PackageService.GetOverrides](https://create.roblox.com/docs/reference/engine/classes/PackageService#GetOverrides) (scopeRoot: Instance) -> DataModelDiff
  * Added Event [PackageService.OverrideStateChanged](https://create.roblox.com/docs/reference/engine/classes/PackageService#OverrideStateChanged)
  * Added Event [PackageService.OverridesCleared](https://create.roblox.com/docs/reference/engine/classes/PackageService#OverridesCleared)
* Update Class [PhysicsSettings](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Property [PhysicsSettings.CollisionGeomDrawOriginalParts](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings#CollisionGeomDrawOriginalParts): bool [⚡ThreadSafety: ReadSafe]
  * Added Property [PhysicsSettings.CollisionGeomMatchPartTransparency](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings#CollisionGeomMatchPartTransparency): bool [⚡ThreadSafety: ReadSafe]
  * Added Property [PhysicsSettings.CollisionGeomOverlayTransparency](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings#CollisionGeomOverlayTransparency): float [⚡ThreadSafety: ReadSafe]
  * Added Property [PhysicsSettings.CollisionGeomShowCollidableParts](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings#CollisionGeomShowCollidableParts): bool [⚡ThreadSafety: ReadSafe]
  * Added Property [PhysicsSettings.CollisionGeomShowCollisionGroup](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings#CollisionGeomShowCollisionGroup): string [⚡ThreadSafety: ReadSafe]
  * Added Property [PhysicsSettings.CollisionGeomShowQueryableParts](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings#CollisionGeomShowQueryableParts): bool [⚡ThreadSafety: ReadSafe]
  * Added Property [PhysicsSettings.CollisionGeomShowTouchableParts](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings#CollisionGeomShowTouchableParts): bool [⚡ThreadSafety: ReadSafe]
* Update Class [Player](https://create.roblox.com/docs/reference/engine/classes/Player) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Property [Player.FrustumStreaming](https://create.roblox.com/docs/reference/engine/classes/Player#FrustumStreaming): FrustumStreamingMode {🚧Read: Players} [⚡ThreadSafety: ReadSafe]
  * Added Function [Player.GetGlobalUserId](https://create.roblox.com/docs/reference/engine/classes/Player#GetGlobalUserId) () -> int64 {🚧Players}
* Update Class [SlimDebugSettings](https://create.roblox.com/docs/reference/engine/classes/SlimDebugSettings) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [SlimDebugSettings.GetAvailableTintModes](https://create.roblox.com/docs/reference/engine/classes/SlimDebugSettings#GetAvailableTintModes) (context: SlimViewContext, isRunning: bool) -> Array
* Update Class [Studio](https://create.roblox.com/docs/reference/engine/classes/Studio) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Property [Studio.CameraKeyMoveSmoothing](https://create.roblox.com/docs/reference/engine/classes/Studio#CameraKeyMoveSmoothing): bool [⚡ThreadSafety: ReadSafe]
  * Added Property [Studio.CameraRotateShiftFactor](https://create.roblox.com/docs/reference/engine/classes/Studio#CameraRotateShiftFactor): float [⚡ThreadSafety: ReadSafe]
* Update Class [StudioWidget](https://create.roblox.com/docs/reference/engine/classes/StudioWidget) [⬆️Extends: StudioObjectBase] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Function [StudioWidget.Resize](https://create.roblox.com/docs/reference/engine/classes/StudioWidget#Resize) (width: int, height: int) -> null
* Update Class [ThirdPartyUserService](https://create.roblox.com/docs/reference/engine/classes/ThirdPartyUserService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Removed Function ThirdPartyUserService.RegisterActiveUser
* Update Class [UserGameSettings](https://create.roblox.com/docs/reference/engine/classes/UserGameSettings) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Property [UserGameSettings.UIScaleMultiplierHundredths](https://create.roblox.com/docs/reference/engine/classes/UserGameSettings#UIScaleMultiplierHundredths): int [🏷️ Hidden] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
* Added Class [Logger](https://create.roblox.com/docs/reference/engine/classes/Logger) {🔒None} [⬆️Extends: Object] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Property [Logger.FullPath](https://create.roblox.com/docs/reference/engine/classes/Logger#FullPath) [🏷️ ReadOnly] [🏷️ NotReplicated] {🚧Read: Logging | Write: Logging} [⚡ThreadSafety: ReadSafe]
  * Added Property [Logger.Name](https://create.roblox.com/docs/reference/engine/classes/Logger#Name) [🏷️ ReadOnly] [🏷️ NotReplicated] {🚧Read: Logging | Write: Logging} [⚡ThreadSafety: ReadSafe]
  * Added Function [Logger.Error](https://create.roblox.com/docs/reference/engine/classes/Logger#Error) [🏷️ CustomLuaState] {🚧Logging}
  * Added Function [Logger.GetLogger](https://create.roblox.com/docs/reference/engine/classes/Logger#GetLogger) [🏷️ CustomLuaState] {🚧Logging}
  * Added Function [Logger.Info](https://create.roblox.com/docs/reference/engine/classes/Logger#Info) [🏷️ CustomLuaState] {🚧Logging}
  * Added Function [Logger.Log](https://create.roblox.com/docs/reference/engine/classes/Logger#Log) [🏷️ CustomLuaState] {🚧Logging}
  * Added Function [Logger.Output](https://create.roblox.com/docs/reference/engine/classes/Logger#Output) [🏷️ CustomLuaState] {🚧Logging}
  * Added Function [Logger.Warn](https://create.roblox.com/docs/reference/engine/classes/Logger#Warn) [🏷️ CustomLuaState] {🚧Logging}
  * Added Event [Logger.MessageOut](https://create.roblox.com/docs/reference/engine/classes/Logger#MessageOut) {🚧Logging}
* Added Enum [AudioPositionType](https://create.roblox.com/docs/reference/engine/enums/AudioPositionType)
  * Added EnumItem `Parent` (0)
  * Added EnumItem `Instance` (1)
* Added Enum [FrustumStreamingMode](https://create.roblox.com/docs/reference/engine/enums/FrustumStreamingMode)
  * Added EnumItem `Default` (0)
  * Added EnumItem `Enabled` (1)
  * Added EnumItem `Disabled` (2)
  * Added EnumItem `Automatic` (3)
* Update Enum [ImageCombineType](https://create.roblox.com/docs/reference/engine/enums/ImageCombineType)
  * Added EnumItem `Subtract` (7)
* Update Enum [SlimTintMode](https://create.roblox.com/docs/reference/engine/enums/SlimTintMode)
  * Added EnumItem `MeshResourcePtr` (3)
  * Added EnumItem `ContentId` (4)
  * Added EnumItem `TranscoderStatus` (6)
* Added Enum [SlimViewContext](https://create.roblox.com/docs/reference/engine/enums/SlimViewContext)
  * Added EnumItem `Player` (0)
  * Added EnumItem `Editor` (1)
  * Added EnumItem `ImGui` (2)
* Added Enum [WindSoundProfile](https://create.roblox.com/docs/reference/engine/enums/WindSoundProfile)
  * Added EnumItem `Turbulence` (0)
  * Added EnumItem `Whistle` (1)
  * Added EnumItem `Foliage` (2)
