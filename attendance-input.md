This is the input file for an attendance event.

Data should be supplied as a UTF-8 Tab Seperated File called attendance.tsv

# attendance
* [EVENT_ID](#event_id) [1]
* [STUDENT_ID](#student_id) [1]
* [STAFF_ID](#staff_id) [0..1]
* [EVENT_TYPE_ID](#event_type_id) [1]
* [EVENT_TYPE](#event_type) [0..1]
* [EVENT_DESCRIPTION](#event_description) [0..1]
* [EVENT_MAX_COUNT](#event_max_count) [0..1]
* [MOD_INSTANCE_ID](#mod_instance_id) [1]
* [EVENT_START](#event_start) [1]
* [EVENT_END](#event_end) [0..1]
* [EVENT_MANDATORY](#event_mandatory) [0..1]
* [EVENT_ATTENDED](#event_attended) [1]
* [EVENT_LATE](#event_late) [0..1]
* [TIMESTAMP](#timestamp) [1]
* [EVENT_LOGGED_END](#event_logged_end) [0..1]

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


