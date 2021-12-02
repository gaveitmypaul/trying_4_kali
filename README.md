# trying_4_kali
Trying to install kali
 {
        "filename": "python-3.10.0-alpha.5-win32-x64.zip",
        "arch": "x64",
        "platform": "win32",
        "download_url": "https://github.com/actions/python-versions/releases/download/3.10.0-alpha.5-100730/python-3.10.0-alpha.5-win32-x64.zip"
      },<?xml version="1.0" encoding="UTF-16" standalone="true"?>

-<Package xmlns:windowsbuild="http://schemas.microsoft.com/developer/appx/2013/windowsbuild" xmlns:m2="http://schemas.microsoft.com/appx/2013/manifest" xmlns="http://schemas.microsoft.com/appx/2010/manifest" IgnorableNamespaces="windowsbuild">

<Identity Version="17.5.9600.22013" Publisher="CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US" ProcessorArchitecture="x64" Name="microsoft.windowscommunicationsapps"/>


-<Properties>

<DisplayName>ms-resource:communicationsPackageName</DisplayName>

<Description>ms-resource:communicationsPackageName</Description>

<PublisherDisplayName>Microsoft Corporation</PublisherDisplayName>

<Logo>ModernShared\Resources\img\suite_logo.png</Logo>

</Properties>


-<Resources>

<Resource m2:Scale="100"/>

<Resource Language="en-us"/>

<Resource Language="en"/>

<Resource Language="en-gb"/>

</Resources>


-<Prerequisites>

<OSMinVersion>6.3.0</OSMinVersion>

<OSMaxVersionTested>6.3.0</OSMaxVersionTested>

</Prerequisites>


-<windowsbuild:Metadata>

<windowsbuild:Item Name="AppXArch" Value="x64"/>

<windowsbuild:Item Name="Type" Value="fre"/>

<windowsbuild:Item Name="Branch" Value="winblue_ltsb"/>

<windowsbuild:Item Name="Date" Value="180707-0600"/>

<windowsbuild:Item Name="BuildUser" Value="REDMOND\cxesa"/>

<windowsbuild:Item Name="Version" Value="17.5.9600.22013"/>

<windowsbuild:Item Name="ProductVersion" Value="6.3.9600.19095"/>

</windowsbuild:Metadata>


-<Applications>


-<Application StartPage="ModernMail\App\App.html" Id="Microsoft.WindowsLive.Mail">


-<m2:VisualElements ToastCapable="true" BackgroundColor="#0072C6" ForegroundText="light" Description="ms-resource:mailAppTitle" Square30x30Logo="ModernMail\Res\MailSmallLogo.png" Square150x150Logo="ModernMail\Res\MailLogo.png" DisplayName="ms-resource:mailAppTitle">


-<m2:DefaultTile Square310x310Logo="ModernMail\Res\MailLargeLogo.png" Wide310x150Logo="ModernMail\Res\MailWideLogo.png" Square70x70Logo="ModernMail\Res\MailTinyLogo.png" ShortName="ms-resource:mailAppTitle">


-<m2:ShowNameOnTiles>

<m2:ShowOn Tile="square310x310Logo"/>

<m2:ShowOn Tile="square150x150Logo"/>

<m2:ShowOn Tile="wide310x150Logo"/>

</m2:ShowNameOnTiles>

</m2:DefaultTile>

<m2:LockScreen BadgeLogo="ModernMail\Res\MailBadge.png" Notification="badge"/>

<m2:SplashScreen BackgroundColor="#0072C6" Image="ModernMail\Res\MailSplash.png"/>


-<m2:InitialRotationPreference>

<m2:Rotation Preference="landscape"/>

<m2:Rotation Preference="landscapeFlipped"/>

<m2:Rotation Preference="portrait"/>

<m2:Rotation Preference="portraitFlipped"/>

</m2:InitialRotationPreference>

<m2:ApplicationView MinWidth="width320"/>

</m2:VisualElements>


-<ApplicationContentUriRules>

<Rule Match="https://support.microsoft.com/" Type="include"/>

</ApplicationContentUriRules>


-<Extensions>


-<Extension Category="windows.protocol">

<Protocol Name="mailto"/>

</Extension>


-<Extension Category="windows.protocol">

<Protocol Name="ms-mail"/>

</Extension>


-<Extension StartPage="ModernShareTarget\share.html" Category="windows.shareTarget">


-<ShareTarget m2:Description="ms-resource:mailShareDescription">


-<SupportedFileTypes>

<SupportsAnyFileType/>

</SupportedFileTypes>

<DataFormat>Uri</DataFormat>

<DataFormat>Text</DataFormat>

<DataFormat>Html</DataFormat>

<DataFormat>Bitmap</DataFormat>

</ShareTarget>

</Extension>


-<Extension Category="windows.backgroundTasks" EntryPoint="Microsoft.WindowsLive.Platform.VerbBackgroundTask">


-<BackgroundTasks ServerName="Microsoft.WindowsLive.Platform.Server">

<Task Type="systemEvent"/>

<Task Type="timer"/>

<Task Type="pushNotification"/>

</BackgroundTasks>

</Extension>


-<Extension Category="windows.backgroundTasks" EntryPoint="Microsoft.WindowsLive.Platform.LockscreenStateChangeTask">


-<BackgroundTasks ServerName="Microsoft.WindowsLive.Platform.Server">

<Task Type="systemEvent"/>

<Task Type="pushNotification"/>

</BackgroundTasks>

</Extension>


-<Extension Category="windows.backgroundTasks" EntryPoint="Microsoft.WindowsLive.Platform.ServicingCompleteTask">


-<BackgroundTasks ServerName="Microsoft.WindowsLive.Platform.Server">

<Task Type="systemEvent"/>

<Task Type="pushNotification"/>

</BackgroundTasks>

</Extension>


-<Extension Category="windows.backgroundTasks" EntryPoint="Microsoft.WindowsLive.Platform.OnlineIdConnectedStateChangeTask">


-<BackgroundTasks ServerName="Microsoft.WindowsLive.Platform.Server">

<Task Type="systemEvent"/>

<Task Type="pushNotification"/>

</BackgroundTasks>

</Extension>


-<Extension Category="windows.backgroundTasks" EntryPoint="Microsoft.LiveComm.FirstRun">


-<BackgroundTasks ServerName="Microsoft.WindowsLive.Platform.Server">

<Task Type="systemEvent"/>

<Task Type="pushNotification"/>

</BackgroundTasks>

</Extension>


-<Extension Category="windows.backgroundTasks" EntryPoint="Microsoft.WindowsLive.Platform.DirectPushNotificationTask">


-<BackgroundTasks ServerName="Microsoft.WindowsLive.Platform.Server">

<Task Type="controlChannel"/>

</BackgroundTasks>

</Extension>


-<Extension Category="windows.backgroundTasks" EntryPoint="Microsoft.WindowsLive.Platform.DirectPushKeepAliveTask">


-<BackgroundTasks ServerName="Microsoft.WindowsLive.Platform.Server">

<Task Type="controlChannel"/>

</BackgroundTasks>

</Extension>


-<Extension Category="windows.backgroundTasks" EntryPoint="Microsoft.WindowsLive.Platform.ManualPushNotificationTask">


-<BackgroundTasks ServerName="Microsoft.WindowsLive.Platform.Server">

<Task Type="controlChannel"/>

</BackgroundTasks>

</Extension>


-<Extension Category="windows.backgroundTasks" EntryPoint="Microsoft.WindowsLive.Platform.ManualPushKeepAliveTask">


-<BackgroundTasks ServerName="Microsoft.WindowsLive.Platform.Server">

<Task Type="controlChannel"/>

</BackgroundTasks>

</Extension>

</Extensions>

</Application>


-<Application StartPage="ModernCalendar\app\App.html" Id="Microsoft.WindowsLive.Calendar">


-<m2:VisualElements ToastCapable="true" BackgroundColor="#5133AB" ForegroundText="light" Description="ms-resource:calendarAppTitle" Square30x30Logo="ModernCalendar\CalendarSmallLogo.png" Square150x150Logo="ModernCalendar\CalendarLogo.png" DisplayName="ms-resource:calendarAppTitle">


-<m2:DefaultTile Square310x310Logo="ModernCalendar\CalendarLargeLogo.png" Wide310x150Logo="ModernCalendar\CalendarWideLogo.png" Square70x70Logo="ModernCalendar\CalendarTinyLogo.png" ShortName="ms-resource:calendarAppTitle">


-<m2:ShowNameOnTiles>

<m2:ShowOn Tile="square150x150Logo"/>

<m2:ShowOn Tile="wide310x150Logo"/>

<m2:ShowOn Tile="square310x310Logo"/>

</m2:ShowNameOnTiles>

</m2:DefaultTile>

<m2:LockScreen BadgeLogo="ModernCalendar\CalendarBadge.png" Notification="badgeAndTileText"/>

<m2:SplashScreen BackgroundColor="#5133AB" Image="ModernCalendar\CalendarSplash.png"/>

<m2:ApplicationView MinWidth="width320"/>

</m2:VisualElements>


-<ApplicationContentUriRules>

<Rule Match="https://support.microsoft.com/" Type="include"/>

</ApplicationContentUriRules>


-<Extensions>


-<Extension StartPage="ModernCalendar\app\App.html" Category="windows.protocol">


-<Protocol Name="wlcalendar">

<Logo>ModernCalendar\CalendarLogo.png</Logo>

</Protocol>

</Extension>


-<Extension Category="windows.backgroundTasks" EntryPoint="Dummy.Class.For.Lockscreen.Notification.Capability.Do.Not.Delete" Executable="Dummy.Class.For.Lockscreen.Notification.Capability.Do.Not.Delete.exe">


-<BackgroundTasks>

<Task Type="pushNotification"/>

</BackgroundTasks>

</Extension>


-<Extension Category="windows.backgroundTasks" EntryPoint="Dummy.Class.For.RTC.Control.Channel.Do.Not.Delete" Executable="Dummy.Class.For.RTC.Control.Channel.Do.Not.Delete.exe">


-<BackgroundTasks>

<Task Type="controlChannel"/>

</BackgroundTasks>

</Extension>


-<m2:Extension StartPage="ModernCalendar\views\provider\provider.htm" Category="windows.appointmentsProvider">


-<m2:AppointmentsProvider>


-<m2:AppointmentsProviderLaunchActions DesiredView="useHalf">

<m2:LaunchAction StartPage="ModernCalendar\app\App.html" Verb="showTimeFrame"/>

</m2:AppointmentsProviderLaunchActions>

</m2:AppointmentsProvider>

</m2:Extension>

</Extensions>

</Application>


-<Application StartPage="ModernPeople\AppFrame\People.htm" Id="Microsoft.WindowsLive.People">


-<m2:VisualElements BackgroundColor="#d24726" ForegroundText="light" Description="ms-resource:///strings/peopleAppName" Square30x30Logo="ModernPeople\PeopleSmall.png" Square150x150Logo="ModernPeople\People.png" DisplayName="ms-resource:///strings/peopleAppName">


-<m2:DefaultTile Square310x310Logo="ModernPeople\PeopleLarge.png" Wide310x150Logo="ModernPeople\PeopleWide.png" Square70x70Logo="ModernPeople\PeopleTiny.png" ShortName="ms-resource:///strings/peopleAppName">


-<m2:ShowNameOnTiles>

<m2:ShowOn Tile="square150x150Logo"/>

<m2:ShowOn Tile="wide310x150Logo"/>

<m2:ShowOn Tile="square310x310Logo"/>

</m2:ShowNameOnTiles>

</m2:DefaultTile>

<m2:SplashScreen Image="ModernPeople\PeopleSplash.png"/>

<m2:ApplicationView MinWidth="width320"/>

</m2:VisualElements>


-<ApplicationContentUriRules>

<Rule Match="https://support.microsoft.com/" Type="include"/>

</ApplicationContentUriRules>


-<Extensions>


-<Extension StartPage="ModernPeople\AppFrame\People.htm" Category="windows.protocol">


-<Protocol Name="wlpeople">

<Logo>ModernPeople\Icon.png</Logo>

</Protocol>

</Extension>


-<Extension StartPage="ModernPeople\AppFrame\People.htm" Category="windows.protocol">


-<Protocol Name="profile-messenger">

<Logo>ModernPeople\Icon.png</Logo>

</Protocol>

</Extension>


-<Extension StartPage="ModernPeople\AppFrame\People.htm" Category="windows.protocol">


-<Protocol Name="profile-outlook-com">

<Logo>ModernPeople\Icon.png</Logo>

</Protocol>

</Extension>


-<Extension StartPage="ModernPeople\AppFrame\People.htm" Category="windows.protocol">


-<Protocol Name="profile-skype-com">

<Logo>ModernPeople\Icon.png</Logo>

</Protocol>

</Extension>


-<Extension StartPage="ModernPeople\AppFrame\People.htm" Category="windows.protocol">


-<Protocol Name="profile-twitter-com">

<Logo>ModernPeople\Icon.png</Logo>

</Protocol>

</Extension>


-<Extension StartPage="ModernPeople\AppFrame\People.htm" Category="windows.protocol">


-<Protocol Name="profile-google-com">

<Logo>ModernPeople\Icon.png</Logo>

</Protocol>

</Extension>


-<Extension StartPage="ModernPeople\AppFrame\People.htm" Category="windows.protocol">


-<Protocol Name="profile-weibo-com">

<Logo>ModernPeople\Icon.png</Logo>

</Protocol>

</Extension>


-<Extension StartPage="ModernPeople\AppFrame\People.htm" Category="windows.protocol">


-<Protocol Name="profile-linkedin-com">

<Logo>ModernPeople\Icon.png</Logo>

</Protocol>

</Extension>


-<Extension StartPage="ModernPeople\AppFrame\People.htm" Category="windows.protocol">


-<Protocol Name="profile-yahoo-com">

<Logo>ModernPeople\Icon.png</Logo>

</Protocol>

</Extension>


-<Extension StartPage="ModernPeople\AppFrame\People.htm" Category="windows.protocol">


-<Protocol Name="profile-lync-com">

<Logo>ModernPeople\Icon.png</Logo>

</Protocol>

</Extension>

<Extension StartPage="ModernPeople\AppFrame\People.htm" Category="windows.accountPictureProvider"/>

<Extension StartPage="ModernPeople\AppFrame\Picker.htm" Category="windows.contactPicker"/>

<Extension StartPage="ModernPeople\AppFrame\People.htm" Category="windows.search"/>


-<Extension StartPage="ModernPeople\AppFrame\Share.htm" Category="windows.shareTarget">


-<ShareTarget m2:Description="ms-resource:///strings/raShareDescription">

<DataFormat>WebLink</DataFormat>

</ShareTarget>

</Extension>


-<m2:Extension Category="windows.contact">


-<m2:Contact>


-<m2:ContactLaunchActions>


-<m2:LaunchAction DesiredView="useLess" Verb="post">

<m2:ServiceId>twitter.com</m2:ServiceId>

</m2:LaunchAction>

</m2:ContactLaunchActions>

</m2:Contact>

</m2:Extension>

</Extensions>

</Application>

</Applications>


-<Capabilities>

<Capability Name="privateNetworkClientServer"/>

<Capability Name="sharedUserCertificates"/>

<Capability Name="internetClient"/>

<DeviceCapability Name="webcam"/>

</Capabilities>


-<Extensions>


-<Extension Category="windows.activatableClass.inProcessServer">


-<InProcessServer>

<Path>Microsoft.WindowsLive.Platform.Calendar.dll</Path>

<ActivatableClass ThreadingModel="both" ActivatableClassId="Microsoft.WindowsLive.Platform.Calendar.CalendarManager"/>

<ActivatableClass ThreadingModel="MTA" ActivatableClassId="Microsoft.WindowsLive.Platform.Calendar.CalendarService"/>

<ActivatableClass ThreadingModel="both" ActivatableClassId="Microsoft.WindowsLive.Platform.Calendar.CalendarParser"/>

</InProcessServer>

</Extension>


-<Extension Category="windows.activatableClass.inProcessServer">


-<InProcessServer>

<Path>Microsoft.WindowsLive.Platform.Calendar.dll</Path>

<ActivatableClass ThreadingModel="both" ActivatableClassId="Microsoft.WindowsLive.Platform.Meetings.InvitesManager"/>

</InProcessServer>

</Extension>


-<Extension Category="windows.activatableClass.inProcessServer">


-<InProcessServer>

<Path>ErrorReporting.dll</Path>

<ActivatableClass ThreadingModel="MTA" ActivatableClassId="Microsoft.WindowsLive.Shared.Telemetry.ErrorReporting"/>

</InProcessServer>

</Extension>


-<Extension Category="windows.activatableClass.proxyStub">


-<ProxyStub ClassId="3c20f953-30a9-406c-a60b-e59383c0c2d4">

<Path>ErrorReporting.dll</Path>

<Interface Name="IErrorReporting" InterfaceId="06596403-3E45-4C1D-A884-CA6CD1150CD4"/>

</ProxyStub>

</Extension>


-<Extension Category="windows.activatableClass.inProcessServer">


-<InProcessServer>

<Path>wlcore.dll</Path>

<ActivatableClass ThreadingModel="both" ActivatableClassId="Microsoft.WindowsLive.Cid.CidFormatter"/>

<ActivatableClass ThreadingModel="STA" ActivatableClassId="Microsoft.WindowsLive.Jx"/>

<ActivatableClass ThreadingModel="both" ActivatableClassId="Microsoft.WindowsLive.Market"/>

</InProcessServer>

</Extension>


-<Extension Category="windows.activatableClass.inProcessServer">


-<InProcessServer>

<Path>Microsoft.PerfTrack.dll</Path>

<ActivatableClass ThreadingModel="both" ActivatableClassId="Microsoft.PerfTrack.PerfTrackLogger"/>

</InProcessServer>

</Extension>


-<Extension Category="windows.activatableClass.inProcessServer">


-<InProcessServer>

<Path>bici.dll</Path>

<ActivatableClass ThreadingModel="both" ActivatableClassId="Microsoft.WindowsLive.Instrumentation.Bici"/>

<ActivatableClass ThreadingModel="both" ActivatableClassId="Microsoft.WindowsLive.Instrumentation.DatapointValueList"/>

<ActivatableClass ThreadingModel="both" ActivatableClassId="Microsoft.WindowsLive.Instrumentation.TransactionContext"/>

<ActivatableClass ThreadingModel="both" ActivatableClassId="Microsoft.WindowsLive.Instrumentation.TransactionId"/>

</InProcessServer>

</Extension>


-<Extension Category="windows.activatableClass.inProcessServer">


-<InProcessServer>

<Path>Microsoft.WindowsLive.Launch.dll</Path>

<ActivatableClass ThreadingModel="both" ActivatableClassId="Microsoft.WindowsLive.Config.Shared.SuiteUpdate"/>

<ActivatableClass ThreadingModel="both" ActivatableClassId="Microsoft.WindowsLive.Config.Shared.Feedback"/>

</InProcessServer>

</Extension>


-<Extension Category="windows.activatableClass.inProcessServer">


-<InProcessServer>

<Path>Microsoft.WindowsLive.Platform.dll</Path>

<ActivatableClass ThreadingModel="MTA" ActivatableClassId="Microsoft.LiveComm.FirstRun"/>

<ActivatableClass ThreadingModel="both" ActivatableClassId="Microsoft.WindowsLive.Platform.Client"/>

<ActivatableClass ThreadingModel="MTA" ActivatableClassId="Microsoft.WindowsLive.Platform.LockscreenStateChangeTask"/>

<ActivatableClass ThreadingModel="MTA" ActivatableClassId="Microsoft.WindowsLive.Platform.DirectPushNotificationTask"/>

<ActivatableClass ThreadingModel="MTA" ActivatableClassId="Microsoft.WindowsLive.Platform.DirectPushKeepAliveTask"/>

<ActivatableClass ThreadingModel="MTA" ActivatableClassId="Microsoft.WindowsLive.Platform.ManualPushNotificationTask"/>

<ActivatableClass ThreadingModel="MTA" ActivatableClassId="Microsoft.WindowsLive.Platform.ManualPushKeepAliveTask"/>

<ActivatableClass ThreadingModel="both" ActivatableClassId="Microsoft.WindowsLive.Platform.Private.ClientManagerProvider"/>

<ActivatableClass ThreadingModel="MTA" ActivatableClassId="Microsoft.WindowsLive.Platform.OnlineIdConnectedStateChangeTask"/>

<ActivatableClass ThreadingModel="MTA" ActivatableClassId="Microsoft.WindowsLive.Platform.ServicingCompleteTask"/>

<ActivatableClass ThreadingModel="MTA" ActivatableClassId="Microsoft.WindowsLive.Platform.VerbBackgroundTask"/>

</InProcessServer>

</Extension>


-<Extension Category="windows.activatableClass.outOfProcessServer">


-<OutOfProcessServer ServerName="Microsoft.WindowsLive.Platform.Server">

<Path>LiveComm.exe</Path>

<Instancing>singleInstance</Instancing>

<ActivatableClass ActivatableClassId="Microsoft.WindowsLive.Platform.Service.RemoteProcess"/>

</OutOfProcessServer>

</Extension>


-<Extension Category="windows.activatableClass.proxyStub">


-<ProxyStub ClassId="3F0E13A0-4667-4C78-84B0-9BB753C5EF0E">

<Path>Microsoft.WindowsLive.Platform.dll</Path>

<Interface Name="IContactSynchronizationPrivate" InterfaceId="5F333224-DB8B-4A5D-8294-136963C37A6C"/>

<Interface Name="ILivePlatformRemoteUserFactory" InterfaceId="A18B599B-94DD-41DD-80F5-86E36617F08A"/>

<Interface Name="ILivePlatformRemoteUser" InterfaceId="FCDCFE93-A860-448F-9F59-40E7D85609BC"/>

<Interface Name="ILivePlatformRemoteUserCallback" InterfaceId="D6C4144A-21BD-4385-BAC2-7F2F1C53DE89"/>

<Interface Name="ILivePlatformRemoteUserCollection" InterfaceId="A7E197EA-F5A0-4028-9D8B-1E909B157BF7"/>

<Interface Name="ILivePlatformRestartCallback" InterfaceId="A0BA40C3-0231-4C69-B33D-36F181F09F4E"/>

<Interface Name="ILivePlatformVerb" InterfaceId="8BCEC5DB-850C-469F-862F-8AE7AB6C33FC"/>

<Interface Name="ILivePlatformVerbManager" InterfaceId="09B06684-A2BF-4F62-9A77-D1B04F3187CA"/>

<Interface Name="ILivePlatformSuspendResumeHandler" InterfaceId="C02321F7-A955-40E5-99F0-67E58E088AB1"/>

<Interface Name="ILivePlatformClientVisibility" InterfaceId="10A3C2A2-0BCE-4FE2-94BC-F757CD5A5890"/>

<Interface Name="ILivePlatformPropertyBag" InterfaceId="F2CAF5A9-6237-401D-A8F6-08A553F00C8F"/>

<Interface Name="ILivePlatformObjectWithSite" InterfaceId="F6794DDC-B81A-42B8-817C-C9C5B7309AA1"/>

<Interface Name="ILivePlatformService" InterfaceId="24D38301-B637-48A4-87FF-C5AA37C7B4A5"/>

<Interface Name="ILivePlatformServiceProvider" InterfaceId="946B3A75-7908-4422-AAEC-0848CE3E5D0F"/>

<Interface Name="ILivePlatformServiceSink" InterfaceId="FFE41672-09AD-426E-8516-BD8F20665BDC"/>

<Interface Name="ILivePlatformServiceSite" InterfaceId="2B7B0B00-5A8C-43A0-923A-BD301CE1E641"/>

<Interface Name="ILivePlatformVerbHandler" InterfaceId="236D2810-8F38-4A3F-A962-76671AE05706"/>

<Interface Name="IStoreCacheViewRpc" InterfaceId="146579FD-2F9F-4F33-8D16-E3AEEB5E01F8"/>

<Interface Name="IStoreIndexViewCallbackRpc" InterfaceId="3759ACE6-7445-4381-B1D1-BAF75D537116"/>

<Interface Name="IStoreIndexViewRpc" InterfaceId="A36A9A63-949C-4C1C-BD7D-E136E746A628"/>

<Interface Name="IStoreObjectManagerAttachRpc" InterfaceId="822C098A-6362-4ECE-BB8B-B1644AEA0DDB"/>

<Interface Name="IStoreObjectManagerRpc" InterfaceId="5D18B906-9491-4068-BC9A-EC2DF95D0038"/>

<Interface Name="IStoreObjectViewCallbackRpc" InterfaceId="5BF07B22-C7D9-4D0D-AEA0-A8F5F9B157E4"/>

</ProxyStub>

</Extension>


+<Extension Category="windows.activatableClass.proxyStub">
































-<Extension Category="windows.activatableClass.inProcessServer">


-<InProcessServer>

<Path>Microsoft.WindowsLive.Photomail.dll</Path>

<ActivatableClass ThreadingModel="MTA" ActivatableClassId="Microsoft.WindowsLive.Photomail.PhotomailTranscoder"/>

<ActivatableClass ThreadingModel="MTA" ActivatableClassId="Microsoft.WindowsLive.Photomail.AttachmentManager"/>

</InProcessServer>

</Extension>


-<Extension Category="windows.activatableClass.proxyStub">


-<ProxyStub ClassId="0142FA53-13F8-4b40-A3FE-611389F6600E">

<Path>Microsoft.WindowsLive.Photomail.dll</Path>

<Interface Name="Microsoft.WindowsLive.Photomail.IPhotomailTranscoderStatics" InterfaceId="C10D9473-49AF-4E96-8E19-124046F28CB8"/>

<Interface Name="__FIAsyncOperationCompletedHandler_1_Microsoft__CWindowsLive__CPhotomail__CExifOrientation" InterfaceId="621b1632-abc3-5331-865c-01f013b96079"/>

<Interface Name="__FIAsyncOperation_1_Microsoft__CWindowsLive__CPhotomail__CExifOrientation" InterfaceId="83407ad1-58bd-58f9-859a-a5c2a9815b40"/>

<Interface Name="Microsoft.WindowsLive.Photomail.IAttachmentManagerStatics" InterfaceId="E19BB976-53CD-4DF0-9FC2-20AF457EA1ED"/>

<Interface Name="Microsoft.WindowsLive.Photomail.IAttachmentManager" InterfaceId="C9699850-6154-4577-A0BD-73079BBFC0DD"/>

<Interface Name="IQueueEmptyHandler" InterfaceId="009D04BE-4567-48BA-BBE7-7B18CB8547B2"/>

</ProxyStub>

</Extension>

</Extensions>


-<Dependencies>

<PackageDependency Publisher="CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US" Name="Microsoft.WinJS.2.0"/>

<PackageDependency Publisher="CN=Microsoft Corporation, O=Microsoft Corporation, L=Redmond, S=Washington, C=US" Name="Microsoft.VCLibs.120.00" MinVersion="12.0.20501.1"/>

</Dependencies>

</Package>
