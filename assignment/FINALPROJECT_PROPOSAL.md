# Final Project Proposal

Your assignment this week is to write a detailed proposal for your final
project. In proposing your final, try to address each of the following
areas.

## Problem / Question
How to encourage positive recreational activities for Philadelphia residents using existing assets?

This application will make it easy for Philadelphia residents to find out what is the safest bike route to one of
these asset locations.

## The data
The Parks and Recreation Assets GeoJSON layer includes the following
assets which can be sorted by attribute:
##Assets include: Athletic Fields, Barns, Batting Cages, Boathouses, Community Parks, Concessions\Retail\Cafes, Dugouts, Environmental Education Centers, Farms, Garages\Maintenance\Storage, Gardens, Golf Courses and Ranges, Greenhouses\Nursery, Guard Boxes, Historic Houses, Ice Rinks, Linear Park\Parkways, Lot\Breezeway\Island, Metropolitan Park, Mini Park, Multi-Use Area, Multi-Use Bldg, Museums, Neighborhood Parks, Older Adult Centers, Pavilion\Shelter, Pool, Pumping Station, Recreation Bldg, Recreation Center, Recreation Site, Regional\Watershed Park, Restrooms, Shed, Square\Plaza, Stables, Stage\Stands, Statue\Monument\Sculpture, Watershed\Conservation Park, Weigh Station, Youth & Tot\Play Areas, Zoo Habitat.##

Link found here: https://www.opendataphilly.org/dataset/parks-and-recreation-assets

## Technologies used

turf.js to map radius around the user so they know which assets are within a Range
mapzen: turn-by-turn analysis to route bike routes
leaflet: mapping
jquery: run document.ready functions
bootstrap: formatting

## Design spec

#### User experience

At a high level, how do you expect people to use your application?
- Who are the users? Philadelphia locals and youth
- What do they gain from your application' use? Connections to city assets and
encouragement to stay away from criminal activities.
- Are there any website/application examples in the wild to which you can compare your final?
None as of now, however deeper research will be required.

#### Layouts and visual design

So far, we've built all our applications with a side bar for
representing non-map content and navigation. This is not the only
successful design. Extra content could be displayed in a top bar,
through modals, through side bars on both sides, and any combination of
these as well as a number not mentioned. Try to describe your
application's visual layout. Conceptually (no need for extensive CSS
here), what will this design require?

I will use the same sidebar we've used in class exercises to describe the app, offer filter
options, and user input. I will also use a top bar to highlight additional information (still to be flushed out)

## Anticipated difficulties

I anticipate filtering the data and getting it in a user-input form will be most
difficult. I haven't extensively looked at the asset dataset yet and it may be
more complicated than it appears now. I also anticipate difficulty in combining
different techniques learned in class to function as an individual app.


## Missing pieces
Managing icon-pop-up as a modal to display more information about a location.
