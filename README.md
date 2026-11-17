# Bulls Burger

Online ordering site for Bulls Burger. Pickup only, and customers pay when they order.

- Customers build a burger, then pick sides, dips and a drink. Each item shows its own icon in the cart.
- Orders can only be placed while the restaurant is open. Outside those hours, customers can browse the menu but not check out.
- **Admin panel:** open `#admin` at the end of the address, or use the "Admin" link in the footer. The first PIN is `1234`. The panel has:
  - **Åpningstider:** opening hours for each weekday. Closing after midnight is supported.
  - **Spesielle dager:** holidays and days with different hours.
  - **Inntjening:** revenue, order count, average order, revenue per day, best sellers and the latest orders.
  - **Innstillinger:** pause online ordering, set the time before the first pickup, and change the PIN.

## Test version

Sign-in and payment run in test mode. Settings and orders are saved only in the browser where they were made. For the opening hours to apply to every customer, and for the admin to see all orders, the site needs a database (for example Firebase or Supabase).
