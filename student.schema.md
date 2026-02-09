db.createCollection("student", {
  validator: {
    $jsonSchema: {
      bsonType: "object",
      required: ["name", "age", "course", "gender"],

      properties: {
        name: {
          bsonType: "string",
          description: "name must be a string and is required"
        },

        age: {
          bsonType: "int",
          minimum: 18,
          maximum: 60,
          description: "age must be between 18 and 60"
        },

        course: {
          bsonType: "string",
          enum: ["BA", "MA", "BCA", "MCA", "BBA", "MBA"],
          description: "invalid course value"
        },

        marks: {
          bsonType: "int",
          minimum: 0,
          maximum: 100,
          description: "marks must be between 0 and 100"
        },

        address: {
          bsonType: "object",
          required: ["city"],
          properties: {
            city: {
              bsonType: "string",
              description: "city is required"
            },
            country: {
              bsonType: "string",
              description: "country must be string"
            }
          }
        },

        gender: {
          bsonType: "string",
          enum: ["male", "female"],
          description: "gender must be male or female"
        }
      }
    }
  }
});
