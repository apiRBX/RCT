# Roblox Client Tracker

| Metadata | Details |
| :--- | :--- |
| **Version** | `0.740.0.7400927` |
| **Version Hash** | `version-3afcc74cf8b04b5d` |
| **Official Release Notes** | [Release Notes 740](https://create.roblox.com/docs/release-notes/release-notes-740) |

---

## Changelog

* Update Class [EditableImage](https://create.roblox.com/docs/reference/engine/classes/EditableImage) [⬆️Extends: Object] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed the parameters of Function [EditableImage.DrawImageProjected](https://create.roblox.com/docs/reference/engine/classes/EditableImage#DrawImageProjected)
    from: (mesh: EditableMesh, projection: Dictionary, brushConfig: Dictionary)
    to: (projectionSource: Object, projection: Dictionary, brushConfig: Dictionary)
  * Changed the parameters of Function [EditableImage.SampleImageProjected](https://create.roblox.com/docs/reference/engine/classes/EditableImage#SampleImageProjected)
    from: (sourceMesh: EditableMesh, sourceTexture: EditableImage, projectionConfig: Dictionary, brushConfig: Dictionary)
    to: (projectionSource: Object, sourceTexture: EditableImage, projectionConfig: Dictionary, brushConfig: Dictionary)
* Update Class [AssetQualityService](https://create.roblox.com/docs/reference/engine/classes/AssetQualityService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [AssetQualityService.FetchAssetQualitySummaryFromJobIdV2Async](https://create.roblox.com/docs/reference/engine/classes/AssetQualityService#FetchAssetQualitySummaryFromJobIdV2Async) (jobId: string, desiredQualityChecks: Array) -> Dictionary [🏷️ Yields]
* Update Class [AudioTextToSpeech](https://create.roblox.com/docs/reference/engine/classes/AudioTextToSpeech) [⬆️Extends: Instance] [🧠Memory: Internal]
  * Added Property [AudioTextToSpeech.AutoLocalize](https://create.roblox.com/docs/reference/engine/classes/AudioTextToSpeech#AutoLocalize): bool {🚧Read: Audio | Write: Audio} [⚡ThreadSafety: ReadSafe]
* Update Class [CaptureService](https://create.roblox.com/docs/reference/engine/classes/CaptureService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [CaptureService.StopVideoCaptureForMCP](https://create.roblox.com/docs/reference/engine/classes/CaptureService#StopVideoCaptureForMCP) () -> null {🚧Capture}
  * Added Function [CaptureService.StartVideoCaptureForMCPAsync](https://create.roblox.com/docs/reference/engine/classes/CaptureService#StartVideoCaptureForMCPAsync) (onCaptureReady: Function) -> VideoCaptureStartedResult [🏷️ Yields] {🚧Capture}
* Update Class [InputAction](https://create.roblox.com/docs/reference/engine/classes/InputAction) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Property [InputAction.DisplayName](https://create.roblox.com/docs/reference/engine/classes/InputAction#DisplayName): string {🚧Read: Input | Write: Input} [⚡ThreadSafety: ReadSafe]
* Update Class [Lighting](https://create.roblox.com/docs/reference/engine/classes/Lighting) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the security of Property [Lighting.LightingStyle](https://create.roblox.com/docs/reference/engine/classes/Lighting#LightingStyle)
    from: {🔒Read:None, Write:RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [Lighting.LightingStyle](https://create.roblox.com/docs/reference/engine/classes/Lighting#LightingStyle)
    from: {🚧Read: Environment}
    to: {🚧Read: Environment | Write: PluginOrOpenCloud}
  * Changed the security of Property [Lighting.PrioritizeLightingQuality](https://create.roblox.com/docs/reference/engine/classes/Lighting#PrioritizeLightingQuality)
    from: {🔒Read:None, Write:RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [Lighting.PrioritizeLightingQuality](https://create.roblox.com/docs/reference/engine/classes/Lighting#PrioritizeLightingQuality)
    from: {🚧Read: Environment}
    to: {🚧Read: Environment | Write: PluginOrOpenCloud}
* Update Class [MarketplaceService](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [MarketplaceService.RefreshBulkPurchase](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#RefreshBulkPurchase) (batchPurchaseAuthToken: string, options: Dictionary = nil) -> null
  * Added Event [MarketplaceService.PromptBulkPurchaseRefreshed](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptBulkPurchaseRefreshed)
  * Added Event [MarketplaceService.RefreshBulkPurchaseRequested](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#RefreshBulkPurchaseRequested)
* Update Class [MomentsService](https://create.roblox.com/docs/reference/engine/classes/MomentsService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [MomentsService.FetchPostAsync](https://create.roblox.com/docs/reference/engine/classes/MomentsService#FetchPostAsync) (assetId: int64) -> buffer [🏷️ Yields] {🚧Capture}
* Update Class [TriangleMeshPart](https://create.roblox.com/docs/reference/engine/classes/TriangleMeshPart) [⬆️Extends: BasePart] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotBrowsable]
  * Changed the security of Property [TriangleMeshPart.CollisionFidelity](https://create.roblox.com/docs/reference/engine/classes/TriangleMeshPart#CollisionFidelity)
    from: {🔒Read:None, Write:PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [TriangleMeshPart.CollisionFidelity](https://create.roblox.com/docs/reference/engine/classes/TriangleMeshPart#CollisionFidelity)
    from: {🚧Read: Basic}
    to: {🚧Read: Basic | Write: PluginOrOpenCloud}
  * Changed the security of Property [TriangleMeshPart.FluidFidelity](https://create.roblox.com/docs/reference/engine/classes/TriangleMeshPart#FluidFidelity)
    from: {🔒Read:None, Write:PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [TriangleMeshPart.FluidFidelity](https://create.roblox.com/docs/reference/engine/classes/TriangleMeshPart#FluidFidelity)
    from: {🚧Read: Basic}
    to: {🚧Read: Basic | Write: PluginOrOpenCloud}
* Update Class [PartOperation](https://create.roblox.com/docs/reference/engine/classes/PartOperation) [⬆️Extends: TriangleMeshPart] [🧠Memory: Instances]
  * Changed the security of Property [PartOperation.RenderFidelity](https://create.roblox.com/docs/reference/engine/classes/PartOperation#RenderFidelity)
    from: {🔒Read:None, Write:PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [PartOperation.RenderFidelity](https://create.roblox.com/docs/reference/engine/classes/PartOperation#RenderFidelity)
    from: {🚧Read: Basic, CSG}
    to: {🚧Read: Basic, CSG | Write: PluginOrOpenCloud}
  * Changed the security of Property [PartOperation.SmoothingAngle](https://create.roblox.com/docs/reference/engine/classes/PartOperation#SmoothingAngle)
    from: {🔒Read:None, Write:PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [PartOperation.SmoothingAngle](https://create.roblox.com/docs/reference/engine/classes/PartOperation#SmoothingAngle)
    from: {🚧Read: Basic, CSG}
    to: {🚧Read: Basic, CSG | Write: PluginOrOpenCloud}
* Update Class [WorldRoot](https://create.roblox.com/docs/reference/engine/classes/WorldRoot) [⬆️Extends: Model] [🧠Memory: BaseParts] [🏷️ NotCreatable]
  * Changed ThreadSafety of Property [WorldRoot.PhysicsStepTime](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#PhysicsStepTime) from `Safe` to `ReadSafe`
* Update Class [PerformanceControlService](https://create.roblox.com/docs/reference/engine/classes/PerformanceControlService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [PerformanceControlService.SetUserActivity](https://create.roblox.com/docs/reference/engine/classes/PerformanceControlService#SetUserActivity) (state: ScrollState) -> null
* Update Class [Plugin](https://create.roblox.com/docs/reference/engine/classes/Plugin) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed the parameters of Function [Plugin.FinishFullLoading](https://create.roblox.com/docs/reference/engine/classes/Plugin#FinishFullLoading)
    from: ()
    to: (payload: Variant)
  * Added Function [Plugin.GetPreinitPayload](https://create.roblox.com/docs/reference/engine/classes/Plugin#GetPreinitPayload) () -> Variant [🏷️ CustomLuaState]
* Update Class [TeleportOptions](https://create.roblox.com/docs/reference/engine/classes/TeleportOptions) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Property [TeleportOptions.ReservedServerId](https://create.roblox.com/docs/reference/engine/classes/TeleportOptions#ReservedServerId): string {🚧Read: Teleport | Write: Teleport} [⚡ThreadSafety: ReadSafe]
  * Added Property [TeleportOptions.VipServerId](https://create.roblox.com/docs/reference/engine/classes/TeleportOptions#VipServerId): string {🚧Read: Teleport | Write: Teleport} [⚡ThreadSafety: ReadSafe]
* Update Class [TeleportService](https://create.roblox.com/docs/reference/engine/classes/TeleportService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [TeleportService.TeleportSwitchServer](https://create.roblox.com/docs/reference/engine/classes/TeleportService#TeleportSwitchServer) () -> null {🚧Teleport}
* Update Class [WrapTextureTransfer](https://create.roblox.com/docs/reference/engine/classes/WrapTextureTransfer) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Function [WrapTextureTransfer.PrepareProjectionMeshDataAsync](https://create.roblox.com/docs/reference/engine/classes/WrapTextureTransfer#PrepareProjectionMeshDataAsync) () -> null [🏷️ Yields] {🚧AvatarAppearance, DynamicGeneration}
* Removed Class SnippetService
* Update Enum [TeleportMethod](https://create.roblox.com/docs/reference/engine/enums/TeleportMethod)
  * Added EnumItem `TeleportSwitchServer` (8)
* Removed Enum Language
