# Eatable Dashboard

![Screenshot-IndexPage](https://p-vvf5mjm.t4.n0.cdn.getcloudapp.com/items/bLuKKZvz/8dbdd5a3-7a51-480b-a061-33cc4dc8681d.png)

## Getting started

- Project developed with Vite. To get started with this app, simply clone this repository to your local machine and then run the following commands in your CLI:

```
  $ npm install
  $ cd react-eatable
  $ npm run dev
```

## Resources

- Design: [Figma here](https://www.figma.com/file/9iX52juOI5ZghyewK0svxO/Eatable?type=design&node-id=2569-152&t=dKDE0a7UcMRhDhv1-0)
- API endpoint: https://react-eatable-api.herokuapp.com

## Requirements

The product dashboard should accomplish the following:

- It should be built with React reusable components.
- It should connect to an external API to fetch and persist data.
- It should use CSS in JS for the styles using Emotion.
- It should be able to handle page refreshes without losing the current state of the app. (LocalStorage or SessionStorage are both valid).
- It should handle errors by showing useful messages to the user.

# Main user stories

As a user, I want to...

- See a list of all products currently created on the database
- Be able to create a new product using a form (showing the errors if there are any)
- Be able to update a product using a form (showing the errors if there are any)
- Be able to delete a product. A modal should appear on the screen to confirm the deletion.
