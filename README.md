# UFO Sightings

# Overview

For this project, we created a website that diplayed information from a data set of UFO sightings. The site contains a brief introduction from the author, but its primary purpose is a set of filters that allow the user to explore the data based on criteria of interest to them.

The UFO sightings data set contained seven fields, five of which were developed into filters:

### Filtered
- Date of sighting
- City
- State
- Country
- Shape of object sighted

### Not filtered
- Duration of sighting
- Comments

# Results

The website may be accessed here: https://brianbutler08.github.io/UFOs/

![](https://github.com/brianbutler08/UFOs/blob/main/images%20for%20READme/website.png)

The page includes a title and introduction, but the primary use is the filterable sightings data towards the bottom.

![](https://github.com/brianbutler08/UFOs/blob/main/images%20for%20READme/filters.png)

The first available filter is for the **date** of the reported UFO sighting. Currently, the database includes sightings from the first half of January 2010. The data must be entered with a one or two digit day and month, and a four digit year, spearated by forward slashes.

![](https://github.com/brianbutler08/UFOs/blob/main/images%20for%20READme/date.png)

The **city** field is case sensitive and currently all city data is lowercase.

![](https://github.com/brianbutler08/UFOs/blob/main/images%20for%20READme/city.png)

Similarly, **state** data is held as the two digit state id, all lowercase.

![](https://github.com/brianbutler08/UFOs/blob/main/images%20for%20READme/state.png)

**Country** codes are also two digit and lowercase. The data set currenly has data from the United States (us) and Canada (ca).

![](https://github.com/brianbutler08/UFOs/blob/main/images%20for%20READme/country.png)

The final filter is based on the **shape** of the UFO was was reported.

![](https://github.com/brianbutler08/UFOs/blob/main/images%20for%20READme/shape.png)

Each filter can of course be used idependently or in conjunction with another number of filters.

![](https://github.com/brianbutler08/UFOs/blob/main/images%20for%20READme/filters.png)

# Summary

Despite the usefulness of the webpage, there is always room for improvement. One major drawback of its current design is that it's perhaps too simple, having all of the elements on a sinlge page where scrolling is required to see every element. As more content is added, this situation will only get more cumbersome. There perhaps should be a main menu near the top with separate tabs for writings, headlines, the sightings data set, and anything that may be added in the future.

A suggested area for development would be a way to inform the user about the type(s) of data included in each field in order to make it easier to search. For example, the 'shape' field contains about a dozen different shapes to search for, but if you had no idea what the options were it would be very difficult to know what you are looking for. Perhaps a dropdown menu to choose from would allow users to see all the available choices.

Additionally, to be properly useful to users, the filters could allow for more than a single choice per field. For example, a user could search for 'circle' AND 'oval' shaped sightings in the same search. Or you could enter a date range, instead of only a single date.
