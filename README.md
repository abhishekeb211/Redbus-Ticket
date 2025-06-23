# Redbus-Ticket
Ticket Booking 15 days Prior Prediction of Final Seat Count

## redBus Data Decode Hackathon 2025
The hunt for data champs is here- bigger, bolder, and on the road!
 
Are you ready to solve one of the most complex challenges in the travel industry? The redBus Data Decode - Data Science Hackathon 2025 invites all the Data Scientists, Analysts, and problem-solvers to tackle real-world business scenarios and showcase their analytical skills for a chance to win from a prize pool of ₹5,00,000 and earn interview opportunities with redBus.

## About the Hackathon:
 
In the bus transportation industry, demand forecasting is more than just a pricing tool- it shapes marketing campaigns, discount strategies, SEO initiatives, and much more. The challenge? Less than 20% of bus bookings are made well in advance, leaving limited early signals to accurately predict demand. This makes forecasting highly complex and demands innovative, data-driven solutions.
 
This hackathon aims to forecast the number of travellers for a specific journey date, with a prediction window of 15 days in advance.

# Problem Statement:
 
## Key Factors Influencing Demand:
Demand for bus journeys is influenced by a range of factors, including holiday calendars, wedding seasons, long weekends, school vacations, and exam schedules. Additionally, regional holidays can affect different areas differently, and day-of-week effects further shape booking patterns. However, not all holidays significantly impact demand, making it a complex and non-trivial problem to model.

## The Hackathon Challenge:
In this hackathon, your task is to develop a model that accurately forecasts demand for bus journeys. We will provide historical booking data from our platform, including the following:
	• Seats booked: Historical demand data.
	• Date of journey: The actual travel date.
	• Date of issue: The date when the ticket was booked.
	• Search data: The number of users searching for a particular journey date on a given booking date.
Your goal:
	• Predict the demand (total number of seats booked) for each journey at the route level, 15 days before the actual date of journey (doj).
	• Example: For a route from Source City "A" to Destination City "B" with a date of journey (doj) on 30-Jan-2025, you need to predict the final seat count for this route on 16-Jan-2025, which is exactly 15 days prior to the journey date.

## Evaluation Metric:
 
The evaluation metric for this hackathon would be RMSE (Root Mean Squared Error)
