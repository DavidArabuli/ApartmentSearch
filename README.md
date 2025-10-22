**Apartment Search WebApp** is a full-stack web app, that helps buyer to search for real estate deals in Riga, Latvia.

**Apartment Search Backend** is a PHP app, which serves all the necessary data for the frontend part of the App and creates API to consume.

- Periodically parses SS.lv RSS feed and extracts data from new ads
- Populates DB (MySQL)
- Creates API endpoints for filtering and selecting necessary data like m2, price, districts etc.
- Has notification system, that automatically monitors new ads and notifies you (via email) when a desired apartment is being sold.
- Manages data for analytics of current market based on gathered ads.
- Creates Analytics API endpoints.

**Apartment Search Frontend** is a client-side part (Typescript\HTML\CSS) of a full-stack web app, that helps buyer to search for deals in Riga, Latvia real estate market.
It allows you:

- To subscribe to notification system, that automatically monitors new ads and notifies you (via email) when a desired apartment is being sold.
- To access a database filled with relevant apartment ads.
- To use all relevant filters, like m2, price, districts etc.
- To access a range of analytics and insights on current real estate\apartment market.

It is deployed as Docker container, on VPS, using Nginx. 
[https://apartmentsearch.devstack.lv/](https://apartmentsearch.devstack.lv/)
