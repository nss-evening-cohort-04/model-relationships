class: center, middle

# Model Relationships

---

## Goals

- understand the purpose of models
- how to use a problemset to help build models.
- understand model relationships

---

## Model (Review)

.larger[Representaion of data (entities) and relationships within data]

--

### Roles

- Exposes data as objects and properties usable in code.

--

- Handles connections to database

--

- Determines when reads and writes happen

---

## Model

.larger[Fact: Your problem set drives your models]

--

Think of entities like **objects** (in a database).

--

Rows of a table are analogous to **instances** of an object.

---

## Models Relationships

.larger[Definition: An association between 2 or more enities]

--

.larger[Fact: Model relationships describe the likely behavior of the data]

---

## Model Relationships

### Three types:

--

- One to One

--

- One to Many (same as: Many to One)

--

- Many to Many

---

## Example: One to One

.center.larger[Given the 4 models: **Author**, **Social Security Number(SSN)**, **Published Work** and **Citation Style**]

--

- An Author can only have one SSN

--

- Likewise, a SSN can only be assigned to one Author

---

## Example: One to Many

.center.larger[Given the 4 models: **Author**, **Social Security Number(SSN)**, **Published Work** and **Citation Style**]

--

- A Published Work can only have one Citation Style

--

- However, a **Citation Style** can be used with many Published Works

---


## Example: Many to Many

.center.larger[Given the 4 models: **Author**, **Social Security Number(SSN)**, **Published Work** and **Citation Style**]

--

- An Author can have more than one Published Work

--

- A Published Work can have more than one Author


---

## Example: Github


.center.larger[Discuss the models: **User**, **Repository**, **Wiki** and **Pull Request**]

--

- Does Github keep track of clones in their database?

--



--

- How would we represent a Fork of a **Repository**? Is it an Entity or Association?
