# Roblox Client Tracker

| Metadata | Details |
| :--- | :--- |
| **Version** | `0.742.0.7421053` |
| **Version Hash** | `version-9b554450a0fc4e65` |
| **Official Release Notes** | [Release Notes 742](https://create.roblox.com/docs/release-notes/release-notes-742) |

---

## Changelog

* Update Class [DataModelDiff](https://create.roblox.com/docs/reference/engine/classes/DataModelDiff) [⬆️Extends: Object] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Added Function [DataModelDiff.GetAttributeNames](https://create.roblox.com/docs/reference/engine/classes/DataModelDiff#GetAttributeNames) (identity: ScopedInstanceIdentity) -> Array {🚧PluginOrOpenCloud}
* Update Class [AnimatedImageService](https://create.roblox.com/docs/reference/engine/classes/AnimatedImageService) [⬆️Extends: Instance] [🧠Memory: Gui] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Property [AnimatedImageService.UserCreatedTracks](https://create.roblox.com/docs/reference/engine/classes/AnimatedImageService#UserCreatedTracks): BinaryString [⚡ThreadSafety: ReadSafe]
  * Added Function [AnimatedImageService.CreateTrack](https://create.roblox.com/docs/reference/engine/classes/AnimatedImageService#CreateTrack) (sourceContent: Content, trackName: string, frameDefinitions: Array) -> AnimatedImageTrack
  * Added Function [AnimatedImageService.DestroyTrack](https://create.roblox.com/docs/reference/engine/classes/AnimatedImageService#DestroyTrack) (sourceContent: Content, trackName: string) -> null
* Added Class [AnimationPlayer](https://create.roblox.com/docs/reference/engine/classes/AnimationPlayer) {🔒None} [⬆️Extends: Instance] [🧠Memory: Gui] [🏷️ NotCreatable]
  * Added Property [AnimationPlayer.AnimationContent](https://create.roblox.com/docs/reference/engine/classes/AnimationPlayer#AnimationContent) [🏷️ Hidden] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [AnimationPlayer.AutoPlay](https://create.roblox.com/docs/reference/engine/classes/AnimationPlayer#AutoPlay) [🏷️ Hidden] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [AnimationPlayer.CurrentFrame](https://create.roblox.com/docs/reference/engine/classes/AnimationPlayer#CurrentFrame) [🏷️ Hidden] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [AnimationPlayer.Enabled](https://create.roblox.com/docs/reference/engine/classes/AnimationPlayer#Enabled) [🏷️ Hidden] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [AnimationPlayer.IsPlaying](https://create.roblox.com/docs/reference/engine/classes/AnimationPlayer#IsPlaying) [🏷️ Hidden] [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [AnimationPlayer.Loop](https://create.roblox.com/docs/reference/engine/classes/AnimationPlayer#Loop) [🏷️ Hidden] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [AnimationPlayer.Speed](https://create.roblox.com/docs/reference/engine/classes/AnimationPlayer#Speed) [🏷️ Hidden] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [AnimationPlayer.TimePosition](https://create.roblox.com/docs/reference/engine/classes/AnimationPlayer#TimePosition) [🏷️ Hidden] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [AnimationPlayer.Track](https://create.roblox.com/docs/reference/engine/classes/AnimationPlayer#Track) [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Function [AnimationPlayer.Pause](https://create.roblox.com/docs/reference/engine/classes/AnimationPlayer#Pause)
  * Added Function [AnimationPlayer.Play](https://create.roblox.com/docs/reference/engine/classes/AnimationPlayer#Play)
  * Added Function [AnimationPlayer.Stop](https://create.roblox.com/docs/reference/engine/classes/AnimationPlayer#Stop)
* Update Class [AnimationTrack](https://create.roblox.com/docs/reference/engine/classes/AnimationTrack) [⬆️Extends: Instance] [🧠Memory: Animation] [🏷️ NotCreatable]
  * Added Function [AnimationTrack.UpdateGraphNodeDefinition](https://create.roblox.com/docs/reference/engine/classes/AnimationTrack#UpdateGraphNodeDefinition) (nodeId: string, nodeDefinition: Instance) -> bool {🚧Animation}
* Update Class [AudioEmitter](https://create.roblox.com/docs/reference/engine/classes/AudioEmitter) [⬆️Extends: Instance] [🧠Memory: Internal]
  * Added Function [AudioEmitter.GetWorldCFrame](https://create.roblox.com/docs/reference/engine/classes/AudioEmitter#GetWorldCFrame) () -> CoordinateFrame? {🚧Audio}
* Update Class [AudioListener](https://create.roblox.com/docs/reference/engine/classes/AudioListener) [⬆️Extends: Instance] [🧠Memory: Internal]
  * Added Function [AudioListener.GetWorldCFrame](https://create.roblox.com/docs/reference/engine/classes/AudioListener#GetWorldCFrame) () -> CoordinateFrame? {🚧Audio}
* Update Class [AudioPlayer](https://create.roblox.com/docs/reference/engine/classes/AudioPlayer) [⬆️Extends: Instance] [🧠Memory: Internal]
  * Added Function [AudioPlayer.GetPlaybackState](https://create.roblox.com/docs/reference/engine/classes/AudioPlayer#GetPlaybackState) () -> string {🚧Audio}
* Update Class [Decal](https://create.roblox.com/docs/reference/engine/classes/Decal) [⬆️Extends: FaceInstance] [🧠Memory: GraphicsTexture]
  * Added Property [Decal.ResampleMode](https://create.roblox.com/docs/reference/engine/classes/Decal#ResampleMode): ResamplerMode {🚧Read: Basic} [⚡ThreadSafety: ReadSafe]
* Added Class [FriendsCallingService](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingService) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [FriendsCallingService.EndCall](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingService#EndCall)
  * Added Function [FriendsCallingService.SetMuted](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingService#SetMuted)
  * Added Function [FriendsCallingService.SetVolume](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingService#SetVolume)
  * Added Function [FriendsCallingService.StartCall](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingService#StartCall)
* Added Class [HiddenPlayerService](https://create.roblox.com/docs/reference/engine/classes/HiddenPlayerService) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
* Update Class [HumanoidRigDescription](https://create.roblox.com/docs/reference/engine/classes/HumanoidRigDescription) [⬆️Extends: Instance] [🧠Memory: Animation]
  * Changed the security of Property [HumanoidRigDescription.OriginOffset](https://create.roblox.com/docs/reference/engine/classes/HumanoidRigDescription#OriginOffset)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [HumanoidRigDescription.OriginOffset](https://create.roblox.com/docs/reference/engine/classes/HumanoidRigDescription#OriginOffset)
    from: {🚧Read: Animation}
    to: {🚧Read: Animation, PluginOrOpenCloud | Write: PluginOrOpenCloud}
* Added Class [InstanceRegistryService](https://create.roblox.com/docs/reference/engine/classes/InstanceRegistryService) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [InstanceRegistryService.GetIdentity](https://create.roblox.com/docs/reference/engine/classes/InstanceRegistryService#GetIdentity)
* Update Class [MarketplaceService](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [MarketplaceService.PromptVIPServerPurchase](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptVIPServerPurchase) (player: Player) -> null {🚧PromptExternalPurchase}
  * Added Function [MarketplaceService.CanUsersTransferRobuxAsync](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#CanUsersTransferRobuxAsync) (sender: Player, receiverUser: User) -> RobuxTransferEligibility [🏷️ Yields] {🚧PromptExternalPurchase}
  * Changed the parameters of Function [MarketplaceService.PerformSubscriptionPurchaseV3Async](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PerformSubscriptionPurchaseV3Async)
    from: (productType: string, productId: string, paymentProvider: string, paymentSessionId: string)
    to: (productType: string, productId: string, paymentProvider: string, paymentSessionId: string, referrerId: int64?)
  * Added Event [MarketplaceService.PromptVIPServerPurchaseRequested](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptVIPServerPurchaseRequested)
* Update Class [ModerationService](https://create.roblox.com/docs/reference/engine/classes/ModerationService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [ModerationService.BindViolationProcessor](https://create.roblox.com/docs/reference/engine/classes/ModerationService#BindViolationProcessor) (priority: int, callback: Function) -> RBXScriptConnection {🚧Consequences}
  * Added Function [ModerationService.MockViolationCallbackAsync](https://create.roblox.com/docs/reference/engine/classes/ModerationService#MockViolationCallbackAsync) (report: Dictionary) -> null {🚧Consequences}
* Update Class [MeshPart](https://create.roblox.com/docs/reference/engine/classes/MeshPart) [⬆️Extends: TriangleMeshPart] [🧠Memory: BaseParts]
  * Changed the security of Property [MeshPart.RenderFidelity](https://create.roblox.com/docs/reference/engine/classes/MeshPart#RenderFidelity)
    from: {🔒Read:None, Write:PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [MeshPart.RenderFidelity](https://create.roblox.com/docs/reference/engine/classes/MeshPart#RenderFidelity)
    from: {🚧Read: Basic}
    to: {🚧Read: Basic | Write: PluginOrOpenCloud}
  * Added Function [MeshPart.GetSurfaceSlotsAsync](https://create.roblox.com/docs/reference/engine/classes/MeshPart#GetSurfaceSlotsAsync) () -> Array [🏷️ Yields] {🚧Basic}
* Update Class [Camera](https://create.roblox.com/docs/reference/engine/classes/Camera) [⬆️Extends: PVInstance] [🧠Memory: Instances] [🏷️ NotReplicated]
  * Added Property [Camera.OrthographicMode](https://create.roblox.com/docs/reference/engine/classes/Camera#OrthographicMode): OrthographicMode {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Property [Camera.OrthographicSize](https://create.roblox.com/docs/reference/engine/classes/Camera#OrthographicSize): float {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Property [Camera.ProjectionType](https://create.roblox.com/docs/reference/engine/classes/Camera#ProjectionType): ProjectionType {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Property [Camera.ViewStretch](https://create.roblox.com/docs/reference/engine/classes/Camera#ViewStretch): float {🚧Read: Basic | Write: Basic} [⚡ThreadSafety: ReadSafe]
* Update Class [Model](https://create.roblox.com/docs/reference/engine/classes/Model) [⬆️Extends: PVInstance] [🧠Memory: BaseParts]
  * Changed the security of Property [Model.LevelOfDetail](https://create.roblox.com/docs/reference/engine/classes/Model#LevelOfDetail)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [Model.LevelOfDetail](https://create.roblox.com/docs/reference/engine/classes/Model#LevelOfDetail)
    from: {🚧None}
    to: {🚧Read: PluginOrOpenCloud | Write: PluginOrOpenCloud}
* Update Class [Workspace](https://create.roblox.com/docs/reference/engine/classes/Workspace) [⬆️Extends: WorldRoot] [🧠Memory: BaseParts] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the security of Property [Workspace.FallHeightEnabled](https://create.roblox.com/docs/reference/engine/classes/Workspace#FallHeightEnabled)
    from: {🔒Read:None, Write:PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [Workspace.FallHeightEnabled](https://create.roblox.com/docs/reference/engine/classes/Workspace#FallHeightEnabled)
    from: {🚧Read: Basic}
    to: {🚧Read: Basic | Write: PluginOrOpenCloud}
  * Changed the security of Property [Workspace.FallenPartsDestroyHeight](https://create.roblox.com/docs/reference/engine/classes/Workspace#FallenPartsDestroyHeight)
    from: {🔒Read:None, Write:PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [Workspace.FallenPartsDestroyHeight](https://create.roblox.com/docs/reference/engine/classes/Workspace#FallenPartsDestroyHeight)
    from: {🚧Read: Basic}
    to: {🚧Read: Basic | Write: PluginOrOpenCloud}
  * Changed the security of Property [Workspace.LuauTypeCheckMode](https://create.roblox.com/docs/reference/engine/classes/Workspace#LuauTypeCheckMode)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [Workspace.LuauTypeCheckMode](https://create.roblox.com/docs/reference/engine/classes/Workspace#LuauTypeCheckMode)
    from: {🚧None}
    to: {🚧Read: PluginOrOpenCloud | Write: PluginOrOpenCloud}
  * Added Property [Workspace.ReplicationFrequency](https://create.roblox.com/docs/reference/engine/classes/Workspace#ReplicationFrequency): ReplicationMode {🚧Read: PluginOrOpenCloud | Write: PluginOrOpenCloud} [⚡ThreadSafety: ReadSafe]
  * Added Property [Workspace.ReplicationThroughput](https://create.roblox.com/docs/reference/engine/classes/Workspace#ReplicationThroughput): ReplicationMode {🚧Read: PluginOrOpenCloud | Write: PluginOrOpenCloud} [⚡ThreadSafety: ReadSafe]
  * Changed the security of Property [Workspace.StreamingEnabled](https://create.roblox.com/docs/reference/engine/classes/Workspace#StreamingEnabled)
    from: {🔒Read:None, Write:PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [Workspace.StreamingEnabled](https://create.roblox.com/docs/reference/engine/classes/Workspace#StreamingEnabled)
    from: {🚧None}
    to: {🚧Write: PluginOrOpenCloud}
* Update Class [PackageLink](https://create.roblox.com/docs/reference/engine/classes/PackageLink) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotBrowsable]
  * Removed Function PackageLink.getOverrides
* Update Class [PackageService](https://create.roblox.com/docs/reference/engine/classes/PackageService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [PackageService.RevertAttributeOverridesAsync](https://create.roblox.com/docs/reference/engine/classes/PackageService#RevertAttributeOverridesAsync) (scopeRoot: Instance, identities: Array, attributeNames: Array) -> null [🏷️ Yields]
  * Added Function [PackageService.RevertInstanceOverridesAsync](https://create.roblox.com/docs/reference/engine/classes/PackageService#RevertInstanceOverridesAsync) (scopeRoot: Instance, identities: Array) -> null [🏷️ Yields]
  * Added Function [PackageService.RevertPropertyOverridesAsync](https://create.roblox.com/docs/reference/engine/classes/PackageService#RevertPropertyOverridesAsync) (scopeRoot: Instance, identities: Array, propertyNames: Array) -> null [🏷️ Yields]
* Update Class [PopLatencyService](https://create.roblox.com/docs/reference/engine/classes/PopLatencyService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [PopLatencyService.GetForcedPop](https://create.roblox.com/docs/reference/engine/classes/PopLatencyService#GetForcedPop) () -> string
  * Added Function [PopLatencyService.SetForcedPop](https://create.roblox.com/docs/reference/engine/classes/PopLatencyService#SetForcedPop) (popCode: string) -> null
* Update Class [Sound](https://create.roblox.com/docs/reference/engine/classes/Sound) [⬆️Extends: Instance] [🧠Memory: Internal]
  * Added Function [Sound.GetPlaybackState](https://create.roblox.com/docs/reference/engine/classes/Sound#GetPlaybackState) () -> string {🚧LegacySound}
  * Added Function [Sound.GetWorldCFrame](https://create.roblox.com/docs/reference/engine/classes/Sound#GetWorldCFrame) () -> CoordinateFrame? {🚧LegacySound}
* Update Class [SoundService](https://create.roblox.com/docs/reference/engine/classes/SoundService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [SoundService.GetListenerWorldCFrame](https://create.roblox.com/docs/reference/engine/classes/SoundService#GetListenerWorldCFrame) () -> CoordinateFrame? {🚧Audio}
* Update Class [Stats](https://create.roblox.com/docs/reference/engine/classes/Stats) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [Stats.GetMemoryUsageMbAllCategoriesFiltered](https://create.roblox.com/docs/reference/engine/classes/Stats#GetMemoryUsageMbAllCategoriesFiltered) (dmId: int, vmClass: int) -> Array {🚧InternalTest}
  * Added Function [Stats.GetMemoryUsageMbFiltered](https://create.roblox.com/docs/reference/engine/classes/Stats#GetMemoryUsageMbFiltered) (dmId: int, vmClass: int) -> float {🚧InternalTest}
* Update Class [SurfaceAppearance](https://create.roblox.com/docs/reference/engine/classes/SurfaceAppearance) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Property [SurfaceAppearance.SurfaceSlot](https://create.roblox.com/docs/reference/engine/classes/SurfaceAppearance#SurfaceSlot): int {🚧Read: Basic} [⚡ThreadSafety: ReadSafe]
* Update Class [TeleportService](https://create.roblox.com/docs/reference/engine/classes/TeleportService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the parameters of Function [TeleportService.TeleportSwitchServer](https://create.roblox.com/docs/reference/engine/classes/TeleportService#TeleportSwitchServer)
    from: ()
    to: (gameIdsToExclude: Array = {})
* Update Class [TestService](https://create.roblox.com/docs/reference/engine/classes/TestService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ Service]
  * Added Function [TestService.ListTests](https://create.roblox.com/docs/reference/engine/classes/TestService#ListTests) () -> Array
  * Added Function [TestService.RegisterSuite](https://create.roblox.com/docs/reference/engine/classes/TestService#RegisterSuite) (suiteName: string, options: Dictionary = nil) -> TestSuite
  * Changed the parameters of Function [TestService.RegisterTest](https://create.roblox.com/docs/reference/engine/classes/TestService#RegisterTest)
    from: (testOptions: Dictionary)
    to: (testName: string, options: Dictionary = nil, callback: Function = nil)
  * Changed the capabilities of Function [TestService.RegisterTest](https://create.roblox.com/docs/reference/engine/classes/TestService#RegisterTest)
    from: {🚧InternalTest}
    to: {🚧None}
  * Added Function [TestService.ResetTestRegistry](https://create.roblox.com/docs/reference/engine/classes/TestService#ResetTestRegistry) () -> null
  * Added Function [TestService.RunTestsAsync](https://create.roblox.com/docs/reference/engine/classes/TestService#RunTestsAsync) (filter: Dictionary = nil) -> TestRunResult [🏷️ Yields]
  * Added Function [TestService.StartAudioCaptureAsync](https://create.roblox.com/docs/reference/engine/classes/TestService#StartAudioCaptureAsync) (artifactName: string = , options: Dictionary = nil) -> Tuple [🏷️ Yields] {🚧InternalTest}
  * Added Function [TestService.StopAudioCaptureAsync](https://create.roblox.com/docs/reference/engine/classes/TestService#StopAudioCaptureAsync) () -> Tuple [🏷️ Yields] {🚧InternalTest}
  * Added Event [TestService.TestRegistryChanged](https://create.roblox.com/docs/reference/engine/classes/TestService#TestRegistryChanged)
* Added Class [UIBlur](https://create.roblox.com/docs/reference/engine/classes/UIBlur) {🔒None} [⬆️Extends: UIComponent] [🧠Memory: Gui]
  * Added Property [UIBlur.Color](https://create.roblox.com/docs/reference/engine/classes/UIBlur#Color) {🚧Read: UI} [⚡ThreadSafety: ReadSafe]
  * Added Property [UIBlur.Enabled](https://create.roblox.com/docs/reference/engine/classes/UIBlur#Enabled) {🚧Read: UI} [⚡ThreadSafety: ReadSafe]
  * Added Property [UIBlur.Strength](https://create.roblox.com/docs/reference/engine/classes/UIBlur#Strength) {🚧Read: UI} [⚡ThreadSafety: ReadSafe]
  * Added Property [UIBlur.Transparency](https://create.roblox.com/docs/reference/engine/classes/UIBlur#Transparency) {🚧Read: UI} [⚡ThreadSafety: ReadSafe]
* Update Class [VRService](https://create.roblox.com/docs/reference/engine/classes/VRService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Property [VRService.PresentationMode](https://create.roblox.com/docs/reference/engine/classes/VRService#PresentationMode): VRPresentationMode [🏷️ Hidden] [🏷️ ReadOnly] [🏷️ NotReplicated] {🚧Read: Input} [⚡ThreadSafety: ReadSafe]
* Update Class [TestCase](https://create.roblox.com/docs/reference/engine/classes/TestCase) [⬆️Extends: Object] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed Superclass of Class [TestCase](https://create.roblox.com/docs/reference/engine/classes/TestCase) from `Instance` to `Object`
  * Added Property [TestCase.SuiteName](https://create.roblox.com/docs/reference/engine/classes/TestCase#SuiteName): string [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [TestCase.TestId](https://create.roblox.com/docs/reference/engine/classes/TestCase#TestId): string [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [TestCase.TestName](https://create.roblox.com/docs/reference/engine/classes/TestCase#TestName): string [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [TestCase.TimeoutSec](https://create.roblox.com/docs/reference/engine/classes/TestCase#TimeoutSec): double [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Function [TestCase.GetTestTags](https://create.roblox.com/docs/reference/engine/classes/TestCase#GetTestTags) () -> Array
* Added Class [TestExecutionContext](https://create.roblox.com/docs/reference/engine/classes/TestExecutionContext) {🔒None} [⬆️Extends: Object] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
* Added Class [TestFailure](https://create.roblox.com/docs/reference/engine/classes/TestFailure) {🔒None} [⬆️Extends: Object] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Property [TestFailure.Line](https://create.roblox.com/docs/reference/engine/classes/TestFailure#Line) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [TestFailure.Matcher](https://create.roblox.com/docs/reference/engine/classes/TestFailure#Matcher) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [TestFailure.Message](https://create.roblox.com/docs/reference/engine/classes/TestFailure#Message) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [TestFailure.StackTrace](https://create.roblox.com/docs/reference/engine/classes/TestFailure#StackTrace) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Function [TestFailure.GetActual](https://create.roblox.com/docs/reference/engine/classes/TestFailure#GetActual)
  * Added Function [TestFailure.GetContext](https://create.roblox.com/docs/reference/engine/classes/TestFailure#GetContext)
  * Added Function [TestFailure.GetExpected](https://create.roblox.com/docs/reference/engine/classes/TestFailure#GetExpected)
  * Added Function [TestFailure.GetSource](https://create.roblox.com/docs/reference/engine/classes/TestFailure#GetSource)
* Added Class [TestResult](https://create.roblox.com/docs/reference/engine/classes/TestResult) {🔒None} [⬆️Extends: Object] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Property [TestResult.Duration](https://create.roblox.com/docs/reference/engine/classes/TestResult#Duration) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [TestResult.FailedChecks](https://create.roblox.com/docs/reference/engine/classes/TestResult#FailedChecks) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [TestResult.PassedChecks](https://create.roblox.com/docs/reference/engine/classes/TestResult#PassedChecks) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [TestResult.Status](https://create.roblox.com/docs/reference/engine/classes/TestResult#Status) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [TestResult.SuiteName](https://create.roblox.com/docs/reference/engine/classes/TestResult#SuiteName) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [TestResult.TestId](https://create.roblox.com/docs/reference/engine/classes/TestResult#TestId) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [TestResult.TestName](https://create.roblox.com/docs/reference/engine/classes/TestResult#TestName) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [TestResult.UncaughtError](https://create.roblox.com/docs/reference/engine/classes/TestResult#UncaughtError) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Function [TestResult.GetFailures](https://create.roblox.com/docs/reference/engine/classes/TestResult#GetFailures)
  * Added Function [TestResult.GetTestTags](https://create.roblox.com/docs/reference/engine/classes/TestResult#GetTestTags)
* Added Class [TestRunResult](https://create.roblox.com/docs/reference/engine/classes/TestRunResult) {🔒None} [⬆️Extends: Object] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Property [TestRunResult.Duration](https://create.roblox.com/docs/reference/engine/classes/TestRunResult#Duration) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [TestRunResult.Failed](https://create.roblox.com/docs/reference/engine/classes/TestRunResult#Failed) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [TestRunResult.Passed](https://create.roblox.com/docs/reference/engine/classes/TestRunResult#Passed) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [TestRunResult.Skipped](https://create.roblox.com/docs/reference/engine/classes/TestRunResult#Skipped) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [TestRunResult.Status](https://create.roblox.com/docs/reference/engine/classes/TestRunResult#Status) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [TestRunResult.Summary](https://create.roblox.com/docs/reference/engine/classes/TestRunResult#Summary) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [TestRunResult.Total](https://create.roblox.com/docs/reference/engine/classes/TestRunResult#Total) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Function [TestRunResult.GetTests](https://create.roblox.com/docs/reference/engine/classes/TestRunResult#GetTests)
* Added Class [TestSuite](https://create.roblox.com/docs/reference/engine/classes/TestSuite) {🔒None} [⬆️Extends: Object] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Property [TestSuite.SuiteName](https://create.roblox.com/docs/reference/engine/classes/TestSuite#SuiteName) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [TestSuite.TimeoutSec](https://create.roblox.com/docs/reference/engine/classes/TestSuite#TimeoutSec) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Function [TestSuite.GetTestTags](https://create.roblox.com/docs/reference/engine/classes/TestSuite#GetTestTags)
  * Added Function [TestSuite.RegisterTest](https://create.roblox.com/docs/reference/engine/classes/TestSuite#RegisterTest)
* Removed Class AnimatedImage
* Added Enum [OrthographicMode](https://create.roblox.com/docs/reference/engine/enums/OrthographicMode)
  * Added EnumItem `Vertical` (0)
  * Added EnumItem `Horizontal` (1)
  * Added EnumItem `Diagonal` (2)
  * Added EnumItem `MaxAxis` (3)
* Update Enum [PioneerSource](https://create.roblox.com/docs/reference/engine/enums/PioneerSource)
  * Added EnumItem `RobloxPioneerTest` (3)
* Added Enum [ProjectionType](https://create.roblox.com/docs/reference/engine/enums/ProjectionType)
  * Added EnumItem `Perspective` (0)
  * Added EnumItem `Orthographic` (1)
* Added Enum [ReplicationMode](https://create.roblox.com/docs/reference/engine/enums/ReplicationMode)
  * Added EnumItem `Automatic` (0)
  * Added EnumItem `Low` (1)
  * Added EnumItem `Medium` (2)
  * Added EnumItem `High` (3)
* Added Enum [RobuxTransferEligibility](https://create.roblox.com/docs/reference/engine/enums/RobuxTransferEligibility)
  * Added EnumItem `Unknown` (0)
  * Added EnumItem `Eligible` (1)
  * Added EnumItem `SenderNotEligible` (2)
  * Added EnumItem `ReceiverNotEligible` (3)
* Added Enum [TestCaseStatus](https://create.roblox.com/docs/reference/engine/enums/TestCaseStatus)
  * Added EnumItem `Pass` (0)
  * Added EnumItem `Fail` (1)
  * Added EnumItem `TimedOut` (2)
  * Added EnumItem `Skipped` (3)
* Added Enum [TestRunStatus](https://create.roblox.com/docs/reference/engine/enums/TestRunStatus)
  * Added EnumItem `Pass` (0)
  * Added EnumItem `Fail` (1)
  * Added EnumItem `NoTests` (2)
  * Added EnumItem `Skipped` (3)
* Added Enum [UIBlurStrength](https://create.roblox.com/docs/reference/engine/enums/UIBlurStrength)
  * Added EnumItem `Light` (0)
  * Added EnumItem `Medium` (1)
  * Added EnumItem `Heavy` (2)
* Added Enum [VRPresentationMode](https://create.roblox.com/docs/reference/engine/enums/VRPresentationMode)
  * Added EnumItem `Stereo` (0)
  * Added EnumItem `Flat` (1)
* Removed Enum AnimatedImagePlaybackState
