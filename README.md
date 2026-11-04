# Roblox Client Tracker

| Metadata | Details |
| :--- | :--- |
| **Version** | `0.746.0.7461264` |
| **Version Hash** | `version-fee454b8e2094ba9` |
| **Official Release Notes** | [Release Notes 746](https://create.roblox.com/docs/release-notes/release-notes-746) |

---

## Changelog

* Update Class [EditableImage](https://create.roblox.com/docs/reference/engine/classes/EditableImage) [⬆️Extends: Object] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed the parameters of Function [EditableImage.DrawCircle](https://create.roblox.com/docs/reference/engine/classes/EditableImage#DrawCircle)
    from: (center: Vector2, radius: int, color: Color3, transparency: float, combineType: ImageCombineType, antiAliasing: AntiAliasing = Enabled)
    to: (center: Vector2, radius: int, color: Color3, transparency: float, combineType: ImageCombineType, antiAliasing: AntiAliasing = Enabled, alphaBlendType: ImageAlphaType = Default)
  * Changed the parameters of Function [EditableImage.DrawImage](https://create.roblox.com/docs/reference/engine/classes/EditableImage#DrawImage)
    from: (position: Vector2, image: EditableImage, combineType: ImageCombineType)
    to: (position: Vector2, image: EditableImage, combineType: ImageCombineType, alphaBlendType: ImageAlphaType = Default)
  * Changed the parameters of Function [EditableImage.DrawLine](https://create.roblox.com/docs/reference/engine/classes/EditableImage#DrawLine)
    from: (p1: Vector2, p2: Vector2, color: Color3, transparency: float, combineType: ImageCombineType, antiAliasing: AntiAliasing = Enabled)
    to: (p1: Vector2, p2: Vector2, color: Color3, transparency: float, combineType: ImageCombineType, antiAliasing: AntiAliasing = Enabled, alphaBlendType: ImageAlphaType = Default)
  * Changed the parameters of Function [EditableImage.DrawRectangle](https://create.roblox.com/docs/reference/engine/classes/EditableImage#DrawRectangle)
    from: (position: Vector2, size: Vector2, color: Color3, transparency: float, combineType: ImageCombineType)
    to: (position: Vector2, size: Vector2, color: Color3, transparency: float, combineType: ImageCombineType, alphaBlendType: ImageAlphaType = Default)
* Update Class [FeatureMatchingSession](https://create.roblox.com/docs/reference/engine/classes/FeatureMatchingSession) [⬆️Extends: Object] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Function [FeatureMatchingSession.Search](https://create.roblox.com/docs/reference/engine/classes/FeatureMatchingSession#Search) (query: buffer, params: FeatureSearchParams = nil) -> Dictionary {🚧InternalTest}
  * Added Function [FeatureMatchingSession.SearchBatch](https://create.roblox.com/docs/reference/engine/classes/FeatureMatchingSession#SearchBatch) (queries: Array, sharedParams: FeatureSearchParams = nil, perQueryParams: Array = {}) -> Array {🚧InternalTest}
* Added Class [FeatureSearchParams](https://create.roblox.com/docs/reference/engine/classes/FeatureSearchParams) {🔒None} [⬆️Extends: Object] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Property [FeatureSearchParams.AnchorCostScale](https://create.roblox.com/docs/reference/engine/classes/FeatureSearchParams#AnchorCostScale) {🚧Read: InternalTest | Write: InternalTest} [⚡ThreadSafety: ReadSafe]
  * Added Property [FeatureSearchParams.AnchorIgnoresTagFilters](https://create.roblox.com/docs/reference/engine/classes/FeatureSearchParams#AnchorIgnoresTagFilters) {🚧Read: InternalTest | Write: InternalTest} [⚡ThreadSafety: ReadSafe]
  * Added Property [FeatureSearchParams.AnchorRow](https://create.roblox.com/docs/reference/engine/classes/FeatureSearchParams#AnchorRow) {🚧Read: InternalTest | Write: InternalTest} [⚡ThreadSafety: ReadSafe]
  * Added Property [FeatureSearchParams.MaxDistance](https://create.roblox.com/docs/reference/engine/classes/FeatureSearchParams#MaxDistance) {🚧Read: InternalTest | Write: InternalTest} [⚡ThreadSafety: ReadSafe]
  * Added Property [FeatureSearchParams.MaxResults](https://create.roblox.com/docs/reference/engine/classes/FeatureSearchParams#MaxResults) {🚧Read: InternalTest | Write: InternalTest} [⚡ThreadSafety: ReadSafe]
  * Added Property [FeatureSearchParams.NormalizationKey](https://create.roblox.com/docs/reference/engine/classes/FeatureSearchParams#NormalizationKey) {🚧Read: InternalTest | Write: InternalTest} [⚡ThreadSafety: ReadSafe]
  * Added Property [FeatureSearchParams.ReturnChannelCosts](https://create.roblox.com/docs/reference/engine/classes/FeatureSearchParams#ReturnChannelCosts) {🚧Read: InternalTest | Write: InternalTest} [⚡ThreadSafety: ReadSafe]
  * Added Property [FeatureSearchParams.SelectionMode](https://create.roblox.com/docs/reference/engine/classes/FeatureSearchParams#SelectionMode) {🚧Read: InternalTest | Write: InternalTest} [⚡ThreadSafety: ReadSafe]
  * Added Property [FeatureSearchParams.SelectionSeed](https://create.roblox.com/docs/reference/engine/classes/FeatureSearchParams#SelectionSeed) {🚧Read: InternalTest | Write: InternalTest} [⚡ThreadSafety: ReadSafe]
  * Added Property [FeatureSearchParams.SelectionTemperature](https://create.roblox.com/docs/reference/engine/classes/FeatureSearchParams#SelectionTemperature) {🚧Read: InternalTest | Write: InternalTest} [⚡ThreadSafety: ReadSafe]
  * Added Function [FeatureSearchParams.GetChannelWeights](https://create.roblox.com/docs/reference/engine/classes/FeatureSearchParams#GetChannelWeights) {🚧InternalTest}
  * Added Function [FeatureSearchParams.GetCostBiases](https://create.roblox.com/docs/reference/engine/classes/FeatureSearchParams#GetCostBiases) {🚧InternalTest}
  * Added Function [FeatureSearchParams.GetFilters](https://create.roblox.com/docs/reference/engine/classes/FeatureSearchParams#GetFilters) {🚧InternalTest}
  * Added Function [FeatureSearchParams.GetReturnedFields](https://create.roblox.com/docs/reference/engine/classes/FeatureSearchParams#GetReturnedFields) {🚧InternalTest}
  * Added Function [FeatureSearchParams.SetChannelWeights](https://create.roblox.com/docs/reference/engine/classes/FeatureSearchParams#SetChannelWeights) {🚧InternalTest}
  * Added Function [FeatureSearchParams.SetCostBiases](https://create.roblox.com/docs/reference/engine/classes/FeatureSearchParams#SetCostBiases) {🚧InternalTest}
  * Added Function [FeatureSearchParams.SetFilters](https://create.roblox.com/docs/reference/engine/classes/FeatureSearchParams#SetFilters) {🚧InternalTest}
  * Added Function [FeatureSearchParams.SetReturnedFields](https://create.roblox.com/docs/reference/engine/classes/FeatureSearchParams#SetReturnedFields) {🚧InternalTest}
* Update Class [AchievementService](https://create.roblox.com/docs/reference/engine/classes/AchievementService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [AchievementService.IsAchievementAvailable](https://create.roblox.com/docs/reference/engine/classes/AchievementService#IsAchievementAvailable) (achievementName: string) -> bool
* Update Class [AnimationNodeDefinition](https://create.roblox.com/docs/reference/engine/classes/AnimationNodeDefinition) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the security of Property [AnimationNodeDefinition.NodeId](https://create.roblox.com/docs/reference/engine/classes/AnimationNodeDefinition#NodeId)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AnimationNodeDefinition.NodeId](https://create.roblox.com/docs/reference/engine/classes/AnimationNodeDefinition#NodeId)
    from: {🚧Read: Animation}
    to: {🚧Read: Animation | Write: Animation}
* Update Class [AnimationPlayer](https://create.roblox.com/docs/reference/engine/classes/AnimationPlayer) [⬆️Extends: Instance] [🧠Memory: Gui]
  * Added Property [AnimationPlayer.Parameters](https://create.roblox.com/docs/reference/engine/classes/AnimationPlayer#Parameters): bool [🏷️ NotReplicated] [🏷️ NotScriptable] [⚡ThreadSafety: ReadSafe]
  * Added Function [AnimationPlayer.GetParameter](https://create.roblox.com/docs/reference/engine/classes/AnimationPlayer#GetParameter) (name: string) -> Variant
  * Added Function [AnimationPlayer.GetParameterDefaults](https://create.roblox.com/docs/reference/engine/classes/AnimationPlayer#GetParameterDefaults) () -> Dictionary
  * Added Function [AnimationPlayer.SetParameter](https://create.roblox.com/docs/reference/engine/classes/AnimationPlayer#SetParameter) (name: string, value: Variant) -> null
* Update Class [AnimationRigData](https://create.roblox.com/docs/reference/engine/classes/AnimationRigData) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Removed Function AnimationRigData.LoadFromHumanoid
* Update Class [AnimationValueNodeDefinition](https://create.roblox.com/docs/reference/engine/classes/AnimationValueNodeDefinition) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the security of Property [AnimationValueNodeDefinition.NodeId](https://create.roblox.com/docs/reference/engine/classes/AnimationValueNodeDefinition#NodeId)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [AnimationValueNodeDefinition.NodeId](https://create.roblox.com/docs/reference/engine/classes/AnimationValueNodeDefinition#NodeId)
    from: {🚧Read: Animation}
    to: {🚧Read: Animation | Write: Animation}
* Update Class [AssetImportService](https://create.roblox.com/docs/reference/engine/classes/AssetImportService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [AssetImportService.PickAnimatedImageFileWithPromptAsync](https://create.roblox.com/docs/reference/engine/classes/AssetImportService#PickAnimatedImageFileWithPromptAsync) () -> string [🏷️ Yields]
  * Added Function [AssetImportService.PickTextDocumentFileWithPromptAsync](https://create.roblox.com/docs/reference/engine/classes/AssetImportService#PickTextDocumentFileWithPromptAsync) () -> string [🏷️ Yields]
* Update Class [FeatureMatchingService](https://create.roblox.com/docs/reference/engine/classes/FeatureMatchingService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [FeatureMatchingService.CreateSearchParams](https://create.roblox.com/docs/reference/engine/classes/FeatureMatchingService#CreateSearchParams) () -> FeatureSearchParams {🚧InternalTest}
* Update Class [FriendsCallingInstance](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingInstance) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the security of Property [FriendsCallingInstance.CallId](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingInstance#CallId)
    from: {🔒RobloxSecurity}
    to: {🔒RobloxScriptSecurity}
  * Changed the security of Property [FriendsCallingInstance.ConversationId](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingInstance#ConversationId)
    from: {🔒RobloxSecurity}
    to: {🔒RobloxScriptSecurity}
  * Changed the security of Property [FriendsCallingInstance.EndReason](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingInstance#EndReason)
    from: {🔒RobloxSecurity}
    to: {🔒RobloxScriptSecurity}
  * Changed the security of Property [FriendsCallingInstance.InitiatorUserId](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingInstance#InitiatorUserId)
    from: {🔒RobloxSecurity}
    to: {🔒RobloxScriptSecurity}
  * Changed the security of Property [FriendsCallingInstance.IsDeafened](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingInstance#IsDeafened)
    from: {🔒RobloxSecurity}
    to: {🔒RobloxScriptSecurity}
  * Changed the security of Property [FriendsCallingInstance.Phase](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingInstance#Phase)
    from: {🔒RobloxSecurity}
    to: {🔒RobloxScriptSecurity}
  * Changed the security of Property [FriendsCallingInstance.Volume](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingInstance#Volume)
    from: {🔒RobloxSecurity}
    to: {🔒RobloxScriptSecurity}
* Update Class [FriendsCallingParticipant](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingParticipant) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the security of Property [FriendsCallingParticipant.Error](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingParticipant#Error)
    from: {🔒RobloxSecurity}
    to: {🔒RobloxScriptSecurity}
  * Changed the security of Property [FriendsCallingParticipant.IsLocalMuted](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingParticipant#IsLocalMuted)
    from: {🔒RobloxSecurity}
    to: {🔒RobloxScriptSecurity}
  * Changed the security of Property [FriendsCallingParticipant.IsSpeaking](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingParticipant#IsSpeaking)
    from: {🔒RobloxSecurity}
    to: {🔒RobloxScriptSecurity}
  * Changed the security of Property [FriendsCallingParticipant.LeaveReason](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingParticipant#LeaveReason)
    from: {🔒RobloxSecurity}
    to: {🔒RobloxScriptSecurity}
  * Changed the security of Property [FriendsCallingParticipant.Status](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingParticipant#Status)
    from: {🔒RobloxSecurity}
    to: {🔒RobloxScriptSecurity}
  * Changed the security of Property [FriendsCallingParticipant.UserId](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingParticipant#UserId)
    from: {🔒RobloxSecurity}
    to: {🔒RobloxScriptSecurity}
  * Changed the security of Property [FriendsCallingParticipant.Volume](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingParticipant#Volume)
    from: {🔒RobloxSecurity}
    to: {🔒RobloxScriptSecurity}
* Update Class [FriendsCallingService](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [FriendsCallingService.AnswerCall](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingService#AnswerCall) (callId: string) -> null
  * Changed the parameters of Function [FriendsCallingService.EndCall](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingService#EndCall)
    from: ()
    to: (callId: string, reason: string)
  * Added Function [FriendsCallingService.ReceiveCall](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingService#ReceiveCall) (pushPayloadJson: string) -> null
* Update Class [GamepadService](https://create.roblox.com/docs/reference/engine/classes/GamepadService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the parameters of Function [GamepadService.EnableGamepadCursor](https://create.roblox.com/docs/reference/engine/classes/GamepadService#EnableGamepadCursor)
    from: (guiObject: Instance)
    to: (guiObject: GuiObject = nil)
* Update Class [GeometryService](https://create.roblox.com/docs/reference/engine/classes/GeometryService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [GeometryService.SplitApartAsync](https://create.roblox.com/docs/reference/engine/classes/GeometryService#SplitApartAsync) (parts: Array, options: Dictionary = nil) -> Array [🏷️ Yields] {🚧CSG}
* Update Class [LayerCollector](https://create.roblox.com/docs/reference/engine/classes/LayerCollector) [⬆️Extends: GuiBase2d] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotBrowsable]
  * Added Property [LayerCollector.InputSinkEnabled](https://create.roblox.com/docs/reference/engine/classes/LayerCollector#InputSinkEnabled): RolloutState {🚧Read: UI, PluginOrOpenCloud | Write: PluginOrOpenCloud} [⚡ThreadSafety: ReadSafe]
* Update Class [GuiService](https://create.roblox.com/docs/reference/engine/classes/GuiService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [GuiService.GetUIScaleOptions](https://create.roblox.com/docs/reference/engine/classes/GuiService#GetUIScaleOptions) () -> Dictionary {🚧UI}
* Update Class [HapticEffect](https://create.roblox.com/docs/reference/engine/classes/HapticEffect) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Function [HapticEffect.GetWaveformKeys](https://create.roblox.com/docs/reference/engine/classes/HapticEffect#GetWaveformKeys) () -> Array {🚧Input}
* Update Class [Terrain](https://create.roblox.com/docs/reference/engine/classes/Terrain) [⬆️Extends: BasePart] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed the capabilities of Property [Terrain.Decoration](https://create.roblox.com/docs/reference/engine/classes/Terrain#Decoration)
    from: {🚧Read: Environment | Write: Environment}
    to: {🚧Read: Environment | Write: PluginOrOpenCloud}
  * Changed the capabilities of Property [Terrain.GrassLength](https://create.roblox.com/docs/reference/engine/classes/Terrain#GrassLength)
    from: {🚧Read: Environment | Write: Environment}
    to: {🚧Read: Environment | Write: PluginOrOpenCloud}
* Update Class [WorldRoot](https://create.roblox.com/docs/reference/engine/classes/WorldRoot) [⬆️Extends: Model] [🧠Memory: BaseParts] [🏷️ NotCreatable]
  * Changed the parameters of Function [WorldRoot.Blockcast](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#Blockcast)
    from: (cframe: CFrame, size: Vector3, direction: Vector3, params: RaycastParams = RaycastParams{IgnoreWater=false, BruteForceAllSlow=false, RespectCanCollide=false, CollisionGroup=Default, FilterDescendantsInstances={}})
    to: (cframe: CFrame, size: Vector3, direction: Vector3, params: RaycastParams = RaycastParams{IgnoreWater=false, Margin=0, SizeGradient=0, BruteForceAllSlow=false, RespectCanCollide=false, CollisionGroup=Default, FilterDescendantsInstances={}})
  * Changed the parameters of Function [WorldRoot.Raycast](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#Raycast)
    from: (origin: Vector3, direction: Vector3, raycastParams: RaycastParams = RaycastParams{IgnoreWater=false, BruteForceAllSlow=false, RespectCanCollide=false, CollisionGroup=Default, FilterDescendantsInstances={}})
    to: (origin: Vector3, direction: Vector3, raycastParams: RaycastParams = RaycastParams{IgnoreWater=false, Margin=0, SizeGradient=0, BruteForceAllSlow=false, RespectCanCollide=false, CollisionGroup=Default, FilterDescendantsInstances={}})
  * Changed the parameters of Function [WorldRoot.Shapecast](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#Shapecast)
    from: (part: BasePart, direction: Vector3, params: RaycastParams = RaycastParams{IgnoreWater=false, BruteForceAllSlow=false, RespectCanCollide=false, CollisionGroup=Default, FilterDescendantsInstances={}}, cframeOverride: CoordinateFrame? = nil, sizeOverride: Vector3? = nil)
    to: (part: BasePart, direction: Vector3, params: RaycastParams = RaycastParams{IgnoreWater=false, Margin=0, SizeGradient=0, BruteForceAllSlow=false, RespectCanCollide=false, CollisionGroup=Default, FilterDescendantsInstances={}}, cframeOverride: CoordinateFrame? = nil, sizeOverride: Vector3? = nil)
  * Changed the parameters of Function [WorldRoot.Spherecast](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#Spherecast)
    from: (position: Vector3, radius: float, direction: Vector3, params: RaycastParams = RaycastParams{IgnoreWater=false, BruteForceAllSlow=false, RespectCanCollide=false, CollisionGroup=Default, FilterDescendantsInstances={}})
    to: (position: Vector3, radius: float, direction: Vector3, params: RaycastParams = RaycastParams{IgnoreWater=false, Margin=0, SizeGradient=0, BruteForceAllSlow=false, RespectCanCollide=false, CollisionGroup=Default, FilterDescendantsInstances={}})
* Update Class [Workspace](https://create.roblox.com/docs/reference/engine/classes/Workspace) [⬆️Extends: WorldRoot] [🧠Memory: BaseParts] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the security of Property [Workspace.AuthorityMode](https://create.roblox.com/docs/reference/engine/classes/Workspace#AuthorityMode)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [Workspace.AuthorityMode](https://create.roblox.com/docs/reference/engine/classes/Workspace#AuthorityMode)
    from: {🚧None}
    to: {🚧Read: Basic | Write: PluginOrOpenCloud}
  * Added Property [Workspace.InputSinkEnabled](https://create.roblox.com/docs/reference/engine/classes/Workspace#InputSinkEnabled): RolloutState [⚡ThreadSafety: ReadSafe]
  * Added Property [Workspace.NextGenerationPhysicsSolver](https://create.roblox.com/docs/reference/engine/classes/Workspace#NextGenerationPhysicsSolver): RolloutState {🚧Read: PluginOrOpenCloud | Write: PluginOrOpenCloud} [⚡ThreadSafety: ReadSafe]
  * Added Property [Workspace.ParticlesUseDynamicWind](https://create.roblox.com/docs/reference/engine/classes/Workspace#ParticlesUseDynamicWind): RolloutState [🏷️ NotScriptable] {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
  * Changed the capabilities of Property [Workspace.PredictiveStreamingMode](https://create.roblox.com/docs/reference/engine/classes/Workspace#PredictiveStreamingMode)
    from: {🚧None}
    to: {🚧Read: PluginOrOpenCloud | Write: PluginOrOpenCloud}
  * Changed the capabilities of Property [Workspace.StreamOutBehavior](https://create.roblox.com/docs/reference/engine/classes/Workspace#StreamOutBehavior)
    from: {🚧None}
    to: {🚧Read: PluginOrOpenCloud | Write: PluginOrOpenCloud}
  * Changed the capabilities of Property [Workspace.StreamingIntegrityMode](https://create.roblox.com/docs/reference/engine/classes/Workspace#StreamingIntegrityMode)
    from: {🚧None}
    to: {🚧Read: PluginOrOpenCloud | Write: PluginOrOpenCloud}
  * Changed the capabilities of Property [Workspace.StreamingMinRadius](https://create.roblox.com/docs/reference/engine/classes/Workspace#StreamingMinRadius)
    from: {🚧None}
    to: {🚧Read: PluginOrOpenCloud | Write: PluginOrOpenCloud}
  * Changed the capabilities of Property [Workspace.StreamingTargetRadius](https://create.roblox.com/docs/reference/engine/classes/Workspace#StreamingTargetRadius)
    from: {🚧None}
    to: {🚧Read: PluginOrOpenCloud | Write: PluginOrOpenCloud}
  * Removed Property Workspace.PrimalPhysicsSolver
  * Removed Property Workspace.UseInputSink
* Added Class [PlaceSettings](https://create.roblox.com/docs/reference/engine/classes/PlaceSettings) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [PlaceSettings.GetActiveRollouts](https://create.roblox.com/docs/reference/engine/classes/PlaceSettings#GetActiveRollouts) {🚧PluginOrOpenCloud}
  * Added Function [PlaceSettings.GetRolloutState](https://create.roblox.com/docs/reference/engine/classes/PlaceSettings#GetRolloutState) {🚧PluginOrOpenCloud}
  * Added Function [PlaceSettings.SetRolloutState](https://create.roblox.com/docs/reference/engine/classes/PlaceSettings#SetRolloutState) {🚧PluginOrOpenCloud}
* Update Class [ScriptEditorService](https://create.roblox.com/docs/reference/engine/classes/ScriptEditorService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [ScriptEditorService.GetActiveScriptDocument](https://create.roblox.com/docs/reference/engine/classes/ScriptEditorService#GetActiveScriptDocument) () -> ScriptDocument
  * Added Function [ScriptEditorService.OpenTextDocumentAsync](https://create.roblox.com/docs/reference/engine/classes/ScriptEditorService#OpenTextDocumentAsync) (textDocument: TextDocument, options: Dictionary = nil) -> Tuple [🏷️ Yields]
  * Added Event [ScriptEditorService.ActiveScriptDocumentChanged](https://create.roblox.com/docs/reference/engine/classes/ScriptEditorService#ActiveScriptDocumentChanged)
  * Removed Function ScriptEditorService.OpenTextDocumentDocumentAsync
* Update Class [SerializationService](https://create.roblox.com/docs/reference/engine/classes/SerializationService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [SerializationService.DeserializeValue](https://create.roblox.com/docs/reference/engine/classes/SerializationService#DeserializeValue) (buffer: buffer, format: SerializationFormat = Binary) -> Variant {🚧PluginOrOpenCloud}
  * Added Function [SerializationService.SerializeValue](https://create.roblox.com/docs/reference/engine/classes/SerializationService#SerializeValue) (value: Variant, format: SerializationFormat = Binary) -> buffer {🚧PluginOrOpenCloud}
* Update Class [SoundService](https://create.roblox.com/docs/reference/engine/classes/SoundService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the security of Property [SoundService.DefaultListenerLocation](https://create.roblox.com/docs/reference/engine/classes/SoundService#DefaultListenerLocation)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [SoundService.DefaultListenerLocation](https://create.roblox.com/docs/reference/engine/classes/SoundService#DefaultListenerLocation)
    from: {🚧Read: Audio}
    to: {🚧Read: Audio, PluginOrOpenCloud | Write: PluginOrOpenCloud}
  * Changed the security of Function [SoundService.GetInputDevice](https://create.roblox.com/docs/reference/engine/classes/SoundService#GetInputDevice)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Function [SoundService.GetInputDevice](https://create.roblox.com/docs/reference/engine/classes/SoundService#GetInputDevice)
    from: {🚧Audio}
    to: {🚧Audio, InternalTest}
* Update Class [StateMachineTransitionDefinition](https://create.roblox.com/docs/reference/engine/classes/StateMachineTransitionDefinition) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the security of Property [StateMachineTransitionDefinition.TransitionId](https://create.roblox.com/docs/reference/engine/classes/StateMachineTransitionDefinition#TransitionId)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [StateMachineTransitionDefinition.TransitionId](https://create.roblox.com/docs/reference/engine/classes/StateMachineTransitionDefinition#TransitionId)
    from: {🚧Read: Animation}
    to: {🚧Read: Animation | Write: Animation}
* Update Class [StudioService](https://create.roblox.com/docs/reference/engine/classes/StudioService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the parameters of Function [StudioService.GizmoRaycast](https://create.roblox.com/docs/reference/engine/classes/StudioService#GizmoRaycast)
    from: (origin: Vector3, direction: Vector3, raycastParams: RaycastParams = RaycastParams{IgnoreWater=false, BruteForceAllSlow=false, RespectCanCollide=false, CollisionGroup=Default, FilterDescendantsInstances={}})
    to: (origin: Vector3, direction: Vector3, raycastParams: RaycastParams = RaycastParams{IgnoreWater=false, Margin=0, SizeGradient=0, BruteForceAllSlow=false, RespectCanCollide=false, CollisionGroup=Default, FilterDescendantsInstances={}})
* Update Class [TextChatService](https://create.roblox.com/docs/reference/engine/classes/TextChatService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the security of Property [TextChatService.ChatTranslationEnabled](https://create.roblox.com/docs/reference/engine/classes/TextChatService#ChatTranslationEnabled)
    from: {🔒Read:None, Write:RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [TextChatService.ChatTranslationEnabled](https://create.roblox.com/docs/reference/engine/classes/TextChatService#ChatTranslationEnabled)
    from: {🚧Read: Chat}
    to: {🚧Read: Chat | Write: PluginOrOpenCloud}
  * Changed the security of Property [TextChatService.CreateDefaultCommands](https://create.roblox.com/docs/reference/engine/classes/TextChatService#CreateDefaultCommands)
    from: {🔒Read:None, Write:PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [TextChatService.CreateDefaultCommands](https://create.roblox.com/docs/reference/engine/classes/TextChatService#CreateDefaultCommands)
    from: {🚧Read: Chat}
    to: {🚧Read: Chat | Write: PluginOrOpenCloud}
  * Changed the security of Property [TextChatService.CreateDefaultTextChannels](https://create.roblox.com/docs/reference/engine/classes/TextChatService#CreateDefaultTextChannels)
    from: {🔒Read:None, Write:PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [TextChatService.CreateDefaultTextChannels](https://create.roblox.com/docs/reference/engine/classes/TextChatService#CreateDefaultTextChannels)
    from: {🚧Read: Chat}
    to: {🚧Read: Chat | Write: PluginOrOpenCloud}
* Update Class [TestFailure](https://create.roblox.com/docs/reference/engine/classes/TestFailure) [⬆️Extends: Object] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Removed Function TestFailure.GetContext
* Removed Class WrapDeformMeshProvider
* Update Enum [AnimationValueNodeType](https://create.roblox.com/docs/reference/engine/enums/AnimationValueNodeType)
  * Added EnumItem `FeatureMatching` (2)
* Added Enum [FeatureMatchingSource](https://create.roblox.com/docs/reference/engine/enums/FeatureMatchingSource)
  * Added EnumItem `Input` (0)
  * Added EnumItem `Continuity` (1)
  * Added EnumItem `Ignore` (2)
* Added Enum [FeatureSelectionMode](https://create.roblox.com/docs/reference/engine/enums/FeatureSelectionMode)
  * Added EnumItem `Nearest` (0)
  * Added EnumItem `WeightedRandom` (1)
* Added Enum [SerializationFormat](https://create.roblox.com/docs/reference/engine/enums/SerializationFormat)
  * Added EnumItem `Binary` (0)
  * Added EnumItem `Json` (1)
  * Added EnumItem `Luau` (2)
* Removed Enum PrimalPhysicsSolver
