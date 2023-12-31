# plant-collection-website

This project is a website for both desktop and mobile. It should use the [anttijankeri/object-image-server](https://github.com/anttijankeri/object-image-server) backend repo. The site should allow users to create listings of plants with some data. Each plant should be saved into the backend and retrievable later via email/password or Google authentication. The user should be able to filter their plants with any of the text values. They should also be able to fetch a list of the filtered - or all - plant listings as a file. The users should also be able to link a plant listing or image and share it to others if wanted. Finally, the user should be able to delete their data from the server.

The coding language is **Typescript** and the website uses **React**

## SETUP

Rename the .env.example file into .env and change all the variables into the ones you have. You will also need to setup an Auth0 app for React/Single page application and follow their guide to get the service running. The Auth App and API should be under the same domain.

## Plant data to save:

Strings:

- Latin genus name
- Latin species name
- Common name
- Identifying info
- Plant origin/country
- Free-hand note
- Acquired from
- Growing note
- Publication name/link
- Purchase price
- Sale price
- Collection number/tag

Boolean:

- For sale
- Sharing authorization for object

Date:

- Date acquired
- Date first flowered
- Date last flowered
- Date plant removed

Image:

- Image itself (separate file)
- Links to image files
- Sharing status per image

Special:

- Event diary ({string, date}[])
- Watering schedule (unknown)
