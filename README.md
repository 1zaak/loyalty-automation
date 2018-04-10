# Beehappy Project Dashboard

> This is the project dashboard for Beehappy. 
> Stakeholders are Araken development team, managers and project client.

## Deployment

> Continuous deployment using [Netlify CDN](https://netlify.com).
> Commits to master will trigger deploy in Netlify.

## Development
``` bash
# Use this to serve in localhost:3000 for development
npm start

# Usually we don't touch this: sends email to stakeholders during Netlify build (see mail-others.js file) 
npm run build
```

## How to Change Stuff
- Everything is in `index.html`
- Remember to change the current date-time on `line 27`
- How to [use](https://frappe.github.io/gantt/) the Gantt chart 

## Libraries
- [MomentJS](https://momentjs.com/)
- [Frappe Gantt](https://github.com/frappe/gantt)