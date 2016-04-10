# RealityHack-Challenge-3
RealityHack Challenge #3: Reinvent the Workplace (Estimote + Slack API)

Team Members
-----
- Juan Herrador
- Hugo Peral
- Jose Salazar
- Isra San Jose

# Repository structure
- **ios:** ai{D}FY iOS application
- **cloud/activity-aidifycloud:** ai{D}FY activity management service, store github event data
- **cloud/apigateway-aidifycloud:** Rest api to access ai{D}FY services, offers response caching.
- **cloud/github-aidifycloud:** ai{D}FY GitHub service, retrieve user and organization events from GitHub.
- **cloud/messagebroker:** ai{D}FY light weight message broker for asynchronous communications between services.
- **cloud/pointsservice:** ai{D}FY scoring system, emit pointed activities.
- **cloud/slackservice:** ai{D}FY slack service, send direct messages to the users in Slack when a new activity is processed.
- **cloud/statsmanagement:** ai{D}FY stats management service, store user statistics.
- **cloud/usermanagement-aidifycloud:** ai{D}FY user management service, store github user data.
