# Exercise Template Data

Holds an id, and an instruction. May have a `data` object which may hold arbitrary data (object keys must be `str`, value may be anything).

Must hold one reference to a `Generator` and one to an `ExerciseType`.

May have an array `blockedBy`, which is a flat list of other `ExerciseTemplateData`'s ids.