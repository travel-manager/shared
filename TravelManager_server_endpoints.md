travellers/
- [x] GET one by _id
- [ ] GET all by username
- [x] POST new Traveller
- [x] PUT new data

trips/
- [x] GET one by _id
- [ ] GET all by datestart and dateend and public   // datestart > [datestartparameter] AND dateend < [dateendparameter] AND public == true
- [ ] GET all by lat and long   // lat == [latparameter] AND long == [longparameter]
- [x] POST new Trip	  // returns _id of created trip
- [x] PUT new data
- [x] DELETE one by _id

memberships/
- [x] GET one by travellerId
- [ ] GET all by tripId
- [ ] GET all by travellerId and tripId
- [x] POST new Membership
- [x] DELETE one by _id
- [ ] DELETE all by tripId

notifications/
- [ ] GET all by tripId
- [x] POST new Notification	// server adds timestamp 
- [ ] DELETE all by tripId

markers/
- [x] GET one by _id
- [ ] GET all by tripId
- [x] POST new Marker
- [x] DELETE one by _id
- [ ] DELETE all by tripId

transactions/
- [ ] GET all by payer and tripId
- [ ] GET all by freeloader and tripId
- [x] POST new Transaction	// server adds timestamp
- [x] DELETE one by _id
