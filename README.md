# One-Day Trip Route Planning

Final project for the Building AI course

## Summary

Sometimes we have a free day that we would like to spend relaxing, enjoying new experiences, and discovering interesting places. However, organizing even a short trip can take a lot of time and effort.

With this application, users can enter a few preferences, such as their starting location, trip duration, budget, and personal interests. Based on these parameters, the system will automatically generate a convenient and personalized one-day travel itinerary.

The goal of this application is to make planning short trips simple, quick, and accessible, helping people make the most of their free time.


## Background

People often want to spend their free days travelling and exploring new places, but planning a one-day trip can be challenging.

Main problems:
* Time-consuming planning: Finding interesting destinations requires a lot of research.
* Route optimization: Choosing the best route between multiple locations can be difficult.
* Time limitations: It is challenging to fit several activities into one day.
* Budget constraints: Finding destinations that match a specific budget is not always easy.
* Lack of personalization: Existing travel guides may not match individual interests and preferences.

## How is it used?

Usage process:
1. The user opens the application and enters their starting location.
2. Selects available time, budget, transportation method, and personal interests.
3. The AI analyzes the preferences and finds suitable destinations.
4. The application generates an optimized one-day travel route.
5. The user reviews the itinerary and follows the suggested route.

When is it needed?
1. During free days, weekends, or holidays.
2. When planning spontaneous trips.
3. When visiting a new city or region.
4. When looking for interesting places nearby.

Target users:
1. Individuals and couples looking for short trips.
2. Families planning weekend activities.
3. Tourists exploring unfamiliar locations.
4. Groups of friends looking for new experiences.

User needs to consider:
1. Available time and budget.
2. Personal interests and preferences.
3. Transportation options and travel distances.
4. Comfortable routes and realistic schedules.
5. Accessibility and family-friendly destinations.


## Data sources and AI methods

The application uses third-party APIs and user-provided information to generate personalized travel itineraries.

| Data                        | Source                                                                                    |
| Maps and locations          | [Google Maps Platform](https://developers.google.com/maps)                                |
| Places and attractions      | [Google Places API](https://developers.google.com/maps/documentation/places/web-service)  |
| Routes and travel distances | [OpenRouteService](https://openrouteservice.org/)                                         |
| Weather information         | [OpenWeather API](https://openweathermap.org/api)                                         |

The application collects the following information directly from users:
- Starting location
- Available travel time
- Budget
- Preferred transportation method
- Personal interests and preferences

Data Processing
External data and user inputs are processed by the AI component to generate personalized travel recommendations and optimized one-day routes.
*Note: The listed APIs are proposed data sources and may be replaced depending on the final implementation.*

## Challenges
Limitations
- Data accuracy: Information about attractions, opening hours, and prices may be outdated or incorrect.
- Real-time changes: The application may not account for unexpected road closures, traffic, or weather changes.
- API limitations: External data providers may have usage limits, costs, or service interruptions.
- AI recommendations: Generated routes may not always be optimal or suitable for every user.
- Limited coverage: Some rural or less popular destinations may have insufficient information.
Ethical Considerations
- Data privacy: Users' personal information and location data must be protected.
- Transparency: Users should understand that AI-generated recommendations may contain inaccuracies.
- Accessibility: Routes should consider people with disabilities and different mobility needs.
- Safety: Recommendations should prioritize safe and publicly accessible destinations.
- Bias: The system should provide diverse recommendations without unfairly prioritizing certain destinations or businesses.

## What next?
Goal: Build a smart travel assistant that makes spontaneous one-day trips easier, more accessible, and enjoyable.
