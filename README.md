# Rust UIs to the Terminal

> Rust is quietly becoming the language of choice for UI work in constrained environments: think fewer dependencies, more control, and UIs that run beautifully in terminals—and now, thanks to no_std, even on embedded devices. My library Ratatui is leading that charge.
>
> Join us to explore how to build terminal UIs, adapt them for embedded hardware, and deploy them. We’ll walk through the full workflow:
>
> - building a TUI on desktop so you can iterate fast,
> - porting to embedded devices using no_std,
> - cross-compilation and deployment to real hardware (yes, demo flashing to ESP32!),
> - and how Ratatui helps make all of this smoother.
>
> If you’re curious about Rust, TUIs, or embedded Rust, this can be a journey you’ll learn from no matter your experience level.

## Presenting

To start the presentation, first install [presenterm](https://github.com/mfontanini/presenterm):

```bash
cargo install presenterm
```

Then simply run:

```bash
presenterm presentation.md -X -c config/presenterm.yml -p
```

> [!IMPORTANT]  
> It is recommended to use [wezterm](https://github.com/wez/wezterm) for good image rendering. The configuration file can be found in [`config/wezterm.lua`](./config/wezterm.lua).

> [!TIP]  
> Run the [`present.sh`](./present.sh) script to present with the recommended tools and configuration.
