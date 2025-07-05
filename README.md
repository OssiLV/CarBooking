# Car Booking Application

An application that helps employees register for company vehicle use for business purposes.

# Features

- Mobile, PC, and Tablet interfaces (Tablet view follows the PC layout)
- Three user roles: Admin, Employee, and Board of Directors (BOD)
- Register for single-day and multi-day trips
- Book a car on behalf of another user
- Each trip can have one of seven statuses:
  - **PENDING**: Waiting for approval (for overnight multi-day trips)
  - **APPROVED**: Approved by department manager
  - **CONFIRMED**: Car has been assigned by Admin
  - **CANCELED**: Canceled by the requester or the person booking on behalf
  - **REJECTED_BY_APPROVER**: Rejected by the department manager
  - **REJECTED_BY_ADMIN**: Rejected by Admin during car assignment
  - **CLOSED**: Trip has ended
- One approval level for multi-day (overnight) trips
- Calendar view showing both single-day and multi-day trips
- Filter trips that already have cars assigned
- Filter to show available and unavailable cars for Admins during car assignment
- Users can edit trip details after creation
- Users can view a history log including:
  - Approval time
  - Rejection time
  - Creation time
  - Cancellation time
  - Related notes
