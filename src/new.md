---
layout: page
permalink: /resources/new/
title: What's New
---

## 5.7.1902

- [ApplicationVersionInformation]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.ApplicationVersionInformation): Added beta support

- [BinaryDataType]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.BinaryDataType): Added `SoftwareVersionSection1`, `SoftwareVersionSection2`, `SoftwareVersionSection3`

- [DefectRemark]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.DefectRemark): Added beta support

- [DefectSeverity]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.DefectSeverity): Added `Unregulated`

- [Device]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.Device): Adding a device will now force the ActiveTo property to max date. Setting a device's ActiveTo property to a future date, but not max date, will force the value to max date.

- [DeviceType]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.DeviceType): Added `GO9`

- [DiagnosticType]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.Engine.DiagnosticType): Added `ProprietaryFault`, `LegacyFault`

- [DriverRegulation]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.DriverRegulation): Added beta support

- [DtcClass]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.Engine.DtcClass): Added beta support

- [DtcSeverity]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.Engine.DtcSeverity): Added beta support

- [DutyStatusAvailability]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.DutyStatusAvailability): Added properties `CycleRest`, `DutySinceCycleRest`, `Is16HourExemptionAvailable`, `IsAdverseDrivingExemptionAvailable`, `IsOffDutyDeferralExemptionAvailable`

- DutyStatusAvailabilityDuration: Removed from documentionation, will be obsoleted in future

- [DutyStatusViolationType]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.DutyStatusViolationType): Added `CycleRest` and `DutySinceCycleRest`

- [DVIRDefect]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.DVIRDefect): Added beta support

- [ElectricEnergyUnit]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.Settings.ElectricEnergyUnit): Added beta support

- [ElectricEnergyEconomyUnit]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.Settings.ElectricEnergyEconomyUnit): Added beta support

- [FaultData]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.Engine.FaultData): Added `ClassCode`, `Severity` and `SourceAddress` properties

- [GO9]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.Go9): Added support

- [GroupSearch]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.GroupSearch): Added search by `Reference`

- [HosRuleSet]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.Settings.HosRuleSet): Added `CaliforniaFlammableLiquid`, `CaliforniaSchoolPupil`, `CaliforniaFarmProduct`, `OilTransportCalifornia8day`, `OilWellCalifornia8day`

- [KnownId]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.KnownId): Added `UnitOfMeasureLitersPerTonneId`, `DiagnosticStateOfChargeId`, `DiagnosticTotalLifetimeBatteryEnergyInDuringACChargingId`, `DiagnosticTotalLifetimeBatteryEnergyInDuringDCChargingId`, `DiagnosticTotalLifetimeOnBoardChargerEnergyOutDuringACChargingId`, `DiagnosticTotalLifetimeOnBoardChargerEnergyInDuringACChargingInId`, `DiagnosticOnBoardChargerAcInputVoltageId`, `DiagnosticElectricVehicleChargingStateId`, `DiagnosticElectricVehicleBatteryPowerId`,  `DiagnosticOnBoardChargerACInputPowerId`, `DiagnosticOnBoardChargerDCOutputPowerId`, `DiagnosticElectricEnergyInId,DiagnosticElectricEnergyOutId`, `HosRuleSetCaliforniaFlammableLiquid`, `HosRuleSetCaliforniaSchoolPupil`, `HosRuleSetCaliforniaFarmProduct`, `HosRuleSetOilTransportCalifornia8day`, `HosRuleSetOilWellCalifornia8day`, `ControllerProprietaryFaultId`, `ControllerLegacyFaultId`, `SourceProprietaryId`, `SourceLegacyId`, `DiagnosticBluetoothNitricOxideConcentrationId`, `DiagnosticBluetoothNitrogenDioxideConcentrationId`, `DiagnosticBluetoothCarbonMonoxideConcentrationId`, `DiagnosticBluetoothAmmoniaConcentrationId`, `DiagnosticBluetoothMethaneConcentrationId`, `DiagnosticBluetoothEthanolConcentrationId`, `DiagnosticBluetoothHydrogenConcentrationId`, `DiagnosticBluetoothCarbonDioxideConcentrationId`

- [MimeContent]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.MimeContent): Added `ChannelNumber` property

- [RepairStatusType]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.RepairStatusType): Added beta support

- [SecurityIdentifierPermalink]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.SecurityIdentifierPermalink): Added `InspectDVIR`, `CertifyDVIR` - Removed `DailyUsageReport`

- [User]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.User): Added `ElectricEnergyEconomyUnit` and `isEmailReportEnabled` properties

- [User]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.User): Fixed bug where `isDriver` property would be included with `id` in nested driver entities. This property is removed from nested entities. It will remain in non-nested users.

- [VersionInformation]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.VersionInformation): `Server` is obsolete and replaced with more detailed `Application` property (see [ApplicationVersionInformation]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.ApplicationVersionInformation))

### Result and Rate Limits

For an in-depth description of the result in rate limit changes in 5.7.1902 and future releases see [this blog post](https://www.geotab.com/blog/result-and-rate-limits/)

- [Concepts]({{site.baseurl}}/software/guides/concepts/#limits) section updated to reflect new result and rate limits.

- Result Limits: Maximum result limit of 50,000 has been added to generic `Get` (including `Get` using `search`) requests of entity types: AnnotationLog, DVIRLog, TrailerAttachment, IoxAddOn, CustomData, BinaryData. Results limits will be added to more entity types in future releases.

- Rate Limits: Rate limits of 1 RPS (request-per-second) has been added to all `GetFeed` APIs.

## 5.7.1901

- Sun-setting support for SendEmail API. No longer available in API documentation.

- [Device]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.Device): Active from/to:
  - The device property `ActiveTo` will automatically be set to max date (2050-01-01) to denote that it is active.
  - To account for differences in Client machine time vs Server machine time, we are allowing users to set the value of `ActiveTo` to a max window of 24 hours in the future (i.e. Current Time + 24 hours). In this situation we are considering it to be historical.

- [DVIRLog]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.DVIRLog): Added `Location` property.

- [SecurityIdentifier]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.SecurityIdentifier): Added `ViewBusinessIntelligence`, `ActiveTrackingClearance`.

- SecurityRole: Added `EmailSent`, `SkipHosVerify`, `SkipHosClaimUnassigned`, `SkipDvirInspect`.

## 5.7.1804.1

- [API.cs]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.API) (.Net only): Fix bug, Windows 10 using IIS Express possible hanging *synchronous* requests using nuget package 5.7.1803\5.7.1804.

## 5.7.1804

- [Add]({{site.baseurl}}/software/api/reference/#M:Geotab.Checkmate.Database.DataStore.Add1)/[Set]({{site.baseurl}}/software/api/reference/#M:Geotab.Checkmate.Database.DataStore.Set1) [Device]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.Device): `ParameterVersion` will auto increment server side when device parameters property changed. Server must see that  `ParameterVersion` has incremented to send parameters to an installed GO device (ex device beeping instructions). Previously, `ParameterVersion` required manual increment.

- [API.cs]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.API) (.Net only): Fix bug, in certian senario changing `Timeout` property could abort the action on timeout and not cancel underlying request.

- [CustomVehicleDevice]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.CustomVehicleDevice): Support of vehicle specific custom devices which provide vehicle specific properties and functionality. Custom device product ID must be of CustomVehicleDevice type. Contact your reseller for more information.

  - Improved support for calculated odometer and raw odometer with third-party diagnostic KnownId `DiagnosticThirdPartyOdometerId` and `OdometerAdjusmentId`

  - Improved support for calculated engine hours with third-party diagnostic KnownId `DiagnosticThirdPartyEngineRunTimeId` and `EngineHoursAdjusmentId`

  - `VehicleIdentificationNumber` property moved from CustomDevice to CustomVehicleDevice

  - Added `LicencePlate` and `LicenceState` properties

- [DutyStatusAvailability]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.DutyStatusAvailability): Added BETA support for `Recap` and `CycleAvailabilities` properties

- [DutyStatusAvailability]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.DutyStatusAvailability): Replaced `Availabilities` list with separate properties: `Driving`, `Cycle`, `Rest`, `Duty`, `Workday`

- [DeviceType]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.DeviceType): Added `CustomVehicleDevice`.

- [DriverChange]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.DriverChange): DriverChange object Id property is no longer backed by integer type. It is now backed by GUID type. When update 1804 is applied to the database, all previous numeric entity Id's will be invalidated and assigned a new GUID Id's. This could pose an issue if your integration stores driver change Id and you then reference the DriverChange by that Id. Note: JSON representation of Id was previously string and remains string type.

- [DutyStatusLogType]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.DutyStatusLogType): Added `ExemptionOffDutyDeferral`.

- [DutyStatusViolationType]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.DutyStatusViolationType): Added `DailyDriving`, `DailyRest`, `DailyDuty`, `DailyOff`.

- [KnownId]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.KnownId): Added `DiagnosticThirdPartyEngineRunTimeId`,  `DiagnosticThirdPartyOdometerId`.

- [GetFeed]({{site.baseurl}}/software/api/reference/#M:Geotab.Checkmate.Database.DataStore.GetFeed1) [LogRecord]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.LogRecord): Fixed bug with inconstant results limit.

- [SecurityIdentifier]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.SecurityIdentifier): Added `DirectSupportAdmin`, `UserLoginStatusRead`, `UserLoginStatusSet`.

- [SecurityIdentifier]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.SecurityIdentifier): Values `AlarmSoundList`, `Tracking`, `CreateNewSqlDatabase`, `EngineControllerList`, `PurgeSettings`, `SendImmobilizationInstruction` are obsolete and will be removed in version 1806+.

- [SecurityRole]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.SecurityRole): Added `SupportTicketInsert`, `TrainingTicketInser`, `SupportTicketSet`, `TrainingTicketSetUser`, `LoginFailure`, `UserLockout`, `UserUnlocked`, `ShipmentLogInsert`, `ShipmentLogSet`, `ShipmentLogRemove`, `TrailerAttachmentInsert`, `TrailerAttachmentSet`, `TrailerAttachmentRemove`.

- [ZoneSearch]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.ZoneSearch): Added `FromDate` and `ToDate` search properties providing ability to filter zones by their active dates.

> [API.cs]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.API) (.Net only): There is a known issue on Windows 10 using IIS Express with possible hanging *synchronous* requests using nuget package 5.7.1803\5.7.1804. This issue is solved in 5.7.1804.1 or greater.

## 5.7.1803

* SecurityRole: Added `CertificateSet` permission

* [DriverChangeSearch]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.DriverChangeSearch): Added property `Type` indicating the DriverChangeType to search for exclusively.

> [API.cs]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.API) (.Net only): There is a known issue on Windows 10 using IIS Express with possible hanging *synchronous* requests using nuget package 5.7.1803\5.7.1804. This issue is solved in 5.7.1804.1 or greater.

## 5.7.1802

* [DutyStatusLog]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.DutyStatusLog): Added properties `Odometer`, `EngineHours`, `EventRecordStatus`, `EventCode`, `EventType`

* [DutyStatusLogType]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.DutyStatusLogType): Added `SituationalDrivingClear`

* [FuelTaxDetail]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.FuelTaxDetail): Added properties `HourlyIsOdometerInterpolated`, `IsEnterOdometerInterpolated`, `IsExitOdometerInterpolated`

* [FuelTaxDetail]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.FuelTaxDetail): Obsolete `IsClusterOdometer` - Superseded by the IsEnterOdometerInterpolated, HourlyIsOdometerInterpolated, and IsExitOdometerInterpolated properties. Will be removed in future version.

* [FuelTaxDetailSearch]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.FuelTaxDetailSearch): Added properties `IncludeBoundaries`, `IncludeHourlyData`

* [SecurityIdentifier]({{site.baseurl}}/software/api/reference/#T:Geotab.Checkmate.ObjectModel.SecurityIdentifier): Added `ViewTripTypeChangeData`, `EditTripTypeChangeData`

### Notice

An issue was discovered which could cause integrations using the Geotab.Checkmate.Objectmodel nuget package v5.7.1801 and lower to encounter a serailizaion failure when a new DiagnosticType is introduced. The issue has been addressed in nuget package v[5.7.1802](https://www.nuget.org/packages/Geotab.Checkmate.ObjectModel/). To ensure compatibility, it is strongly recommended that all integrations referencing the nuget package v5.7.1801 and lower update to version v5.7.1802 as soon as possible. (this issue is only relevant to .Net nuget package users)

## 5.7.1801

* KnownId - Removed: `UnitOfMeasureLitersPer100KilometersId`. Diagnostics associated with this unit of measure now use `UnitOfMeasureKilometersPerLiterId`. This will not affect any previously recorded data.

* KnownId - Added: `DiagnosticGpsLogReasonId`, `DiagnosticEngineRoadSpeedId`

* ConditionType - Added: `DVIRDefect` - Currently works with Devices not Trailers

* SecurityIdentifier - Added: `DriverIdentificationClearance`, `AccelerometerDataClearance`, `ServicePlansClearance`, `AuxiliaryClearance`, `EngineStatusDataClearance`, `ResellerControlClearance`, `GoTalkClearance`, `StatusGroupsClearance`, `ProductGuideClearance`, `FeaturePreviewClearance`, `NewsNotificationsClearance`, `ManageAddinsClearance`, `DeviceCurrentStatusClearance`

### Notice

In early 2018 the following legacy properties will be removed:

**Authenticate**: `userLogin` parameter. This was kept around for compatibility with legacy (5.6.* and lower) integrations. It has not been publicly exposed or documented since version 5.6 of MyGeotab. It is planned to be removed as a valid parameter in version 5.7.1803. The `userName` parameter is the standard supported property that should be used.

**LoginResult**: `securityToken` property. LoginResult is the object returned by the Authenticate method. It's property `securityToken` was kept around for compatibility with legacy (5.6.* and lower) integrations. It has not been publicly exposed or documented since version 5.6 of MyGeotab. It is planned to be removed as a valid parameter in version 5.7.1803. The property `credentials` is the standard supported property that shares the same value.

## 5.7.1712

* API.cs (.Net only) - Fix: When password and session id are supplied to constructor, session id will be used until no longer valid. Previously, session id would only be used if password was not supplied.

* FuelTaxDetail - Added properties: ”IsEnterOdometerInterpolated”, “IsExitOdometerInterpolated”, “HourlyIsOdometerInterpolated”

* User - Removed property: “MenuCollapsedNotified”

## 5.7.1711

* GetAddresses - Added: "hosAddresses" parameter to optionally search for ELD compliant address

* UnitOfMeaure - Added: Kilowatt hours ("UnitOfMeasureKiloWattHoursId")

* SecurityIdentifier - Added "ViewBinaryData", "ManageAddInData", "ViewAddInData"

* HosRuleSet - Added "CarrierExemption"

* .Net SDK samples updated to target netcoreapp2.0

* .Net nuget package now supports framework: netstandard2.0 (removed support for net46)

## 5.7.1709

* API.cs (.Net only) - Added cancellation token parameter to AuthenticateAsync and CallAsync methods.

* DutyStatusLog - Added "Malfunction" property - The DutyStatusMalfunctionType of the DutyStatusLog record. As a flag it can be both a diagnostic and malfunction state which is used to mark status based records (e.g. "D", "SB") as having a diagnostic or malfunction present at time of recording.

* DutyStatusLog - Added "Sequence" property - The sequence number, which is used to generate the sequence ID.

* DutyStatusLogType - Added "EnginePowerup", "EngineShutdown", "EnginePowerupPC", "EngineShutdownPC", "PowerCompliance", "EngineSyncCompliance", "TimingCompliance", "PositioningCompliance", "DataRecordingCompliance", "DataTransferCompliance", "OtherCompliance", "MissingElementCompliance", "UnidentifiedDrivingCompliance", "INT_PC", "INT_D".

* Controller - Added short integer "CodeId" property, which will replace the "Code" property. New "AnyController" for J1708 engine diagnostics to allow replacing those engine diagnostics identical except for the controller with one diagnostic. J1708 engine diagnostics for 58 separate SIDs were updated.

* CustomDevice - Added "VehicleIdentificationNumber" property.

* FuelTaxDetail - Added "Driver" property.

* DriverChangeSearch - Added "IncludeOverlappedChanges" property - A value indicating whether to include the last driver change before the from date or the most recent driver change (if the from date is not provided).

* InvalidUserException - Message changed from to "Incorrect MyGeotab login credentials..." to "Incorrect login credentials...".

### New Objects

* DutyStatusMalfunctionType - Added - Malfunction or Diagnostic type of the DutyStatusLog.

* DutyStatusState - Added - The record status of DutyStatusLog.

## 5.7.1707

* Web Request Notifications: fix {zoneId} and {zoneComment} tokens would not get populated unless {zone} or {address} were also included.

* Documentation: API Reference updated to include default value and max length of object properties in their descriptions. Default values are automatically used when adding an entity and those properties have no value assigned (are null). For example, adding a Group with color = null, will add group with default color "Blue". If a property has no default value, it is required when calling "Add".

* Set operations now retain the value of missing (null) properties. A positive effect of this change is that is remedies a long existing issue that could occur when a server is a newer version (ex 5.7.1704) than client nuget package (ex 5.7.1701) which is making requests to it. The issue could arise when a new Enum value was added and exists only in the server's code base, not client client nuget package. When the unknown Enum was received by the client, it could not be deserialiezed into an Enum value and would throw an exception. Starting in nuget package version 5.7.1707.x, the unknown Enum value will be deserialiezed to null. This means the object can round trip" on "Set" because the server will now (starting at version 5.7.1707) fill in the null value with the existing saved value of the property.

* Added: JsonRpcError, JsonRpcErrorData - to better align JSON-RPC errors with the JSON-RPC 2.0 specification. Non-standard (now legacy) error properties have been deprecated. This should not affect nuget package users as the API.cs object serialized the JSON-RPC error results as Exceptions which are thrown. This may affect users consuming the raw JSON-RPC result of requests. It's recommended to update usages to the official, standardized, properties as outlined in the API Reference. Of note: the new objects exposes "requestIndex" property which is the index at which a "multicall" failed.

* Added: User/Driver objects now have property "IsDriver" to clearly indicate when a user is a driver. This also makes it easier to save a user who is no longer a driver, set the property to false and save.

* Added: FuelTaxDetail - A new entity which provides API access to calculated fuel tax data. In the past this data was only available via the IFTA Report in MyGeotab where it was calculated on the fly. Fuel tax details are now processed using live data and stored in the database and they can be access using the API via Get and GetFeed methods. Full documentation coming soon.

## 5.7.1706

* DatabaseId has been removed from .net package as per the [December 2016 post](https://helpdesk.geotab.com/hc/en-us/community/posts/255601466--NET-SDK-ID-Object-Changes)

* DutyStatusLogType: Added: "Authority"
***requires update of .net nuget package to ensure compatibility***

* FuelTransaction: Added: "ExternalReference"

* FuelTransactionSearch: Added: "ExternalReference" and "Provider"

* User: Added: "AuthorityName" and "AuthorityAddress"

* GetFeed of Trip now includes stop point (woohoo!)
***requires server running 5.7.1706.x**

* [API Clients](https://my112.geotab.com/sdk/#/apiWrappers) section added to SDK documentation

* Geotab.Reflection package no longer a dependency of Geotab.Checkmate.Objectmodel nuget package

## 5.7.1705

* GO8: Added preliminary support for GO8 devices
***requires update of .net nuget package to correctly read/write GO8 devices***

* IoxAddOn: Added preliminary support for IoxAddOn, IoxAddOnSearch, SerialIoxContent,KnownIoxAddOnType, IoxOutputContent, MimeContent

* TextMessageSearch: Added search by: "ParentTextMessageId"

## 5.7.1704

* DutyStatusLog - Added property: State

* DutyStatusLogSearch - Added search by device groups

* API.cs is now compatible with System.Net.Http v4.3.1

* Fix, API.cs proxy support. New constructor that accepts HttpMessageHandler, deprecated constructor that accepts IWebProxy and Proxy property

* Fix, content type of API response headers changed from "text/html" to "application/json"

## 5.7.1703

* DevicePlan: Added: D2GODriverChallengeStandard
***requires update of .net nuget package to ensure compatibility***

* HosRuleSet.cs Added: America7DayNo34h, America8DayNo34h, AmericaShortHaulNo34h, AmericaShortHaul8DayNo34h, BrazilShortHaul
***requires update of .net nuget package to ensure compatibility***

* SecurityRole.cs Added: ReassignData
***requires update of .net nuget package to ensure compatibility***

* TimeZoneId: it was possible to add a user or device with "Unknown" time zone ID. This was only possible using the API and "Unknown" is not returned via the GetTimeZones method or a valid Olson time zone. The ability to add users and devices with "Unknown" as been removed and all users and devices with this time zone ID have been changed to "Etc/GMT"

## 5.7.1702

* FuelTransactionProvider: Added - "Voyager", "UltramarCST"

* SecurityIdentifier: Added - "PurchaseMarketplacePaidItems"
***requires update of .net nuget package to ensure compatibility***

* SecurityRole: Added: "TripTypeChangeInsert", "TripTypeChangeRemove", "CustomReportSendError" 
***requires update of .net nuget package to ensure compatibility***

* Fix: nuget package issue making API requests from Azure WebJob

* Fix: TimeZoneInfoAdjustmentRule serialization (result of GetDaylightSavingRules)

## 5.7.1701

* Added "Hardware" section to SDK

* Nuget: Replace usage of Microsoft.Net.Http with System.Net.Http (WebRequest => HttpClient)

* DiagnosticSearch: Added DiagnosticType property to search by the type of diagnostic. Ex, only GoFault diagnostics.

* Added "ExpiredPasswordException" object. This exception can be thrown if a user makes a request while their ChangePassword flag is true. The user must change their password before they are able to successfully make further requests

* SecurityRole: Added "ReportHosAvailability" 
***requires update of .net nuget package to ensure compatibility***

* If you are using the .net nuget package and plan to use the new "HOS Only" device plan you must update to nuget package version 5.7.1701 or greater to ensure compatibility.

## 5.7.1612

* Id refactoring - The ID object has been refactored in the .NET SDK. See [this forum post](https://helpdesk.geotab.com/hc/en-us/community/posts/255601466--NET-SDK-ID-Object-Changes) for details.

* Updated description of GoCurveAuxiliary (GO4v3, GO6, GO7) properties:
ImmobilizeUnit: With ImmobilizeUnit being true, it is used to define the delay before the driver identification reminder is sent out if the driver key has not been not swiped. The maximum value of this property is 255. When it is less or equal to 180, it indicates the number of seconds of the delay.  When it is greater than 180, the delay increases 30 seconds for every increment of one of this property. For example, 180 indicates 180 seconds, 181 indicates 210 seconds, and 182 indicates 240 seconds.
ImmobilizeArming: A value mainly used for enable or disable driver identification reminder. If it is used in conjunction with vehicle relay circuits, it can force the driver to swipe the driver key before starting the vehicle.

## 5.7.1611

* Authentication rate limiting being phased in. See this [Blog Post](https://www.geotab.com/blog/api-call-limits/) for more details. Added "Rate Limiting" section to SDK [Concepts](https://my.geotab.com/sdk/default.html#/concepts).

* KnownId - Added: "DiagnosticDieselExhaustFluidId", ”DiagnosticDieselParticulateFilterLampId”, “DiagnosticPowerTakeoffEngagedId”, “DiagnosticPowerTakeoffTotalFuelUsedId”

* KnownId - Removed: "DiagnosticBluetoothBeaconOutOfRangeId"

* Trailer - Added "Groups" property. Trailers can now be added to groups.

* TrailerSearch - Added property groups. Search for Trailers that are members of these GroupSearch(s) one of it's children or one of it's parents.

* *SecurityIdentifier - Added: "RepairDVIR"

*Important: Update .Net [nuget](https://www.nuget.org/packages/Geotab.Checkmate.ObjectModel/) package to ensure compatibility

## 5.7.1610

* KnownId - Added: "DiagnosticDieselExhaustFluidId”, "DiagnosticDieselParticulateFilterLampId”, “DiagnosticPowerTakeoffEngagedId”, “DiagnosticPowerTakeoffTotalFuelUsedId”

* HosRuleSet - Added: "Florida7Day”, "Florida8Day”, “FloridaShortHaul7Day”, “FloridaShortHaul8Day”

### New Objects

* OverLimitException:
Thrown when a user has exceeded the query limit of an API (currently only applies to authentication). Previously, if a user reached this limit, an InvalidUserException would have been thrown.

## 5.7.1609

* KnownId - "DiagnosticRamFailure" name fixed to be “DiagnosticRamFailureId”

## 5.7.1608

* MessageContentType - Added: "DriverWhiteList"

* DutyStatusLogType - Added: "PC" (Personal conveyance driver status), “YM” (Yard move driver status), “WT” (Wait time oil well driver status).

* FuelTransaction - Added "ProductType" property.

* FuelTransactionProvider - Added "WexLegacy", “Fuelman” and “Comdata”.

* GoDevice - Added "GoTalkLanguage" property.

* User - Added "IsYardMoveEnabled" and "IsPersonalConveyanceEnabled" properties.

* HosRuleSet - Added "OilWell7Day", “OilWell7DayBig”, “OilWell8Day”, “OilWell8DayBig”, “AmericaTexas”, “AmericaTexasShortHaul”, “OilTransportTexas”, “OilWellTexas”, “AmericaShortHaul8Day”, “AmericaShortHaulPassenger8Day”, “OilTransportShortHaul8Day”, “AmericaTexasShortHaul8Day”

* KnownId - Added "DiagnosticSystemAlertId"

* TimeZoneInfo - Adjusted to support recently updated Windows times zones and the latest version of [IANA/Windows](http://www.unicode.org/cldr/charts/dev/supplemental/zone_tzid.html) maped time zones. [Click here for more info](https://docs.google.com/document/d/1kjIhyqpgOg1wNHi3JkvV7uXVBzhl5stlZZxIVjXs1Fc/edit#)

### New Objects

* DriverWhiteListContent

* GoTalkLanguage

* FuelTransactionProductType

For detailed information on new features please review the API Reference.

**.Net users will require a dll update*

## 5.7.1607

* Performance and maintenance enhancements.

## 5.7.1606

* DiagnosticTypes - Added "GoFault"

* FuelTransactionProvider - Added "WexCustomer", "Drive" and "FuelTracker"

* SecurityIdentifier - Added "EventOccurrenceList","ViewCertificates","ManageCertificates"

* HosRuleSet - Added "AmericaSalesperson"

* .Net: MachineSettings - Fix to work with ASP.Net Web API projects

* .Net: DataToComponenet - Updated "Equals" method to compare payloads for equality

* .Net: DutyStatusOrigin - removed unused "Serializable" attribute

* .Net - Changes in API.cs to use HttpClient instead of HttpWebRequest in order to support .Net core in the future.

* dll requires .Net Framework version v4.6+

### New APIs

* GetDirections

* OptimizeWaypoints

### New Objects

* Directions

* Leg

* Step

* Waypoint

**.Net users will require a dll update*

## 5.7.1605

*  Added new Units of Measure (km/L, kg/km, L/lane km, L/ton and g/m^2)
** .Net users will require a dll update*

## 5.7.1604

* For security reasons, TLS 1.2 is being enforced on all servers. To fix the integration, please update to at least .NET 4.5 and use the [latest nuget package](https://www.nuget.org/packages/Geotab.Checkmate.ObjectModel/). For more information, please visit the [forum discussion](https://helpdesk.geotab.com/entries/108236723-TLS1-2-Upgrade-Notice).

* Driver has a new property: viewDriversOwnDataOnly. When set to true, a driver gains the ability to view their own driving data.
** .Net users will require a dll update*

## 5.7.1602

* TextToSpeechContent has been renamed to GoTalkContent and RelayContent has been renamed to IoxOutputContent
** .Net users will require a dll update*

## 5.7.1601

* New recipient types added that will send even if there is a delay in data. (BeepTenTimesRapidlyAllowDelay, BeepThreeTimesAllowDelay, BeepThreeTimesRapidlyAllowDelay , TextToSpeechAllowDelay)
** .Net users will require a dll update*

* Access to third party messages via API.
** .Net users will require a dll update*

### New Objects

* IoxAddOn

* KnownIoxAddOnType

* IoxAddOnSearch

* IoxOutputContent

* GoTalkContent

## 5.7.1512

* Fixed operator overloading for Id object in .Net dll (id1 == id2 is the same as id1.Equals(id2)) - **If you are using dll version 5.7.1508-1511 this will require a dll update.*

* New addin: Trips Streetview added to [GitHub](https://github.com/Geotab/addin-trips-streetview)

## 5.7.1511

* Added new security clearances for:

    * ViewMarketplacePaidItems:  Allow user to see paid Marketplace items

    * DeviceAdminDeleteUnplugReplace: Access to removing vehicle, unpluging device, and replacing device.

**If you are using dll version 5.7.1508-1510 this will require a dll update.*

## 5.7.1509

* New SDK.  Featuring the new [SDK Runner](https://geotab.github.io/sdk/software/api/runner.html), new methods and objects (click [here](https://geotab.github.io/sdk/software/api/reference/) to see the preview items)

* Code snippets in the reference documentation.  Now you can see working examples of the methods as they are used in the runner.

* .Net users will require a .DLL update to access the latest features.

### New Methods

* CreateDatabase

* DatabaseExists

* GenerateCaptcha

* GetVersionInformation

### New Objects

* AnnotationLog

* AnnotationLogSearch

* CaptchaAnswer

* CaptchaException

* Color

* CompanyDetails

* DVIRLog

* DVIRLogSearch

* DiagnosticCategory

* DistributionList

* DuplicateException

* DutyStatusAvailability

* DutyStatusAvailabilityDuration

* DutyStatusAvailablitySearch

* DutyStatusLog

* DutyStatusLogSearch

* DutyStatusLogType

* DutyStatusViolation

* DutyStatusViolationSearch

* DutyStatusViolationType

* EntityWithVersion

* FuelEconomyUnit

* FuelEvent

* FuelTransaction

* FuelTransactionProvider

* HosRuleSet

* IncludeGroups

* InvalidMyAdminUserException

* MapView

* NameEntity

* NameEntityWithVersion

* RadioDownloaderSearch

* Recipient

* RecipientType

* RegistrationException

* Search

* ShipmentLog

* ShipmentLogSearch

* TextMessageContentType

* Trailer

* TrailerAttachment

* TrailerAttachmentSearch

* TrailerSearch

* VersionInformation

* VolumeUnit

### Deprecated

* BingMapStyle

* EngineType

* EngineTypeSearch

* StatusDataRequestContent

## 5.7.1508

* DriverChangeSearch received new search points including: DeviceSearch, DriverSearch, FromDate and ToDate. Checkout the [API Reference](https://my.geotab.com/sdk/default.html#/api) for more details

* DistributionList is now supported by the API. Checkout the [API Reference](https://my.geotab.com/sdk/default.html#/api) for more details. Some related objects are still pending support (Notification, NotificationTemplate, BinaryData)

* [Add-In examples](https://my.geotab.com/sdk/default.html#/addinExamples) have been added to SDK documentation

* When searching for Zones you can now specify a traversal method of the group tree. You can choose to include just the specified element, just the ancestors, just the descendents, or both ancestors and descendents. See the ZoneSearch object in the [API Reference](https://my.geotab.com/sdk/default.html#/api) for more details

* Fix documentation for object properties

* Added KnownIds: DiagnosticDeviceTotalIdleFuel

* Added FuelTransaction API (*Beta*)

* HOS/DVIR objects supported in API. Key objects are AnnotationLog, DVIRLog, DutyStatusAvailability, DutyStatusLog, DutyStatusViolation, and ShipmentLog. Check out the [API Reference](https://my.geotab.com/sdk/default.html#/api) for more details

* Added Groups property to StatusDataSearch. This allows searching for status data for devices in the supplied groups. This does not return interpolated results

* Added from/to date search to UserSearch object. Checkout the [API Reference](https://my.geotab.com/sdk/default.html#/api) for more details

* [API Reference](https://www.geotab.com/dev-channel/), objects now show properties of from inherited classes. For example GoDevice extends Device and will show properties of GoDevice and Device in the documentation

* Geotab Announces New [DEV Channel](https://www.geotab.com/dev-channel/) for Developers

## 5.7.1505

* New condition types added - .Net will require dll update

## 5.7.1504

* Add KnownId for DiagnosticDeviceTotalIdleFuelId - .Net will require dll update

## 5.7.1502

* Get *all* zones now populating points correctly ([see forum post](https://helpdesk.geotab.com/entries/26004844-Get-Zone-return-distinct-points))

* Fixed TimeZoneInfo isDaylightSavingsSupported always false using .Net API client

* Units of measure have been converted to use Known Id’s ([see forum post](https://helpdesk.geotab.com/entries/52897090-MyGeotab-SDK-Update-KnownId))

* Adding, setting and removing of some entities has been disabled via the API. Exception Event, Trip, Status Data, Fault Data, Log Record with exceptions for adding odometer and engine hours adjustments and dismissing faults

* Clearer documentation of date and long values in [API Reference](https://my.geotab.com/sdk/default.html#/api)

* Data Feed section added to Guides portion of SDK ([see document](https://docs.google.com/document/d/1LJfb57qyBX2WklnqioHtlWkYN9xKBWxA_FIpaJzjKyY/edit))