
Sales Stage
# Sales Stage



```
Beta functionality is not fully tested or completed.
```
Window Type
### Window Type

**Maintain**

```
The Sales Transaction checkbox indicates if this item is a Sales Transaction.
```

Tabs
## Tabs


Sales Stage
### Sales Stage


```
If not selected, the user cannot create a new Record.  This is automatically disabled, if the Tab is Read Only.
```
Fields
## Fields


Client
### Client

**Description**
 *Client/Tenant for this installation.*
**Help**
 *A Client is a company or a legal entity. You cannot share data between Clients. Tenant is a synonym for Client.*

Organization
### Organization

**Description**
 *Organizational entity within client*
**Help**
 *An organization is a unit of your client or legal entity - examples are store, department. You can share data between organizations.*

Active
### Active

**Description**
 *The record is active in the system*
**Help**
 *There are two methods of making records unavailable in the system: One is to delete the record, the other is to de-activate the record. A de-activated record is not available for selection, but available for reports.
There are two reasons for de-activating and not deleting records:
(1) The system requires the record for audit purposes.
(2) The record is referenced by other records. E.g., you cannot delete a Business Partner, if there are invoices for this partner record existing. You de-activate the Business Partner and prevent that this record is used for future entries.*

Search Key
### Search Key

**Description**
 *Search key for the record in the format required - must be unique*
**Help**
 *A search key allows you a fast method of finding a particular record.
If you leave the search key empty, the system automatically creates a numeric number.  The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*

Name
### Name

**Description**
 *Alphanumeric identifier of the entity*
**Help**
 *The name of an entity (record) is used as an default search option in addition to the search key. The name is up to 60 characters in length.*

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*

Probability
### Probability


Closed Status
### Closed Status

**Description**
 *The status is closed*
**Help**
 *This allows to have multiple closed status*

Won
### Won

**Description**
 *The opportunity was won*

Opportunity
### Opportunity


```
The Read Only indicates that this field may only be Read.  It may not be updated.
```
Fields
## Fields


Client
### Client

**Description**
 *Client/Tenant for this installation.*
**Help**
 *A Client is a company or a legal entity. You cannot share data between Clients. Tenant is a synonym for Client.*

Organization
### Organization

**Description**
 *Organizational entity within client*
**Help**
 *An organization is a unit of your client or legal entity - examples are store, department. You can share data between organizations.*

Document No
### Document No

**Description**
 *Document sequence number of the document*
**Help**
 *The document number is usually automatically generated by the system and determined by the document type of the document. If the document is not saved, the preliminary number is displayed in "<>".

If the document type of your document has no automatic document sequence defined, the field is empty if you create a new document. This is for documents which usually have an external number (like vendor invoice).  If you leave the field empty, the system will generate a document number for you. The document sequence used for this fallback number is defined in the "Maintain Sequence" window with the name "DocumentNo_<TableName>", where TableName is the actual name of the table (e.g. C_Order).*

Business Partner
### Business Partner

**Description**
 *Identifies a Business Partner*
**Help**
 *A Business Partner is anyone with whom you transact.  This can include Vendor, Customer, Employee or Salesperson*

User/Contact
### User/Contact

**Description**
 *User within the system - Internal or Business Partner Contact*
**Help**
 *The User identifies a unique user in the system. This could be an internal user or a business partner contact*

Campaign
### Campaign

**Description**
 *Marketing Campaign*
**Help**
 *The Campaign defines a unique marketing program.  Projects can be associated with a pre defined Marketing Campaign.  You can then report based on a specific Campaign.*

Sales Representative
### Sales Representative

**Description**
 *Sales Representative or Company Agent*
**Help**
 *The Sales Representative indicates the Sales Rep for this Region.  Any Sales Rep must be a valid internal user.*

Sales Stage
### Sales Stage

**Description**
 *Stages of the sales process*
**Help**
 *Define what stages your sales process will move through*

Probability
### Probability


Expected Close Date
### Expected Close Date

**Description**
 *Expected Close Date*
**Help**
 *The Expected Close Date indicates the expected last or final date*

Opportunity Amount
### Opportunity Amount

**Description**
 *The estimated value of this opportunity.*

Currency
### Currency

**Description**
 *The Currency for this record*
**Help**
 *Indicates the Currency to be used when processing or reporting on this record*

Description
### Description

**Description**
 *Optional short description of the record*
**Help**
 *A description is limited to 255 characters.*

Comments
### Comments

**Description**
 *Comments or additional information*
**Help**
 *The Comments field allows for free form entry of additional information.*

Close Date
### Close Date

**Description**
 *Close Date*
**Help**
 *The Close Date indicates the last or final date*

Cost
### Cost

**Description**
 *Cost information*
