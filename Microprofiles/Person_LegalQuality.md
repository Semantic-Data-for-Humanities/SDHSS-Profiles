# Person - Legal Quality

## Questions to answer

- Should we have a sub-class for Nationality? (No to me, but then it must be clear by the user that "Legal Fact" is the one to use for a Nationality)
- Include both the Acquisition and the Fact in the same profile?
- Why sdh-so:P38 has legal connotation type and sdh-so:P39 has type directed to the SAME sdh-so:C22 Legal Quality Type?
- Why sdh-so:C22 Actor's Legal Quality Acquisition Type and not just sdh-so:C22 Legal Quality Acquisition Type?
- Should the relation to which this legal fact is related be an instance of `sdh:C25 Intentional Collective`? Isn't `crm:E74 Group` too limited?

It is necessary to change:

- sdh-so:P38 has legal connotation type -> sdh-so:P38 has legal quality type
- sdh-so:P52 is legal connotation of -> sdh-so:P52 is legal fact of
- Do we need multiple labels for this profile? It seems it would be more suitable to link it to a vocabulary, as there can be many different legal facts

## Description

This profile describes the legal quality of an individual over a given time-span. A legal quality is the fact that a person is perceived by human groups, society, or portions of it as having a legal status that is defined by law or custom, such as Nationality, Work Permit, etc.

## What can be described in this profile

- The Legal Quality, documented with a controlled vocabulary
- The Legal Quality Type, documented with a controlled vocabulary
- The time-span when this legal fact was in action
- The group in which the legal fact is in relation with

## Diagram

![Alt text](<Diagrams/GV_Profile_Person-Legal Quality.drawio.png>)

## Examples

### Example 1

Louis Pasteur (1822, 1895) was born and kept his bern nationality until his death.

### Example 2

With the adoption of the antisemitic and racist Nuremberg Laws on September 15, 1935 in Nazi Germany, the status of the Jews is not anymore a cultural or religious appartenance to beliefs and customs, but a legal status dictated by strict rules. Otto Frank (1889-1980, father of Anne Frrank), who can be documented as being of jewish religious affiliation, can be documented as having the legal status of Jew within the context of Nazi Germany until the repealing of the antisemtic laws in 1945.
