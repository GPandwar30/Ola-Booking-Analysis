# 🧾 Data Dictionary

## 📁 Bookings Table
| Column Name        | Description |
|-------------------|-------------|
| BookingID         | Unique ID for each ride |
| Date              | Booking date |
| Time              | Booking time |
| CustomerID        | Unique customer identifier |
| DriverID          | Unique driver identifier |
| Status            | Success / Canceled / Driver Not Found |
| BookingValue      | Fare amount for the ride |
| PaymentMode       | Cash / UPI / Wallet / Card |
| VehicleType       | Auto, Mini, Sedan, Prime SUV, Bike |
| PickupLocation    | Customer’s pickup zone |
| DropLocation      | Customer’s destination |

## 📁 Cancellations Table
| Column Name     | Description |
|----------------|-------------|
| CancelID       | Unique cancellation record |
| BookingID      | Associated booking |
| CancelReason   | Reason of cancellation |
| CanceledBy     | Driver / Customer |

## 📁 Ratings Table
| Column | Description |
|--------|-------------|
| RatingID | Unique rating |
| BookingID | Associated ride |
| CustomerRating | Rating given to driver |
| DriverRating | Rating given to customer |
