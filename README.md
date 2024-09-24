# contral-profile-manager

Spring Boot + Java + Gradle.

The project consists of four parts at the moment. First user profile. Profile must be extendable such that you can have different types of profiles (e.g. TravelProfile, AgentProfile, and ContractorProfile), but they must maintain the same id. Set those up as well. Profile can have many attributes but must have a unique id. The second part is the controllers. You need the ability to create a profile, update a profile and delete a profile. You will need to make a system for profile permissions such that only a person with certain permissions can run those requests. Lastly you will need to setup a system to handle logins, such that a person would need to be logged in to your system to initiate those requests. If you have any questions or require any clarification please let me know here.
Also with profile, they should have familyName, givenName, date of birth, phone number as a starting point. Maybe add frequent flyer number to traveller profile, contractor should have website, hourly rate. We can expand these later :slightly_smiling_face:
