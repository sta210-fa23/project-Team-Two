# Data

We are sourcing our data set from [a TidyTuesday project](https://github.com/rfordatascience/tidytuesday/blob/master/data/2023/2023-05-23/readme.md) on GitHub. Their data originally came from The [2018 Squirrel Census](https://data.cityofnewyork.us/Environment/2018-Central-Park-Squirrel-Census-Squirrel-Data/vfnx-vebw), a project based on the sightings of squirrels in Central Park, New York City.

## Squirrels Dataset

|variable                                   |class     |description                                |
|:------------------------------------------|:---------|:------------------------------------------|
|X                                          |double    |Longitude coordinate for squirrel sighting point                                          |
|Y                                          |double    |Latitude coordinate for squirrel sighting point                                          |
|Unique Squirrel ID                         |character |Identification tag for each squirrel sightings. The tag is comprised of "Hectare ID" + "Shift" + "Date" + "Hectare Squirrel Number."                        |
|Hectare                                    |character |ID tag, which is derived from the hectare grid used to divide and count the park area. One axis that runs predominantly north-to-south is numerical (1-42), and the axis that runs predominantly east-to-west is roman characters (A-I).                                    |
|Shift                                      |character |Value is either "AM" or "PM," to communicate whether or not the sighting session occurred in the morning or late afternoon.                                      |
|Date                                       |double    |Concatenation of the sighting session day and month.                                       |
|Hectare Squirrel Number                    |double    |Number within the chronological sequence of squirrel sightings for a discrete sighting session.                    |
|Age                                        |character |Value is either "Adult" or "Juvenile."                                        |
|Primary Fur Color                          |character |Primary Fur Color - value is either "Gray," "Cinnamon" or "Black."                          |
|Highlight Fur Color                        |character |Discrete value or string values comprised of "Gray," "Cinnamon" or "Black."                        |
|Combination of Primary and Highlight Color |character |A combination of the previous two columns; this column gives the total permutations of primary and highlight colors observed. |
|Color notes                                |character |Sighters occasionally added commentary on the squirrel fur conditions. These notes are provided here.                                |
|Location                                   |character |Value is either "Ground Plane" or "Above Ground." Sighters were instructed to indicate the location of where the squirrel was when first sighted.                                 |
|Above Ground Sighter Measurement           |character |For squirrel sightings on the ground plane, fields were populated with a value of "FALSE."          |
|Specific Location                          |character |Sighters occasionally added commentary on the squirrel location. These notes are provided here.                         |
|Running                                    |logical   |Squirrel was seen running.                                   |
|Chasing                                    |logical   |Squirrel was seen chasing another squirrel.                                 |
|Climbing                                   |logical   |Squirrel was seen climbing a tree or other environmental landmark.                                  |
|Eating                                     |logical   |Squirrel was seen eating.                                    |
|Foraging                                   |logical   |Squirrel was seen foraging for food.                                  |
|Other Activities                           |character |Other activities squirrels were observed doing.                           |
|Kuks                                       |logical   |Squirrel was heard kukking, a chirpy vocal communication used for a variety of reasons.                                       |
|Quaas                                      |logical   |Squirrel was heard quaaing, an elongated vocal communication which can indicate the presence of a ground predator such as a dog.                                      |
|Moans                                      |logical   |Squirrel was heard moaning, a high-pitched vocal communication which can indicate the presence of an air predator such as a hawk.                                     |
|Tail flags                                 |logical   |Squirrel was seen flagging its tail. Flagging is a whipping motion used to exaggerate squirrel's size and confuse rivals or predators. Looks as if the squirrel is scribbling with tail into the air.                                 |
|Tail twitches                              |logical   |Squirrel was seen twitching its tail. Looks like a wave running through the tail, like a breakdancer doing the arm wave. Often used to communicate interest, curiosity.                              |
|Approaches                                 |logical   |Squirrel was seen approaching human, seeking food.                                 |
|Indifferent                                |logical   |Squirrel was indifferent to human presence.                               |
|Runs from                                  |logical   |Squirrel was seen running from humans, seeing them as a threat.                                 |
|Other Interactions                         |character |Sighter notes on other types of interactions between squirrels and humans.                         |
|Lat/Long                                   |character |Latitude and longitude       
