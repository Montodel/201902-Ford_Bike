# 2019-Ford Go Bike Dataset Analysis and Visualization
## by Suleiman Mohamed


## Dataset

> This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area. The dataset contains 183412 entries with 16 columns.

<table>
  <thead>
    <tr>
      <th>Variable Name</th>
      <th>Definition</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>duration_sec</td>
      <td>int64</td>
    </tr>
    <tr>
      <td>start_time</td>
      <td>object</td>
    </tr>
    <tr>
      <td>end_time</td>
      <td>object</td>
    </tr>
    <tr>
      <td>start_station_id</td>
      <td>float64</td>
    </tr>
    <tr>
      <td>start_station_name</td>
      <td>object</td>
    </tr>
    <tr>
      <td>start_station_latitude</td>
      <td>float64</td>
    </tr>
    <tr>
      <td>start_station_longitude</td>
      <td>float64</td>
    </tr>
    <tr>
      <td>end_station_id</td>
      <td>float64</td>
    </tr>
    <tr>
      <td>end_station_name</td>
      <td>object</td>
    </tr>
    <tr>
      <td>end_station_latitude</td>
      <td>float64</td>
    </tr>
    <tr>
      <td>end_station_longitude</td>
      <td>float64</td>
    </tr>
    <tr>
      <td>bike_id</td>
      <td>int64</td>
    </tr>
    <tr>
      <td>user_type</td>
      <td>object</td>
    </tr>
    <tr>
      <td>member_birth_year</td>
      <td>float64</td>
    </tr>
    <tr>
      <td>member_gender</td>
      <td>object</td>
    </tr>
    <tr>
      <td>bike_share_for_all_trip</td>
      <td>object</td>
    </tr>
  </tbody>
</table>

> For better display and distribution, I cleaned up the dataset's characteristics. I altered the datatype of the extracted week, hour, and time from the provided Start time. I adjusted the period from seconds to hours for better visualization. I also removed several values that were missing. I converted the start and end times from objects to timestamps. I added categories for user type, gender, and bike share for all trip. I assigned the objects bike id, start station id, and end station id. I determined the user's age. The dataset now includes a member age group column that categorizes the ages.


## Summary of Findings

> In terms of usage, Subscribers outnumber Customers. The busiest day is Thursday, with peak times at 8 a.m. and 5 p.m. Males ride the most in comparison to the other genders. The majority of users are between the ages of 30 and 40.


## Key Insights for Presentation

> The major goal of my presentation is to create responses to the question, "What gender rides bikes the most?" What is the busiest time of day? Which user type has the most bike rides? What is the busiest day of the week? How does the age distribution of User type ride counts differ?

> We had to change the scale to fit our distribution when analyzing the total number of bike rides for user type with age classes. For the piechart of user type counts, we had set the startangle to 90.