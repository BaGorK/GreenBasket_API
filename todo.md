### TODO's

- [] ParseUUIDPipe every uuid param
- [] category resource - add a route to in-activate the category or update the category status on delete category instead of destroying the doc
- [] products table add multiple image for a product instead of one image
- [] change the relation names on the foreign key (categories, cartItems, orders, orderItems)
- [] Add currency if multi-currency support is expected.
- [] on products model Add a slug field for SEO-friendly URLs
- [] update on orders model
  - [] Add shipping_fee, tax, discount, etc.
  - [] Add tracking_number or shipping provider fields.
  - [] Add note field for buyer instructions.
- [] Add analytics tables later (e.g., product views, abandoned carts).
- [] Add a wishlist table for users to save products for later.
- [] Add a reviews table for users to leave feedback on products.

- [] Product Pricing: Consider a currency field for products if you’ll support multiple currencies in the future.
- [] Wishlist Model: Add an active boolean or soft delete for tracking removed wishlists.
- [] Cart Expiry: Add an expiresAt field to Cart for auto-cleanup.
- [] Promo Codes / Discounts: Add a Promotion or Coupon model and a linking table to Order/Cart.
- [] Notification System: Add a Notification model for system/user notifications.
- [] Multi-language/Localization: If global, consider localized fields for product/category names.
- [] Ratings & Reviews: For more analytics, add helpful_votes, reported, etc., to Review.
- [] Data Redundancy for Orders:Store denormalized copies of critical info (like product name/price) in OrderItem to keep order history immutable if product data changes.
