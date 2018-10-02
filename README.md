# kakoune-ember

Helpers for navigating around an Ember project in Kakoune

## Install

Add `ember.kak` to your autoload dir: `~/.config/kak/autoload/`.

## Usage

By default kakoune-ember registers a keymapping in your user mode: 

```
    map global user e ':enter-user-mode<space>ember<ret>' -docstring 'ember commands...'
```

To access it merely enter your user mode, `,` and press `e`.  Should you want to change the key, copy the above line to your kakrc and use a different mapping.
