# Roblox Client Tracker

| Metadata | Details |
| :--- | :--- |
| **Version** | `0.735.0.7351131` |
| **Version Hash** | `version-dcbeee682ce74ee0` |
| **Official Release Notes** | [Release Notes 735](https://create.roblox.com/docs/release-notes/release-notes-735) |

---

## Changelog

* Update Class [AnimationNodeDefinition](https://create.roblox.com/docs/reference/engine/classes/AnimationNodeDefinition) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the security of Function [AnimationNodeDefinition.AddInputPin](https://create.roblox.com/docs/reference/engine/classes/AnimationNodeDefinition#AddInputPin)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the security of Function [AnimationNodeDefinition.GetOrderedInputPinNames](https://create.roblox.com/docs/reference/engine/classes/AnimationNodeDefinition#GetOrderedInputPinNames)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the security of Function [AnimationNodeDefinition.RemoveInputPin](https://create.roblox.com/docs/reference/engine/classes/AnimationNodeDefinition#RemoveInputPin)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the security of Function [AnimationNodeDefinition.SetOrderedInputPinNames](https://create.roblox.com/docs/reference/engine/classes/AnimationNodeDefinition#SetOrderedInputPinNames)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the security of Event [AnimationNodeDefinition.InputPinsChanged](https://create.roblox.com/docs/reference/engine/classes/AnimationNodeDefinition#InputPinsChanged)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
* Update Class [AppLifecycleObserverService](https://create.roblox.com/docs/reference/engine/classes/AppLifecycleObserverService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [AppLifecycleObserverService.TriggerOnPageMilestone](https://create.roblox.com/docs/reference/engine/classes/AppLifecycleObserverService#TriggerOnPageMilestone) (page: PageType, milestone: PageMilestoneType) -> null
* Update Class [AvatarAbilityRules](https://create.roblox.com/docs/reference/engine/classes/AvatarAbilityRules) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Removed Property AvatarAbilityRules.EnableStrafing
* Added Class [BranchService](https://create.roblox.com/docs/reference/engine/classes/BranchService) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
* Update Class [GenerationService](https://create.roblox.com/docs/reference/engine/classes/GenerationService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [GenerationService.ExportMeshToGlbAsync](https://create.roblox.com/docs/reference/engine/classes/GenerationService#ExportMeshToGlbAsync) (meshPart: MeshPart) -> string [🏷️ Yields] {🚧DynamicGeneration}
  * Added Function [GenerationService.LoadModelFromUrlAsync](https://create.roblox.com/docs/reference/engine/classes/GenerationService#LoadModelFromUrlAsync) (url: string) -> Model [🏷️ Yields] {🚧DynamicGeneration}
* Added Class [IntentService](https://create.roblox.com/docs/reference/engine/classes/IntentService) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
* Update Class [LogService](https://create.roblox.com/docs/reference/engine/classes/LogService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [LogService.GetLogHistoryAsync](https://create.roblox.com/docs/reference/engine/classes/LogService#GetLogHistoryAsync) (user: User) -> Array [🏷️ Yields] {🚧Logging}
* Update Class [Terrain](https://create.roblox.com/docs/reference/engine/classes/Terrain) [⬆️Extends: BasePart] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Added Function [Terrain.GenerateWaterFlowMap](https://create.roblox.com/docs/reference/engine/classes/Terrain#GenerateWaterFlowMap) (generateFoam: bool) -> null {🚧Environment}
  * Added Function [Terrain.ResetWaterFlowMap](https://create.roblox.com/docs/reference/engine/classes/Terrain#ResetWaterFlowMap) () -> null {🚧Environment}
* Update Class [Workspace](https://create.roblox.com/docs/reference/engine/classes/Workspace) [⬆️Extends: WorldRoot] [🧠Memory: BaseParts] [🏷️ NotCreatable] [🏷️ Service]
  * Added Property [Workspace.ExpandedTerrain](https://create.roblox.com/docs/reference/engine/classes/Workspace#ExpandedTerrain): RolloutState [🏷️ NotScriptable] [⚡ThreadSafety: ReadSafe]
* Update Class [Player](https://create.roblox.com/docs/reference/engine/classes/Player) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Function [Player.GetFriendsInUniverseAsync](https://create.roblox.com/docs/reference/engine/classes/Player#GetFriendsInUniverseAsync) () -> Array [🏷️ Yields] {🚧Players, Social}
* Added Class [PlayerControlState](https://create.roblox.com/docs/reference/engine/classes/PlayerControlState) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotBrowsable]
  * Added Property [PlayerControlState.Owner](https://create.roblox.com/docs/reference/engine/classes/PlayerControlState#Owner) [⚡ThreadSafety: ReadSafe]
  * Added Function [PlayerControlState.AddBoolField](https://create.roblox.com/docs/reference/engine/classes/PlayerControlState#AddBoolField)
  * Added Function [PlayerControlState.AddCFrameField](https://create.roblox.com/docs/reference/engine/classes/PlayerControlState#AddCFrameField)
  * Added Function [PlayerControlState.AddInstanceField](https://create.roblox.com/docs/reference/engine/classes/PlayerControlState#AddInstanceField)
  * Added Function [PlayerControlState.AddIntField](https://create.roblox.com/docs/reference/engine/classes/PlayerControlState#AddIntField)
  * Added Function [PlayerControlState.AddNumberField](https://create.roblox.com/docs/reference/engine/classes/PlayerControlState#AddNumberField)
  * Added Function [PlayerControlState.AddUnitVector3Field](https://create.roblox.com/docs/reference/engine/classes/PlayerControlState#AddUnitVector3Field)
  * Added Function [PlayerControlState.AddVector2Field](https://create.roblox.com/docs/reference/engine/classes/PlayerControlState#AddVector2Field)
  * Added Function [PlayerControlState.AddVector3Field](https://create.roblox.com/docs/reference/engine/classes/PlayerControlState#AddVector3Field)
  * Added Function [PlayerControlState.GetChangedState](https://create.roblox.com/docs/reference/engine/classes/PlayerControlState#GetChangedState)
  * Added Function [PlayerControlState.GetReplicationWeight](https://create.roblox.com/docs/reference/engine/classes/PlayerControlState#GetReplicationWeight)
  * Added Function [PlayerControlState.GetState](https://create.roblox.com/docs/reference/engine/classes/PlayerControlState#GetState)
  * Added Function [PlayerControlState.SetField](https://create.roblox.com/docs/reference/engine/classes/PlayerControlState#SetField)
  * Added Function [PlayerControlState.UpdateFields](https://create.roblox.com/docs/reference/engine/classes/PlayerControlState#UpdateFields)
  * Added Event [PlayerControlState.OnStateChanged](https://create.roblox.com/docs/reference/engine/classes/PlayerControlState#OnStateChanged)
* Update Class [RealtimeMedia](https://create.roblox.com/docs/reference/engine/classes/RealtimeMedia) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Event [RealtimeMedia.AudioInputRequested](https://create.roblox.com/docs/reference/engine/classes/RealtimeMedia#AudioInputRequested) {🚧InternalTest}
* Update Class [SafetyService](https://create.roblox.com/docs/reference/engine/classes/SafetyService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [SafetyService.ReportBuildUIClose](https://create.roblox.com/docs/reference/engine/classes/SafetyService#ReportBuildUIClose) () -> null
  * Added Function [SafetyService.ReportBuildUIOpen](https://create.roblox.com/docs/reference/engine/classes/SafetyService#ReportBuildUIOpen) () -> null
* Added Class [ScriptScannerService](https://create.roblox.com/docs/reference/engine/classes/ScriptScannerService) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
* Update Class [Studio](https://create.roblox.com/docs/reference/engine/classes/Studio) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Removed Property Studio.CameraAdaptiveSpeed
  * Removed Property Studio.CameraOrbitSensitivity
  * Removed Property Studio.CameraPanSensitivity
  * Removed Property Studio.CameraZoomSpeed
* Update Class [StudioCameraService](https://create.roblox.com/docs/reference/engine/classes/StudioCameraService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the serialization of Property [StudioCameraService.LockCameraSpeed](https://create.roblox.com/docs/reference/engine/classes/StudioCameraService#LockCameraSpeed)
    from: [💾|📁Serialized]
    to: [🚫None]
* Update Class [WindowProtocolService](https://create.roblox.com/docs/reference/engine/classes/WindowProtocolService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [WindowProtocolService.OnDragAreaRightClicked](https://create.roblox.com/docs/reference/engine/classes/WindowProtocolService#OnDragAreaRightClicked) (windowId: int) -> null
* Added Enum [IntentReplicability](https://create.roblox.com/docs/reference/engine/enums/IntentReplicability)
* Added Enum [PageMilestoneType](https://create.roblox.com/docs/reference/engine/enums/PageMilestoneType)
  * Added EnumItem `Interactive` (0)
  * Added EnumItem `SurfaceMounted` (1)
  * Added EnumItem `FunctionallyReady` (2)
  * Added EnumItem `SurfaceReady` (3)
* Added Enum [PageType](https://create.roblox.com/docs/reference/engine/enums/PageType)
  * Added EnumItem `AvatarEditor` (0)
  * Added EnumItem `Party` (1)
  * Added EnumItem `ExperienceDetail` (2)
  * Added EnumItem `AvatarMarketplace` (3)
* Added Enum [ScriptScannerUpdateType](https://create.roblox.com/docs/reference/engine/enums/ScriptScannerUpdateType)
  * Added EnumItem `Init` (0)
  * Added EnumItem `Added` (1)
  * Added EnumItem `Removed` (2)
* Added Enum [StateReferenceFrame](https://create.roblox.com/docs/reference/engine/enums/StateReferenceFrame)
  * Added EnumItem `CurrentState` (0)
  * Added EnumItem `PreviousState` (1)
  * Added EnumItem `LastObservedState` (2)
* Removed Enum TagReplicability
