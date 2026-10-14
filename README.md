# Roblox Client Tracker

| Metadata | Details |
| :--- | :--- |
| **Version** | `0.743.0.7431133` |
| **Version Hash** | `version-4f087c32742644ab` |
| **Official Release Notes** | [Release Notes 743](https://create.roblox.com/docs/release-notes/release-notes-743) |

---

## Changelog

* Update Class [AnimatedImageService](https://create.roblox.com/docs/reference/engine/classes/AnimatedImageService) [⬆️Extends: Instance] [🧠Memory: Gui] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [AnimatedImageService.GetAnimatedImageClipsChangedSignal](https://create.roblox.com/docs/reference/engine/classes/AnimatedImageService#GetAnimatedImageClipsChangedSignal) (content: Content) -> RBXScriptSignal
  * Added Function [AnimatedImageService.AddAnimatedImageClipAsync](https://create.roblox.com/docs/reference/engine/classes/AnimatedImageService#AddAnimatedImageClipAsync) (content: Content, clipName: string, frames: Array) -> null [🏷️ Yields]
  * Added Function [AnimatedImageService.GetAnimatedImageClipFramesAsync](https://create.roblox.com/docs/reference/engine/classes/AnimatedImageService#GetAnimatedImageClipFramesAsync) (content: Content, clipName: string) -> Array [🏷️ Yields]
  * Removed Function AnimatedImageService.CreateTrack
  * Removed Function AnimatedImageService.DestroyTrack
  * Removed Function AnimatedImageService.GetFrameNames
  * Removed Function AnimatedImageService.GetTrack
  * Removed Function AnimatedImageService.GetTracksChanged
  * Removed Function AnimatedImageService.Prewarm
  * Removed Function AnimatedImageService.UnloadTracks
* Update Class [AnimationRigData](https://create.roblox.com/docs/reference/engine/classes/AnimationRigData) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the security of Function [AnimationRigData.LoadFromModel](https://create.roblox.com/docs/reference/engine/classes/AnimationRigData#LoadFromModel)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Function [AnimationRigData.LoadFromModel](https://create.roblox.com/docs/reference/engine/classes/AnimationRigData#LoadFromModel)
    from: {🚧Animation}
    to: {🚧Animation, PluginOrOpenCloud}
* Update Class [Animator](https://create.roblox.com/docs/reference/engine/classes/Animator) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Changed the security of Function [Animator.StepAnimations](https://create.roblox.com/docs/reference/engine/classes/Animator#StepAnimations)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Function [Animator.StepAnimations](https://create.roblox.com/docs/reference/engine/classes/Animator#StepAnimations)
    from: {🚧Animation}
    to: {🚧Animation, PluginOrOpenCloud}
* Update Class [AssetQualityService](https://create.roblox.com/docs/reference/engine/classes/AssetQualityService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [AssetQualityService.FetchAssetQualitySummaryFromUrlAsync](https://create.roblox.com/docs/reference/engine/classes/AssetQualityService#FetchAssetQualitySummaryFromUrlAsync) (summaryUrl: string, jobId: string, desiredQualityChecks: Array) -> Dictionary [🏷️ Yields]
* Update Class [AssetService](https://create.roblox.com/docs/reference/engine/classes/AssetService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [AssetService.FetchAssetWithFormat](https://create.roblox.com/docs/reference/engine/classes/AssetService#FetchAssetWithFormat) (url: ContentId, assetFormat: string, options: Dictionary?) -> Instances [🏷️ Yields]
* Update Class [AudioSpeechToText](https://create.roblox.com/docs/reference/engine/classes/AudioSpeechToText) [⬆️Extends: Instance] [🧠Memory: Internal]
  * Added Property [AudioSpeechToText.UsageType](https://create.roblox.com/docs/reference/engine/classes/AudioSpeechToText#UsageType): string [🏷️ Hidden] {🚧Read: Audio} [⚡ThreadSafety: ReadSafe]
* Update Class [AvatarAccessoryRules](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Property [AvatarAccessoryRules.BackAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#BackAccessoryOverride): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarAccessoryRules.FaceAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#FaceAccessoryOverride): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarAccessoryRules.FrontAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#FrontAccessoryOverride): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarAccessoryRules.HairAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#HairAccessoryOverride): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarAccessoryRules.HeadAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#HeadAccessoryOverride): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarAccessoryRules.NeckAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#NeckAccessoryOverride): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarAccessoryRules.ShoulderAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#ShoulderAccessoryOverride): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarAccessoryRules.WaistAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAccessoryRules#WaistAccessoryOverride): int64 [⚡ThreadSafety: ReadSafe]
* Update Class [AvatarAnimationRules](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Property [AvatarAnimationRules.ClimbAnimationOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#ClimbAnimationOverride): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarAnimationRules.FallAnimationOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#FallAnimationOverride): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarAnimationRules.IdleAltAnimationOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#IdleAltAnimationOverride): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarAnimationRules.IdleAnimationOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#IdleAnimationOverride): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarAnimationRules.JumpAnimationOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#JumpAnimationOverride): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarAnimationRules.MoodAnimationOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#MoodAnimationOverride): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarAnimationRules.RunAnimationOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#RunAnimationOverride): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarAnimationRules.SwimAnimationOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#SwimAnimationOverride): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarAnimationRules.SwimIdleAnimationOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#SwimIdleAnimationOverride): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarAnimationRules.WalkAnimationOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarAnimationRules#WalkAnimationOverride): int64 [⚡ThreadSafety: ReadSafe]
* Update Class [AvatarBodyRules](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Property [AvatarBodyRules.AvatarType](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#AvatarType): GameAvatarType [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarBodyRules.CustomBuildBodyType](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomBuildBodyType): NumberRange [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarBodyRules.CustomBuildHead](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomBuildHead): NumberRange [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarBodyRules.CustomBuildHeight](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomBuildHeight): NumberRange [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarBodyRules.CustomBuildProportions](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomBuildProportions): NumberRange [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarBodyRules.CustomBuildWidth](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomBuildWidth): NumberRange [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarBodyRules.CustomWorldHeight](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#CustomWorldHeight): NumberRange [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarBodyRules.HeadOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#HeadOverride): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarBodyRules.LeftArmOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#LeftArmOverride): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarBodyRules.LeftLegOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#LeftLegOverride): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarBodyRules.RightArmOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#RightArmOverride): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarBodyRules.RightLegOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#RightLegOverride): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarBodyRules.TorsoOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarBodyRules#TorsoOverride): int64 [⚡ThreadSafety: ReadSafe]
* Update Class [AvatarClothingRules](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Property [AvatarClothingRules.ClassicPantsAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#ClassicPantsAccessoryOverride): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarClothingRules.ClassicShirtsAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#ClassicShirtsAccessoryOverride): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarClothingRules.ClassicTShirtsAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#ClassicTShirtsAccessoryOverride): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarClothingRules.DressSkirtAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#DressSkirtAccessoryOverride): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarClothingRules.JacketAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#JacketAccessoryOverride): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarClothingRules.LeftShoesAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#LeftShoesAccessoryOverride): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarClothingRules.PantsAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#PantsAccessoryOverride): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarClothingRules.RightShoesAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#RightShoesAccessoryOverride): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarClothingRules.ShirtAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#ShirtAccessoryOverride): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarClothingRules.ShortsAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#ShortsAccessoryOverride): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarClothingRules.SweaterAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#SweaterAccessoryOverride): int64 [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarClothingRules.TShirtAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#TShirtAccessoryOverride): int64 [⚡ThreadSafety: ReadSafe]
* Update Class [AvatarSettings](https://create.roblox.com/docs/reference/engine/classes/AvatarSettings) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Property [AvatarSettings.RulesSchemaVersion](https://create.roblox.com/docs/reference/engine/classes/AvatarSettings#RulesSchemaVersion): int [⚡ThreadSafety: ReadSafe]
* Update Class [DigitsRigDescription](https://create.roblox.com/docs/reference/engine/classes/DigitsRigDescription) [⬆️Extends: Instance] [🧠Memory: Animation]
  * Changed the security of Function [DigitsRigDescription.SetJoint](https://create.roblox.com/docs/reference/engine/classes/DigitsRigDescription#SetJoint)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Function [DigitsRigDescription.SetJoint](https://create.roblox.com/docs/reference/engine/classes/DigitsRigDescription#SetJoint)
    from: {🚧Animation}
    to: {🚧Animation, PluginOrOpenCloud}
* Added Class [FeatureMatchingTable](https://create.roblox.com/docs/reference/engine/classes/FeatureMatchingTable) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Property [FeatureMatchingTable.SchemaName](https://create.roblox.com/docs/reference/engine/classes/FeatureMatchingTable#SchemaName) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Function [FeatureMatchingTable.GetSchema](https://create.roblox.com/docs/reference/engine/classes/FeatureMatchingTable#GetSchema)
* Update Class [FriendsCallingService](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the parameters of Function [FriendsCallingService.StartCall](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingService#StartCall)
    from: ()
    to: (params: Dictionary)
* Update Class [GenerationService](https://create.roblox.com/docs/reference/engine/classes/GenerationService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [GenerationService.GenerateAnimationAsync](https://create.roblox.com/docs/reference/engine/classes/GenerationService#GenerateAnimationAsync) (inputs: Dictionary, options: Dictionary?, progressCallback: Function?) -> Tuple [🏷️ Yields] {🚧DynamicGeneration}
* Update Class [LayerCollector](https://create.roblox.com/docs/reference/engine/classes/LayerCollector) [⬆️Extends: GuiBase2d] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotBrowsable]
  * Changed the security of Function [LayerCollector.GetGuiObjectsAtPosition](https://create.roblox.com/docs/reference/engine/classes/LayerCollector#GetGuiObjectsAtPosition)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
* Update Class [Humanoid](https://create.roblox.com/docs/reference/engine/classes/Humanoid) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Function [Humanoid.ApplyAvatarRulesAsync](https://create.roblox.com/docs/reference/engine/classes/Humanoid#ApplyAvatarRulesAsync) (avatarRules: AvatarRules) -> null [🏷️ Yields]
* Update Class [HumanoidRigDescription](https://create.roblox.com/docs/reference/engine/classes/HumanoidRigDescription) [⬆️Extends: Instance] [🧠Memory: Animation]
  * Changed the security of Function [HumanoidRigDescription.GetJoint](https://create.roblox.com/docs/reference/engine/classes/HumanoidRigDescription#GetJoint)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Function [HumanoidRigDescription.GetJoint](https://create.roblox.com/docs/reference/engine/classes/HumanoidRigDescription#GetJoint)
    from: {🚧Animation}
    to: {🚧Animation, PluginOrOpenCloud}
  * Changed the security of Function [HumanoidRigDescription.GetR15JointLabels](https://create.roblox.com/docs/reference/engine/classes/HumanoidRigDescription#GetR15JointLabels)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Function [HumanoidRigDescription.GetR15JointLabels](https://create.roblox.com/docs/reference/engine/classes/HumanoidRigDescription#GetR15JointLabels)
    from: {🚧Animation}
    to: {🚧Animation, PluginOrOpenCloud}
  * Changed the security of Function [HumanoidRigDescription.SetJoint](https://create.roblox.com/docs/reference/engine/classes/HumanoidRigDescription#SetJoint)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Function [HumanoidRigDescription.SetJoint](https://create.roblox.com/docs/reference/engine/classes/HumanoidRigDescription#SetJoint)
    from: {🚧Animation}
    to: {🚧Animation, PluginOrOpenCloud}
  * Changed the security of Function [HumanoidRigDescription.SetTposeAdjustment](https://create.roblox.com/docs/reference/engine/classes/HumanoidRigDescription#SetTposeAdjustment)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Function [HumanoidRigDescription.SetTposeAdjustment](https://create.roblox.com/docs/reference/engine/classes/HumanoidRigDescription#SetTposeAdjustment)
    from: {🚧Animation}
    to: {🚧Animation, PluginOrOpenCloud}
* Update Class [InputBinding](https://create.roblox.com/docs/reference/engine/classes/InputBinding) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Property [InputBinding.Deadzone](https://create.roblox.com/docs/reference/engine/classes/InputBinding#Deadzone): NumberRange {🚧Read: Input | Write: Input} [⚡ThreadSafety: ReadSafe]
* Added Class [InputReplayService](https://create.roblox.com/docs/reference/engine/classes/InputReplayService) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
* Update Class [BaseScript](https://create.roblox.com/docs/reference/engine/classes/BaseScript) [⬆️Extends: LuaSourceContainer] [🧠Memory: Script] [🏷️ NotCreatable]
  * Changed the security of Property [BaseScript.RunContext](https://create.roblox.com/docs/reference/engine/classes/BaseScript#RunContext)
    from: {🔒Read:None, Write:PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [BaseScript.RunContext](https://create.roblox.com/docs/reference/engine/classes/BaseScript#RunContext)
    from: {🚧None}
    to: {🚧Write: PluginOrOpenCloud}
* Update Class [MarketplaceService](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [MarketplaceService.RedeemGamePassFreeTrial](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#RedeemGamePassFreeTrial) (user: Player, gamePassId: int64, startTime: string, endTime: string) -> null
  * Added Function [MarketplaceService.GetPassOwnershipAsync](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#GetPassOwnershipAsync) (user: Player, gamePassId: int64) -> Dictionary [🏷️ Yields] {🚧AssetRead}
  * Added Event [MarketplaceService.GamePassFreeTrialRedeemed](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#GamePassFreeTrialRedeemed)
* Update Class [WorldRoot](https://create.roblox.com/docs/reference/engine/classes/WorldRoot) [⬆️Extends: Model] [🧠Memory: BaseParts] [🏷️ NotCreatable]
  * Changed the parameters of Function [WorldRoot.Shapecast](https://create.roblox.com/docs/reference/engine/classes/WorldRoot#Shapecast)
    from: (part: BasePart, direction: Vector3, params: RaycastParams = RaycastParams{IgnoreWater=false, BruteForceAllSlow=false, RespectCanCollide=false, CollisionGroup=Default, FilterDescendantsInstances={}})
    to: (part: BasePart, direction: Vector3, params: RaycastParams = RaycastParams{IgnoreWater=false, BruteForceAllSlow=false, RespectCanCollide=false, CollisionGroup=Default, FilterDescendantsInstances={}}, cframeOverride: CoordinateFrame? = nil, sizeOverride: Vector3? = nil)
* Update Class [Workspace](https://create.roblox.com/docs/reference/engine/classes/Workspace) [⬆️Extends: WorldRoot] [🧠Memory: BaseParts] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the security of Property [Workspace.PlayerScriptsUseInputActionSystem](https://create.roblox.com/docs/reference/engine/classes/Workspace#PlayerScriptsUseInputActionSystem)
    from: {🔒None}
    to: {🔒RobloxScriptSecurity}
* Update Class [Packages](https://create.roblox.com/docs/reference/engine/classes/Packages) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Property [Packages.OverridesRecalculated](https://create.roblox.com/docs/reference/engine/classes/Packages#OverridesRecalculated): bool [🏷️ Hidden] [⚡ThreadSafety: ReadSafe]
* Added Class [ParticleEmitter2D](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotBrowsable]
  * Added Property [ParticleEmitter2D.Acceleration](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D#Acceleration) {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Property [ParticleEmitter2D.Blend](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D#Blend) {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Property [ParticleEmitter2D.Brightness](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D#Brightness) {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Property [ParticleEmitter2D.Color](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D#Color) {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Property [ParticleEmitter2D.Drag](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D#Drag) {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Property [ParticleEmitter2D.EmissionAngle](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D#EmissionAngle) {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Property [ParticleEmitter2D.EmissionMode](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D#EmissionMode) {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Property [ParticleEmitter2D.EmissionOffset](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D#EmissionOffset) {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Property [ParticleEmitter2D.EmissionSpread](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D#EmissionSpread) {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Property [ParticleEmitter2D.Enabled](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D#Enabled) {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Property [ParticleEmitter2D.FlipbookBlendFrames](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D#FlipbookBlendFrames) {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Property [ParticleEmitter2D.FlipbookFramerate](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D#FlipbookFramerate) {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Property [ParticleEmitter2D.FlipbookLayout](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D#FlipbookLayout) {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Property [ParticleEmitter2D.FlipbookMode](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D#FlipbookMode) {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Property [ParticleEmitter2D.FlipbookSizeX](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D#FlipbookSizeX) {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Property [ParticleEmitter2D.FlipbookSizeY](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D#FlipbookSizeY) {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Property [ParticleEmitter2D.FlipbookStartRandom](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D#FlipbookStartRandom) {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Property [ParticleEmitter2D.Lifetime](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D#Lifetime) {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Property [ParticleEmitter2D.LightEmission](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D#LightEmission) {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Property [ParticleEmitter2D.LockedToParent](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D#LockedToParent) {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Property [ParticleEmitter2D.Rate](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D#Rate) {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Property [ParticleEmitter2D.RotSpeed](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D#RotSpeed) {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Property [ParticleEmitter2D.Rotation](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D#Rotation) {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Property [ParticleEmitter2D.Size](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D#Size) {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Property [ParticleEmitter2D.Speed](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D#Speed) {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Property [ParticleEmitter2D.SpreadAngle](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D#SpreadAngle) {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Property [ParticleEmitter2D.Squash](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D#Squash) {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Property [ParticleEmitter2D.TextureContent](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D#TextureContent) {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Property [ParticleEmitter2D.TimeScale](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D#TimeScale) {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Property [ParticleEmitter2D.Transparency](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D#Transparency) {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Property [ParticleEmitter2D.ZIndex](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D#ZIndex) {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Function [ParticleEmitter2D.Clear](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D#Clear) {🚧Basic}
  * Added Function [ParticleEmitter2D.Emit](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D#Emit) {🚧Basic}
  * Added Function [ParticleEmitter2D.FastForward](https://create.roblox.com/docs/reference/engine/classes/ParticleEmitter2D#FastForward) {🚧Basic}
* Update Class [PhysicsSettings](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Property [PhysicsSettings.DrawShapecast](https://create.roblox.com/docs/reference/engine/classes/PhysicsSettings#DrawShapecast): bool [⚡ThreadSafety: ReadSafe]
* Update Class [Player](https://create.roblox.com/docs/reference/engine/classes/Player) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Function [Player.LoadCharacterWithAvatarRulesAsync](https://create.roblox.com/docs/reference/engine/classes/Player#LoadCharacterWithAvatarRulesAsync) (avatarRules: AvatarRules) -> null [🏷️ Yields] {🚧Players}
  * Added Event [Player.EmotesLoaded](https://create.roblox.com/docs/reference/engine/classes/Player#EmotesLoaded) {🚧Players}
  * Removed Function Player.LoadCharacterWithAvatarRules
* Update Class [RunService](https://create.roblox.com/docs/reference/engine/classes/RunService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [RunService.IsTeamCreateViewer](https://create.roblox.com/docs/reference/engine/classes/RunService#IsTeamCreateViewer) () -> bool {🚧Basic} [⚡ThreadSafety: Safe]
* Added Class [PhysicsActivitySensor](https://create.roblox.com/docs/reference/engine/classes/PhysicsActivitySensor) {🔒None} [⬆️Extends: SensorBase] [🧠Memory: Instances] [🏷️ NotBrowsable]
  * Added Property [PhysicsActivitySensor.Active](https://create.roblox.com/docs/reference/engine/classes/PhysicsActivitySensor#Active) [🏷️ ReadOnly] [🏷️ NotReplicated] {🚧Read: InternalTest | Write: InternalTest} [⚡ThreadSafety: ReadSafe]
  * Added Property [PhysicsActivitySensor.Position](https://create.roblox.com/docs/reference/engine/classes/PhysicsActivitySensor#Position) {🚧Read: InternalTest | Write: InternalTest} [⚡ThreadSafety: ReadSafe]
  * Added Property [PhysicsActivitySensor.Size](https://create.roblox.com/docs/reference/engine/classes/PhysicsActivitySensor#Size) {🚧Read: InternalTest | Write: InternalTest} [⚡ThreadSafety: ReadSafe]
* Update Class [SoundService](https://create.roblox.com/docs/reference/engine/classes/SoundService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [SoundService.GetPeakLevel](https://create.roblox.com/docs/reference/engine/classes/SoundService#GetPeakLevel) () -> float {🚧Audio}
* Update Class [StarterGear](https://create.roblox.com/docs/reference/engine/classes/StarterGear) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Property [StarterGear.Loaded](https://create.roblox.com/docs/reference/engine/classes/StarterGear#Loaded): bool [🏷️ ReadOnly] [🏷️ NotReplicated] {🚧Read: Players | Write: Players} [⚡ThreadSafety: ReadSafe]
* Update Class [StarterPlayer](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the security of Property [StarterPlayer.CreateDefaultPlayerModule](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#CreateDefaultPlayerModule)
    from: {🔒None}
    to: {🔒RobloxScriptSecurity}
  * Added Property [StarterPlayer.UseImprovedCharacterEvents](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#UseImprovedCharacterEvents): RolloutState [🏷️ NotScriptable] {🚧Read: Players} [⚡ThreadSafety: ReadSafe]
* Update Class [StudioService](https://create.roblox.com/docs/reference/engine/classes/StudioService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Removed Function StudioService.GetPlaceIsPersistedToCloud
* Update Class [SystemThemeService](https://create.roblox.com/docs/reference/engine/classes/SystemThemeService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [SystemThemeService.setAppIcon](https://create.roblox.com/docs/reference/engine/classes/SystemThemeService#setAppIcon) (iconName: string) -> null
* Update Class [UIDragDetector](https://create.roblox.com/docs/reference/engine/classes/UIDragDetector) [⬆️Extends: UIComponent] [🧠Memory: Instances]
  * Added Property [UIDragDetector.Selectable](https://create.roblox.com/docs/reference/engine/classes/UIDragDetector#Selectable): bool {🚧Read: UI | Write: UI} [⚡ThreadSafety: ReadSafe]
* Update Class [TestCase](https://create.roblox.com/docs/reference/engine/classes/TestCase) [⬆️Extends: Object] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Function [TestCase.Check](https://create.roblox.com/docs/reference/engine/classes/TestCase#Check) (actualValue: Variant, expectedValue: Variant, message: string = ) -> null [🏷️ CustomLuaState]
  * Changed the parameters of Function [TestCase.Require](https://create.roblox.com/docs/reference/engine/classes/TestCase#Require)
    from: (condition: bool, message: string = , source: Instance = nil, line: int = 0)
    to: (actualValue: Variant, expectedValue: Variant, message: string = )
  * Changed the capabilities of Function [TestCase.Require](https://create.roblox.com/docs/reference/engine/classes/TestCase#Require)
    from: {🚧InternalTest}
    to: {🚧None}
* Removed Class AnimatedImageTrack
* Update Enum [AssetType](https://create.roblox.com/docs/reference/engine/enums/AssetType)
  * Added EnumItem `AnimatedImage` (95)
* Added Enum [FeatureChannelEncoding](https://create.roblox.com/docs/reference/engine/enums/FeatureChannelEncoding)
  * Added EnumItem `Float32` (0)
  * Added EnumItem `Float16` (1)
* Added Enum [FeatureNormalization](https://create.roblox.com/docs/reference/engine/enums/FeatureNormalization)
  * Added EnumItem `None` (0)
  * Added EnumItem `StandardScore` (1)
  * Added EnumItem `UnitL2` (2)
* Added Enum [MetadataFieldType](https://create.roblox.com/docs/reference/engine/enums/MetadataFieldType)
  * Added EnumItem `UInt8` (0)
  * Added EnumItem `UInt16` (1)
  * Added EnumItem `UInt32` (2)
  * Added EnumItem `Float32` (3)
  * Added EnumItem `Int32` (4)
  * Added EnumItem `Int64` (5)
  * Added EnumItem `UInt64` (6)
  * Added EnumItem `Float64` (7)
  * Added EnumItem `Buffer` (8)
  * Added EnumItem `Vector3` (9)
  * Added EnumItem `CFrame` (10)
  * Added EnumItem `ContentId` (11)
  * Added EnumItem `TagMask32` (12)
  * Added EnumItem `Vector2` (13)
* Added Enum [ParticleEmitter2DEmissionMode](https://create.roblox.com/docs/reference/engine/enums/ParticleEmitter2DEmissionMode)
  * Added EnumItem `Point` (0)
  * Added EnumItem `BoundingBox` (1)
* Removed Enum ProjectServiceOperationResult
