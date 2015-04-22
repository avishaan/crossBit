## High Level Requirements
### Codename: "RhinoBoss"
The following set of requirement describe the currently understood scope of the application. Specific requirements may have a scope that would require its implementation in a future version. Those are called out where applicable. Only v1 is applicable for the first scope. Higher version numbers are there to allow us to know the potential next steps you are planning on taking. This allows us to make design decisions to support your future versions with minimum rework.

| Domain      | Description                                                        | Version | Priority |
| ---         | ---                                                                | ---     | ---      |
| login       | ability for virtual gym member login                               | v1      | high     |
| login       | ability for virtual gym trainer to login                           | v1      | high     |
| login       | user can sign up using email address                               | v1      | high     |
| login       | user can sign up using Facebook                                    | v1      | high     |
| login       | user can sign up using Google+                                     | v1      | high     |
| login       | user can sign up using Instagram                                   | v2      | low      |
| login       | user can sign up using LinkedIn                                    | v2      | low      |
| login       | user can sign up using Twitter                                     | v1      | high     |
| permissions | unique permissions for gym trainer                                 | v1      | high     |
| permissions | unique permissions for gym member                                  | v1      | high     |
| profile     | trainer can fill out a profile                                     | v1      | high     |
| profile     | trainer can import profile from Facebook                           | v1      | low      |
| profile     | trainer can import profile from LinkedIn                           | v1      | low      |
| profile     | trainer can attach images to profile                               | v1      | high     |
| profile     | trainer can include link Facebook account                          | v1      | high     |
| profile     | trainer can include link Instagram account                         | v1      | high     |
| profile     | trainer can include link to YouTube account                        | v1      | high     |
| profile     | trainer can fill out free form text field about themselves         | v1      | high     |
| contact     | member can contact trainer for session                             | v1      | high     |
| contact     | member can initiate contact to trainer for session                 | v1      | high     |
| contact     | member can not initiate contact to trainer for session             | v1      | high     |
| video       | trainer can add YouTube video recording they have made using url   | v1      | high     |
| video       | trainer can specify muscle group tags for video                    | v1      | low      |
| video       | trainer can specify calories for video                             | v1      | low      |
| video       | trainer can specify exercise type                                  | v1      | high     |
| video       | member can search for video based on muscle group                  | v1      | low      |
| video       | member can search for video based on calories                      | v1      | low      |
| video       | member can search for video based on exercise type                 | v1      | high     |
| video       | member can rate video quaity                                       | v1      | high     |
| video       | member can specify issue with video when rating is under threshold | v1      | low      |
| video       | member can search for video based on time uploaded                 | v1      | high     |
| video       | member can search for video based on workout time                  | v1      | low      |
| video       | member can share video on Facebook                                 | v1      | low      |
| tracking    | track users through pages                                          | v1      | high     |
| tracking    | perform automatic analytics of users on pages                      | v1      | low      |
| tracking    | review data of users through pages (basic analytics)               | v1      | high     |
| site-wide   | responsive design                                                  | v1      | high     |
| site-wide   | breakpoint based design allowing layout changes                    | v1      | high     |
| site-wide   | nested design                                                      | v2      | high     |
| site-wide   | desktop/mobile first????????????????????                           | v1      | high     |
| site-wide   | vector based images                                                | v1      | low      |
| referral    | generate referral code for all users                               | v1      | high     |
| referral    | track referral code for user sign up                               | v1      | high     |
| referral    | analytics on referral code                                         | v2      | high     |
| referral    | raw data on referral code                                          | v1      | high     |
| referral    | allow user to customize referral code                              | v2      | low      |
| referral    | referral code field during sign up                                 | v1      | high     |
| referral    | referral code automatically redirects to sign up and auto fill     | v2      | low      |
| qr code     | scanned qr code takes user to video page                           | v1      | high     |
| qr code     | scanned qr code requires logged in user                            | v1      | low      |
| qr code     | allow site to scan qr code                                         | v1      | low      |
| payment     | accept reoccurring payment                                         | v1      | high     |
| payment     | require payment by user                                            | v1      | high     |
| payment     | accept PayPal as payment method                                    | v1      | low      |
| payment     | accept visa/mastercard as payment method                           | v1      | high     |
| payment     | accept american express as payment method                          | v1      | high     |
| payment     | accept bitcoin as payment method                                   | v2      | low      |
| payment     | accept Amazon as payment method                                    | v2      | high     |
| 



| Check Red Flags    | Ability to check red flags via question check                               | v1      | High     |
| Check Red Flags    | Red flags saved locally for offline use                                     | v1      | High     |
| Patient Screening  | Ability to check patient info questions                                     | v1      | High     |
| Patient Screening  | Ability to perform probability analysis based on questions                  | v1      | High     |
| Patient Screening  | Actively inform app user of possible victim status                          | v1      | High     |
| Patient Screening  | Customize screening questions from dashboard                                | v2      | Medium   |
| Patient Screening  | Save patient info answers to database for future retrieval                  | v1      | Medium   |
| Patient Screening  | Save GPS location with answers to database for future retrieval             | v1      | Medium   |
| Patient Screening  | Allow exporting of data into excel for analysis via integration             | v1      | Low      |
| Triage             | Protocols for addressing situation when positive analysis is encountered    | v1      | High     |
| Triage             | Resource list for helping victim when positive analysis is encountered      | v1      | High     |
| Triage             | Protocols based on location                                                 | v2      | Medium   |
| Triage             | Resource list based on location                                             | v2      | Medium   |
| Meta-data          | Analytics on app usage                                                      | v1      | Low      |
| Integration        | Integrate screening tool info from EMR                                      | v2      | Medium   |
| Integration        | Generic integration hook to send data to analytics vendor                   | v2      | High     |
| Push Notification  | Send push notification to user for alerts                                   | v1      | Medium   |
| Call Hotline       | Automatically call hotline number when button clicked                       | v1      | High     |
| Call Hotline       | Call hotline number based on regional location from GPS                     | v2      | High     |
| Text Hotline       | Text hotline service when button is clicked                                 | v1      | Medium   |
| Call 911           | Call 911 button which user has to confirm action to prevent accidental push | v1      | High     |
| Polaris Conection  | Direct user to online National Human Trafficking Referral Directory         | v1      | Medium   |
| Polaris Connection | Integrate call button to dial regional number via GPS location              | v2      | Medium   |


### Legend

#### Domain:
The high level component of the app which the requirement is related to.

#### Description:
The detailed description of the requirement for the app in the specified domain.

#### Version:
The version of the app the requirement would be present in. V1 represents the initial version from the high level scope. V2 might describe
a few months later after discussing a scope change or amendment.

#### Priority:
The relative importance of the requirement to the app as a whole.

#### Examples:
A requirement with v1 low priority means it would be implemented in v1 (typically mvp) but would have a low importance. This could be used when a requirement would be present in the mvp but it is more of a nice to have vs an absolute necessity.
A requirements with v3 high priority means it would be implemented in v3 but would be very important. This could be used when a requirement would be present in the 3rd version but would be extremely important that it is implemented. This can be for features only necessary when an app has more users or in a more mature state.

#### Meeting on Skype
- Remove clickable prototype
