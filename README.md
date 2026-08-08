# Roblox API Tracker (Development)

| Metadata | Details |
| :--- | :--- |
| **Version** | `0.732.0.7321040` |
| **Version Hash** | `version-ff6341faef444107` |
| **Official Release Notes** | [Release Notes 732](https://create.roblox.com/docs/release-notes/release-notes-732) |

---

## API Changelog

* Update Class [EditableMesh](https://create.roblox.com/docs/reference/engine/classes/EditableMesh) [⬆️Extends: Object] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Added Function [EditableMesh.BatchAdd](https://create.roblox.com/docs/reference/engine/classes/EditableMesh#BatchAdd) (attr: MeshAttribute, data: Array) -> Array [🏷️ CustomLuaState] {🚧DynamicGeneration}
  * Added Function [EditableMesh.BatchGetFaceAttributes](https://create.roblox.com/docs/reference/engine/classes/EditableMesh#BatchGetFaceAttributes) (attr: MeshAttribute, faceIds: Array) -> Array [🏷️ CustomLuaState] {🚧DynamicGeneration}
  * Added Function [EditableMesh.BatchGetValues](https://create.roblox.com/docs/reference/engine/classes/EditableMesh#BatchGetValues) (ids: Array) -> Tuple [🏷️ CustomLuaState] {🚧DynamicGeneration}
  * Added Function [EditableMesh.BatchGetVertexAttributes](https://create.roblox.com/docs/reference/engine/classes/EditableMesh#BatchGetVertexAttributes) (attr: MeshAttribute, vertexIds: Array) -> Array [🏷️ CustomLuaState] {🚧DynamicGeneration}
  * Added Function [EditableMesh.BatchGetVertexFaceAttributes](https://create.roblox.com/docs/reference/engine/classes/EditableMesh#BatchGetVertexFaceAttributes) (attr: MeshAttribute, vertexIds: Array, faceIds: Array) -> Array [🏷️ CustomLuaState] {🚧DynamicGeneration}
  * Added Function [EditableMesh.BatchRemove](https://create.roblox.com/docs/reference/engine/classes/EditableMesh#BatchRemove) (ids: Array) -> null [🏷️ CustomLuaState] {🚧DynamicGeneration}
  * Added Function [EditableMesh.BatchSetFaceAttributes](https://create.roblox.com/docs/reference/engine/classes/EditableMesh#BatchSetFaceAttributes) (faceIds: Array, attrIdArrays: Array) -> null [🏷️ CustomLuaState] {🚧DynamicGeneration}
  * Added Function [EditableMesh.BatchSetValues](https://create.roblox.com/docs/reference/engine/classes/EditableMesh#BatchSetValues) (ids: Array, values: Array) -> null [🏷️ CustomLuaState] {🚧DynamicGeneration}
  * Added Function [EditableMesh.BatchSetVertexFaceAttributes](https://create.roblox.com/docs/reference/engine/classes/EditableMesh#BatchSetVertexFaceAttributes) (vertexIds: Array, faceIds: Array, attrIds: Array) -> null [🏷️ CustomLuaState] {🚧DynamicGeneration}
* Update Class [AdService](https://create.roblox.com/docs/reference/engine/classes/AdService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [AdService.IsAdLoaded](https://create.roblox.com/docs/reference/engine/classes/AdService#IsAdLoaded) (adFormat: AdFormat) -> bool {🚧Monetization}
* Update Class [AssetService](https://create.roblox.com/docs/reference/engine/classes/AssetService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [AssetService.CreateEditableImageFromDownloadAsync](https://create.roblox.com/docs/reference/engine/classes/AssetService#CreateEditableImageFromDownloadAsync) (url: string) -> EditableImage [🏷️ Yields]
* Update Class [AudioEmitter](https://create.roblox.com/docs/reference/engine/classes/AudioEmitter) [⬆️Extends: Instance] [🧠Memory: Internal]
  * Added Property [AudioEmitter.DistanceAttenuationBounds](https://create.roblox.com/docs/reference/engine/classes/AudioEmitter#DistanceAttenuationBounds): NumberRange {🚧Read: Audio | Write: Audio} [⚡ThreadSafety: ReadSafe]
  * Added Property [AudioEmitter.DistanceAttenuationMode](https://create.roblox.com/docs/reference/engine/classes/AudioEmitter#DistanceAttenuationMode): DistanceAttenuationMode {🚧Read: Audio | Write: Audio} [⚡ThreadSafety: ReadSafe]
* Update Class [AvatarCreationService](https://create.roblox.com/docs/reference/engine/classes/AvatarCreationService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Event [AvatarCreationService.AvatarOutfitModerationCompleted](https://create.roblox.com/docs/reference/engine/classes/AvatarCreationService#AvatarOutfitModerationCompleted) {🚧DynamicGeneration}
* Update Class [BadgeService](https://create.roblox.com/docs/reference/engine/classes/BadgeService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [BadgeService.GetUserBadgesAsync](https://create.roblox.com/docs/reference/engine/classes/BadgeService#GetUserBadgesAsync) (userId: User, badgeIds: Array) -> Array [🏷️ Yields] {🚧AssetManagement}
* Update Class [MaterialImportData](https://create.roblox.com/docs/reference/engine/classes/MaterialImportData) [⬆️Extends: BaseImportData] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Property [MaterialImportData.DiffuseVersionedAssetId](https://create.roblox.com/docs/reference/engine/classes/MaterialImportData#DiffuseVersionedAssetId): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [MaterialImportData.EmissiveVersionedAssetId](https://create.roblox.com/docs/reference/engine/classes/MaterialImportData#EmissiveVersionedAssetId): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [MaterialImportData.MetalnessVersionedAssetId](https://create.roblox.com/docs/reference/engine/classes/MaterialImportData#MetalnessVersionedAssetId): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [MaterialImportData.NormalVersionedAssetId](https://create.roblox.com/docs/reference/engine/classes/MaterialImportData#NormalVersionedAssetId): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [MaterialImportData.RoughnessVersionedAssetId](https://create.roblox.com/docs/reference/engine/classes/MaterialImportData#RoughnessVersionedAssetId): int64 [⚡ThreadSafety: ReadSafe]
* Update Class [MeshImportData](https://create.roblox.com/docs/reference/engine/classes/MeshImportData) [⬆️Extends: BaseImportData] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Property [MeshImportData.VersionedAssetId](https://create.roblox.com/docs/reference/engine/classes/MeshImportData#VersionedAssetId): int64 [⚡ThreadSafety: ReadSafe]
* Update Class [BaseWrap](https://create.roblox.com/docs/reference/engine/classes/BaseWrap) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Added Property [BaseWrap.HSRContent](https://create.roblox.com/docs/reference/engine/classes/BaseWrap#HSRContent): Content {🚧Read: AvatarAppearance} [⚡ThreadSafety: ReadSafe]
* Update Class [CaptureService](https://create.roblox.com/docs/reference/engine/classes/CaptureService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [CaptureService.CheckMomentTextStatusAsync](https://create.roblox.com/docs/reference/engine/classes/CaptureService#CheckMomentTextStatusAsync) (token: string) -> Tuple [🏷️ Yields] {🚧Capture}
  * Added Function [CaptureService.GenerateMomentTextAsync](https://create.roblox.com/docs/reference/engine/classes/CaptureService#GenerateMomentTextAsync) (capture: Capture) -> Tuple [🏷️ Yields] {🚧Capture}
  * Added Function [CaptureService.UploadPostAsync](https://create.roblox.com/docs/reference/engine/classes/CaptureService#UploadPostAsync) (capture: Capture, postMetadata: Dictionary = nil) -> Dictionary [🏷️ Yields] {🚧Capture}
* Update Class [CollectionService](https://create.roblox.com/docs/reference/engine/classes/CollectionService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [CollectionService.GetTagAddedSignal](https://create.roblox.com/docs/reference/engine/classes/CollectionService#GetTagAddedSignal) (instance: Instance) -> RBXScriptSignal {🚧Basic}
  * Added Function [CollectionService.GetTagRemovedSignal](https://create.roblox.com/docs/reference/engine/classes/CollectionService#GetTagRemovedSignal) (instance: Instance) -> RBXScriptSignal {🚧Basic}
* Update Class [ContextActionService](https://create.roblox.com/docs/reference/engine/classes/ContextActionService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the parameters of Function [ContextActionService.UnbindActivate](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#UnbindActivate)
    from: (userInputTypeForActivation: UserInputType, keyCodeForActivation: KeyCode = Unknown)
    to: (userInputTypeForActivation: UserInputType, keyCodeForActivation: KeyCode = None)
  * Changed the parameters of Function [ContextActionService.UnbindCoreActivate](https://create.roblox.com/docs/reference/engine/classes/ContextActionService#UnbindCoreActivate)
    from: (userInputTypeForActivation: UserInputType, keyCodeForActivation: KeyCode = Unknown)
    to: (userInputTypeForActivation: UserInputType, keyCodeForActivation: KeyCode = None)
* Update Class [DraggerService](https://create.roblox.com/docs/reference/engine/classes/DraggerService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Property [DraggerService.UseBoundingBoxes](https://create.roblox.com/docs/reference/engine/classes/DraggerService#UseBoundingBoxes): bool [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
* Update Class [Decal](https://create.roblox.com/docs/reference/engine/classes/Decal) [⬆️Extends: FaceInstance] [🧠Memory: GraphicsTexture]
  * Added Property [Decal.TexturePackContent](https://create.roblox.com/docs/reference/engine/classes/Decal#TexturePackContent): Content {🚧Read: Basic} [⚡ThreadSafety: ReadSafe]
* Update Class [GenerationService](https://create.roblox.com/docs/reference/engine/classes/GenerationService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [GenerationService.SegmentMeshAsync](https://create.roblox.com/docs/reference/engine/classes/GenerationService#SegmentMeshAsync) (meshPart: MeshPart, schema: Dictionary, options: Dictionary?) -> Tuple [🏷️ Yields] {🚧DynamicGeneration}
* Added Class [InputActionLabel](https://create.roblox.com/docs/reference/engine/classes/InputActionLabel) {🔒None} [⬆️Extends: GuiObject] [🧠Memory: Gui]
  * Added Property [InputActionLabel.FontFace](https://create.roblox.com/docs/reference/engine/classes/InputActionLabel#FontFace) {🚧Read: UI} [⚡ThreadSafety: ReadSafe]
  * Added Property [InputActionLabel.ImageColor3](https://create.roblox.com/docs/reference/engine/classes/InputActionLabel#ImageColor3) {🚧Read: UI} [⚡ThreadSafety: ReadSafe]
  * Added Property [InputActionLabel.ImageTransparency](https://create.roblox.com/docs/reference/engine/classes/InputActionLabel#ImageTransparency) {🚧Read: UI} [⚡ThreadSafety: ReadSafe]
  * Added Property [InputActionLabel.InputAction](https://create.roblox.com/docs/reference/engine/classes/InputActionLabel#InputAction) {🚧Read: UI} [⚡ThreadSafety: ReadSafe]
  * Added Property [InputActionLabel.ResolvedImageContent](https://create.roblox.com/docs/reference/engine/classes/InputActionLabel#ResolvedImageContent) [🏷️ ReadOnly] [🏷️ NotReplicated] {🚧Read: UI} [⚡ThreadSafety: ReadSafe]
  * Added Property [InputActionLabel.ResolvedText](https://create.roblox.com/docs/reference/engine/classes/InputActionLabel#ResolvedText) [🏷️ ReadOnly] [🏷️ NotReplicated] {🚧Read: UI} [⚡ThreadSafety: ReadSafe]
  * Added Property [InputActionLabel.TextColor3](https://create.roblox.com/docs/reference/engine/classes/InputActionLabel#TextColor3) {🚧Read: UI} [⚡ThreadSafety: ReadSafe]
  * Added Property [InputActionLabel.TextSize](https://create.roblox.com/docs/reference/engine/classes/InputActionLabel#TextSize) {🚧Read: UI} [⚡ThreadSafety: ReadSafe]
  * Added Property [InputActionLabel.TextTransparency](https://create.roblox.com/docs/reference/engine/classes/InputActionLabel#TextTransparency) {🚧Read: UI} [⚡ThreadSafety: ReadSafe]
  * Added Property [InputActionLabel.TextWrapped](https://create.roblox.com/docs/reference/engine/classes/InputActionLabel#TextWrapped) {🚧Read: UI} [⚡ThreadSafety: ReadSafe]
  * Added Property [InputActionLabel.TextXAlignment](https://create.roblox.com/docs/reference/engine/classes/InputActionLabel#TextXAlignment) {🚧Read: UI} [⚡ThreadSafety: ReadSafe]
  * Added Property [InputActionLabel.TextYAlignment](https://create.roblox.com/docs/reference/engine/classes/InputActionLabel#TextYAlignment) {🚧Read: UI} [⚡ThreadSafety: ReadSafe]
* Update Class [AssetImportSession](https://create.roblox.com/docs/reference/engine/classes/AssetImportSession) [⬆️Extends: ImportSession] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Function [AssetImportSession.GetPlaceholderInstanceTree](https://create.roblox.com/docs/reference/engine/classes/AssetImportSession#GetPlaceholderInstanceTree) () -> Instance
* Update Class [InsertService](https://create.roblox.com/docs/reference/engine/classes/InsertService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the parameters of Function [InsertService.LoadAssetWithBytecodeAsync](https://create.roblox.com/docs/reference/engine/classes/InsertService#LoadAssetWithBytecodeAsync)
    from: (assetId: int64, version: int64)
    to: (content: Content)
* Added Class [LuauExpressionService](https://create.roblox.com/docs/reference/engine/classes/LuauExpressionService) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [LuauExpressionService.CreateExpression](https://create.roblox.com/docs/reference/engine/classes/LuauExpressionService#CreateExpression)
* Update Class [MLService](https://create.roblox.com/docs/reference/engine/classes/MLService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Removed Function MLService.GetNPCInferenceSpecAsync
  * Removed Function MLService.RunNPCInferenceAsync
* Update Class [WorldModel](https://create.roblox.com/docs/reference/engine/classes/WorldModel) [⬆️Extends: WorldRoot] [🧠Memory: BaseParts]
  * Added Property [WorldModel.UseWorkspaceCollisionGroups](https://create.roblox.com/docs/reference/engine/classes/WorldModel#UseWorkspaceCollisionGroups): bool {🚧Read: Basic} [⚡ThreadSafety: ReadSafe]
* Added Class [Path3D](https://create.roblox.com/docs/reference/engine/classes/Path3D) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Function [Path3D.GetControlPoint](https://create.roblox.com/docs/reference/engine/classes/Path3D#GetControlPoint)
  * Added Function [Path3D.GetControlPoints](https://create.roblox.com/docs/reference/engine/classes/Path3D#GetControlPoints)
  * Added Function [Path3D.GetLength](https://create.roblox.com/docs/reference/engine/classes/Path3D#GetLength)
  * Added Function [Path3D.GetMaxControlPoints](https://create.roblox.com/docs/reference/engine/classes/Path3D#GetMaxControlPoints)
  * Added Function [Path3D.GetPositionOnCurve](https://create.roblox.com/docs/reference/engine/classes/Path3D#GetPositionOnCurve)
  * Added Function [Path3D.GetPositionOnCurveArcLength](https://create.roblox.com/docs/reference/engine/classes/Path3D#GetPositionOnCurveArcLength)
  * Added Function [Path3D.GetSegmentCount](https://create.roblox.com/docs/reference/engine/classes/Path3D#GetSegmentCount)
  * Added Function [Path3D.GetTangentOnCurve](https://create.roblox.com/docs/reference/engine/classes/Path3D#GetTangentOnCurve)
  * Added Function [Path3D.GetTangentOnCurveArcLength](https://create.roblox.com/docs/reference/engine/classes/Path3D#GetTangentOnCurveArcLength)
  * Added Function [Path3D.InsertControlPoint](https://create.roblox.com/docs/reference/engine/classes/Path3D#InsertControlPoint)
  * Added Function [Path3D.RemoveControlPoint](https://create.roblox.com/docs/reference/engine/classes/Path3D#RemoveControlPoint)
  * Added Function [Path3D.SetControlPoints](https://create.roblox.com/docs/reference/engine/classes/Path3D#SetControlPoints)
  * Added Function [Path3D.UpdateControlPoint](https://create.roblox.com/docs/reference/engine/classes/Path3D#UpdateControlPoint)
  * Added Event [Path3D.ControlPointChanged](https://create.roblox.com/docs/reference/engine/classes/Path3D#ControlPointChanged)
* Added Class [PinShortcutService](https://create.roblox.com/docs/reference/engine/classes/PinShortcutService) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [PinShortcutService.IsAvailable](https://create.roblox.com/docs/reference/engine/classes/PinShortcutService#IsAvailable)
  * Added Function [PinShortcutService.PinExperience](https://create.roblox.com/docs/reference/engine/classes/PinShortcutService#PinExperience)
* Update Class [Player](https://create.roblox.com/docs/reference/engine/classes/Player) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Property [Player.VoiceChatVolume](https://create.roblox.com/docs/reference/engine/classes/Player#VoiceChatVolume): float [🏷️ Hidden] [🏷️ NotReplicated] {🚧Read: Players} [⚡ThreadSafety: ReadSafe]
* Added Class [RequestOrchestratorService](https://create.roblox.com/docs/reference/engine/classes/RequestOrchestratorService) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Event [RequestOrchestratorService.BatchCreated](https://create.roblox.com/docs/reference/engine/classes/RequestOrchestratorService#BatchCreated)
  * Added Event [RequestOrchestratorService.BatchExhausted](https://create.roblox.com/docs/reference/engine/classes/RequestOrchestratorService#BatchExhausted)
  * Added Event [RequestOrchestratorService.BatchResponseReceived](https://create.roblox.com/docs/reference/engine/classes/RequestOrchestratorService#BatchResponseReceived)
  * Added Event [RequestOrchestratorService.BatchRetrying](https://create.roblox.com/docs/reference/engine/classes/RequestOrchestratorService#BatchRetrying)
  * Added Event [RequestOrchestratorService.BatchSent](https://create.roblox.com/docs/reference/engine/classes/RequestOrchestratorService#BatchSent)
  * Added Event [RequestOrchestratorService.CacheHit](https://create.roblox.com/docs/reference/engine/classes/RequestOrchestratorService#CacheHit)
  * Added Event [RequestOrchestratorService.CacheItemAdded](https://create.roblox.com/docs/reference/engine/classes/RequestOrchestratorService#CacheItemAdded)
  * Added Event [RequestOrchestratorService.JitterStarted](https://create.roblox.com/docs/reference/engine/classes/RequestOrchestratorService#JitterStarted)
  * Added Event [RequestOrchestratorService.OperationCoalesced](https://create.roblox.com/docs/reference/engine/classes/RequestOrchestratorService#OperationCoalesced)
  * Added Event [RequestOrchestratorService.OperationEnqueued](https://create.roblox.com/docs/reference/engine/classes/RequestOrchestratorService#OperationEnqueued)
* Update Class [ScriptEditorService](https://create.roblox.com/docs/reference/engine/classes/ScriptEditorService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [ScriptEditorService.ClearUriScript](https://create.roblox.com/docs/reference/engine/classes/ScriptEditorService#ClearUriScript) (uri: string) -> null
  * Added Function [ScriptEditorService.SetUriScript](https://create.roblox.com/docs/reference/engine/classes/ScriptEditorService#SetUriScript) (uri: string, source: string) -> null
* Update Class [DataModel](https://create.roblox.com/docs/reference/engine/classes/DataModel) [⬆️Extends: ServiceProvider] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Added Property [DataModel.IsPioneerBuild](https://create.roblox.com/docs/reference/engine/classes/DataModel#IsPioneerBuild): bool [🏷️ Hidden] [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [DataModel.PioneerSource](https://create.roblox.com/docs/reference/engine/classes/DataModel#PioneerSource): PioneerSource [🏷️ Hidden] [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
* Update Class [Studio](https://create.roblox.com/docs/reference/engine/classes/Studio) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Property [Studio.DraggerShowDraggedPoint](https://create.roblox.com/docs/reference/engine/classes/Studio#DraggerShowDraggedPoint): bool [⚡ThreadSafety: ReadSafe]
* Update Class [StudioCaptureService](https://create.roblox.com/docs/reference/engine/classes/StudioCaptureService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [StudioCaptureService.CapturePluginGui](https://create.roblox.com/docs/reference/engine/classes/StudioCaptureService#CapturePluginGui) (pluginGui: PluginGui) -> StudioScreenshotCapture
* Update Class [StudioDeviceEmulatorService](https://create.roblox.com/docs/reference/engine/classes/StudioDeviceEmulatorService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Removed Property StudioDeviceEmulatorService.HasMultiTouchStarted
  * Removed Property StudioDeviceEmulatorService.IsMultiTouchEmulationOn
  * Removed Property StudioDeviceEmulatorService.IsMultiTouchEnabled
  * Removed Property StudioDeviceEmulatorService.PivotPosition
  * Removed Function StudioDeviceEmulatorService.GetMaxNumTouches
  * Removed Function StudioDeviceEmulatorService.GetTouchInBounds
  * Removed Function StudioDeviceEmulatorService.GetTouchPosition
  * Removed Event StudioDeviceEmulatorService.TouchInBoundsChanged
  * Removed Event StudioDeviceEmulatorService.TouchPositionsChanged
* Update Class [SurfaceAppearance](https://create.roblox.com/docs/reference/engine/classes/SurfaceAppearance) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Property [SurfaceAppearance.TexturePackContent](https://create.roblox.com/docs/reference/engine/classes/SurfaceAppearance#TexturePackContent): Content {🚧Read: Basic} [⚡ThreadSafety: ReadSafe]
* Update Class [TestCase](https://create.roblox.com/docs/reference/engine/classes/TestCase) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Added Function [TestCase.AssertLegacy](https://create.roblox.com/docs/reference/engine/classes/TestCase#AssertLegacy) (condition: bool, message: string = , source: Instance = nil, line: int = 0) -> null {🚧InternalTest}
  * Added Function [TestCase.RequireLegacy](https://create.roblox.com/docs/reference/engine/classes/TestCase#RequireLegacy) (condition: bool, message: string = , source: Instance = nil, line: int = 0) -> null {🚧InternalTest}
* Update Class [TestService](https://create.roblox.com/docs/reference/engine/classes/TestService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ Service]
  * Added Function [TestService.RegisterTestLegacy](https://create.roblox.com/docs/reference/engine/classes/TestService#RegisterTestLegacy) (testOptions: Dictionary) -> TestCase {🚧InternalTest}
  * Added Function [TestService.FetchTestControlsAsync](https://create.roblox.com/docs/reference/engine/classes/TestService#FetchTestControlsAsync) (category: string) -> Tuple [🏷️ Yields] {🚧InternalTest}
  * Changed the parameters of Function [TestService.RequestValidationAsync](https://create.roblox.com/docs/reference/engine/classes/TestService#RequestValidationAsync)
    from: (artifactType: string, artifactName: string)
    to: (artifactType: string, artifactName: string, timeoutSeconds: double = 60)
* Update Class [TextChatService](https://create.roblox.com/docs/reference/engine/classes/TextChatService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Property [TextChatService.PlatformIntegratedChat](https://create.roblox.com/docs/reference/engine/classes/TextChatService#PlatformIntegratedChat): RolloutState {🚧Read: Chat} [⚡ThreadSafety: ReadSafe]
  * Added Function [TextChatService.SendTextChatCommandClientSent](https://create.roblox.com/docs/reference/engine/classes/TextChatService#SendTextChatCommandClientSent) (textChatCommandName: string, chatWindowType: string = , textChannelWindowName: string = ) -> null {🚧Chat}
  * Removed Property TextChatService.EnableProtectedChat
* Update Class [UIShadow](https://create.roblox.com/docs/reference/engine/classes/UIShadow) [⬆️Extends: UIComponent] [🧠Memory: Instances]
  * Added Property [UIShadow.Mode](https://create.roblox.com/docs/reference/engine/classes/UIShadow#Mode): ApplyShadowMode {🚧Read: UI} [⚡ThreadSafety: ReadSafe]
* Added Class [WindowProtocolService](https://create.roblox.com/docs/reference/engine/classes/WindowProtocolService) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [WindowProtocolService.BeginDrag](https://create.roblox.com/docs/reference/engine/classes/WindowProtocolService#BeginDrag)
  * Added Function [WindowProtocolService.Close](https://create.roblox.com/docs/reference/engine/classes/WindowProtocolService#Close)
  * Added Function [WindowProtocolService.EndDrag](https://create.roblox.com/docs/reference/engine/classes/WindowProtocolService#EndDrag)
  * Added Function [WindowProtocolService.GetLogicalCaptionButtonsBounds](https://create.roblox.com/docs/reference/engine/classes/WindowProtocolService#GetLogicalCaptionButtonsBounds)
  * Added Function [WindowProtocolService.GetNativeTitleBarControlsPosition](https://create.roblox.com/docs/reference/engine/classes/WindowProtocolService#GetNativeTitleBarControlsPosition)
  * Added Function [WindowProtocolService.GetTitleBarMode](https://create.roblox.com/docs/reference/engine/classes/WindowProtocolService#GetTitleBarMode)
  * Added Function [WindowProtocolService.GetWindowState](https://create.roblox.com/docs/reference/engine/classes/WindowProtocolService#GetWindowState)
  * Added Function [WindowProtocolService.IsAvailable](https://create.roblox.com/docs/reference/engine/classes/WindowProtocolService#IsAvailable)
  * Added Function [WindowProtocolService.Maximize](https://create.roblox.com/docs/reference/engine/classes/WindowProtocolService#Maximize)
  * Added Function [WindowProtocolService.Minimize](https://create.roblox.com/docs/reference/engine/classes/WindowProtocolService#Minimize)
  * Added Function [WindowProtocolService.Restore](https://create.roblox.com/docs/reference/engine/classes/WindowProtocolService#Restore)
  * Added Function [WindowProtocolService.SetCustomTitleBarHeight](https://create.roblox.com/docs/reference/engine/classes/WindowProtocolService#SetCustomTitleBarHeight)
  * Added Function [WindowProtocolService.SetTitleBarMode](https://create.roblox.com/docs/reference/engine/classes/WindowProtocolService#SetTitleBarMode)
  * Added Function [WindowProtocolService.ShouldRenderTitleBarControlsNatively](https://create.roblox.com/docs/reference/engine/classes/WindowProtocolService#ShouldRenderTitleBarControlsNatively)
  * Added Event [WindowProtocolService.OnWindowStateChanged](https://create.roblox.com/docs/reference/engine/classes/WindowProtocolService#OnWindowStateChanged)
* Added Class [LuauExpression](https://create.roblox.com/docs/reference/engine/classes/LuauExpression) {🔒None} [⬆️Extends: Object] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Added Function [LuauExpression.Evaluate](https://create.roblox.com/docs/reference/engine/classes/LuauExpression#Evaluate)
* Added Enum [ApplyShadowMode](https://create.roblox.com/docs/reference/engine/enums/ApplyShadowMode)
  * Added EnumItem `Shape` (0)
  * Added EnumItem `Text` (1)
* Update Enum [AssetType](https://create.roblox.com/docs/reference/engine/enums/AssetType)
  * Removed EnumItem `VoxelFragment`
* Added Enum [DistanceAttenuationMode](https://create.roblox.com/docs/reference/engine/enums/DistanceAttenuationMode)
  * Added EnumItem `Custom` (0)
  * Added EnumItem `InverseTapered` (1)
  * Added EnumItem `Linear` (2)
  * Added EnumItem `LinearSquared` (3)
  * Added EnumItem `Inverse` (4)
* Added Enum [GenerateMomentTextResult](https://create.roblox.com/docs/reference/engine/enums/GenerateMomentTextResult)
  * Added EnumItem `Success` (0)
  * Added EnumItem `Pending` (1)
  * Added EnumItem `Failed` (2)
* Update Enum [InternalVideoUsage](https://create.roblox.com/docs/reference/engine/enums/InternalVideoUsage)
  * Added EnumItem `FeatureTileAd` (3)
* Update Enum [KeyCode](https://create.roblox.com/docs/reference/engine/enums/KeyCode)
  * Added EnumItem `None` (0)
  * Added EnumItem `ButtonCenter` (1051)
  * Added EnumItem `ButtonBack` (1052)
  * Added EnumItem `ButtonUp` (1053)
  * Added EnumItem `ButtonDown` (1054)
  * Added EnumItem `ButtonLeft` (1055)
  * Added EnumItem `ButtonRight` (1056)
  * Removed EnumItem `Unknown`
* Added Enum [KnownWindow](https://create.roblox.com/docs/reference/engine/enums/KnownWindow)
  * Added EnumItem `Main` (0)
* Added Enum [MeshAttribute](https://create.roblox.com/docs/reference/engine/enums/MeshAttribute)
  * Added EnumItem `Vertex` (0)
  * Added EnumItem `Normal` (1)
  * Added EnumItem `Color` (2)
  * Added EnumItem `UV` (3)
  * Added EnumItem `Face` (4)
* Added Enum [PioneerSource](https://create.roblox.com/docs/reference/engine/enums/PioneerSource)
  * Added EnumItem `Roblox` (0)
  * Added EnumItem `DaveyBazooka` (1)
  * Added EnumItem `Oof` (2)
* Update Enum [PreferredInput](https://create.roblox.com/docs/reference/engine/enums/PreferredInput)
  * Added EnumItem `MicroGamepad` (3)
* Added Enum [TitleBarControlsPosition](https://create.roblox.com/docs/reference/engine/enums/TitleBarControlsPosition)
  * Added EnumItem `Unknown` (0)
  * Added EnumItem `Left` (1)
  * Added EnumItem `Right` (2)
* Added Enum [TitleBarMode](https://create.roblox.com/docs/reference/engine/enums/TitleBarMode)
  * Added EnumItem `Native` (0)
  * Added EnumItem `Custom` (1)
* Added Enum [UserAcquisitionSource](https://create.roblox.com/docs/reference/engine/enums/UserAcquisitionSource)
  * Added EnumItem `Unknown` (0)
  * Added EnumItem `PendingAttribution` (1)
  * Added EnumItem `HomeRecommendation` (2)
  * Added EnumItem `ContinueToPlay` (3)
  * Added EnumItem `Curation` (4)
  * Added EnumItem `Friends` (5)
  * Added EnumItem `Search` (6)
  * Added EnumItem `Teleport` (7)
  * Added EnumItem `Ads` (8)
  * Added EnumItem `HomeOther` (9)
  * Added EnumItem `Other` (10)
* Added Enum [UserIdMode](https://create.roblox.com/docs/reference/engine/enums/UserIdMode)
  * Added EnumItem `Invalid` (0)
  * Added EnumItem `Global` (1)
  * Added EnumItem `Domain` (2)
* Added Enum [UserNewReturningStatus](https://create.roblox.com/docs/reference/engine/enums/UserNewReturningStatus)
  * Added EnumItem `Unknown` (0)
  * Added EnumItem `New` (1)
  * Added EnumItem `Returning` (2)
* Added Enum [UserReturnStatus](https://create.roblox.com/docs/reference/engine/enums/UserReturnStatus)
  * Added EnumItem `Unknown` (0)
  * Added EnumItem `New` (1)
  * Added EnumItem `Returning` (2)
* Added Enum [WindowState](https://create.roblox.com/docs/reference/engine/enums/WindowState)
  * Added EnumItem `Normal` (0)
  * Added EnumItem `Minimized` (1)
  * Added EnumItem `Maximized` (2)
