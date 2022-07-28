---
title: EASProvisionDoc
second_title: Aspose.Email för .NET API-referens
description: Anger samlingen av säkerhetsinställningar för enhetsprovisionering.
type: docs
weight: 1190
url: /sv/net/aspose.email.clients.activesync.transportlayer/easprovisiondoc/
---
## EASProvisionDoc class

Anger samlingen av säkerhetsinställningar för enhetsprovisionering.

```csharp
public class EASProvisionDoc
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [EASProvisionDoc](easprovisiondoc)() | Default_Constructor |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [AllowBluetooth](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowbluetooth) { get; set; } | Anger användningen av Bluetooth på enheten. Den här egenskapen SKA ignoreras om klienten inte stöder Bluetooth. |
| [AllowBrowser](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowbrowser) { get; set; } | Anger om enheten tillåter användning av en webbläsare. |
| [AllowCamera](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowcamera) { get; set; } | Anger om enheten tillåter användning av den inbyggda kameran. Den här egenskapen SKA ignoreras om klienten inte har en kamera och ingen kamera kan anslutas till enheten. |
| [AllowConsumerEmail](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowconsumeremail) { get; set; } | Anger om enheten tillåter användaren att konfigurera ett personligt e-postkonto. |
| [AllowDesktopSync](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowdesktopsync) { get; set; } | Anger om enheten tillåter synkronisering med Desktop ActiveSync. Den här egenskapen SKA ignoreras om klienten inte stöder anslutning till en persondator. |
| [AllowHTMLEmail](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowhtmlemail) { get; set; } | Anger om klienten använder HTML-formaterad e-post. |
| [AllowInternetSharing](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowinternetsharing) { get; set; } | Anger om enheten tillåter användning av Internetdelning. Den här egenskapen SKA ignoreras om klienten inte stöder delning av sin internetanslutning med andra enheter. |
| [AllowIrDA](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowirda) { get; set; } | Anger om enheten tillåter användning av IrDA (infraröda) anslutningar. Den här egenskapen SKA ignoreras om klienten inte har förmågan att sända eller ta emot infraröda signaler. |
| [AllowPOPIMAPEmail](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowpopimapemail) { get; set; } | Anger om enheten tillåter åtkomst till POP- eller IMAP-e-post. |
| [AllowRemoteDesktop](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowremotedesktop) { get; set; } | Anger om enheten tillåter användning av Remote Desktop. Den här egenskapen SKA ignoreras om klienten inte stöder fjärranslutning till en persondator. |
| [AllowSimpleDevicePassword](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowsimpledevicepassword) { get; set; } | Anger om klienten tillåter enkla lösenord. Ett enkelt lösenord är ett som endast består av upprepade ("2222") eller sekventiella ("abcd") tecken. Om AllowSimpleDevicePassword är null, SKA en klient behandla detta värde som TRUE. Om värdet för DevicePasswordEnabled är satt till FALSE , klienten SKA ignorera den här egenskapen. |
| [AllowSMIMEEncryptionAlgorithmNegotiation](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowsmimeencryptionalgorithmnegotiation) { get; set; } | Styr förhandlingen av krypteringsalgoritmen. |
| [AllowSMIMESoftCerts](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowsmimesoftcerts) { get; set; } | Anger om klienten kan använda mjuka certifikat för att signera utgående meddelanden. |
| [AllowStorageCard](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowstoragecard) { get; set; } | Anger om enheten tillåter användning av minneskortet. Den här egenskapen SKA ignoreras om klienten inte stöder lagring av data på flyttbar lagring. |
| [AllowTextMessaging](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowtextmessaging) { get; set; } | Anger om enheten tillåter användning av SMS eller textmeddelanden. Den här egenskapen SKA ignoreras om klienten inte stöder SMS eller textmeddelanden. |
| [AllowUnsignedApplications](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowunsignedapplications) { get; set; } | Anger om enheten tillåter att osignerade applikationer körs. |
| [AllowUnsignedInstallationPackages](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowunsignedinstallationpackages) { get; set; } | Anger om enheten tillåter att osignerade kabinettfiler (.cab) installeras. |
| [AllowWiFi](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/allowwifi) { get; set; } | Anger om enheten tillåter användning av Wi-Fi-anslutningar. Den här egenskapen SKA ignoreras om klienten inte har Wi-Fi-kapacitet. |
| [AlphanumericDevicePasswordRequired](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/alphanumericdevicepasswordrequired) { get; set; } | Anger om en klient kräver ett alfanumeriskt lösenord. Om AlphanumericDevicePasswordRequired är null, SKA en klient behandla detta värde som FALSE. Om värdet på DevicePasswordEnabled är FALSE, SKA klienten0-egenskapen ignorera_x00. |
| [ApprovedApplicationList](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/approvedapplicationlist) { get; } | Anger en lista över program i minnet som är godkända för körning. Endast appar i minnet påverkas av den här egenskapen. Den här egenskapen gäller inte för in-ROM-applikationer. Om den inte är tom, MÅSTE klienten endast tillåta de program i minnet som anges av den här egenskapen att köras. |
| [AttachmentsEnabled](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/attachmentsenabled) { get; set; } | Anger om e-postbilagor är aktiverade. |
| [DevicePasswordEnabled](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/devicepasswordenabled) { get; set; } | Anger om en klient kräver ett lösenord. |
| [DevicePasswordExpiration](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/devicepasswordexpiration) { get; set; } | Anger det maximala antalet dagar tills ett lösenord löper ut. DevicePasswordExpiration kan vara null, vilket indikerar att ingen policy för utgångsdatum för lösenord har angetts. Giltiga värden listas nedan: = 0 - Lösenord löper inte ut._ &gt;0000 löper ut._ &gt;000 i det angivna maximala antalet dagar. Om DevicePasswordExpiration är null, SKA en klient behandla detta värde som 0. Om värdet för DevicePasswordEnabled är inställt på FALSE, SKA klienten ignorera denna egenskap. |
| [DevicePasswordHistory](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/devicepasswordhistory) { get; set; } | Anger det minsta antalet tidigare använda lösenord som lagras för att förhindra återanvändning av klienten. Giltiga värden listas nedan: = 0 - Lagring av tidigare använda lösenord krävs inte. &gt; 0 - Minsta antal tidigare använda lösenord som ska användas stored. Om DevicePasswordHistory är null, SKA en klient behandla detta värde som 0. Om värdet för DevicePasswordEnabled är satt till TRUE, tillåter klienten användaren från att använda ett lagrat tidigare lösenord efter att ett lösenord löper ut. Om värdet för DevicePasswordEnabled är satt till TRUE av DevicePasswordEnabled är inställd på FALSE, SKA klienten ignorera denna egenskap. |
| [MaxAttachmentSize](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/maxattachmentsize) { get; set; } | Anger den maximala bifogade storleken i byte enligt säkerhetspolicyn. Om egenskapen är null tolkar klienten detta som att ingen maximal storlek för bilagor har ställts in av säkerhetspolicyn. |
| [MaxCalendarAgeFilter](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/maxcalendaragefilter) { get; set; } | Anger det maximala antalet kalenderdagar som kan synkroniseras. Giltiga värden listas nedan: Alla dagar 2 veckor 1 månad 3 månader 6 månader_x00d_ |
| [MaxDevicePasswordFailedAttempts](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/maxdevicepasswordfailedattempts) { get; set; } | Anger det maximala antalet misslyckade lösenordsinloggningsförsök som är tillåtna. Klienten BÖR utföra en lokal radering eller gå in i ett tidsbestämt låsningsläge om det maximala antalet misslyckade lösenordsinloggningsförsök nås. MaxDevicePasswordFailedAttempts kan vara null eller ha ett värde i intervallet från 4 till 16. Om egenskapen är null, tolkar klienten detta som att inget maximalt antal misslyckade lösenordsinloggningsförsök har ställts in av säkerhetspolicyn. Om värdet för DevicePasswordEnabled är inställt på FALSE, ignorerar klienten denna egenskap. |
| [MaxEmailAgeFilter](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/maxemailagefilter) { get; set; } | Anger åldersgränsen för e-post för synkronisering. Giltiga värden listas nedan: Sync all 1 day 3 days 1 week 2 weeks 1d month |
| [MaxEmailBodyTruncationSize](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/maxemailbodytruncationsize) { get; set; } | Anger trunkeringsstorleken för vanlig textformaterad e-post. Giltiga värden listas nedan: -1 Ingen trunkering. =0 Trunkera endast rubriken. &gt;0 Trunkera e-posttexten till den angivna storleken_x0000d. |
| [MaxEmailHTMLBodyTruncationSize](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/maxemailhtmlbodytruncationsize) { get; set; } | Anger trunkeringsstorleken för HTML-formaterad e-post. Giltiga värden listas nedan: -1 Ingen trunkering. =0 Trunkera endast rubriken. &gt;0 Trunkera e-posttexten till den angivna storleken. |
| [MaxInactivityTimeDeviceLock](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/maxinactivitytimedevicelock) { get; set; } | Anger det maximala antalet sekunders inaktivitet innan enheten låser sig. Om detta värde är större än eller lika med 9999 tolkar klienten det som obegränsat. Om MaxInactivityTimeDeviceLock är null tolkar klienten detta som att ingen tidsenhetslås har ställts in av säkerhetspolicyn. |
| [MinDevicePasswordComplexCharacters](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/mindevicepasswordcomplexcharacters) { get; set; } | Anger den nödvändiga komplexitetsnivån för klientlösenordet. Värdet anger antalet teckengrupper som måste finnas i lösenordet. Teckengrupperna definieras som: Små bokstäver alfabetiska tecken = 1 Gemener och versaler alfabetiska tecken = 2 Gemener, versaler alfabetiska tecken och siffror = 3 Små bokstäver och versaler tecken = Små bokstäver och versaler 4 Till exempel: Om värdet på MinDevicePasswordComplexCharacters är 2 räcker det med ett lösenord med både versaler och gemener, liksom ett lösenord med små bokstäver och siffror. |
| [MinDevicePasswordLength](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/mindevicepasswordlength) { get; set; } | Anger minsta klientlösenordslängd. MinDevicePasswordLength kan vara tom eller ha ett värde som inte är mindre än 1 och inte större än 16. Om egenskapen är null eller värdet för den här egenskapen är 1, finns det ingen minimilängd för enhetslösenord. Om värdet på DevicePasswordEnabled är FALSE, SKA klienten ignorera denna egenskap . |
| [PasswordRecoveryEnabled](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/passwordrecoveryenabled) { get; set; } | Anger om servern stöder lagring av ett återställningslösenord som ska skickas av klienten med kommandot Inställningar. Ett återställningslösenord är ett speciellt lösenord skapat av klienten som ger administratören eller användaren möjlighet att logga in på enheten en gång , varefter användaren måste skapa ett nytt lösenord. Klienten skapar sedan ett nytt återställningslösenord. Om PasswordRecoveryEnabled är satt till TRUE, stöder servern lagring av ett återställningslösenord som skickas av enheten. Om egenskapen är inställd på FALSE SKA enheten INTE skicka ett återställningslösenord, eftersom servern inte stöder lagring av lösenordet. Om PasswordRecoveryEnabled är null, SKA en klient behandla detta värde som FALSK. Om värdet på DevicePasswordEnabled är FALSE, SKA klienten ignorera den här egenskapen. Den här egenskapen SKA ignoreras om klienten inte stöder återställningslösenord. |
| [RequireDeviceEncryption](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/requiredeviceencryption) { get; set; } | Anger om klienten använder kryptering. |
| [RequireEncryptedSMIMEMessages](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/requireencryptedsmimemessages) { get; set; } | Anger om klienten skickar krypterade e-postmeddelanden. |
| [RequireEncryptionSMIMEAlgorithm](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/requireencryptionsmimealgorithm) { get; set; } | Anger algoritmen som används vid kryptering av S/MIME-meddelanden. |
| [RequireManualSyncWhenRoaming](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/requiremanualsyncwhenroaming) { get; set; } | Anger om enheten kräver manuell synkronisering när enheten roaming. |
| [RequireSignedSMIMEAlgorithm](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/requiresignedsmimealgorithm) { get; set; } | Anger algoritmen som används vid signering av S/MIME-meddelanden. |
| [RequireSignedSMIMEMessages](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/requiresignedsmimemessages) { get; set; } | Anger om klienten skickar signerade S/MIME-meddelanden. |
| [RequireStorageCardEncryption](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/requirestoragecardencryption) { get; set; } | Anger om enheten krypterar innehåll som är lagrat på enheten. Den här egenskapen SKA ignoreras om klienten inte stöder lagring av data på flyttbar lagring. |
| [UnapprovedInROMApplicationList](../../aspose.email.clients.activesync.transportlayer/easprovisiondoc/unapprovedinromapplicationlist) { get; } | Anger en lista över in-ROM-applikationer som inte är godkända för körning. Endast program som är förinstallerade i ROM påverkas av posterna i den här egenskapen. Den här egenskapen gäller inte för program som är installerade i minnet. |

### Se även

* namnutrymme [Aspose.Email.Clients.ActiveSync.TransportLayer](../../aspose.email.clients.activesync.transportlayer)
* hopsättning [Aspose.Email](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Email.dll -->
