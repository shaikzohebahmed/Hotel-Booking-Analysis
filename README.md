# Hotel Booking Analysis


![dfrnt-types-oof-hotels](https://user-images.githubusercontent.com/60965420/202893508-65590298-147f-4169-a721-dcba2e38623c.jpg)


**Have you ever wondered when the best time of year to book a hotel room is? Or the optimal length of stay in order to get the best daily rate? What if you wanted to predict whether or not a hotel was likely to receive a disproportionately high number of special requests? This hotel booking dataset can help you explore those questions!**

**This data set contains booking information for a city hotel and a resort hotel and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. All personally identifying information has been removed from the data.**

**Explore and analyze the data to discover important factors that govern the bookings.**

# **Dataset Information**
*   Number of instances: 261337
*   Number of attributes: 32
  
# **Features information:**

**The dataset contains features like:**

* **hotel**: H1 = Resort Hotel, H2 = City Hotel 
* **is_canceled**: If the booking was cancelled(1) or not(0)
* **lead_time**: Number of days that elasped between the entering date of the booking into the PMS and the arrival date
* **arrival_date_year**: Year of arrival date
* **arrival_date_month**: Month of arrival date
* **arrival_date_week_number**: Weekday for arrival date
* **arrival_date_day**: Day of arrival date
* **stays_in_weekend_nights**: Number of weekend nights (sat or sun) the guest stayed or booked to stay at hotel
* **stays_in_week_nights**: Number of week nights (sat or sun) the guest stayed or booked to stay at hotel
* **adults**: Number of adults
* **children**: Number of children
* **babies**: Number of babies
* **meal**: Kind of meal opted for
* **country**: Country code
* **market_segment**: Which segment the customer belongs to
* **distribution_channel**: How the customer accessed the stay-corporate booking/direct/TA.TO
* **is_repeated_guest**: Guest coming for first time or not
* **previous_cancellations**: Was there a cancellation before
* **previous_bookings**: Count of previous bookings
* **reserved_room_type**: Type of room reserved
* **assigned_room_type**: Type of room assigned                   
* **booking_changes**: Count of changes made to booking                      
* **deposit_type**: Deposit type                      
* **agent**: Booking through agent                                            
* **days_in_waiting_list**: Number of days in waiting list                  
* **customer_type**: Type of customer                                              
* **required_car_parking**: If car is required        
* **total_of_special_req**: Number of additional special requirements             
* **reservation_status**: Reservation of status                     
* **reservation_status_date**: Date of specific status

# **Prerequisites**
* **Understanding of Python and its libraries like Numpy, pandas, Matplotlib and seaborn**

# **Technologies used**
* **IDE- Jupyter Notebook**

### **Goal:** **The main objective is to discover important factors that govern the bookings.**

# **Project Workflow**
1. **Importing Libraries**

2. **Loading the Dataset**

3. **Data Cleaning**

4. **Handling Outliers**

5. **Data Visualization**

6. **Conclusion**

# **Conclusion**
* Maximum number of bookings are in the month May to August, so hotels should provide exciting deal to customers to increase their booking in off season. As hotels are getting less repeated customers so management should take customer’s feedback and improve the hotel facilities to increase the count of their repeated guests.

# **Visualizations done on Tableau**
https://public.tableau.com/views/Hotel_Booking_Analysis_16919210151950/Dashboard1?:language=en-US&:display_count=n&:origin=viz_share_link
