# High Level System Design

Entities:
- User
- Car
- Booking

Relations:
User (1) -> (N) Booking  
Car (1) -> (N) Booking  

Booking Flow:
1. User selects car and dates
2. System checks for conflicts
3. If available → create booking
4. Else → reject
