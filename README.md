# Data-Visualization---Dashboards-and-Reports

## Name: Mrunal Kiran
## Hawk ID: mkiran@hawk.iit.edu
## ID: A20580436

## Data Dictionary
The following data dictionary provides descriptions for key tables and calculated measures used in the Airbnb market analysis of Albany, NY. This reference facilitates understanding of the dataset structure, enhancing clarity for data exploration and analysis.

Listings Table

id: Unique identifier for each listing.
name: Name or title of the Airbnb listing.
host_id: Unique identifier of the host.
host_name: Name of the listing host.
neighbourhood_cleansed: Standardized neighborhood name.
room_type: Type of room or property offered (e.g., Entire home/apt, Private room).
latitude: Geographic latitude coordinate.
longitude: Geographic longitude coordinate.

Calendar Table

listing_id: Identifier linking calendar data to listings.
date: Specific date of availability or booking.
available: Availability status (true/false).
price: Listed price per night (numeric).

Reviews Table

id: Unique identifier for each review.
listing_id: Identifier linking reviews to listings.
date: Date when the review was submitted.
reviewer_id: Unique identifier of the reviewer.
reviewer_name: Name of the reviewer.

Calculated Measures

AvgPrice: Average price across listings.
TotalReviews: Total number of reviews received.
ReviewsPerListing: Average number of reviews per individual listing.
TotalListings: Count of unique listings.
ListingsOverTime: Count of distinct listings available over a period.
PeakReviewCount: Highest number of reviews received in any month.
MostActiveMonth: Month with the highest number of reviews.