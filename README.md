# Roblox Client Tracker

| Metadata | Details |
| :--- | :--- |
| **Version** | `0.745.0.7451137` |
| **Version Hash** | `version-7062aec9dbe74b14` |
| **Official Release Notes** | [Release Notes 745](https://create.roblox.com/docs/release-notes/release-notes-745) |

---

## Changelog

* Update Class [EditableMesh](https://create.roblox.com/docs/reference/engine/classes/EditableMesh) [⬆️Extends: Object] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Changed the parameters of Function [EditableMesh.AddFace](https://create.roblox.com/docs/reference/engine/classes/EditableMesh#AddFace)
    from: (vertexIds: Array)
    to: (vertexIds: Tuple)
* Added Class [FeatureMatchingSession](https://create.roblox.com/docs/reference/engine/classes/FeatureMatchingSession) {🔒None} [⬆️Extends: Object] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Function [FeatureMatchingSession.GetChannels](https://create.roblox.com/docs/reference/engine/classes/FeatureMatchingSession#GetChannels) {🚧InternalTest}
  * Added Function [FeatureMatchingSession.GetDimensionCount](https://create.roblox.com/docs/reference/engine/classes/FeatureMatchingSession#GetDimensionCount) {🚧InternalTest}
  * Added Function [FeatureMatchingSession.GetFeatureRow](https://create.roblox.com/docs/reference/engine/classes/FeatureMatchingSession#GetFeatureRow) {🚧InternalTest}
  * Added Function [FeatureMatchingSession.GetFeatureRows](https://create.roblox.com/docs/reference/engine/classes/FeatureMatchingSession#GetFeatureRows) {🚧InternalTest}
  * Added Function [FeatureMatchingSession.GetMetadataRow](https://create.roblox.com/docs/reference/engine/classes/FeatureMatchingSession#GetMetadataRow) {🚧InternalTest}
  * Added Function [FeatureMatchingSession.GetRowCount](https://create.roblox.com/docs/reference/engine/classes/FeatureMatchingSession#GetRowCount) {🚧InternalTest}
  * Added Function [FeatureMatchingSession.GetSchemaName](https://create.roblox.com/docs/reference/engine/classes/FeatureMatchingSession#GetSchemaName) {🚧InternalTest}
  * Added Function [FeatureMatchingSession.GetTagColumns](https://create.roblox.com/docs/reference/engine/classes/FeatureMatchingSession#GetTagColumns) {🚧InternalTest}
  * Added Function [FeatureMatchingSession.StandardizeQuery](https://create.roblox.com/docs/reference/engine/classes/FeatureMatchingSession#StandardizeQuery) {🚧InternalTest}
* Update Class [AnimatedImageService](https://create.roblox.com/docs/reference/engine/classes/AnimatedImageService) [⬆️Extends: Instance] [🧠Memory: Gui] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [AnimatedImageService.GetAnimatedImageClipsAsync](https://create.roblox.com/docs/reference/engine/classes/AnimatedImageService#GetAnimatedImageClipsAsync) (content: Content) -> Array [🏷️ Yields]
  * Added Function [AnimatedImageService.GetAnimatedImageFrameIndexAtTimeAsync](https://create.roblox.com/docs/reference/engine/classes/AnimatedImageService#GetAnimatedImageFrameIndexAtTimeAsync) (content: Content, clipName: string, timePosition: double) -> int [🏷️ Yields]
* Update Class [AnimationClipProvider](https://create.roblox.com/docs/reference/engine/classes/AnimationClipProvider) [⬆️Extends: Instance] [🧠Memory: Animation] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [AnimationClipProvider.ReloadAnimationClipAsync](https://create.roblox.com/docs/reference/engine/classes/AnimationClipProvider#ReloadAnimationClipAsync) (assetId: ContentId) -> AnimationClip [🏷️ Yields] {🚧Animation}
* Update Class [AnimationPlayer](https://create.roblox.com/docs/reference/engine/classes/AnimationPlayer) [⬆️Extends: Instance] [🧠Memory: Gui]
  * Added Event [AnimationPlayer.Ended](https://create.roblox.com/docs/reference/engine/classes/AnimationPlayer#Ended)
  * Added Event [AnimationPlayer.Stopped](https://create.roblox.com/docs/reference/engine/classes/AnimationPlayer#Stopped)
* Update Class [AssetService](https://create.roblox.com/docs/reference/engine/classes/AssetService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [AssetService.GetLatestVersionUriAsync](https://create.roblox.com/docs/reference/engine/classes/AssetService#GetLatestVersionUriAsync) (asset: Content) -> Content [🏷️ Yields] {🚧AssetRead}
* Update Class [AudioDeviceInput](https://create.roblox.com/docs/reference/engine/classes/AudioDeviceInput) [⬆️Extends: Instance] [🧠Memory: Internal]
  * Added Property [AudioDeviceInput.Streaming](https://create.roblox.com/docs/reference/engine/classes/AudioDeviceInput#Streaming): bool [🏷️ Hidden] {🚧Read: Audio, Input} [⚡ThreadSafety: ReadSafe]
* Update Class [AudioSpeechToText](https://create.roblox.com/docs/reference/engine/classes/AudioSpeechToText) [⬆️Extends: Instance] [🧠Memory: Internal]
  * Added Property [AudioSpeechToText.Streaming](https://create.roblox.com/docs/reference/engine/classes/AudioSpeechToText#Streaming): bool [🏷️ Hidden] {🚧Read: Audio} [⚡ThreadSafety: ReadSafe]
* Update Class [AvatarClothingRules](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Property [AvatarClothingRules.ClassicPantsOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#ClassicPantsOverride): int64 {🚧Read: AvatarAppearance} [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarClothingRules.ClassicShirtOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#ClassicShirtOverride): int64 {🚧Read: AvatarAppearance} [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarClothingRules.ClassicTShirtOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#ClassicTShirtOverride): int64 {🚧Read: AvatarAppearance} [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarClothingRules.LeftShoeAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#LeftShoeAccessoryOverride): int64 {🚧Read: AvatarAppearance} [⚡ThreadSafety: ReadSafe]
  * Added Property [AvatarClothingRules.RightShoeAccessoryOverride](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#RightShoeAccessoryOverride): int64 {🚧Read: AvatarAppearance} [⚡ThreadSafety: ReadSafe]
  * Removed Property AvatarClothingRules.ClassicPantsAccessoryOverride
  * Removed Property AvatarClothingRules.ClassicShirtsAccessoryOverride
  * Removed Property AvatarClothingRules.ClassicTShirtsAccessoryOverride
  * Removed Property AvatarClothingRules.LeftShoesAccessoryOverride
  * Removed Property AvatarClothingRules.RightShoesAccessoryOverride
* Update Class [AvatarCollisionRules](https://create.roblox.com/docs/reference/engine/classes/AvatarCollisionRules) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Property [AvatarCollisionRules.BodyPartsCollidableOnDeath](https://create.roblox.com/docs/reference/engine/classes/AvatarCollisionRules#BodyPartsCollidableOnDeath): bool {🚧Read: AvatarAppearance} [⚡ThreadSafety: ReadSafe]
* Update Class [CloudClientService](https://create.roblox.com/docs/reference/engine/classes/CloudClientService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Property [CloudClientService.IsCloudClient](https://create.roblox.com/docs/reference/engine/classes/CloudClientService#IsCloudClient): bool [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [CloudClientService.IsRobloxRealityEnvironment](https://create.roblox.com/docs/reference/engine/classes/CloudClientService#IsRobloxRealityEnvironment): bool [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [CloudClientService.RobloxRealityFilterEnabled](https://create.roblox.com/docs/reference/engine/classes/CloudClientService#RobloxRealityFilterEnabled): bool [⚡ThreadSafety: ReadSafe]
  * Added Property [CloudClientService.SessionTimeLimit](https://create.roblox.com/docs/reference/engine/classes/CloudClientService#SessionTimeLimit): double [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Function [CloudClientService.GetSessionElapsedTime](https://create.roblox.com/docs/reference/engine/classes/CloudClientService#GetSessionElapsedTime) () -> double
  * Added Function [CloudClientService.ReleaseReservation](https://create.roblox.com/docs/reference/engine/classes/CloudClientService#ReleaseReservation) (reservationToken: string) -> null
  * Added Function [CloudClientService.CheckEligibilityAsync](https://create.roblox.com/docs/reference/engine/classes/CloudClientService#CheckEligibilityAsync) (pool: string = ) -> bool [🏷️ Yields]
  * Added Function [CloudClientService.MakeReservationAsync](https://create.roblox.com/docs/reference/engine/classes/CloudClientService#MakeReservationAsync) (placeId: int64, pool: string = ) -> string [🏷️ Yields]
  * Added Event [CloudClientService.ReservationExpired](https://create.roblox.com/docs/reference/engine/classes/CloudClientService#ReservationExpired)
* Update Class [CollectionService](https://create.roblox.com/docs/reference/engine/classes/CollectionService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [CollectionService.GetAllCollections](https://create.roblox.com/docs/reference/engine/classes/CollectionService#GetAllCollections) () -> Array {🚧Basic}
* Added Class [FeatureMatchingService](https://create.roblox.com/docs/reference/engine/classes/FeatureMatchingService) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [FeatureMatchingService.CreateTable](https://create.roblox.com/docs/reference/engine/classes/FeatureMatchingService#CreateTable)
  * Added Function [FeatureMatchingService.Load](https://create.roblox.com/docs/reference/engine/classes/FeatureMatchingService#Load) {🚧InternalTest}
  * Added Function [FeatureMatchingService.LoadAsync](https://create.roblox.com/docs/reference/engine/classes/FeatureMatchingService#LoadAsync) [🏷️ Yields] {🚧InternalTest}
* Update Class [GeometryService](https://create.roblox.com/docs/reference/engine/classes/GeometryService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [GeometryService.BakeToMeshAsync](https://create.roblox.com/docs/reference/engine/classes/GeometryService#BakeToMeshAsync) (input: Instance, options: Dictionary = nil) -> MeshPart [🏷️ Yields] {🚧CSG}
* Added Class [IntegrityService](https://create.roblox.com/docs/reference/engine/classes/IntegrityService) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Callback [IntegrityService.EvaluatePlayerDeviceTrust](https://create.roblox.com/docs/reference/engine/classes/IntegrityService#EvaluatePlayerDeviceTrust) {🚧Consequences}
* Update Class [LinkingService](https://create.roblox.com/docs/reference/engine/classes/LinkingService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [LinkingService.RegisterLuaUrlWithPolicy](https://create.roblox.com/docs/reference/engine/classes/LinkingService#RegisterLuaUrlWithPolicy) (url: string, policy: string) -> null
* Update Class [MarketplaceService](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [MarketplaceService.PromptNativePurchaseWithContext](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptNativePurchaseWithContext) (productId: string, context: Dictionary = nil) -> null
* Update Class [Player](https://create.roblox.com/docs/reference/engine/classes/Player) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Property [Player.DeviceTrustLevel](https://create.roblox.com/docs/reference/engine/classes/Player#DeviceTrustLevel): PlayerDeviceTrustLevel [🏷️ Hidden] [🏷️ ReadOnly] [🏷️ NotReplicated] {🚧Read: Players, Consequences | Write: Consequences} [⚡ThreadSafety: ReadSafe]
  * Removed Property Player.StepIdOffset
* Update Class [Players](https://create.roblox.com/docs/reference/engine/classes/Players) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the capabilities of Property [Players.BanningEnabled](https://create.roblox.com/docs/reference/engine/classes/Players#BanningEnabled)
    from: {🚧Read: Players}
    to: {🚧Read: Players, PluginOrOpenCloud | Write: PluginOrOpenCloud}
  * Changed the capabilities of Property [Players.UseStrafingAnimations](https://create.roblox.com/docs/reference/engine/classes/Players#UseStrafingAnimations)
    from: {🚧Read: Players}
    to: {🚧Read: Players, PluginOrOpenCloud | Write: PluginOrOpenCloud}
* Update Class [RunService](https://create.roblox.com/docs/reference/engine/classes/RunService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [RunService.BindToAnimationParallel](https://create.roblox.com/docs/reference/engine/classes/RunService#BindToAnimationParallel) (function: Function, frequency: StepFrequency = Hz30, priority: int = 2000) -> RBXScriptConnection {🚧Basic}
  * Added Function [RunService.BindToSimulationParallel](https://create.roblox.com/docs/reference/engine/classes/RunService#BindToSimulationParallel) (function: Function, frequency: StepFrequency = Hz30, priority: int = 2000) -> RBXScriptConnection {🚧Basic}
* Update Class [SceneAnalysisService](https://create.roblox.com/docs/reference/engine/classes/SceneAnalysisService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [SceneAnalysisService.GetCollisionGeometryMemoryAsync](https://create.roblox.com/docs/reference/engine/classes/SceneAnalysisService#GetCollisionGeometryMemoryAsync) () -> Dictionary [🏷️ Yields]
* Update Class [ScriptEditorService](https://create.roblox.com/docs/reference/engine/classes/ScriptEditorService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the parameters of Function [ScriptEditorService.OpenTemporaryDocumentAsync](https://create.roblox.com/docs/reference/engine/classes/ScriptEditorService#OpenTemporaryDocumentAsync)
    from: (scriptId: string, initialContent: string)
    to: (scriptId: string, initialContent: string, options: Dictionary = nil)
  * Added Function [ScriptEditorService.OpenTextDocumentDocumentAsync](https://create.roblox.com/docs/reference/engine/classes/ScriptEditorService#OpenTextDocumentDocumentAsync) (textDocument: TextDocument, options: Dictionary = nil) -> Tuple [🏷️ Yields]
* Update Class [FluidForceSensor](https://create.roblox.com/docs/reference/engine/classes/FluidForceSensor) [⬆️Extends: SensorBase] [🧠Memory: Instances]
  * Added Property [FluidForceSensor.BuoyancyForce](https://create.roblox.com/docs/reference/engine/classes/FluidForceSensor#BuoyancyForce): Vector3 [🏷️ ReadOnly] [🏷️ NotReplicated] {🚧Read: Basic} [⚡ThreadSafety: ReadSafe]
  * Added Property [FluidForceSensor.BuoyancyTorque](https://create.roblox.com/docs/reference/engine/classes/FluidForceSensor#BuoyancyTorque): Vector3 [🏷️ ReadOnly] [🏷️ NotReplicated] {🚧Read: Basic} [⚡ThreadSafety: ReadSafe]
* Update Class [StarterPlayer](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Changed the security of Property [StarterPlayer.CreateDefaultPlayerModule](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#CreateDefaultPlayerModule)
    from: {🔒RobloxScriptSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [StarterPlayer.CreateDefaultPlayerModule](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer#CreateDefaultPlayerModule)
    from: {🚧Read: Players}
    to: {🚧Read: Players, PluginOrOpenCloud | Write: PluginOrOpenCloud}
* Update Class [TestService](https://create.roblox.com/docs/reference/engine/classes/TestService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ Service]
  * Changed the parameters of Function [TestService.RegisterTest](https://create.roblox.com/docs/reference/engine/classes/TestService#RegisterTest)
    from: (testName: string, options: Dictionary = nil, callback: Function = nil)
    to: (testName: string, callback: Function, options: Dictionary = nil)
* Update Class [TextDocument](https://create.roblox.com/docs/reference/engine/classes/TextDocument) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotBrowsable]
  * Changed the security of Property [TextDocument.TextContent](https://create.roblox.com/docs/reference/engine/classes/TextDocument#TextContent)
    from: {🔒PluginSecurity}
    to: {🔒None}
  * Changed the capabilities of Property [TextDocument.TextContent](https://create.roblox.com/docs/reference/engine/classes/TextDocument#TextContent)
    from: {🚧None}
    to: {🚧Read: PluginOrOpenCloud | Write: PluginOrOpenCloud}
* Update Class [VoiceChatService](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [VoiceChatService.lastVoiceChatRemoteOperations](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#lastVoiceChatRemoteOperations) () -> Dictionary {🚧Audio, Chat}
* Update Class [TestExecutionContext](https://create.roblox.com/docs/reference/engine/classes/TestExecutionContext) [⬆️Extends: Object] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Function [TestExecutionContext.Skip](https://create.roblox.com/docs/reference/engine/classes/TestExecutionContext#Skip) (reason: string = ) -> null
* Update Class [TestResult](https://create.roblox.com/docs/reference/engine/classes/TestResult) [⬆️Extends: Object] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Property [TestResult.SkipReason](https://create.roblox.com/docs/reference/engine/classes/TestResult#SkipReason): string [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
* Update Class [TestSuite](https://create.roblox.com/docs/reference/engine/classes/TestSuite) [⬆️Extends: Object] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Changed the parameters of Function [TestSuite.RegisterTest](https://create.roblox.com/docs/reference/engine/classes/TestSuite#RegisterTest)
    from: (testName: string, options: Dictionary = nil, callback: Function = nil)
    to: (testName: string, callback: Function, options: Dictionary = nil)
* Removed Class BulkImportService
* Update Enum [PartType](https://create.roblox.com/docs/reference/engine/enums/PartType)
  * Added EnumItem `Capsule` (5)
* Added Enum [PlayerDeviceTrustDecision](https://create.roblox.com/docs/reference/engine/enums/PlayerDeviceTrustDecision)
  * Added EnumItem `Accept` (0)
  * Added EnumItem `Reject` (1)
* Added Enum [PlayerDeviceTrustLevel](https://create.roblox.com/docs/reference/engine/enums/PlayerDeviceTrustLevel)
  * Added EnumItem `Pending` (0)
  * Added EnumItem `Unknown` (1)
  * Added EnumItem `None` (2)
  * Added EnumItem `Standard` (3)
  * Added EnumItem `Full` (4)
