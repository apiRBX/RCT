# Roblox Client Tracker

| Metadata | Details |
| :--- | :--- |
| **Version** | `0.741.19.7411056` |
| **Version Hash** | `version-76e1a02649ad4f35` |
| **Official Release Notes** | [Release Notes 741](https://create.roblox.com/docs/release-notes/release-notes-741) |

---

## Changelog

* Update Class [AnimationClipProvider](https://create.roblox.com/docs/reference/engine/classes/AnimationClipProvider) [⬆️Extends: Instance] [🧠Memory: Animation] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [AnimationClipProvider.GetAnimationValueNodeDefinition](https://create.roblox.com/docs/reference/engine/classes/AnimationClipProvider#GetAnimationValueNodeDefinition) (type: AnimationValueNodeType) -> Dictionary {🚧Animation}
  * Added Function [AnimationClipProvider.GetAnimationValueNodeTypes](https://create.roblox.com/docs/reference/engine/classes/AnimationClipProvider#GetAnimationValueNodeTypes) () -> Array {🚧Animation}
* Update Class [AssetImportService](https://create.roblox.com/docs/reference/engine/classes/AssetImportService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Changed the parameters of Function [AssetImportService.UploadAssetFromPathAsync](https://create.roblox.com/docs/reference/engine/classes/AssetImportService#UploadAssetFromPathAsync)
    from: (filepath: string, createAssetRequest: Dictionary)
    to: (filepath: string, createAssetRequest: Dictionary, progressCallback: Function? = nil)
* Update Class [AssetService](https://create.roblox.com/docs/reference/engine/classes/AssetService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [AssetService.CreateTextContentAsync](https://create.roblox.com/docs/reference/engine/classes/AssetService#CreateTextContentAsync) (text: string) -> Content [🏷️ Yields]
  * Added Function [AssetService.ReadTextContentAsync](https://create.roblox.com/docs/reference/engine/classes/AssetService#ReadTextContentAsync) (content: Content) -> string [🏷️ Yields]
* Update Class [AudioSpeechToText](https://create.roblox.com/docs/reference/engine/classes/AudioSpeechToText) [⬆️Extends: Instance] [🧠Memory: Internal]
  * Added Property [AudioSpeechToText.Locale](https://create.roblox.com/docs/reference/engine/classes/AudioSpeechToText#Locale): string [🏷️ Hidden] {🚧Read: Audio} [⚡ThreadSafety: ReadSafe]
* Update Class [AvatarClothingRules](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Function [AvatarClothingRules.WillLimitLayeredAccessoryAsync](https://create.roblox.com/docs/reference/engine/classes/AvatarClothingRules#WillLimitLayeredAccessoryAsync) (humanoid: Humanoid, accessory: Accoutrement) -> bool [🏷️ Yields]
* Added Class [BackendReplicatedStorage](https://create.roblox.com/docs/reference/engine/classes/BackendReplicatedStorage) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
* Added Class [BackendServerScriptService](https://create.roblox.com/docs/reference/engine/classes/BackendServerScriptService) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
* Added Class [BackendServerStorage](https://create.roblox.com/docs/reference/engine/classes/BackendServerStorage) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
* Update Class [ExperienceService](https://create.roblox.com/docs/reference/engine/classes/ExperienceService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [ExperienceService.ConsumePendingExperienceLeaveWithReason](https://create.roblox.com/docs/reference/engine/classes/ExperienceService#ConsumePendingExperienceLeaveWithReason) () -> Dictionary
  * Added Function [ExperienceService.LeaveExperienceWithReason](https://create.roblox.com/docs/reference/engine/classes/ExperienceService#LeaveExperienceWithReason) (reason: string) -> null
* Update Class [Decal](https://create.roblox.com/docs/reference/engine/classes/Decal) [⬆️Extends: FaceInstance] [🧠Memory: GraphicsTexture]
  * Changed the security of Property [Decal.LocalizedTextureContent](https://create.roblox.com/docs/reference/engine/classes/Decal#LocalizedTextureContent)
    from: {🔒RobloxScriptSecurity}
    to: {🔒Read:RobloxScriptSecurity, Write:NotAccessibleSecurity}
* Added Class [FriendsCallingInstance](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingInstance) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Property [FriendsCallingInstance.CallId](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingInstance#CallId) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [FriendsCallingInstance.ConversationId](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingInstance#ConversationId) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [FriendsCallingInstance.EndReason](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingInstance#EndReason) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [FriendsCallingInstance.InitiatorUserId](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingInstance#InitiatorUserId) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [FriendsCallingInstance.IsDeafened](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingInstance#IsDeafened) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [FriendsCallingInstance.Phase](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingInstance#Phase) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [FriendsCallingInstance.Volume](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingInstance#Volume) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
* Added Class [FriendsCallingParticipant](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingParticipant) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ NotReplicated]
  * Added Property [FriendsCallingParticipant.Error](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingParticipant#Error) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [FriendsCallingParticipant.IsLocalMuted](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingParticipant#IsLocalMuted) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [FriendsCallingParticipant.IsSpeaking](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingParticipant#IsSpeaking) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [FriendsCallingParticipant.LeaveReason](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingParticipant#LeaveReason) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [FriendsCallingParticipant.Status](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingParticipant#Status) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [FriendsCallingParticipant.UserId](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingParticipant#UserId) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
  * Added Property [FriendsCallingParticipant.Volume](https://create.roblox.com/docs/reference/engine/classes/FriendsCallingParticipant#Volume) [🏷️ ReadOnly] [🏷️ NotReplicated] [⚡ThreadSafety: ReadSafe]
* Update Class [ImageButton](https://create.roblox.com/docs/reference/engine/classes/ImageButton) [⬆️Extends: GuiButton] [🧠Memory: Gui]
  * Changed the security of Property [ImageButton.LocalizedImageContent](https://create.roblox.com/docs/reference/engine/classes/ImageButton#LocalizedImageContent)
    from: {🔒RobloxScriptSecurity}
    to: {🔒Read:RobloxScriptSecurity, Write:NotAccessibleSecurity}
  * Changed the serialization of Property [ImageButton.LocalizedImageContent](https://create.roblox.com/docs/reference/engine/classes/ImageButton#LocalizedImageContent)
    from: [🚫None]
    to: [📁LoadOnly]
* Update Class [ImageLabel](https://create.roblox.com/docs/reference/engine/classes/ImageLabel) [⬆️Extends: GuiLabel] [🧠Memory: Gui]
  * Changed the security of Property [ImageLabel.LocalizedImageContent](https://create.roblox.com/docs/reference/engine/classes/ImageLabel#LocalizedImageContent)
    from: {🔒RobloxScriptSecurity}
    to: {🔒Read:RobloxScriptSecurity, Write:NotAccessibleSecurity}
  * Changed the serialization of Property [ImageLabel.LocalizedImageContent](https://create.roblox.com/docs/reference/engine/classes/ImageLabel#LocalizedImageContent)
    from: [🚫None]
    to: [📁LoadOnly]
* Update Class [HeightmapImporterService](https://create.roblox.com/docs/reference/engine/classes/HeightmapImporterService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [HeightmapImporterService.ImportHeightmapWithMaterialSlotsAsync](https://create.roblox.com/docs/reference/engine/classes/HeightmapImporterService#ImportHeightmapWithMaterialSlotsAsync) (region: Region3, heightmapAssetId: ContentId, colormapAssetId: ContentId, defaultMaterialIndex: int) -> null [🏷️ Yields]
* Update Class [MarketplaceService](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Event [MarketplaceService.PromptBulkPurchaseRequestedV3](https://create.roblox.com/docs/reference/engine/classes/MarketplaceService#PromptBulkPurchaseRequestedV3)
* Update Class [NotificationService](https://create.roblox.com/docs/reference/engine/classes/NotificationService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [NotificationService.SubscribeToTopic](https://create.roblox.com/docs/reference/engine/classes/NotificationService#SubscribeToTopic) (token: string, replaceToken: string = ) -> null {🚧Players}
  * Added Function [NotificationService.UnsubscribeFromTopic](https://create.roblox.com/docs/reference/engine/classes/NotificationService#UnsubscribeFromTopic) (token: string) -> null {🚧Players}
  * Added Event [NotificationService.TopicNotificationReceived](https://create.roblox.com/docs/reference/engine/classes/NotificationService#TopicNotificationReceived) {🚧Players}
* Update Class [Terrain](https://create.roblox.com/docs/reference/engine/classes/Terrain) [⬆️Extends: BasePart] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Added Function [Terrain.IsMaterialSlotInvalid](https://create.roblox.com/docs/reference/engine/classes/Terrain#IsMaterialSlotInvalid) (slotIndex: int) -> bool {🚧Environment}
* Update Class [Player](https://create.roblox.com/docs/reference/engine/classes/Player) [⬆️Extends: Instance] [🧠Memory: Instances]
  * Added Function [Player.GetFriendsInServerAsync](https://create.roblox.com/docs/reference/engine/classes/Player#GetFriendsInServerAsync) () -> Array [🏷️ Yields] {🚧Players, Social}
* Added Class [ProjectService](https://create.roblox.com/docs/reference/engine/classes/ProjectService) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [ProjectService.CreateFolder](https://create.roblox.com/docs/reference/engine/classes/ProjectService#CreateFolder)
  * Added Function [ProjectService.Exists](https://create.roblox.com/docs/reference/engine/classes/ProjectService#Exists)
  * Added Function [ProjectService.GetContentMapMemoryBytes](https://create.roblox.com/docs/reference/engine/classes/ProjectService#GetContentMapMemoryBytes)
  * Added Function [ProjectService.GetOrphanPathSubscribers](https://create.roblox.com/docs/reference/engine/classes/ProjectService#GetOrphanPathSubscribers)
  * Added Function [ProjectService.GetPathSubscribers](https://create.roblox.com/docs/reference/engine/classes/ProjectService#GetPathSubscribers)
  * Added Function [ProjectService.GetPaths](https://create.roblox.com/docs/reference/engine/classes/ProjectService#GetPaths)
  * Added Function [ProjectService.Move](https://create.roblox.com/docs/reference/engine/classes/ProjectService#Move)
  * Added Function [ProjectService.RemovePath](https://create.roblox.com/docs/reference/engine/classes/ProjectService#RemovePath)
  * Added Function [ProjectService.RemovePathSubscribers](https://create.roblox.com/docs/reference/engine/classes/ProjectService#RemovePathSubscribers)
  * Added Function [ProjectService.ResolveContent](https://create.roblox.com/docs/reference/engine/classes/ProjectService#ResolveContent)
  * Added Function [ProjectService.SetContent](https://create.roblox.com/docs/reference/engine/classes/ProjectService#SetContent)
  * Added Function [ProjectService.GetMetaDataAsync](https://create.roblox.com/docs/reference/engine/classes/ProjectService#GetMetaDataAsync) [🏷️ Yields]
  * Added Event [ProjectService.EffectivePathsChanged](https://create.roblox.com/docs/reference/engine/classes/ProjectService#EffectivePathsChanged)
  * Added Event [ProjectService.PathAdded](https://create.roblox.com/docs/reference/engine/classes/ProjectService#PathAdded)
  * Added Event [ProjectService.PathChanged](https://create.roblox.com/docs/reference/engine/classes/ProjectService#PathChanged)
  * Added Event [ProjectService.PathMoved](https://create.roblox.com/docs/reference/engine/classes/ProjectService#PathMoved)
  * Added Event [ProjectService.PathRemoved](https://create.roblox.com/docs/reference/engine/classes/ProjectService#PathRemoved)
* Update Class [RunService](https://create.roblox.com/docs/reference/engine/classes/RunService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [RunService.GetRobloxClientIxpEnrolledExperiments](https://create.roblox.com/docs/reference/engine/classes/RunService#GetRobloxClientIxpEnrolledExperiments) () -> string {🚧Basic}
* Update Class [ScriptEditorService](https://create.roblox.com/docs/reference/engine/classes/ScriptEditorService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [ScriptEditorService.OpenStringValueDocumentAsync](https://create.roblox.com/docs/reference/engine/classes/ScriptEditorService#OpenStringValueDocumentAsync) (stringValue: StringValue, options: Dictionary = nil) -> Tuple [🏷️ Yields]
* Update Class [StarterPlayer](https://create.roblox.com/docs/reference/engine/classes/StarterPlayer) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Removed Property StarterPlayer.GameSettingsAssetIDFace
  * Removed Property StarterPlayer.GameSettingsAssetIDHead
  * Removed Property StarterPlayer.GameSettingsAssetIDLeftArm
  * Removed Property StarterPlayer.GameSettingsAssetIDLeftLeg
  * Removed Property StarterPlayer.GameSettingsAssetIDPants
  * Removed Property StarterPlayer.GameSettingsAssetIDRightArm
  * Removed Property StarterPlayer.GameSettingsAssetIDRightLeg
  * Removed Property StarterPlayer.GameSettingsAssetIDShirt
  * Removed Property StarterPlayer.GameSettingsAssetIDTeeShirt
  * Removed Property StarterPlayer.GameSettingsAssetIDTorso
  * Removed Property StarterPlayer.GameSettingsScaleRangeBodyType
  * Removed Property StarterPlayer.GameSettingsScaleRangeHead
  * Removed Property StarterPlayer.GameSettingsScaleRangeHeight
  * Removed Property StarterPlayer.GameSettingsScaleRangeProportion
  * Removed Property StarterPlayer.GameSettingsScaleRangeWidth
* Update Class [StudioAssetService](https://create.roblox.com/docs/reference/engine/classes/StudioAssetService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [StudioAssetService.UploadAndInsertAssetForJobAsync](https://create.roblox.com/docs/reference/engine/classes/StudioAssetService#UploadAndInsertAssetForJobAsync) (jobId: string) -> Instance [🏷️ Yields]
* Update Class [StudioCaptureService](https://create.roblox.com/docs/reference/engine/classes/StudioCaptureService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service] [🏷️ NotReplicated]
  * Added Function [StudioCaptureService.CapturePluginGuiByPluginGuiIdAsync](https://create.roblox.com/docs/reference/engine/classes/StudioCaptureService#CapturePluginGuiByPluginGuiIdAsync) (pluginGuiId: string) -> StudioScreenshotCapture [🏷️ Yields]
* Update Class [TestService](https://create.roblox.com/docs/reference/engine/classes/TestService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ Service]
  * Added Property [TestService.Enabled](https://create.roblox.com/docs/reference/engine/classes/TestService#Enabled): bool [🏷️ ReadOnly] [🏷️ NotReplicated]
* Update Class [TextChatMessage](https://create.roblox.com/docs/reference/engine/classes/TextChatMessage) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable]
  * Added Property [TextChatMessage.IsHistorical](https://create.roblox.com/docs/reference/engine/classes/TextChatMessage#IsHistorical): bool [🏷️ Hidden] {🚧Read: Chat} [⚡ThreadSafety: ReadSafe]
* Added Class [TextDocument](https://create.roblox.com/docs/reference/engine/classes/TextDocument) {🔒None} [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotBrowsable]
  * Added Property [TextDocument.TextContent](https://create.roblox.com/docs/reference/engine/classes/TextDocument#TextContent) [⚡ThreadSafety: ReadSafe]
* Update Class [VoiceChatService](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService) [⬆️Extends: Instance] [🧠Memory: Instances] [🏷️ NotCreatable] [🏷️ Service]
  * Added Function [VoiceChatService.lastVoiceChatConnectivity](https://create.roblox.com/docs/reference/engine/classes/VoiceChatService#lastVoiceChatConnectivity) () -> Dictionary {🚧Audio, Chat}
* Added Enum [FriendsCallingEndReason](https://create.roblox.com/docs/reference/engine/enums/FriendsCallingEndReason)
  * Added EnumItem `None` (0)
  * Added EnumItem `LocalHangup` (1)
  * Added EnumItem `RemoteHangup` (2)
  * Added EnumItem `Missed` (3)
  * Added EnumItem `Declined` (4)
  * Added EnumItem `Failed` (5)
  * Added EnumItem `Canceled` (6)
* Added Enum [FriendsCallingParticipantErrors](https://create.roblox.com/docs/reference/engine/enums/FriendsCallingParticipantErrors)
  * Added EnumItem `None` (0)
  * Added EnumItem `Unknown` (1)
  * Added EnumItem `ConnectionFailed` (2)
  * Added EnumItem `PublishFailed` (3)
  * Added EnumItem `PermissionDenied` (4)
* Added Enum [FriendsCallingParticipantLeaveReason](https://create.roblox.com/docs/reference/engine/enums/FriendsCallingParticipantLeaveReason)
  * Added EnumItem `None` (0)
  * Added EnumItem `Hangup` (1)
  * Added EnumItem `Declined` (2)
  * Added EnumItem `Missed` (3)
  * Added EnumItem `Removed` (4)
  * Added EnumItem `Failed` (5)
  * Added EnumItem `TimedOut` (6)
* Added Enum [FriendsCallingParticipantStatus](https://create.roblox.com/docs/reference/engine/enums/FriendsCallingParticipantStatus)
  * Added EnumItem `Invited` (0)
  * Added EnumItem `Ringing` (1)
  * Added EnumItem `Joined` (2)
  * Added EnumItem `Declined` (3)
  * Added EnumItem `Left` (4)
  * Added EnumItem `Removed` (5)
  * Added EnumItem `Ineligible` (6)
  * Added EnumItem `TimedOut` (7)
  * Added EnumItem `Muted` (8)
* Added Enum [FriendsCallingPhase](https://create.roblox.com/docs/reference/engine/enums/FriendsCallingPhase)
  * Added EnumItem `Idle` (0)
  * Added EnumItem `Ringing` (1)
  * Added EnumItem `Active` (2)
  * Added EnumItem `Ended` (3)
* Update Enum [GradientType](https://create.roblox.com/docs/reference/engine/enums/GradientType)
  * Added EnumItem `Elliptical` (3)
* Added Enum [ProjectServiceOperationResult](https://create.roblox.com/docs/reference/engine/enums/ProjectServiceOperationResult)
