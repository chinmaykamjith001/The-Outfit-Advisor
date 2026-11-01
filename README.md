# Weather Outfit Advisor

## Project Goal
I often forget to check the weather before picking clothes, and sometimes it rains later in the day. This program takes the times I'll be outside and today's weather, alerts me if bad weather hits during that window, and recommends an outfit (e.g. "Wear a jacket today" or "T-shirt and shorts").

## MVP Scope
- User enters the start and end time they'll be outdoors
- Pull hourly temperature and weather for the day from a weather API
- Check for rain/snow or big temperature changes during the user's time window
- Recommend an outfit using simple, deterministic rules based on temperature and weather
- Alert the user about inclement weather and show the recommended outfit

## Future Plans
- Read the class schedule automatically instead of typing in times
- Let the user set their location instead of a fixed one
- Personalize outfits (e.g. user runs hot/cold, list of clothes they own)
- Send a morning notification instead of having to run the program

## Tech Stack
- Java
- Weather API
