# Roblox Client Tracker

| Metadata | Details |
| :--- | :--- |
| **Version** | `0.739.0.7390687` |
| **Version Hash** | `version-55808de4b1914919` |
| **Official Release Notes** | [Release Notes 739](https://create.roblox.com/docs/release-notes/release-notes-739) |

---

## Changelog

* Added Class [AdPlacement](https://create.roblox.com/docs/reference/engine/classes/AdPlacement) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Property [AdPlacement.ActivationInstance](https://create.roblox.com/docs/reference/engine/classes/AdPlacement#ActivationInstance) {🚧Read: Monetization | Write: Monetization} [⚡ThreadSafety: ReadSafe]
  * Added Property [AdPlacement.AdFormat](https://create.roblox.com/docs/reference/engine/classes/AdPlacement#AdFormat) {🚧Read: Monetization | Write: Monetization} [⚡ThreadSafety: ReadSafe]
  * Added Property [AdPlacement.PlacementId](https://create.roblox.com/docs/reference/engine/classes/AdPlacement#PlacementId) {🚧Read: Monetization | Write: Monetization} [⚡ThreadSafety: ReadSafe]
  * Added Property [AdPlacement.RewardId](https://create.roblox.com/docs/reference/engine/classes/AdPlacement#RewardId) [🏷️ ReadOnly] [🏷️ NotReplicated] {🚧Read: Monetization | Write: Monetization} [⚡ThreadSafety: ReadSafe]
  * Added Property [AdPlacement.RewardImageContent](https://create.roblox.com/docs/reference/engine/classes/AdPlacement#RewardImageContent) [🏷️ ReadOnly] [🏷️ NotReplicated] {🚧Read: Monetization | Write: Monetization} [⚡ThreadSafety: ReadSafe]
  * Added Property [AdPlacement.RewardName](https://create.roblox.com/docs/reference/engine/classes/AdPlacement#RewardName) [🏷️ ReadOnly] [🏷️ NotReplicated] {🚧Read: Monetization | Write: Monetization} [⚡ThreadSafety: ReadSafe]
  * Added Property [AdPlacement.Visible](https://create.roblox.com/docs/reference/engine/classes/AdPlacement#Visible) [🏷️ ReadOnly] [🏷️ NotReplicated] {🚧Read: Monetization | Write: Monetization} [⚡ThreadSafety: ReadSafe]
* Update Class [CallingService](https://create.roblox.com/docs/reference/engine/classes/CallingService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [CallingService.CreateCallAsync](https://create.roblox.com/docs/reference/engine/classes/CallingService#CreateCallAsync) (participantIds: Array = {}, chatChannelId: string = ) -> Dictionary [🏷️ Yields]
  * Removed Function CallingService.CreateCall
* Added Class [ExternalIdentityService](https://create.roblox.com/docs/reference/engine/classes/ExternalIdentityService) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [ExternalIdentityService.CancelActiveOperation](https://create.roblox.com/docs/reference/engine/classes/ExternalIdentityService#CancelActiveOperation)
  * Added Function [ExternalIdentityService.AcquireProofAsync](https://create.roblox.com/docs/reference/engine/classes/ExternalIdentityService#AcquireProofAsync) [🏷️ Yields]
  * Added Function [ExternalIdentityService.GetCapabilitiesAsync](https://create.roblox.com/docs/reference/engine/classes/ExternalIdentityService#GetCapabilitiesAsync) [🏷️ Yields]
* Update Class [Terrain](https://create.roblox.com/docs/reference/engine/classes/Terrain) [⬆️Extends: BasePart] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Added Function [Terrain.ReplaceMaterialInTransformSubregionSlot](https://create.roblox.com/docs/reference/engine/classes/Terrain#ReplaceMaterialInTransformSubregionSlot) (cframe: CFrame, size: Vector3, sourceMaterialIndex: int, targetMaterialIndex: int, targetRegion: Region3int16) -> null {🚧Environment}
  * Added Function [Terrain.SetMaterialInTransformSubregionSlot](https://create.roblox.com/docs/reference/engine/classes/Terrain#SetMaterialInTransformSubregionSlot) (cframe: CFrame, size: Vector3, targetMaterialIndex: int, targetRegion: Region3int16) -> null {🚧Environment}
* Update Class [Workspace](https://create.roblox.com/docs/reference/engine/classes/Workspace) [⬆️Extends: WorldRoot] [🧠Memory: BaseParts] [🏷️ NotCreatable] [🏷️ Service]
  * Added Property [Workspace.MapTVRemoteToGamepadKeycodes](https://create.roblox.com/docs/reference/engine/classes/Workspace#MapTVRemoteToGamepadKeycodes): RolloutState [🏷️ NotScriptable] [⚡ThreadSafety: ReadSafe]
* Added Class [QueueService](https://create.roblox.com/docs/reference/engine/classes/QueueService) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [QueueService.GetStandardQueue](https://create.roblox.com/docs/reference/engine/classes/QueueService#GetStandardQueue) {🚧DataStore}
* Added Class [StandardQueue](https://create.roblox.com/docs/reference/engine/classes/StandardQueue) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Function [StandardQueue.BatchCommitAsync](https://create.roblox.com/docs/reference/engine/classes/StandardQueue#BatchCommitAsync) [🏷️ Yields] {🚧DataStore}
  * Added Function [StandardQueue.PublishAsync](https://create.roblox.com/docs/reference/engine/classes/StandardQueue#PublishAsync) [🏷️ Yields] {🚧DataStore}
  * Added Function [StandardQueue.SubscribeAsync](https://create.roblox.com/docs/reference/engine/classes/StandardQueue#SubscribeAsync) [🏷️ Yields] {🚧DataStore}
* Update Class [StarterPlayer](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Property [StarterPlayer.PlaceAvatarRules](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#PlaceAvatarRules): Instance [🏷️ Hidden] {🚧Read: Players} [⚡ThreadSafety: ReadSafe]
* Update Class [StateMachineTransitionDefinition](https://create.roblox.com/docs/reference/engine/classes/StateMachineTransitionDefinition) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Property [StateMachineTransitionDefinition.From](https://create.roblox.com/docs/reference/engine/classes/StateMachineTransitionDefinition#From): Instance {🚧Read: Animation | Write: Animation} [⚡ThreadSafety: ReadSafe]
  * Added Property [StateMachineTransitionDefinition.Priority](https://create.roblox.com/docs/reference/engine/classes/StateMachineTransitionDefinition#Priority): int {🚧Read: Animation | Write: Animation} [⚡ThreadSafety: ReadSafe]
  * Added Property [StateMachineTransitionDefinition.To](https://create.roblox.com/docs/reference/engine/classes/StateMachineTransitionDefinition#To): Instance {🚧Read: Animation | Write: Animation} [⚡ThreadSafety: ReadSafe]
  * Added Property [StateMachineTransitionDefinition.TransitionId](https://create.roblox.com/docs/reference/engine/classes/StateMachineTransitionDefinition#TransitionId): string {🚧Read: Animation} [⚡ThreadSafety: ReadSafe]
* Update Class [TextChannel](https://create.roblox.com/docs/reference/engine/classes/TextChannel) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Property [TextChannel.IsDefaultTextChannel](https://create.roblox.com/docs/reference/engine/classes/TextChannel#IsDefaultTextChannel): bool [🏷️ Hidden] {🚧Read: Chat} [⚡ThreadSafety: ReadSafe]
* Update Class [ChatWindowConfiguration](https://create.roblox.com/docs/reference/engine/classes/ChatWindowConfiguration) [⬆️Extends: TextChatConfigurations] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Added Property [ChatWindowConfiguration.TextChannelDisplayMode](https://create.roblox.com/docs/reference/engine/classes/ChatWindowConfiguration#TextChannelDisplayMode): TextChannelDisplayMode {🚧Read: Chat | Write: PluginOrOpenCloud} [⚡ThreadSafety: ReadSafe]
* Update Class [UGCValidationService](https://create.roblox.com/docs/reference/engine/classes/UGCValidationService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [UGCValidationService.GetLayeredClothingPostDeformationSizeAsync](https://create.roblox.com/docs/reference/engine/classes/UGCValidationService#GetLayeredClothingPostDeformationSizeAsync) (accessory: Accessory, editableMesh: EditableMesh, meshScale: Vector3) -> Vector3 [🏷️ Yields]
* Added Enum [AnimationNodeBlendMode](https://create.roblox.com/docs/reference/engine/enums/AnimationNodeBlendMode)
  * Added EnumItem `Over` (0)
  * Added EnumItem `Add` (1)
  * Added EnumItem `Subtract` (2)
* Update Enum [AnimationNodeType](https://create.roblox.com/docs/reference/engine/enums/AnimationNodeType)
  * Added EnumItem `OneShotNode` (14)
  * Added EnumItem `StateMachineNode` (16)
* Update Enum [PromptCreateOutfitResult](https://create.roblox.com/docs/reference/engine/enums/PromptCreateOutfitResult)
  * Added EnumItem `UGCValidationFailed` (8)
* Added Enum [QueueDecision](https://create.roblox.com/docs/reference/engine/enums/QueueDecision)
  * Added EnumItem `Commit` (0)
  * Added EnumItem `Defer` (1)
* Added Enum [TextChannelDisplayMode](https://create.roblox.com/docs/reference/engine/enums/TextChannelDisplayMode)
  * Added EnumItem `AllTextChannels` (0)
  * Added EnumItem `DefaultTextChannels` (1)
