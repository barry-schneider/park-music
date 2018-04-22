# Object Model

## Musician

* MusicianId
* Name
* Email - need to verify
* Phone - need to verify
* LocationId - mailing address
* Instrument[]
* Genre[]

## Band

* BandId
* Name
* Musician[]

## Venue

* VenueId
* Name
* LocationID

## Stage

* StageId
* Name
* Location - need another name as confusing - this is the location within the venue. ie second floor room 202
* VenueId

## Event

* EventId
* Name
* StageId
* Date
* StartTime
* Duration
* BandId
* BandConfirmed

## Regulation

* MusicianId

## InstrumentPrimary

* MusicianId

## InstrumentSecondary

* MusicianId

## Genre

* MusicianId

## Review

* ReviewId
* Review
* BandId

## Social

* SocialId
* YouTube
* Instagram
* Facebook