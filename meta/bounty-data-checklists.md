
### Bounty Data Update Checklists

## Each Month at the Start of the Round
* [ ] Update the dates.yml file with the next set of round dates. 
* [ ] Review the bounty-faq.md file, make any changes or adjustments necessary.
* [ ] Review the resources.md file, make any changes or adjustments necessary.
* [ ] Review the bounty-proposal-template.md file, make any changes or adjustments necessary.
* [ ] Review the bounty-definition-template.md file, make any changes or adjustments necessary.
* [ ] Review this checklist, and make any changes or adjustments necessary.

## Each Month When Bounty Proposals Are Judged
* [ ] For each successful proposal
  * [ ] Create an entry in the bounty tracking spreadsheet for the bounty. 
    * [ ] Set relevant columns.
  * [ ] Check if proposers have included a definition with their bounty proposals. If so:
    * [ ] Review the definition, checking against the following points, and make any edits or follow-ups required:
      * [ ] Check format matches the template provided.
      * [ ] Check for ambiguity.
      * [ ] Check text is written for bounty-hunter audience.
      * [ ] Check any commitments to work from external parties have been agreed.
      * [ ] Add any dependencies.
    * [ ] Create a markdown file for the bounty when the title is the bounty code.
      * [ ] Use the bounty data template.
      * [ ] Fill in the bounty definition, note that the definition template and data template are not 1:1.
      * [ ] Fill in the data preamble section using the definition contents and general bounty information.
    * [ ] Update the contacts.yml file to include contact information for contacts that have not been previously listed on a bounty. 
  * [ ] If proposers have not included a bounty definition with their proposal. 
    * [ ] Add to a list of undefined proposals.

## On Bounty Work Delivered
* [ ] Update the tracking spreadsheet and set appropriate columns.
* [ ] Is bounty fully completed? If so:
  * [ ] Find the matching bounty data file, and set the external-status to closed.
* [ ] Find the matching bounty data file, and set the external-status to unavailable if appropriate to do so.
  * [ ] Check for exclusivity clauses that make this bounty unavailable to other bounty hunters.
  * [ ] Check if there are new dependencies that need to be met.
* [ ] Mark status changes in the tracking spreadsheet.

## Each Week
* [ ] For each open bounty
  * [ ] If bounty has expired
    * [ ] Mark external-status as unavailable or closed in the bounty data file.
  * [ ] If bounties dependencies are no longer met
    * [ ] Mark external-status as unavailable or closed in the bounty data file.
  * [ ] Mark status changes in the tracking spreadsheet.
* [ ] For each unavailable bounty
  * [ ] Check to see if bounty should be moved to open
    * [ ] Check if dependencies are now met.
    * [ ] Check if there is some other reason this should now be open.
  * [ ] Mark status changes in the tracking spreadsheet.