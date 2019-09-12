# Notes

## A good data model

- captures ALL the information the system needs
- captures ONLY the information the system needs <== _Abstraction_
- reflects reality (from the point of view of the system)
- is flexible, can evolve with the system
- guarantess data integrity, without sacrificing performance <-- _using constraints_
- is driven by the way we access the data

## Components

- entities (nouns: zoo, animal, species), like a resource --> tables
- properties --> columns or fields.
- relationships --> Foreign Keys

## Workflow

- identify entities 
- identify properties
- identify relationships

## Relationships

- one to one
- one to many
- many to many

## Mantras

- every table must have a Primary Key
- one to many relationship requires a Foreign key
- the Foreign key goes on the many side
- many to many needs a third table
- the third table can have other information
- work on two or three entities at a time
