---
layout: default
---

# Hi, I'm John.

I'm a senior software engineer at [Spokenote](https://spokenote.com), based in Indianapolis. I build things for the web and occasionally for the physical world.

When I'm not at a keyboard, I'm probably working on something around the house, "up north" in Michigan with my wife, Annie, and our golden retriever, Mabel, or deep in something new entirely.

## Projects

- [Squawk](https://github.com/johnfernkas/squawk) — macOS menubar app that discovers and monitors MCP servers across all your AI coding tools
- [Braun BC03 Clock](https://github.com/johnfernkas/bc03-embedded-swift) — Replica of the Braun BC03 desk clock running Embedded Swift on a Waveshare RP2350
- [Home](https://github.com/johnfernkas/home) — Home Assistant configuration and automations
- [Dotfiles](https://github.com/johnfernkas/dotfiles) — My macOS development environment

{% if site.posts.size > 0 %}
## Writing

<ul>
{% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a><span class="post-date">{{ post.date | date: "%B %Y" }}</span>
  </li>
{% endfor %}
</ul>
{% endif %}
