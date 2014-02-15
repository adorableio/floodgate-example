# Floodgate Example

## Getting Started

Heroku development suggests the use of foreman.

Ensure you have an `.env` file with the requisite environment variables and that this file is Git ignored.

    # Example
    FLOODGATE_FILTER_TRAFFIC=true
    MAINTENANCE_PAGE_URL=http://adorable.io

Then `foreman start` and the example app will be available at [http://localhost:5000]().
