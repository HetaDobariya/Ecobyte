# Online Food Delivery - Key Project Concepts

## 1. User
- **Context**: Used for login, placing orders, and managing the cart.
- **Information**:
  - Name
  - Email
  - Address
  - Role (User/Admin)

## 2. Menu Item
- **Context**: Display categories.
- **Information**:
  - ID
  - Name
  - Description
  - Image

## 3. Cart
- **Context**: Temporary storage for selected items before checkout.
- **Information**:
  - User ID
  - Items (ID, Quantity)
  - Total Price

## 4. Order
- **Context**: Created after checkout and shown in `orders` page.
- **Information**:
  - Order ID
  - User ID
  - Items
  - Amount
  - Status (Pending, Preparing, Delivered)

## 5. Payment
- **Context**: After checkout, handled in `pay` folder.
- **Information**:
  - Order ID
  - Payment Amount
  - Payment Status

## 6. Product
- **Context**: Used by admin to add/delete food items in `add` or `product` folders.
- **Information**:
  - Name
  - Category
  - Price
  - Stock
  - Image
