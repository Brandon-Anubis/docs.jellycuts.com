# Writing Your First Script

## Downloading the iOS App

If you have not already, you can get the Jellycuts iOS app from the [App Store](https://apps.apple.com/us/app/jellycuts/id1522625245). After installing, run through the in-app tutorial to connect Jellycuts with Shortcuts and open the **Starter Jellycut** project.

## Let's get started

When you create a new project (or open *Starter Jellycut*) the first thing you will see is an **import statement**. This pulls in the Standard Shortcuts Library at a specific version. The next line is the **metadata definition** which tells Jellycuts details about how the Shortcut should be exported (for example its colour and icon).

```jelly
import Shortcuts
#Color: red, #Icon: shortcuts
```

### Hello World!

Time for a classic 🖐🏻 `Hello World`.

1. Add a *Text* block:

    ```jelly
    text(text: "Hello World!")
    ```

2. Attach a **Magic Variable** so we can reference the output later:

    ```jelly
    text(text: "Hello World!") >> introduction
    ```

3. Display it with an **alert** (showing [String interpolation](../language-guide/strings.md)):

    ```jelly
    alert(alert: "${introduction}")
    ```

Putting it all together you get:

```jelly
import Shortcuts
#Color: red, #Icon: shortcuts

text(text: "Hello World!") >> introduction
alert(alert: "${introduction}")
```

## Next steps

Now that you have written your first Jellycut you can jump straight into creating more, or continue through the docs. A good next read is the [Language Guide](../language-guide/basics.md) where you can learn the fundamentals.