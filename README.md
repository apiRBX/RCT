# Roblox Client Tracker

| Metadata | Details |
| :--- | :--- |
| **Version** | `0.747.0.7471481` |
| **Version Hash** | `version-63eb6055af4e4688` |
| **Official Release Notes** | [Release Notes 747](https://create.roblox.com/docs/release-notes/release-notes-747) |

---

## Changelog

* Added Class [AudioStreamReader](https://create.roblox.com/docs/reference/engine/classes/AudioStreamReader) {🔒None} [⬆️Extends: Instance] [🧠Memory: Internal] [🏷️ NotBrowsable]
  * Added Property [AudioStreamReader.Layout](https://create.roblox.com/docs/reference/engine/classes/AudioStreamReader#Layout) {🚧Read: Audio | Write: Audio} [⚡ThreadSafety: ReadSafe]
  * Added Property [AudioStreamReader.SampleFormat](https://create.roblox.com/docs/reference/engine/classes/AudioStreamReader#SampleFormat) [🏷️ ReadOnly] [🏷️ NotReplicated] {🚧Read: Audio | Write: Audio} [⚡ThreadSafety: ReadSafe]
  * Added Property [AudioStreamReader.SampleRate](https://create.roblox.com/docs/reference/engine/classes/AudioStreamReader#SampleRate) [🏷️ ReadOnly] [🏷️ NotReplicated] {🚧Read: Audio | Write: Audio} [⚡ThreadSafety: ReadSafe]
  * Added Property [AudioStreamReader.WindowSize](https://create.roblox.com/docs/reference/engine/classes/AudioStreamReader#WindowSize) {🚧Read: Audio | Write: Audio} [⚡ThreadSafety: ReadSafe]
  * Added Function [AudioStreamReader.GetConnectedWires](https://create.roblox.com/docs/reference/engine/classes/AudioStreamReader#GetConnectedWires) {🚧Audio}
  * Added Function [AudioStreamReader.GetInputPins](https://create.roblox.com/docs/reference/engine/classes/AudioStreamReader#GetInputPins) {🚧Audio}
  * Added Function [AudioStreamReader.GetOutputPins](https://create.roblox.com/docs/reference/engine/classes/AudioStreamReader#GetOutputPins) {🚧Audio}
  * Added Function [AudioStreamReader.Peek](https://create.roblox.com/docs/reference/engine/classes/AudioStreamReader#Peek) [🏷️ CustomLuaState] {🚧Audio} [⚡ThreadSafety: Safe]
  * Added Function [AudioStreamReader.Read](https://create.roblox.com/docs/reference/engine/classes/AudioStreamReader#Read) [🏷️ CustomLuaState] {🚧Audio} [⚡ThreadSafety: Safe]
  * Added Event [AudioStreamReader.WiringChanged](https://create.roblox.com/docs/reference/engine/classes/AudioStreamReader#WiringChanged) {🚧Audio}
* Added Class [AudioStreamWriter](https://create.roblox.com/docs/reference/engine/classes/AudioStreamWriter) {🔒None} [⬆️Extends: Instance] [🧠Memory: Internal] [🏷️ NotBrowsable]
  * Added Property [AudioStreamWriter.Layout](https://create.roblox.com/docs/reference/engine/classes/AudioStreamWriter#Layout) {🚧Read: Audio | Write: Audio} [⚡ThreadSafety: ReadSafe]
  * Added Property [AudioStreamWriter.SampleFormat](https://create.roblox.com/docs/reference/engine/classes/AudioStreamWriter#SampleFormat) [🏷️ ReadOnly] [🏷️ NotReplicated] {🚧Read: Audio | Write: Audio} [⚡ThreadSafety: ReadSafe]
  * Added Property [AudioStreamWriter.SampleRate](https://create.roblox.com/docs/reference/engine/classes/AudioStreamWriter#SampleRate) [🏷️ ReadOnly] [🏷️ NotReplicated] {🚧Read: Audio | Write: Audio} [⚡ThreadSafety: ReadSafe]
  * Added Property [AudioStreamWriter.WindowSize](https://create.roblox.com/docs/reference/engine/classes/AudioStreamWriter#WindowSize) {🚧Read: Audio | Write: Audio} [⚡ThreadSafety: ReadSafe]
  * Added Function [AudioStreamWriter.GetConnectedWires](https://create.roblox.com/docs/reference/engine/classes/AudioStreamWriter#GetConnectedWires) {🚧Audio}
  * Added Function [AudioStreamWriter.GetInputPins](https://create.roblox.com/docs/reference/engine/classes/AudioStreamWriter#GetInputPins) {🚧Audio}
  * Added Function [AudioStreamWriter.GetOutputPins](https://create.roblox.com/docs/reference/engine/classes/AudioStreamWriter#GetOutputPins) {🚧Audio}
  * Added Function [AudioStreamWriter.Space](https://create.roblox.com/docs/reference/engine/classes/AudioStreamWriter#Space) {🚧Audio} [⚡ThreadSafety: Safe]
  * Added Function [AudioStreamWriter.Write](https://create.roblox.com/docs/reference/engine/classes/AudioStreamWriter#Write) [🏷️ CustomLuaState] {🚧Audio} [⚡ThreadSafety: Safe]
  * Added Event [AudioStreamWriter.WiringChanged](https://create.roblox.com/docs/reference/engine/classes/AudioStreamWriter#WiringChanged) {🚧Audio}
* Update Class [AvatarAccessoryRules](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Property [AvatarAccessoryRules.EnableSpawnEffects](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#EnableSpawnEffects): bool {🚧Read: AvatarAppearance | Write: AvatarAppearance} [⚡ThreadSafety: ReadSafe]
* Update Class [AvatarCollisionRules](https://create.roblox.com/docs/reference/engine/classes/AvatarCollisionRules) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the security of Property [AvatarCollisionRules.HitAndTouchDetectionMode](https://create.roblox.com/docs/reference/engine/classes/AvatarCollisionRules#HitAndTouchDetectionMode)
    from: {🔒None}
    to: {🔒RobloxScriptSecurity}
  * Changed the serialization of Property [AvatarCollisionRules.HitAndTouchDetectionMode](https://create.roblox.com/docs/reference/engine/classes/AvatarCollisionRules#HitAndTouchDetectionMode)
    from: [💾|📁Serialized]
    to: [📁LoadOnly]
  * Added Property [AvatarCollisionRules.HitboxSize](https://create.roblox.com/docs/reference/engine/classes/AvatarCollisionRules#HitboxSize): Vector3 {🚧Read: AvatarAppearance} [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarCollisionRules.TouchAndQueryDetectionMode](https://create.roblox.com/docs/reference/engine/classes/AvatarCollisionRules#TouchAndQueryDetectionMode): AvatarSettingsTouchAndQueryDetectionMode {🚧Read: AvatarAppearance} [⚡ThreadSafety: ReadSafe]
* Added Class [AvatarEffectDescription](https://create.roblox.com/docs/reference/engine/classes/AvatarEffectDescription) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Property [AvatarEffectDescription.AssetId](https://create.roblox.com/docs/reference/engine/classes/AvatarEffectDescription#AssetId) {🚧Read: AvatarAppearance | Write: AvatarAppearance} [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarEffectDescription.EffectType](https://create.roblox.com/docs/reference/engine/classes/AvatarEffectDescription#EffectType) {🚧Read: AvatarAppearance | Write: AvatarAppearance} [⚡ThreadSafety: ReadSafe]
* Update Class [BaseWrap](https://create.roblox.com/docs/reference/engine/classes/BaseWrap) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed the security of Property [BaseWrap.CageMeshContent](https://create.roblox.com/docs/reference/engine/classes/BaseWrap#CageMeshContent)
    from: {🔒Read:None, Write:PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [BaseWrap.CageMeshContent](https://create.roblox.com/docs/reference/engine/classes/BaseWrap#CageMeshContent)
    from: {🚧Read: AvatarAppearance}
    to: {🚧Read: AvatarAppearance | Write: PluginOrOpenCloud}
  * Changed the security of Property [BaseWrap.CageMeshId](https://create.roblox.com/docs/reference/engine/classes/BaseWrap#CageMeshId)
    from: {🔒Read:None, Write:PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [BaseWrap.CageMeshId](https://create.roblox.com/docs/reference/engine/classes/BaseWrap#CageMeshId)
    from: {🚧Read: AvatarAppearance}
    to: {🚧Read: AvatarAppearance | Write: PluginOrOpenCloud}
  * Changed the security of Property [BaseWrap.CageOrigin](https://create.roblox.com/docs/reference/engine/classes/BaseWrap#CageOrigin)
    from: {🔒Read:None, Write:PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [BaseWrap.CageOrigin](https://create.roblox.com/docs/reference/engine/classes/BaseWrap#CageOrigin)
    from: {🚧Read: AvatarAppearance}
    to: {🚧Read: AvatarAppearance | Write: PluginOrOpenCloud}
  * Changed the security of Property [BaseWrap.ImportOrigin](https://create.roblox.com/docs/reference/engine/classes/BaseWrap#ImportOrigin)
    from: {🔒Read:None, Write:PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [BaseWrap.ImportOrigin](https://create.roblox.com/docs/reference/engine/classes/BaseWrap#ImportOrigin)
    from: {🚧Read: AvatarAppearance}
    to: {🚧Read: AvatarAppearance | Write: PluginOrOpenCloud}
* Update Class [WrapLayer](https://create.roblox.com/docs/reference/engine/classes/WrapLayer) [⬆️Extends: BaseWrap] [🧠Memory: Instances]
  * Changed the security of Property [WrapLayer.BindOffset](https://create.roblox.com/docs/reference/engine/classes/WrapLayer#BindOffset)
    from: {🔒Read:None, Write:PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [WrapLayer.BindOffset](https://create.roblox.com/docs/reference/engine/classes/WrapLayer#BindOffset)
    from: {🚧Read: AvatarAppearance}
    to: {🚧Read: AvatarAppearance | Write: PluginOrOpenCloud}
  * Changed the security of Property [WrapLayer.ReferenceMeshContent](https://create.roblox.com/docs/reference/engine/classes/WrapLayer#ReferenceMeshContent)
    from: {🔒Read:None, Write:PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [WrapLayer.ReferenceMeshContent](https://create.roblox.com/docs/reference/engine/classes/WrapLayer#ReferenceMeshContent)
    from: {🚧Read: AvatarAppearance}
    to: {🚧Read: AvatarAppearance | Write: PluginOrOpenCloud}
  * Changed the security of Property [WrapLayer.ReferenceMeshId](https://create.roblox.com/docs/reference/engine/classes/WrapLayer#ReferenceMeshId)
    from: {🔒Read:None, Write:PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [WrapLayer.ReferenceMeshId](https://create.roblox.com/docs/reference/engine/classes/WrapLayer#ReferenceMeshId)
    from: {🚧Read: AvatarAppearance}
    to: {🚧Read: AvatarAppearance | Write: PluginOrOpenCloud}
  * Changed the security of Property [WrapLayer.ReferenceOrigin](https://create.roblox.com/docs/reference/engine/classes/WrapLayer#ReferenceOrigin)
    from: {🔒Read:None, Write:PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [WrapLayer.ReferenceOrigin](https://create.roblox.com/docs/reference/engine/classes/WrapLayer#ReferenceOrigin)
    from: {🚧Read: AvatarAppearance}
    to: {🚧Read: AvatarAppearance | Write: PluginOrOpenCloud}
* Update Class [WrapTarget](https://create.roblox.com/docs/reference/engine/classes/WrapTarget) [⬆️Extends: BaseWrap] [🧠Memory: Instances]
  * Changed the security of Property [WrapTarget.Stiffness](https://create.roblox.com/docs/reference/engine/classes/WrapTarget#Stiffness)
    from: {🔒Read:None, Write:PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [WrapTarget.Stiffness](https://create.roblox.com/docs/reference/engine/classes/WrapTarget#Stiffness)
    from: {🚧Read: AvatarAppearance}
    to: {🚧Read: AvatarAppearance | Write: PluginOrOpenCloud}
* Update Class [Chat](https://create.roblox.com/docs/reference/engine/classes/Chat) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the security of Property [Chat.LoadDefaultChat](https://create.roblox.com/docs/reference/engine/classes/Chat#LoadDefaultChat)
    from: {🔒Read:None, Write:NotAccessibleSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [Chat.LoadDefaultChat](https://create.roblox.com/docs/reference/engine/classes/Chat#LoadDefaultChat)
    from: {🚧Read: Chat}
    to: {🚧Read: Chat | Write: PluginOrOpenCloud}
* Update Class [CloudClientService](https://create.roblox.com/docs/reference/engine/classes/CloudClientService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [CloudClientService.CheckOfferEligibility](https://create.roblox.com/docs/reference/engine/classes/CloudClientService#CheckOfferEligibility) (offerType: string) -> bool
  * Added Function [CloudClientService.CheckOfferEligibilityAsync](https://create.roblox.com/docs/reference/engine/classes/CloudClientService#CheckOfferEligibilityAsync) (offerType: string) -> bool [🏷️ Yields]
  * Added Function [CloudClientService.MakeOfferReservationAsync](https://create.roblox.com/docs/reference/engine/classes/CloudClientService#MakeOfferReservationAsync) (placeId: int64, offerType: string) -> string [🏷️ Yields]
* Update Class [Decal](https://create.roblox.com/docs/reference/engine/classes/Decal) [⬆️Extends: FaceInstance] [🧠Memory: GraphicsTexture]
  * Changed the security of Property [Decal.EmissiveMaskContent](https://create.roblox.com/docs/reference/engine/classes/Decal#EmissiveMaskContent)
    from: {🔒Read:None, Write:PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [Decal.EmissiveMaskContent](https://create.roblox.com/docs/reference/engine/classes/Decal#EmissiveMaskContent)
    from: {🚧Read: Basic}
    to: {🚧Read: Basic | Write: PluginOrOpenCloud}
  * Changed the security of Property [Decal.MetalnessMap](https://create.roblox.com/docs/reference/engine/classes/Decal#MetalnessMap)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [Decal.MetalnessMap](https://create.roblox.com/docs/reference/engine/classes/Decal#MetalnessMap)
    from: {🚧Read: Basic}
    to: {🚧Read: Basic, PluginOrOpenCloud | Write: PluginOrOpenCloud}
  * Changed the security of Property [Decal.MetalnessMapContent](https://create.roblox.com/docs/reference/engine/classes/Decal#MetalnessMapContent)
    from: {🔒Read:None, Write:PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [Decal.MetalnessMapContent](https://create.roblox.com/docs/reference/engine/classes/Decal#MetalnessMapContent)
    from: {🚧Read: Basic}
    to: {🚧Read: Basic | Write: PluginOrOpenCloud}
  * Changed the security of Property [Decal.NormalMap](https://create.roblox.com/docs/reference/engine/classes/Decal#NormalMap)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [Decal.NormalMap](https://create.roblox.com/docs/reference/engine/classes/Decal#NormalMap)
    from: {🚧Read: Basic}
    to: {🚧Read: Basic, PluginOrOpenCloud | Write: PluginOrOpenCloud}
  * Changed the security of Property [Decal.NormalMapContent](https://create.roblox.com/docs/reference/engine/classes/Decal#NormalMapContent)
    from: {🔒Read:None, Write:PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [Decal.NormalMapContent](https://create.roblox.com/docs/reference/engine/classes/Decal#NormalMapContent)
    from: {🚧Read: Basic}
    to: {🚧Read: Basic | Write: PluginOrOpenCloud}
  * Changed the security of Property [Decal.RoughnessMap](https://create.roblox.com/docs/reference/engine/classes/Decal#RoughnessMap)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [Decal.RoughnessMap](https://create.roblox.com/docs/reference/engine/classes/Decal#RoughnessMap)
    from: {🚧Read: Basic}
    to: {🚧Read: Basic, PluginOrOpenCloud | Write: PluginOrOpenCloud}
  * Changed the security of Property [Decal.RoughnessMapContent](https://create.roblox.com/docs/reference/engine/classes/Decal#RoughnessMapContent)
    from: {🔒Read:None, Write:PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [Decal.RoughnessMapContent](https://create.roblox.com/docs/reference/engine/classes/Decal#RoughnessMapContent)
    from: {🚧Read: Basic}
    to: {🚧Read: Basic | Write: PluginOrOpenCloud}
* Update Class [Folder](https://create.roblox.com/docs/reference/engine/classes/Folder) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Property [Folder.ExplorerIconContent](https://create.roblox.com/docs/reference/engine/classes/Folder#ExplorerIconContent): Content {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
* Added Class [FollowRotationBoneBehavior](https://create.roblox.com/docs/reference/engine/classes/FollowRotationBoneBehavior) {🔒None} [⬆️Extends: Instance] [🧠Memory: Animation] [🏷️ NotBrowsable]
  * Added Property [FollowRotationBoneBehavior.CounterRotate](https://create.roblox.com/docs/reference/engine/classes/FollowRotationBoneBehavior#CounterRotate) {🚧Read: InternalTest | Write: InternalTest} [⚡ThreadSafety: ReadSafe]
  * Added Property [FollowRotationBoneBehavior.Driver](https://create.roblox.com/docs/reference/engine/classes/FollowRotationBoneBehavior#Driver) {🚧Read: InternalTest | Write: InternalTest} [⚡ThreadSafety: ReadSafe]
  * Added Property [FollowRotationBoneBehavior.Weight](https://create.roblox.com/docs/reference/engine/classes/FollowRotationBoneBehavior#Weight) {🚧Read: InternalTest | Write: InternalTest} [⚡ThreadSafety: ReadSafe]
* Added Class [FollowTwistBoneBehavior](https://create.roblox.com/docs/reference/engine/classes/FollowTwistBoneBehavior) {🔒None} [⬆️Extends: Instance] [🧠Memory: Animation] [🏷️ NotBrowsable]
  * Added Property [FollowTwistBoneBehavior.Axis](https://create.roblox.com/docs/reference/engine/classes/FollowTwistBoneBehavior#Axis) {🚧Read: InternalTest | Write: InternalTest} [⚡ThreadSafety: ReadSafe]
  * Added Property [FollowTwistBoneBehavior.AxisMode](https://create.roblox.com/docs/reference/engine/classes/FollowTwistBoneBehavior#AxisMode) {🚧Read: InternalTest | Write: InternalTest} [⚡ThreadSafety: ReadSafe]
  * Added Property [FollowTwistBoneBehavior.CounterRotate](https://create.roblox.com/docs/reference/engine/classes/FollowTwistBoneBehavior#CounterRotate) {🚧Read: InternalTest | Write: InternalTest} [⚡ThreadSafety: ReadSafe]
  * Added Property [FollowTwistBoneBehavior.Driver](https://create.roblox.com/docs/reference/engine/classes/FollowTwistBoneBehavior#Driver) {🚧Read: InternalTest | Write: InternalTest} [⚡ThreadSafety: ReadSafe]
  * Added Property [FollowTwistBoneBehavior.EndBone](https://create.roblox.com/docs/reference/engine/classes/FollowTwistBoneBehavior#EndBone) {🚧Read: InternalTest | Write: InternalTest} [⚡ThreadSafety: ReadSafe]
  * Added Property [FollowTwistBoneBehavior.StartBone](https://create.roblox.com/docs/reference/engine/classes/FollowTwistBoneBehavior#StartBone) {🚧Read: InternalTest | Write: InternalTest} [⚡ThreadSafety: ReadSafe]
  * Added Property [FollowTwistBoneBehavior.Weight](https://create.roblox.com/docs/reference/engine/classes/FollowTwistBoneBehavior#Weight) {🚧Read: InternalTest | Write: InternalTest} [⚡ThreadSafety: ReadSafe]
* Added Class [GameDownloaderService](https://create.roblox.com/docs/reference/engine/classes/GameDownloaderService) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [GameDownloaderService.CancelGameDownload](https://create.roblox.com/docs/reference/engine/classes/GameDownloaderService#CancelGameDownload)
  * Added Function [GameDownloaderService.DownloadGame](https://create.roblox.com/docs/reference/engine/classes/GameDownloaderService#DownloadGame)
  * Added Function [GameDownloaderService.GetGameDownloadStatus](https://create.roblox.com/docs/reference/engine/classes/GameDownloaderService#GetGameDownloadStatus)
  * Added Event [GameDownloaderService.DownloadCompleted](https://create.roblox.com/docs/reference/engine/classes/GameDownloaderService#DownloadCompleted)
  * Added Event [GameDownloaderService.DownloadProgressChanged](https://create.roblox.com/docs/reference/engine/classes/GameDownloaderService#DownloadProgressChanged)
* Update Class [GeometryService](https://create.roblox.com/docs/reference/engine/classes/GeometryService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [GeometryService.NegateAsync](https://create.roblox.com/docs/reference/engine/classes/GeometryService#NegateAsync) (parts: Instances) -> Array [🏷️ Yields] {🚧CSG, PluginOrOpenCloud}
  * Added Function [GeometryService.SeparateAsync](https://create.roblox.com/docs/reference/engine/classes/GeometryService#SeparateAsync) (parts: Instances) -> Array [🏷️ Yields] {🚧CSG, PluginOrOpenCloud}
* Update Class [GuiObject](https://create.roblox.com/docs/reference/engine/classes/GuiObject) [⬆️Extends: GuiBase2d] [🧠Memory: Gui] [🏷️ NotCreatable] [🏷️ NotBrowsable]
  * Changed the parameters of Event [GuiObject.SelectionGained](https://create.roblox.com/docs/reference/engine/classes/GuiObject#SelectionGained)
    from: ()
    to: (inputDirection: GuiNavigationDirection)
  * Changed the parameters of Event [GuiObject.SelectionLost](https://create.roblox.com/docs/reference/engine/classes/GuiObject#SelectionLost)
    from: ()
    to: (inputDirection: GuiNavigationDirection)
* Update Class [VideoFrame](https://create.roblox.com/docs/reference/engine/classes/VideoFrame) [⬆️Extends: GuiObject] [🧠Memory: Gui]
  * Added Event [VideoFrame.SubtitlesChanged](https://create.roblox.com/docs/reference/engine/classes/VideoFrame#SubtitlesChanged) {🚧Audio, UI}
* Update Class [QWidgetPluginGui](https://create.roblox.com/docs/reference/engine/classes/QWidgetPluginGui) [⬆️Extends: PluginGui] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Property [QWidgetPluginGui.CloseButtonEnabled](https://create.roblox.com/docs/reference/engine/classes/QWidgetPluginGui#CloseButtonEnabled): bool [🏷️ Hidden] [🏷️ NotReplicated] {🚧Read: UI} [⚡ThreadSafety: ReadSafe]
* Added Class [ModelInfoService](https://create.roblox.com/docs/reference/engine/classes/ModelInfoService) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [ModelInfoService.GetModelTriangleCount](https://create.roblox.com/docs/reference/engine/classes/ModelInfoService#GetModelTriangleCount)
* Update Class [Model](https://create.roblox.com/docs/reference/engine/classes/Model) [⬆️Extends: PVInstance] [🧠Memory: BaseParts]
  * Added Property [Model.ExplorerIconContent](https://create.roblox.com/docs/reference/engine/classes/Model#ExplorerIconContent): Content {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
* Update Class [Workspace](https://create.roblox.com/docs/reference/engine/classes/Workspace) [⬆️Extends: WorldRoot] [🧠Memory: BaseParts] [🏷️ NotCreatable] [🏷️ Service]
  * Removed Property Workspace.ImprovedAnimationConstraint
* Update Class [ParticleEmitter2D](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotBrowsable]
  * Added Property [ParticleEmitter2D.LightInfluence](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D#LightInfluence): float {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
  * Removed Property ParticleEmitter2D.LightEmission
* Update Class [Player](https://create.roblox.com/docs/reference/engine/classes/Player) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Removed Function Player.GetData
* Update Class [PlayerData](https://create.roblox.com/docs/reference/engine/classes/PlayerData) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Removed Function PlayerData.GetPlayer
  * Removed Function PlayerData.GetRecordAsync
* Update Class [PlayerDataService](https://create.roblox.com/docs/reference/engine/classes/PlayerDataService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Removed Property PlayerDataService.LoadFailureBehavior
  * Removed Function PlayerDataService.GetRecordConfig
* Update Class [RealtimeMedia](https://create.roblox.com/docs/reference/engine/classes/RealtimeMedia) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the parameters of Event [RealtimeMedia.Disconnected](https://create.roblox.com/docs/reference/engine/classes/RealtimeMedia#Disconnected)
    from: (expected: bool)
    to: (expected: bool, reason: string)
* Update Class [PhysicsActivitySensor](https://create.roblox.com/docs/reference/engine/classes/PhysicsActivitySensor) [⬆️Extends: SensorBase] [🧠Memory: Instances] [🏷️ NotBrowsable]
  * Changed the capabilities of Property [PhysicsActivitySensor.Active](https://create.roblox.com/docs/reference/engine/classes/PhysicsActivitySensor#Active)
    from: {🚧Read: InternalTest | Write: InternalTest}
    to: {🚧Read: Basic | Write: Basic}
  * Changed the capabilities of Property [PhysicsActivitySensor.Position](https://create.roblox.com/docs/reference/engine/classes/PhysicsActivitySensor#Position)
    from: {🚧Read: InternalTest | Write: InternalTest}
    to: {🚧Read: Basic | Write: Basic}
  * Changed the serialization of Property [PhysicsActivitySensor.Position](https://create.roblox.com/docs/reference/engine/classes/PhysicsActivitySensor#Position)
    from: [💾|📁Serialized]
    to: [🚫None]
  * Changed the capabilities of Property [PhysicsActivitySensor.Size](https://create.roblox.com/docs/reference/engine/classes/PhysicsActivitySensor#Size)
    from: {🚧Read: InternalTest | Write: InternalTest}
    to: {🚧Read: Basic | Write: Basic}
  * Changed the serialization of Property [PhysicsActivitySensor.Size](https://create.roblox.com/docs/reference/engine/classes/PhysicsActivitySensor#Size)
    from: [💾|📁Serialized]
    to: [🚫None]
* Update Class [DataModel](https://create.roblox.com/docs/reference/engine/classes/DataModel) [⬆️Extends: ServiceProvider] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Added Property [DataModel.ServerRegion](https://create.roblox.com/docs/reference/engine/classes/DataModel#ServerRegion): string [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
* Update Class [SocialService](https://create.roblox.com/docs/reference/engine/classes/SocialService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [SocialService.RateExperiencePromptCompleted](https://create.roblox.com/docs/reference/engine/classes/SocialService#RateExperiencePromptCompleted) (result: ExperienceRatingResult) -> null {🚧Social}
  * Added Function [SocialService.PromptRateExperienceAsync](https://create.roblox.com/docs/reference/engine/classes/SocialService#PromptRateExperienceAsync) () -> ExperienceRatingResult [🏷️ Yields] {🚧Social}
  * Added Event [SocialService.ShowRateExperiencePrompt](https://create.roblox.com/docs/reference/engine/classes/SocialService#ShowRateExperiencePrompt) {🚧Social}
* Update Class [Studio](https://create.roblox.com/docs/reference/engine/classes/Studio) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Property [Studio.Enable Flag Editor](https://create.roblox.com/docs/reference/engine/classes/Studio#Enable%20Flag%20Editor): bool [⚡ThreadSafety: ReadSafe]
* Update Class [TextDocument](https://create.roblox.com/docs/reference/engine/classes/TextDocument) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotBrowsable]
  * Added Function [TextDocument.ReadAsync](https://create.roblox.com/docs/reference/engine/classes/TextDocument#ReadAsync) () -> string [🏷️ Yields] {🚧PluginOrOpenCloud}
* Update Class [UGCValidationService](https://create.roblox.com/docs/reference/engine/classes/UGCValidationService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Removed Function UGCValidationService.ValidateEditableMeshCageNonManifoldAndHoles
  * Removed Function UGCValidationService.ValidateEditableMeshFullBodyCageDeletion
  * Removed Function UGCValidationService.ValidateEditableMeshTriangles
* Update Class [UserInputService](https://create.roblox.com/docs/reference/engine/classes/UserInputService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the parameters of Function [UserInputService.CreateVirtualInput](https://create.roblox.com/docs/reference/engine/classes/UserInputService#CreateVirtualInput)
    from: ()
    to: (target: Instance = nil)
  * Added Function [UserInputService.CreateVirtualInputForPluginGuiId](https://create.roblox.com/docs/reference/engine/classes/UserInputService#CreateVirtualInputForPluginGuiId) (pluginGuiId: string) -> Object {🚧Input}
* Update Class [VoiceChatService](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the security of Property [VoiceChatService.DefaultDistanceAttenuation](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#DefaultDistanceAttenuation)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [VoiceChatService.DefaultDistanceAttenuation](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#DefaultDistanceAttenuation)
    from: {🚧Read: Audio, Chat}
    to: {🚧Read: Audio, Chat, PluginOrOpenCloud | Write: PluginOrOpenCloud}
  * Changed the security of Property [VoiceChatService.EnableDefaultVoice](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#EnableDefaultVoice)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [VoiceChatService.EnableDefaultVoice](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#EnableDefaultVoice)
    from: {🚧Read: Audio, Chat}
    to: {🚧Read: Audio, Chat, PluginOrOpenCloud | Write: PluginOrOpenCloud}
  * Changed the security of Property [VoiceChatService.UseAudioApi](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#UseAudioApi)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [VoiceChatService.UseAudioApi](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#UseAudioApi)
    from: {🚧Read: Audio, Chat}
    to: {🚧Read: Audio, Chat, PluginOrOpenCloud | Write: PluginOrOpenCloud}
* Removed Class PlayerDataRecord
* Removed Class PlayerDataRecordConfig
* Update Enum [AppShellActionType](https://create.roblox.com/docs/reference/engine/enums/AppShellActionType)
  * Added EnumItem `TapCampaignPageTab` (12)
  * Added EnumItem `CampaignPageLoaded` (13)
* Update Enum [AssetType](https://create.roblox.com/docs/reference/engine/enums/AssetType)
  * Added EnumItem `ComputeFunction` (96)
  * Added EnumItem `SpawnEffect` (97)
* Update Enum [AvatarAssetType](https://create.roblox.com/docs/reference/engine/enums/AvatarAssetType)
  * Added EnumItem `SpawnEffect` (97)
* Added Enum [AvatarEffectType](https://create.roblox.com/docs/reference/engine/enums/AvatarEffectType)
  * Added EnumItem `None` (0)
  * Added EnumItem `Spawn` (1)
* Update Enum [AvatarSettingsHitAndTouchDetectionMode](https://create.roblox.com/docs/reference/engine/enums/AvatarSettingsHitAndTouchDetectionMode)
  * Added EnumItem `UseHitbox` (2)
* Added Enum [AvatarSettingsTouchAndQueryDetectionMode](https://create.roblox.com/docs/reference/engine/enums/AvatarSettingsTouchAndQueryDetectionMode)
  * Added EnumItem `UseParts` (0)
  * Added EnumItem `UseCollider` (1)
  * Added EnumItem `UseHitbox` (2)
* Added Enum [ExperienceRatingResult](https://create.roblox.com/docs/reference/engine/enums/ExperienceRatingResult)
  * Added EnumItem `Completed` (1)
  * Added EnumItem `Dismissed` (2)
  * Added EnumItem `NotAllowed` (3)
  * Added EnumItem `Failed` (4)
* Added Enum [FollowTwistBoneAxisMode](https://create.roblox.com/docs/reference/engine/enums/FollowTwistBoneAxisMode)
  * Added EnumItem `Local` (0)
  * Added EnumItem `Follower` (1)
  * Added EnumItem `StartToEndBone` (2)
* Added Enum [GameDownloadPhase](https://create.roblox.com/docs/reference/engine/enums/GameDownloadPhase)
  * Added EnumItem `FetchingManifest` (0)
  * Added EnumItem `CheckingGuards` (1)
  * Added EnumItem `Downloading` (2)
* Added Enum [GameDownloadResult](https://create.roblox.com/docs/reference/engine/enums/GameDownloadResult)
  * Added EnumItem `Success` (0)
  * Added EnumItem `ManifestUnavailable` (1)
  * Added EnumItem `NotEnoughSpace` (2)
  * Added EnumItem `NotOnWiFi` (3)
  * Added EnumItem `NetworkMetered` (4)
  * Added EnumItem `LowPowerMode` (5)
  * Added EnumItem `Moderated` (6)
  * Added EnumItem `NetworkError` (7)
  * Added EnumItem `Cancelled` (8)
* Added Enum [GameDownloadStartResult](https://create.roblox.com/docs/reference/engine/enums/GameDownloadStartResult)
  * Added EnumItem `Started` (0)
  * Added EnumItem `AlreadyDownloading` (1)
  * Added EnumItem `GameDownloadInProgress` (2)
  * Added EnumItem `NotOnWiFi` (3)
  * Added EnumItem `NetworkMetered` (4)
  * Added EnumItem `LowPowerMode` (5)
* Added Enum [GuiNavigationDirection](https://create.roblox.com/docs/reference/engine/enums/GuiNavigationDirection)
  * Added EnumItem `None` (0)
  * Added EnumItem `Up` (1)
  * Added EnumItem `Down` (2)
  * Added EnumItem `Left` (3)
  * Added EnumItem `Right` (4)
  * Added EnumItem `Forward` (5)
  * Added EnumItem `Backward` (6)
* Update Enum [ImageCombineType](https://create.roblox.com/docs/reference/engine/enums/ImageCombineType)
  * Added EnumItem `Darken` (8)
  * Added EnumItem `Lighten` (9)
  * Added EnumItem `Screen` (10)
  * Added EnumItem `Overlay` (11)
  * Added EnumItem `SoftLight` (12)
  * Added EnumItem `HardLight` (13)
  * Added EnumItem `Difference` (14)
* Removed Enum PlayerDataErrorState
* Removed Enum PlayerDataLoadFailureBehavior
