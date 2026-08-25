# Roblox Client Tracker

| Metadata | Details |
| :--- | :--- |
| **Version** | `0.736.0.7361342` |
| **Version Hash** | `version-9e2e9085d9794dd1` |
| **Official Release Notes** | [Release Notes 736](https://create.roblox.com/docs/release-notes/release-notes-736) |

---

## Changelog

* Update Class [AdService](https://create.roblox.com/docs/reference/engine/classes/AdService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [AdService.RegisterImpressionSource](https://create.roblox.com/docs/reference/engine/classes/AdService#RegisterImpressionSource) (instance: Instance, adIntegrationPlacementId: string) -> null {🚧Monetization}
* Update Class [AssetService](https://create.roblox.com/docs/reference/engine/classes/AssetService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [AssetService.CreateDecalAsync](https://create.roblox.com/docs/reference/engine/classes/AssetService#CreateDecalAsync) (content: Dictionary) -> Decal [🏷️ Yields] {🚧Basic}
  * Added Function [AssetService.CreateTextureAsync](https://create.roblox.com/docs/reference/engine/classes/AssetService#CreateTextureAsync) (content: Dictionary) -> Texture [🏷️ Yields] {🚧Basic}
* Update Class [AvatarAbilityRules](https://create.roblox.com/docs/reference/engine/classes/AvatarAbilityRules) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Property [AvatarAbilityRules.EnableTurning](https://create.roblox.com/docs/reference/engine/classes/AvatarAbilityRules#EnableTurning): bool [⚡ThreadSafety: ReadSafe]
* Update Class [CaptureService](https://create.roblox.com/docs/reference/engine/classes/CaptureService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [CaptureService.CheckUploadCaptureStatusForSupportTicketAsync](https://create.roblox.com/docs/reference/engine/classes/CaptureService#CheckUploadCaptureStatusForSupportTicketAsync) (operationId: string) -> Tuple [🏷️ Yields] {🚧Capture}
* Update Class [Decal](https://create.roblox.com/docs/reference/engine/classes/Decal) [⬆️Extends: FaceInstance] [🧠Memory: GraphicsTexture]
  * Added Property [Decal.EmissiveMaskContent](https://create.roblox.com/docs/reference/engine/classes/Decal#EmissiveMaskContent): Content {🚧Read: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Property [Decal.EmissiveStrength](https://create.roblox.com/docs/reference/engine/classes/Decal#EmissiveStrength): float {🚧Read: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Property [Decal.EmissiveTint](https://create.roblox.com/docs/reference/engine/classes/Decal#EmissiveTint): Color3 {🚧Read: Basic} [⚡ThreadSafety: ReadSafe]
* Update Class [TriangleMeshPart](https://create.roblox.com/docs/reference/engine/classes/TriangleMeshPart) [⬆️Extends: BasePart] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotBrowsable]
  * Added Property [TriangleMeshPart.CollisionPrecision](https://create.roblox.com/docs/reference/engine/classes/TriangleMeshPart#CollisionPrecision): float [🏷️ NotReplicated] {🚧Read: Basic} [⚡ThreadSafety: ReadSafe]
* Update Class [PluginManagementService](https://create.roblox.com/docs/reference/engine/classes/PluginManagementService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [PluginManagementService.ListPluginGuisAsync](https://create.roblox.com/docs/reference/engine/classes/PluginManagementService#ListPluginGuisAsync) () -> Dictionary [🏷️ Yields]
* Update Class [PublishService](https://create.roblox.com/docs/reference/engine/classes/PublishService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [PublishService.TagEmoteAnimation](https://create.roblox.com/docs/reference/engine/classes/PublishService#TagEmoteAnimation) (instance: Instance) -> null
* Update Class [RunService](https://create.roblox.com/docs/reference/engine/classes/RunService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [RunService.IsTeamTest](https://create.roblox.com/docs/reference/engine/classes/RunService#IsTeamTest) () -> bool {🚧Basic} [⚡ThreadSafety: Safe]
* Update Class [ScriptEditorService](https://create.roblox.com/docs/reference/engine/classes/ScriptEditorService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [ScriptEditorService.OpenTemporaryDocumentAsync](https://create.roblox.com/docs/reference/engine/classes/ScriptEditorService#OpenTemporaryDocumentAsync) (scriptId: string, initialContent: string) -> Tuple [🏷️ Yields]
* Update Class [DataModel](https://create.roblox.com/docs/reference/engine/classes/DataModel) [⬆️Extends: ServiceProvider] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Added Event [DataModel.ServerLowMemoryWarning](https://create.roblox.com/docs/reference/engine/classes/DataModel#ServerLowMemoryWarning)
* Added Class [StateMachineDefinition](https://create.roblox.com/docs/reference/engine/classes/StateMachineDefinition) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotReplicated]
  * Added Property [StateMachineDefinition.NodeId](https://create.roblox.com/docs/reference/engine/classes/StateMachineDefinition#NodeId) [⚡ThreadSafety: ReadSafe]
* Added Class [StateMachineTransitionDefinition](https://create.roblox.com/docs/reference/engine/classes/StateMachineTransitionDefinition) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotReplicated]
* Update Class [StudioWidget](https://create.roblox.com/docs/reference/engine/classes/StudioWidget) [⬆️Extends: StudioObjectBase] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Function [StudioWidget.SetMinSize](https://create.roblox.com/docs/reference/engine/classes/StudioWidget#SetMinSize) (width: int, height: int) -> null
* Update Class [TestService](https://create.roblox.com/docs/reference/engine/classes/TestService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ Service]
  * Added Function [TestService.SignalProfilingCapture](https://create.roblox.com/docs/reference/engine/classes/TestService#SignalProfilingCapture) (target: string = , options: Dictionary = nil) -> null {🚧InternalTest}
  * Added Function [TestService.SignalProfilingStart](https://create.roblox.com/docs/reference/engine/classes/TestService#SignalProfilingStart) (target: string = , options: Dictionary = nil) -> null {🚧InternalTest}
  * Added Function [TestService.SignalProfilingStop](https://create.roblox.com/docs/reference/engine/classes/TestService#SignalProfilingStop) (target: string = ) -> null {🚧InternalTest}
  * Changed the parameters of Function [TestService.RequestValidationAsync](https://create.roblox.com/docs/reference/engine/classes/TestService#RequestValidationAsync)
    from: (artifactType: string, artifactName: string, timeoutSeconds: double = 60)
    to: (module: string, artifactName: string, options: Variant)
* Update Class [UGCValidationService](https://create.roblox.com/docs/reference/engine/classes/UGCValidationService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [UGCValidationService.AreInstanceTreesEquivalent](https://create.roblox.com/docs/reference/engine/classes/UGCValidationService#AreInstanceTreesEquivalent) (expectedTree: Instance, candidateTree: Instance) -> bool
* Update Class [LuauExpression](https://create.roblox.com/docs/reference/engine/classes/LuauExpression) [⬆️Extends: Object] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Added Function [LuauExpression.References](https://create.roblox.com/docs/reference/engine/classes/LuauExpression#References) (variableName: string) -> bool
* Added Enum [AnimationNodeTransitionWhen](https://create.roblox.com/docs/reference/engine/enums/AnimationNodeTransitionWhen)
  * Added EnumItem `Finished` (0)
  * Added EnumItem `BeforeFinished` (1)
* Update Enum [CollisionFidelity](https://create.roblox.com/docs/reference/engine/enums/CollisionFidelity)
  * Added EnumItem `Tunable` (4)
  * Removed EnumItem `Scalable`
* Update Enum [GenerateMomentTextResult](https://create.roblox.com/docs/reference/engine/enums/GenerateMomentTextResult)
  * Added EnumItem `Filtered` (3)
