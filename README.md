# assignmnent_viking_analytics

Morgan and Mike

1. User.find_by_sql "SELECT users.id,username FROM users JOIN states ON (users.state_id = states.id) WHERE states.name = 'California'"

2. Airport.find_by_sql "SELECT long_name FROM airports JOIN states ON (airports.state_id = states.id) WHERE states.name = 'Minnesota'"

3. Itinerary.find_by_sql "SELECT payment_method FROM itineraries JOIN users ON (users.id = itineraries.user_id) WHERE users.email = 'heidenreich_kara@kunde.net'"