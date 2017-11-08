<br>
<p align="center">
  <img alt="Croquetas Bar" src="https://github.com/TheCroquetasBar/frontend/blob/master/images/logo.png?raw=true" width="200"/>
</p>
<br>

# The Croquetas Bar

The Croquetas Bar events website, forked from [HackCU Events](https://github.com/HackCU/events)

# Run project

Needs: Ruby

## Local 

1. Clone repository to your computer with `https://github.com/TheCroquetasBar/events.git`
2. `cd events/`
3. `gem install jekyll`
4. `jekyll serve --watch`

## Deploy

1. Activate GitHub pages for repo on master branch
2. Push changes to master
3. There's no `3`

Deployment is done automatically by [GitHub pages](https://pages.github.com/). You don't need to do anything else than pushing to master.

# Personalization

## Add an event

1. Go to [_data/events.yml](_data/events.yml)
2. Copy and paste the following text
```
- name: Twilight Hawkers Market #Event name
  light_background: True # Optional: only put if image-url is set and image is light
  image-url: assets/img/twilighthawkersmarket.png # Optional: only if you want a preview image in the heading
  line: original & biggest Street Food Market bringing the tastiest street food
  date: 2017-10-19 6:00 PM # Optional: When is the event starting
  end-date: 2017-10-19 8:00 PM # Optional: When is the event ending, make sure you set it if date is set
  location: Perth # Optional: Location where the event will be celebrated, set TBD if not sure yet
  url: http://twilighthawkersmarket.com/ # Optional: Url with more info about the event

```
3. Edit the properties as described in the text you just copied

If you need a preview image please add it to [assets/img/](assets/img/). 

## Add/change footer links

You can change footer links by editing the file  [_data/footer_links.yml](_data/footer_links.yml)

## Global variables

You can change various strings across the site, including the title of your app on [_config.yml](_config.yml)

## Theme variables

Main colors can be changed on [_config.yml](_config.yml). For more "deep" styling, you can edit all styling in [assets/css/main.scss](assets/css/main.scss)

# License

MIT © The Croquetas Bar
