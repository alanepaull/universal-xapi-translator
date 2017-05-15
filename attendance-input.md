This is the input file for an attendance event.

Data should be supplied as a UTF-8 Tab Seperated File called attendance.tsv

# attendance
* EVENT_ID [1]
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

# course_instance
* [COURSE_INSTANCE_ID](#course_instance_id) [1] *
* [COURSE_ID](course.md#course_id) [1]
* [START_DATE](#start_date) [0..1]
* [END_DATE](#end_date) [0..1]
* [ACADEMIC_YEAR](#academic_year) [0..1]


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
