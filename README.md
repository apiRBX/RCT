# Roblox Client Tracker

| Metadata | Details |
| :--- | :--- |
| **Version** | `0.737.0.7371584` |
| **Version Hash** | `version-9fe94fb0e9d84c25` |
| **Official Release Notes** | [Release Notes 737](https://create.roblox.com/docs/release-notes/release-notes-737) |

---

## Changelog

* Update Class [AssetService](https://create.roblox.com/docs/reference/engine/classes/AssetService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [AssetService.PromptCreatePlatformContentAsync](https://create.roblox.com/docs/reference/engine/classes/AssetService#PromptCreatePlatformContentAsync) (player: Player, object: Object, assetType: AssetType) -> Tuple [🏷️ Yields] {🚧AssetCreateUpdate}
  * Changed the parameters of Event [AssetService.OpenPublishResultModal](https://create.roblox.com/docs/reference/engine/classes/AssetService#OpenPublishResultModal)
    from: (resultType: PromptPublishAssetResult)
    to: (resultType: PromptCreatePlatformContentResult)
  * Removed Function AssetService.PromptCreateAssetAsync
  * Removed Event AssetService.OpenCreateResultModal
* Update Class [WrapTarget](https://create.roblox.com/docs/reference/engine/classes/WrapTarget) [⬆️Extends: BaseWrap] [🧠Memory: Instances]
  * Added Function [WrapTarget.CreateTextureInCageSpaceAsync](https://create.roblox.com/docs/reference/engine/classes/WrapTarget#CreateTextureInCageSpaceAsync) (texture: EditableImage, options: Dictionary?) -> EditableImage [🏷️ Yields] {🚧AvatarAppearance, DynamicGeneration}
  * Added Function [WrapTarget.CreateTextureInTargetSpaceAsync](https://create.roblox.com/docs/reference/engine/classes/WrapTarget#CreateTextureInTargetSpaceAsync) (texture: EditableImage, wrapTextureTransfer: WrapTextureTransfer) -> EditableImage [🏷️ Yields] {🚧AvatarAppearance, DynamicGeneration}
* Update Class [BranchService](https://create.roblox.com/docs/reference/engine/classes/BranchService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [BranchService.CompleteMerge](https://create.roblox.com/docs/reference/engine/classes/BranchService#CompleteMerge) () -> null
  * Added Function [BranchService.GetInstanceConflicts](https://create.roblox.com/docs/reference/engine/classes/BranchService#GetInstanceConflicts) () -> Array
  * Added Function [BranchService.GetMergeChanges](https://create.roblox.com/docs/reference/engine/classes/BranchService#GetMergeChanges) () -> DataModelDiff
  * Added Function [BranchService.GetMergeResolution](https://create.roblox.com/docs/reference/engine/classes/BranchService#GetMergeResolution) (identity: ScopedInstanceIdentity, propName: string?) -> MergeResolution
  * Added Function [BranchService.GetMergeStatus](https://create.roblox.com/docs/reference/engine/classes/BranchService#GetMergeStatus) () -> MergeStatus
  * Added Function [BranchService.SetMergeResolution](https://create.roblox.com/docs/reference/engine/classes/BranchService#SetMergeResolution) (identity: ScopedInstanceIdentity, propName: string?, resolution: MergeResolution) -> null
  * Added Function [BranchService.ArchiveBranchAsync](https://create.roblox.com/docs/reference/engine/classes/BranchService#ArchiveBranchAsync) (branchPlaceId: int64) -> null [🏷️ Yields]
  * Added Function [BranchService.CreateBranchAsync](https://create.roblox.com/docs/reference/engine/classes/BranchService#CreateBranchAsync) (sourcePlaceId: int64, sourceVersionNumber: int64, name: string) -> Dictionary [🏷️ Yields]
  * Added Function [BranchService.GetBranchesAsync](https://create.roblox.com/docs/reference/engine/classes/BranchService#GetBranchesAsync) (placeId: int64, archived: bool) -> Dictionary [🏷️ Yields]
  * Added Function [BranchService.GetDiffAsync](https://create.roblox.com/docs/reference/engine/classes/BranchService#GetDiffAsync) (placeId: int64, baseVersion: int64, targetVersion: int64) -> DataModelDiff [🏷️ Yields]
  * Added Function [BranchService.RestoreBranchAsync](https://create.roblox.com/docs/reference/engine/classes/BranchService#RestoreBranchAsync) (branchPlaceId: int64) -> null [🏷️ Yields]
  * Added Function [BranchService.StartMergeAsync](https://create.roblox.com/docs/reference/engine/classes/BranchService#StartMergeAsync) (sourcePlaceId: int64, ancestorVersion: int64) -> null [🏷️ Yields]
  * Added Function [BranchService.UpdateBranchAsync](https://create.roblox.com/docs/reference/engine/classes/BranchService#UpdateBranchAsync) (branchPlaceId: int64, status: BranchStatus, name: string) -> Dictionary [🏷️ Yields]
  * Added Event [BranchService.MergeStateChanged](https://create.roblox.com/docs/reference/engine/classes/BranchService#MergeStateChanged)
  * Added Event [BranchService.MergeStateCleared](https://create.roblox.com/docs/reference/engine/classes/BranchService#MergeStateCleared)
  * Added Event [BranchService.MergeStatusChanged](https://create.roblox.com/docs/reference/engine/classes/BranchService#MergeStatusChanged)
* Added Class [WrapContentProvider](https://create.roblox.com/docs/reference/engine/classes/WrapContentProvider) {🔒None} [⬆️Extends: CacheableContentProvider] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
* Added Class [CallingService](https://create.roblox.com/docs/reference/engine/classes/CallingService) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [CallingService.AnswerIncomingCall](https://create.roblox.com/docs/reference/engine/classes/CallingService#AnswerIncomingCall)
  * Added Function [CallingService.CreateCall](https://create.roblox.com/docs/reference/engine/classes/CallingService#CreateCall)
  * Added Function [CallingService.EndCall](https://create.roblox.com/docs/reference/engine/classes/CallingService#EndCall)
  * Added Function [CallingService.GetCallingState](https://create.roblox.com/docs/reference/engine/classes/CallingService#GetCallingState)
  * Added Event [CallingService.OnCallingRemoved](https://create.roblox.com/docs/reference/engine/classes/CallingService#OnCallingRemoved)
  * Added Event [CallingService.OnCallingStateChange](https://create.roblox.com/docs/reference/engine/classes/CallingService#OnCallingStateChange)
* Update Class [CaptureService](https://create.roblox.com/docs/reference/engine/classes/CaptureService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the parameters of Function [CaptureService.GenerateMomentTextAsync](https://create.roblox.com/docs/reference/engine/classes/CaptureService#GenerateMomentTextAsync)
    from: (capture: Capture)
    to: (capture: Capture, tone: string = )
* Added Class [ControlState](https://create.roblox.com/docs/reference/engine/classes/ControlState) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotBrowsable]
  * Added Property [ControlState.Owner](https://create.roblox.com/docs/reference/engine/classes/ControlState#Owner) [⚡ThreadSafety: ReadSafe]
  * Added Function [ControlState.AddBoolField](https://create.roblox.com/docs/reference/engine/classes/ControlState#AddBoolField)
  * Added Function [ControlState.AddCFrameField](https://create.roblox.com/docs/reference/engine/classes/ControlState#AddCFrameField)
  * Added Function [ControlState.AddInstanceField](https://create.roblox.com/docs/reference/engine/classes/ControlState#AddInstanceField)
  * Added Function [ControlState.AddIntField](https://create.roblox.com/docs/reference/engine/classes/ControlState#AddIntField)
  * Added Function [ControlState.AddNumberField](https://create.roblox.com/docs/reference/engine/classes/ControlState#AddNumberField)
  * Added Function [ControlState.AddUnitVector3Field](https://create.roblox.com/docs/reference/engine/classes/ControlState#AddUnitVector3Field)
  * Added Function [ControlState.AddVector2Field](https://create.roblox.com/docs/reference/engine/classes/ControlState#AddVector2Field)
  * Added Function [ControlState.AddVector3Field](https://create.roblox.com/docs/reference/engine/classes/ControlState#AddVector3Field)
  * Added Function [ControlState.GetChangedState](https://create.roblox.com/docs/reference/engine/classes/ControlState#GetChangedState)
  * Added Function [ControlState.GetReplicationWeight](https://create.roblox.com/docs/reference/engine/classes/ControlState#GetReplicationWeight)
  * Added Function [ControlState.GetState](https://create.roblox.com/docs/reference/engine/classes/ControlState#GetState)
  * Added Function [ControlState.SetField](https://create.roblox.com/docs/reference/engine/classes/ControlState#SetField)
  * Added Function [ControlState.UpdateFields](https://create.roblox.com/docs/reference/engine/classes/ControlState#UpdateFields)
  * Added Event [ControlState.OnStateChanged](https://create.roblox.com/docs/reference/engine/classes/ControlState#OnStateChanged)
* Update Class [FaceControls](https://create.roblox.com/docs/reference/engine/classes/FaceControls) [⬆️Extends: Instance] [🧠Memory: Animation]
  * Changed the security of Property [FaceControls.ChinRaiser](https://create.roblox.com/docs/reference/engine/classes/FaceControls#ChinRaiser)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.ChinRaiserUpperLip](https://create.roblox.com/docs/reference/engine/classes/FaceControls#ChinRaiserUpperLip)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.Corrugator](https://create.roblox.com/docs/reference/engine/classes/FaceControls#Corrugator)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.EyesLookDown](https://create.roblox.com/docs/reference/engine/classes/FaceControls#EyesLookDown)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.EyesLookLeft](https://create.roblox.com/docs/reference/engine/classes/FaceControls#EyesLookLeft)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.EyesLookRight](https://create.roblox.com/docs/reference/engine/classes/FaceControls#EyesLookRight)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.EyesLookUp](https://create.roblox.com/docs/reference/engine/classes/FaceControls#EyesLookUp)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.FlatPucker](https://create.roblox.com/docs/reference/engine/classes/FaceControls#FlatPucker)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.Funneler](https://create.roblox.com/docs/reference/engine/classes/FaceControls#Funneler)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.JawDrop](https://create.roblox.com/docs/reference/engine/classes/FaceControls#JawDrop)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.JawLeft](https://create.roblox.com/docs/reference/engine/classes/FaceControls#JawLeft)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.JawRight](https://create.roblox.com/docs/reference/engine/classes/FaceControls#JawRight)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.LeftBrowLowerer](https://create.roblox.com/docs/reference/engine/classes/FaceControls#LeftBrowLowerer)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.LeftCheekPuff](https://create.roblox.com/docs/reference/engine/classes/FaceControls#LeftCheekPuff)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.LeftCheekRaiser](https://create.roblox.com/docs/reference/engine/classes/FaceControls#LeftCheekRaiser)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.LeftDimpler](https://create.roblox.com/docs/reference/engine/classes/FaceControls#LeftDimpler)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.LeftEyeClosed](https://create.roblox.com/docs/reference/engine/classes/FaceControls#LeftEyeClosed)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.LeftEyeUpperLidRaiser](https://create.roblox.com/docs/reference/engine/classes/FaceControls#LeftEyeUpperLidRaiser)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.LeftInnerBrowRaiser](https://create.roblox.com/docs/reference/engine/classes/FaceControls#LeftInnerBrowRaiser)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.LeftLipCornerDown](https://create.roblox.com/docs/reference/engine/classes/FaceControls#LeftLipCornerDown)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.LeftLipCornerPuller](https://create.roblox.com/docs/reference/engine/classes/FaceControls#LeftLipCornerPuller)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.LeftLipStretcher](https://create.roblox.com/docs/reference/engine/classes/FaceControls#LeftLipStretcher)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.LeftLowerLipDepressor](https://create.roblox.com/docs/reference/engine/classes/FaceControls#LeftLowerLipDepressor)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.LeftNoseWrinkler](https://create.roblox.com/docs/reference/engine/classes/FaceControls#LeftNoseWrinkler)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.LeftOuterBrowRaiser](https://create.roblox.com/docs/reference/engine/classes/FaceControls#LeftOuterBrowRaiser)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.LeftUpperLipRaiser](https://create.roblox.com/docs/reference/engine/classes/FaceControls#LeftUpperLipRaiser)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.LipPresser](https://create.roblox.com/docs/reference/engine/classes/FaceControls#LipPresser)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.LipsTogether](https://create.roblox.com/docs/reference/engine/classes/FaceControls#LipsTogether)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.LowerLipSuck](https://create.roblox.com/docs/reference/engine/classes/FaceControls#LowerLipSuck)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.MouthLeft](https://create.roblox.com/docs/reference/engine/classes/FaceControls#MouthLeft)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.MouthRight](https://create.roblox.com/docs/reference/engine/classes/FaceControls#MouthRight)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.Pucker](https://create.roblox.com/docs/reference/engine/classes/FaceControls#Pucker)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.RightBrowLowerer](https://create.roblox.com/docs/reference/engine/classes/FaceControls#RightBrowLowerer)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.RightCheekPuff](https://create.roblox.com/docs/reference/engine/classes/FaceControls#RightCheekPuff)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.RightCheekRaiser](https://create.roblox.com/docs/reference/engine/classes/FaceControls#RightCheekRaiser)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.RightDimpler](https://create.roblox.com/docs/reference/engine/classes/FaceControls#RightDimpler)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.RightEyeClosed](https://create.roblox.com/docs/reference/engine/classes/FaceControls#RightEyeClosed)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.RightEyeUpperLidRaiser](https://create.roblox.com/docs/reference/engine/classes/FaceControls#RightEyeUpperLidRaiser)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.RightInnerBrowRaiser](https://create.roblox.com/docs/reference/engine/classes/FaceControls#RightInnerBrowRaiser)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.RightLipCornerDown](https://create.roblox.com/docs/reference/engine/classes/FaceControls#RightLipCornerDown)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.RightLipCornerPuller](https://create.roblox.com/docs/reference/engine/classes/FaceControls#RightLipCornerPuller)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.RightLipStretcher](https://create.roblox.com/docs/reference/engine/classes/FaceControls#RightLipStretcher)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.RightLowerLipDepressor](https://create.roblox.com/docs/reference/engine/classes/FaceControls#RightLowerLipDepressor)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.RightNoseWrinkler](https://create.roblox.com/docs/reference/engine/classes/FaceControls#RightNoseWrinkler)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.RightOuterBrowRaiser](https://create.roblox.com/docs/reference/engine/classes/FaceControls#RightOuterBrowRaiser)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.RightUpperLipRaiser](https://create.roblox.com/docs/reference/engine/classes/FaceControls#RightUpperLipRaiser)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.TongueDown](https://create.roblox.com/docs/reference/engine/classes/FaceControls#TongueDown)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.TongueOut](https://create.roblox.com/docs/reference/engine/classes/FaceControls#TongueOut)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.TongueUp](https://create.roblox.com/docs/reference/engine/classes/FaceControls#TongueUp)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the security of Property [FaceControls.UpperLipSuck](https://create.roblox.com/docs/reference/engine/classes/FaceControls#UpperLipSuck)
    from: {🔒PluginSecurity}
    to: {🔒None}
* Update Class [GenerationService](https://create.roblox.com/docs/reference/engine/classes/GenerationService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [GenerationService.ExportInstanceToGlbAsync](https://create.roblox.com/docs/reference/engine/classes/GenerationService#ExportInstanceToGlbAsync) (rootInstance: Instance, userId: int64) -> string [🏷️ Yields] {🚧DynamicGeneration}
* Update Class [GeometryService](https://create.roblox.com/docs/reference/engine/classes/GeometryService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [GeometryService.CreateBasicMeshPart](https://create.roblox.com/docs/reference/engine/classes/GeometryService#CreateBasicMeshPart) (shape: BasicMeshPartShape, options: Dictionary = nil) -> MeshPart {🚧CSG, InternalTest}
  * Removed Function GeometryService.CreateSolidPrimitive
* Update Class [GuiObject](https://create.roblox.com/docs/reference/engine/classes/GuiObject) [⬆️Extends: GuiBase2d] [🧠Memory: Gui] [🏷️ NotCreatable] [🏷️ NotBrowsable]
  * Changed the serialization of Property [GuiObject.InputSink](https://create.roblox.com/docs/reference/engine/classes/GuiObject#InputSink)
    from: [💾|📁Serialized]
    to: [🚫None]
* Update Class [TextChannelWindow](https://create.roblox.com/docs/reference/engine/classes/TextChannelWindow) [⬆️Extends: GuiObject] [🧠Memory: Gui] [🏷️ NotBrowsable]
  * Added Property [TextChannelWindow.FontFace](https://create.roblox.com/docs/reference/engine/classes/TextChannelWindow#FontFace): Font {🚧Read: UI, Chat} [⚡ThreadSafety: ReadSafe]
  * Added Property [TextChannelWindow.UseDefaultFont](https://create.roblox.com/docs/reference/engine/classes/TextChannelWindow#UseDefaultFont): bool {🚧Read: UI, Chat} [⚡ThreadSafety: ReadSafe]
* Update Class [GuiService](https://create.roblox.com/docs/reference/engine/classes/GuiService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [GuiService.GetAutoUIScaleHundredths](https://create.roblox.com/docs/reference/engine/classes/GuiService#GetAutoUIScaleHundredths) () -> int {🚧UI}
  * Added Function [GuiService.GetEffectiveUIScaleHundredths](https://create.roblox.com/docs/reference/engine/classes/GuiService#GetEffectiveUIScaleHundredths) () -> int {🚧UI}
  * Added Event [GuiService.ScrollStateChanged](https://create.roblox.com/docs/reference/engine/classes/GuiService#ScrollStateChanged) {🚧UI}
  * Removed Function GuiService.GetUIScaleMultiplier
* Update Class [Terrain](https://create.roblox.com/docs/reference/engine/classes/Terrain) [⬆️Extends: BasePart] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Added Function [Terrain.SmoothRegionMaterialSlots](https://create.roblox.com/docs/reference/engine/classes/Terrain#SmoothRegionMaterialSlots) (region: Region3, resolution: float, strength: float) -> Tuple [🏷️ CustomLuaState] {🚧Environment} [⚡ThreadSafety: Safe]
  * Added Event [Terrain.GridBackendReloadRequired](https://create.roblox.com/docs/reference/engine/classes/Terrain#GridBackendReloadRequired) {🚧Environment}
* Update Class [WorldRoot](https://create.roblox.com/docs/reference/engine/classes/WorldRoot) [⬆️Extends: Model] [🧠Memory: BaseParts] [🏷️ NotCreatable]
  * Added Property [WorldRoot.AutoSimulate](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#AutoSimulate): bool [🏷️ Hidden] [⚡ThreadSafety: ReadSafe]
  * Added Property [WorldRoot.GravityDirection](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#GravityDirection): Vector3 [🏷️ Hidden] [⚡ThreadSafety: ReadSafe]
  * Added Property [WorldRoot.SimulationRate](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#SimulationRate): float [🏷️ Hidden] [⚡ThreadSafety: ReadSafe]
  * Added Property [WorldRoot.Wind](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#Wind): float [🏷️ Hidden] [⚡ThreadSafety: ReadSafe]
  * Added Property [WorldRoot.WindDirection](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#WindDirection): Vector3 [🏷️ Hidden] [⚡ThreadSafety: ReadSafe]
  * Added Function [WorldRoot.Simulate](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#Simulate) (dt: float) -> null
* Update Class [Workspace](https://create.roblox.com/docs/reference/engine/classes/Workspace) [⬆️Extends: WorldRoot] [🧠Memory: BaseParts] [🏷️ NotCreatable] [🏷️ Service]
  * Added Property [Workspace.UseInputSink](https://create.roblox.com/docs/reference/engine/classes/Workspace#UseInputSink): RolloutState [🏷️ NotScriptable] [⚡ThreadSafety: ReadSafe]
* Update Class [PublishService](https://create.roblox.com/docs/reference/engine/classes/PublishService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the parameters of Function [PublishService.CreateAssetAndWaitForAssetId](https://create.roblox.com/docs/reference/engine/classes/PublishService#CreateAssetAndWaitForAssetId)
    from: (instances: Instances, operationId: string, creatorType: AssetCreatorType, creatorId: int64, assetType: string, name: string, description: string, expectedPrice: int = 0)
    to: (instances: Instances, operationId: string, creatorType: AssetCreatorType, creatorId: int64, assetType: string, name: string, description: string, expectedPrice: int = 0, additionalParameters: Dictionary = nil)
* Update Class [DataModel](https://create.roblox.com/docs/reference/engine/classes/DataModel) [⬆️Extends: ServiceProvider] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Added Function [DataModel.GetPioneerRootPlaceId](https://create.roblox.com/docs/reference/engine/classes/DataModel#GetPioneerRootPlaceId) () -> int64
  * Added Function [DataModel.GetPioneerSource](https://create.roblox.com/docs/reference/engine/classes/DataModel#GetPioneerSource) () -> PioneerSource
  * Added Function [DataModel.IsPioneerApp](https://create.roblox.com/docs/reference/engine/classes/DataModel#IsPioneerApp) () -> bool
* Update Class [StudioDeviceSimulatorService](https://create.roblox.com/docs/reference/engine/classes/StudioDeviceSimulatorService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Removed Function StudioDeviceSimulatorService.GetRegisteredSimulators
  * Removed Function StudioDeviceSimulatorService.RegisterSimulator
  * Removed Function StudioDeviceSimulatorService.UnregisterSimulator
  * Removed Event StudioDeviceSimulatorService.SimulatorRegistryChanged
* Update Class [SystemThemeService](https://create.roblox.com/docs/reference/engine/classes/SystemThemeService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [SystemThemeService.setClassicThemeActive](https://create.roblox.com/docs/reference/engine/classes/SystemThemeService#setClassicThemeActive) (active: bool) -> null
* Update Class [TweenService](https://create.roblox.com/docs/reference/engine/classes/TweenService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed ThreadSafety of Function [TweenService.GetValue](https://create.roblox.com/docs/reference/engine/classes/TweenService#GetValue) from `Unsafe` to `Safe`
* Update Class [UGCValidationService](https://create.roblox.com/docs/reference/engine/classes/UGCValidationService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [UGCValidationService.GetSerializedSizeExcludingCollisionAsync](https://create.roblox.com/docs/reference/engine/classes/UGCValidationService#GetSerializedSizeExcludingCollisionAsync) (inputInstances: Instances) -> double [🏷️ Yields]
* Removed Class PlayerControlState
* Added Enum [AudioSampleFormat](https://create.roblox.com/docs/reference/engine/enums/AudioSampleFormat)
  * Added EnumItem `Int16` (0)
  * Added EnumItem `Float32` (1)
* Added Enum [BasicMeshPartShape](https://create.roblox.com/docs/reference/engine/enums/BasicMeshPartShape)
  * Added EnumItem `Capsule` (5)
  * Added EnumItem `Cone` (6)
  * Added EnumItem `RoundedBox` (7)
* Added Enum [BranchStatus](https://create.roblox.com/docs/reference/engine/enums/BranchStatus)
  * Added EnumItem `Draft` (0)
  * Added EnumItem `ReadyToMerge` (1)
  * Added EnumItem `Merged` (2)
  * Added EnumItem `Archived` (3)
* Added Enum [MergeResolution](https://create.roblox.com/docs/reference/engine/enums/MergeResolution)
  * Added EnumItem `None` (0)
  * Added EnumItem `UseSource` (1)
  * Added EnumItem `UseTarget` (2)
  * Added EnumItem `Manual` (3)
* Added Enum [MergeStatus](https://create.roblox.com/docs/reference/engine/enums/MergeStatus)
  * Added EnumItem `None` (0)
  * Added EnumItem `Loading` (1)
  * Added EnumItem `Merging` (2)
* Added Enum [PromptCreatePlatformContentResult](https://create.roblox.com/docs/reference/engine/enums/PromptCreatePlatformContentResult)
  * Added EnumItem `Success` (1)
  * Added EnumItem `PermissionDenied` (2)
  * Added EnumItem `Timeout` (3)
  * Added EnumItem `UploadFailed` (4)
  * Added EnumItem `NoUserInput` (5)
  * Added EnumItem `UnknownFailure` (6)
  * Added EnumItem `UGCValidationFailed` (7)
  * Added EnumItem `ModeratedName` (8)
  * Added EnumItem `PurchaseFailure` (9)
  * Added EnumItem `TokenInvalid` (10)
* Added Enum [ScrollState](https://create.roblox.com/docs/reference/engine/enums/ScrollState)
  * Added EnumItem `Idle` (0)
  * Added EnumItem `Scrolling` (1)
* Update Enum [SlimTintMode](https://create.roblox.com/docs/reference/engine/enums/SlimTintMode)
  * Added EnumItem `LevelOfDetail` (1)
  * Added EnumItem `DataModelState` (5)
  * Removed EnumItem `LOD`
  * Removed EnumItem `Zone`
* Update Enum [SlimTranscoderStatus](https://create.roblox.com/docs/reference/engine/enums/SlimTranscoderStatus)
  * Added EnumItem `Transcoding` (1)
  * Changed Value of EnumItem `Succeeded` from `5` to `2`
  * Changed Value of EnumItem `Failed` from `6` to `3`
  * Removed EnumItem `NoHash`
  * Removed EnumItem `NotUploaded`
  * Removed EnumItem `Uploaded`
  * Removed EnumItem `InProgress`
* Update Enum [TeleportMethod](https://create.roblox.com/docs/reference/engine/enums/TeleportMethod)
  * Added EnumItem `Teleport` (7)
* Removed Enum SolidPrimitiveType
