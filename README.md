# ![LOGO](logo.png) AGCO API **flow**ground Connector

## Description

A generated **flow**ground connector for the AGCO API API (version v1).

Generated from: https://api.apis.guru/v2/specs/agco-ats.com/v1/swagger.json<br/>
Generated at: 2019-05-07T17:34:51+03:00

## API Description



## Authorization

This API does not require authorization.

## Actions

### No Documentation Found.

*Tags:* `AftermarketServices`

### Activate or Deactivate an ECU, or Report an ECU as Damaged.

> No Documentation Found.

*Tags:* `AftermarketServices`

#### Input Parameters
* `serialNumber` - _required_ - The serial number of the ECU.
* `EDTInstanceId` - _required_ - The EDT Instance Id of the kit calling this method.

### Get injector codes given engine.

> No Documentation Found.

*Tags:* `AftermarketServices`

#### Input Parameters
* `serialNumber` - _required_ - The serial number of the engine.
* `EDTInstanceId` - _required_ - The EDT Instance Id of the kit calling this method.

### Report the IQA codes used by an engine

> No Documentation Found.

*Tags:* `AftermarketServices`

#### Input Parameters
* `serialNumber` - _required_ - The serial number of the Engine
* `EDTInstanceId` - _required_ - The EDT Instance Id of the kit calling this method.

### Get production calibration data for given engine.

> No Documentation Found.

*Tags:* `AftermarketServices`

#### Input Parameters
* `serialNumber` - _required_ - The serial number of the engine.
* `EDTInstanceId` - _required_ - The EDT Instance Id of the kit calling this method.

### Check whether there is connectivity to AGCO Power Web Services

> No Documentation Found.

*Tags:* `AftermarketServices`

### Retrieve the status of an EDT Kit Registration with AGCO Power Web Services

> No Documentation Found.

*Tags:* `AftermarketServices`

#### Input Parameters
* `voucherCode` - _required_
* `dealerCode` - _required_

### Update the status of an EDT Kit Registration with AGCO Power Web Services

> No Documentation Found.

*Tags:* `AftermarketServices`

### Manage API tokens.

> No Documentation Found.

*Tags:* `Authentication`

#### Input Parameters
* `UserID` - _required_

### Authenticate a user.

> No Documentation Found.

*Tags:* `Authentication`

### Acknowledges the connection to the API

> No Documentation Found.

*Tags:* `Authentication`

### Request a password reset.

> No Documentation Found.

*Tags:* `Authentication`

### Reset a password

> No Documentation Found.

*Tags:* `Authentication`

### Get authorization code definitions.

> Additional searches: validationFields[Name]=true and dataFields[Name]=true. These can be used to search for authorization code definitions that have the specified data or validation fields.

*Tags:* `AuthorizationCodeDefinitions`

#### Input Parameters
* `limit` - _optional_ - Optional. The page limit.  If not specified, the default page limit is 10.
* `offset` - _optional_ - Optional. The page offset.  If not specified, the default page offset is 0.
* `name` - _optional_ - Optional. If specified, filters definitions by name. Starting and ending wildcards (*) supported.
* `createdByUserID` - _optional_ - Optional. If specified, filters definitions to those created by the given User ID.
* `deletedByUserID` - _optional_ - Optional. If specified, filters definitions to those deleted by the given User ID.
* `includeDeleted` - _optional_ - Optional. Whether to include deleted definitions. 'False' by default.

### Add an authorization code definition.

> No Documentation Found.

*Tags:* `AuthorizationCodeDefinitions`

### Disable an authorization code definition

> No Documentation Found.

*Tags:* `AuthorizationCodeDefinitions`

#### Input Parameters
* `id` - _required_ - The ID of the authorization code definition.

### Get an authorization code definition by its ID

> No Documentation Found.

*Tags:* `AuthorizationCodeDefinitions`

#### Input Parameters
* `id` - _required_ - The ID of the authorization code definition.

### Update an authorization code definition

> No Documentation Found.

*Tags:* `AuthorizationCodeDefinitions`

#### Input Parameters
* `id` - _required_ - The ID of the authorization code definition.

### Get authorization codes.

> Additional searches: validationParameters[Name]=Value and dataParameters[Name]=Value. These can be used to search for authorization codes that have been generated using specified values for data or validation parameters.

*Tags:* `AuthorizationCodes`

#### Input Parameters
* `code` - _optional_ - Optional. If provided, searches for entities with the provided authorization code.
* `limit` - _optional_ - Optional. The page limit.  If not specified, the default page limit is 10.
* `offset` - _optional_ - Optional. The page offset.  If not specified, the default page offset is 0.
* `definitionID` - _optional_ - Optional. If specified, filters codes by definition id.
* `createdByUserID` - _optional_ - Optional. If specified, filters codes to those created by the given User ID.
* `deletedByUserID` - _optional_ - Optional. If specified, filters codes to those deleted by the given User ID.
* `includeDeleted` - _optional_ - Optional. Whether to include deleted codes. 'False' by default.

### Generates an authorization code using the provided definition and parameters.

> No Documentation Found.

*Tags:* `AuthorizationCodes`

### Hide an authorization code.

> No Documentation Found.

*Tags:* `AuthorizationCodes`

#### Input Parameters
* `id` - _required_ - The id of the authorization code.

### Get an authorization code by its ID.

> No Documentation Found.

*Tags:* `AuthorizationCodes`

#### Input Parameters
* `id` - _required_ - The id of the authorization code.

### Update an authorization code.

> No Documentation Found.

*Tags:* `AuthorizationCodes`

#### Input Parameters
* `id` - _required_ - The id of the authorization code.

### Gets a list of Brands.

> No Documentation Found.

*Tags:* `Brands`

### Get the list of bundles.

> No Documentation Found.

*Tags:* `Bundles`

#### Input Parameters
* `UpdateGroupID` - _optional_ - Optional. Filter by UpdateGroup ID.
* `Active` - _optional_ - Optional. Filter by active status.
* `limit` - _optional_ - Optional. The page limit. The default page limit is 10.
* `offset` - _optional_ - Optional. The page offset. The default page offset is 0.

### Add a Bundle to the Update System.

> No Documentation Found.

*Tags:* `Bundles`

### Delete a Bundle.

> No Documentation Found.

*Tags:* `Bundles`

#### Input Parameters
* `ID` - _required_ - The Bundle ID to Delete

### Get a specific Bundle by ID.

> No Documentation Found.

*Tags:* `Bundles`

#### Input Parameters
* `ID` - _required_ - The Bundle ID

### Modify a Bundle in the Update System.

> No Documentation Found.

*Tags:* `Bundles`

#### Input Parameters
* `ID` - _required_ - The unique ID of the Bundle

### Get a List of Clients in the Update System.

> No Documentation Found.

*Tags:* `Clients`

#### Input Parameters
* `Tag` - _optional_ - Optional. Filter clients by Tag. Wildcards are supported (*).
* `limit` - _optional_ - Optional. The page limit. The default page limit is 10.
* `offset` - _optional_ - Optional. The page offset. The default page offset is 0.

### Get a list of Cached Files installed on the client Machine.

> No Documentation Found.

*Tags:* `UpdateSystem`

#### Input Parameters
* `ClientID` - _required_ - The ClientID of the Client
* `Expired` - _required_ - Only Expired Files (true|false)

### Get the package reports for a client.

> No Documentation Found.

*Tags:* `PackageReports`

#### Input Parameters
* `ClientID` - _required_ - The Client ID

### Submit a package report

> No Documentation Found.

*Tags:* `PackageReports`

#### Input Parameters
* `ClientID` - _required_ - The Client ID

### Submit a batch of package reports

> No Documentation Found.

*Tags:* `PackageReports`

#### Input Parameters
* `ClientID` - _required_ - The Client ID

### Get a Client in the Update System.

> No Documentation Found.

*Tags:* `Clients`

#### Input Parameters
* `ID` - _required_ - The Client ID

### Update a Client.

> No Documentation Found.

*Tags:* `Clients`

#### Input Parameters
* `ID` - _required_ - The Client ID

### Get a Client's Available Update Group Subscriptions

> No Documentation Found.

*Tags:* `Clients`

#### Input Parameters
* `ID` - _required_ - The Client ID
* `UpdateGroupID` - _optional_ - Optional. Filter by Update Group.
* `limit` - _optional_ - Optional. The page limit. The default page limit is 10.
* `offset` - _optional_ - Optional. The page offset. The default page offset is 0.

### Get a Client's Current Update Group Subscriptions

> No Documentation Found.

*Tags:* `Clients`

#### Input Parameters
* `ID` - _required_ - The Client ID
* `UpdateGroupID` - _optional_ - Optional. Filter by Update Group.
* `limit` - _optional_ - Optional. The page limit. The default page limit is 10.
* `offset` - _optional_ - Optional. The page offset. The default page offset is 0.

### Get ContentDefinitions

> Gets a collection of ContentDefinitions. When successful, the response is a PagedResponse of ContentDefinitions.<br/>
>             If unsuccessful, an appropriate ApiError is returned.

*Tags:* `ContentDefinitions`

#### Input Parameters
* `limit` - _optional_ - Optional. The page limit.  If not specified, the default page limit is 10.
* `offset` - _optional_ - Optional. The page offset.  If not specified, the default page offset is 0.
* `userID` - _optional_ - Optional. Filter by UserID.

### Create a ContentDefinition

> Creates a ContentDefinition.  The body of the POST is the ContentDefinition to create.<br/>
>             The ContentDefinitionID will be assigned on creation of the Job.  When successful, the response<br/>
>             is the JobID.  If unsuccessful, an appropriate ApiError is returned.

*Tags:* `ContentDefinitions`

### Delete a ContentDefinition

> Deletes an ContentDefinition. When successful, the response is empty.  If unsuccessful, an appropriate<br/>
>             ApiError is returned.

*Tags:* `ContentDefinitions`

#### Input Parameters
* `contentDefinitionID` - _required_ - The ID of the ContentDefinition to delete

### Get a ContentDefinition by ID

> Gets a ContentDefinition by ID. When successful, the response is the requested ContentDefinition.<br/>
>             If unsuccessful, an appropriate ApiError is returned.

*Tags:* `ContentDefinitions`

#### Input Parameters
* `contentDefinitionID` - _required_ - The ID of the ContentDefinition to get.

### Update a ContentDefinition

> Updates a ContentDefinition.  The body of the PUT is the updated ContentDefinition.  <br/>
>             When successful, the response is empty.  If unsuccessful, an appropriate ApiError is returned.

*Tags:* `ContentDefinitions`

#### Input Parameters
* `contentDefinitionID` - _required_ - The ID of the ContentDefinition to update

### Get ContentReleaseVersion

> Gets a collection of ContentReleaseVersion. When successful, the response is a PagedResponse of ContentReleaseVersion.<br/>
>             If unsuccessful, an appropriate ApiError is returned.

*Tags:* `ContentRelease`

#### Input Parameters
* `limit` - _optional_ - Optional. The page limit.  If not specified, the default page limit is 10.
* `offset` - _optional_ - Optional. The page offset.  If not specified, the default page offset is 0.
* `deleted` - _optional_ - Optional. Filter by deleted.
* `releaseID` - _optional_ - Optional. Filter by releaseID.
* `userId` - _optional_ - Optional. Filter by UserID.
* `contentDefinitionID` - _optional_ - Optional. Filter by ContentDefinitionID.
* `version` - _optional_ - Optional. Filter by Version.

### Create a ContentReleaseVersion

> Creates a ContentReleaseVersion.  The body of the POST is the ContentReleaseVersion to create.<br/>
>             The ContentReleaseId will be assigned on creation of the Job.  When successful, the response<br/>
>             is the contentReleaseId.  If unsuccessful, an appropriate ApiError is returned.

*Tags:* `ContentRelease`

### Delete a ContentReleaseVersion

> Deletes an ContentReleaseVersion. When successful, the response is empty.  If unsuccessful, an appropriate<br/>
>             ApiError is returned.

*Tags:* `ContentRelease`

#### Input Parameters
* `ContentReleaseId` - _required_ - The ID of the ContentReleaseVersion to delete

### Get a Content Release Version by ID

> Gets a ContentReleaseVersion by ID. When successful, the response is the requested ContentReleaseVersion.<br/>
>             If unsuccessful, an appropriate ApiError is returned.

*Tags:* `ContentRelease`

#### Input Parameters
* `ContentReleaseId` - _required_ - The ID of the ContentReleaseVersion to get.

### Update a ContentReleaseVersion

> Updates a ContentReleaseVersion.  The body of the PUT is the updated ContentReleaseVersion.  <br/>
>             When successful, the response is empty.  If unsuccessful, an appropriate ApiError is returned.

*Tags:* `ContentRelease`

#### Input Parameters
* `ContentReleaseId` - _required_ - The ID of the ContentReleaseVersion to update

### Returns available Content Submission Types.

> No Documentation Found.

*Tags:* `ContentSubmissionTypes`

#### Input Parameters
* `enabled` - _optional_

### Add a Content Submission Type

> No Documentation Found.

*Tags:* `ContentSubmissionTypes`

### Remove a Content Submission Type

> No Documentation Found.

*Tags:* `ContentSubmissionTypes`

#### Input Parameters
* `id` - _required_ - The ID of the Content Submission Type

### Retrieves a Content Submission Type by its ID.

> No Documentation Found.

*Tags:* `ContentSubmissionTypes`

#### Input Parameters
* `id` - _required_ - The ID of the Content Submission Type

### Update a Content Submission Type

> No Documentation Found.

*Tags:* `ContentSubmissionTypes`

#### Input Parameters
* `id` - _required_ - The ID of the Content Submission Type

### Get ContentSubmissions

> Gets a collection of ContentSubmissions. When successful, the response is a PagedResponse of ContentSubmissions.<br/>
>             If unsuccessful, an appropriate ApiError is returned.

*Tags:* `ContentSubmissions`

#### Input Parameters
* `limit` - _optional_ - Optional. The page limit.  If not specified, the default page limit is 10.
* `offset` - _optional_ - Optional. The page offset.  If not specified, the default page offset is 0.
* `userID` - _optional_ - Optional. Filter by UserID.
* `contentDefinitionID` - _optional_ - Optional. Filter by ContentDefinitionID

### Create a ContentSubmission

> Creates a ContentSubmission.  The body of the POST is the ContentSubmission to create.<br/>
>             The ContentSubmissionID will be assigned on creation of the Job.  When successful, the response<br/>
>             is the ContentSubmissionID.  If unsuccessful, an appropriate ApiError is returned.

*Tags:* `ContentSubmissions`

### Delete a ContentSubmission

> Deletes an ContentSubmission. When successful, the response is empty.  If unsuccessful, an appropriate<br/>
>             ApiError is returned.

*Tags:* `ContentSubmissions`

#### Input Parameters
* `contentSubmissionID` - _required_ - The ID of the ContentSubmission to delete

### Get a ContentSubmission by ID

> Gets a ContentSubmission by ID. When successful, the response is the requested ContentSubmission.<br/>
>             If unsuccessful, an appropriate ApiError is returned.

*Tags:* `ContentSubmissions`

#### Input Parameters
* `contentSubmissionID` - _required_ - The ID of the ContentSubmission to get.

### Update a ContentSubmission

> Updates a ContentSubmission.  The body of the PUT is the updated ContentSubmission.  <br/>
>             When successful, the response is empty.  If unsuccessful, an appropriate ApiError is returned.

*Tags:* `ContentSubmissions`

#### Input Parameters
* `contentSubmissionID` - _required_ - The ID of the ContentSubmission to update

### Get a total count of dealers per country

> No Documentation Found.

*Tags:* `DealerByCountry`

#### Input Parameters
* `limit` - _optional_ - Optional. The page limit. The default page limit is 10.
* `offset` - _optional_ - Optional. The page offset. The default page offset is 0.

### Get a list of dealers.

> No Documentation Found.

*Tags:* `Dealers`

#### Input Parameters
* `Brand` - _optional_ - The brand to filter by.
* `ShippingCountry` - _optional_ - The country to filter by.
* `DealerName` - _optional_ - The partial Dealer Name to filter by. Wildcard supported (*).
* `limit` - _optional_ - Optional. The page limit. The default page limit is 10.
* `offset` - _optional_ - Optional. The page offset. The default page offset is 0.

### Lookup a dealer using a dealer code.

> No Documentation Found.

*Tags:* `Dealers`

#### Input Parameters
* `DealerCode` - _required_ - The Dealer Code to Search for

### Create a license activation.

> No Documentation Found.

*Tags:* `LicenseActivations`

### Register an EDT Lite with the Server

> No Documentation Found.

*Tags:* `LicenseActivations`

### Update a license activiation.

> No Documentation Found.

*Tags:* `LicenseActivations`

#### Input Parameters
* `ID` - _required_ - The ID of the license.

### Confirm that the client has applied the updated license.

> No Documentation Found.

*Tags:* `LicenseActivations`

#### Input Parameters
* `ID` - _required_ - The ID of the license

### Gets a list of licenses with the specified criteria.

> No Documentation Found.

*Tags:* `Licenses`

#### Input Parameters
* `VoucherCode` - _optional_ - Optional. Filter by VoucherCode
* `DealerCode` - _optional_ - Optional. Filter by DealerCode
* `Status` - _optional_ - Optional. Filter by Status.  By default only active licenses will be returned.
    Possible values: Active, Inactive, All.
* `limit` - _optional_ - Optional. The page limit. The default page limit is 10.
* `offset` - _optional_ - Optional. The page offset. The default page offset is 0.

### Get a license.

> No Documentation Found.

*Tags:* `Licenses`

#### Input Parameters
* `ID` - _required_ - The ID of the license to get.

### Get the API System logs, most recent first.

> No Documentation Found.

*Tags:* `Logs`

#### Input Parameters
* `limit` - _optional_ - Optional. The page limit. The default page limit is 10.
* `offset` - _optional_ - Optional. The page offset. The default page offset is 0.

### Add a Log entry

> No Documentation Found.

*Tags:* `Logs`

#### Input Parameters
* `Message` - _required_ - Message to enter into the log

### Get a log by ID

> No Documentation Found.

*Tags:* `Logs`

#### Input Parameters
* `ID` - _required_ - The Log ID

### Sends an email message.

> No Documentation Found.

*Tags:* `Notifications`

### Get all of the Package Types.

> No Documentation Found.

*Tags:* `PackageTypes`

#### Input Parameters
* `limit` - _optional_ - Optional. The page limit. The default page limit is 10.
* `offset` - _optional_ - Optional. The page offset. The default page offset is 0.

### Add a Package Type.

> No Documentation Found.

*Tags:* `PackageTypes`

### Delete a Package Type.

> No Documentation Found.

*Tags:* `PackageTypes`

#### Input Parameters
* `ID` - _required_ - The Package Type ID

### Get a specific Package Type.

> No Documentation Found.

*Tags:* `PackageTypes`

#### Input Parameters
* `ID` - _required_ - The Package Type ID

### Modify a Package Type.

> No Documentation Found.

*Tags:* `PackageTypes`

#### Input Parameters
* `ID` - _required_ - The ID of the Package Type

### Delete a Package Type to Bundle Relationship.

> No Documentation Found.

*Tags:* `PackageTypetoBundles`

#### Input Parameters
* `BundleID` - _required_ - The BundleID
* `PackageTypeID` - _required_ - The PackageTypeID

### Get all of the Package Type to Bundle Relationships.

> No Documentation Found.

*Tags:* `PackageTypetoBundles`

#### Input Parameters
* `BundleID` - _optional_ - Optional. Filter by BundleID.
* `limit` - _optional_ - Optional. The page limit. The default page limit is 10.
* `offset` - _optional_ - Optional. The page offset. The default page offset is 0.

### Add a new Package Type ID to Bundle Relationship.

> No Documentation Found.

*Tags:* `PackageTypetoBundles`

### Update a Package Type ID to Bundle Relationship.

> No Documentation Found.

*Tags:* `PackageTypetoBundles`

### List Packages.

> No Documentation Found.

*Tags:* `Packages`

#### Input Parameters
* `limit` - _optional_ - Optional. The page limit. The default page limit is 10.
* `offset` - _optional_ - Optional. The page offset. The default page offset is 0.

### Add a Packge to the Update System.

> No Documentation Found.

*Tags:* `Packages`

### Delete a Package.

> No Documentation Found.

*Tags:* `Packages`

#### Input Parameters
* `ID` - _required_ - The Package ID to Delete

### Find a Package.

> No Documentation Found.

*Tags:* `Packages`

#### Input Parameters
* `ID` - _required_ - The Package ID to Search for

### Modify a Packge to the Update System.

> No Documentation Found.

*Tags:* `Packages`

#### Input Parameters
* `ID` - _required_ - The unique ID of the Package

### List Permissions

> No Documentation Found.

*Tags:* `Permissions`

#### Input Parameters
* `limit` - _optional_ - Optional. The page limit. The default page limit is 10.
* `offset` - _optional_ - Optional. The page offset. The default page offset is 0.
* `name` - _optional_ - Filter by permission name. Supports ending wildcard (*). Optional.

### Adds a Permission

> No Documentation Found.

*Tags:* `Permissions`

### Deletes a Permission

> No Documentation Found.

*Tags:* `Permissions`

#### Input Parameters
* `id` - _required_ - Id of Permission

### Gets a Permission

> No Documentation Found.

*Tags:* `Permissions`

#### Input Parameters
* `id` - _required_ - Id of Permission

### Updates a Permission

> No Documentation Found.

*Tags:* `Permissions`

#### Input Parameters
* `id` - _required_ - Id of Permission

### Get a list of Priority Packages by Client.

> No Documentation Found.

*Tags:* `PriorityPackages`

#### Input Parameters
* `ClientID` - _optional_ - Optional. Filter priority packages by ClientID.
* `Status` - _optional_ - Optional. Filter returned packages by status. By default only active packages will be returned.
    Possible values: Active, Completed, All.
* `limit` - _optional_ - Optional. The page limit. The default page limit is 10.
* `offset` - _optional_ - Optional. The page offset. The default page offset is 0.

### Add a Priority Package for a Client.

> No Documentation Found.

*Tags:* `PriorityPackages`

### Delete a Priority Package for a Client.

> No Documentation Found.

*Tags:* `PriorityPackages`

#### Input Parameters
* `ID` - _required_ - The Priority Package ID

### Get a Priority Packages for a Client.

> No Documentation Found.

*Tags:* `PriorityPackages`

#### Input Parameters
* `ID` - _required_ - The Priority Package ID

### Get Release

> Gets a collection of Release. When successful, the response is a PagedResponse of Release.<br/>
>             If unsuccessful, an appropriate ApiError is returned.

*Tags:* `Release`

#### Input Parameters
* `limit` - _optional_ - Optional. The page limit.  If not specified, the default page limit is 10.
* `offset` - _optional_ - Optional. The page offset.  If not specified, the default page offset is 0.
* `visible` - _optional_ - Optional. Filter by visible.

### Create a Release

> Creates a Release.  The body of the POST is the Release to create.<br/>
>             The ReleaseId will be assigned on creation of the Job.  When successful, the response<br/>
>             is the Release Id.  If unsuccessful, an appropriate ApiError is returned.

*Tags:* `Release`

### Get a  Release by ID

> Gets a Release by ID. When successful, the response is the requested Release.<br/>
>             If unsuccessful, an appropriate ApiError is returned.

*Tags:* `Release`

#### Input Parameters
* `ReleaseId` - _required_ - The ID of the Release to get.

### Update a Release

> Updates a Release.  The body of the PUT is the updated Release.  <br/>
>             When successful, the response is empty.  If unsuccessful, an appropriate ApiError is returned.

*Tags:* `Release`

#### Input Parameters
* `releaseId` - _required_ - The ID of the Release to update

### Get a summary of all Packages in a Bundle

> No Documentation Found.

*Tags:* `Reporting`

#### Input Parameters
* `BundleID` - _required_ - The BundleID
* `limit` - _optional_ - Optional. The page limit. The default page limit is 10.
* `offset` - _optional_ - Optional. The page offset. The default page offset is 0.

### Get a list of bundles for UpdateGroup.

> No Documentation Found.

*Tags:* `Reporting`

#### Input Parameters
* `ID` - _required_ - The UpdateGroupID
* `IncludeInactive` - _required_ - Include Inactive Bundles (true|false)
* `limit` - _optional_ - Optional. The page limit. The default page limit is 10.
* `offset` - _optional_ - Optional. The page offset. The default page offset is 0.

### Get Client Information

> No Documentation Found.

*Tags:* `Reporting`

#### Input Parameters
* `ClientID` - _required_ - The Client ID

### Get the current packages for an update group.

> No Documentation Found.

*Tags:* `Reporting`

#### Input Parameters
* `ID` - _required_ - The UpdateGroupID
* `SubscriptionTypeFilter` - _optional_ - Optional.  The subscription type filter to use.  By default the Default packages (Required and IncludeByDefault) will be returned.
    Possible values: RequiredOnly, Default, All.

### Get a Client in the Update System.

> No Documentation Found.

*Tags:* `Reporting`

#### Input Parameters
* `ID` - _required_ - The Client ID

### Get a list of current Client Subscriptions.

> No Documentation Found.

*Tags:* `Reporting`

#### Input Parameters
* `ClientID` - _optional_ - Optional. Filter by Client ID
* `UpdateGroupID` - _optional_ - Optional. Filter by Update Group ID
* `limit` - _optional_ - Optional. The page limit. The default page limit is 10.
* `offset` - _optional_ - Optional. The page offset. The default page offset is 0.

### Get a summary report for a Specific Package

> No Documentation Found.

*Tags:* `Reporting`

#### Input Parameters
* `PackageID` - _required_ - The Package ID

### Get a list of subscribed clients

> No Documentation Found.

*Tags:* `Reporting`

#### Input Parameters
* `UpdateGroupID` - _optional_ - Optional. The Update Group ID. If not provided, all clients will be returned.
* `ClientID` - _optional_ - Optional. Filter where ClientID matches a value. Wildcards are supported (*).
* `Tag` - _optional_ - Optional. Filter where Tag matches a value. Wildcards are supported (*).
* `ReportResult` - _optional_ - Optional. Filter where ReportResult matches a value. Wildcards are supported (*).
* `ReportResultIsValid` - _optional_ - Optional. When 'true' filters results where ReportResult equals ReportResultExpected.  When 'false' filters results where ValueToValidate does not equal ReportResults.
* `ReportValue` - _optional_ - Optional. Filter where ReportValue matches a value. Wildcards are supported (*).
* `LastCheckInBefore` - _optional_ - Optional. Filter where LastCheckIn occured before the provided date.
* `LastCheckInAfter` - _optional_ - Optional. Filter where LastCheckIn occured after the provided date.
* `OrderBy` - _optional_ - Optional. Specify the order in which results should be returned. Use this format: [FieldName] [ASC|ASCENDING|DESC|DESCENDING],...   
            If sort direction is not provided for a field, it will be sorted ascending.
* `limit` - _optional_ - Optional. The page limit. The default page limit is 10.
* `offset` - _optional_ - Optional. The page offset. The default page offset is 0.

### Get a list of Update Groups.  Update Groups are used by the client to register for a specific type of update.

> No Documentation Found.

*Tags:* `Reporting`

#### Input Parameters
* `limit` - _optional_ - Optional. The page limit. The default page limit is 10.
* `offset` - _optional_ - Optional. The page offset. The default page offset is 0.

### Get data for pie charts in UpdateMetrics.

> No Documentation Found.

*Tags:* `Reporting`

#### Input Parameters
* `UpdateGroupID` - _required_ - The UpdateType in which clients must be for the report to include them.
* `bundleNumber` - _optional_ - Optional. Tells us which chart to show based upon filter.

### List Roles

> No Documentation Found.

*Tags:* `Roles`

#### Input Parameters
* `limit` - _optional_ - Optional. The page limit. The default page limit is 10.
* `offset` - _optional_ - Optional. The page offset. The default page offset is 0.
* `name` - _optional_ - Optional. Finds a role with the given name.

### Adds a User Role

> No Documentation Found.

*Tags:* `Roles`

### Deletes a User Role

> No Documentation Found.

*Tags:* `Roles`

#### Input Parameters
* `id` - _required_ - The role's id

### Gets a User Role

> No Documentation Found.

*Tags:* `Roles`

#### Input Parameters
* `id` - _required_ - The role's id

### Updates a User Role

> No Documentation Found.

*Tags:* `Roles`

#### Input Parameters
* `id` - _required_ - The role's id

### Get the Permissions for a Role

> No Documentation Found.

*Tags:* `Roles`

#### Input Parameters
* `id` - _required_ - The id of the Role
* `name` - _optional_ - Filter by permission name. Optional.
* `limit` - _optional_ - Optional. The page limit. The default page limit is 10.
* `offset` - _optional_ - Optional. The page offset. The default page offset is 0.

### Manage the Permissions for a Role

> No Documentation Found.

*Tags:* `Roles`

#### Input Parameters
* `id` - _required_ - The id of the Role

### Get all user's in a role

> No Documentation Found.

*Tags:* `UserPermissions`

#### Input Parameters
* `id` - _required_ - The Role's ID
* `limit` - _optional_ - The page limit. The default page limit is 10.
* `offset` - _optional_ - The page offset. The default page offset is 0.

### Update a Role's users

> No Documentation Found.

*Tags:* `UserPermissions`

#### Input Parameters
* `id` - _required_ - The Role's ID

### Get a list of current Client Subscriptions.

> No Documentation Found.

*Tags:* `UpdateGroupClientRelationships`

#### Input Parameters
* `ClientID` - _optional_ - Optional. Filter by Client ID
* `UpdateGroupID` - _optional_ - Optional. Filter by Update Group ID
* `limit` - _optional_ - Optional. The page limit. The default page limit is 10.
* `offset` - _optional_ - Optional. The page offset. The default page offset is 0.

### Add a subscription

> No Documentation Found.

*Tags:* `UpdateGroupClientRelationships`

### DEPRECATED. Set client subscription status for an update group.

> No Documentation Found.

*Tags:* `UpdateGroupClientRelationships`

#### Input Parameters
* `ClientID` - _required_ - The Client ID.  This can be a client ID that has not been registered yet.
* `UpdateGroupID` - _required_ - The Update Group ID
* `Active` - _required_ - Subscribe the client to the Update Group.

### Get a subscription by RelationshipID

> No Documentation Found.

*Tags:* `UpdateGroupClientRelationships`

#### Input Parameters
* `RelationshipID` - _required_ - The RelationshipID.

### Updates a Subscription

> No Documentation Found.

*Tags:* `UpdateGroupClientRelationships`

#### Input Parameters
* `RelationshipID` - _required_ - The relationship id of the UpdateGroupClientRelationship

### Get Update Group Subscriptions

> No Documentation Found.

*Tags:* `UpdateGroupSubscriptions`

#### Input Parameters
* `UpdateGroupID` - _optional_ - Optional. Filter by Update Group ID.
* `PackageTypeID` - _optional_ - Optional. Filter by Package Type ID.
* `ClientID` - _optional_ - Optional. Filter by Client ID.
* `limit` - _optional_ - Optional. The page limit. The default page limit is 10.
* `offset` - _optional_ - Optional. The page offset. The default page offset is 0.

### Add an Update Group Subscription

> No Documentation Found.

*Tags:* `UpdateGroupSubscriptions`

### Delete an Update Group Subscription

> No Documentation Found.

*Tags:* `UpdateGroupSubscriptions`

#### Input Parameters
* `UpdateGroupSubscriptionID` - _required_ - The Update Group Subscription ID to delete

### Get an Update Group Subscription

> No Documentation Found.

*Tags:* `UpdateGroupSubscriptions`

#### Input Parameters
* `UpdateGroupSubscriptionID` - _required_ - The Update Group Subscription ID

### Update an Update Group Subscription

> No Documentation Found.

*Tags:* `UpdateGroupSubscriptions`

#### Input Parameters
* `UpdateGroupSubscriptionID` - _required_ - The Update Group Subscription ID

### Get a list of Update Groups.  Update Groups are used by the client to register for a specific type of update.

> No Documentation Found.

*Tags:* `UpdateGroups`

#### Input Parameters
* `limit` - _optional_ - Optional. The page limit. The default page limit is 10.
* `offset` - _optional_ - Optional. The page offset. The default page offset is 0.

### Add a new Update Group.  The report field is a string that has a dot based request for a specific piece of submitted data.

> No Documentation Found.

*Tags:* `UpdateGroups`

### Delete an Update Group.

> No Documentation Found.

*Tags:* `UpdateGroups`

#### Input Parameters
* `ID` - _required_ - The ID of the Update Group to Delete

### Get a specific Update Group by ID.

> No Documentation Found.

*Tags:* `UpdateGroups`

#### Input Parameters
* `ID` - _required_ - The ID of the Update Group

### Modify an Update Group.

> No Documentation Found.

*Tags:* `UpdateGroups`

#### Input Parameters
* `ID` - _required_ - ID of the Update Group

### Get a list of bundles for UpdateGroup.

> No Documentation Found.

*Tags:* `UpdateGroups`

#### Input Parameters
* `ID` - _required_ - The UpdateGroupID
* `IncludeInactive` - _required_ - Include Inactive Bundles (true|false)
* `limit` - _optional_ - Optional. The page limit. The default page limit is 10.
* `offset` - _optional_ - Optional. The page offset. The default page offset is 0.

### Checks the Client ID into the Update System.

> No Documentation Found.

*Tags:* `UpdateSystem`

#### Input Parameters
* `ClientID` - _required_ - The Client ID to check-in.  If this is a new client ID it will be added to Clients.
* `Preview` - _required_ - Get Pkgs w\o updating Datetimes(true|false)

### Get UserContentDefinitions

> Gets a collection of UserContentDefinitions. When successful, the response is a PagedResponse of UserContentDefinitions.<br/>
>             If unsuccessful, an appropriate ApiError is returned.

*Tags:* `UserContentDefinitions`

#### Input Parameters
* `limit` - _optional_ - Optional. The page limit.  If not specified, the default page limit is 10.
* `offset` - _optional_ - Optional. The page offset.  If not specified, the default page offset is 0.
* `userID` - _optional_ - Optional. Filter by UserID.
* `contentDefinitionID` - _optional_ - Optional. Filter by ContentDefinitionID

### Create a UserContentDefinition

> Creates a UserContentDefinition.  The body of the POST is the UserContentDefinition to create.<br/>
>             The UserContentDefinitionID will be assigned on creation of the Job.  When successful, the response<br/>
>             is the UserContentDefinitionID.  If unsuccessful, an appropriate ApiError is returned.

*Tags:* `UserContentDefinitions`

### Delete a UserContentDefinition

> Deletes an UserContentDefinition. When successful, the response is empty.  If unsuccessful, an appropriate<br/>
>             ApiError is returned.

*Tags:* `UserContentDefinitions`

#### Input Parameters
* `userContentDefinitionID` - _required_ - The ID of the UserContentDefinition to delete

### Get a UserContentDefinition by ID

> Gets a UserContentDefinition by ID. When successful, the response is the requested UserContentDefinition.<br/>
>             If unsuccessful, an appropriate ApiError is returned.

*Tags:* `UserContentDefinitions`

#### Input Parameters
* `userContentDefinitionID` - _required_ - The ID of the UserContentDefinition to get.

### Get users

> No Documentation Found.

*Tags:* `Users`

#### Input Parameters
* `username` - _optional_ - Optional. Search by username. Supports beginning and ending wildcards (*).
* `email` - _optional_ - Optional. Search by email. Supports beginning and ending wildcards (*).
* `name` - _optional_ - Optional. Search by name. Supports beginning and ending wildcards (*).
* `limit` - _optional_ - Optional. The page limit. The default page limit is 10.
* `offset` - _optional_ - Optional. The page offset. The default page offset is 0.

### Create a user

> No Documentation Found.

*Tags:* `Users`

### Gets the current user

> No Documentation Found.

*Tags:* `Users`

### Update a user

> No Documentation Found.

*Tags:* `Users`

### Get a user's permissions

> No Documentation Found.

*Tags:* `UserPermissions`

#### Input Parameters
* `Permission` - _optional_ - Filter by permission name. Supports ending wildcard (*). Optional.
* `limit` - _optional_ - The page limit. The default page limit is 10.
* `offset` - _optional_ - The page offset. The default page offset is 0.

### Gets the current user's roles

> No Documentation Found.

*Tags:* `UserPermissions`

#### Input Parameters
* `Role` - _optional_ - Filter by role name. Supports ending wildcard (*). Optional.
* `limit` - _optional_ - The page limit. The default page limit is 10.
* `offset` - _optional_ - The page offset. The default page offset is 0.

### Delete a user

> No Documentation Found.

*Tags:* `Users`

#### Input Parameters
* `id` - _required_ - The user id

### Get a specific user

> No Documentation Found.

*Tags:* `Users`

#### Input Parameters
* `id` - _required_ - The user ID

### Update a user

> No Documentation Found.

*Tags:* `Users`

#### Input Parameters
* `id` - _required_ - The user id

### Get a user's permissions

> No Documentation Found.

*Tags:* `UserPermissions`

#### Input Parameters
* `id` - _required_ - The User's ID
* `Permission` - _optional_ - Filter by permission name. Supports ending wildcard (*). Optional.
* `limit` - _optional_ - The page limit. The default page limit is 10.
* `offset` - _optional_ - The page offset. The default page offset is 0.

### Get a user's roles

> No Documentation Found.

*Tags:* `UserPermissions`

#### Input Parameters
* `id` - _required_ - The User's ID
* `Role` - _optional_ - Filter by role name. Supports ending wildcard (*). Optional.
* `limit` - _optional_ - The page limit. The default page limit is 10.
* `offset` - _optional_ - The page offset. The default page offset is 0.

### Update a user's roles

> No Documentation Found.

*Tags:* `UserPermissions`

#### Input Parameters
* `id` - _required_ - The User's ID

### Gets voucher history data

> No Documentation Found.

*Tags:* `VoucherHistory`

#### Input Parameters
* `VoucherCode` - _optional_ - Optional. Filter history data by Voucher Code.
* `ChangedBefore` - _optional_ - Optional. Filter history data where changes occured before provided date.
* `ChangedAfter` - _optional_ - Optional. Filter history data where changes occured after provided date.
* `limit` - _optional_ - Optional. The page limit. The default page limit is 10.
* `offset` - _optional_ - Optional. The page offset. The default page offset is 0.

### Gets a list of vouchers

> No Documentation Found.

*Tags:* `Vouchers`

#### Input Parameters
* `Type` - _optional_ - Optional. Filter vouchers by Type
    Possible values: Commercial, Internal, Temporary.
* `DealerCode` - _optional_ - Optional. Filter vouchers by DealerCode
* `LicenseTo` - _optional_ - Optional. Filter vouchers by LicenseTo. Wildcard supported (*).
* `Purpose` - _optional_ - Optional. Filter vouchers by Purpose. Wildcard supported (*).
* `OrderNumber` - _optional_ - Optional. Filter vouchers by OrderNumber
* `Email` - _optional_ - Optional. Filter vouchers by Email. Wildcard supported (*).
* `ModifiedBy` - _optional_ - Optional. Filter vouchers by ModifiedBy
* `CreatedAfter` - _optional_ - Optional. Filter vouchers by CreatedDate
* `CreatedBefore` - _optional_ - Optional. Filter vouchers by CreatedDate
* `PunchedAfter` - _optional_ - Optional. Filter vouchers by PunchedDate
* `PunchedBefore` - _optional_ - Optional. Filter vouchers by PunchedDate
* `Punched` - _optional_ - Optional. Filter vouchers by Punched status
* `ExpirationAfter` - _optional_ - Optional. Filter vouchers by ExpirationDate
* `ExpirationBefore` - _optional_ - Optional. Filter vouchers by ExpirationDate
* `Deleted` - _optional_ - Optional. Filter vouchers by Deleted state. By default only vouchers that are not deleted are returned.
    Possible values: NotDeleted, Deleted, All.
* `limit` - _optional_ - Optional. The page limit. The default page limit is 10.
* `offset` - _optional_ - Optional. The page offset. The default page offset is 0.

### Create a voucher

> No Documentation Found.

*Tags:* `Vouchers`

### Delete a voucher

> No Documentation Found.

*Tags:* `Vouchers`

#### Input Parameters
* `VoucherCode` - _required_ - The voucher code of the voucher to delete.

### Get a voucher

> No Documentation Found.

*Tags:* `Vouchers`

#### Input Parameters
* `VoucherCode` - _required_ - The voucher code of the voucher to get.
* `Deleted` - _optional_ - Optional. Filter vouchers by Deleted state. By default only vouchers that are not deleted are returned.
    Possible values: NotDeleted, Deleted, All.

### Update a voucher

> No Documentation Found.

*Tags:* `Vouchers`

#### Input Parameters
* `VoucherCode` - _required_ - The voucher code of the voucher to update.

### Get a voucher's history.

> No Documentation Found.

*Tags:* `Vouchers`

#### Input Parameters
* `VoucherCode` - _required_ - The voucher code to get history for.
* `limit` - _optional_ - Optional. The page limit. The default page limit is 10.
* `offset` - _optional_ - Optional. The page offset. The default page offset is 0.

### Get Activities

> Gets a collection of Activities. When successful, the response is a PagedResponse of Activities.  <br/>
>             If unsuccessful, an appropriate ApiError is returned.

*Tags:* `Activities`

#### Input Parameters
* `limit` - _optional_ - Optional. The page limit.  If not specified, the default page limit is 10.
* `offset` - _optional_ - Optional. The page offset.  If not specified, the default page offset is 0.
* `isIncludeDeleted` - _optional_ - Does it include deleted activity, or not

### Create an Activity

> Creates an Activity.  The body of the POST is the Activity to create.  The ActivityID will be assigned<br/>
>             on creation of the Activity.  When successful, the response is the ActivityID.  If unsuccessful, an <br/>
>             appropriate ApiError is returned.

*Tags:* `Activities`

### Mark the delete flag for the Activity

> Deletes an Activity. When successful, the response is empty.  If unsuccessful, an appropriate<br/>
>             ApiError is returned.

*Tags:* `Activities`

#### Input Parameters
* `activityID` - _required_ - The id of the activity to delete

### Get an Activity by ID

> Gets an Activity by ID. When successful, the response is the requested Activity.  If unsuccessful,<br/>
>             an appropriate ApiError is returned.

*Tags:* `Activities`

#### Input Parameters
* `activityID` - _required_ - The ID of the Activity to get.
* `isIncludeDeleted` - _optional_ - Does it include deleted activity, or not

### Update an Activity

> Updates an Activity.  The body of the PUT is the updated Activity.  When successful, the response is empty.<br/>
>             If unsuccessful, an appropriate ApiError is returned.

*Tags:* `Activities`

#### Input Parameters
* `activityID` - _required_ - The id of the activity to update

### Get ActivityRuns

> Gets a collection of ActivityRuns. When successful, the response is a PagedResponse of ActivityRuns.  <br/>
>             If unsuccessful, an appropriate ApiError is returned.

*Tags:* `ActivityRuns`

#### Input Parameters
* `limit` - _optional_ - Optional. The page limit.  If not specified, the default page limit is 10.
* `offset` - _optional_ - Optional. The page offset.  If not specified, the default page offset is 0.
* `status` - _optional_ - Optional. Filter activity runs by status.  Value should be a comma separated list of status to include.
            If not specified, the default status filter is "InProgress".
    Possible values: Ready, InProgress, Succeeded, Cancelled, Failed.

### Get an ActivityRun by ID

> Gets an ActivityRun by ID. When successful, the response is the requested ActivityRun.  If unsuccessful,<br/>
>             an appropriate ApiError is returned.

*Tags:* `ActivityRuns`

#### Input Parameters
* `activityRunID` - _required_ - The ID of the ActivityRun to get.

### Update an ActivityRun

> Updates the ActivityRunStatus of an ActivityRun.  The body of the PUT is the updated ActivityRunStatus.<br/>
>             When successful, the response is empty.  If unsuccessful, an appropriate ApiError is returned.

*Tags:* `ActivityRuns`

#### Input Parameters
* `activityRunID` - _required_ - The ID of the ActivityRun to update ActivityRunStatus for.

### Get the ActivityRunStatus of an ActivityRun

> Gets the ActivityRunStatus of an ActivityRun.  When successful, the response is the requested ActivityRunStatus.<br/>
>             If unsuccessful, an appropriate ApiError is returned.

*Tags:* `ActivityRuns`

#### Input Parameters
* `activityRunID` - _required_ - The ID of the ActivityRun to get ActivityRunStatus for.

### Update the ActivityRunStatus of an ActivityRun

> Updates the ActivityRunStatus of an ActivityRun.  The body of the PUT is the updated ActivityRunStatus.<br/>
>             When successful, the response is empty.  If unsuccessful, an appropriate ApiError is returned.

*Tags:* `ActivityRuns`

#### Input Parameters
* `activityRunID` - _required_ - The ID of the ActivityRun to update ActivityRunStatus for.

### Get Agents

> Gets a collection of Agents. When successful, the response is a PagedResponse of Agents.  <br/>
>             If unsuccessful, an appropriate ApiError is returned.

*Tags:* `Agents`

#### Input Parameters
* `limit` - _optional_ - Optional. The page limit.  If not specified, the default page limit is 10.
* `offset` - _optional_ - Optional. The page offset.  If not specified, the default page offset is 0.

### Create an Agent

> Creates an Agent.  The body of the POST is the Agent to create.  The AgentID will be assigned<br/>
>             on creation of the Agent.  When successful, the response is the AgentID.  If unsuccessful, an<br/>
>             appropriate ApiError is returned.

*Tags:* `Agents`

### Get Agent associated with the current user

> Gets the Agent associated with the current user. When successful, the response is the requested Agent.  If unsuccessful,<br/>
>             an appropriate ApiError is returned.

*Tags:* `Agents`

### Get the ActivityRun of Agent associated with the current user

> Gets the activity run assigned to an agent.  When successful, the response is the ActivityRun<br/>
>             assigned to the Agent.  If unsuccessful, an appropriate ApiError is returned.

*Tags:* `Agents`

### Delete an Agent

> Deletes an Agent. When successful, the response is empty.  If unsuccessful, an appropriate<br/>
>             ApiError is returned.

*Tags:* `Agents`

#### Input Parameters
* `agentID` - _required_ - The id of the Agent to delete.

### Get Agent

> Gets an Agent by ID. When successful, the response is the requested Agent.  If unsuccessful,<br/>
>             an appropriate ApiError is returned.

*Tags:* `Agents`

#### Input Parameters
* `agentID` - _required_ - The id of the Agent to get.

### Update an Agent

> Updates an Agent.  The body of the PUT is the updated Agent.  When successful, the response is empty.<br/>
>             If unsuccessful, an appropriate ApiError is returned.

*Tags:* `Agents`

#### Input Parameters
* `agentID` - _required_ - The id of the Agent to update.

### Get an Agent's ActivityRun

> Gets the activity run assigned to an agent.  When successful, the response is the ActivityRun<br/>
>             assigned to the Agent.  If unsuccessful, an appropriate ApiError is returned.

*Tags:* `Agents`

#### Input Parameters
* `agentID` - _required_ - The id of the Agent to get.

### Update the ActivityRun assigned to the Agent.

> No Documentation Found.

*Tags:* `Agents`

#### Input Parameters
* `agentID` - _required_ - The id of the Agent to update.

### Update an Agent

> Updates the status of an Agent.The body of the PUT is the updated Agent status.  When successful,<br/>
>             the response is empty.If unsuccessful, an appropriate ApiError is returned.

*Tags:* `Agents`

#### Input Parameters
* `agentID` - _required_ - The id of the Agent to update.

### Get JobRuns

> Gets a collection of JobRuns. When successful, the response is a PagedResponse of JobRuns.<br/>
>             If unsuccessful, an appropriate ApiError is returned.

*Tags:* `JobRuns`

#### Input Parameters
* `limit` - _optional_ - Optional. The page limit.  If not specified, the default page limit is 10.
* `offset` - _optional_ - Optional. The page offset.  If not specified, the default page offset is 0.
* `includeActivityRunDetails` - _optional_ - Optional. Indicates whether to include ActivityRun details.  Defaults to false.

### Create a JobRun

> Creates a JobRun.  The body of the POST is the JobRun to create.  The JobRunID will be assigned on<br/>
>             creation of the JobRun.  When successful, the response is the JobRunID.  If unsuccessful, an <br/>
>             appropriate ApiError is returned.

*Tags:* `JobRuns`

### Delete a JobRun

> Deletes a JobRun. When successful, the response is empty.  If unsuccessful, an appropriate<br/>
>             ApiError is returned.

*Tags:* `JobRuns`

#### Input Parameters
* `jobRunID` - _required_ - The id of the JobRun to delete

### Get a JobRun by ID

> Gets a JobRun by ID. When successful, the response is the requested JobRun.<br/>
>             If unsuccessful, an appropriate ApiError is returned.

*Tags:* `JobRuns`

#### Input Parameters
* `jobRunID` - _required_ - The ID of the JobRun to get.
* `includeActivityRunDetails` - _optional_ - Optional. Indicates whether to include ActivityRun details.  Defaults to false.

### Update a JobRun

> /// <br/>
>             Updates a JobRun.  The body of the PUT is the updated JobRun.<br/>
>             When successful, the response is empty.  If unsuccessful, an appropriate ApiError is returned.

*Tags:* `JobRuns`

#### Input Parameters
* `jobRunID` - _required_ - The id of the JobRun to update

### Get Jobs

> Gets a collection of Jobs. When successful, the response is a PagedResponse of Jobs.<br/>
>             If unsuccessful, an appropriate ApiError is returned. <br/>
>             ///

*Tags:* `Jobs`

#### Input Parameters
* `limit` - _optional_ - Optional. The page limit.  If not specified, the default page limit is 10.
* `offset` - _optional_ - Optional. The page offset.  If not specified, the default page offset is 0.
* `isIncludeDeleted` - _optional_ - Does it include deleted job, or not

### Create a Job

> Creates a Job.  The body of the POST is the Job to create.  The JobID will be assigned on<br/>
>             creation of the Job.  When successful, the response is the JobID.  If unsuccessful, an <br/>
>             appropriate ApiError is returned.

*Tags:* `Jobs`

### Mark the delete flag for the Job

> Deletes a Job. When successful, the response is empty.  If unsuccessful, an appropriate<br/>
>             ApiError is returned.

*Tags:* `Jobs`

#### Input Parameters
* `jobID` - _required_ - The id of the job to delete

### Get a Job by ID

> Gets a Job by ID. When successful, the response is the requested Job.<br/>
>             If unsuccessful, an appropriate ApiError is returned.

*Tags:* `Jobs`

#### Input Parameters
* `jobID` - _required_ - The ID of the Job to get.
* `isIncludeDeleted` - _optional_ - Does it include deleted job, or not

### Update a Job

> Updates a Job.  The body of the PUT is the updated Job.  When successful, the response is empty.<br/>
>             If unsuccessful, an appropriate ApiError is returned.

*Tags:* `Jobs`

#### Input Parameters
* `jobID` - _required_ - The id of the job to update

### Get Steps

> Gets a collection of Steps. When successful, the response is a PagedResponse of Steps.<br/>
>             If unsuccessful, an appropriate ApiError is returned.  Steps.Read permission is required.

*Tags:* `Steps`

#### Input Parameters
* `limit` - _optional_ - Optional. The page limit.  If not specified, the default page limit is 10.
* `offset` - _optional_ - Optional. The page offset.  If not specified, the default page offset is 0.
* `includeDeleted` - _optional_ - Does it include deleted step, or not

### Create a Step

> No Documentation Found.

*Tags:* `Steps`

### Get a Step by ID

> Gets a Step by ID. When successful, the response is the requested Step.<br/>
>             If unsuccessful, an appropriate ApiError is returned.  Steps.Read permission is required.

*Tags:* `Steps`

#### Input Parameters
* `stepID` - _required_ - The ID of the Step to get.
* `isIncludeDeleted` - _optional_ - Does it include deleted step, or not

### Update a Step

> No Documentation Found.

*Tags:* `Steps`

#### Input Parameters
* `stepID` - _required_ - The step ID of the step to update

## License

**flow**ground :- Telekom iPaaS / agco-ats-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
