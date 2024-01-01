# textgen

Build an Intranet system for Nairobi City county. The intanet system supports the sharing of informations within th eorganization such as documents, links, news, events. Also the intranet provides the access to various sectors in the organization. Sectors contain employees and their information.

For the structure of the system, there are several webpages. The root webpage would be the organization webpage. It contains information describing the organization, The profile of the head of the org who is the governor. His three topmost assistants profiles. Some news and events. Staff cards containing their info. 

The subsequest webpages are for the sectors which follow the structure of the root webpage but the content is specific to the sector. Where we have the head of the sector.

From the sector webpage one can drill down to the sub sectors webpage to access information specific to the subsector. The structure of the subsector is similar to thr root webpage and the sector webpage.

The navbar provides navigation to the various sectors where there is a dropdown menu to select from. We also have navigation to documents, staffs and staff profile and messages.

We also have a search bar for searching the whole intranet repository. When the user searches, any result matching the search query is presented under its type header.

The system is to be developed using nodejs, express, sequelize for db, multer for file uploading, jwt for auth, webpack for configuration, react for frontend, bootstrap for css, react redux and any relevant tool.

