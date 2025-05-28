# Port-Hugo (A simple portfolio)

currently tested with hugo v0.141.0

This theme is a simple, customizable portfolio for designers or web developers.

![Thumbnail](https://raw.githubusercontent.com/tylersayshi/port-hugo/master/images/tn.png)

![Screenshot](https://raw.githubusercontent.com/tylersayshi/port-hugo/master/images/screenshot.png)

## Features

- Responsive portfolio
- Easy sections to use
- Hugo image processing for optimization
- PostCSS for autoprefixing
- SCSS for easy styling
- [Port Hugo](https://github.com/tylersayshi/port-hugo) based theme

## Install theme on your hugo site

```
hugo new site your-site-name # if you already have a site ignore this line and the next
cd your-site-name
cd themes
git clone https://github.com/tylersayshi/port-hugo.git
cd port-hugo
pnpm install # or yarn, npm, bun, etc.
```

Once you have done this, you may use the `exampleSite` folder as an example for how to set your project up. The two main things to pay attention to is to first set this in your `config.toml` file:

```toml
theme = "yanka-hugo"
```

Then you will need to replicate the data used in the `exampleSite/data/content.yaml` file to fill in the fields for your portfolio. Please also see the `exampleSite/config.toml` for guidance on setting up the more general site configurations.

### Logo support

Images named `logo.svg` and `logo-dark.svg` are meant to be used for the logos. They should be stored in `static/images` as seen in [./exampleSite/static/images](./exampleSite/static/images). If you wish to change this, the code to control the images is in `assets/js/script.js`.

## Credits

I'd like to express gratitude to [Tyler Sayshi](https://github.com/tylersayshi) for creating the Port Hugo theme that I have used as a jumping off point. The theme may look similar to Port Hugo, however I have simplified the design of some sections while enhancing the organisation of the SCSS files for easier maintenance. 

## Contributing

Please feel free to post issues or make pull requests at any time. I am always open to collaboration.
