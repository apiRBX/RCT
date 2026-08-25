# Roblox Client Tracker

| Metadata | Details |
| :--- | :--- |
| **Version** | `0.735.0.7351131` |
| **Version Hash** | `version-dcbeee682ce74ee0` |
| **Official Release Notes** | [Release Notes 735](https://create.roblox.com/docs/release-notes/release-notes-735) |

---

## Changelog

* Update Class [AdService](https://create.roblox.com/docs/reference/engine/classes/AdService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Removed Function AdService.RegisterImpressionSource
* Update Class [AssetService](https://create.roblox.com/docs/reference/engine/classes/AssetService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Removed Function AssetService.CreateDecalAsync
  * Removed Function AssetService.CreateTextureAsync
* Update Class [AvatarAbilityRules](https://create.roblox.com/docs/reference/engine/classes/AvatarAbilityRules) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Removed Property AvatarAbilityRules.EnableTurning
* Update Class [CaptureService](https://create.roblox.com/docs/reference/engine/classes/CaptureService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Removed Function CaptureService.CheckUploadCaptureStatusForSupportTicketAsync
* Update Class [Decal](https://create.roblox.com/docs/reference/engine/classes/Decal) [⬆️Extends: FaceInstance] [🧠Memory: GraphicsTexture]
  * Removed Property Decal.EmissiveMaskContent
  * Removed Property Decal.EmissiveStrength
  * Removed Property Decal.EmissiveTint
* Update Class [TriangleMeshPart](https://create.roblox.com/docs/reference/engine/classes/TriangleMeshPart) [⬆️Extends: BasePart] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Removed Property TriangleMeshPart.CollisionPrecision
* Update Class [PluginManagementService](https://create.roblox.com/docs/reference/engine/classes/PluginManagementService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Removed Function PluginManagementService.ListPluginGuisAsync
* Update Class [PublishService](https://create.roblox.com/docs/reference/engine/classes/PublishService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Removed Function PublishService.TagEmoteAnimation
* Update Class [RunService](https://create.roblox.com/docs/reference/engine/classes/RunService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Removed Function RunService.IsTeamTest
* Update Class [ScriptEditorService](https://create.roblox.com/docs/reference/engine/classes/ScriptEditorService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Removed Function ScriptEditorService.OpenTemporaryDocumentAsync
* Update Class [DataModel](https://create.roblox.com/docs/reference/engine/classes/DataModel) [⬆️Extends: ServiceProvider] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Removed Event DataModel.ServerLowMemoryWarning
* Update Class [StudioWidget](https://create.roblox.com/docs/reference/engine/classes/StudioWidget) [⬆️Extends: StudioObjectBase] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Removed Function StudioWidget.SetMinSize
* Update Class [TestService](https://create.roblox.com/docs/reference/engine/classes/TestService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ Service]
  * Changed the parameters of Function [TestService.RequestValidationAsync](https://create.roblox.com/docs/reference/engine/classes/TestService#RequestValidationAsync)
    from: (module: string, artifactName: string, options: Variant)
    to: (artifactType: string, artifactName: string, timeoutSeconds: double = 60)
  * Removed Function TestService.SignalProfilingCapture
  * Removed Function TestService.SignalProfilingStart
  * Removed Function TestService.SignalProfilingStop
* Update Class [UGCValidationService](https://create.roblox.com/docs/reference/engine/classes/UGCValidationService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Removed Function UGCValidationService.AreInstanceTreesEquivalent
* Update Class [LuauExpression](https://create.roblox.com/docs/reference/engine/classes/LuauExpression) [⬆️Extends: Object] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Removed Function LuauExpression.References
* Removed Class StateMachineDefinition
* Removed Class StateMachineTransitionDefinition
* Update Enum [CollisionFidelity](https://create.roblox.com/docs/reference/engine/enums/CollisionFidelity)
  * Added EnumItem `Scalable` (4)
  * Removed EnumItem `Tunable`
* Update Enum [GenerateMomentTextResult](https://create.roblox.com/docs/reference/engine/enums/GenerateMomentTextResult)
  * Removed EnumItem `Filtered`
* Removed Enum AnimationNodeTransitionWhen
