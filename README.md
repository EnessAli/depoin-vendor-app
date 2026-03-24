# depoin-vendor-app

**Depoin Vendor Panel** — A cross-platform Flutter application for marketplace vendors. Enables product management, order tracking, coupon creation, revenue analytics, and customer messaging in a single interface.

> The application code is maintained in a private repository. This repository serves as a public showcase.

## Features

| Module | Description |
|--------|-------------|
| **Dashboard** | Revenue charts, order statistics, and KPI overview |
| **Products** | Full product CRUD with image upload |
| **Orders** | Real-time order status tracking and management |
| **Coupons** | Create and manage discount campaigns |
| **Offers** | Flash deals and special pricing engine |
| **Messaging** | Real-time in-app chat with customers |
| **Notifications** | Push notification management |
| **Revenue** | Detailed earnings analytics and payout history |
| **Profile** | Store and vendor profile management |

## Tech Stack

`Flutter` `Dart` `Riverpod` `GoRouter` `Dio` `REST API`

## Key Dependencies

| Package | Purpose |
|---------|---------|
| `flutter_riverpod` | State management |
| `go_router` | Declarative routing |
| `dio` | HTTP client with interceptors |
| `fl_chart` | Revenue and analytics charts |
| `image_picker` | Product image upload |
| `flutter_secure_storage` | Secure token storage |
| `cached_network_image` | Optimized image loading |
| `connectivity_plus` | Network status detection |

## Architecture

Feature-first folder structure with clean separation of data, domain, and presentation layers per module.

```
lib/
  features/
    auth/
    dashboard/
    products/
    orders/
    coupons/
    offers/
    messages/
    notifications/
    revenue/
    profile/
  config/
  network/
  router/
  theme/
  utils/
```
