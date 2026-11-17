# Roblox Client Tracker

| Metadata | Details |
| :--- | :--- |
| **Version** | `0.748.0.7481526` |
| **Version Hash** | `version-8d7a1009c17e4ff8` |
| **Official Release Notes** | [Release Notes 748](https://create.roblox.com/docs/release-notes/release-notes-748) |

---

## Changelog

* Added Class [Blob](https://create.roblox.com/docs/reference/engine/classes/Blob) {🔒None} [⬆️Extends: Object] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Function [Blob.Destroy](https://create.roblox.com/docs/reference/engine/classes/Blob#Destroy)
  * Added Function [Blob.GetMimeType](https://create.roblox.com/docs/reference/engine/classes/Blob#GetMimeType)
  * Added Function [Blob.GetSizeBytes](https://create.roblox.com/docs/reference/engine/classes/Blob#GetSizeBytes)
  * Added Function [Blob.ReadBytesAsync](https://create.roblox.com/docs/reference/engine/classes/Blob#ReadBytesAsync) [🏷️ Yields]
* Update Class [EditableImage](https://create.roblox.com/docs/reference/engine/classes/EditableImage) [⬆️Extends: Object] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed the parameters of Function [EditableImage.DrawCircle](https://create.roblox.com/docs/reference/engine/classes/EditableImage#DrawCircle)
    from: (center: Vector2, radius: int, color: Color3, transparency: float, combineType: ImageCombineType, antiAliasing: AntiAliasing = Enabled, alphaBlendType: ImageAlphaType = Default)
    to: (center: Vector2, radius: int, color: Color3, transparency: float = 0, combineType: ImageCombineType = Overwrite, antiAliasing: AntiAliasing = Enabled, alphaBlendType: ImageAlphaType = Default)
  * Changed the parameters of Function [EditableImage.DrawImage](https://create.roblox.com/docs/reference/engine/classes/EditableImage#DrawImage)
    from: (position: Vector2, image: EditableImage, combineType: ImageCombineType, alphaBlendType: ImageAlphaType = Default)
    to: (position: Vector2, image: EditableImage, combineType: ImageCombineType = AlphaBlend, alphaBlendType: ImageAlphaType = Default)
  * Changed the parameters of Function [EditableImage.DrawLine](https://create.roblox.com/docs/reference/engine/classes/EditableImage#DrawLine)
    from: (p1: Vector2, p2: Vector2, color: Color3, transparency: float, combineType: ImageCombineType, antiAliasing: AntiAliasing = Enabled, alphaBlendType: ImageAlphaType = Default)
    to: (p1: Vector2, p2: Vector2, color: Color3, transparency: float = 0, combineType: ImageCombineType = Overwrite, antiAliasing: AntiAliasing = Enabled, alphaBlendType: ImageAlphaType = Default)
  * Changed the parameters of Function [EditableImage.DrawRectangle](https://create.roblox.com/docs/reference/engine/classes/EditableImage#DrawRectangle)
    from: (position: Vector2, size: Vector2, color: Color3, transparency: float, combineType: ImageCombineType, alphaBlendType: ImageAlphaType = Default)
    to: (position: Vector2, size: Vector2, color: Color3, transparency: float = 0, combineType: ImageCombineType = Overwrite, alphaBlendType: ImageAlphaType = Default)
* Update Class [AdService](https://create.roblox.com/docs/reference/engine/classes/AdService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [AdService.CompleteRewardedVideoGrant](https://create.roblox.com/docs/reference/engine/classes/AdService#CompleteRewardedVideoGrant) (userId: int64, productId: int64) -> null {🚧Monetization}
  * Added Function [AdService.PlayRewardedVideoAdOnClient](https://create.roblox.com/docs/reference/engine/classes/AdService#PlayRewardedVideoAdOnClient) (player: Player, rewardDetails: Dictionary, placementId: int64) -> null {🚧Monetization}
  * Added Callback [AdService.OnRewardedVideoAdResult](https://create.roblox.com/docs/reference/engine/classes/AdService#OnRewardedVideoAdResult) [🏷️ NoYield] {🚧Monetization}
  * Added Callback [AdService.OnShowRewardedVideoAd](https://create.roblox.com/docs/reference/engine/classes/AdService#OnShowRewardedVideoAd) {🚧Monetization}
* Update Class [AnimatedImageService](https://create.roblox.com/docs/reference/engine/classes/AnimatedImageService) [⬆️Extends: Instance] [🧠Memory: Gui] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Removed Function AnimatedImageService.GetAnimatedImageClipsChangedSignal
  * Removed Function AnimatedImageService.AddAnimatedImageClipAsync
  * Removed Function AnimatedImageService.GetAnimatedImageClipFramesAsync
  * Removed Function AnimatedImageService.GetAnimatedImageClipsAsync
  * Removed Function AnimatedImageService.GetAnimatedImageFrameIndexAtTimeAsync
* Update Class [AnimationClipProvider](https://create.roblox.com/docs/reference/engine/classes/AnimationClipProvider) [⬆️Extends: Instance] [🧠Memory: Animation] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [AnimationClipProvider.GetAnimatedImageClipsChangedSignal](https://create.roblox.com/docs/reference/engine/classes/AnimationClipProvider#GetAnimatedImageClipsChangedSignal) (content: Content) -> RBXScriptSignal {🚧Animation}
  * Added Function [AnimationClipProvider.AddAnimatedImageClipAsync](https://create.roblox.com/docs/reference/engine/classes/AnimationClipProvider#AddAnimatedImageClipAsync) (content: Content, clipName: string, frames: Array) -> null [🏷️ Yields] {🚧Animation}
  * Added Function [AnimationClipProvider.GetAnimatedImageClipFramesAsync](https://create.roblox.com/docs/reference/engine/classes/AnimationClipProvider#GetAnimatedImageClipFramesAsync) (content: Content, clipName: string) -> Array [🏷️ Yields] {🚧Animation}
  * Added Function [AnimationClipProvider.GetAnimatedImageClipsAsync](https://create.roblox.com/docs/reference/engine/classes/AnimationClipProvider#GetAnimatedImageClipsAsync) (content: Content) -> Array [🏷️ Yields] {🚧Animation}
  * Added Function [AnimationClipProvider.GetAnimatedImageFrameIndexAtTimeAsync](https://create.roblox.com/docs/reference/engine/classes/AnimationClipProvider#GetAnimatedImageFrameIndexAtTimeAsync) (content: Content, clipName: string, timePosition: double) -> int [🏷️ Yields] {🚧Animation}
* Update Class [AnimationPlayer](https://create.roblox.com/docs/reference/engine/classes/AnimationPlayer) [⬆️Extends: Instance] [🧠Memory: Animation]
  * Changed MemoryCategory of Class [AnimationPlayer](https://create.roblox.com/docs/reference/engine/classes/AnimationPlayer) from `Gui` to `Animation`
* Update Class [AnimationRigData](https://create.roblox.com/docs/reference/engine/classes/AnimationRigData) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Function [AnimationRigData.Inspect](https://create.roblox.com/docs/reference/engine/classes/AnimationRigData#Inspect) () -> Array {🚧Animation, PluginOrOpenCloud}
* Update Class [AssetImportService](https://create.roblox.com/docs/reference/engine/classes/AssetImportService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the parameters of Function [AssetImportService.UploadVersionedAssetFromPathAsync](https://create.roblox.com/docs/reference/engine/classes/AssetImportService#UploadVersionedAssetFromPathAsync)
    from: (filepath: string, createAssetRequest: Dictionary, assetId: int64 = 0)
    to: (filepath: string, createAssetRequest: Dictionary, assetId: int64 = 0, progressCallback: Function? = nil)
* Update Class [AvatarChatService](https://create.roblox.com/docs/reference/engine/classes/AvatarChatService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Event [AvatarChatService.PlayerClientFeaturesResolved](https://create.roblox.com/docs/reference/engine/classes/AvatarChatService#PlayerClientFeaturesResolved)
* Update Class [WrapLayer](https://create.roblox.com/docs/reference/engine/classes/WrapLayer) [⬆️Extends: BaseWrap] [🧠Memory: Instances]
  * Added Property [WrapLayer.NonUniformScaleContent](https://create.roblox.com/docs/reference/engine/classes/WrapLayer#NonUniformScaleContent): Content {🚧Read: AvatarAppearance | Write: AvatarAppearance} [⚡ThreadSafety: ReadSafe]
  * Added Property [WrapLayer.RotateUniformScaleContent](https://create.roblox.com/docs/reference/engine/classes/WrapLayer#RotateUniformScaleContent): Content {🚧Read: AvatarAppearance | Write: AvatarAppearance} [⚡ThreadSafety: ReadSafe]
  * Changed the security of Property [WrapLayer.TargetShaping](https://create.roblox.com/docs/reference/engine/classes/WrapLayer#TargetShaping)
    from: {🔒Read:None, Write:PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [WrapLayer.TargetShaping](https://create.roblox.com/docs/reference/engine/classes/WrapLayer#TargetShaping)
    from: {🚧Read: AvatarAppearance}
    to: {🚧Read: AvatarAppearance | Write: AvatarAppearance}
  * Added Property [WrapLayer.UniformScaleContent](https://create.roblox.com/docs/reference/engine/classes/WrapLayer#UniformScaleContent): Content {🚧Read: AvatarAppearance | Write: AvatarAppearance} [⚡ThreadSafety: ReadSafe]
  * Removed Property WrapLayer.RotateScaleDeformationMap
  * Removed Property WrapLayer.ScaleOnlyDeformationMap
* Update Class [CaptureService](https://create.roblox.com/docs/reference/engine/classes/CaptureService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [CaptureService.CloneForSnapshot](https://create.roblox.com/docs/reference/engine/classes/CaptureService#CloneForSnapshot) (instances: Instances, includeNonArchivable: bool = false) -> SceneSnapshot {🚧Capture}
* Update Class [CloudClientService](https://create.roblox.com/docs/reference/engine/classes/CloudClientService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [CloudClientService.ReportOfferDecision](https://create.roblox.com/docs/reference/engine/classes/CloudClientService#ReportOfferDecision) (reservationToken: string, decision: string) -> null
* Update Class [ExperienceService](https://create.roblox.com/docs/reference/engine/classes/ExperienceService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [ExperienceService.GetConnectedServerInfo](https://create.roblox.com/docs/reference/engine/classes/ExperienceService#GetConnectedServerInfo) () -> Dictionary
  * Added Function [ExperienceService.GetConnectedServerProbeSnapshot](https://create.roblox.com/docs/reference/engine/classes/ExperienceService#GetConnectedServerProbeSnapshot) () -> Array
  * Added Function [ExperienceService.SetConnectedServerProbingActive](https://create.roblox.com/docs/reference/engine/classes/ExperienceService#SetConnectedServerProbingActive) (active: bool) -> bool
* Added Class [FilePickerService](https://create.roblox.com/docs/reference/engine/classes/FilePickerService) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [FilePickerService.IsSupported](https://create.roblox.com/docs/reference/engine/classes/FilePickerService#IsSupported)
  * Added Function [FilePickerService.PickFilesAsync](https://create.roblox.com/docs/reference/engine/classes/FilePickerService#PickFilesAsync) [🏷️ Yields]
* Update Class [BoxHandleAdornment](https://create.roblox.com/docs/reference/engine/classes/BoxHandleAdornment) [⬆️Extends: HandleAdornment] [🧠Memory: Instances]
  * Changed the security of Property [BoxHandleAdornment.DoubleSided](https://create.roblox.com/docs/reference/engine/classes/BoxHandleAdornment#DoubleSided)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
* Update Class [ConeHandleAdornment](https://create.roblox.com/docs/reference/engine/classes/ConeHandleAdornment) [⬆️Extends: HandleAdornment] [🧠Memory: Instances]
  * Changed the security of Property [ConeHandleAdornment.DoubleSided](https://create.roblox.com/docs/reference/engine/classes/ConeHandleAdornment#DoubleSided)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
* Update Class [CylinderHandleAdornment](https://create.roblox.com/docs/reference/engine/classes/CylinderHandleAdornment) [⬆️Extends: HandleAdornment] [🧠Memory: Instances]
  * Changed the security of Property [CylinderHandleAdornment.DoubleSided](https://create.roblox.com/docs/reference/engine/classes/CylinderHandleAdornment#DoubleSided)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
* Update Class [ImageHandleAdornment](https://create.roblox.com/docs/reference/engine/classes/ImageHandleAdornment) [⬆️Extends: HandleAdornment] [🧠Memory: Instances]
  * Changed the security of Property [ImageHandleAdornment.DoubleSided](https://create.roblox.com/docs/reference/engine/classes/ImageHandleAdornment#DoubleSided)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
* Update Class [PyramidHandleAdornment](https://create.roblox.com/docs/reference/engine/classes/PyramidHandleAdornment) [⬆️Extends: HandleAdornment] [🧠Memory: Instances]
  * Changed the security of Property [PyramidHandleAdornment.DoubleSided](https://create.roblox.com/docs/reference/engine/classes/PyramidHandleAdornment#DoubleSided)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
* Update Class [SphereHandleAdornment](https://create.roblox.com/docs/reference/engine/classes/SphereHandleAdornment) [⬆️Extends: HandleAdornment] [🧠Memory: Instances]
  * Changed the security of Property [SphereHandleAdornment.DoubleSided](https://create.roblox.com/docs/reference/engine/classes/SphereHandleAdornment#DoubleSided)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
* Update Class [Humanoid](https://create.roblox.com/docs/reference/engine/classes/Humanoid) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Property [Humanoid.UsesAvatarCollider](https://create.roblox.com/docs/reference/engine/classes/Humanoid#UsesAvatarCollider): bool [🏷️ Hidden] {🚧Read: AvatarBehavior} [⚡ThreadSafety: ReadSafe]
  * Added Function [Humanoid.GetCanCollideOnDeath](https://create.roblox.com/docs/reference/engine/classes/Humanoid#GetCanCollideOnDeath) (part: BasePart, fallback: bool) -> bool {🚧AvatarBehavior} [⚡ThreadSafety: Safe]
  * Added Function [Humanoid.PlayAvatarEffectAsync](https://create.roblox.com/docs/reference/engine/classes/Humanoid#PlayAvatarEffectAsync) (assetId: int64) -> Instances [🏷️ Yields]
* Update Class [Lighting](https://create.roblox.com/docs/reference/engine/classes/Lighting) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Property [Lighting.LightAttenuationMode](https://create.roblox.com/docs/reference/engine/classes/Lighting#LightAttenuationMode): LightAttenuationMode {🚧Read: Environment | Write: PluginOrOpenCloud} [⚡ThreadSafety: ReadSafe]
* Update Class [Player](https://create.roblox.com/docs/reference/engine/classes/Player) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Function [Player.HasSpawnEffectPlayed](https://create.roblox.com/docs/reference/engine/classes/Player#HasSpawnEffectPlayed) () -> bool {🚧Players}
* Update Class [ColorCorrectionEffect](https://create.roblox.com/docs/reference/engine/classes/ColorCorrectionEffect) [⬆️Extends: PostEffect] [🧠Memory: Instances]
  * Added Property [ColorCorrectionEffect.ColorLutContent](https://create.roblox.com/docs/reference/engine/classes/ColorCorrectionEffect#ColorLutContent): Content {🚧Read: Environment} [⚡ThreadSafety: ReadSafe]
  * Added Property [ColorCorrectionEffect.ColorLutIntensity](https://create.roblox.com/docs/reference/engine/classes/ColorCorrectionEffect#ColorLutIntensity): float {🚧Read: Environment} [⚡ThreadSafety: ReadSafe]
* Update Class [ControllerPartSensor](https://create.roblox.com/docs/reference/engine/classes/ControllerPartSensor) [⬆️Extends: ControllerSensor] [🧠Memory: Instances]
  * Added Function [ControllerPartSensor.GetExtents](https://create.roblox.com/docs/reference/engine/classes/ControllerPartSensor#GetExtents) () -> any [🏷️ NotBrowsable] {🚧Basic}
* Added Class [SessionStorage](https://create.roblox.com/docs/reference/engine/classes/SessionStorage) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
* Update Class [Studio](https://create.roblox.com/docs/reference/engine/classes/Studio) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Property [Studio.AutoPlayAnimatedImages](https://create.roblox.com/docs/reference/engine/classes/Studio#AutoPlayAnimatedImages): bool [🏷️ Hidden] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [Studio.CameraFocusFillPercent](https://create.roblox.com/docs/reference/engine/classes/Studio#CameraFocusFillPercent): float [⚡ThreadSafety: ReadSafe]
  * Added Property [Studio.CameraNavigationModelLocked](https://create.roblox.com/docs/reference/engine/classes/Studio#CameraNavigationModelLocked): bool [⚡ThreadSafety: ReadSafe]
  * Added Property [Studio.CameraRotateCursorLock](https://create.roblox.com/docs/reference/engine/classes/Studio#CameraRotateCursorLock): CameraRotateCursorLock [⚡ThreadSafety: ReadSafe]
  * Added Property [Studio.Camera Orbit Speed](https://create.roblox.com/docs/reference/engine/classes/Studio#Camera%20Orbit%20Speed): float [⚡ThreadSafety: ReadSafe]
* Update Class [StudioCameraService](https://create.roblox.com/docs/reference/engine/classes/StudioCameraService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Property [StudioCameraService.GraspDistance](https://create.roblox.com/docs/reference/engine/classes/StudioCameraService#GraspDistance): float [⚡ThreadSafety: ReadSafe]
* Update Class [TeleportOptions](https://create.roblox.com/docs/reference/engine/classes/TeleportOptions) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Property [TeleportOptions.ForcePublicServer](https://create.roblox.com/docs/reference/engine/classes/TeleportOptions#ForcePublicServer): bool {🚧Read: Teleport | Write: Teleport} [⚡ThreadSafety: ReadSafe]
* Update Class [UGCValidationService](https://create.roblox.com/docs/reference/engine/classes/UGCValidationService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [UGCValidationService.GetCurveAnimationRenderedFrames](https://create.roblox.com/docs/reference/engine/classes/UGCValidationService#GetCurveAnimationRenderedFrames) (curveAnimation: Instance, templateRig: Model, classicTemplateRig: Model, maxDuration: float) -> Dictionary
* Update Class [VRService](https://create.roblox.com/docs/reference/engine/classes/VRService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Property [VRService.VRSessionActive](https://create.roblox.com/docs/reference/engine/classes/VRService#VRSessionActive): bool [🏷️ Hidden] [🏷️ ReadOnly] [🏷️ NotReplicated] {🚧Read: Input} [⚡ThreadSafety: ReadSafe]
* Update Class [ParticipantHandle](https://create.roblox.com/docs/reference/engine/classes/ParticipantHandle) [⬆️Extends: Object] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Function [ParticipantHandle.InvokePluginCommand](https://create.roblox.com/docs/reference/engine/classes/ParticipantHandle#InvokePluginCommand) (command: string, args: Dictionary = nil) -> string {🚧InternalTest}
* Added Class [PickedFile](https://create.roblox.com/docs/reference/engine/classes/PickedFile) {🔒None} [⬆️Extends: Object] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Function [PickedFile.Destroy](https://create.roblox.com/docs/reference/engine/classes/PickedFile#Destroy)
  * Added Function [PickedFile.GetExtension](https://create.roblox.com/docs/reference/engine/classes/PickedFile#GetExtension)
  * Added Function [PickedFile.GetMimeType](https://create.roblox.com/docs/reference/engine/classes/PickedFile#GetMimeType)
  * Added Function [PickedFile.GetName](https://create.roblox.com/docs/reference/engine/classes/PickedFile#GetName)
  * Added Function [PickedFile.LoadAsync](https://create.roblox.com/docs/reference/engine/classes/PickedFile#LoadAsync) [🏷️ Yields]
* Added Class [SceneSnapshot](https://create.roblox.com/docs/reference/engine/classes/SceneSnapshot) {🔒None} [⬆️Extends: Object] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Function [SceneSnapshot.GetRoots](https://create.roblox.com/docs/reference/engine/classes/SceneSnapshot#GetRoots)
  * Added Function [SceneSnapshot.GetSourceGuid](https://create.roblox.com/docs/reference/engine/classes/SceneSnapshot#GetSourceGuid)
* Added Enum [CameraRotateCursorLock](https://create.roblox.com/docs/reference/engine/enums/CameraRotateCursorLock)
  * Added EnumItem `Never` (0)
  * Added EnumItem `FpsOnly` (1)
  * Added EnumItem `BothModes` (2)
* Update Enum [DomainType](https://create.roblox.com/docs/reference/engine/enums/DomainType)
  * Added EnumItem `Experience` (1)
  * Added EnumItem `Group` (2)
  * Added EnumItem `OAuth` (3)
  * Removed EnumItem `EXPERIENCE`
  * Removed EnumItem `OAUTH`
* Update Enum [EngineFolder](https://create.roblox.com/docs/reference/engine/enums/EngineFolder)
  * Added EnumItem `ClientSettings` (3)
* Added Enum [LightAttenuationMode](https://create.roblox.com/docs/reference/engine/enums/LightAttenuationMode)
  * Added EnumItem `Legacy` (0)
  * Added EnumItem `Realistic` (1)
