This is the input file for an attendance event.

Data should be supplied as a UTF-8 Tab Seperated File called attendance.tsv

# attendance
* [EVENT_ID](#event_id) [1]
* STUDENT_ID [1]
* STAFF_ID [0..1]
* EVENT_TYPE_ID [1]
* EVENT_TYPE [0..1]
* EVENT_DESCRIPTION [0..1]
* EVENT_MAX_COUNT [0..1]
* MOD_INSTANCE_ID [1]
* EVENT_START [1]
* EVENT_END [0..1]
* EVENT_MANDATORY [0..1]
* EVENT_ATTENDED [1]
* EVENT_LATE [0..1]
* TIMESTAMP [1]
* EVENT_LOGGED_END [0..1]

## EVENT_ID 
### Description

A unique identifier for that event

### Purpose

Analytics - to allow groups of all attendees at an event.

### Derivation
Jisc

### Valid Values
Any

### Format
String (255)

### Notes

## STUDENT_ID 
### Description

The institutions identifier for the student

### Purpose

To link the student to the UDD

### Derivation
Jisc

### Valid Values
Any

### Format
String (255)

### Notes
