# Looking Glass
An unfinished plug-in for [The Sahara Framework](https://github.com/INNVTV/Sahara-Framework) that turns the platform into a searchable customer database that allows for segmentation, profiles and psychological analysis.

**Aggregates multiple services such as:**

[Full Contact](https://www.fullcontact.com)

[pipl](https://pipl.com)

[People Finders](https://www.peoplefinders.com/enterprise)

[Truth Finder](https://www.truthfinder.com/)

[Twitter](https://twitter.com)

[Facebook](https://facebook.com)

[Instagram](https://instagram.com)

[Email Hunter](https://hunter.io/)


Allows for psychological segmentation and analysis.

Profiles include photos, interests, tags, followers, followings, etc...

Search engine allows you to search by tags, interests, text strings, locations, etc...

# Instructions

Plugs into [The Sahara Framework](https://github.com/INNVTV/Sahara-Framework).

**CustomerPlugin.cs** Replaces **Application.Product** logic and services.

Processing happens as a background process.

Segmentation is created using Sahara's **Categorization** system.

Replaces products in Public/Admin Search engine.

Plug-in new services/data as they become available.

Offload data into DataLake for further processing and analysys.

# Refactoring Notes

"Product" can be renamed as "Customer" or other.
