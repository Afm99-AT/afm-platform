# AFM Database Design v1.0

## Approved Business Rules

- One owner can register multiple tractors.
- One owner can register multiple machines.
- Tractor-mounted implements are linked to a specific tractor.
- Standalone machines are supported.
- One machine per booking.
- Booking includes Tractor + Implement + Operator where applicable.
- Machine-specific pricing only.
- Search priority: Availability, Distance, Verified Owner, Rating, Price.
- First Come, First Serve: The first confirmed booking reserves the tractor and attached implement for the selected date/time. Overlapping bookings for the same equipment are not allowed.
