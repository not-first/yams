---
weight: 120
title: Recommendations
---

# What should YOU do now?

Everything is working now! Yay! 🎉

Here are some cool ways to make your YAMS experience even better in the future:

## Now

### Learn
You want to be in control of your server, and hence you must understand it too. If you are unsure about the role of any application, do some personal research about how it works. I know its a touchy topic within the community, but AI can be quite handy for asking specific questions like this, or explaining how anything within your YAMS compose works! 🙃

Check out the [fundamentals](/docs/fundamentals/docker-and-compose/) of the YAMS website if you haven't already to learn the basics about Docker, Torrenting, and how environment variables and hardlinks work within YAMS.

### Join the community

Join the [YAMS discord](https://discord.gg/Gwae3tNMST) to discuss with likeminded people who might just be getting started too, or ask for help from people years deep! If you enjoy any specific services, make sure to join their communities too.

Not a fan of discord? Fair. You can use the [YAMS forumn](https://forum.yams.media/)!

### Get those apps 📱
Install your media service apps (Emby/Jellyfin/Plex) on all your devices.

Generally they're available for:
- Laptops (Linux, macOS, Windows)
- Phones (Android, iOS)
- TVs (Android, Google, Amazon Fire, Chromecast, Roku, Xbox)
- Home Theater PCs
- Nintendo 3DS ⁉️
- And lots more!

### Quality Profiles
Not all torrents are as good of a watch as others. Radarr and Sonarr both use a system called 'Quality Profiles' where properties of the file are extracted from the file name and used to compare against other releases to identify the highest 'quality' one. You can adjust them to prioritise smaller file sizes, higher video quality, specific video formats, nearly anything! It is very helpful to have these set up nicely to ensure you only use your valuable storage on actually good torrents.

[TRaSH Guides](https://trash-guides.info/) has some great presets you can either setup manually, or use a profile sync tool like [Recyclarr](docs/advanced/custom-containers/#recyclarr-) to do it automatically for you. [Profilarr](docs/advanced/custom-containers/#profilarr-) is another option with a beginner-friendly UI. YAMS has ready-to-go docker compose examples for each at the links above, after which it is up to you and the respective documentation!

## Later

### Add more indexers 🔍
Learn about [torrent trackers](/docs/fundamentals/torrenting-and-vpns/#trackers) (also known as indexers). The more indexers you have, the easier it'll be to find those hard-to-get movies, and the higher chance your Radarr/Sonarr can source a higher quality release. Each tracker has its own community, different rules, and differing requirements of entry (especially private trackers). Finding a popular one with reliable seeding and a wide spread of media can be great for starting out, and might even be all you need.


### Check out new containers
YAMS is just a docker compose file. You can add any containers you like, or even remove them completely!

There are many many projects out there. Check out adding new containers for some common ones, and an example of adapting a brand new one to fit into YAM's


### Make it yours!
Take time to configure and fine-tune all the services. Figure out how they work, tweak settings as you go to fit your requirements. YAMS is just a recommended default, not the objectively best options for everyone's unique situation. The best media server is one that's customized to how YOU want to use it!

