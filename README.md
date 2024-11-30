**To start your mongoshell type the following command :**

mongosh

**To create or switch to the Codetribe database type the following command:**

use CodeTribe

**To create the Facilitators collection type the following command:**

db.createCollection('Facilitators')

**To create the Trainees collection type the following command:**

db.createCollection('Trainees')

**To create the Projects collection type the following command:**

db.createCollection('Projects')

**To insert data into the Facilitators collection type the following command:**

db.Facilitators.insertOne({Name:'Kb', Location:'Kimberly', Course:'React-development'})

**To insert data into the Trainees collection type the following command:**

db.Trainees.insertOne({Name:'Lebz', Location:'Kimberly', Facilitator:'Kaybee'})

**To insert data into the Projects collection type the following command:**

db.Projects.insertOne({Name:'React', Course:'App-development', Lesson:'Types of databases'})
