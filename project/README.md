Below are the requirements that you need to use for this project.

- A university has a unique ID, name, address, city, state, country, and URL. A university can have many campuses.
- Each campus has a unique ID, name, address, city, state, country, and URL. A campus can have many colleges.
- Each college has a unique id, name, phone, email, and URL.
- A campus can have many units. Each unit has a unique id within the campus, name, phone, and type (academic or non-academic). An academic unit is associated to a college. A non-academic unit has a job description.
- A college or unit may offer courses. Each course has code, number, credit, and title. Each course is uniquely identified by the code and number together.
- Each user of the system has a unique id, first name, middle initial, last name, email, phone, address, city, state, and country. A user may have several phones.
- A user has to be a faculty, staff, student or a combination. Faculty has a rank. Staff has a position. Student can be undergraduate or graduate.
- A tutor is a user hired by a unit or college and has a pay rate (dollars per hour) and a list of courses to tutor associate with this position. A tutor can tutor in more than one unit and/or college. A unit or college can have many tutors.
- A supervisor is a faculty member assigned to supervise tutors. A supervisor has an office hour for supervising and a special email for contact. Each tutor is supervised by one supervisor. A supervisor can supervise many tutors.
- An on-call is initiated by a faculty to ask a tutor to help in one specific course. The on-call has a unique id, location, date, start time, end time, number of hours, task type (classroom assistant, lab assistant, or exam monitoring), and status (assigned, missed, or attended).
- An appointment is between a tutor and a student and has a unique id, location, date, start time, end time, number of hours, list of courses, and status (requested, canceled, or attended).
- A tutoring session is offered by a unit or college. A tutoring session has a unique id within the unit or college, location, date, start time, end time, list of tutors assigned to the session, list of courses that students could get help for. The assignment of a tutor to a session has a status (assigned, missed, or attended) and number of hours.
- An appointment is only needed for outside of the tutoring session.
 Your task:

Identify the Entities, Attributes and Relationships for the above set of requirements.
For Entities: Identify the strong and weak entities
For attributes: Identify key, multi-valued, composite, and derived attributes.
For relationships: use (min, max) constraints
Create the ER/EER Model Diagram using Dia
