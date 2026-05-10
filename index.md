---
layout: default
---

# Hi, I'm John.

I'm a senior software engineer at [Spokenote](https://spokenote.com), based in Indianapolis. I build things for the web and occasionally for the physical world.

When I'm not at a keyboard, I'm probably working on something around the house, at the lake in Northern Michigan with my wife, Annie, and our golden retriever, Mabel, or chasing the next interesting rabbit hole.

## Projects

- [Braun BC03 Clock](https://github.com/johnfernkas/bc03-embedded-swift) — Replica of the Braun BC03 wall clock running Embedded Swift on a Waveshare RP2350
- [Leveled](https://github.com/johnfernkas/leveled) — Hardware sensor with custom firmware and a companion macOS app
- [Desktop Plane Tracker](https://github.com/johnfernkas/desktop-plane-tracker) — Live flight tracking on your desktop

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
