> Brief Description
> =================
> This use case describes a user adding a book to the library. This is the "ideal
> case" where all metadata fields are filled out with with correct data.
>
> An alternate flow is used to model the case where a duplicate entry is made.
> 
> 
> Actor Brief Descriptions
> ========================
> 
> ## `<actor 1>` -- Gibson
> Gibson is the user of the library system. 
> He accesses the system through the web application by means of a web browser.
> 
> 
> Preconditions
> =============
> 
> `<pre-condition 1>`
> 
> 
> Basic Flow of Events
> ====================
> 
> 1. The use case begins when Gibson, adds a book
> 2. Gibson clicks the “New Book” button
> 3. Gibson fills out all metadata fields
> 4. Gibson clicks the “Save” button, whereby the use case ends
> 
> 
> Alternative Flows
> =================
> 
> ## `<alternative flow 1>`
> 
> If in step 4 of the basic flow the system detects that all metadata fields
> of an existing entry exactly matches those of the entered book.
> 
> 1. The system notifies Gibson that an identical book already exists in the
>    library.
> 
> 2.  The use case resumes at step 3.
> 
> 
> Subflows
> ========
> 
> ## `<subflow 1>`
> 
> 1. `<subflow 1, step 1>`
> 
> 2. `...`
> 
> 3. `<subflow 1, step n>`
> 
> 
> Key Scenarios
> =============
> 
> ## `<scenario 1>`
> 
> 1. `<scenario 1, step 1>`
> 
> 2. `...`
> 
> 3. `<scenario 1, step n>`
> 
> 
> Post-conditions
> ===============
> 
> ## `<post-condition 1>`
> 
> 
> Special Requirements
> ====================
> 
> 1. `<special requirement 1>`
> 
> 
