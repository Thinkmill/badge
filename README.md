# Thinkmill Badges

"Supported by Thinkmill" badge for READMEs.

![Simple badge](https://thinkmill.github.io/badge/simple.svg) ![Heart badge](https://thinkmill.github.io/badge/heart.svg) ![Rocket badge](https://thinkmill.github.io/badge/rocket.svg) ![Bolt badge](https://thinkmill.github.io/badge/bolt.svg) ![Invader badge](https://thinkmill.github.io/badge/invader.svg)

## Usage

To embed the heart badge in a Github README use this snippet:

```markdown
[![Supported by Thinkmill](https://thinkmill.github.io/badge/heart.svg)](http://thinkmill.com.au/?utm_source=github&utm_medium=badge&utm_campaign=xyz)
```

(Replace the `xyz` in the `utm_campaign` part of the link with your project name)

Which looks like this:

[![Supported by Thinkmill](https://thinkmill.github.io/badge/heart.svg)](http://thinkmill.com.au/?utm_source=github&utm_medium=badge&utm_campaign=xyz)

Alternatively you can embed HTML (a limited subset works on Github in Markdown):

```HTML
<a href="http://thinkmill.com.au/?utm_source=github&utm_medium=badge&utm_campaign=xyz">
	<img alt="Supported by Thinkmill" src="https://thinkmill.github.io/badge/heart.svg" />
</a>
```

### General

The general usage looks like this: `https://thinkmill.github.io/badge/<type>.svg`, where `<type>` is to be replaced with one of:

- `simple`
- `heart`
- `rocket`
- `bolt`
- `invader`


### Best practices

- Link to `http://thinkmill.com.au/?utm_source=github&utm_medium=badge&utm_campaign=xyz` when using these badges, (otherwise people who click on them just see a bigger version) replacing the `xyz` in the `utm_campaign` part of the link with your project name and possibly change the `utm_source` to whatever site you use it on
- Add "Supported by Thinkmill" as the alt text

## License

This repo and all its files are licensed under CC0 and are public domain. See [LICENSE.md](LICENSE.md) for more information.
