# Spring Security Auto-Configuration

When you integrate Spring Security into your project without any specific configuration, Spring Boot’s auto-configuration feature provides a default SecurityFilterChain with the following characteristics:

    1. **Endpoint Protection:** All endpoints are protected, requiring authentication for access.

    2. **Form Login**: A default login page is enabled, facilitating form-based authentication.

    3. **HTTP Basic Authentication:** Basic authentication is supported, allowing access through username and password.

    4. **CSRF Protection:** Cross-Site Request Forgery (CSRF) attacks are mitigated through built-in protection.

    5. **Security Headers:** Additional security headers such as X-Frame-Options and X-Content-Type-Options are added to enhance security.

    6. **Default User:** A default user is created with the username user and a password that is printed to the console.
