## SD Stores Logistics Releases

### 3.0.0

#### Enhancements



#### Bug Fixes



### 2.1.1

#### Enhancements

- Existing code base was ported to NAV 2018.

#### Bug Fixes

- TryFunction issue in Page 43018079 SD-LG Load Planner Card - fixed in this NAV 2018 release of SD Logistics.
- TryFunction issue in Codeunit 43018043 SD-LG Geo Manager - fixed in this NAV 2018 release of SD Logistics.
- TryFunction issue in Codeunit 43018042 SD-LG Load Plan Manager - fixed in this NAV 2018 release of SD Logistics.
- TryFunction issue in Codeunit 43018041 SD-LG Manifest Manager - fixed in this NAV 2018 release of SD Logistics.
- TryFunction issue in Codeunit 43018040 SD-LG Utilities - fixed in this NAV 2018 release of SD Logistics.
- A TryFunction issue in Document Queue was fixed.
- A TryFunction error raised in the SD-LG Suggest Zone page in NAV 2018 was fixed.
- A TryFunction error raised in the SD-LG Suggest Rates page in NAV 2018 was fixed.
- A TryFuntion error raised in Load Manifest Card when Assigning Documents to the Manifest in a NAV 2018 release of SD Logistics was fixed.

### 2.1.0

#### Enhancements

- Renumbered objects.
- Made changes to code for NAV 2017 compliance.
- Changes made for NAV 2017.
- Added an option on Shipping Agent/Vendor to bypass PO generation.
- Made a change to display a description on the info boxes when displaying statically.
- Added new functionality to open a document from the Manifest Document List on the Visual Load Planner.
- Restyled the Google Infoboxes.
- Restyled the Map popup.
- Changed Planner label logic to handle static vs popup.
- Made a number of general minor enhancements.
- Added Show Caption functionality to Planner Labels.
- Made a change to hide toggle info box on Planner if setup is not running static info boxes.

#### Bug Fixes

- Fixed an issue where if there are no orders, load map planner does not load the google map.
- Fixed an issue where, when unticking multi order, the UI was not updating.

### 1.2.0

#### Enhancements

- Alternative Latitude and Longitude per Document Type.
- Allow assign/unassign on Document Operations page.
- Created Suggest Manifest on Document Operations page.
- Allow to toggle Infoboxes.
- Allow to toggle Released.
- Created Planner Labels.
- When adding an Order to a Manifest from a different Zone to the Manifest Zone, prompt the user if they would like to update to theZone (if the Zone is more expensive).
- Unassign Manifest if Manifest is assigned to Documents.
- Created new functionality so that Sales/Purchase Orders can have geo stamping.
- Created a BeforeOrderLoadedOnPlanner Event, an AfterManifestRelease Event, an AfterDocumentCreated Event.
- Made general improvements to functionality.
- Developed new Rate design.
- Replaced Location information with Zone information on the Manifest.
- Suggest Manifest from Documents.
- Suggest Rates.
- Suggest Zones.
- Rate Preview.
- Document Order on Manifest.
- Document Sublist on Visual Load Planner.
- Manifest factbox.
- Static info boxes on Visual Load Planner Map.
- Update XML Ports.
- General UI Improvements.
- Create a subscription event on PO Generation.
- Fail back on Net weight if Gross Weight is blank.
- Change Rank To Drop No. on Document.
- On Document Generation, if Document exists, update.
- Stamp Standard Package Tracking Field on Sales/Purchase/Transfer.
- Add Text Line to PO Generation.
- Allow blank Zone on Rate Calculation.
- Default Load Shipment Date - Manifest Card - field Shipping Date to be auto-populated to Next Working Date.
- Hide closed Manifest Orders from map view.
- Allow for blank Zones on Rates (Manifest Rate Lookup).
- System wide optimisation.

#### Bug Fixes

- Error on PO create when there is more than one Manifest Order.
- Assigned PIN Colour for Load - When all orders on a Manifest are assigned, if the Manifest/Orders are mixed, then the PIN colour stays as is rather than changing to ALL assigned.
- On the Load Planner Card, the Manifest General Information, make Shipping Zone, Shipment Date, Shipping Agent visible andeditable.
- On the Load Planner Card, the Assigned Documents Section, the choose columns option is not working.

### 1.1.0

#### Enhancements

- Created a Pick List Report. Add to SD Logistics Setup Report Selection.
- Created a Delivery Docket Report to run off the Sales Orders as the Shipments won't have been posted.
- Added a Report Selection to the SD Logistics Setup page to allow users configure and select the required reports (Pick List, DeliveryDocket, Manifest Report).
- Added Enforce Trailer Option functionality on to the Hauler Service Setup. If not enforced, display a warning but to not prohibit the user from continuing.
- Created a Customer Document view for the Operation Role Centre where the users can collect documents that would be used on theLoad Map Planner.
- Created an icon indicator matrix based on the Shipment Method. Allow user to select a colour (option) for the state. States areAssigned, Unassigned, Partial Assign, Assigned To Other. Use a grid to determine the icon on the tag.
- Added Trailer Capacity/Weight to the Manifest Info FactBox.
- Created a sublist of Documents for Manifest.
- Created a new Logistics Manifest Report.
- Updated functionality to only cater for the following Document Types - Sales Order, Sales Return Order, PO, PO Return, TransferShipment (TO Out).
- Added Manifest Info - Weight, Cubage, No. of Parcels to factbox/page/list.
- Changes to the Visual Load Planner.
- On change of Haulier, if enforce trailer option assigned the warn user to clear out lines and delete PO.
- Changes to the Manifest process.

### 1.0.0

#### Enhancements

- Implemented Visual Manifest / Load Planner.
- Developed a Mobile Phone Role Centre.
- Created tables, pages and associated functionality for Haulage Setup, Zone, Rate, Rate Additions, Driver, Shipping Agent Vendor,Vehicle Type, Vehicle Type Compartment, Vehicle, Manifest, Load Planner Setup, and Map Selection.
- Implemented Planner Manager, Load Manifest Item, Shipping Manifest Item.
- Created a Role Center.
- Implemented code change to suggest Zones based on current orders on the system and to suggest Zone Rate based on Orders,Locations and Zones.
- Developed code to manage all geo location requests.
- Created a Visual Planner Worksheet.
- Developed Order Suggest functionality and Visual Load Planner functionality.
- Developed Manifest Document.
- Created a Query that merges the Load Manifest and Shipped Manifest tables.
- Created a Query that merges the Load Manifest Document and Shipped Manifest Document tables.
- Created a Query that merges the Load Manifest Item and Shipped Manifest Item tables.
- Created Drops Tracking functionality.
- Updated the XMLPort to handle new Drop Table.
- Added in Installer.
- Exposed activity items on Role Center navigation.
- If shipment date defaults are blank, then use the workdate.
- Renamed Zones to Region.
- Moved Purchase order creation to Shipping Vendor.
- Renamed "Above X Drop" to ">= X Drops".
- Renamed "Rate per drop" to "Extra drop rate".
- Changed "Zones per rate" sublist to Regions (Country/Post Code).
- Added functionality to suggest region rate.
- Enhanced Vehicle Type compartment, weight and cubage functionality.
- Moved suggest Manifest from Role Center to Manifest list.
- Split out shipment date range to start and end date.
- Change to functionality to not to determine latitude at suggestion level.
- Moved add all manifest remove shipped to an action item.
- Removed Load Map selection to filter selection on Visual Load Planner.
- Implemented functionality whereby if orders are still available for partial order allow to assign all.
- Developed a report to build selection filters for Visual Load Planner.
- Removed "Release and Post" option from Visual Load Planner.
- Created an XMLPort to allow Import/Export of setup and data.
- Extended Load Manifest Document for other document types.
- Implemented Photo Capture for Mobile Role Center.
- Created Shipped Drops Tables and associated functionality.

#### Bug Fixes

- Fixed not Blank on Shipping Agent bug.
- Fixed bug in Maps Loader Web Client.
- Fixed bug where all Manifest from Role Center is not allowing suggested Manifests.

