# new-ceylinco-cdm-deployment

Dated publish folders for the Ceylinco CDM admin portal and API.

- `admin_YYYYMMDD_N/` — Vue `dist` (serve on `http://192.168.119.62`)
- `core_YYYYMMDD_N/` — `dotnet publish` output (Kestrel `http://0.0.0.0:5172`)

Put real DB, JWT, SMS, and SMTP values in a server-only `appsettings.Production.json`. Do not commit passwords.
