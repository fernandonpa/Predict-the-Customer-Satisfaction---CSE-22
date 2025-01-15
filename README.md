# **Predict the Customer Satisfaction - CSE 22**

### Dataset Description

#### **Files**

- **train.csv** - The training set, containing both the features and the target variable `customer_experience`. Use this data to train your model.
- **test.csv** - The test set, containing the features only. You will predict the target variable `customer_experience` for this set.
- **sample_submission.csv** - A sample submission file that shows the correct format for submitting your predictions. This file contains `id` and `customer_experience` columns.

# **Predict the Customer Satisfaction - CSE 22**

#### **Dataset**

Below are the descriptions of the columns present in each dataset:

**User Information**

- `user_id` - A unique identifier for each user.
- `age` - The age of the user.
- `Gender` - The gender of the user (e.g., Male, Female, Other).
- `Date_Registered` - The date when the user registered.

**Loyalty Program Info**

- `Is_current_loyalty_program_member` - Whether the user is currently a member of the loyalty program (Yes/No).
- `loyalty_points_redeemed` - The number of loyalty points redeemed by the user.
- `loyalty_tier` - The loyalty tier of the user.
- `Received_tier_discount_percentage` - The percentage of discount the user received based on their loyalty tier.
- `Received_card_discount_percentage` - The percentage of discount the user received from using a loyalty card.
- `Received_coupon_discount_percentage` - The percentage of discount the user
  received from using a coupon.

**Product Information**

- `product_category` - The category of the purchased product (e.g., electronics, office supplies).
- `Product_value` - The displayed price of the product.
  Transaction Details
- `transaction_id` - A unique identifier for each transaction.
- `order_id` - The unique identifier for the order that the transaction is part of.
- `payment_method` - The method of payment used for the transaction.
- `payment_datetime` - The date and time when the payment was made.
- `purchased_datetime` - The date and time when the product was purchased.
- `purchase_medium` - The medium used for the purchase.
- `final_payment` - The final amount paid by the user (after discounts and shipping cost).

**Delivery Information**

- `released_date` - The date when the product was released for shipment.
- `estimated_delivery_date` - The estimated delivery date for the product.
- `received_date` - The actual date when the product was received by the customer.
- `shipping_method` - The method used for shipping (e.g., Standard, Express).
- `tracking_number` - The tracking number assigned to the shipment.

**Target Variable**

- `customer_experience` - The target variable, representing the customer’s experience with the transaction. It can have the following values:
  - `good`
  - `neutral`
  - `bad`
