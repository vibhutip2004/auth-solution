
**API Reference**
* `POST /auth/signup`: Create account (No Auth)
* `POST /auth/login`: Authenticate & return JWT (No Auth)
* `POST /auth/logout`: End session (Requires Auth)
* `GET /public/info`: Public data (No Auth)
* `GET /protected/profile`: Private profile data (Requires Auth)

To test authentication, visit `http://localhost:8000/docs`, click the **Authorize** lock icon, and paste your JWT access token.
