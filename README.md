# pefince (personal finance)

## description: personal finance manager android app



Core Features

* User Authentication (Login \& Registration)
* Password Recovery \& Reset
* Email / Account Verification
* User Profile Management
* Income Management
* Expense Management
* Savings Profile Management
* Income \& Expense Analytics Dashboard
* Session Management (Supabase Database)



Functional Requirements

1\. User Roles

&nbsp;   - The system shall implement a single role: User.



2\. Authentication \& Account Management

    - The system shall allow users to register using the following data:

        - Username

        - First Name

        - Last Name

        - Email Address

        - Date of Birth

        - Password

    - The system shall allow users to log in using:

        - Username

        - Password



    - The system shall require email verification after registration by sending a verification link or code to the registered email address.

    - The system shall require account verification after login by sending a verification link or one-time code to the registered email address.

    - The system shall generate an Emergency Code upon successful registration and send it to the user's registered email.

    - The system shall allow users to reset their password via:

        - Email-based reset link or verification code, or

        - Emergency Code authentication mechanism.

    - The system shall allow users to manage and update their personal profile information.



3\. Financial Management

    - The system shall allow users to:

        - Add income records.

        - Add expense records.

    - The system shall allow users to view:

        - A list of income records.

        - A list of expense records.

    - The system shall provide a financial analytics dashboard displaying:

        - Income data represented in green.

        - Expense data represented in red.

    - A visual chart comparing income and expenses.



4\. Savings Management

    - The system shall allow users to:

        - Create savings profiles.

        - View savings profiles.

        - Edit savings profiles.

        - Delete savings profiles.

    - The system shall allow users to allocate a portion of their income to a selected savings profile.



5\. Session Management

    - The system shall manage user sessions using Supabase Authentication.

    - The system shall support creating, retrieving, updating, and deleting session records within the Supabase-managed authentication system.



page:

* home
* detail income and expenses
* add income
* edit income
* add expenses
* edit expenses
* profile
