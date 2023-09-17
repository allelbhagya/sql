# ER Model

## design alternatives for database design

avoiding two major pitfalls:

- redundancy
- incompleteness

## ER Entity Relationship Model

- data model developed to facilitate database logic by allowing specification of enterprise schema to represent overall logical structure of database

### 3 major sections- Entity sets, Relationship sets and Attributes.

### Entity set

an entity is a “thing” or “object” in the real world which is distinguishable from all other objects. person is an entity.

- entity set is a set of entities of same type that share the same properties or attributes.
- entities are represented by a set of attributes, descriptive properties possessed by each member of the entity set
- each entity has a value for each of its attributes

### Relationship sets

- a relationship set is an association among several entities.
- relationship set is a set of relationships of same type

**Descriptive attributes** - descriptive data, attributes that describe the characteristics or properties of an entity

## Attributes

### Simple and composite

- simple - not have been divided into subparts, city, roll number
- composite - can be divided into subparts, address, name

### Single and multi valued attributes

- single - can be only one value, adhar number, roll number
- multivalued - can have multiple values, teachers, phone numbers

### Derived

- attributes which can be derived from other values or other related attributes or entities (age from DOB)

## Constraints

Mapping Cardinalities 

- express the number of entities to which another entity can be associated via a relationship set

— one to one

— one to many 

— many to one 

— many to many  

## Keys

![download](https://github.com/allelbhagya/sql/assets/80905783/0921922b-a117-43d9-ae30-fb054e30618b)


# ER Diagram 

[![d4c90b23560edce50d78838d439880c7](https://github.com/allelbhagya/sql/assets/80905783/e922e1fd-040b-4b1f-9009-f54de7494b7b)
](https://www.professionalqa.com/assets/images/er-diagram-example.png)

## Weak and strong entity

- an entity set that does not have sufficient attributes to form a primary key is termed as a **weak entity set**
- An entity set that has a primary key is termed as **strong entity set**
- the **discriminator** of a weak entity set is a set of attributes that allows this distinction to be made (underlined with dash)
