# One Piece Webring 🏴‍☠️

> *Inspired by [XXIIVV webring](https://github.com/XXIIVV/webring) & [Psycho Helmet Webring](https://sugarforbrains.neocities.org/mobring/)*

## 📝 Info

This [webring](https://webring.kjelsrud.dev) is tailored for fans of One Piece, aiming to inspire artists & developers within the fandom to create and maintain their own personal websites. The primary goal of the webring is to cultivate a sense of community, enabling members to exchange traffic while exhibiting their personally crafted websites, including personal diaries, wikis, and portfolios.

## 🤝 Join the webring 

1. Add the webring icon to your website.
2. Add your website information to the [index.vue](https://github.com/SindreKjelsrud/onepiece-webring/blob/main/pages/index.vue) file underneath `<!-- LIST -->`. Keep your link name short, and don't leave a trailing `/` in the `href` attribute. For the `id` attribute, use something like a alphanumerical value or your tag.
3. Submit a Pull Request with **the location of the webring icon** on your site. Blank description PRs will be rejected.

### ✅ Webring criteria

- Your website must have atleast 5-6 pages and an about page. (Blog posts are not counted as content pages)
- You must use the webring icon, not other gifs representing it etc.
- Your website will be rejected if one of the following are true:
    - Single page websites, acting as a social media portal.
    - Websites with violent, racist, sexist or speciesist content.
    - Javascript/CSS3 is required to display the ***majority*** of its content or to navigate.

> *Websites without activity for over 2 years might also be periodically removed*

### 🖇 Circular Linking

Instead of linking to the crewmates directory, you can link to a random link in the ring by adding their `id` to your webring icon!

```html
<a href="https://webring.kjelsrud.dev/#id" target="_blank" rel="noopener noreferrer">
  <img src="https://webring.kjelsrud.dev/icon.black.svg" alt="grand line webring"/>
</a>
```
