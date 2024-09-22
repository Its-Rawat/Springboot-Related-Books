# @OneToOne Relationship

`In Hibernate, **One-to-One** mapping refers to the relationship where one entity is related to exactly one other entity. This is typically represented using foreign keys in the database, where one table has a foreign key column referencing the primary key of another table, and each value in that column corresponds to one unique row in the other table.`

-------------------------------------------------------------------------------
##### Lets Understand this Concept with Person and Passport Example.
>Each Person `Entity` has one Passport `Entity`.

>**`@OneToOne`**: This specifies that the relationship between `Person` and `Passport` is one-to-one. That means for every person, there is exactly one associated passport, and vice versa.


### Types of @OneToOne Mapping
1. **Uni-directional One-to-One Mapping**
> In unidirectional `@OneToOne` mapping, only one entity knows about the relationship. The foreign key is present in the table of the owning entity, and only this entity has a reference to the other entity.
> EXAMPLE:  ***https://github.com/Its-Rawat/Hibernate-OneTOne-Uni-Directional-Mapping


2. **Bi-directional One-to-One Mapping**
> 


