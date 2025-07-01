# Cyber Cafe Management System - Test Cases

| Test ID     | Module       | Test Description                   | Input                             | Expected Result                        | Status |
|-------------|--------------|------------------------------------|-----------------------------------|-----------------------------------------|--------|
| TC-CC-01    | Login        | Valid login credentials            | Username: `admin`, Password: `admin123` | Redirect to admin dashboard       | ✅     |
| TC-CC-02    | Login        | Invalid login credentials          | Username: `xyz`, Password: `123`  | Show error message                      | ✅     |
| TC-CC-03    | Time Tracker | Start session                      | Start time: 10:00 AM              | Timer starts and session is recorded    | ✅     |
| TC-CC-04    | Time Tracker | End session                        | End time: 11:00 AM                | Session duration saved                  | ✅     |
| TC-CC-05    | Billing      | Generate session bill              | Duration: 1 hour                  | Bill amount calculated and displayed    | ✅     |
| TC-CC-06    | System Admin | Add new system to DB               | System name: `PC-10`              | System added successfully               | ✅     |
| TC-CC-07    | Logout       | Logout                             | Click logout                      | Redirect to login page                  | ✅     |
