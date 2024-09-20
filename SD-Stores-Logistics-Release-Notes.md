## SD Stores Logistics Releases

### 4.0.1

#### Enhancements

- AppSource App - Update for 2024 wave 2 release. Report Interactions no longer contain a definition for the FindInteractTmplCode function in 2024 wave 2. The FindInteractTmplCode function is replaced with new functionality. The SD Logistics Delivery Docket report was updated to use the new functionality.

- AppSource App - A change was made to the Assisted Setup functionality.

- AppSource App - The links in the About page were updated.

- AppSource App - The logo in the App was updated to the new logo.

### 4.0.0.1

#### Enhancements

- BCv14 App - A permission set was created for SD Stores Logistics.

### 4.0.0

#### Enhancements

- AppSource App - The initial auto population of the Queued Documents list was changed to populate using the Default Movement Types from the SD Stores Logistics Setup. 

- AppSource App - A new column, Agreed Rate, was added to the Queued Documents. If the Total Rate has a value and the Agreed Rate has a value the Manifest picks up the Agreed Rate. A new field called Enforce Manifest Cost was added to the setup card. This option will check if there is a rate amount on the Manifest when the manifest is released. 

- AppSource App - A Shipping Agent Booking Reference field was added to the Manifest.  

- AppSource App - A new Boolean called Enforce Shipment on Close Manifest was added to the SD Stores Logistics Setup card. This field checks for any Ship or Receive (depending on the document type) made against the document. 

- AppSource App - When updating Rates in the Queued Documents list the take effect date is set to the work date. Users will be prompted to create a new rate if they enter a different rate the next day. 

- AppSource App - The Rate Amount from the Shipped Manifest was surfaced in the Shipped Manifest FactBox to allow for a drill down to see the breakdown of rates. 

- AppSource App - A generated Purchase Document for a foreign currency had the currency amount for rates in LCY values. This was changed so that the rates must be entered on the rate card in the Vendor's/Shipping Agent's currency. 

- AppSource App - Users are not allowed to delete a record from the Queued Documents if the record has a manifest number. 

- AppSource App - If a Shipping Agent Code or Shipping Agent Service are updated on the Queued Documents, these changes are now saved. 

- AppSource App - Do not allow users to add rates of type Fuel Surcharge and Agreed Rate on the Zone Rates List in the Zone Card. 

- AppSource App - When the Enforce Manifest Cost option in the Setup card is off, don't prompt the user to enter rates on the Manifest. 

- AppSource App - Update the text on the message displayed if the Enforce Manifest Cost is switched on in the Setup card and there is no rate on the manifest. 

- AppSource App - The new fields on the Shipped Load Manifest Pallet Rate Currency Code, No. of Pallets, No. of Pallet Spaces, Total Rate, Agreed Rate and Booking Reference were added to the Shipped/Closed Load Manifest. 

- AppSource App - Some ToolTips on the Setup Card were updated. 

- AppSource App - If a rate is entered in the Queued Documents list and the Shipping Agent or Shipping Agent Service is then changed, the rates are revalidated. 

- AppSource App - On the Visual Load Planner a change was made to not allow orders with a different Shipping Agents to exist on the Manifest.  

- AppSource App - In the Rates card there is a new Type of Fuel Surcharge. Do not allow users to add a rate of with a Type of Fuel Surcharge. Fuel Surcharge is added to the Agent to Vendor list.  

- AppSource App - The Pallet Cost Currency Code was surfaced on the Queued Documents.   

- AppSource App - When assigning documents to manifests checks are made and a prompt is raised if the documents exists on another manifest. 

- AppSource App - The SD Stores Logistics Available Documents list was recaptioned to SD Stores Logistics Queued Documents to match the cue caption in the Role Centre. 

- AppSource App - Updating the Shipping Agent and Shipping Agent Service on the Queued Documents list does not update the underlying document but the modified changes are stored on the manifest lines.  

- AppSource App - A change was made to display the Default Movement Types DateFormula from the Setup card in the Document Selector request page. 

- AppSource App - The captions in the Document Selector request page were updated to reflect the Document Types that you are entering the filters for rather than the Table.  

- AppSource App - Captions in the Movement Types Defaults FastTab in the SD Stores Logistics Setup card were updated. 

- AppSource App - An ODATA feed was created for the closed manifests to view the carriage costs.  

- AppSource App - Changes were made to the automatically generated Purchase Order and Purchase Invoice for shipping charges. A Fuel Surcharge % field was added to the Shipping Agent to Vendor list. The Fuel Surcharge % is calculated on the release of a manifest as a percentage of the load cost. 

- AppSource App - A number of changes were made to the manifests. Manifest status has been changed to Open, Released or Closed. Cues on the Role Centre have been updated to reflect this change. Pallet information is now stored on the manifest. When assigning orders to manifests, the orders are checked and users are prompted if the orders exist on another manifest. 

- AppSource App - A number of changes were made to the Queued Documents. The Queued Documents cue was moved to the first cue in the Role Centre. When the Queued Documents list is opened, the page is automatically refreshed to bring in the documents based on the default movement type values in the SD Stores Logistics Setup card. The Get Documents action was pinned to the menu and the action was renamed to Refresh. The Batch field has been retired. A new option of pallet has been added to the Type field in the Rates table. New columns were added to the Queued Documents list to enter the number of pallets, pallet spaces, pallet space rate, and total rate. In the Queued Documents list the users can update the Shipping Agent Code, Shipping Agent Service Code, and Zone. If the user manually types in a rate or modifies a rate, a prompt is rasied to ask if they want to update the rate if the Shipping Agent/Service Code/Zone combination exists or if they want to create the rate if the Shipping Agent/Service Code/Zone combination does not exist.   

- AppSource App - The Enforce Trailer Loading field was removed from the Shipping Agents to Vendors list.  

- AppSource App - A new FastTab for movement types defaults with associated DateFormula fields was added to the SD Stores Logistics Setup card. On open of the Queued Documents list, the documents are now automatically populated using the values in the movement type default DateFormulas. A new Refresh action was surfaced on the Queued Documents to allow refresh of the data. 

- AppSource App - Some existing KPIs on the SD Stores Logistics Setup card were removed and other KPIs were added. 

- AppSource App - A new Visual Planner Setup page was created. Existing Visual Planner setup fields were removed from the SD Stores Logistics Setup Card and added to this new page. 

- AppSource App - The Drivers, Vehicle Types and Vehicles actions were removed from the SD Stores Logistics Setup Card. A new action called Own Transport was surfaced on the Setup Card that opens the SD Stores Logistics Vehicles list. 

- AppSource App - The standard Shipping Agents page was extended for SD Stores Logistics and a new action for the Shipping Agents page was added to the SD Stores Logistics Setup Card.  The Shipping Agents to Vendors, Zones, and Rates actions were removed from the SD Stores Logistics Setup card and placed on the extended Shipping Agents page. 

- BCv14 App - The v4.0.0 AppSource App was backported to BCv14.

- BCv14 App - Documents that are fully shipped and invoiced should not appear in the Queued Documents list. 

- BCv14 App - Add a prompt on open of the SD Stores Logistics Role Centre to Activate the SD Stores Logistics Licence. 

- BCv14 App - The Cue Group Captions on the Role Centre were removed. 

- BCv14 App - When the Enforce Manifest Cost option in the Setup card is off, don't prompt the user to enter rates on the Manifest. 

- BCv14 App - Do not allow users to add rates of type Fuel Surcharge and Agreed Rate on the Zone Rates List in the Zone Card. 


#### Bug Fixes

- AppSource App - A new rate was entered on the Queued Documents and was inserted into the Rate Card/List without prompting the user. This was fixed. 

- AppSource App - Update the message raised when prompting the user to update an existing rate. 

- AppSource App - From the Manifest card, an empty Manifest was deleted but the Manifest was still showing in the Open Load Manifest list. This was fixed. 

- AppSource App - On Closing a Manifest with Sales Orders and Sales Return Orders, the Sales Orders were no longer showing in the Queued Documents list but the Sales Return Order was. This was fixed. 

- AppSource App - The take effect date was added to the prompt shown to users when updating rates where an existing rate exists. 

- AppSource App - When adding a Vendor to the Shipping Agent to Vendor list, the Vendor's Currency Code was not picked up.  

- AppSource App - Auto population of the Queued Documents was bringing in all documents up to the DateFormulas as specified in the SD Stores Logistics Setup but the Refresh action was bringing in documents limited to the from/to date. This was changed so documents are initially populated and refreshed with ..(workdate + dateformula). 

- AppSource App - Currency codes on the rate record were not validating off the currency table. 

- AppSource App - A change was made to allow a drill down from the Load Manifest No. in the Queued Documents to the Manifest Card. 

- AppSource App - Fixed an issue where the Manifest was Closed but the status on the Manifest was still showing a status of Released. 

- AppSource App - A small typo was fixed on the message displayed when posting/shipping a manifest. 

- AppSource App - When creating a new rate based on user input into the Queued Documents list, the Shipping Agent Service Code was not being updated on the Rate Card. 

- BCv14 App - The rate was  not revalidating if a Shipping Agent or Shipping Agent Service on the line was changed. 

- BCv14 App - In the SD Stores Logistics Visual Planner Setup the Fields could be selected from the list of fields on the table. This was fixed. 

- BCv14 App - A new rate was entered on the Queued Documents and was inserted into the Rate Card/List without prompting the user. This was fixed. 

- BCv14 App - Changing a Shipping Agent or Service Code was revalidating the Pallet Space Rate but was not revalidating the Total Rate.

- BCv14 App - Update the message raised when prompting the user to update an existing rate. 

### 3.1.1

#### Enhancements

- AppSource App - A change was made to limit the SD ISV Tenant Subscriptions page to display just our SD ISV AppSource Apps and not other SD PTE Apps.

- AppSource App - A notification was added to SD Stores Logistics pages to show users that they need to activate the licence on first install of the App.

- AppSource App - The SD Stores Logistics Assisted Setup page was removed from the Tell Me search.

#### Bug Fixes

- AppSource App - When selecting SD Stores Logistics activity pages in the Tell Me search in a BCv22 environment, the activity pages were hanging.

- AppSource App - A change was made to the ISV Licence Notification procedure in SD Stores Logistics to fix an issue that would raise an error when the language is changed from English to another language.

- AppSource App - The SD Stores Logistics Setup card was unresponsive if the KPI FastTab was minimised on open of the page.

### 3.1.0

#### Enhancements

- BCv21 App - A new activity table was created, and the SD Stores Logistics activity pages were changed to have this table as their source table. 

- BCv21 App - The format of the SD Stores Logisitics permission names were standardised to that of our other Apps. 

- BCv21 App - The Latest ISV Licence Control was added to SD Stores Logistics. 

- BCv21 App - The Licence Message displayed on first install of SD Stores Logistics was changed to prompt the user to activate a free trial and to choose Assisted Setup from the Setup Card to create demo data. 

- BCv21 App - A page was created to display all the Simply Dynamics Apps and subscription details for the tenant. 

- BCv21 App - The Licence Expiry message/notification was updated to display the App Name as part of the message. 

- BCv21 App - The Product Activation Page was updated to point to the new CRM URL. 

- BCv21 App - The ToolTips were updated to look at our new website. 

- BCv21 App - The links in the About Page were updated to point to new URLs. 

#### Bug Fixes

- BCv21 App - A fix was made to the code for licence key checks on the SD Stores Logistics Role Centre.  

### 3.0.0

#### Enhancements

- BCv19 App - For increased performance in the Visual Load Planner the javascript files were minified. 

- BCv19 App - A change was made to the Free Trial Licences in the ISV Licence Controller. 

- BCv19 App - The KPI flowfield counts in the Setup Card were updated to cues with images. 

- BCv19 App - Small change made to Delivery Docket Report to show full captions in Information Box on Report. 

- BCv19 App - Small typos in the SD Stores Logistics Document Selector report request page were fixed. 

- BCv19 App - Small typos in the SD Stores Logistics Suggest Rates report request page were fixed. 

- BCv19 App - Small typos in the SD Stores Logistics Suggest Zones report request page were fixed. 

- BCv19 App - The option string for Document Type in the SD Stores Logistics Setup Card was changed from Sales Header to Sales Orders and Return Orders, Purchase Header to Purchase Orders and Return Orders, Transfer Header to Outbound Transfer Orders to display to the user the transaction types that this field is applicable to. 

- BCv19 App - A Flowfield count of the Advanced Icon Assignment records was added to the KPI FastTab in the SD Stores Logistics Setup card. 

- BCv19 App - The caption on the Maximum Weight Capacity (Kg) field in the SD Stores Logistics Vehicle Types card page was updated to Maximum Weight Capacity (KG). 

- BCv19 App - The caption on the Maximum Weight Capacity (Kg) field in the SD Stores Logistics Vehicle Types list page was updated to Maximum Weight Capacity (KG). 

- BCv19 App - In the Visual Load Planner the order of the menu groups in the Actions group were changed to match the order on the page menu. 

- BCv19 App - The captions in the Visual Planner factbox that are showing cubage were updated to show (m3) as per other factboxes in SD Stores Logistics. 

- BCv19 App - When a Manifest is Shipped its assigned documents are now removed from the Queued Documents list. 

- BCv19 App - The coordinate fields option on the SD Stores Logistics Setup Card was reduced to Sales, Purchase and Transfer Header. 

- BCv19 App - The code was updated to handle the fact that only Rate Types of Base and Drop are applicable for this version of SD Stores Logistics. 

- BCv19 App - The Release and Ship Action in the Process group of the Load Manifest list were recaptioned to Release Selected and Ship Selected.  

- BCv19 App - The Preview Rates action was missing from the menu group in the Load Manifest list. 

- BCv19 App - A spelling mistake in the SD Logistics Activities Manifest Page was fixed. 

- BCv19 App - Various changes to the text displayed on the Assisted Setup Wizard were made. 

- BCv19 App - The newly added KPI FastTab in the Setup Card was moved to the last FastTab on the card. 

- BCv19 App -  A change was made to the message raised in the Visual Load Planner when locations can not be determined by their address. 

- BCv19 App - A History Activity Panel with Shipped Manifests cues was added to the Role Centre. 

- BCv19 App - The Planner Function Demo action in the Setup Card was removed. 

- BCv19 App - Field captions in the SD Stores Logistics Setup Card were updated. 

- BCv19 App - The ISV Licence Controller validation checks were added to specific areas in the code. 

- BCv19 App - In the Icon Colours FastTab on the Setup Card, the caption on the Un-Assigned Colour field was changed to Unassigned Colour. 

- BCv19 App - The captions of the flowfields in the Visual Planner FactBox were all prefixed with the letter g. 

- BCv19 App - The cubage captions in the Load Manifest FactBox were updated to display as (m3) rather than (m). 

- BCv19 App - Various changes were made to the actions displayed in the action groups on the Queued Documents list. 

- BCv19 App - Some actions were missing from the action menu groups in the Load Manifest list. 

- BCv19 App - In the Load Manifest List the caption of the Pick list action was updated to Pick List. 

- BCv19 App - The caption on the SD Stores Logistics Manifest report was updated. 

- BCv19 App - In the SD Stores Logistics Manifest Report, the caption on the Password field was updated to Note as this field displays the Note from the Driver Table. 

- BCv19 App - The caption on the SD Stores Logistics Load Manifest FactBox was updated. 

- BCv19 App - The report caption on the printed SD Stores Logistics Pick Instruction report was changed. 

- BCv19 App - The Assisted Setup action was modified to call a Wizard to guide users through product setup. 

- BCv19 App -  For ease of setup, a KPI FastTab was added to the Setup Card with flowfields to the Zones, Rates, Vehicles etc. 

- BCv19 App - The order of actions on the Load Manifests Documents FastTab in the Load Manifest Card were changed for ease of use. 

- BCv19 App - A Test Codeunit was created. 

- BCv19 App - An Open Document Action was added to the Load Manifest Card. 

- BCv19 App - Actions in the Rates List were reordered and renamed. 

- BCv19 App - The Suggest group in the Zones List was updated to Suggest Zones. 

- BCv19 App - The Caption on the Suggest Zones Report was updated. 

- BCv19 App - The Co-ordinate Alternatives FastTab in the Setup card was renamed to Coordinate Alternatives. 

- BCv19 App - The Name of the Role Centres were updated using the same conventions as our other existing ISV Products. 

- BCv19 App - SD Stores Logistics was readied for submission to AppSource. 

- BCv19 App - Standard notes and link actions were removed from the SD Stores Logistics pages. 

- BCv19 App - Changes were made to the About Page. The Latest Version of the Product and the AppSource URL were surfaced on the About Page. 

- BCv19 App - Updated Captions for Translations. 

- BCv19 App - Allowed users to search on the SD Logistics Role Centre Activities in the Tell Me. 

- BCv19 App - Assisted Setup was added to SD Stores Logistics. 

- BCv19 App - The Usage Category was added to pages for the Tell Me search. 

- BCv19 App - Permission Sets were created for SD Stores Logistics. 

- BCv19 App - The size of the description and name fields were increased as per the standard D365 BC change. 

- BCv19 App - The ISV About Page was added to the Product. 

- BCv19 App - The existing objects were renamed to ISV standards. 

- BCv19 App - The latest ISV Licence Control was added to the Product. 

- BCv19 App - Existing SD Stores Logistics C/AL objects were converted to AL. 

- BCv19 App - The Activities in the Role Centres were split out into individual pages. 

- BCv19 App - A number of user interface changes were made to the SD Stores Logistics Setup card - a new action called Zones was added to the menu. 

#### Bug Fixes

- BCv19 App - An "Attempted to divide by zero" error was raised when using the Suggest Rates action in a company with no data in sales header table. 

- BCv19 App - The capacity of vehicles were not checked on release of manifests even if Enforce Capacity Planning was switched on. 

- BCv19 App - An issue was fixed where when multiple reports were run in SD Stores Logistics only the last report was printing. 

- BCv19 App - An error was raised when Shipping a Manifest for a Sales Order that had already been partially shipped on another Manifest. 

- BCv19 App - Choosing the Document pack action in the Visual Load Planner did not print any documents. 

- BCv19 App - Fixed an issue where an error was raised when the Pick List report was run from the Queued Document List and the Visual Load Planner. 

- BCv19 App - Fixed an issue where the Rate calculations were unnecessarily looping through all Manifest Documents before the rate was assigned to the Manifest. 

- BCv19 App - When suggesting rates in the Rates list, a record with a service code is created for shipping agents with no assigned service code. 

- BCv29 App - Various issues related to Vehicle and Vehicle Type renaming and deletion were fixed. 

- BCv19 App - Setting a Table in the Coordinate Alternatives of the Setup card but not specifying the Longitude or Latitude fields caused a blank map to display. 

- BCv19 App - Vehicle Compartments for Vehicles could not be created. 

- BCv19 App - In the Visual Load Planner the action group View was renamed to Visual. 

- BCv19 App - Creating a record in the Visual Planner Labels in the Setup Card caused the Visual Load Map Planner to raise a Record not Found message and no Pins were displayed. 

- BCv19 App - An issue was fixed where users could create a Zone record with a blank Zone Code. 

- BCv19 App - Icon Shape and Colour Assignment was not working as expected. 

- BCv19 App - A Pin on the Visual Load Planner was displaying a colour that was not set up in the Icon Colours FastTab in the Setup Card. 

- BCv19 App - Creating a record in the Visual Planner Labels in the Setup Card caused the Visual Load Planner map not to display any pins. 

- BCv19 App - Running the Suggest Rates action in the Rates List created a blank line. 

- BCv19 App - On the Rates list, the Suggest Rates action group contained the Zones action and the Related action group contained the Suggest Rates action. 

- BCv19 App - An issue was fixed where the Suggest Zones action on the Zones list created a line with no Code but with a Country/Region code. 

- BCv19 App - An error is raised on release of a Manifest if a rate does not exist for the Zone Code on the Manifest and the user does not want to create a Purchase Document for the Shipping Agent. 

- BCv19 App - An issue was fixed where SD Stores Logistics was throwing an error when reopening a Blanket Order. 

- BCv19 App - When licence was due to expire within 5 days a call to the licence validator in a TryFunction was raising an error.

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

