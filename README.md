# Airbnb-Listings-Bangkok-Analysis

### **Background**
Airbnb, a global online platform facilitating short-term lodging rentals, encompasses diverse accommodation options in numerous cities worldwide, including Bangkok, Thailand. The dataset in focus pertains specifically to Airbnb listings in Bangkok, providing comprehensive details about various accommodations, guest reviews, geographical distribution, and attributes associated with these listings.

### **Problem Statement**
The dataset's objective is to analyze Airbnb Listings in Bangkok to extract insights for improving policies, enhancing host-guest trust, and optimizing the Airbnb experience. By identifying trends, understanding guest preferences, and addressing issues such as inadequate reviews or negative feedback, this analysis aims to guide Airbnb Bangkok in devising better strategies for hosts, renters, and guests. The fundamental question this analysis seeks to answer is:

**"How Do Varied Booking Preferences Unfold Among Travelers on a Airbnb Rental Platform?"**

Understanding user preferences and booking trends is crucial for improving customer experience and optimizing the platform's offerings. Both of these distinctions can assist in tailoring services, refining marketing strategies, and fostering a more conducive environment for both hosts and guests within the Airbnb ecosystem in Bangkok.

### **Data Information**

| **Feature**               | **Description**                                                                             |
|---------------------------|---------------------------------------------------------------------------------------------|
| `id`                      | Unique identifier for the Airbnb listing.                                                    |
| `name`                    | Name of the listing.                                                                        |
| `host_id`                 | Unique identifier for the host/user associated with the listing.                             |
| `host_name`               | Name of the host (usually the first name or names).                                          |
| `neighborhood`            | Geocoded neighborhood using latitude and longitude.                                           |
| `latitude`                | Latitude coordinates of the property using WGS84.                                             |
| `longitude`               | Longitude coordinates of the property using WGS84.                                            |
| `room_type`               | Categorization of the type of room available (e.g., Entire home/apt, Private room, Shared room, Hotel) |
| `price`                   | Daily price in local currency, represented with the $ sign.                                    |
| `minimum_nights`          | The minimum number of nights required for booking the listing.                                 |
| `number_of_reviews`       | Total number of reviews the listing has received.                                             |
| `last_review`             | Date of the last/newest review.                                                              |
| `reviews_per_month`       | The average number of reviews received by the listing per month.                               |
| `calculated_host_listings_count` | The count of listings the host has in the current scrape in the city/region geography.      |
| `availability_365`        | Availability of the listing for x days in the future.                                          |
| `number_of_reviews_ltm`   | The number of reviews the listing has received in the last 12 months.                          |

### Getting Started

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Kyielas/Airbnb-Listings-Bangkok-Analysis.git
   cd Capstone-GymDB

2. **Run the Program**

   ```bash
   python main.ipynb
