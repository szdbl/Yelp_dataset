charlotte_business.csv
business_id: id of business
business_city: city of business
business_full_address: full address of business
business_latitude: latitude of business
business_longitude: longitude of business
business_name: name of business
business_review_count: number of reviews of business
business_stars: stars of business (average over users, rounded to 0.5 star)
business_state: state of business (all NC)
business_Take-out: does the business offer take-out? (boolean)
business_Alcohol: does the business sell alcohol (different values)
business_NoiseLevel: noise level of the business
business_Attire: attire level of business
business_Delivery: does the business offer delivery? (boolean)
business_HasTV: does the business have a TV? (boolean)
business_TakesReservations: does the business take reservations? (boolean)
business_WheelchairAccessible: is the business wheelchair accessible? (boolean)
business_WaiterService: does the table have waiter service? (boolean)
business_AcceptsCreditCards: does the business accept credit cards? (boolean)
business_GoodforKids: is the business good for kids? (boolean)
business_GoodForGroups: is the business good for groups? (boolean)
business_PriceRange: price level of business (integer 1-4)
business_categories: list of subcategories of business (e.g. "Sandwiches")

------------
charlotte_reviewer.csv
reviewer_id: id of reviewer
reviewer_average_stars: average stars of reviews given by reviewer
reviewer_fans: number of fans of reviewer
reviewer_name: name of reviewer
reviewer_review_count: number of reviewer written by reviewer
reviewer_yelper_since: year reviewer started being a yelper
reviewer_funny_votes: number of funny votes received by reviewer
reviewer_useful_votes: number of useful votes received by reviewer
reviewer_cool_votes: number of cool votes received by reviewer
reviewer_total_votes: number of total votes (funny + useful + cool) received by reviewer
reviewer_num_friends: number of friends of reviewer
reviewer_years_elite: number of yearse reviewer has been elite
reviewer_currently_elite: is the user currently elite? (1 is yes, 0 is no)
reviewer_num_compliments: number of compliments received by user

------------
charlotte_review.csv
review_date: date of review in 'YYYY-MM-DD' format
review_id: id of review
review_stars: number of stars on review
review_text: text of review
review_funny_votes: number of funny votes received for review
review_useful_votes: number of useful votes received for review
review_cool_votes: number of cool votes received for review
review_total_votes: number of total votes (funny + useful + cool) received for review

------------
charlotte_data_joined.csv
charlotte_review joined with charlotte_business and charlotte_reviewer according to
business_id and reviewer_id