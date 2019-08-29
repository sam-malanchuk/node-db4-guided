# Requirements

A client has hired you to track zoo animals.
For each animal, you must track that their name, species, and all zoos in which they have resided (including zoo name and address).

## Solution

Tables: Animals, Species, Zoos

Animals (many) <==> Species (one)

Zoos (many) <==> Animals (many)

### Table Details

Zoos:
- id
- name
- address

Species:
- id
- species_name

Animals:
- id
- name
- species_id

zoo_animals:
- zoo_id
- animal_id

Determine the database tables necessary to track this information.

Label any relationships between table.
