# x

## Quick start

1. Install Neva CLI
2. Run `neva run main`
3. Check `neva.yml` for module config

## Usage

Here's how to call the `Println` function from another module:

```neva
import { Println }

func example(start any) (stop any) {
    _, err := Println("Hello, world!")
    if err != nil {
        // handle error
    }
}
```